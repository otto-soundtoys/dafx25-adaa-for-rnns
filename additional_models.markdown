---
title: Additional Models
permalink: /additional-models
layout: page
---

This page lists results for additional LSTM models from the [GuitarML Tone Library](https://guitarml.com/tonelibrary/tonelib-pro.html) *Proteus Tone Pack.*

- [LSTM : Blackstar HT40](#lstm--blackstar-ht40)
  - [Signal-to-Aliasing Noise (SNRA)](#signal-to-aliasing-noise-snra)
  - [Harmonic Deviation](#harmonic-deviation)
  - [Sweeps](#sweeps)
- [LSTM : Matchless SC30](#lstm--matchless-sc30)
  - [Signal-to-Aliasing Noise (SNRA)](#signal-to-aliasing-noise-snra-1)
  - [Harmonic Deviation](#harmonic-deviation-1)
  - [Sweeps](#sweeps-1)
- [LSTM : Peavey 6505+](#lstm--peavey-6505)
  - [Signal-to-Aliasing Noise (SNRA)](#signal-to-aliasing-noise-snra-2)
  - [Harmonic Deviation](#harmonic-deviation-2)
  - [Sweeps](#sweeps-2)

<!--
Memo: Model numbers and names

lsmt-1 | BlackstarHT40_AmpHighGain     
lsmt-2 | RockmanXPR_HighGain           
lsmt-3 | MatchlessSC30_Ch1_DirectOut   
lsmt-4 | MesaMiniRec_HighGain_DirectOut
lsmt-5 | 6505Plus_Red_DirectOut        
lsmt-6 | DumbleKit_HighG_DirectOut     
lsmt-7 | MesaIICplus_Drive8_5EQoff     
lsmt-8 | Splawn_OD_FractalFM3_HighGain 
-->

{% assign model_type = 'lstm' %}

## LSTM : Blackstar HT40

{% assign model1_n = '1' %}
{% assign model1_name = 'BlackstarHT40_AmpHighGain' %}

### Signal-to-Aliasing Noise (SNRA)
{% include snra-parametrized.html model_type=model_type model_n=model1_n %}

### Harmonic Deviation
{% include harmonic-deviation-parametrized.html model_type=model_type model_n=model1_n %}

### Sweeps

{% include sweeps-lstm-parametrized.html model_n=model1_n model_name=model1_name %}

## LSTM : Matchless SC30

{% assign model2_n = '3' %}
{% assign model2_name = 'MatchlessSC30_Ch1_DirectOut' %}

### Signal-to-Aliasing Noise (SNRA)
{% include snra-parametrized.html model_type=model_type model_n=model2_n %}

### Harmonic Deviation
{% include harmonic-deviation-parametrized.html model_type=model_type model_n=model2_n %}

### Sweeps
{% include sweeps-lstm-parametrized.html model_n=model2_n model_name=model2_name %}

## LSTM : Peavey 6505+

{% assign model3_n = '5' %}
{% assign model3_name = '6505Plus_Red_DirectOut' %}

### Signal-to-Aliasing Noise (SNRA)
{% include snra-parametrized.html model_type=model_type model_n=model3_n %}

### Harmonic Deviation
{% include harmonic-deviation-parametrized.html model_type=model_type model_n=model3_n %}

### Sweeps
{% include sweeps-lstm-parametrized.html model_n=model3_n model_name=model3_name %}