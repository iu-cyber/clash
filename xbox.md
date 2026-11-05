payload:
  # --- 1. 微软支付网关与商城结算核心（最关键：杜绝被后续规则分流到香港）---
  - DOMAIN,purchase.mp.microsoft.com
  - DOMAIN,store.mp.microsoft.com
  - DOMAIN,displaycatalog.mp.microsoft.com
  - DOMAIN,licensing.mp.microsoft.com
  - DOMAIN,account.microsoft.com
  - DOMAIN-SUFFIX,onestore.ms
  - DOMAIN-SUFFIX,mpnevolution.com

  # --- 2. 账号与身份认证鉴权（决定购买时的身份属地与 Token）---
  - DOMAIN,login.live.com
  - DOMAIN,logincdn.msauth.net
  - DOMAIN,login.microsoftonline.com
  - DOMAIN-SUFFIX,passport.net
  - DOMAIN-SUFFIX,msauth.net
  - DOMAIN-SUFFIX,msauthimages.net
  - DOMAIN-SUFFIX,msftauth.net
  - DOMAIN-SUFFIX,msftauthimages.net
  - DOMAIN-SUFFIX,msidentity.com

  # --- 3. Xbox 核心系统与商城界面（均为轻量 API，无大流量）---
  - DOMAIN,img-prod-cms-rt-microsoft-com.akamaized.net
  - DOMAIN,store-images.s-microsoft.com
  - DOMAIN-SUFFIX,xbox.com
  - DOMAIN-SUFFIX,xboxlive.com
  - DOMAIN-SUFFIX,xboxservices.com
  - DOMAIN-SUFFIX,xboxservice.com
  - DOMAIN-SUFFIX,gamepass.com
  - DOMAIN-SUFFIX,xboxgamepass.com
  - DOMAIN-SUFFIX,xboxplayanywhere.com
  - DOMAIN-SUFFIX,xboxgamestudios.com
  - DOMAIN-SUFFIX,xboxstudios.com
  - DOMAIN-SUFFIX,xbox.co
  - DOMAIN-SUFFIX,xbox.eu
  - DOMAIN-SUFFIX,xbox.org
  - DOMAIN-SUFFIX,xbox360.com
  - DOMAIN-SUFFIX,xbox360.co
  - DOMAIN-SUFFIX,xbox360.eu
  - DOMAIN-SUFFIX,xbox360.org
  - DOMAIN-SUFFIX,xboxone.com
  - DOMAIN-SUFFIX,xboxone.co
  - DOMAIN-SUFFIX,xboxone.eu
  - DOMAIN-SUFFIX,xboxab.com
  - DOMAIN-SUFFIX,xboxab.net
  - DOMAIN-SUFFIX,xbx.lv
  - DOMAIN-SUFFIX,renovacionxboxlive.com
