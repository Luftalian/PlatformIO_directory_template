# Avi_73J_Board

## How to develop
1. Get token
    1. `https://github.com/settings/tokens/new`
    2. check `public_repo`
    3. Copy token
2. set ${{ secrets.UPDATE_SUBMODULE }}
    1. `https://github.com/Avi-73/Avi_73J_***/settings/secrets/actions/new`
    2. Name : `UPDATE_SUBMODULE`
    3. Secret : Paste token
3. `$ make init`

## Commands
|Command|action|
|:--|--|
|`make init`|Gitリポジトリにサブモジュールを追加するためのコマンド|
|`make branch-push`|新しいブランチを作成して、ローカルリポジトリに変更を追加し、変更をリモートリポジトリにプッシュするためのコマンド|
|`make clear`|src/utilsディレクトリを削除するためのコマンド|
|`make delete-submodule`|サブモジュールを削除するためのコマンド|
|`make set-submodule`|新しいサブモジュールを追加するためのコマンド|
|`make update-submodule`|サブモジュールを最新の状態に更新するためのコマンド|
|`make obsolesce-submodule`|update-submoduleする前の状態に戻すコマンド|
