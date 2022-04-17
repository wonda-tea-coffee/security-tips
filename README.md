# security-tips

## Web一般
- [PortSwigger Web Secrity Academy](https://portswigger.net/web-security)
- [web.dev 安全とセキュリティ](https://web.dev/secure/)
- [安全なウェブサイトの作り方](https://www.ipa.go.jp/security/vuln/websecurity.html)
- [Web セキュリティ研修 / GMO ペパボ 新卒研修 2021](https://speakerdeck.com/mrtc0/gmo-pepabo-xin-zu-yan-xiu-2021)
- [mozilla Web Security](https://infosec.mozilla.org/guidelines/web_security.html)

## クラウド
### 一般
- [クラウドコンピューティングのためのセキュリティガイダンス](https://www.cloudsecurityalliance.jp/guidance.html)

### AWS
- [AWS Well-Architected フレームワーク](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/index.ja.html)
- [インターネットからのイングレストラフィックフローのためのファイアウォールのデプロイ設計](https://aws.amazon.com/jp/blogs/news/design-your-firewall-deployment-for-internet-ingress-traffic-flows/)

## コンテナ
- [アプリケーションコンテナセキュリティガイド](https://www.ipa.go.jp/files/000085279.pdf)
- [container-dev-security](https://speakerdeck.com/mochizuki875/container-dev-security)
- [脅威モデリングで考える Kubernetes セキュリティ](https://speakerdeck.com/mrtc0/cloudnative-days-tokyo-2021-number-cndt2021-number-cndt2021-b)
- [コンテナのセキュリティを 中身から理解しよう](https://speakerdeck.com/udzura/inside-out-container-and-its-security)
- [[AWS Black Belt Online Seminar] コンテナセキュリティ入門](https://aws.amazon.com/jp/blogs/news/aws-black-belt-online-seminar-container-security-introduction/)

## HTML
- [HTML5 Security Cheatsheet](https://html5sec.org/)

## 脅威別
### XSS
- [Browser's XSS Filter Bypass Cheat Sheet](https://github.com/masatokinugawa/filterbypass/wiki/Browser's-XSS-Filter-Bypass-Cheat-Sheet)
- [AngularJS Sandbox Bypass Collection](https://pastebin.com/xMXwsm0N)

### SQL Injection
- [SQL injection cheat sheet](https://portswigger.net/web-security/sql-injection/cheat-sheet)

### drive-by attacks
- [Why are developers so vulnerable to drive-by attacks?](https://about.gitlab.com/blog/2021/09/07/why-are-developers-vulnerable-to-driveby-attacks/)

## Github
- [GitHubリポジトリにおけるレビュープロセスの統制](https://engineering.mercari.com/blog/entry/20211213-8f5f5a5aee/)
- [GitHubセキュリティ Organization運用のベストプラクティス](https://zenn.dev/tmknom/books/github-organization-security)
- [Github Actions Security guides](https://docs.github.com/en/actions/security-guides)
- [GitHubをorgレベルでセキュアに運用する設定](https://zenn.dev/tmknom/scraps/6974be5ba56332)
- [GitHub ActionsのTipsやベストプラクティスを淡々と記録する](https://zenn.dev/tmknom/scraps/f05911dad51689)
- [GitHub EnterpriseのOrganizationに関するガイド　[GitHub Enterprise管理者向け]](https://github.blog/jp/2022-04-05-ghe-organization-guide/)
- [GitHub EnterpriseのOrganization管理　ベストプラクティス　[GitHub Enterprise管理者向け]](https://github.blog/jp/2022-04-05-github-enterprise-organization-best-practice/)

## 認証・認可
- [【電子版】OAuth、OAuth認証、OpenID Connectの違いを整理して理解できる本](https://booth.pm/ja/items/1550861)
- [攻撃して学ぶJWT【ハンズオンあり】](https://moneyforward.com/engineers_blog/2020/09/15/jwt/)

## CircleCI
- [CircleCI Docs Security recommendations](https://circleci.com/docs/2.0/security-recommendations/)

## OPA/Rego
- [OPA/Rego入門](https://zenn.dev/mizutani/books/d2f1440cfbba94)

## 静的解析
### 一般
- [CodeQL](https://codeql.github.com/)
- [Semgrep](https://semgrep.dev/)
- [horusec](https://github.com/ZupIT/horusec)
- [Snyk Code](https://snyk.io/product/snyk-code/)
- [recheck](https://makenowjust-labs.github.io/recheck/)

### Ruby
- [brakeman](https://github.com/presidentbeef/brakeman)

### Go
- [gosec](https://github.com/securego/gosec)

### コンテナ
- [Snyk Container](https://snyk.io/product/container-vulnerability-management/)

### IaC
- [Snyk Infrastructure as Code](https://snyk.io/product/infrastructure-as-code-security/)

## 依存関係の脆弱性検出・管理
- [trivy](https://github.com/aquasecurity/trivy)
- [vuls](https://github.com/future-architect/vuls)
- [dependency track](https://dependencytrack.org/)
- [Snyk Open Source](https://snyk.io/product/open-source-security-management/)
- [octovy](https://github.com/m-mizutani/octovy)
  - 脆弱性検出(trivy)、管理
- [snyk Advisor](https://snyk.io/advisor/)
  - オープンソースプロジェクトのヘルススコアの算出
- [Deadpendency](https://deadpendency.com/)
  - オープンソースプロジェクトのヘルスチェック

### rubygems
- [bundler-audit](https://github.com/rubysec/bundler-audit)

## バグバウンティ
- [Google Hacking Database](https://www.exploit-db.com/google-hacking-database)
- [urlscan.io](https://urlscan.io/)
- [IPAddress.com](https://www.ipaddress.com/)
- [trickest/cve](https://github.com/trickest/cve)
- [Reading RFCs for bug bounty hunters](https://edoverflow.com/2022/reading-rfcs-for-bug-bounty-hunters/)

## Rails
- [Securing Rails Applications](https://guides.rubyonrails.org/security.html)
- [Deserialization on Rails](https://zenn.dev/ooooooo_q/books/rails_deserialize)
- [How to hack with ransack](https://younes.codes/posts/how-to-hack-with-ransack)

## リスク分析
- [制御システムのセキュリティリスク分析ガイド](https://www.ipa.go.jp/security/controlsystem/riskanalysis.html)

## その他情報源
- [Flatt Security Blog](https://blog.flatt.tech/)
- [はてなブックマーク セキュリティ技術](https://b.hatena.ne.jp/hotentry/it/%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3%E6%8A%80%E8%A1%93)
- [徳丸浩の日記](https://blog.tokumaru.org/)
- [徳丸浩のウェブセキュリティ講座](https://www.youtube.com/channel/UCLNW6Bo_YU3TxnzsII2gEDA)
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
- [Webアプリケーション脆弱性診断ガイドライン](https://github.com/WebAppPentestGuidelines/WebAppPentestGuidelines)
- [AWS ホワイトペーパーとガイド](https://aws.amazon.com/jp/whitepapers/?whitepapers-main.sort-by=item.additionalFields.sortDate&whitepapers-main.sort-order=desc&awsf.whitepapers-content-type=*all&awsf.whitepapers-tech-category=tech-category%23security-identity-compliance&awsf.whitepapers-industries=*all&awsf.whitepapers-business-category=*all&awsf.whitepapers-global-methodology=*all)
- [GitHub Advisory Database](https://github.com/advisories)
- [Github Topics](https://github.com/topics)
- [Github Marketplace](https://github.com/marketplace)

## 本
- [安全なWebアプリケーションの作り方](https://wasbook.org/)
- [Webブラウザセキュリティ ― Webアプリケーションの安全性を支える仕組みを整理する](https://www.lambdanote.com/products/wbs)
- [マスタリングTCP/IP 情報セキュリティ編](https://www.ohmsha.co.jp/book/9784274069215/)
- [リアルワールドバグハンティング――ハッキング事例から学ぶウェブの脆弱性](https://www.oreilly.co.jp/books/9784873119212/)
- [セキュア・バイ・デザイン](https://www.amazon.co.jp/dp/B09F697K2V/)
- [Hacking：美しき策謀 第2版――脆弱性攻撃の理論と実際](https://www.oreilly.co.jp/books/9784873115146/)
- [クラウドネイティブセキュリティ入門](https://www.amazon.co.jp/dp/B096TGTN53/)
- [要点整理から攻略する『AWS認定 セキュリティ-専門知識』](https://www.amazon.co.jp/dp/B08DCLRHC7/)
- [サイバー術 プロに学ぶサイバーセキュリティ](https://www.amazon.co.jp/dp/B09JSFTDCH/)
- [実践 CSIRTプレイブック――セキュリティ監視とインシデント対応の基本計画](https://www.oreilly.co.jp/books/9784873118383/)
- [脅威インテリジェンスの教科書](https://gihyo.jp/book/2022/978-4-297-12457-1)
- [イラスト図解式 この一冊で全部わかるセキュリティの基本](https://www.amazon.co.jp/dp/B0756SS7N3/)
- [カオスエンジニアリング入門](https://www.amazon.co.jp/dp/B09VMP3B69/)
- [セキュリティエンジニアのための機械学習――AI技術によるサイバーセキュリティ対策入門](https://www.oreilly.co.jp/books/9784873119076/)
- [実践 bashによるサイバーセキュリティ対策――セキュリティ技術者のためのシェルスクリプト活用術](https://www.oreilly.co.jp/books/9784873119052/)
- [入門 監視――モダンなモニタリングのためのデザインパターン](https://www.oreilly.co.jp//books/9784873118642/index.html)
