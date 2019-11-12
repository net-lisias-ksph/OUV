# Orbital Utility Vehicle :: Change Log

* 2019-0604: 1.3.0.1 (linuxgurugamer) for KSP 1.7.0 PRE-RELEASE
	+ All these changes have been done by forum user @zer0kerbal
	+ KERBALCHANGELOG
				- showChangelog = True
				- modName = OrbitalTug
				- VERSION
						- version = 0.13
						- change =
						- change = [DONE] fwdAdaptor: adjusted Attachment node(s) placement
						- change = [DONE] fwdAdaptor: if B9PartSwitch installed, set up  node switch
						- change - [NEW] fwdAdaptor: add inside pole nodes
						- change = [DONE] adaptorCarrier: adjusted Attachment node(s) placement
						- change = [DONE] adaptorCarrier: if B9PartSwitch installed, set up  node switch
						- change ﻿= [NEW] adaptorCarrier: add inside pole nodes
						- change = [DONE] OrbitalTugPod: verified node orientation
						- change = [WIP][BUG 0.12a] OrbitalTugPod: light adjusting only one thing (cabin) and not the spotlights
						- change = [WIP] OrbitalTugPod: KAS Winch adjustments
						- change = [DONE][BUG 0.12a] dronePod: not showing up in editor ... missing 6 commas
						- change = [WIP] grapplerJr: KAS winch
						- change = [WIP] grapplerJr: Nodes - 3/2/0 engine node; generic misc placement
						- change = [WIP] grapplerJr:
						- change = [NEW] fwdAdapter: merge in separate patch to adjust node orientation
						- change = [NEW] adaptorCarrier: merge in separate patch to adjust node orientation
				- VERSION
						- version = 0.12
						- change = [DONE] fwdAdaptor, adaptorCarrier: split into two
						- change = fwdAdaptor: adjusted Attachment node(s) placement
						- change = [WIP]fwdAdaptor: if B9PartSwitch installed, set up  node switch
						- change = adaptorCarrier: adjusted Attachment node(s) placement
						- change = [WIP]adaptorCarrier: if B9PartSwitch installed, set up  node switch
						- change = [DONE] OrbitalTugPod: adjusted Attachment node(s) placement
						- change = [BUG 0.12a] OrbitalTugPod: light adjusting only one thing (cabin) and not the spotlights
						- change = [WIP]OrbitalTugPod: KAS Winch adjustments
						- change = dronePod: adjusted Attachment node(s) placement
						- change = [BUG 0.12b] dronePod: not showing up in editor ... bringing out the can of RAID.
						- change = dronePod: Bill and Bob each had a nodeDazzler Glue Gun....
						- change = [NEW] grapplerJr: KAS winch
						- change = [NEW] grapplerJr: Nodes
						- change = [NEW] grapplerJr:
				- VERSION
						- version = 0.11
						- change = intial beta
						- change = Removed bugs
						- change = TugCore: add attachment nodes
						- change = TugCore: if B9PartSwitch installed, set up 4/2/0 node switch
						- change = TugCore: change node size from 2 to 1 to match rest of parts
						- change = engineOnArm: Add Attachment nodes
						- change = engineOnArm: Correct attachRules to allow node attachment
						- change = engineOnArm: if B9PartSwitch installed, set up 3/1 node switch
						- change = engineOnArm: added stackSymmetry
						- change = helperDrone: Add Attachment nodes
						- change = helperDrone: Correct attachRules to allow node attachment
						- change = helperDrone: if B9PartSwitch installed, set up 2/1 node switch
						- change = DronePod: Add Attachment nodes
						- change = DronePod: Correct attachRules to allow node attachment
						- change = DronePod: if B9PartSwitch installed, set up 7/5/3/1 node switch
						- change = OrbitalTugPod: Add Attachment nodes
						- change = [DONE] OrbitalTugPod: Correct attachRules to allow node attachment
						- change = OrbitalTugPod: if B9PartSwitch installed, set up 7/5/3/1 node switch
						- change = [DONE] fwdAdaptor, adaptorCarrier: correct node orientation
						- change = [DONE] fwdAdaptor, adaptorCarrier: Correct attachRules to allow node attachment
						- change = [NEW] fwdAdaptor, adaptorCarrier: might need to split into two, if not merge
						- change = [NEW] fwdAdaptor, adaptorCarrier: add Attachment nodes
						- change = [NEW] fwdAdaptor, adaptorCarrier: if B9PartSwitch installed, set up  node switch
						- change = [NEW] grapplerJr: Add Attachment nodes
						- change = [NEW] grapplerJr: Correct attachRules to allow node attachment
						- change = [NEW] grapplerJr: if B9PartSwitch installed, set up  node switch
				- VERSION
						- version = 0.10
						- change = Initial Commit
