In order to update macOS Monterey 12.0.1 or later via an MDM utilizing Apples newly introduced 'InstallLater' MDM Command, a bootstrap token must be escrowed to the MDM Server.

To determine the Escrow status of a Bootstrap Token I've included 3 Extension Attributes. One to determine the Bootstrap Token escrow status, a second to determine the SecureToken holder status & a third if the SecureToken holder is unknown. (I did not write these from scratch - credit is not mine)


Good Reads
_____________________________________________________________________________________________________
https://docs.jamf.com/technical-articles/Manually_Leveraging_Apples_Bootstrap_Token_Functionality.html
https://support.apple.com/guide/deployment/use-secure-and-bootstrap-tokens-dep24dbdcf9e/web
