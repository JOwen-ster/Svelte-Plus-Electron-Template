# electron-svelte-ts

## EDIT electron-builder.yml FOR YOUR PREFERRED INSTALLER SETTINGS BEFORE PACKAGING

## Using Template
![image](https://github.com/user-attachments/assets/f6fcd53a-976f-4d51-b234-c35ead67044f)

### Install Dev Dependancies
```bash
npm i
```

### Live Dev Server
```bash
npm run dev
```

### Building -> Packaging
```bash
npm run build
```

### Packaging
```bash
npx electron-builder --win
```

```bash
npx electron-builder --mac
```

```bash
npx electron-builder --linux
```

## Creating App From Scratch Using Electron-Vite
```bash
npm i electron-vite -D
```

```bash
npm create @quick-start/electron@latest
```

```bash
cd electron-app
```

```bash
npm i
```

```bash
npm run build
```

```bash
npx electron-builder --win
```

```bash
npx electron-builder --mac
```

```bash
npx electron-builder --linux
```
