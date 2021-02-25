# tesla_clone

- [Vadim Savin - Build your first App in React Native in under 2 hours [Tutorial for beginners]](https://www.youtube.com/watch?v=iQ_0Fd_N3Mk)

## What will you learn?

- Setting up a project
- Rendering Components(Texts, Views, Images)
- Creating Custom Components
- Using Props
- Rendering Scrollable Lists

## init

- [Expo CLI](https://docs.expo.io/)
- install Expo CLI and Initialise the expo project

```
> npm install -g expo-cli
> expo --version
> expo init TeslaClone
> cd TeslaClone
> yarn start
```

## Car Item Component

- 1. Render the text(Model, etc)
- 2. Render the Background Image
- 3. Create a separate component for CarItem

## Button Component

- 1. Create a separate component
- 2. Receive props
- 3. Style The button based on 'type' prop

## Finish Car Item Component

- 1. Use Buttons
- 2. Implement props

## Render a scrollable list of Cars

- 1. Use the dummy data
- 2. Render the FlatList
- 3. Setup Snap to view

## Render the header of the app

## error

- [Expo] 앱 실행시 Network response timed out 오류 발생 시
  - [solve](https://answers.microsoft.com/en-us/windows/forum/windows_10-networking/adapter-priority-setting-unavailable-in-windows-10/d2b63caa-e77c-4b46-88b5-eeeaee00c306)
  - 1. Goto Control Panel > Network and Internet > Network Connections
  - 2. Right click the desired connection (Higher Priority Connection)
  - 3. Click Properties > Internet Protocol Version 4
  - 4. Click Properties > Advanced
  - 5. Uncheck 'Automatic Metric'
  - 6. Enter 10 in 'Interface Metric'
  - 7. Click OK
  - Repeat for the Lower Priority Connection, but this time put 20 into the 'Interface Metric'
