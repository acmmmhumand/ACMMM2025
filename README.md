# Ours: Towards Multi-Level Geometry Learning for Monocular 3D Textured Human Reconstruction
<center>
<img src="asset/2row_vis_1115.jpg" width="900px">

The gallery of paper "Ours: Towards Multi-Level Geometry Learning for Monocular 3D Textured Human Reconstruction"
</center>


# Abstract

This paper investigates the research task of reconstructing the 3D clothed human body from a monocular image. Due to the inherent ambiguity of single-view input, existing approaches leverage pre-trained SMPL(-X) estimation models or generative models to provide auxiliary information for human reconstruction. However, these methods capture only the general human body geometry and overlook specific geometric details, leading to inaccurate skeleton reconstruction, incorrect joint positions, and unclear cloth wrinkles. In response to these issues, we propose a multi-level geometry learning framework. Technically, we design three key components: skeleton-level enhancement, joint-level augmentation, and wrinkle-level refinement modules. Specifically, we effectively integrate the projected 3D Fourier features into a Gaussian reconstruction model, introduce perturbations to improve joint depth estimation during training, and refine the human coarse wrinkles by resembling the de-noising process of diffusion model. Extensive quantitative and qualitative experiments on two out-of-distribution test sets show the superior performance of our approach compared to state-of-the-art (SOTA) methods. 



# Comparison with SOTA Methods

---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/1095.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/texture/other_2_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_2_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>
</center>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/1703.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/texture/other_10_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_10_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/1793.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/texture/other_12_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_12_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>



---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/541.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/texture/other_13_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_13_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>



---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/1616.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/texture/other_9_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_9_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>
</center>

---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/cropped_istockphoto-1169130132-612x612.png" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/texture/other_18_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_18_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/cropped_istockphoto-1253466968-612x612.png" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/texture/other_20_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/texture/other_20_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>



---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>SiTH</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/cropped_istockphoto-1253466968-612x612.png" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>VS</th>
      <th>HiLo</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/geometry/thuman_10_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="asset/geometry/thuman_10_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_10_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


  
---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>SiTH</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="asset/ood_28/cropped_istockphoto-1253466968-612x612.png" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>VS</th>
      <th>HiLo</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="asset/geometry/custom_16_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="asset/geometry/custom_16_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_16_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>




# More Examples





<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/texture/other_22_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_3_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_21_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>

---


<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/texture/other_8_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_19_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_11_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>

---


<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/texture/other_17_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_14_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_16_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>


---


<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/texture/other_6_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_5_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="asset/texture/other_1_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>



# Animatable 3D Avatars
<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/animation/3.gif" alt="1" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/8.gif" alt="2" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/7.gif" alt="3" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/4.gif" alt="4" width="250px">
    </td>
  </tr>
  <tr align="center">
    <td align="center">
      <img src="asset/animation/5.gif" alt="5" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/6.gif" alt="6" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/1.gif" alt="7" width="250px">
    </td>
    <td align="center">
      <img src="asset/animation/2.gif" alt="8" width="250px">
    </td>
  </tr>
</table>
</center>

# How Ours Works
<center>
<img src="asset/Overview_1115.png" width="900px">
</center>
Our method, Ours, addresses monocular textured 3D human reconstruction by introducing a multi-level geometry learning framework that significantly enhances reconstruction quality. To accurately capture the human body's posture, we propose the SLE module, which projects 3D Fourier features into the 2D space of the input image, allowing the Gaussian reconstruction model to fully utilize prior human shape knowledge. For improved depth estimation of human joints, the JLA strategy applies controlled perturbations during training, increasing the model's robustness to depth inaccuracies during inference. To refine geometric details like body wrinkles, the WLR module resembles the final de-noising steps in diffusion theory, treating coarse meshes as Gaussian noise and using the high-quality texture of reconstructed Gaussian as conditions to refine wrinkles.
