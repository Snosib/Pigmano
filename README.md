---- Minecraft Crash Report ----
// You're mean.

Time: 2024-03-13 15:09:07
Description: Unexpected error

java.lang.IllegalArgumentException: The stack count must be 1
	at net.minecraftforge.common.ForgeHooks.lambda$onCreativeModeTabBuildContents$17(ForgeHooks.java:1631) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading}
	at net.minecraft.world.item.CreativeModeTab$Output.accept(CreativeModeTab.java:414) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B}
	at net.citroncactus.pigmano.item.ModCreativeModeTabs.lambda$static$1(ModCreativeModeTabs.java:24) ~[main/:?] {re:classloading}
	at net.minecraftforge.common.ForgeHooks.onCreativeModeTabBuildContents(ForgeHooks.java:1629) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading}
	at net.minecraft.world.item.CreativeModeTab.buildContents(CreativeModeTab.java:129) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.item.CreativeModeTabs.lambda$buildAllTabContents$50(CreativeModeTabs.java:1696) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.accept(ForEachOps.java:183) ~[?:?] {}
	at java.util.stream.ReferencePipeline$2$1.accept(ReferencePipeline.java:179) ~[?:?] {}
	at java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?] {}
	at java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1845) ~[?:?] {}
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?] {}
	at java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:499) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp.evaluateSequential(ForEachOps.java:150) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.evaluateSequential(ForEachOps.java:173) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:234) ~[?:?] {}
	at java.util.stream.ReferencePipeline.forEach(ReferencePipeline.java:596) ~[?:?] {}
	at net.minecraft.world.item.CreativeModeTabs.buildAllTabContents(CreativeModeTabs.java:1695) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.item.CreativeModeTabs.tryRebuildTabContents(CreativeModeTabs.java:1710) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen.<init>(CreativeModeInventoryScreen.java:90) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.inventory.InventoryScreen.init(InventoryScreen.java:50) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.init(Screen.java:321) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.setScreen(Minecraft.java:1029) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.handleKeybinds(Minecraft.java:1975) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.tick(Minecraft.java:1842) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.runTick(Minecraft.java:1138) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.run(Minecraft.java:723) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at net.minecraftforge.fml.loading.targets.ForgeClientUserdevLaunchHandler.devService(ForgeClientUserdevLaunchHandler.java:19) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonDevLaunchHandler.lambda$makeService$7(CommonDevLaunchHandler.java:135) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Suspected Mod: 
	Pigmano (pigmano), Version: 0.1-1.20.1
		at TRANSFORMER/pigmano@0.1-1.20.1/net.citroncactus.pigmano.item.ModCreativeModeTabs.lambda$static$1(ModCreativeModeTabs.java:24)
Stacktrace:
	at net.minecraftforge.common.ForgeHooks.lambda$onCreativeModeTabBuildContents$17(ForgeHooks.java:1631) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23190%23197!/:?] {re:classloading}
	at net.minecraft.world.item.CreativeModeTab$Output.accept(CreativeModeTab.java:414) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B}
	at net.citroncactus.pigmano.item.ModCreativeModeTabs.lambda$static$1(ModCreativeModeTabs.java:24) ~[%23196!/:?] {re:classloading}
	at net.minecraftforge.common.ForgeHooks.onCreativeModeTabBuildContents(ForgeHooks.java:1629) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23190%23197!/:?] {re:classloading}
	at net.minecraft.world.item.CreativeModeTab.buildContents(CreativeModeTab.java:129) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.item.CreativeModeTabs.lambda$buildAllTabContents$50(CreativeModeTabs.java:1696) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.accept(ForEachOps.java:183) ~[?:?] {}
	at java.util.stream.ReferencePipeline$2$1.accept(ReferencePipeline.java:179) ~[?:?] {}
	at java.util.Iterator.forEachRemaining(Iterator.java:133) ~[?:?] {}
	at java.util.Spliterators$IteratorSpliterator.forEachRemaining(Spliterators.java:1845) ~[?:?] {}
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?] {}
	at java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:499) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp.evaluateSequential(ForEachOps.java:150) ~[?:?] {}
	at java.util.stream.ForEachOps$ForEachOp$OfRef.evaluateSequential(ForEachOps.java:173) ~[?:?] {}
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:234) ~[?:?] {}
	at java.util.stream.ReferencePipeline.forEach(ReferencePipeline.java:596) ~[?:?] {}
	at net.minecraft.world.item.CreativeModeTabs.buildAllTabContents(CreativeModeTabs.java:1695) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.world.item.CreativeModeTabs.tryRebuildTabContents(CreativeModeTabs.java:1710) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B}
	at net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen.<init>(CreativeModeInventoryScreen.java:90) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.inventory.InventoryScreen.init(InventoryScreen.java:50) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.init(Screen.java:321) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.setScreen(Minecraft.java:1029) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.handleKeybinds(Minecraft.java:1975) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar%23191!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
