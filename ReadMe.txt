### STUCAuthoringDeviceCocoaSample ###

===========================================================================
DESCRIPTION:

Finds all attached storage devices that use SCSI Multimedia Commands (MMC) and are authoring devices, such as DVD-RW drives. Sends SCSI commands to these devices using the SCSITask User Client (STUC) API.

===========================================================================
BUILD REQUIREMENTS:

Xcode 3.1 or later, Mac OS X Leopard v10.5 or later

===========================================================================
RUNTIME REQUIREMENTS:

Mac OS X Leopard v10.5 or later

===========================================================================
PACKAGING LIST:

AuthoringDevice.{h,m}
Class representing an authoring device attached to the system.

AuthoringDeviceTester.{h,m}
Sends commands to an instance of AuthoringDevice.

DeviceDataSource.{h,m}
Table view data source that tracks devices being attached and removed.

InterfaceController.{h,m}
Controller class for the main view.

MyDocument.{h,m}
Main view for the application.

===========================================================================
CHANGES FROM PREVIOUS VERSIONS:

Version 1.0
- First version.

===========================================================================
Copyright (C) 2009 Apple Inc. All rights reserved.
