---
layout: page
title: projects
permalink: /projects/
nav: true
nav_order: 3
markdown: kramdown  # Explicitly set markdown processor
---

<style>
.project-container {
  display: flex;
  align-items: center;
  margin-bottom: 40px;
  gap: 30px;
}
.project-image {
  flex: 0 0 40%;
}
.project-image img {
  width: 100%;
  border-radius: 5px;
}
.project-content {
  flex: 1;
}
@media (max-width: 768px) {
  .project-container {
    flex-direction: column;
  }
  .project-image {
    flex: 1;
  }
}
</style>


<div class="project-container">
  <div class="project-image">
    <img src="/assets/img/data.jpg" alt="ML Project">
    <img src="/assets/img/masked.jpg" alt="ML Project">
  </div>

  <div class="project-content">
    <h3>Multi-Modal Masked Autoencoders for Learning Image-Spectrum Associations for Cosmology </h3>
    <p><em>Astrophysics Data Lab | June 2025 - Present </em></p>
    <p>Through the UCLA Physics REU program, I’ve been working with Professor Tuan Do and Morgan Himes on incorporating multimodal data in redshift prediction models for cosmology. Upcoming surveys, like the Legacy Survey of Space and Time will produce billions of galaxy images but comparatively few spectra, motivating models that learn cross-modal representations. </p>
        <p>We built a dataset of 134,533 galaxy images (HSC-PDR2) and spectra (DESI-DR1) and adapted a Multi-Modal Masked Autoencoder (MMAE) to embed both images and spectra in a shared representation. The MMAE is a transformer-based architecture, which we train by masking 75% of the data and reconstructing missing image and spectral tokens. We use this model to test three applications: spectral and image reconstruction from heavily masked data and redshift regression from images alone. For redshift regression, the MMAE performs comparably or better than prior multi-modal models in terms of prediction scatter even when missing spectra in testing. </p>
        <p>I’ve had the opportunity to apply machine learning to an actual scientific question and follow the engineering design process to build a model and dataset from start to finish. I learned that in order to successfully apply ML to a problem, domain knowledge and understanding the dataset is 70% of the work. </p>
    <p>🔗 <a href="/assets/pdf/REUTalks.pdf" target="_blank">Presentation</a></p>
  </div>
</div>

<div class="project-container">
  <div class="project-image">
    <img src="/assets/img/models.jpg" alt="ML Project">
    <img src="/assets/img/temodel.jpg" alt="ML Project">
  </div>
  <div class="project-content">
    <h3>Empirical Modeling of Electron Temperature in the Polar Cap Ionosphere</h3>
    <p><em> Varney Geospace Research Group | January 2025 - Present </em></p>
    <p>Under the supervision of Dr. Roger Varney, I worked on the development of an empirical model for electron temperature (Te) in the polar cap ionosphere using measurements from the Resolute Bay Incoherent Scatter Radar (RISR-N) in Nunavut, Canada (82.7° magnetic latitude). Our research focuses specifically on constructing a baseline model that expresses Te as a function of key solar driving conditions: the F10.7 solar flux index and solar zenith angle (SZA). The polar cap region, characterized by open magnetic field lines directly connected to the solar wind, presents a unique opportunity to study ionospheric responses to solar influences. This foundational empirical model represents the first phase of a larger project aimed at observing solar wind parameter influences on polar cap electron heating. By establishing a relationship between solar conditions and electron temperature variations, this work allows future research to isolate and analyze other heating mechanisms, particularly those related to polar rain electron precipitation.
</p>
    <p>🔗 <a href="/assets/pdf/SamikshaKrishnamurthyURW.pdf" target="_blank">URW 2025 Presentation</a></p>
  </div>
</div>

<div class="project-container">
  <div class="project-image">
    <img src="/assets/img/pulsar.jpg" alt="ML Project">
  </div>
  <div class="project-content">
    <h3>Timing Analysis of the Crab Pulsar</h3>
    <p><em> NANOGrav | August 2023 - Present </em></p>
        <p>Through the Pulsar Science Collaboratory (PSC), an outreach program that connects high school students with astronomy mentors, I’ve been a part of the Advanced Timing Research group. The project involves regularly monitoring the Crab Pulsar using the 20-meter radio telescope at the Green Bank Observatory site which is accessible through the Skynet robotic telescope network. As a young pulsar, the Crab Pulsar presents an interesting laboratory due to its distinctive features, including giant pulse emission and being situated within a radio-bright supernova remnant. Here, we report efforts to measure and track fluctuations in timing parameters, namely the rotational period and its derivatives, with the goal of searching for correlations between giant pulse emission rates and timing parameter modulation. Utilizing pulsar timing techniques and the timing package PINT Is Not TEMPO3 (PINT), we developed a pipeline tailored for timing data from the Crab Pulsar and other bright pulsars. </p>
<p>This project was my first introduction to scientific research and the computational tools, complex instrumentation, and large datasets involved. I had the opportunity to present our research at the American Astronomical Society in June 2024 and witness the intersection of physics, engineering, and computing.</p>
    <p>🔗 <a href="https://samikris.github.io/AAS224-advancedtiming/">GitHub</a> | <a href="https://aas244-aas.ipostersessions.com/Default.aspx?s=C1-89-9A-8D-04-EF-C1-ED-11-03-7F-9A-A9-9D-F1-D5">AAS Poster</a></p>
  </div>
</div>


<div class="project-container">
  <div class="project-image">
    <img src="/assets/img/bp.jpg" alt="BP Project">
  </div>
  <div class="project-content">
    <h3>Understanding the Correlation Between Blood Pressure and Eye Condition with ML</h3>
    <p><em> March 2023 </em></p>
    <p>Growing up, the combination of my father’s heart condition and hypertension made it crucial for us to monitor exactly when his blood pressure was high. I started noticing that when he took higher readings with his blood pressure monitor, his eyes would typically be more bloodshot and puffy. This led me to ask the following question: how do changes in blood pressure relate to eye condition?</p>
    <p> To answer this, I collected images of his eyes and their corresponding blood pressure labels for three months. I turned to machine learning to help me discern this relationship by building a small image classifier with fast.ai. Given an image of the eyes, if there is actually a relationship with blood pressure and eye condition, the model would be able to predict whether it’s high or low. The model had ~60% prediction accuracy on a test set, but this small application of machine learning was my first introduction to how it could be used in healthcare.</p>
    <p>After diving deeper into computer vision and diverse ML architectures in the Astrodata Lab, I’m currently revisiting this project. I’ve been rebuilding the model with a Pytorch-lightning framework and testing different architectures. I also intend to build a larger, diverse dataset. </p>
    <p>🔗 <a href="https://github.com/samikris/HCMProject">GitHub</a> | <a href="/assets/pdf/QuadDiagram.pdf">Writeup</a></p>
    
  </div>
</div>

<div class="project-container">
  <div class="project-image">
    <img src="/assets/img/pcb.jpg" alt="BP Project">
  </div>
  <div class="project-content">
    <h3>Light Sensing PCB </h3>
    <p><em>March 2023</em></p>
    <p>As the final project in my digital electronics class, I had the opportunity to design and fabricate a light sensing PCB board from start to finish. Using Fusion 360 Circuit Design, I developed a schematic and used a PCB layout for routing. I was also involved in the manufacturing process, which included masking a board, drilling holes, and soldering in components. </p>
    <p> 🔗<a href="/assets/pdf/P225_KrishnamurthySamiksha_Documentation.pdf" target="_blank">Documentation</a></p>
  </div>
</div>


