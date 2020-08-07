# TOTP说明
### KeePass的Tray TOTP插件和KeePassX（推荐）
- **在软件里设置或直接在字串字段设置两步验证**<br />
【名称】：TOTP Seed<br />
【值】：TOTP种子密钥<br />
【名称】：TOTP Settings<br />
【值】：时间步长;一次性密码位数
______________________________________________________________________________
### 各个版本TOTP的兼容性
- keepass的KeeTrayTOTP插件：不兼容keepass的KeePassOTP插件、KeeOtp插件，KeePassXC，KeeWeb，KeePassDX
- keepass的KeePassOTP插件：不兼容keepass的KeeTrayTOTP插件、KeeOtp插件，KeePassXC，KeeWeb，KeePassDX
- keepass的KeeOtp插件：不兼容keepass的KeeTrayTOTP插件、KeePassOTP插件，KeePassXC，KeeWeb，KeePassDX
- KeePassXC：兼容keepass的KeeTrayTOTP插件、KeePassOTP插件、KeeOtp插件，KeeWeb，KeePassDX
- KeeWeb：兼容keepass的KeeTrayTOTP插件、KeePassOTP插件（设置TOTP一次性密码时必须设置用户名）、KeeOtp插件，KeePassXC，KeePassDX
- Keepass2Android：兼容keepass的KeeTrayTOTP插件、KeePassOTP插件（设置TOTP一次性密码时必须设置用户名）、KeeOtp插件，KeeWeb（TOTP密钥粘贴完成后时需要点击一下TOTP密钥生成otpauth://totp/default?secret=），KeePassXC，KeePassDX
- KeePassDX：兼容keepass的KeeTrayTOTP插件、KeePassOTP插件、KeeOtp插件，KeePassXC，KeeWeb（TOTP密钥粘贴完成后时需要点击一下TOTP密钥生成otpauth://totp/default?secret=）