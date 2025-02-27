---
UID: NS:p2p.peer_collab_event_data_tag~r1
title: PEER_COLLAB_EVENT_DATA
ms.date: 01/30/19
ms.keywords: peer_collab_event_data_tag, PEER_COLLAB_EVENT_DATA
f1_keywords:
- p2p/peer_collab_event_data_tag
dev_langs:
- c++
targetos: Windows
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: p2p.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.typenames: PEER_COLLAB_EVENT_DATA, *PPEER_COLLAB_EVENT_DATA
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
- apiref
api_type:
- HeaderDef
api_location:
- p2p.h
api_name:
- peer_collab_event_data_tag
- PEER_COLLAB_EVENT_DATA
---

# PEER_COLLAB_EVENT_DATA structure


## -description

The <b>PEER_COLLAB_EVENT_DATA</b> union contains variant data for each possible peer collaboration network event raised on a peer.


## -struct-fields

### -field eventType

<a href="https://docs.microsoft.com/windows/desktop/api/p2p/ne-p2p-peer_collab_event_type">PEER_COLLAB_EVENT_TYPE</a> enumeration value that contains the type of the event whose corresponding data structure appears in the subsequent union arm.


### -field __unnamed_union_03e8_5

### -field watchListChangedData

A <a href="https://docs.microsoft.com/windows/desktop/api/p2p/ns-p2p-peer_event_watchlist_changed_data">PEER_EVENT_WATCHLIST_CHANGED_DATA</a> structure. This data structure is present when <b>eventType</b> is set to PEER_EVENT_WATCHLIST_CHANGED.


### -field presenceChangedData

A <a href="https://docs.microsoft.com/windows/desktop/api/p2p/ns-p2p-peer_event_presence_changed_data">PEER_EVENT_PRESENCE_CHANGED_DATA</a> structure. This data structure is present when <b>eventType</b> is set to PEER_EVENT_ENDPOINT_PRESENCE_CHANGED or PEER_EVENT_MY_PRESENCE_CHANGED.


### -field applicationChangedData

A <a href="https://docs.microsoft.com/windows/desktop/api/p2p/ns-p2p-peer_event_application_changed_data">PEER_EVENT_APPLICATION_CHANGED_DATA</a> structure. This data structure is present when <b>eventType</b> is set to PEER_EVENT_ENDPOINT_APPLICATION_CHANGED or PEER_EVENT_MY_APPLICATION_CHANGED.


### -field objectChangedData

A <a href="https://docs.microsoft.com/windows/desktop/api/p2p/ns-p2p-peer_event_object_changed_data">PEER_EVENT_OBJECT_CHANGED_DATA</a> structure. This data structure is present when <b>eventType</b> is set to PEER_EVENT_ENDPOINT_OBJECT_CHANGED or PEER_EVENT_MY_OBJECT_CHANGED.


### -field endpointChangedData

A <a href="https://docs.microsoft.com/windows/desktop/api/p2p/ns-p2p-peer_event_endpoint_changed_data">PEER_EVENT_ENDPOINT_CHANGED_DATA</a> structure. This data structure is present when <b>eventType</b> is set to PEER_EVENT_ENDPOINT_CHANGED or PEER_EVENT_MY_ENDPOINT_CHANGED.


### -field peopleNearMeChangedData

A <a href="https://docs.microsoft.com/windows/desktop/api/p2p/ns-p2p-peer_event_people_near_me_changed_data">PEER_EVENT_PEOPLE_NEAR_ME_CHANGED_DATA</a> structure. This data structure is present when <b>eventType</b> is set to PEER_EVENT_PEOPLE_NEAR_ME_CHANGED.


### -field requestStatusChangedData

A <a href="https://docs.microsoft.com/windows/desktop/api/p2p/ns-p2p-peer_event_request_status_changed_data">PEER_EVENT_REQUEST_STATUS_CHANGED_DATA</a> structure. This data structure is present when <b>eventType</b> is set to PEER_EVENT_REQUEST_STATUS_CHANGED.


## -remarks

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/P2PSdk/collaboration-api-structures">Peer Collaboration API Structures</a>

