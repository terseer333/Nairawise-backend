# Nairawise-backend
import express, { type Request, Response, NextFunction } from "express";


// Categories endpoint
app.get("/api/categories", async (req, res) => {

{
  "name": "nairawise-backend",
  "version": "1.0.0",
  "description": "Backend server for the NairaWise budget tracker",
  "main": "dist/index.js",
  "scripts": {
    "build": "tsc",
    "start": "node dist/index.js",
    "dev": "ts-node server/index.ts"
  },
  "dependencies": {
    "express": "^5.1.0"
  },
  "devDependencies": {
    "typescript": "^5.9.2",
    "ts-node": "^10.9.2",
    "@types/express": "^5.0.3",
    "@types/node": "^18.16.19"
  },
  "author": "",
  "license": "MIT"
}

{
  "compilerOptions": {
    "target": "ES2020",
    "module": "commonjs",
    "outDir": "dist",
    "rootDir": "server",
    "strict": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "forceConsistentCasingInFileNames": true,
    "moduleResolution": "node"
  },
  "include": ["server/**/*"]
}
