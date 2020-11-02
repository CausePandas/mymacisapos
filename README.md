# mymacisapos
help me fix this thing please

panic(cpu 8 caller 0xffffff80096469aa): Kernel trap at 0xffffff8009628b94, type 14=page fault, registers:
CR0: 0x0000000080010033, CR2: 0x0000000000000040, CR3: 0x00000000657bd16d, CR4: 0x00000000003626e0
RAX: 0x000000000047dffe, RBX: 0x0000000000000000, RCX: 0x000000000000ffff, RDX: 0xffffff8032bc1240
RSP: 0xffffff92219b3dc0, RBP: 0xffffff92219b3e30, RSI: 0xffffff803e064a68, RDI: 0xffffff803f915520
R8:  0xffffff8042688b40, R9:  0xffffff8042688b60, R10: 0x0000000000000000, R11: 0x0000000000000000
R12: 0x0000000000000000, R13: 0x00000000657bd000, R14: 0x0000000000142796, R15: 0xffffff8032bc12c0
RFL: 0x0000000000010283, RIP: 0xffffff8009628b94, CS:  0x0000000000000008, SS:  0x0000000000000010
Fault CR2: 0x0000000000000040, Error code: 0x0000000000000000, Fault CPU: 0x8, PL: 1, VF: 0

Backtrace (CPU 8), Frame : Return Address
0xffffff92219b3820 : 0xffffff800951a65d 
0xffffff92219b3870 : 0xffffff8009654a75 
0xffffff92219b38b0 : 0xffffff80096465fe 
0xffffff92219b3900 : 0xffffff80094c0a40 
0xffffff92219b3920 : 0xffffff8009519d27 
0xffffff92219b3a20 : 0xffffff800951a117 
0xffffff92219b3a70 : 0xffffff8009cc1a6c 
0xffffff92219b3ae0 : 0xffffff80096469aa 
0xffffff92219b3c60 : 0xffffff80096466a8 
0xffffff92219b3cb0 : 0xffffff80094c0a40 
0xffffff92219b3cd0 : 0xffffff8009628b94 
0xffffff92219b3e30 : 0xffffff80095cdb4b 
0xffffff92219b3e70 : 0xffffff80095c44e8 
0xffffff92219b3f20 : 0xffffff8009a725be 
0xffffff92219b3f40 : 0xffffff8009b84be7 
0xffffff92219b3fa0 : 0xffffff80094c1206 

BSD process name corresponding to current thread: Google Chrome He

Mac OS version:
19H2

Kernel version:
Darwin Kernel Version 19.6.0: Mon Aug 31 22:12:52 PDT 2020; root:xnu-6153.141.2~1/RELEASE_X86_64
Kernel UUID: 05D51A3D-3A87-3FF0-98C3-9CF3827A3EDD
Kernel slide:     0x0000000009200000
Kernel text base: 0xffffff8009400000
__HIB  text base: 0xffffff8009300000
System model name: iMac19,2 (Mac-63001698E7A34814)
System shutdown begun: NO
Panic diags file available: YES (0x0)