-- Affected level --
Details:
	All players: 1 total; [LocalPlayer['Dev'/205, l='ClientLevel', x=-99.53, y=66.00, z=91.73]]
	Chunk stats: 961, 609
	Level dimension: minecraft:overworld
	Level spawn location: World: (-64,69,16), Section: (at 0,5,0 in -4,4,1; chunk contains blocks -64,-64,16 to -49,319,31), Region: (-1,0; contains chunks -32,0 to -1,31, blocks -512,-64,0 to -1,319,511)
	Level time: 1994 game time, 1994 day time
	Server brand: forge
	Server type: Integrated singleplayer server
Stacktrace:
	at net.minecraft.client.multiplayer.ClientLevel.fillReportDetails(ClientLevel.java:470) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.fillReport(Minecraft.java:2381) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.run(Minecraft.java:745) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1.20.1-recomp.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at net.minecraftforge.fml.loading.targets.ForgeClientUserdevLaunchHandler.devService(ForgeClientUserdevLaunchHandler.java:19) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonDevLaunchHandler.lambda$makeService$7(CommonDevLaunchHandler.java:135) ~[fmlloader-1.20.1-47.2.20.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Last reload --
Details:
	Reload number: 1
	Reload reason: initial
	Finished: Yes
	Packs: vanilla, mod_resources

-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.8, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode, sharing), Oracle Corporation
	Memory: 417763408 bytes (398 MiB) / 1715470336 bytes (1636 MiB) up to 4253024256 bytes (4056 MiB)
	CPUs: 12
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz
	Identifier: Intel64 Family 6 Model 158 Stepping 10
	Microarchitecture: Coffee Lake
	Frequency (GHz): 2.59
	Number of physical packages: 1
	Number of physical CPUs: 6
	Number of logical CPUs: 12
	Graphics card #0 name: Intel(R) UHD Graphics 630
	Graphics card #0 vendor: Intel Corporation (0x8086)
	Graphics card #0 VRAM (MB): 1024.00
	Graphics card #0 deviceId: 0x3e9b
	Graphics card #0 versionInfo: DriverVersion=26.20.100.6911
	Graphics card #1 name: NVIDIA GeForce RTX 2060
	Graphics card #1 vendor: NVIDIA (0x10de)
	Graphics card #1 VRAM (MB): 4095.00
	Graphics card #1 deviceId: 0x1f15
	Graphics card #1 versionInfo: DriverVersion=31.0.15.4633
	Memory slot #0 capacity (MB): 8192.00
	Memory slot #0 clockSpeed (GHz): 2.67
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 8192.00
	Memory slot #1 clockSpeed (GHz): 2.67
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 22877.05
	Virtual memory used (MB): 17060.58
	Swap memory total (MB): 6656.00
	Swap memory used (MB): 321.48
	JVM Flags: 1 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump
	Launched Version: MOD_DEV
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: Intel(R) UHD Graphics 630 GL version 4.6.0 - Build 26.20.100.6911, Intel
	Window size: 1920x1001
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'; Server brand changed to 'forge'
	Type: Integrated Server (map_client.txt)
	Graphics mode: fancy
	Resource Packs: 
	Current Language: en_us
	CPU: 12x Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz
	Server Running: true
	Player Count: 1 / 8; [ServerPlayer['Dev'/205, l='ServerLevel[New World]', x=-99.53, y=66.00, z=91.73]]
	Data Packs: vanilla, mod:forge, mod:pigmano
	Enabled Feature Flags: minecraft:vanilla
	World Generation: Stable
	ModLauncher: 10.0.9+10.0.9+main.dcd20f30
	ModLauncher launch target: forgeclientuserdev
	ModLauncher naming: mcp
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.5.jar eventbus PLUGINSERVICE 
		fmlloader-1.20.1-47.2.20.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.20.1-47.2.20.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.20.1-47.2.20.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.20.1-47.2.20.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.20.1-47.2.20.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.9.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		lowcodefml@null
		javafml@null
	Mod List: 
		forge-1.20.1-47.2.20_mapped_parchment_2023.06.26-1|Minecraft                     |minecraft                     |1.20.1              |DONE      |Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		                                                  |Forge                         |forge                         |47.2.20             |DONE      |Manifest: NOSIGNATURE
		main                                              |Pigmano                       |pigmano                       |0.1-1.20.1          |DONE      |Manifest: NOSIGNATURE
	Crash Report UUID: 56943b0e-20ba-4ef6-bd35-c36326571b67
	FML: 47.2
	Forge: net.minecraftforge:47.2.20
