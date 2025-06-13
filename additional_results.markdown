---
title: Additional Results
permalink: /additional-results
layout: page
---

Table of Contents:
- [Additional Content](#additional-content)
  - [Sweeps](#sweeps)
    - [GRU](#gru)
    - [LSTM](#lstm)
  - [Alternative LSTM Models](#alternative-lstm-models)
    - [LSTM : BlackstarHT40\_AmpHighGain](#lstm--blackstarht40_amphighgain)

# Additional Content

## Sweeps

### GRU
{% include sweeps-gru.html %}

### LSTM
{% include sweeps-lstm-parametrized.html model_n='4' model_name='MesaMiniRec_HighGain_DirectOut' %}

## Alternative LSTM Models

{% assign model_type = 'lstm' %}
{% assign model_n = '1' %}
{% assign model_name = 'BlackstarHT40_AmpHighGain' %}

### LSTM : BlackstarHT40_AmpHighGain

**SNRA**
{% include snra-parametrized.html model_type=model_type model_n=model_n %}

**Harmonic Deviation**
{% include harmonic-deviation-parametrized.html model_type=model_type model_n=model_n %}

**Sweeps**
{% include sweeps-lstm-parametrized.html model_n=model_n model_name=model_name %}