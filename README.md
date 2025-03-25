# Bulletproof React（Reactを防弾に）🛡️ ⚛️

[![MIT License](https://img.shields.io/github/license/alan2207/bulletproof-react)](https://github.com/alan2207/bulletproof-react/blob/master/LICENSE)
[![Next.js App CI](https://github.com/alan2207/bulletproof-react/actions/workflows/nextjs-app-ci.yml/badge.svg)](https://github.com/alan2207/bulletproof-react/actions/workflows/nextjs-app-ci.yml)
[![Next.js Pages CI](https://github.com/alan2207/bulletproof-react/actions/workflows/nextjs-pages-ci.yml/badge.svg)](https://github.com/alan2207/bulletproof-react/actions/workflows/nextjs-pages-ci.yml)
[![React Vite CI](https://github.com/alan2207/bulletproof-react/actions/workflows/react-vite-ci.yml/badge.svg)](https://github.com/alan2207/bulletproof-react/actions/workflows/react-vite-ci.yml)

本番環境に対応したReactのアプリケーションを作るためのシンプルで、拡張性が高い、強力なアーキテクチャ

## はじめに

Reactはとても素晴らしいフロントエンドアプリケーション開発ツールです。必要なものは文字通り何でもある、数百の素晴らしいライブラリを持つ多様なエコシステムもあります。しかし、選定をしなければならない量に圧倒されるでしょう。また、Reactは柔軟性が非常に高く、あなたが好きな方法でアプリケーションを書くことができるとも言えますが、その柔軟性にはコストが伴います。さらに、開発者が参考にできる定義済みのアーキテクチャがないため、乱雑で、一貫性がなく、必要以上に複雑なコードになることがよくあります。

このリポジトリはエコシステムにあるベストなツールと拡張性に優れたプロジェクト構成を使ったReactアプリケーションを作る方法を提示することを試みます。さまざまなコードベースで作業した経験から、このアーキテクチャが最も効果的であることが分かりました。

このレポジトリのゴールはReactのアプリケーションを開発する際のリソースとベストプラクティスを提供することです。アプリケーションで実際に起こる問題を実用的な方法で解決し、開発者がより良いアプリケーションを書けるよう手助けすることを目指します。

このリポジトリから最大限の価値を得られるよう、気軽にサンプルアプリのコードを調べてみてください。

## Reactアプリケーションを「防弾」にするとは？

このレポジトリはさまざまなユースケースのReactアプリケーションに対応する銀の弾丸になることを目指してはいません。しかし、次の原則に基づいた、アプリケーションを作る上での強固な基盤を提供することを目指します。

- 始めやすい
- 理解しやすく、維持しやすい
- 仕事に適したツールを使う
- アプリケーションのさまざまな部品の間に明確な境界を置く
- 物事の進め方に関して、チーム全員が同じ認識を持つ
- セキュア
- パフォーマンスが高い
- コードやチームの規模への拡張性が高い
- 出来るだけ早く問題を見つけられる

#### 免責事項:

このリポジトリはテンプレートやボイラープレート、フレームワークではありません。特定の方法で物事を行うやり方を示す独断的なガイドです。ここで示したことを全て正確に行う必要はありません。あなた自身、それからあなたのチームにとって何がベストかを決め、スタイルの一貫性を保ちましょう。

最大限に活用するには、サンプルアプリで使われている技術だけを使うようにするのではなく、示されている原則とコンセプトに注目する必要があります。ここで使われているツールやライブラリは提案にすぎず、必要に応じてより良いものに置き換えることが可能です。時折、あなたのプロジェクトでは少し違ったアプローチをとる必要があるかもしれません。これはまったく問題ありません。

## Table Of Contents:

- [💻 Application Overview](docs/application-overview.md)
- [⚙️ Project Standards](docs/project-standards.md)
- [🗄️ Project Structure](docs/project-structure.md)
- [🧱 Components And Styling](docs/components-and-styling.md)
- [📡 API Layer](docs/api-layer.md)
- [🗃️ State Management](docs/state-management.md)
- [🧪 Testing](docs/testing.md)
- [⚠️ Error Handling](docs/error-handling.md)
- [🔐 Security](docs/security.md)
- [🚄 Performance](docs/performance.md)
- [🌐 Deployment](docs/deployment.md)
- [📚 Additional Resources](docs/additional-resources.md)

## Contributing

Contributions are always welcome! If you have any ideas, suggestions, fixes, feel free to contribute. You can do that by going through the following steps:

1. Clone this repo
2. Create a branch: `git checkout -b your-feature`
3. Execute the `yarn prepare` script.
4. Make some changes
5. Test your changes
6. Push your branch and open a Pull Request

## License

[MIT](/LICENSE)
