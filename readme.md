#BetaFirmwares

###### An open-source Swift project that pulls OTA updates from Apple, and checks the data type.

This is in complete beta, so some features aren't there yet and bugs may occur.
If you want to add these things yourself, please make a pull request.

#Setup
We use SwiftyJSON, so you must run two commands: 
`git submodule init` to initialize your local configuration file, and `git submodule update` to fetch all the data from that project and check out the appropriate commit.

Thanks to [/u/AppleBetas](https://reddit.com/user/AppleBetas) for helping me loop through JSON; I personally have never worked with JSON in swift, only in Obj-C, so a lot of credit should go to him.
