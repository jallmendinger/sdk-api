---
UID: NS:d3d12video.D3D12_FEATURE_DATA_VIDEO_ENCODER_INTRA_REFRESH_MODE
tech.root: mf
title: D3D12_FEATURE_DATA_VIDEO_ENCODER_INTRA_REFRESH_MODE
ms.date: 06/07/2021
targetos: Windows
description: Retrieves a value indicating if the specified intra refresh mode is supported for the specified codec, profile, and level.
prerelease: false
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: d3d12video.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.typenames: D3D12_FEATURE_DATA_VIDEO_ENCODER_INTRA_REFRESH_MODE
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3d12video.h
api_name:
 - D3D12_FEATURE_DATA_VIDEO_ENCODER_INTRA_REFRESH_MODE
f1_keywords:
 - D3D12_FEATURE_DATA_VIDEO_ENCODER_INTRA_REFRESH_MODE
 - d3d12video/D3D12_FEATURE_DATA_VIDEO_ENCODER_INTRA_REFRESH_MODE
dev_langs:
 - c++
---

## -description

Provides data for calls to [ID3D12VideoDevice::CheckFeatureSupport](nf-d3d12video-id3d12videodevice-checkfeaturesupport.md) when the feature specified is [D3D12_FEATURE_VIDEO_ENCODER_INTRA_REFRESH_MODE](ne-d3d12video-d3d12_feature_video.md). Retrieves a value indicating if the specified intra refresh mode is supported for the specified codec, profile, and level.

## -struct-fields

### -field NodeIndex

In multi-adapter operation, this indicates which physical adapter of the device this operation applies to.

### -field Codec

A member of the [D3D12_VIDEO_ENCODER_CODEC](ne-d3d12video-d3d12_video_encoder_codec.md) enumeration specifying the codec for which intra refresh mode support is being queried.

### -field Profile

A [D3D12_VIDEO_ENCODER_PROFILE_DESC](ns-d3d12video-d3d12_video_encoder_profile_desc.md) structure specifying the profile for which intra refresh mode support is being queried.

### -field Level

A [D3D12_VIDEO_ENCODER_LEVEL_SETTING](ns-d3d12video-d3d12_video_encoder_level_setting.md) structure specifying the level for which intra refresh mode support is being queried.

### -field IntraRefreshMode

A member of the [D3D12_VIDEO_ENCODER_INTRA_REFRESH_MODE](ne-d3d12video-d3d12_video_encoder_intra_refresh_mode.md) enumeration specifying the intra refresh mode for which support is being queried.

### -field IsSupported

Receives a boolean value indicating if the specified intra refresh mode is supported for the specified codec, profile, and level.

## -remarks

## -see-also

