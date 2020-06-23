# ASUS-TUF B365M-Plus Gaming hackintosh-EFI OpenCore 0.59

# 配置清单: 
    i5 9400
    32G DDR4
    ASUS RX580 2304
    INTEL M.2 xxxx

Catalina 10.15.5 (19F101)

# BIOS需要关闭的都要关闭
    快速启动
    安全启动
    VT-D （虽然可以不关闭，不过这个直通好象macos也用不上）
    CSM
    Thunderbolt
    Intel SGX
    Intel Platform Trust
    CFG Lock

# 参考网站：
    OpenCore: https://dortania.github.io/OpenCore-Desktop-Guide/config.plist/coffee-lake.html
    ProperTree：https://github.com/corpnewt/ProperTree
    GenSMBIOS：https://github.com/corpnewt/GenSMBIOS

目前使用未发现问题
