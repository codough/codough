# codough

![codough](./logo.png)

## インセプションデッキ

今すぐプロダクト・プロトタイピングを作成したい、プロダクト開発・検証向けの「codough」は「コード（code）」と「生地（dough）」の意味を合わせた、プロダクトを作るのに必要なベースとなる成果物を提供するための活動の総称です。

![](./contents/scrum/scrum-sprint0.png)

Webベース、かつGitpodを組み合わせたプラットフォームでの提供であり、これはその技術に精通していない誰にでもすぐに動作を確認することができ、他のサンドボックス系のサービスとは違ってプロダクト開発をアジャイルに展開するのに「Sprint 0」として実施しなければいけないことの多くを肩代わりしてくれた状態から開始できるというメリットが備わっています。

## プレーン

(WIP)

### Twelve-Factor App

- `The Twelve-Factor App`  に準拠している

![](./contents/cicd/twelve_factor_app.png)

### CI/CD Cycle

![](./contents/cicd/buildPipeline.png)

- 以下の機能を備えている
    - make setup
    - make test
    - make lint
        - make autocorrect
    - make test
        - make ui-test
    - make build
    - make deploy



## プレーン メニュー

### Webフロントエンド (Nodeベース)

| React (Web) | Vue.js | Angular | 
| --- | --- | --- |
| [![react-web](./contents/menu/icon-react-web.png)](https://github.com/codough/codough-plate-web-react) | [![](./contents/menu/icon-vue.png)](https://github.com/codough/codough-plate-web-vue) | [![](./contents/menu/icon-angular.png)](https://github.com/codough/codough-plate-web-angular) |

### iOS フロントエンド

| UIKit | SwiftUI |
| --- | --- |
| [![iOS UIKit](./contents/menu/icon-ios-uikit.png)](https://github.com/codough/codough-plate-ios-uikit) | [![iOS SwiftUI](./contents/menu/icon-ios-swiftui.png)](https://github.com/codough/codough-plate-ios-swiftui) |

### Android フロントエンド

| Android View | Jetpack Compose |
| --- | --- |
| [![Android View](./contents/menu/icon-android-view.png)](https://github.com/codough/codough-plate-android-view) | [![Android Jetpack Compose](./contents/menu/icon-android-jetpack.png)](https://github.com/codough/codough-plate-android-jetpack-compose) |

### xPlatform フロントエンド

| React Native | Flutter |
| --- | --- |
| ![React Native](./contents/menu/icon-react-native.png) | ![Flutter](./contents/menu/icon-flutter.png) |

## CI/CD

### CI (継続的インテグレーション)

| | |
| --- | --- |
| | **ソースコードリポジトリ** | |
| ![AWS CodeCommit](./contents/cicd/icon-cicd-codecommit.png) | AWS CodeCommit | 
| ![GitHub](./contents/cicd/icon-cicd-github.png) | GitHub | 
| | **ビルドパイプライン** | |
| ![AWS CodePipeline](./contents/cicd/icon-cicd-codepipeline.png) | AWS CodePipeline | 
| ![AWS CodeBuild](./contents/cicd/icon-cicd-codebuild.png) | AWS CodeBuild | 
| ![Bitrise](./contents/cicd/icon-cicd-bitrise.png) | Bitrise | 
| ![GitHub Actions](./contents/cicd/icon-cicd-githubactions.png) | GitHub Actions | 

### CD (継続的デリバリーまたは継続的デプロイメント)

| | |
| --- | --- |
| | **デプロイメント** | |
| ![AWS CodeDeploy](./contents/cicd/icon-cicd-codedeploy.png) | AWS CodeDeploy | 
| ![AWS Amplify](./contents/cicd/icon-cicd-amplify.png) | AWS Amplify Console | 
| ![Fastlane](./contents/cicd/icon-cicd-fastlane.png) | Fastlane | 
| | **E2E** | |
| ![AWS Device Farm](./contents/cicd/icon-cicd-devicefarm.png) | AWS Device Farm | 
| ![AWS Device Farm](./contents/cicd/icon-cicd-appetize.io.png) | Appetize.io | ΩΩ
