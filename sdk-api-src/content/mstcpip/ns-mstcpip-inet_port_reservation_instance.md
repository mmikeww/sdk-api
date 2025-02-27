---
UID: NS:mstcpip.__unnamed_struct_2
title: INET_PORT_RESERVATION_INSTANCE (mstcpip.h)
description: Contains a port reservation and a token for a block of TCP or UDP ports.
old-location: winsock\inet_port_reservation_instance.htm
tech.root: WinSock
ms.assetid: F2332474-453F-40A3-8A0B-03A97300B724
ms.date: 12/05/2018
ms.keywords: '*PINET_PORT_RESERVATION_INSTANCE, INET_PORT_RESERVATION_INSTANCE, INET_PORT_RESERVATION_INSTANCE structure [Winsock], PINET_PORT_RESERVATION_INSTANCE, PINET_PORT_RESERVATION_INSTANCE structure pointer [Winsock], mstcpip/INET_PORT_RESERVATION_INSTANCE, mstcpip/PINET_PORT_RESERVATION_INSTANCE, winsock.inet_port_reservation_instance'
ms.topic: struct
f1_keywords:
- mstcpip/INET_PORT_RESERVATION_INSTANCE
dev_langs:
- c++
req.header: mstcpip.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Mstcpip.h
api_name:
- INET_PORT_RESERVATION_INSTANCE
targetos: Windows
req.typenames: INET_PORT_RESERVATION_INSTANCE, *PINET_PORT_RESERVATION_INSTANCE
req.redist: 
ms.custom: 19H1
---

# INET_PORT_RESERVATION_INSTANCE structure


## -description


The <b>INET_PORT_RESERVATION_INSTANCE</b> structure contains a port reservation and a token for a block of TCP or UDP ports.


## -struct-fields




### -field Reservation

A runtime port reservation for a block of TCP or UDP ports.

The <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-inet_port_range">INET_PORT_RESERVATION</a> structure is typedefed to the <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-inet_port_range">INET_PORT_RANGE</a> structure. 


### -field Token

A port reservation token for a block of TCP or UDP ports. 


## -remarks



The  <b>INET_PORT_RESERVATION_INSTANCE</b> structure is supported on Windows Vistaand later.

The  <b>INET_PORT_RESERVATION_INSTANCE</b> structure is returned by the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/gg699720(v=vs.85)">SIO_ACQUIRE_PORT_RESERVATION</a> IOCTL when acquring a runtime reservation for a block of TCP or UDP ports.  




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/iphlpapi/nf-iphlpapi-createpersistenttcpportreservation">CreatePersistentTcpPortReservation</a>



<a href="https://docs.microsoft.com/windows/desktop/api/iphlpapi/nf-iphlpapi-createpersistentudpportreservation">CreatePersistentUdpPortReservation</a>



<a href="https://docs.microsoft.com/windows/desktop/api/iphlpapi/nf-iphlpapi-deletepersistenttcpportreservation">DeletePersistentTcpPortReservation</a>



<a href="https://docs.microsoft.com/windows/desktop/api/iphlpapi/nf-iphlpapi-deletepersistentudpportreservation">DeletePersistentUdpPortReservation</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-inet_port_range">INET_PORT_RANGE</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-inet_port_reservation_token">INET_PORT_RESERVATION_TOKEN</a>



<a href="https://docs.microsoft.com/windows/desktop/api/iphlpapi/nf-iphlpapi-lookuppersistenttcpportreservation">LookupPersistentTcpPortReservation</a>



<a href="https://docs.microsoft.com/windows/desktop/api/iphlpapi/nf-iphlpapi-lookuppersistentudpportreservation">LookupPersistentUdpPortReservation</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/gg699720(v=vs.85)">SIO_ACQUIRE_PORT_RESERVATION</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/gg699721(v=vs.85)">SIO_ASSOCIATE_PORT_RESERVATION</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/gg699722(v=vs.85)">SIO_RELEASE_PORT_RESERVATION</a>
 

 

