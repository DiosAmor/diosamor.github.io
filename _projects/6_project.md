---
layout: page
title: Framework for ns-3
description: 2023 - 2025
img: assets/img/sw/workflow_simulation.png
importance: 6
category: software development
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sw/workflow_simulation.png" title="framework for ns-3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Workflow of simulation with ns-3
</div>

Developed a framework to automate and standardize the simulation workflow from planning to plotting, enabling researchers to focus on core strategic planning and data analysis.

<br>

<h3><b>⚙️ Statistical Framework for System Level Simulator (ns-3) </b></h3>

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sw/statistical_framework.png" title="statistical framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Concept of ns-3 Statistical Framework
</div>

Developed a statistical framework for the <a href="https://www.nsnam.org">ns-3 simulator</a> to facilitate the collection and analysis of simulation results.

Developed a containerized statistical framework that automates the entire pipeline from parameter input to result analysis using Django and Apache Airflow. I implemented a robust data architecture using PostgreSQL and MongoDB to ensure data integrity and scalability. By leveraging Docker for the entire ecosystem, I achieved environment consistency and streamlined the deployment process.

- <b>Automated Workflow</b>: Replaced manual simulation execution with Airflow DAGs, reducing human error.

- <b>Hybrid Database Strategy</b>: Optimized data storage by using PostgreSQL for structured logs and MongoDB for large-scale simulation results.

- <b>Scalable Architecture</b>: Ensured seamless scalability and environment parity across different systems via Docker containers.

<div class="table-responsive">
  <table class="table table-striped table-bordered">
    <thead>
      <tr>
        <th>Category</th>
        <th>Technologies Used</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Backend & Orchestration</strong></td>
        <td>Django, Apache Airflow, Python</td>
      </tr>
      <tr>
        <td><strong>Database</strong></td>
        <td>PostgreSQL (Relational), MongoDB (NoSQL)</td>
      </tr>
      <tr>
        <td><strong>Infrastructure</strong></td>
        <td>Docker, Docker-compose</td>
      </tr>
      <tr>
        <td><strong>Tools & Monitoring</strong></td>
        <td>MongoDB Compass, Microsoft Teams Integration</td>
      </tr>
    </tbody>
  </table>
</div>

<br>

<h3><b>⚙️ Deep Learning Framework for System Level Simulator (ns-3) </b></h3>

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sw/mlflow.png" title="mlflow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Architecture of MLflow Tracking Server with PostgreSQL and Local File System
</div>

Developed an advanced deep learning framework by integrating <a href="https://mlflow.org/">MLflow</a> into the existing statistical architecture to automate experiment tracking and model management.

I established a robust pipeline between localhost and remote hosts to log hyperparameters, metrics, and artifacts in real-time. This enhancement significantly improved reproducibility and research efficiency for complex system-level simulation-based AI studies.

- <b>Enhanced Experiment Traceability</b>: Leveraged MLflow Tracking Server to monitor all DL training sessions and hyperparameter tuning.

- <b>Scalable Artifact Management</b>: Implemented an Artifact Proxy to securely store and retrieve large-scale model files and configurations across remote hosts.

- <b>Integrated Data Pipeline</b>: Combined PostgreSQL for metadata tracking and local/remote file systems for comprehensive storage.
