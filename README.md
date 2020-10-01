# Crash-Reports
crash reports
---- Minecraft Crash Report ----

WARNING: coremods are present:
  FMLLoadingPlugin (noclosemychat-v1.0.jar)
  FMLLoadingPlugin ([1.8+] Sk1er MouseBindFix-1.0.jar)
  ItemPatchingLoader (Itemphysics v1.3 1.8.9.jar)
  ModTweaker (Patcher-1.3 (1.8.9).jar)
  FMLLoadingPlugin (Sk1er Levelhead (1.8.9)-6.3.jar)
  PatcherTweaker (Patcher-1.3 (1.8.9).jar)
Contact their authors BEFORE contacting forge

// My bad.

Time: 10/1/20 11:17 AM
Description: There was a severe problem during mod loading that has caused the game to fail

net.minecraftforge.fml.common.LoaderException: java.lang.VerifyError: Bad local variable type
Exception Details:
  Location:
    net/minecraft/client/renderer/EntityRenderer.func_175068_a(IFJ)V @217: dload_3
  Reason:
    Type long (current frame, locals[3]) is not assignable to double
  Current Frame:
    bci: @217
    flags: { }
    locals: { 'net/minecraft/client/renderer/EntityRenderer', integer, float, long, long_2nd, integer, 'net/minecraft/client/renderer/RenderGlobal', 'net/minecraft/client/particle/EffectRenderer', integer, 'net/minecraft/client/renderer/culling/Frustum' }
    stack: { }
  Bytecode:
    0x0000000: b804 5336 0515 0599 0009 1b24 21b8 0673
    0x0000010: 2ab4 00db b402 0d3a 062a b400 dbb4 0677
    0x0000020: 3a07 2ab7 0679 3608 b806 7c2a b400 dbb4
    0x0000030: 021a 1306 7eb6 057e 1505 9900 1903 032a
    0x0000040: b400 dbb4 0165 2ab4 00db b401 68b8 0681
    0x0000050: a700 1603 032a b400 dbb4 0165 2ab4 00db
    0x0000060: b401 68b8 05a1 2a24 b706 8611 4100 b805
    0x0000070: b115 0599 0006 b806 892a b400 dbb4 021a
    0x0000080: 1306 8bb6 057e 2a24 1bb6 068d 1505 9900
    0x0000090: 0724 b806 902a b400 dbb4 01c4 2ab4 00db
    0x00000a0: b401 a3b4 03b1 05a0 0007 04a7 0004 03b8
    0x00000b0: 0694 2ab4 00db b402 1a13 0696 b605 7eb8
    0x00000c0: 069c 572a b400 dbb4 021a 1306 9eb6 057e
    0x00000d0: bb06 a059 b706 a13a 0929 b306 a62a b400
    0x00000e0: dbb6 0150 3a0a 190a b406 a919 0ab4 01cc
    0x00000f0: 190a b406 a967 248d 6b63 390b 190a b406
    0x0000100: ac19 0ab4 01cf 190a b406 ac67 248d 6b63
    0x0000110: 390d 190a b406 af19 0ab4 01d6 190a b406
    0x0000120: af67 248d 6b63 390f 1505 9900 1119 0918
    0x0000130: 0b18 0d18 0fb8 06b3 a700 0e19 0918 0b18
    0x0000140: 0d18 0fb6 06b6 b806 b99a 000f b806 bc9a
    0x0000150: 0009 b806 bf99 0096 b206 c29a 0090 2a02
    0x0000160: 24b7 06c5 2ab4 00db b402 1a13 06c7 b605
    0x0000170: 7e11 1701 b804 09b8 040c 2a24 04b7 0424
    0x0000180: 2ab4 00db b401 6586 2ab4 00db b401 6886
    0x0000190: 6e13 01b1 2ab4 00bf b804 2911 1700 b804
    0x00001a0: 0915 0599 0006 b806 ca19 0624 1bb6 06cd
    0x00001b0: 1505 9900 06b8 06d0 1117 01b8 0409 b804
    0x00001c0: 0c2a 2404 b704 242a b400 dbb4 0165 862a
    0x00001d0: b400 dbb4 0168 866e 1301 b12a b400 bfb8
    0x00001e0: 0429 1117 00b8 0409 a700 06b8 0654 2a03
    0x00001f0: 24b7 06c5 111d 01b8 06d3 190a b401 cf19
    0x0000200: 0ab6 01d3 8d63 1406 d42a b400 dbb4 01a3
    0x0000210: b406 d812 bd6a 8d63 989c 000b 2a19 0624
    0x0000220: 1bb7 06dc 2ab4 00db b402 1a13 06de b605
    0x0000230: 7e2a 0324 b706 c52a b400 dbb6 00e9 b206
    0x0000240: e3b6 0495 b806 e82a b400 dbb4 021a 1306
    0x0000250: eab6 057e 1505 9900 2619 0619 0a24 8d19
    0x0000260: 092a 59b4 00d9 5a04 60b5 00d9 2ab4 00db
    0x0000270: b401 c4b6 06ed b806 f1a7 0023 1906 190a
    0x0000280: 248d 1909 2a59 b400 d95a 0460 b500 d92a
    0x0000290: b400 dbb4 01c4 b606 edb6 06f5 1b99 0008
    0x00002a0: 1b05 a000 272a b400 dbb4 021a 1306 f7b6
    0x00002b0: 057e b206 fbb6 06fe 2ab4 00db b402 0d21
    0x00002c0: b607 02b2 06fb b607 052a b400 dbb4 021a
    0x00002d0: 1307 07b6 057e b207 0ab6 06fe 2ab4 00db
    0x00002e0: b401 a3b4 070d 9900 241b 9e00 202a b400
    0x00002f0: dbb4 021a 1307 0fb6 057e b807 122a b400
    0x0000300: dbb4 021a 1307 07b6 057e 1117 00b8 0409
    0x0000310: b804 5bb8 0715 1505 9900 06b8 0718 1906
    0x0000320: b207 1e24 8d1b 190a b607 2257 b806 6315
    0x0000330: 0599 0006 b807 2519 06b2 0728 248d 1b19
    0x0000340: 0ab6 0722 572a b400 dbb6 00e9 b206 e3b6
    0x0000350: 072c 0303 b907 3203 0015 0599 0006 b807
    0x0000360: 3519 06b2 0738 248d 1b19 0ab6 0722 572a
    0x0000370: b400 dbb6 00e9 b206 e3b6 072c b907 3b01
    0x0000380: 0015 0599 0006 b807 3eb2 070a b607 0511
    0x0000390: 1d00 b806 d311 0204 1301 ecb8 0587 2ab4
    0x00003a0: 00b2 9a01 0211 1700 b804 09b8 0479 b804
    0x00003b0: 5bb8 0741 2ab4 00db b402 1a13 0743 b605
    0x00003c0: 7eb2 0746 b601 4699 0014 b207 4604 bd00
    0x00003d0: 0459 0303 b805 b953 b803 8e19 0619 0a19
    0x00003e0: 0924 b607 4ab2 0746 b601 4699 0014 b207
    0x00003f0: 4604 bd00 0459 0302 b805 b953 b803 8eb8
    0x0000400: 06e8 2ab6 0476 1117 00b8 0409 b804 79b8
    0x0000410: 045b 2ab4 00db b402 35c6 008b 190a b203
    0x0000420: 1bb6 074e 9900 8015 0899 007b 190a c001
    0x0000430: 523a 11b8 0715 2ab4 00db b402 1a13 0750
    0x0000440: b605 7eb2 0753 b601 4699 003b b207 5310
    0x0000450: 06bd 0004 5903 1906 5359 0419 1153 5905
    0x0000460: 2ab4 00db b402 3553 5906 03b8 05b9 5359
    0x0000470: 0719 11b6 0756 5359 0824 b803 2553 b807
    0x0000480: 599a 0020 2ab4 00db b401 a3b4 0464 9a00
    0x0000490: 1319 0619 112a b400 dbb4 0235 0324 b607
    0x00004a0: 5db8 0663 1117 00b8 0409 b804 7915 0899
    0x00004b0: 0090 2ab4 00db b402 35c6 0086 190a b203
    0x00004c0: 1bb6 074e 9a00 7b19 0ac0 0152 3a11 b807
    0x00004d0: 152a b400 dbb4 021a 1307 50b6 057e b207
    0x00004e0: 53b6 0146 9900 3bb2 0753 1006 bd00 0459
    0x00004f0: 0319 0653 5904 1911 5359 052a b400 dbb4
    0x0000500: 0235 5359 0603 b805 b953 5907 1911 b607
    0x0000510: 5653 5908 24b8 0325 53b8 0759 9a00 202a
    0x0000520: b400 dbb4 01a3 b404 649a 0013 1906 1911
    0x0000530: 2ab4 00db b402 3503 24b6 075d b806 6319
    0x0000540: 06b4 0761 b907 6601 009a 0056 2ab4 00db
    0x0000550: b402 1a13 0768 b605 7eb8 063b 1103 0204
    0x0000560: 0403 b806 3e2a b400 dbb6 00e9 b206 e3b6
    0x0000570: 072c 0303 b907 3203 0019 06b8 076e b807
    0x0000580: 6eb6 0772 190a 24b6 0776 2ab4 00db b600
    0x0000590: e9b2 06e3 b607 2cb9 073b 0100 b806 5411
    0x00005a0: 0302 1103 0304 03b8 063e b806 542a b400
    0x00005b0: b29a 0056 2ab6 046a 2ab4 00db b402 1a13
    0x00005c0: 0778 b605 7e15 0599 0006 b807 7b19 0719
    0x00005d0: 0a24 b607 7fb8 06e8 2a03 24b7 06c5 2ab4
    0x00005e0: 00db b402 1a13 0781 b605 7e15 0599 0006
    0x00005f0: b807 8419 0719 0a24 b607 8715 0599 0006
    0x0000600: b807 8a2a b604 7603 b806 44b8 067c 2ab4
    0x0000610: 00db b402 1a13 078c b605 7e15 0599 0006
    0x0000620: b807 8f2a 24b6 0792 1505 9900 06b8 0795
    0x0000630: 04b8 0644 1906 190a 24b6 0798 1505 9900
    0x0000640: 0c2a 241b b807 9cb8 079f b806 54b8 067c
    0x0000650: 1103 0211 0303 0403 b806 3e11 0204 1301
    0x0000660: ecb8 0587 2a03 24b7 06c5 b806 3b03 b806
    0x0000670: 442a b400 dbb6 00e9 b206 e3b6 0495 111d
    0x0000680: 01b8 06d3 2ab4 00db b402 1a13 07a1 b605
    0x0000690: 7e15 0599 0006 b807 a419 06b2 07a7 248d
    0x00006a0: 1b19 0ab6 0722 5715 0599 0006 b807 aab2
    0x00006b0: 0746 b601 4699 0059 2ab4 00b2 9a00 52b8
    0x00006c0: 0741 2ab4 00db b402 1a13 0743 b605 7eb2
    0x00006d0: 0746 04bd 0004 5903 04b8 05b9 53b8 038e
    0x00006e0: 2ab4 00db b402 0d19 0a19 0924 b607 4a11
    0x00006f0: 0302 1103 0304 03b8 063e b207 4604 bd00
    0x0000700: 0459 0302 b805 b953 b803 8eb8 06e8 111d
    0x0000710: 00b8 06d3 04b8 0644 b806 7cb8 0654 b807
    0x0000720: ad19 0ab4 01cf 190a b601 d38d 6314 06d4
    0x0000730: 2ab4 00db b401 a3b4 06d8 12bd 6a8d 6397
    0x0000740: 9b00 182a b400 dbb4 021a 1307 afb6 057e
    0x0000750: 2a19 0624 1bb7 06dc b207 b2b6 0146 9900
    0x0000760: 262a b400 dbb4 021a 1307 b4b6 057e b207
    0x0000770: b205 bd00 0459 0319 0653 5904 24b8 0325
    0x0000780: 53b8 038e 2ab4 00db b402 1a13 07b6 b605
    0x0000790: 7e2a b400 dbb4 020d 241b b804 6136 1215
    0x00007a0: 129a 003d 2ab4 0098 9900 36b2 06c2 9a00
    0x00007b0: 3015 0599 000c 2a24 1bb8 07b9 b807 bc11
    0x00007c0: 0100 b805 b115 0599 000c 2a24 1bb8 07bf
    0x00007d0: a700 092a 241b b707 c12a 24b7 07c3 1505
    0x00007e0: 9900 06b8 07c6 b1                      
  Stackmap Table:
    append_frame(@16,Integer)
    append_frame(@83,Object[#527],Object[#1667],Integer)
    same_frame(@102)
    same_frame(@121)
    same_frame(@149)
    same_locals_1_stack_item_frame(@174,Object[#1074])
    full_frame(@175,{Object[#2],Integer,Float,Long,Integer,Object[#527],Object[#1667],Integer},{Object[#1074],Integer})
    full_frame(@315,{Object[#2],Integer,Float,Long,Integer,Object[#527],Object[#1667],Integer,Object[#1696],Object[#457],Double,Double,Double},{})
    same_frame(@326)
    same_frame(@344)
    same_frame_extended(@425)
    same_frame(@440)
    same_frame(@491)
    same_frame(@494)
    same_frame(@548)
    same_frame_extended(@636)
    same_frame(@668)
    same_frame(@677)
    same_frame(@713)
    same_frame_extended(@778)
    same_frame(@798)
    same_frame(@823)
    same_frame(@865)
    same_frame(@905)
    same_frame_extended(@987)
    same_frame(@1023)
    append_frame(@1156,Object[#338])
    same_frame(@1185)
    chop_frame(@1188,1)
    append_frame(@1311,Object[#338])
    same_frame(@1340)
    chop_frame(@1343,1)
    same_frame_extended(@1439)
    same_frame(@1485)
    same_frame(@1523)
    same_frame(@1539)
    same_frame(@1543)
    same_frame(@1571)
    same_frame(@1584)
    same_frame(@1610)
    same_frame_extended(@1689)
    same_frame(@1711)
    same_frame_extended(@1806)
    same_frame_extended(@1880)
    same_frame(@1924)
    append_frame(@1983,Top,Integer)
    same_frame(@2003)
    same_frame(@2009)
    same_frame(@2014)
    same_frame(@2022)

	at net.minecraftforge.fml.common.LoadController.transition(LoadController.java:162)
	at net.minecraftforge.fml.common.Loader.preinitializeMods(Loader.java:551)
	at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:240)
	at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:417)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:329)
	at net.minecraft.client.main.Main.main(SourceFile:124)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)
Caused by: java.lang.VerifyError: Bad local variable type
Exception Details:
  Location:
    net/minecraft/client/renderer/EntityRenderer.func_175068_a(IFJ)V @217: dload_3
  Reason:
    Type long (current frame, locals[3]) is not assignable to double
  Current Frame:
    bci: @217
    flags: { }
    locals: { 'net/minecraft/client/renderer/EntityRenderer', integer, float, long, long_2nd, integer, 'net/minecraft/client/renderer/RenderGlobal', 'net/minecraft/client/particle/EffectRenderer', integer, 'net/minecraft/client/renderer/culling/Frustum' }
    stack: { }
  Bytecode:
    0x0000000: b804 5336 0515 0599 0009 1b24 21b8 0673
    0x0000010: 2ab4 00db b402 0d3a 062a b400 dbb4 0677
    0x0000020: 3a07 2ab7 0679 3608 b806 7c2a b400 dbb4
    0x0000030: 021a 1306 7eb6 057e 1505 9900 1903 032a
    0x0000040: b400 dbb4 0165 2ab4 00db b401 68b8 0681
    0x0000050: a700 1603 032a b400 dbb4 0165 2ab4 00db
    0x0000060: b401 68b8 05a1 2a24 b706 8611 4100 b805
    0x0000070: b115 0599 0006 b806 892a b400 dbb4 021a
    0x0000080: 1306 8bb6 057e 2a24 1bb6 068d 1505 9900
    0x0000090: 0724 b806 902a b400 dbb4 01c4 2ab4 00db
    0x00000a0: b401 a3b4 03b1 05a0 0007 04a7 0004 03b8
    0x00000b0: 0694 2ab4 00db b402 1a13 0696 b605 7eb8
    0x00000c0: 069c 572a b400 dbb4 021a 1306 9eb6 057e
    0x00000d0: bb06 a059 b706 a13a 0929 b306 a62a b400
    0x00000e0: dbb6 0150 3a0a 190a b406 a919 0ab4 01cc
    0x00000f0: 190a b406 a967 248d 6b63 390b 190a b406
    0x0000100: ac19 0ab4 01cf 190a b406 ac67 248d 6b63
    0x0000110: 390d 190a b406 af19 0ab4 01d6 190a b406
    0x0000120: af67 248d 6b63 390f 1505 9900 1119 0918
    0x0000130: 0b18 0d18 0fb8 06b3 a700 0e19 0918 0b18
    0x0000140: 0d18 0fb6 06b6 b806 b99a 000f b806 bc9a
    0x0000150: 0009 b806 bf99 0096 b206 c29a 0090 2a02
    0x0000160: 24b7 06c5 2ab4 00db b402 1a13 06c7 b605
    0x0000170: 7e11 1701 b804 09b8 040c 2a24 04b7 0424
    0x0000180: 2ab4 00db b401 6586 2ab4 00db b401 6886
    0x0000190: 6e13 01b1 2ab4 00bf b804 2911 1700 b804
    0x00001a0: 0915 0599 0006 b806 ca19 0624 1bb6 06cd
    0x00001b0: 1505 9900 06b8 06d0 1117 01b8 0409 b804
    0x00001c0: 0c2a 2404 b704 242a b400 dbb4 0165 862a
    0x00001d0: b400 dbb4 0168 866e 1301 b12a b400 bfb8
    0x00001e0: 0429 1117 00b8 0409 a700 06b8 0654 2a03
    0x00001f0: 24b7 06c5 111d 01b8 06d3 190a b401 cf19
    0x0000200: 0ab6 01d3 8d63 1406 d42a b400 dbb4 01a3
    0x0000210: b406 d812 bd6a 8d63 989c 000b 2a19 0624
    0x0000220: 1bb7 06dc 2ab4 00db b402 1a13 06de b605
    0x0000230: 7e2a 0324 b706 c52a b400 dbb6 00e9 b206
    0x0000240: e3b6 0495 b806 e82a b400 dbb4 021a 1306
    0x0000250: eab6 057e 1505 9900 2619 0619 0a24 8d19
    0x0000260: 092a 59b4 00d9 5a04 60b5 00d9 2ab4 00db
    0x0000270: b401 c4b6 06ed b806 f1a7 0023 1906 190a
    0x0000280: 248d 1909 2a59 b400 d95a 0460 b500 d92a
    0x0000290: b400 dbb4 01c4 b606 edb6 06f5 1b99 0008
    0x00002a0: 1b05 a000 272a b400 dbb4 021a 1306 f7b6
    0x00002b0: 057e b206 fbb6 06fe 2ab4 00db b402 0d21
    0x00002c0: b607 02b2 06fb b607 052a b400 dbb4 021a
    0x00002d0: 1307 07b6 057e b207 0ab6 06fe 2ab4 00db
    0x00002e0: b401 a3b4 070d 9900 241b 9e00 202a b400
    0x00002f0: dbb4 021a 1307 0fb6 057e b807 122a b400
    0x0000300: dbb4 021a 1307 07b6 057e 1117 00b8 0409
    0x0000310: b804 5bb8 0715 1505 9900 06b8 0718 1906
    0x0000320: b207 1e24 8d1b 190a b607 2257 b806 6315
    0x0000330: 0599 0006 b807 2519 06b2 0728 248d 1b19
    0x0000340: 0ab6 0722 572a b400 dbb6 00e9 b206 e3b6
    0x0000350: 072c 0303 b907 3203 0015 0599 0006 b807
    0x0000360: 3519 06b2 0738 248d 1b19 0ab6 0722 572a
    0x0000370: b400 dbb6 00e9 b206 e3b6 072c b907 3b01
    0x0000380: 0015 0599 0006 b807 3eb2 070a b607 0511
    0x0000390: 1d00 b806 d311 0204 1301 ecb8 0587 2ab4
    0x00003a0: 00b2 9a01 0211 1700 b804 09b8 0479 b804
    0x00003b0: 5bb8 0741 2ab4 00db b402 1a13 0743 b605
    0x00003c0: 7eb2 0746 b601 4699 0014 b207 4604 bd00
    0x00003d0: 0459 0303 b805 b953 b803 8e19 0619 0a19
    0x00003e0: 0924 b607 4ab2 0746 b601 4699 0014 b207
    0x00003f0: 4604 bd00 0459 0302 b805 b953 b803 8eb8
    0x0000400: 06e8 2ab6 0476 1117 00b8 0409 b804 79b8
    0x0000410: 045b 2ab4 00db b402 35c6 008b 190a b203
    0x0000420: 1bb6 074e 9900 8015 0899 007b 190a c001
    0x0000430: 523a 11b8 0715 2ab4 00db b402 1a13 0750
    0x0000440: b605 7eb2 0753 b601 4699 003b b207 5310
    0x0000450: 06bd 0004 5903 1906 5359 0419 1153 5905
    0x0000460: 2ab4 00db b402 3553 5906 03b8 05b9 5359
    0x0000470: 0719 11b6 0756 5359 0824 b803 2553 b807
    0x0000480: 599a 0020 2ab4 00db b401 a3b4 0464 9a00
    0x0000490: 1319 0619 112a b400 dbb4 0235 0324 b607
    0x00004a0: 5db8 0663 1117 00b8 0409 b804 7915 0899
    0x00004b0: 0090 2ab4 00db b402 35c6 0086 190a b203
    0x00004c0: 1bb6 074e 9a00 7b19 0ac0 0152 3a11 b807
    0x00004d0: 152a b400 dbb4 021a 1307 50b6 057e b207
    0x00004e0: 53b6 0146 9900 3bb2 0753 1006 bd00 0459
    0x00004f0: 0319 0653 5904 1911 5359 052a b400 dbb4
    0x0000500: 0235 5359 0603 b805 b953 5907 1911 b607
    0x0000510: 5653 5908 24b8 0325 53b8 0759 9a00 202a
    0x0000520: b400 dbb4 01a3 b404 649a 0013 1906 1911
    0x0000530: 2ab4 00db b402 3503 24b6 075d b806 6319
    0x0000540: 06b4 0761 b907 6601 009a 0056 2ab4 00db
    0x0000550: b402 1a13 0768 b605 7eb8 063b 1103 0204
    0x0000560: 0403 b806 3e2a b400 dbb6 00e9 b206 e3b6
    0x0000570: 072c 0303 b907 3203 0019 06b8 076e b807
    0x0000580: 6eb6 0772 190a 24b6 0776 2ab4 00db b600
    0x0000590: e9b2 06e3 b607 2cb9 073b 0100 b806 5411
    0x00005a0: 0302 1103 0304 03b8 063e b806 542a b400
    0x00005b0: b29a 0056 2ab6 046a 2ab4 00db b402 1a13
    0x00005c0: 0778 b605 7e15 0599 0006 b807 7b19 0719
    0x00005d0: 0a24 b607 7fb8 06e8 2a03 24b7 06c5 2ab4
    0x00005e0: 00db b402 1a13 0781 b605 7e15 0599 0006
    0x00005f0: b807 8419 0719 0a24 b607 8715 0599 0006
    0x0000600: b807 8a2a b604 7603 b806 44b8 067c 2ab4
    0x0000610: 00db b402 1a13 078c b605 7e15 0599 0006
    0x0000620: b807 8f2a 24b6 0792 1505 9900 06b8 0795
    0x0000630: 04b8 0644 1906 190a 24b6 0798 1505 9900
    0x0000640: 0c2a 241b b807 9cb8 079f b806 54b8 067c
    0x0000650: 1103 0211 0303 0403 b806 3e11 0204 1301
    0x0000660: ecb8 0587 2a03 24b7 06c5 b806 3b03 b806
    0x0000670: 442a b400 dbb6 00e9 b206 e3b6 0495 111d
    0x0000680: 01b8 06d3 2ab4 00db b402 1a13 07a1 b605
    0x0000690: 7e15 0599 0006 b807 a419 06b2 07a7 248d
    0x00006a0: 1b19 0ab6 0722 5715 0599 0006 b807 aab2
    0x00006b0: 0746 b601 4699 0059 2ab4 00b2 9a00 52b8
    0x00006c0: 0741 2ab4 00db b402 1a13 0743 b605 7eb2
    0x00006d0: 0746 04bd 0004 5903 04b8 05b9 53b8 038e
    0x00006e0: 2ab4 00db b402 0d19 0a19 0924 b607 4a11
    0x00006f0: 0302 1103 0304 03b8 063e b207 4604 bd00
    0x0000700: 0459 0302 b805 b953 b803 8eb8 06e8 111d
    0x0000710: 00b8 06d3 04b8 0644 b806 7cb8 0654 b807
    0x0000720: ad19 0ab4 01cf 190a b601 d38d 6314 06d4
    0x0000730: 2ab4 00db b401 a3b4 06d8 12bd 6a8d 6397
    0x0000740: 9b00 182a b400 dbb4 021a 1307 afb6 057e
    0x0000750: 2a19 0624 1bb7 06dc b207 b2b6 0146 9900
    0x0000760: 262a b400 dbb4 021a 1307 b4b6 057e b207
    0x0000770: b205 bd00 0459 0319 0653 5904 24b8 0325
    0x0000780: 53b8 038e 2ab4 00db b402 1a13 07b6 b605
    0x0000790: 7e2a b400 dbb4 020d 241b b804 6136 1215
    0x00007a0: 129a 003d 2ab4 0098 9900 36b2 06c2 9a00
    0x00007b0: 3015 0599 000c 2a24 1bb8 07b9 b807 bc11
    0x00007c0: 0100 b805 b115 0599 000c 2a24 1bb8 07bf
    0x00007d0: a700 092a 241b b707 c12a 24b7 07c3 1505
    0x00007e0: 9900 06b8 07c6 b1                      
  Stackmap Table:
    append_frame(@16,Integer)
    append_frame(@83,Object[#527],Object[#1667],Integer)
    same_frame(@102)
    same_frame(@121)
    same_frame(@149)
    same_locals_1_stack_item_frame(@174,Object[#1074])
    full_frame(@175,{Object[#2],Integer,Float,Long,Integer,Object[#527],Object[#1667],Integer},{Object[#1074],Integer})
    full_frame(@315,{Object[#2],Integer,Float,Long,Integer,Object[#527],Object[#1667],Integer,Object[#1696],Object[#457],Double,Double,Double},{})
    same_frame(@326)
    same_frame(@344)
    same_frame_extended(@425)
    same_frame(@440)
    same_frame(@491)
    same_frame(@494)
    same_frame(@548)
    same_frame_extended(@636)
    same_frame(@668)
    same_frame(@677)
    same_frame(@713)
    same_frame_extended(@778)
    same_frame(@798)
    same_frame(@823)
    same_frame(@865)
    same_frame(@905)
    same_frame_extended(@987)
    same_frame(@1023)
    append_frame(@1156,Object[#338])
    same_frame(@1185)
    chop_frame(@1188,1)
    append_frame(@1311,Object[#338])
    same_frame(@1340)
    chop_frame(@1343,1)
    same_frame_extended(@1439)
    same_frame(@1485)
    same_frame(@1523)
    same_frame(@1539)
    same_frame(@1543)
    same_frame(@1571)
    same_frame(@1584)
    same_frame(@1610)
    same_frame_extended(@1689)
    same_frame(@1711)
    same_frame_extended(@1806)
    same_frame_extended(@1880)
    same_frame(@1924)
    append_frame(@1983,Top,Integer)
    same_frame(@2003)
    same_frame(@2009)
    same_frame(@2014)
    same_frame(@2022)

	at java.lang.Class.getDeclaredFields0(Native Method)
	at java.lang.Class.privateGetDeclaredFields(Class.java:2583)
	at java.lang.Class.getDeclaredField(Class.java:2068)
	at com.orangemarshall.animations.util.FieldWrapper.<init>(FieldWrapper.java:22)
	at com.orangemarshall.animations.BlockhitAnimation.<clinit>(BlockhitAnimation.java:71)
	at com.orangemarshall.animations.proxy.ClientProxy.preInit(ClientProxy.java:20)
	at com.orangemarshall.animations.Animations.preInit(Animations.java:37)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraftforge.fml.common.FMLModContainer.handleModStateEvent(FMLModContainer.java:560)
	at sun.reflect.GeneratedMethodAccessor2.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74)
	at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47)
	at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322)
	at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304)
	at com.google.common.eventbus.EventBus.post(EventBus.java:275)
	at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:211)
	at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:189)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74)
	at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47)
	at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322)
	at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304)
	at com.google.common.eventbus.EventBus.post(EventBus.java:275)
	at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:118)
	at net.minecraftforge.fml.common.Loader.preinitializeMods(Loader.java:548)
	... 10 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- System Details --
Details:
	Minecraft Version: 1.8.9
	Operating System: Windows 10 (amd64) version 10.0
	CPU: 4x Intel(R) Core(TM) i3-5005U CPU @ 2.00GHz
	Java Version: 1.8.0_51, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 2759299624 bytes (2631 MB) / 3186360320 bytes (3038 MB) up to 3186360320 bytes (3038 MB)
	JVM Flags: 6 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx3G -Xms3G -XX:+UseConcMarkSweepGC -XX:+CMSIncrementalMode -XX:-UseAdaptiveSizePolicy
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	FML: MCP 9.19 Powered by Forge 11.15.0.1684 Optifine OptiFine_1.8.9_HD_U_I3 28 mods loaded, 27 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
	UCH	mcp{9.18} [Minecraft Coder Pack] (minecraft.jar) 
	UCH	FML{8.0.99.99} [Forge Mod Loader] (forge-1.8.9-11.15.0.1684.jar) 
	UCH	Forge{11.15.0.1684} [Minecraft Forge] (forge-1.8.9-11.15.0.1684.jar) 
	UCH	itemphysic{1.3.0} [ItemPhysic] (minecraft.jar) 
	UCH	LEVEL_HEAD{6.3} [Sk1er Level Head] (minecraft.jar) 
	UCH	ingameserverswitcher{1.0} [Ingame Server Switcher] ((1.8.9) IngameServerSwitcher.jar) 
	UCH	canelexkeystrokes{1.0} [Canelex Keystrokes] ((1.8.9) canelex3keystrokes.jar) 
	UCH	coordsmod{1.0} [CoordsMod] ([1.8.9] CoordsMod.jar) 
	UCH	sidebarmod{1.01} [SidebarMod] ([1.8.9]SidebarMod-1.01.jar) 
	UCH	perspectivemod{1.0} [Perspective Mod] ([1.8.9] Perspective Mod [fix2].jar) 
	UCH	autogg{2.0.4} [Auto GG] (AutoGG-2.0.4 (1.8.9).jar) 
	UCH	blockoverlay{3.2} [Block Overlay] (Block_Overlay_3.2.jar) 
	UCH	autotip{3.0} [Autotip] (Autotip-3.0 [1.8-1.12.2].jar) 
	UCH	foamfix{@VERSION@} [FoamFix] (FoamFixUnofficial-1.8.9-0.6.3-Lawful.jar) 
	UCH	resourceexploitfix{1.0.2} [Resource Exploit Fix] (Resource.Exploit.Fix-1.0.2.jar) 
	UCH	namehistory{1.1} [Player Name History Checker] (NameHistory-1.8.9-v1.1.jar) 
	UCH	{1.0} [] (NuploxTexturePack Fixer 1.8.9.jar) 
	UCH	IngameAccountSwitcher{7.0.1} [In-Game Account Switcher] (InGameAccountSwitcher-Forge-1.8.9-7.0.1.jar) 
	UCH	timechanger1.8{1.0} [TimeChanger 1.8] (TimeChanger-.1.8.9.jar) 
	UCH	TcpNoDelayMod{1.0} [TcpNoDelayMod] (Lowkey2.0.jar) 
	UCH	FpsReducer{mc1.8.9-1.10.3} [FPS Reducer] (FPS-Reducer-Mod-1.8.9.jar) 
	UCH	publictogglechat{2.1.0} [§6Hypixel §7-§a ToggleChat] (ToggleChat-2.1.0-SNAPSHOT.jar) 
	UCH	orangesimplemod{1.0} [orangesimplemod] (Orange's Simple Mods-1.2.jar) 
	UCH	quickplay{2.0.3} [Quickplay] (Quickplay-1.8.9-2.0.3.jar) 
	UCE	animations{5.3} [Orange's 1.7 Animations] (Old-Animations-Mod-1.8.9.jar) 
	UCH	patcher{1.3} [Patcher] (Patcher-1.3 (1.8.9).jar) 
	UCH	modcore{0.1.43} [ModCore] (Sk1er Modcore-0.1.43 (1.8.9).jar) 
	UD	mousebindfix{1.0} [Mouse Bind Fix] (minecraft.jar) 
	Loaded coremods (and transformers): 
FMLLoadingPlugin (noclosemychat-v1.0.jar)
  com.cecer1.noclosemychat.asm.NoCloseMyChatTransformer
FMLLoadingPlugin ([1.8+] Sk1er MouseBindFix-1.0.jar)
  club.sk1er.mods.mousefix.forge.ClassTransformer
ItemPatchingLoader (Itemphysics v1.3 1.8.9.jar)
  com.creativemd.itemphysic.ItemTransformer
ModTweaker (Patcher-1.3 (1.8.9).jar)
  club.sk1er.patcher.tweaker.other.ModClassTransformer
FMLLoadingPlugin (Sk1er Levelhead (1.8.9)-6.3.jar)
  club.sk1er.mods.levelhead.forge.transform.ClassTransformer
PatcherTweaker (Patcher-1.3 (1.8.9).jar)
  club.sk1er.mods.core.forge.ClassTransformer
  club.sk1er.patcher.tweaker.ClassTransformer
	GL info: ' Vendor: 'Intel' Version: '4.4.0 - Build 20.19.15.4835' Renderer: 'Intel(R) HD Graphics 5500'
