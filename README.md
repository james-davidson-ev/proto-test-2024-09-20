# proto-test-2024-09-20

buf generate --template buf.gen.go.yaml
cd iw-mapviewer.cmh.platform-dev.evinternal.net
git add .
git commit -m update
git push

## note

The file index.html on https://iw-mapviewer.cmh.platform-dev.evinternal.net includes:

<meta name="go-import" content="iw-mapviewer.cmh.platform-dev.evinternal.net git https://github.com/james-davidson-ev/test-2024-09-20">
