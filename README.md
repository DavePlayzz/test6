# DBots API
Bot for DBots.

Projects to Host Series - https://www.youtube.com/watch?v=ARkTLD_j2cM&list=PLGfT2ttRbfiyyci-6_mmKaTA0-2qm_U6H&index=1

**Dashboard**: https://github.com/theADAMJR/DBots

![API](https://cdn.discordapp.com/attachments/772003992598347776/776014657415544868/image.png)

## Installation
1) Fork/download this respository
2) `npm i` to install packages

### Config
`config.json` example:
```
{
    "bot": {
        "token": "",
        "secret": "",
        "ownerId": "218459216145285121",
        "activity": "dbots.co",
        "id": "533947001578979328"
    },
    "guild": {
        "botRoleId": "723982260554039349",
        "devRoleId": "",
        "id": "531196495584821314",
        "logChannelId": "724730682433077359"
    },
    "api": {
        "url": "http://localhost:3000/api/v1",
        "port": "3000",
        "supportInvite": "uDTgxyg"
    },
    "dashboardURL": "http://localhost:4200",
    "mongoURL": "mongodb://localhost/DBots"
}
```

### Redirect URIs
- `http://localhost:3000/api/v1/auth` (locally)
- `http://localhost:4200/dashboard` (locally)
