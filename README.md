## パーミッション
マウントされるディレクトリがUID: 1000 GID:1000によって読み書きできるようにする必要があります
> For persistent storage you can either create a named volume or mount a new/existing db path -v /hydrus/client/db:/opt/hydrus/db. The client runs with default permissions of 1000:1000, this can be changed by the ENV UID and GID(not working atm, fixed to 1000) will be fixed someday™.

## Usage
```
docker compose up
```
80番ポートからHydrus Webにアクセスできるようになります

## VNC
`http://localhost/__vnc/`にアクセスすることによりHydrusのGUIを触ることができます

## インポート
VNCにつなげて`/import`フォルダを定期巡回するように設定してください
