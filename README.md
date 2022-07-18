[![](https://img.shields.io/badge/Kang_Minchul-181717?style=&logo=github&logoColor=white)](https://github.com/kangtegong) [![](https://img.shields.io/badge/Kim_Jaeuk-220052?style=&logo=github&logoColor=white)](https://github.com/zzxx3081)

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179363100-f119d8b7-849f-4a6c-9dba-5c2d30047215.svg"height="200px" width="700px"></p>

:herb: **`TryThisOnBrowser`** is an open source demo platform made by `Kang Minchul`, `Kim Jaeuk`. Our project provides the services that
registering, searching, testing and reporting for any open sources. You can easily upload and try out various open sources like [gcc](http://gcc.gnu.org/), [clang](https://clang.llvm.org/), [linux distros](https://distrowatch.com/), [uftrace](https://github.com/namhyung/uftrace), etc and reach out to maintainers of these projects through this platform. Through the below badge, you can visit our website and try to enjoy searching interesting open sources without any dependency packages.

|                                                                         `Project Link`                                                                          |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [![TryThisOnBrowser_logo](https://user-images.githubusercontent.com/74658309/179361886-25a20165-bd00-462a-84d4-1b5024e5a533.svg)](http://trythisonbrowser.com/) |

</br>

# Contents

1. [How to Sing up](#How-to-Sign-up)
2. [Main Page](#Main-Page)
   - [Most Popular Projects](#Most-Popular-Projects)
   - [Open Sources You May Like](#Open-Sources-You-May-Like)
   - [Recently Added](#Recently-Added)
3. [Navigate](#Navigate)
   - [Dashboard](#Dashboard)
   - [Search open sources](#Search-open-sources)
   - [My containers](#My-containers)
   - [About](#About)
4. [How to upload your open source](#How-to-upload-your-open-source)
   - [Create with installation script](#Create-with-installation-script)
   - [Create with Dockerfile](#Create-with-Dockerfile)
5. [How to test](#How-to-test)
6. [Bug reports or contribute](#Bug-reports-or-contribute)

# How to Sign up

:herb: You can sign in with **`google`** or **`github`**. Otherwise, you'll be able to sign up manually with `username`, `password`, and `email`. If you want to delete your accout, go to `user settings`, and press `Delete your ID` button.

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179385000-6cf8e2fd-8e7c-41ca-9718-16a4dac909f3.gif" height="400px" width="300"></p>

# Main Page

## Most Popular Projects

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179403888-a193af19-f573-482d-9e30-0a8b9fb52dca.jpg"></p>

:herb: Once you visit our website, you can see `Most Popular Projects` below advertising banner. It shows the top three open sources with the highest number of **likes** in our platform. You'll be able to know that what open sources other developers prefer. Moreover, you are free to test them and communicate with other main tainers about their open sources.

:herb: You'll see `Hashtags` for some open sources. It tells technolocal information used in the open source. Thus, you'll expect what skills included in there open source.

:herb: `Mark of heart` means the `number of likes` for some open source. All of our members can record likes if they are interested for the open source.

## Open Sources You May Like

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179416690-dde5bc4c-3947-49d4-a28a-08390a6a66b8.jpg"></p>

:herb: You can easily find out `Open Sources You May Like` in the middle of our main page. It is a open source preferation board that you may like. The recommandation system is based on your **likes** and **hashtags**. In other words, if you want to show this record, you should sign in our platform and press the button of **likes** for any other open sources.

## Recently Added

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179417217-bdeda61a-f349-440e-9bc8-88ed9bde0286.jpg"></p>

:herb: `Recently Added` is Final tap of our main page. It has five record about open sources updated the most recently. You'll be able to browse uploaded new open sources in real time through this banner. each of records include `Image Name`, `Tag`, `Author`, `Uploaded At (GMT)` and `likes`.

:herb: If you would like to test any open sources, just click the button `Try`. Note that we only allow **one open source per user**. You cannot try out more than two open source at the same time.

# Navigate

## Dashboard

:herb: It is the function of move to main page. If you want to move, click this tap.

## Search open sources

:herb: If you want to find any open sources or need to inquire all of open sources list, you can use `Search open sources` placed on the left site of main page. This means that you'll be able to show seven open sources per pages like below figure.

:herb: If you would like to find unique open sources, you'll be able to use `search bar` located above the main page. We provide a function of search based on `Image Name`.

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179418334-7d087ac5-24a9-4ffb-b2de-3a5ea2d98f68.gif"></p>

## My containers

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179418891-c2ef0f54-4ef5-4ec2-97b9-9c8d94a35ade.png"></p>

:herb: If you click the menu `My containers`, you can inqure all of your open sorces you pressed the `likes` button. In addition, It is possible to demonstrate these open sources or delete certain records. If you press `Delete` button, it'll be changed `Open Sources You May Like`.

## About

:herb: It is a guide for the platform. If you need more information for our website, read this.

# How to upload your open source

:herb: You can either upload your opensource with your **Dockerfile**, or **installation script**. Note that you should **sign up** before upload your project.
If you click `+ Create New Project` above, you will see `Create with installation script`, and `Create with Dockerfile`.

<p align="center"><img src="https://user-images.githubusercontent.com/74658309/179420106-eb7f85b2-6edb-465c-9bf5-4b29012a995b.png"height="180px" width="200px" ></p>

## Create with installation script

:herb: This is a way to upload your opensource with installation script.
First type `Author`, `Project name`, `Tag` (of the image), `Contact point`, `Project description` and `Hash Tag`. Then choose your `Base OS` you want to install and write out installation script.
**Note that** the script should be detailed and precise(otherwise) because otherwise it would not be installed.
Once script ran successfully, `Trythisonbrowser` will create an docker image based on your script. please refer to the figure below.

|              Items               |                    Description                     |
| :------------------------------: | :------------------------------------------------: |
|             `Author`             |            Name of Open source Develper            |
|          `Project name`          |           Your project name (Image Name)           |
|              `Tag`               |     Version of open source (Ex. latest, 18.04)     |
|         `Contact point`          |                Email of Maintianer                 |
|      `Project description`       | Your project menual or How to use your open source |
|            `Hash Tag`            |    Technical information included your project     |
|            `Base OS`             |        Operation System you want to install        |
| `Enter your installation script` |  Installation script of your open source project   |

### Example: [uftrace](https://github.com/namhyung/uftrace)

<img src="https://user-images.githubusercontent.com/74658309/179465948-61682a4a-f58e-45b4-9e48-c2cee61fa83d.png">

<img src="https://user-images.githubusercontent.com/74658309/179468765-f367c3be-fdfd-4bf0-8c8f-53328f1cbe14.gif">

## Create with Dockerfile

:herb: If your project has Dockerfile, just upload your Dockerfile like below. Then `Trythisonbrowser` will create an docker image based on your Dockerfile.

:herb: Note that Except for Dockerfile upload, the input list is the same as above.

### Example: cURL project

<img src="https://user-images.githubusercontent.com/74658309/179470629-4dbbe73a-a71a-41be-9ef8-dd25e2a82400.png">
<img src="https://user-images.githubusercontent.com/74658309/179470828-2da35cf3-fd35-4342-bac4-78a3d0c0a5d1.png">

# How to test

:herb: If you're interested in some open sources, press the button `Try`. Then you can move to `Try page` about these open sources. The page consists of three items. (`Project information`, `Terminal` and `Commant box`)

### Project information (sample. Git)

<img src="https://user-images.githubusercontent.com/74658309/179484775-72fce8f4-3e58-4725-ad52-5663f2af01f4.png">

:herb: Project information has `Contact Maintainer`, `Likes`, `OpenSource Not Working`, `Project description` and `Hash tag`. You'll be able to know about the project and commnicate with its developer by mailing through botton of `Contact Maintainer`.
Moreover, If you find out any bugs or problems for the open source, you can report to other users through button of `OpenSource Not Working`.

### Terminal (sample. Git)

<img src="https://user-images.githubusercontent.com/74658309/179515108-033f6df9-6319-4b17-88e4-f17b0ee21d79.gif">

:herb: You can test the open source you choose in `Terminal` without intalling any file or packeges. In additon, you will be able to experience excellent functions created by maintainers.

### Commant box

<img src="https://user-images.githubusercontent.com/74658309/179516094-3821bc16-80c0-45b3-abae-df06c063bf99.png">

:herb: If you have question about open source you are testing, you can use `Commant box`.

# Appendix

:herb: Our platfrom have many open sources registered by maintainers all over the world. Visit our project and connect with various developers.

### Example 1 (Python Primality_test Algorithm)

![git pty](https://user-images.githubusercontent.com/74658309/179555482-32547e9b-16b5-491b-954f-bc45fd016c8b.gif)

### Example 2 (Perl Print "Hello world")

![git pty455](https://user-images.githubusercontent.com/74658309/179560004-7c1f8cc6-d66b-4308-a19b-1dc21b907c06.gif)

### Example 3 (Ruby Fibonachi_sequence)

![git ruby](https://user-images.githubusercontent.com/74658309/179535880-79d35ae1-b4c7-4d2a-9201-aed121195717.gif)

# Bug reports or contribute

If you have any issues or great ideas, fill free to contact me via email or github issues.

- Email: tegongkang@gmail.com
- Github: https://github.com/kangtegong/trythisonbrowser/issues
