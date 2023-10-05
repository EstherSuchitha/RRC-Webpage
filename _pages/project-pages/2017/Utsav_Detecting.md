---
layout: project-page-new
title: "Detecting, Localizing, and Recognizing Trees with a Monocular MAV:
Towards Preventing Deforestation"
authors:
  - name: Utsav Shah
    sup: #
  - name: Rishabh Khawad
    sup: #
  - name: K. Madhava Krishna
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
permalink: /publications/2017/Utsav_Detecting/
abstract: "We propose a novel pipeline for detecting, localizing, and recognizing trees with a quadcoptor equipped with monocular camera. The quadcoptor flies in an area of semidense plantation filled with many trees of more than 5 meter in height. Trees are detected on a per frame basis using state of the art Convolutional Neural Networks inspired by recent rapid advancements showcased in Deep Learning literature.
Once detected, the trees are tagged with a GPS coordinate through our global localizing and positioning framework. Further the localized trees are segmented, characterized by feature descriptors, and stored in a database by their GPS coordinates. In a subsequent run in the same area, the trees that get detected are queried to the database and get associated with the trees in the database. The association problem is posed as a dynamic programming problem and the optimal association is
inferred. The algorithm has been verified in various zones in our campus infested with trees with varying density on the Bebop 2 drone equipped with omnidirectional vision. High percentage of successful recognition and association of the trees between two or more runs is the cornerstone of this effort. The proposed method is also able to identify if trees are missing from their expected GPS tagged locations thereby making it possible to immediately alert concerned authorities about possible unlawful felling of trees. We also propose a novel way of obtaining dense
disparity map for quadcopter with monocular camera."
paper: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7989229
#video: http://robotics.iiit.ac.in/people/harsha.turlapati/DCMR.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---