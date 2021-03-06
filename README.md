<h1 align="center">Welcome to Novel-Template ð</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/haoblackj/Novel-Template#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/haoblackj/Novel-Template/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/haoblackj/Novel-Template/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/haoblackj/Novel-Template" />
  </a>
</p>


### ð  [Homepage](https://github.com/haoblackj/Novel-Template#readme)

## Author

ð¤ **haoblackj**

* Github: [@haoblackj](https://github.com/haoblackj)

## ð¤ Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/haoblackj/Novel-Template/issues). You can also take a look at the [contributing guide](https://github.com/haoblackj/Novel-Template/blob/master/CONTRIBUTING.md).

## Show your support

Give a â­ï¸ if this project helped you!

##  åæ
- åä½ãµãã¼ãã¯ä¸åã§ãã¾ãããæã£ãã¨ããåããªã? ç¥ã£ããã£ã¡ããªãã§ãããèªç±ã«ãã£ã¦ãã¤ã£ã¹
-  èª¬æã«ç¨ããç°å¢ã¯æ¬¡ã®ã¨ããã
    - Windows 10 November 2021 Update(ãã¼ã¸ã§ã³ 21H2) (OS ãã«ã 19044.1645) (x64)
    - Google Chrome
- MacãLinuxãä½¿ãæ¹ã¯é©å½ã«èª­ã¿æ¿ãã¦ãã ããã
- FirefoxãMicrosoft Edgeãä½¿ãæ¹ã§ããä»¥ä¸ã®æé ã§ç¹ã«åé¡ãªããã¨ã¯æãã¾ããæ¤è¨¼ã¯ãã¦ã¾ããã
    - Internet Explorer(Microsoft Edgeã®IEã¢ã¼ããå«ã)ãSafariã§ã¯åä½ãç¢ºèªãã¦ãã¾ãããããæ°ãããã¾ããã
##  ãã³ãã¬ã¼ãã®ä½¿ç¨æ¹æ³
1.  ãã³ãã¬ã¼ããªãã¸ããªãã¼ã¸ä¸­æ®µã®ãUse this templateããæ¼ä¸ããã
2.  ä½æããããªãã¸ããªåãå¥åããã
3.  å¬éãªãã¸ããªãéå¬éãªãã¸ããªããé¸æããã
4.  Include all branchesã®ãã§ãã¯ãç©ºç½ã«ãªã£ã¦ãããã¨ãç¢ºèªããã
5.  ãªãã¸ããªä½æå®äºã
## ãªãã¸ããªä½æå¾ã«ãããã¨
1.  package.jsonçæ
    1.  ã¯ã­ã¼ã³ããã­ã¼ã«ã«ãã£ã¬ã¯ããªã§cmdãªããPowerShellãèµ·åããã
    2.  ä»¥ä¸ã®ã³ãã³ããæå¥ããã
    ~~~cmd:generate package.json
    npm init
    ~~~
    3.  è³ªåã«åç­ããªãããpackage.json ãçæããã
    4.  ä»¥ä¸ã®ã³ãã³ããæå¥ããã
    ~~~cmd:generate package.json
    npm install
    ~~~
3.  åå¥ãã¡ã¤ã«ãä¿®æ­£ããã
    - config.toml
        - baseURL
        - title
    - dict/dict.yml
        - ããããã®åºæåè©ããããæ¸ãããããããããªãã§ããã­ã
    - .github/ISSUE_TEMPLATE/config.yml
        - ãProject Nameã ããªãã¸ããªåã«å¤æ´ããã
2.  GitHub Actionsç¨ã® Secrets ãè¿½å ããã
    1.  AccountâSetting ãã Developer settings ã¸é²ã¿ãPersonal access tokens ãéãã
    2.  ä»¥ä¸ã®3ã¤ã®ãã¼ã¯ã³ãçæããã
        - GitHub Project Automation+ (repo)
        - Labeler (admin:public_key, notifications, repo, user, workflow, write:discussion, write:packages)
        - DEPENDABOT_AUTOMATION_TOKEN (repo)
    3.  åãã¼ã¯ã³çºè¡å¾ããã¼ã¯ã³ãæ§ãã¦ããã
    4.  ãªãã¸ããªã«æ»ããSettings â Secrets â Actionsã«é²ãã
    5.  ããããã®ãã¼ã¯ã³ãç»é²ããã
        - GitHub Project Automation+ : GPA_PAT
        - Labeler : LABELER_PAT
        - DEPENDABOT_AUTOMATION_TOKEN : DEPENDABOT_AUTOMATION_TOKEN
4.  GitHubã®åæ©è½ãæå¹åããã(ç¹è¨ãªãå ´åã¯æå¹åãã)
    - Projects
    - Discussions
    - Pull Requests
        - Allow merge commits
        - Allow squash commits
        - Allow rebase commits
        - Allow auto-merge
        - Automatically delete head branches
    - Code security and analysis
        - Dependency graph
        - Dependabot alerts
        - Dependabot security updates
    - Pages (ãã¬ããªã³ãã¨ãã¦ã®é²è¦§ç¨ãã¼ã¸ãå¿è¦ãªå ´åã¯è¨­å®ãã¦ãã ããããã©ã¤ãã¼ããªãã¸ããªã§ã¯GitHub Proç­ã®å¥ç´ãå¿è¦ã§ã)
        - Source
            - Branch : gh-pages
            - (root)
5.  ãã¬ããªã³ãæ©è½ãä½¿ç¨ããå ´åãHugoã®ãã¼ãããé©å½ãªãã®ãé¸ã³ãè¨­å®ããã

## ToDo
- [ ] ãªãã¸ããªã«å®è£ããæ©è½ã«é¢ããèª¬æ
- [ ] ä½¿ç¨ãã¦ããããã±ã¼ã¸ãhugoã®ãã¼ãã«é¢ããè¨è¿°

## ð License

Copyright Â© 2022 [haoblackj](https://github.com/haoblackj).<br />
This project is [MIT](https://github.com/haoblackj/Novel-Template/blob/master/LICENSE) licensed.

***
_This README was generated with â¤ï¸ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
