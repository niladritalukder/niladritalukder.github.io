---
title: 👩🏼‍🏫 Blog Post - Materials Characterization Series; Raman Spectroscopy
summary: Seeing the Invisible - My Raman Spectroscopy Experience with Graphene Materials
date: 2025-04-25
math: true
authors:
  - me
tags:
  - Raman Spectroscopy
  - Phonon 
  - Raman Spectra
image:
  caption: ""
cover:
  image: "https://images.unsplash.com/photo-1557682250-33bd709cbe85?q=80&w=2560"
  position:
    x: 50
    y: 40
  overlay:
    enabled: true
    type: "gradient"
    opacity: 0.4
    gradient: "bottom"
  fade:
    enabled: true
    height: "80px"
  icon:
    name: "✨"
---

## The First Time I Saw a Raman Spectrum

During my Ph.D. research, I spent many hours working with different nanomaterials, including **graphene, nitrogen-doped graphene, metal–organic frameworks (MOFs), N-G/MOF composites, and phase change materials (PCMs).** Among the many characterization techniques I used, **Raman spectroscopy always felt special.**

I still remember the excitement when I collected my first Raman spectrum of a Nitrogen-doped Graphene catalyst. After focusing the laser onto the sample and running the scan, a set of peaks appeared on the screen. These peaks were not just random signals—they were the fingerprints of the material’s atomic structure.

What fascinated me the most was the idea behind these peaks.

They appear because of **phonons**, which are the **quantized vibrations of atoms in a crystal lattice**. In other words, the atoms inside the material are vibrating, and the laser light interacts with those vibrations. The spectrum we observe is essentially **a conversation between light and atomic motion.**

At that moment, it almost felt mysterious—like seeing something invisible suddenly reveal itself - A ghost!! Ha ha ... ... 

By the way, let's have a deep dive into the fundamentals at this point.


## Light, Energy, and Vibrations

To understand Raman spectroscopy, we need to think about how light interacts with matter.

When a monochromatic laser beam hits a material, most of the photons are scattered without losing energy. This is called **Rayleigh scattering**. However, a very small fraction of the light interacts with the vibrational energy of the atoms in the material.

During this interaction, the scattered photon may:

- Lose energy to the lattice vibration (Stokes scattering), or

- Gain energy from an already excited vibration (anti-Stokes scattering).

The energy difference between the incoming and scattered light corresponds exactly to the **vibrational modes of the material**. These energy differences appear as **peaks in the Raman spectrum.**

When I first learned this, I was amazed: the peaks I saw on the computer screen were actually signatures of atomic vibrations occurring inside the material.

## Why Graphene Raman Spectra Are So Special

Graphene is one of the most fascinating materials to study with Raman spectroscopy because its spectrum reveals a lot about its structure.

A typical graphene Raman spectrum contains several important peaks, including:

- **G peak (~1580 cm⁻¹)**
This peak corresponds to the in-plane vibration of sp² carbon atoms.

- **D peak (~1350 cm⁻¹)**
This peak appears when defects are present in the graphene structure.

- **2D peak (~2700 cm⁻¹)**
This peak is related to second-order phonon scattering and provides information about the number of graphene layers.


Each peak tells a story about the material. By analyzing these peaks, we can learn about:

- Structural defects

- Degree of graphitization

- Layer thickness

- Doping effects

- Structural disorder

For a researcher working with graphene-based materials, Raman spectroscopy becomes almost like a **diagnostic tool for the atomic structure.**


## Watching the Structure Change

During my experiments, I collected Raman spectra for many materials:

- Graphene oxide (GO)

- Nitrogen-doped graphene (N-G)

- Metal–organic frameworks (MOFs)

- N-G/MOF composite catalysts

- Nanomaterial-enhanced phase change materials (PCMs)

Each material had its own spectral signature.

For example, when nitrogen atoms were incorporated into the graphene lattice, the **D/G intensity ratio often changed,** reflecting increased defects or modified bonding structures. When graphene was integrated with MOFs, additional structural effects could be observed.

