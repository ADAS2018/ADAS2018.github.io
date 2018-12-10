---
layout:     post
title:      "商户通APP使用注意事项"
subtitle:   "商户通进件APP进件过程常见问题的解决方法"
date:       2018-12-07 17:20:41
author:     "soaringsoul"
header-img: "img/iphone.jpg"
catalog: true
tags:
    - 商户通
---





# 商户通进件APP进件过程常见问题的解决方法

## 常见问题1: 移动运营商无法认证

![mobile_authenticate](G:\AdasFinTech.github.io\img\shanghutong\mobile_authenticate.png)



* **可能的原因**:

  * 手机号为企业版的手机号
  * 网络不稳定导致认证失败

* **解决方法**

  * 首先核实当前认证的手机号码是否为企业版的手机号，如果确认手机号为企业版的手机号，请换用个人版的手机号重新申请并认证

  * 若确认手机是个人类型的手机号，则尝试重新进行认证，若仍认证失败，点击`下一步`按钮下的`认证失败？请点这里`再次进行认证。

  * 如果仍认证失败，请联系我们的客服人员。

    ![sgt_mobile](G:\AdasFinTech.github.io\img\shanghutong\sgt_mobile.jpg)

## Q: I can't use the import feature for uploading a JSON file! The window keeps closing when I try to select a file!

* **Cause**: This is a known bug in Google Chrome / Firefox that appears in Ubuntu and some Windows builds.
* **Solution**: 
  * For Google Chrome: A good workaround is to open the extension url, chrome-extension://nkbihfbeogaeaoehlefnkodbefgpgknn/popup.html, directly in a new tab and import through the tab.
  * For Firefox:
    1. Open `about:debugging` in a new tab
    2. Scroll down and find the Metamask {Internal UUID} (e.g. 12324c61-abc2-4922-a325-012697643ff5)
    3. Open `moz-extension://{Internal UUID}/popup.html` in a new tab and import through the tab