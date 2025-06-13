---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Table of Contents

- [Abstract](#abstract)
- [Results](#results)
  - [Signal-to-Aliasing Noise (SNRA)](#signal-to-aliasing-noise-snra)
  - [Harmonic Deviation](#harmonic-deviation)
- [Citation](#citation)

# Abstract

<div class="abstract">
Neural networks have become invaluable for general audio processing tasks, such as virtual analog modeling of nonlinear audio equipment. For sequence modeling tasks in particular, recurrent neural networks (RNNs) have gained widespread adoption in recent years. Their general applicability and effectiveness stems partly from their inherent nonlinearity, which makes them prone to aliasing. Recent work has explored mitigating aliasing by oversampling the network---an approach whose effectiveness is directly linked with the incurred computational costs. This work explores an alternative route by extending the antiderivative antialiasing technique to explicit, computable RNNs. Detailed applications to the Gated Recurrent Unit and Long Short-Term Memory cell are shown as case studies. The proposed technique is evaluated on two pre-trained guitar amplifier models, assessing its impact on the amount of aliasing and model tonality. The method is shown to reduce the models' tendency to alias considerably across all considered sample rates while only affecting their tonality moderately, without requiring high oversampling factors. The results of this study can be used in improving sound quality in neural audio processing tasks that utilize either considered recurrent unit in their architecture.
</div>

# Results

## Signal-to-Aliasing Noise (SNRA)

{% include snra-main.html %}

## Harmonic Deviation

{% include harmonic-deviation-main.html %}

## Sweeps

Sweeps.

## Sound Examples

Sound examples.

# Citation

<div>
  <pre><code>
  @conference{Mikkonen2025AntiderivativeAntialiasing,
      title = {Antiderivative Antialiasing for Recurrent Neural Networks},
      author = {Mikkonen, Otto and Werner, Kurt James},
      booktitle = {Proc. Int. Conf. Digital Audio Effects (DAFx)},
      year= {2025},
      month = sep,
      address = {Ancona, Italy}
  }
  </code></pre>
</div>