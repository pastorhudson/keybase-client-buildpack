# keybase-client-buildpack
This is a Keybase Client Buildpack for use with Heroku or Dokku

### Use This URL For The build pack
`https://github.com/pastorhudson/keybase-client-buildpack.git`

### Add Buildpack on Dokku App
`dokku buildpacks:add keybase-buildpack-test https://github.com/pastorhudson/keybase-client-buildpack.git`
Or Possibly
`dokku config:set keybase-buildpack-test BUILDPACK_URL=https://github.com/pastorhudson/keybase-client-buildpack.git`

### Add Buildpack on Heroku
`heroku config:add keybase-buildpack-test BUILDPACK_URL=https://github.com/pastorhudson/keybase-client-buildpack.git`
