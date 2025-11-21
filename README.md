[![GitHub release](https://img.shields.io/github/release/jakegage/jakegage.svg?label=release)](https://github.com/jakegage/jakegage/releases/latest) [![Contributors](https://img.shields.io/github/contributors/jakegage/jakegage.svg)](https://github.com/jakegage/jakegage/graphs/contributors)

```mermaid
architecture-beta
    group api(cloud)[API]

    service db(database)[Database] in api
    service disk1(disk)[Storage] in api
    service disk2(disk)[Storage] in api
    service server(server)[Server] in api

    db:L -- R:server
    disk1:T -- B:server
    disk2:T -- B:db
```

<!--
**jakegage/jakegage** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
