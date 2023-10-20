# reWriteMBR
Rewrite first 512 bytes MBR
1) Change (if need) and create binary data (512 bytes): nasm -f bin data.asm -o data.bin
   ![1 5](https://github.com/impr0ver/reWriteMBR/assets/146122577/f55812eb-a6a3-4269-bc42-df8271b7365c)
   ![2 2](https://github.com/impr0ver/reWriteMBR/assets/146122577/172c4fbc-b7fa-473b-b297-13f0928bf90c)

3) Run InstallMBR.exe via command promt with local admin privilegies 
   ![3](https://github.com/impr0ver/reWriteMBR/assets/146122577/0c117413-8c9f-47b1-ad6f-f4b5ea4aa6da)
4) After reboot VM you see a message
   ![4](https://github.com/impr0ver/reWriteMBR/assets/146122577/cfbf7443-40ef-4836-ab34-d4195769f4a3)


Attention. Run only on a virtual machine!!!

It can be detected by avs!
