# 📜 scroll-list
## Scroll ToDo list. It used MUD framework for ambitious Ethereum applications. It compresses the complexity of building EVM apps with a tightly integrated software stack.
---
## 📝 MUD comes with:
- Store: An [onchain database](https://v2.mud.dev/store)
- World: An [entry-point framework](https://v2.mud.dev/world) that brings standardized access-control, upgrades, and modules.
- Blazing fast development tools based on [Foundry](https://github.com/foundry-rs/foundry).
- Client-side data-stores that magically reflect onchain state.
- MODE: [A Postgres database](https://v2.mud.dev/mode) you can query with SQL that reflects your onchain state 1 to 1.
---
### 🏗️ Local development setup

!!!
The following steps are only necessary if you want to contribute to MUD. To use MUD in your project, install the [packages](#packages) from npm or [set up a new project with the MUD cli](#quickstart).
!!!

1. Install go (required to build [packages/services](packages/services/)): [https://go.dev/doc/install](https://go.dev/doc/install)

2. Install protobuf (required to build [packages/services](packages/services/)): [https://grpc.io/docs/protoc-installation/](https://grpc.io/docs/protoc-installation/)

3. Install the foundry toolkit (required to build and test MUD solidity packages): [https://getfoundry.sh/](https://getfoundry.sh/)

4. Install pnpm

```bash
npm install pnpm --global
```

5. Clone the MUD monorepo

```
git clone https://github.com/bild96/scroll-list.git
```

6. Install MUD dependencies and setup local environment

```
cd scroll-list && pnpm install
```
7. 💡 Run the app
```
pnpm run dev
```
## 🤳 Screenshots <a name = "screenshots"></a>
![Screenshot from 2023-05-22 22-52-12](https://github.com/Bild96/scroll-list/assets/52472445/1f055b92-07cb-43e8-8339-71a4757a8d5a)

## ⛏️ Built With <a name = "MUD"></a>
<img alt="Typescript" src="https://img.shields.io/badge/Typescript-%231572B6.svg?&style=for-the-badge&logo=typescript&logoColor=white"/><img alt="HTML" src="https://img.shields.io/badge/html-%23E34F26.svg?&style=for-the-badge&logo=html&logoColor=white"/><img alt="React" src="https://img.shields.io/badge/ReactJS-%23000.svg?&style=for-the-badge&logo=react&logoColor=blue"/><img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/><img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
