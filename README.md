# Multiplayer Sequence Dice Game

## Repo structure
- AndroidClient/ — Android app
- JavaServer/ — Java TCP server

## How to run server
1. Open terminal in JavaServer/
2. Compile: `javac *.java`
3. Run: `java GameServer`

## How to run Android client
1. Open AndroidClient in Android Studio
2. Run on device/emulator
3. Connect to server via IP/port

## Features
- Multiplayer online gameplay
- TCP/IP networking
- BlockingQueue for server message handling
- Threaded server for multiple clients
