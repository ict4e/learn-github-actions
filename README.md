# learn-github-actions

status of build and test workflow:

![workflow](https://github.com/ict4e/learn-github-actions/actions/workflows/build-and-test.yml/badge.svg)


- build-and-test.yml
    - 初歩的なワークフローの作成
    - ref: https://zenn.dev/farstep/books/learn-github-actions/viewer/create-your-first-workflow


[![Create Merge Pull Request](https://github.com/ict4e/learn-github-actions/actions/workflows/create-merge-pr.yml/badge.svg)](https://github.com/ict4e/learn-github-actions/actions/workflows/create-merge-pr.yml)

- create-merge-pr.yml
    - マージPRを作成するワークフロー
    - souce : main, target : dev4 
    - required settings:
        - team setting: Allow GitHub Actions to create and approve pull requests
        - repo setting: Allow GitHub Actions to create and approve pull requests
        - ※Read and write permissions は PR作成において必須ではない
    - ref: https://zenn.dev/kenghaya/articles/d7f766e5db6437


- workflow-dispatch-sample.yml
    - 手動実行サンプル