* 2019-0524: 1.3.0 (linuxgurugamer) for KSP 0.7.3 PRE-RELEASE
	+ Merged patches by @Deimos Rast and @LeLeon
	+ Merged patch by @Starwaster
	+ Added B9PartSwitcher code, will be primary if it's there
	+ Added jenkins.txt
	+ Added .version file
	+ New branch made to separate patches from parts as a test
* 2018-1202: 1.2.5.1 (Starwaster) for KSP 1.5.1
	+ Fixed texture used by internals
* 2018-1201: 1.2.5 (Starwaster) for KSP 1.5.1
	+ Fixed issues with parts not compiling with KSP 1.5.1
	+ Changed mod file structure; mod folder moved to GameData so unpack contents to KSP root folder.
* 2016-0524: 1.2.4 (nli2work) for KSP 1.1.2
	+ fixed config issues for push adaptors
	+ fixed reversing navball on command pod after switching away then back.
	+ adjusted some configs on staging may improve useability.
* 2016-0523: 1.2.3 (nli2work) for KSP 1.1.2
	+ fixed some scale issues with Grappler JR.
	+ adjusted arm geometry for shorter reach.
	+ adjusted command seat ejection angle to avoid teleporting kerbal.
* 2016-0522: 1.2.2 (nli2work) for KSP 1.1.2
	+ fixed config error prevented stack attachment to Grappler Jr.
* 2016-0521: 1.2.1 (nli2work) for KSP 1.1.2
	+ adjusted Grappler JR grapple angle to +/- 60 degrees.
	+ added EVA tether (KAS winch) for Grappler JR. part; will load if KAS present
	+ added top stack node for attaching command parts instead of using external command seat.
	+ specified controlTransforms for all docking/grappler parts, should be transparent in game.
* 2016-0515: 1.2 (nli2work) for KSP 1.1.2
	+ new Grappler Jr. Service Bay w/ Grappler Arm w/ External Command seat.
	+ added JSIAdvTransparentPod support.
* 2016-0505: 1.1.1 (nli2work) for KSP 1.1.2
	+ maintenance update for KSP 1.1.2
	+ adjustment for some dragCubes
	+ Config and Texture adjustments for KIS/KAS and JSIAdvTransparentPod
* 2016-0424: 1.1 (nli2work) for KSP 1.1
	+ maintenance update for KSP 1.1
	+ Adjusted Service Bay for more space.
	+ Firespitter no longer required. Texture and fuel switch with ModuleManager.
	+ Some additional surface attach area for Adaptor/Carrier
* 2016-0329: 1.0.9.1 (nli2work) for KSP 1.0.5
	+ Fixed some collider issues, for carrier adaptor, where you can become stuck on Size 1 Docking Port after grabbing with perfect alignment.
	+ Added visual indicator for the carrier adaptor, and orientation switcher (for when you use it with Drone or Command Pod). Red=Left; Green=Right; Yellow=Up.
* 2016-0328: 1.0.9 (nli2work) for KSP 1.0.5
	+ Grabber Core reduced SAS to 20; Increased max RCS power to 15 w/ default RCS power at 5%
	+ Helper Drones, remote drones with integrated RCS to help maneuver large objects. Max RCS power 8; default power at 10%.
	+ Adaptor Carrier, transitional part, Forward grabber unit, carriage compartment for up to 4 Helper Drones, 160 Mono capacity. Adjusted RCS thruster locations reduce torque while translating with RCS.
	+ Added indicator for engine reverse thrust  mode.
	+ Foward Adaptor, with service bay, will be phased out in another update or two.
* 2016-0315: 1.0.8 (nli2work) for KSP 1.0.5
	+ Small useability update: Adjusted attachment areas on Adaptor. Indicator icons display Docking or Grappling mode. Visible from outside and IVA
* 2016-0313: 1.0.7 (nli2work) for KSP 1.0.5
	+ Fixed Push Adaptor Docking Port, now docks any ports of node type size1, 2, or 3. Docking port also works as grappler node, be sure to "Release" before attempting to grab. Thsi grappler unit has very narrow tolerances for alignment and very low pivot range, plan accordingly.
	+ Fixed Command pod KAS variant, nose winch now ejects correctly without being blocked.
	+ Lowered Push Adaptor's RCS thrust to 3.
	+ Nuclear Engine now fueled by LF or Mono.
* 2016-0309: 1.0.6 (nli2work) for KSP 1.0.5
	+ added KSPI-E Engine configs
* 2016-0307: 1.0.5 (nli2work) for KSP 1.0.5
	+ No changelog provided
* 2016-0229: 1.0 (nli2work) for KSP 1.0.5
	+ No changelog provided