These spectral changes helped us understand how synthesis processes—such as **ball milling, thermal treatment, or chemical functionalization** altered the material structure.

In this way, Raman spectroscopy allowed us to translate spectral peaks into structural insights.


## My Personal Reflection

One of the things I enjoy most about Raman spectroscopy is how it connects **abstract physics with real materials.**

The peaks we see on a Raman spectrum are not just data points. They represent **quantized vibrations of atoms,** something that cannot be seen directly but can be detected through careful measurement.

Sometimes, when I was running Raman scans late in the lab, watching those peaks appear on the screen felt almost magical. The idea that a laser beam could probe atomic vibrations and reveal structural information made me appreciate how powerful modern scientific tools are.

What initially seemed mysterious gradually became understandable through physics, chemistry, and careful analysis.


## Why Raman Spectroscopy Matters

Raman spectroscopy is widely used in materials science because it provides:

- Non-destructive structural characterization

- Fast measurement with minimal sample preparation

- Detailed information about chemical bonding and crystal structure

For graphene-based materials and nanocatalysts, Raman spectroscopy plays a crucial role in understanding structure–property relationships, which ultimately influence performance in applications such as:

Fuel cells, Batteries, Catalysts, Thermal storage materials, Electronic devices, etc.

## Thoughts

Looking back, Raman spectroscopy was one of the most fascinating tools I used during my Ph.D. research. It allowed me to explore the **vibrational world of atoms** and understand how small structural changes can dramatically influence material behavior.

Every Raman spectrum I collected was more than just a graph—it was a window into the **hidden dynamics of atoms and bonds inside the material.**

And sometimes, seeing those peaks appear still feels a little like watching the invisible become visible.


<!--

## Citation

Here's an example of citing a publication using the cite shortcode:

{{< cite page="/publications/preprint" view="citation" >}}

You can also use the default view by omitting the view parameter:

{{< cite page="/publications/conference-paper" >}}

## Video

Teach your course by sharing videos with your students. Choose from one of the following approaches:

**Youtube**:

    {{</* youtube D2vj0WcvH5c */>}}

{{< youtube D2vj0WcvH5c >}}

**Bilibili**:

    {{</* bilibili BV1WV4y1r7DF */>}}


**Video file**

Videos may be added to a page by either placing them in your `assets/media/` media library or in your [page's folder](https://gohugo.io/content-management/page-bundles/), and then embedding them with the _video_ shortcode:

    {{</* video src="my_video.mp4" controls="yes" */>}}

## Podcast

You can add a podcast or music to a page by placing the MP3 file in the page's folder or the media library folder and then embedding the audio on your page with the _audio_ shortcode:

    {{</* audio src="ambient-piano.mp3" */>}}

Try it out:

{{< audio src="ambient-piano.mp3" >}}

## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

## Math

HugoBlox Kit supports a Markdown extension for $\LaTeX$ math. Enable math by setting the `math: true` option in your page's front matter, or enable math for your entire site by toggling math in your `config/_default/params.yaml` file:

```yaml
features:
  math:
    enable: true
```

To render _inline_ or _block_ math, wrap your LaTeX math with `$...$` or `$$...$$`, respectively.

Example **math block**:

```latex
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
```

renders as

$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$

Example **inline math** `$\nabla F(\mathbf{x}_{n})$` renders as $\nabla F(\mathbf{x}_{n})$.

Example **multi-line math** using the math linebreak (`\\`):

```latex
$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
```

renders as

$$
f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}
$$

## Code

HugoBlox Kit utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    ```python
    import pandas as pd
    data = pd.read_csv("data.csv")
    data.head()
    ```

renders as

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

## Inline Images

```go
{{</* icon name="python" */>}} Python
```

renders as

{{< icon name="python" >}} Python

## Did you find this page helpful? Consider sharing it 🙌

-->

