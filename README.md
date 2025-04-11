# SAT: Supervisor Regularization and Animation Augmentation for Two-process Monocular Texture 3D Human Reconstruction
<center>
<img src="asset/2row_vis_1115.jpg" width="900px">

The gallery of paper "SAT: Supervisor Regularization and Animation Augmentation for Two-process Monocular Texture 3D Human Reconstruction"
</center>


# Abstract

Monocular texture 3D human reconstruction aims to reconstruct the full 3D digital avatar from only one front-view human RGB image. However, the geometry ambiguity of the single 2D image and the scarcity of 3D human training data become the main factors limiting the development of this field. To solve these issues, current methods employed prior geometric estimation networks to obtain varied human geometric forms, like SMPL model, normal, and depth, but struggled to integrate these modalities effectively, leading to view-inconsistencies such as facial distortions. To this end, we propose a two-process 3D human reconstruction framework, SAT, which seamlessly learns various prior geometries in a united manner and reconstructs high-quality texture 3D avatars as the final. To further facilitate the geometry learning, we propose a Supervisor Feature Regularization module. By introducing a same-structure multi-view input network to offer the middle-layer features as training supervision, these varied geometric priors can be better fused. To tackle the data scarcity and further improve the reconstruction quality, we also propose an Online Animation
Augmentation module. By building a once-feed-forward animation network, we augment a massive amount of samples from the original 3D human data online for model training. Extensive quantitative and qualitative experiments on two benchmarks show the superiority of our approach compared to SOTA methods.



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
        <img src="asset/geo_inp_crop/ood_input_images_0_9.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
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
        <img src="asset/geo_inp_crop/ood_input_images_0_19.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
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
        <img src="asset/geometry/thuman_20_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="asset/geometry/thuman_20_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/thuman_20_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
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
        <img src="asset/geo_inp_crop/ood_input_images_0_49.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
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
        <img src="asset/geometry/custom_50_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="asset/geometry/custom_50_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="asset/geometry/custom_50_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
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
        <img src="asset/geo_inp_crop/ood_input_images_0_15.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
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



# Animation
<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="asset/video_gif/0451_00073_03_00121_8views.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="asset/video_gif/0558_00080_01_00161_8views.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="asset/video_gif/0210_00048_06_00041_8views.gif" alt="SiTH" width="250px">
    </td>
    <td align="center">
      <img src="asset/video_gif/0129_00032_06_00041_8views.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="asset/video_gif/0113_00029_05_00041_8views.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>


# How Ours Works
<center>
<img src="asset/Overview_1115.png" width="900px">
</center>
We introduce a novel framework, SAT, for the task of monocular texture 3D human reconstruction, which comprises two key processes: United Geometry Learning (UGL) and Cascading Gaussian Texturing (CGT). Central to these processes are two innovative modules: Supervised Feature Regularization (SFR) and Online Animation Augmentation (OAA). In the UGL process, we extract different-modality geometric features from the input image using various prior models and integrate them into a united geometric learning network for reconstructing 3D human normal Gaussians. To enhance this process, the SFR module is employed. It involves training a multi-view supervisor model that generates multi-level supervisor feature maps, which serve as a regularizing force for monocular geometry learning. The CGT process aims to align with the output distribution of the UGL process while preventing cascading errors. It utilizes the 3D geometry human Gaussian derived from UGL, alongside the input image, to reconstruct the 3D texture Gaussian. To further boost reconstruction quality and address the limited availability of human 3D data, we introduce the OAA module. This module trains an animation model that dynamically generates more pose-varied 3D human samples, augmenting the existing dataset for enhanced model training.
