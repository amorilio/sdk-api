---
UID: NF:audioengineextensionapo.IAudioSystemEffects3.GetControllableSystemEffectsList
tech.root: Audio
title: IAudioSystemEffects3::GetControllableSystemEffectsList
ms.date: 06/17/2021
targetos: Windows
description: Implemented by System Effects Audio Processing Object (sAPO) audio effects to allow the caller to get the current list of effects.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: audioengineextensionapo.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: Windows Build 22000
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - audioengineextensionapo.h
api_name:
 - IAudioSystemEffects3::GetControllableSystemEffectsList
f1_keywords:
 - IAudioSystemEffects3::GetControllableSystemEffectsList
 - audioengineextensionapo/IAudioSystemEffects3::GetControllableSystemEffectsList
dev_langs:
 - c++
---

## -description

Implemented by System Effects Audio Processing Object (sAPO) audio effects to allow the caller to get the current list of effects.

## -parameters

### -param effects

Receives a pointer to an array of [AUDIO_SYSTEMEFFECT_STATE](ns-audioengineextensionapo-audio_systemeffect.md) structures representing the current list of audio effects.

### -param numEffects

Receives the number of **AUDIO_EFFECT** structures returned in *effects*.

### -param event

The HANDLE of the event that will be signaled if the list changes.

## -returns

An HRESULT.

## -remarks

## -see-also

