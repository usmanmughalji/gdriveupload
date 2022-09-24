#### 24-August-2022
- gdrive: publish new stable version
- go.mod: update dependencies
- Add support for OAuth callback flow
#### 01-June-2022
- gdrive: publish new stable version
- go.mod: update dependencies
- allow user specified oauth credentials
- util: move token file to $XDG_CONFIG_HOME
- all: reformat with goimports
- shell.nix: add nix-shell config
#### 04-April-2022
- gdrive: remove redundant slice type
- go.mod: fix go-gitignore requirement again
- drive: add missing formatting arguments
- State support for team drives
- handlers_drive: remove invalid credentials and source at build time
- Switch to Go modules
- Return Unlimited when size is negative
- Dont download data if file is skipped
- Fix about output for unlimited drive accounts
- Use exponential back off for gdrive download and gdrive download query
