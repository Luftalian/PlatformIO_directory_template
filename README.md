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
