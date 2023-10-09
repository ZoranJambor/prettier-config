# An example `prettier-config` that can be extended

This project is used in [Mastering Linting](https://masteringlinting.com) course, to demonstrate how can the same Prettier config be used in different projects, and how can some options from that config can be extended when Prettier config in JavaScript format (`.prettierrc.js`) is used.

## Installation & usage
Install via NPM and add to your development dependencies:
```
npm install @cssweekly/prettier-config --save-dev
```

Use the config in `package.json`:
```
{
    "prettier": "@cssweekly/prettier-config" ``
}
```

Use the config in `.prettierrc.js`:
```
module.exports = {
    ...require("@cssweekly/prettier-config")
    // ...
    // Prettier options you want to override
    // ...
}
```

## Links
- [Mastering Linting Course](https://masteringlinting.com)
- [Mastering Linting GitHub Repository](https://github.com/ZoranJambor/masteringlinting)
- [CSS Weekly Newsletter](https://css-weekly.com)
- [CSS Weekly YouTube Channel](https://youtube.com/@cssweekly)