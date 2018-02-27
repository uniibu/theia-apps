## theia-electron

The electron-based Theia application with TypeScript and Java support.

### Build
```
yarn
```

### Package the application for the host environment
```
yarn package
```

### Create a preview application (without packaging it) for the host environment
```
yarn package:preview
```

### Package the application for all supported environments
```
yarn package:all
```

### Troubleshooting

 - [_"Don't expect that you can build app for all platforms on one platform."_](https://www.electron.build/multi-platform-build)
 - If you want to build a Windows version on UNIX, you can use the [`theia-electron-builder`](https://hub.docker.com/r/theiaide/theia-electron-builder/) Docker image. It comes with `wine`.