# Configs

## For GO

In order to get started with this IDE setup please remember to run the following command:

`:MasonInstall gopls golangci-lint-langserver delve goimports gofumpt gomodifytags gotests impl`

## For Java

Ensure installed

`:MasonInstall jdtls java-debug-adapter java-test`

Prevent default jdtls config, so it gets the ftplugin one
`vim.list_extend(lvim.lsp.automatic_configuration.skipped_servers, { "jdtls" })`
