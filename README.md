# Android iPhone Emulator

Prototype for controlling a remote Android device from an iPhone browser.

Architecture: iPhone Safari -> WebSocket gateway -> ADB -> Android runtime.

## Phase 1
Mobile controller UI plus Node.js ADB gateway. Android runs remotely; this is not yet a local iOS emulator.

## Run
1. Install Node.js 20+ and Android platform-tools (ADB).
2. Run `npm install`.
3. Run `npm start`.
4. Open `http://localhost:3000`.
