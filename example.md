---
theme: ./
layout: cover
class: text-left
transition: slide-left
mdc: true
backgroud: '/ATLAS/ATLAS-Logo.png'
authors:  # First author should be the presenter
  - Xuliang Zhu: ["TDLI"]
  - Tong Sun: ["TDLI"]

meeting: "Dark SHINE Simulation and Analysis Meeting"
preTitle: "Positron 4GeV Validation"
---

<br>

<img id="ATLAS" src="/DarkSHINE/DarkSHINE-Logo.png"> </img>

<style scoped>
#ATLAS {
  width: 160px;
  position: absolute;
  right: 3%;
  bottom: 4%;
  /* background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 15%, #146b8c 50%); */
}
</style>

---
layout: pageBar
---

# Validation: e+ / e-

## Tagging Tracker Reconstruction

<div grid="~ cols-2 gap-20">

![](/Graph/validation_plots/inclusive_e+_e-/fig_3.png){width=500px}

![](/Graph/validation_plots/signal_e+_e-/fig_3.png){width=500px}

</div>


---
layout: pageBar
---

# Validation: e+ / e-

## Recoil Tracker Reconstruction

<div grid="~ cols-2 gap-20">

![](/Graph/validation_plots/inclusive_e+_e-/fig_4.png){width=500px}

![](/Graph/validation_plots/signal_e+_e-/fig_4.png){width=500px}

</div>

---
layout: pageBar
---

# Validation: e+ / e-

## missing P

<div grid="~ cols-2 gap-20">

![](/Graph/validation_plots/inclusive_e+_e-/fig_5.png){width=500px}

![](/Graph/validation_plots/signal_e+_e-/fig_5.png){width=500px}

</div>

---
layout: pageBar
---

# Validation: e+ vs e-

## ECAL truth

<div grid="~ cols-2 gap-20">

![](/Graph/validation_plots/inclusive_e+_e-/fig_6.png){width=500px}

![](/Graph/validation_plots/signal_e+_e-/fig_6.png){width=500px}

</div>

---
layout: pageBar
---

# Validation: e+ vs e-

## ECAL Cluster

<div grid="~ cols-2 gap-20">

![](/Graph/validation_plots/inclusive_e+_e-/fig_9.png){width=500px}

![](/Graph/validation_plots/signal_e+_e-/fig_9.png){width=500px}

</div>

---
layout: pageBar
---

# Validation: e+ vs e-

## HCAL truth

<div grid="~ cols-2 gap-20">

![](/Graph/validation_plots/inclusive_e+_e-/fig_17.png){width=500px}

![](/Graph/validation_plots/signal_e+_e-/fig_17.png){width=500px}

</div>

---
layout: pageBar
---

# Validation: weight distribution of s-channel signal

<br>

<div grid="~ cols-2 gap-20">

<div>

$$
m_{A'} < 63 MeV, w_{MC} > 1
$$

<Transform :scale="0.7">
<PlotlyGraph filePath="/Graph/sch_weight_ls_63/mcEventWeight_precut.json"/>
</Transform>

</div>

<div>

$$
m_{A'} > 63 MeV, w_{MC} < 1
$$

<Transform :scale="0.7">
<PlotlyGraph filePath="/Graph/sch_weight_ge_63/mcEventWeight_precut.json"/>
</Transform>

</div>

</div>

---
layout: pageBar
---

# Validation: weight distribution of t-channel signal

<br>

<div grid="~ cols-2 gap-20">

<div>

Found some high weight with low statistics

<Transform :scale="0.7">
<PlotlyGraph filePath="/Graph/tch_weight/mcEventWeight_precut.json"/>
</Transform>

</div>

<div>

$$
w_{MC} < 200
$$

<Transform :scale="0.7">
<PlotlyGraph filePath="/Graph/tch_weight/mcEventWeight_cut1.json"/>
</Transform>

</div>

</div>

---
layout: pageBar
---

# Validation: w/o weight vs w/ weight

<br>

<div grid="~ cols-2 gap-20">

![](/Graph/MissingP_precut_noweight.png)

![](/Graph/MissingP_precut_weight.png)

</div>


---
layout: pageBar
---

# Validation: Process Type

## full ; brem* region

<div grid="~ cols-2 gap-20">

![](Graph/proc_small.jpg)

![](Graph/ProcessOnTarget_cut4.png)

</div>

---
layout: pageBar
---

# Todo:

<br>

- Minor bug (only in positron brem signal, not found in other background / positron signal): Empty ECAL collection (3 / 1e5)

   ![](/Graph/dbg_ecal_e_tot.png){width=150px}


- 1 week:
   - Validation:
       - Investigate e+ events with **low tracker P** / **~0 missing P**
       - Validation: $w$ - $E_{0}$ curve for MC / formula
   - Signal region definition \[done\]
   - Cut optimizaiton (scan)
   - Limit setting
- Further
    - Bias Factor / rare proces production

---
layout: center
class: "text-center"
---

# Thanks

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)

---
layout: pageBar
---

# Backup

<br>

![](/Graph/validation_plots/inclusive_e+_e-/fig_19.png){width=500px}
