// ============================================
// DAY 1 - JavaScript Introduction Notes
// ============================================

// ---- WHAT IS JAVASCRIPT ----
// - Created to "make web pages alive"
// - Scripts run directly, no compilation needed
//   (unlike C where you manually compile)
// - Originally browser-only, now runs everywhere

// ---- JAVASCRIPT ENGINE ----
// - Engine = built-in compiler inside browser
// - It reads → compiles → runs your code
//   (same 3 steps as C, just automatic)
// - V8 = engine in Chrome and Edge
// - SpiderMonkey = engine in Firefox
// - Node.js also uses V8 (same as Chrome)

// ---- JAVASCRIPT vs C ----
// C:you compile manually → runs on OS
// JS browser: engine compiles auto → runs in browser
// JS Node.js: engine compiles auto → runs on your computer
// Same concept, different environment

// ---- WHERE JAVASCRIPT RUNS ----
// 1. Browser  → frontend (what users see)
// 2. Node.js  → backend (server, files, database)
// In VS Code we use Node.js to run JS
// command: node filename.js

// ---- WHAT JS CAN DO IN BROWSER ----
// - Change HTML and CSS on the fly
// - React to clicks, keypresses, mouse moves
// - Send/receive data from servers (AJAX)
// - Store data locally (localStorage)

// ---- WHAT JS CANNOT DO IN BROWSER ----
// - Cannot read/write files on your computer
//   (unlike C which can fopen() any file)
// - Cannot access other websites' data
//   (Same Origin Policy - each site is isolated)
// - Cannot access camera/mic without permission
// NOTE: Node.js CAN do all these things
//       because it runs on OS, not in browser

// ---- SAME ORIGIN POLICY ----
// gmail.com JS cannot read facebook.com data
// even if both tabs are open
// Browser isolates each website from others
// Think: OS isolates each program's memory in C

// ---- NODE.JS ----
// - Takes JS outside the browser
// - Runs on your computer like a C program
// - CAN access files, network, database
// - Used for backend servers
// - Our LocalLens server.ts ran on Node.js
// - Same V8 engine as Chrome

// ---- CONSOLE.LOG = PRINTF ----
// In C:   printf("hello");
// In JS:  console.log("hello");
// Use it to debug and check variable values

// ---- DEVELOPER CONSOLE ----
// Press F12 in browser → Console tab
// This is where JS errors appear
// Hidden from users, visible to developers
// Like your terminal in C but for browser JS
// console.log() output appears here too

// ---- VS CODE = IDE ----
// IDE = Integrated Development Environment
// Has: autocomplete, Git, terminal, 
//      error detection, file navigation
// VS Code ≠ Visual Studio (completely different)
// VS Code = free, cross platform, use this 
// Visual Studio = paid, Windows only, for .NET

// ---- LANGUAGES THAT COMPILE TO JS ----
// TypeScript = JS with strict types (like C)
//              int x = 5 → must declare type
// CoffeeScript = shorter JS syntax
// These convert TO JavaScript before running
// Learn JS first, then TypeScript later

// ---- JAVASCRIPT IS UNIQUE BECAUSE ----
// 1. Full integration with HTML and CSS
// 2. Simple things done simply  
// 3. Supported by ALL browsers by default
// No other language has all three together

// ---- KEY TERMS TO REMEMBER ----
// Script     = your JS code file (.js)
// Engine     = built-in compiler in browser
// Parse      = engine reading your code
// Compile    = converting to machine code
// Node.js    = JS runtime outside browser
// AJAX       = JS talking to server silently
// ECMAScript = official JS rulebook
// Transpile  = convert one language to JS
// V8         = Google's JS engine (Chrome+Node)
// Console    = developer tool to see errors

