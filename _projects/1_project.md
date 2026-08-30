---
layout: page
title: Soft back support devices
description: Variable-stiffness passive and semi-active wearable assistance.
img: assets/img/BSD.jpg
importance: 1
category: research
---

## Passive variable-stiffness back support device

Back support devices (BSDs) have the potential to mitigate overexertion in industrial tasks and provide assistance to people with weak back muscle strength during daily activities. While state-of-the-art active BSDs can offer high assistive forces, they are bulky and heavy, making them uncomfortable for daily use. In contrast, passive BSDs are compact but require manual adjustment to be versatile.

This work presents a hybrid soft BSD that provides task-oriented assistance by tuning both stiffness (0.58 N/mm, 0.92 N/mm, and 1.7 N/mm) and slack length (0–67 mm) in a compact design. The tunable stiffness enables selection of a task-specific force profile, while slack tuning ensures unhindered movement when assistance is not required. Compared with rigid devices, the device's compliance can potentially improve human comfort.

We propose an analytical model that facilitates device design and estimates device performance. The device's tuning capabilities were evaluated in human squatting and stooping experiments, demonstrating that the desired force profiles were correctly applied.

<div class="row justify-content-sm-center">
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/vsBSD.jpg" title="Passive variable-stiffness back support device" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

## Semi-active device using a variable-stiffness parallel elastic actuator

Back support devices can reduce back-muscle effort during lifting, but existing designs face a tradeoff between lightweight passive assistance and tunable active assistance. We present a soft, lightweight, and untethered semi-active BSD that provides tunable assistance and positive net mechanical work using a variable-stiffness parallel elastic actuator (VPEA).

The VPEA combines a variable-stiffness elastic band with an inverse pneumatic artificial muscle (IPAM), whose active and passive force contributions are co-designed to provide complementary assistance. A dynamic model coupling IPAM mechanics with the complete pneumatic flow path further enables a compact, portable actuation system.

The resulting 1.97 kg device provides payload-adaptive assistance for 0, 7.5, and 15 kg payloads using onboard forearm force-myography and upper-back IMU measurements. During payload lifting and lowering, the device reduced back-extensor electromyography by 16.4 ± 4.9% and 12.2 ± 1.3%, respectively, across fifteen subjects. In a user-preference study, subjects preferred distinct assistance levels across the three payloads.

These results demonstrate that complementary passive–active assistance can provide tunable biomechanical support while preserving the low mass, softness, and untethered operation desirable for wearable BSDs.

<div class="row justify-content-sm-center">
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/saBSD.jpg" title="Semi-active soft back support device" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
