<p align="center">
 <img width="150px" src="https://github.com/Code-Fundi/.github/blob/main/media/gradient-bg-logo.png?raw=true" align="center" alt="Code Fundi" />
 <h2 align="center"><b>Code Fundi</b></h2>
 <p align="center">A CLI tool for Code Fundi; an AI assistant that helps you write better code faster.</p>
 </br>
</p>
</p>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=Stage&message=Alpha&color=0071f3" />
  <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/static/v1?label=Licence&message=AGPL%20v3&color=000" />
  </a>
  <br />
  <a href="https://discord.gg/6RJTWCuWZj">
    <img src="https://img.shields.io/badge/Discord-7289DA?logo=discord&logoColor=white" />
  </a>
  <a href="https://twitter.com/code_fundi">
    <img src="https://img.shields.io/badge/Twitter-00acee?logo=twitter&logoColor=white" />
  </a>
  <a href="https://www.tiktok.com/@codefundi">
    <img src="https://img.shields.io/badge/TikTok-000000?logo=tiktok&logoColor=white" />
  </a>
<br />
</p>


## Usage

```yml
name: Site Build
on: [push]
jobs:

  build:
    name: Build
    runs-on: ubuntu-latest
    steps:
      - name: Auto debug logs incase of error
        uses: code-fundi/code-fundi-action@main
        with:
          command: npm run build
          key: ${{ secrets.CODE_FUNDI_API_KEY }}
```

### Setup API Key
To get your API Key head over to the [dashboard](https://codefundi.app/auth).

Next, click on the `Profile` tab and scroll to the section with the API Key. 
<br />
<a>
  <img src="https://github.com/Code-Fundi/.github/blob/main/media/gen-api-key%20(1).png?raw=true" alt="Alt Text" />
</a>

From here, you can create your API key and copy it in the config file.
<br />
<a>
  <img src="https://github.com/Code-Fundi/.github/blob/main/media/gen-api-key%20(2).png?raw=true" alt="Alt Text" />
</a>