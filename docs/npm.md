# A Guide to Setting Up Node.js Projects with npm

## Introduction to npm

To complete this section, make sure you have ![installed Node.js](/node.md).

## Install Node.js

The simplest way to install Node.js is to use the installer provided by [Node.js official website](https://nodejs.org/).


### Windows

1. First, go to the Nodejs.org official website and go to the download tab. [Node.js official website](https://nodejs.org/en).
![installatoin_window](../assets/images/jin_node_installation1.png)

2. Once the download is complete, run it. When the installation file runs, click the Next button.
![installatoin_window](../assets/images/jin_node_installation2.png)

3. After agreeing to the terms and conditions, click the Next button.
![installatoin_window](../assets/images/jin_node_installation3.png)

4. This is the field that specifies the directory where nodejs will be installed.
By default, it is installed under C:\Program Files\nodejs\.
Click the Next button.
![installatoin_window](../assets/images/jin_node_installation4.png)

5.  Node.js runtime environment (what we are targeting this time)
    corepack manager Core package manager (I don't use it often)
    npm package manager NPM package manager (very often used and useful)
    Online documentation shortcuts. Go to online manual (not used)
    Add to PATH (Must be registered in PATH!)
![installatoin_window](../assets/images/jin_node_installation5.png)

    You may not install them individually as above, but there is no harm in having them, so just click the Next button.
![installatoin_window](./Assets/images/jin_node_installation6.png)

6. ​Finally, installation preparations are complete. Please click the Install button.
![installatoin_window](./Assets/images/jin_node_installation7.png)

7.  Installation is complete. Please click the Finish button.
![installed](/Assets/images/jin_node_installation78.png)


```{js, echoes = false}
import fs from "fs"
fs.readfileSync("./docs/assets/images/sample_img.jpg");
```

// Action first 
// seperate line

### macOS

1. Node.js 공식 웹사이트에서 macOS 인스톨러를 다운로드합니다.
2. 다운로드한 파일을 열고, 화면의 지시에 따라 설치합니다.

### Linux

Linux 사용자는 패키지 매니저를 통해 Node.js를 설치할 수 있습니다. 예를 들어, Ubuntu에서는 다음 명령어를 사용합니다.

```bash
sudo apt update
sudo apt install nodejs
sudo apt install npm