System uptime in nanoseconds: 29334199798348
last loaded kext at 285810518341: @filesystems.msdosfs	1.10 (addr 0xffffff7f8e5d8000, size 69632)
last unloaded kext at 190207154675: >!ASMCRTC	1.0 (addr 0xffffff7f8b743000, size 28672)
loaded kexts:
com.shinywhitebox.iShowU-Audio-Capture	1.0.4
@filesystems.msdosfs	1.10
>!ATopCaseHIDEventDriver	3430.1
@fileutil	20.036.15
>AGPM	111.4.4
>X86PlatformShim	1.0.0
>!APlatformEnabler	2.7.0d0
@filesystems.autofs	3.0
>!AUpstreamUserClient	3.6.8
@kext.AMDFramebuffer	3.1.0
@kext.AMDRadeonX4000	3.1.0
>!AHDA	283.15
@kext.AMDRadeonServiceManager	3.1.0
>!A!IKBLGraphics	14.0.7
>AudioAUUC	1.70
>!AGraphicsDevicePolicy	5.2.6
>!A!IPCHPMC	2.0.1
>!A!ICFLGraphicsFramebuffer	14.0.7
@AGDCPluginDisplayMetrics	5.2.6
>!AThunderboltIP	3.1.4
>!AHV	1
|IOUserEthernet	1.0.1
|IO!BSerialManager	7.0.6f7
>pmtelemetry	1
@Dont_Steal_Mac_OS_X	7.0.0
@kext.AMD9500!C	3.1.0
>!ASMCLMU	212
>!AGFXHDA	100.1.429
>eficheck	1
>!A!ISlowAdaptiveClocking	4.0.0
>!AMCCSControl	1.14
>BCMWLANFirmware4364.Hashstore	1
>BCMWLANFirmware4377.Hashstore	1
>BCMWLANFirmware4355.Hashstore	1
>!AVirtIO	1.0
@filesystems.hfs.kext	522.100.5
@!AFSCompression.!AFSCompressionTypeDataless	1.0.0d1
@BootCache	40
@!AFSCompression.!AFSCompressionTypeZlib	1.0.0
>!ASDXC	1.7.7
|!ABCM5701Ethernet	10.3.5
>!ABCMWLANBusInterfacePCIe	1
@filesystems.apfs	1412.141.1
>!AAHCIPort	341.140.1
@private.KextAudit	1.0
>!ARTC	2.0
>!AACPIButtons	6.1
>!ASMBIOS	2.1
>!AACPIEC	6.1
>!AAPIC	1.7
$!AImage4	1
@nke.applicationfirewall	303
$TMSafetyNet	8
@!ASystemPolicy	2.0.0
|EndpointSecurity	1
>!AHIDKeyboard	209
>!AMultitouchDriver	3440.1
>!AInputDeviceSupport	3440.8
>!AHS!BDriver	3430.1
>IO!BHIDDriver	7.0.6f7
@kext.triggers	1.0
@kext.AMDRadeonX4400HWLibs	1.0
>DspFuncLib	283.15
@kext.OSvKernDSPLib	529
@kext.AMDRadeonX4000HWServices	3.1.0
>!AGraphicsControl	5.2.6
>!ASMBusPCI	1.0.14d1
|IOAccelerator!F2	438.7.3
|IOAVB!F	850.1
|IO!BHost!CUARTTransport	7.0.6f7
|IO!BHost!CTransport	7.0.6f7
|IO!B!F	7.0.6f7
|IO!BPacketLogger	7.0.6f7
@kext.AMDSupport	3.1.0
>!A!ILpssUARTv1	3.0.60
>!A!ILpssUARTCommon	3.0.60
>!AOnboardSerial	1.0
>!AHDA!C	283.15
|IOHDA!F	283.15
@!AGPUWrangler	5.2.6
@!AGraphicsDeviceControl	5.2.6
|IONDRVSupport	576.1
|IOSlowAdaptiveClocking!F	1.0.0
>X86PlatformPlugin	1.0.0
>IOPlatformPlugin!F	6.0.0d8
>!ASMBus!C	1.0.18d1
|IOGraphics!F	576.1
@plugin.IOgPTPPlugin	840.3
>usb.networking	5.0.0
>usb.!UHostCompositeDevice	1.2
|IOAudio!F	300.2
@vecLib.kext	1.2.0
|IOSurface	269.11
@filesystems.hfs.encodings.kext	1
>!AThunderboltPCIDownAdapter	2.5.4
>!AThunderboltDPInAdapter	6.2.6
>!AThunderboltDPAdapter!F	6.2.6
>!AHPM	3.4.4
>!A!ILpssI2C!C	3.0.60
>!A!ILpssDmac	3.0.60
>!A!ILpssI2C	3.0.60
>!AThunderboltNHI	5.8.6
|IOThunderbolt!F	7.6.1
|IOEthernetAVB!C	1.1.0
>!ABCMWLANCore	1.0.0
>mDNSOffloadUserClient	1.0.1b8
>IOImageLoader	1.0.0
|IOSerial!F	11
|IO80211!FV2	1200.12.2b1
>corecapture	1.0.4
|IOSkywalk!F	1
|IOAHCIBlock!S	316.100.5
|IONVMe!F	2.1.0
|IOUSB!F	900.4.2
|IOAHCI!F	290.0.1
>usb.!UXHCIPCI	1.2
>usb.!UXHCI	1.2
>!AEFINVRAM	2.1
>!AEFIRuntime	2.1
|IOSMBus!F	1.1
|IOHID!F	2.0.0
$quarantine	4
$sandbox	300.0
@kext.!AMatch	1.0.0d1
>DiskImages	493.0.0
>!AFDEKeyStore	28.30
>!AEffaceable!S	1.0
>!ASSE	1.0
>!AKeyStore	2
>!UTDM	489.120.1
|IOSCSIBlockCommandsDevice	422.120.3
>!ACredentialManager	1.0
>KernelRelayHost	1
>!ASEPManager	1.0.1
>IOSlaveProcessor	1
|IOUSBMass!SDriver	157.140.1
|IOSCSIArchitectureModel!F	422.120.3
|IO!S!F	2.1
|IOUSBHost!F	1.2
>!UHostMergeProperties	1.2
>usb.!UCommon	1.0
>!ABusPower!C	1.0
|CoreAnalytics!F	1
>!AMobileFileIntegrity	1.0.5
@kext.CoreTrust	1
|IOTimeSync!F	840.3
|IONetworking!F	3.4
|IOReport!F	47
>!AACPIPlatform	6.1
>!ASMC	3.1.9
>watchdog	1
|IOPCI!F	2.9
|IOACPI!F	1.4
@kec.pthread	1
@kec.corecrypto	1.0
@kec.Libm	1
