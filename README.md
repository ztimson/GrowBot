<!-- Header -->
<div id="top" align="center">
  <br />

  <!-- Logo -->
  <img src="https://git.zakscode.com/repo-avatars/02c3c82a2c192095fa04a6ea4d92d9614d37ab508fc948938b37a9cfd3196734" alt="Logo" width="200" height="200">

  <!-- Title -->
### GrowBot

  <!-- Description -->
Plant Manager

  <!-- Repo badges -->
[![Version](https://img.shields.io/badge/dynamic/json.svg?label=Version&style=for-the-badge&url=https://git.zakscode.com/api/v1/repos/ztimson/GrowBot/tags&query=$[0].name)](https://git.zakscode.com/ztimson/GrowBot/tags)
[![Pull Requests](https://img.shields.io/badge/dynamic/json.svg?label=Pull%20Requests&style=for-the-badge&url=https://git.zakscode.com/api/v1/repos/ztimson/GrowBot&query=open_pr_counter)](https://git.zakscode.com/ztimson/GrowBot/pulls)

</div>

## Table of Contents
- [GrowBot](#top)
    - [About](#about)
        - [Built With](#built-with)
    - [Setup](#setup)
        - [Development](#development)
    - [License](#license)

## About
GrowBot is a service intented to monitor & aid in the growing plants. It is meant to run on a [Raspberry Pi](https://www.raspberrypi.com/) with a camera & electronics to automatewater pumps & lights.

By creating grow profiles the amount of water & light can plants recieve can also be adjusted to ensure consistant results. Aditionally you can take notes at anytime which will automatically include images & a record of tempatures, air & soil humidity.

### Built With
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular)](https://angular.io/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![Node](https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org/)

## Setup

<details>
<summary>
  <h3 id="development" style="display: inline">
    Development
  </h3>
</summary>

#### Prerequisites
- [CMake](https://cmake.org/download/)
- [Node.js](https://nodejs.org/en/download)

#### Instructions
1. Install the build tools: `npm install -g node-gyp windows-build-tools`
2. Install dependencies:
    1. Client: `cd client && npm install`
    2. Server: `cd ../server && npm install` 
3. Start the Node server: `npm run start`
4. Start the Angular client: `cd client && npm run start`
5. Open http://localhost:4200

</details>

## License
Copyright © 2023 Zakary Timson | All Rights Reserved | Available under MIT Licensing

See the [license](./LICENSE) for more information.
