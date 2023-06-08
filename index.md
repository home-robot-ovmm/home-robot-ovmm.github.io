---
layout: default
---

## Abstract

**HomeRobot (noun)**: An affordable compliant robot that navigates
homes and manipulates a wide range of objects in order to complete everyday tasks.


Open-Vocabulary Mobile Manipulation (OVMM) is a core challenge for robotics research because it involves bringing together four key capabilities: perception, language understanding, navigation, and manipulation, all of which will be necessary for robots to be useful assistants in human environments. OVMM is a foundational challenge for generally useful robots precisely because it requires tackling and integrating all of these components. To drive research in this area, we introduce the HomeRobot OVMM challenge, where an agent navigates household environments to grasp novel objects and place them on target receptacles. HomeRobot has two components: a simulation component, which uses a large and diverse curated object set in new, high-quality multi-room home environments; and a real-world component, where we provide a software stack for the low-cost Hello Robot Stretch to encourage duplication of real-world experiments across labs. We implement both a reinforcement learning and a
heuristic (model-based) baseline and show evidence of sim-to-real transfer.
 
## Sim success cases

<!-- <video src="./assets/videos/multiport_hub-stool-table_success.mp4" controls="controls"  style="max-width: 270px;"></video>
Move the multiport hub from the stool to the table.
<video src="./assets/videos/toy_construction_set-table-stool-success.mp4" controls="controls"  style="max-width: 270px;"></video>
Move the toy from the table to the stool.
<video src="./assets/videos/box-stand-chair-success.mp4" controls="controls"  style="max-width: 270px;"></video>
Move the box from the stand to the chair. -->


<div class="video-container">
  <video src="./assets/videos/multiport_hub-stool-table_success.mp4" controls="controls" style="max-width: 270px;"></video>
  <p class="caption">Move the multiport hub from the <br> stool to the table.</p>
</div>

<div class="video-container">
  <video src="./assets/videos/toy_construction_set-table-stool-success.mp4" controls="controls" style="max-width: 270px;"></video>
  <p class="caption">Move the toy from the table to the stool.</p>
</div>

<div class="video-container">
  <video src="./assets/videos/box-stand-chair-success.mp4" controls="controls" style="max-width: 270px;"></video>
  <p class="caption">Move the box from the stand to the chair.</p>
</div>

---

## Real-world success cases

<div class="video-container">
  <video src="./assets/videos/ovmm_real_world_success_1_edited.mp4" controls="controls" style="max-width: 400px;"></video>
  <p class="caption">Move the stuffed animal from the chair to the sofa.</p>
</div>
<div class="video-container">
  <video src="./assets/videos/ovmm_real_world_success_2_edited.mp4" controls="controls" style="max-width: 400px;"></video>
  <p class="caption">Move the elephant from the chair to the table.</p>
</div>

---

## Comparing baselines

### Ground-truth vs. DETIC perception

<div class="video-container">
<video src="./assets/videos/gt_seg_661_cell_phone_chest_of_drawers_counter_panel_vis.mp4" controls="controls" style="max-width: 800px;"></video>
<p class="caption">(Ground-truth segmentation) Move the cell phone from the chest of drawers to the counter panel.</p>
</div>

<div class="video-container">
<video src="./assets/videos/detic_661_cellphone_chest_of_drawers_table_cant_detect_cellphone_at_130.mp4" controls="controls" style="max-width: 800px;"></video>
<p class="caption">(DETIC segmentation) Move the cell phone from the chest of drawers to the counter panel.</p>
</div>
