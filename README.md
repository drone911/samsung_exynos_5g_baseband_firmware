# README
This repository contains Samsung Exynos (AKA Shannon) 5g capable baseband firmware downloaded from "sammobile.com" for the project "ATtention-on-Base". Sharing them to reduce manual efforts for further academic use.

"ATtention-on-Base" TLDR: Finding vulnerabilities in AT Commands ([Vulneribility Anlysis of AT commands Tian et al. 2018](https://www.semanticscholar.org/paper/ATtention-Spanned%3A-Comprehensive-Vulnerability-of-Tian-Hernandez/9b3565ec984c01d9fdd2e682037d89a41e47e3d3)) using fuzzing in Shannon and Mediatek baseband binaries.

# Baseband Binaries
**CP_A146BXXU1AVL4_CP23443864**: *A14 5G (Exynos 1330)*  
**CP_A3360ZHU4AVI5_CP22980956**: *A33 5G (Exynos 1280)*  
**CP_A536USQS4AVL1_CP23396906**: *A53 5G (Exynos 1280)*  
**CP_A546WVLU1AWB4_CP23756364**: *A54 5G (Exynos 1380)*  
**CP_G981BXXUGHWCG_CP23967032**: *S20 Ultra 5G (Exynos 990)*  
**CP_G998BXXU4BULG_CP21437897**: *S21 Ultra (Exynos 2100)*  
**CP_N986BXXU5GVJE_CP23165611**: *Note 20 Ultra (Exynos 990)*  
**CP_S901BXXU4CWCH_CL2616274**: *S22 (Exynos 2200)*  

# How to extract the baseband binary
```
tar -xf <baseband firmware>
lz4 <extracted modem.bin.lz4>
```
