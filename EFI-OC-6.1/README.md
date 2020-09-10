# BigSur 11 (20A5364e)
# ASUS-TUF B365M-Plus Gaming hackintosh-EFI OpenCore 0.61

 - 配置清单: 
   - Intel i5 9400
   - Kingston 8G DDR4 2666 * 4
   - ASUS RX580 2304
   - INTEL SSDPEKKW512G8
   - VX2478-4K-HD


- BIOS需要打开选项
  - VT-x
  - Above 4G decoding
  - Hyper-Threading
  - Execute Disable Bit
  - EHCI/XHCI Hand-off
  - OS type: Windows 8.1/10 UEFI Mode
  - DVMT Pre-Allocated(iGPU Memory): 64MB



- BIOS需要关闭的选项
  - Fast Boot
  - Secure Boot
  - VT-D （虽然可以不关闭，不过这个直通好象macos也用不上）
  - CSM
  - Thunderbolt
  - Intel SGX
  - Intel Platform Trust
  - CFG Lock



- 参考网站：
    - OpenCore: https://github.com/acidanthera/OpenCorePkg
    - OpenCoreGuide: https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html
    - ProperTree：https://github.com/corpnewt/ProperTree
    - GenSMBIOS：https://github.com/corpnewt/GenSMBIOS

## 目前使用中发现蓝牙异常
### 如何你使用了这EFI作为安装，那建议你把：ShowPicker 设置为true，否则你将会看不到启动菜单
