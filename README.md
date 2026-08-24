# FacultyHack@Gateways 2026 Curriculum Project

**Course:** CAP 4620 — Artificial Intelligence
**Institution:** Florida A&M University (FAMU)

## Project Overview

This project redesigns **CAP 4620: Artificial Intelligence** at Florida A&M University to explicitly integrate High-Performance Computing (HPC), GPU computing, reproducible research workflows, and Science Gateways into existing AI/ML topics and projects. The course builds students' AI and machine learning skills through search, knowledge representation, neural networks, deep learning, model evaluation, and hyperparameter optimization using tools such as Jupyter, Google Colab, scikit-learn, and TensorFlow/Keras.

Through **FacultyHack@Gateways 2026**, the course is being extended beyond locally executed and Colab-based exercises toward authentic, computationally intensive AI experiences using shared cyberinfrastructure. Rather than adding HPC as a standalone unit, the redesign embeds HPC and Science Gateways directly into concepts already in the course: students train the same models on CPU and GPU resources, run parallel hyperparameter experiments as HPC jobs, execute ML workflows through a Science Gateway, analyze computational performance alongside model performance, and publish reproducible AI workflows.

## Faculty Information

**Name:** Dr. Yohn Jairo Parra Bautista
**Institution:** Florida A&M University
**Department/Discipline:** Computer and Information Sciences

### Brief Bio / CV

Dr. Yohn is an Assistant Professor of Computer and Information Sciences at Florida A&M University, where he is part of the FAMU AI & Data Science Cluster. His teaching and research interests include artificial intelligence, machine learning, LLM safety, data science education, inclusive growth analytics, and the environmental impact of AI infrastructure. He develops hands-on learning experiences that connect AI and machine learning concepts with research computing, real-world datasets, and emerging technologies.


**CV:** [View my CV](CVYh_updated.pdf)

### Faculty Headshot

![Faculty Headshot](images/Screenshot%202023-12-20%20at%204.49.29%20PM.png)

## Mentorship & Support

**Assigned Technical Mentor:** Felicia Doswell

Mentor feedback helped shape the redesign by:

- adding HPC as the computational environment for AI/ML — including HPC architecture for AI, CPU vs. GPU computing, GPU acceleration, remote Jupyter/JupyterHub, computational performance, memory and storage considerations, and scaling AI workloads — delivered as a small number of hands-on labs rather than a major new unit;
- using HPC to reinforce concepts already in the course (neural networks, CNNs, hyperparameter tuning) rather than treating HPC as a standalone topic;
- introducing Science Gateways as the interface that ties together the course's existing outcomes in automation, APIs, cloud tools, scalability, Git, documentation, and reproducibility;
- expanding "optimization" beyond model accuracy to include computational performance analysis; and
- restructuring the final project as an AI + HPC project with explicit, assessable HPC and Science Gateway learning outcomes.

## Science Gateway Resources & Technology Notes

### Tools Used

National Research Platform (NRP)

Description: A national-scale, distributed research computing platform providing shared access to CPU and GPU resources through Kubernetes, including a JupyterHub interface for interactive, GPU-accelerated Jupyter notebooks.
Course Use: Primary student cyberinfrastructure environment. Students access GPU-accelerated Jupyter notebooks through the NRP JupyterHub to execute AI/ML workflows beyond the local desktop or Google Colab. Labs include running the same neural-network experiment on CPU vs. GPU and comparing execution time and resource utilization; training image-classification (CNN) models on NRP GPUs while investigating how batch size, epochs, and model architecture affect training time and performance; and running multiple hyperparameter configurations as parallel experiments.

NRP JupyterHub (Science Gateway Experience)

Description: A web-based gateway through which students select computational resources (CPU/GPU, memory) and launch notebook environments without interacting directly with the underlying Kubernetes/HPC infrastructure.
Course Use: Serves as the students' science gateway experience: they access an AI/ML application through the gateway, select computational resources, execute an ML workflow, monitor the job, retrieve results, visualize results, and explain the computational workflow.

Jupyter / Google Colab / TensorFlow / scikit-learn

Description: The course's existing AI/ML development environment and libraries.
Course Use: Baseline local and cloud environments for model development. Students complete a structured NRP vs. Google Colab comparison, documenting when shared research cyberinfrastructure provides advantages over free cloud notebooks.

Cornell Virtual Workshop & HPC Carpentry

Description: Online instructional resources covering HPC, parallel computing, GPU computing, and research computing workflows.
Course Use: Supporting instructional resources used to scaffold faculty and student understanding of HPC concepts and terminology.
Implementation Notes
Adjustment 1: Added NRP as the computational environment for AI/ML through hands-on Jupyter notebook labs covering HPC architecture for AI, CPU vs. GPU computing, GPU acceleration, remote JupyterHub access, computational performance, memory and storage considerations, and scaling AI workloads.
Adjustment 2: Used NRP to reinforce concepts already in the course — CPU vs. GPU neural-network comparisons, GPU-accelerated CNN training experiments, and hyperparameter tuning via parallel experiments.
Adjustment 3: Introduced the NRP JupyterHub as the students' science gateway experience, bringing together the course's existing outcomes in automation, APIs, cloud tools, scalability, Git, documentation, and reproducibility.
Adjustment 4: Expanded model "optimization" to include AI/ML computational performance analysis: training time, inference time, CPU/GPU utilization, memory usage, scalability, parallel execution, and resource efficiency.
Adjustment 5: Redesigned the final project (beginning after Week 8) as an AI + HPC project requiring students to demonstrate AI/ML, computational resources on NRP, and reproducibility.
Adjustment 6: Added explicit HPC and Science Gateway learning outcomes mapped to labs and the final project, so cyberinfrastructure is assessable rather than supplemental.

### Implementation Notes

- **Adjustment 1:** Added HPC as the computational environment for AI/ML through hands-on labs covering HPC architecture for AI, CPU vs. GPU computing, GPU acceleration, remote Jupyter/JupyterHub, computational performance, memory and storage considerations, and scaling AI workloads.
- **Adjustment 2:** Used HPC to reinforce concepts already in the course — CPU vs. GPU neural-network comparisons, GPU-accelerated CNN training experiments, and hyperparameter tuning via parallel HPC jobs.
- **Adjustment 3:** Introduced a Science Gateway lab that brings together the course's existing outcomes in automation, APIs, cloud tools, scalability, Git, documentation, and reproducibility.
- **Adjustment 4:** Expanded model "optimization" to include AI/ML computational performance analysis: training time, inference time, CPU/GPU utilization, memory usage, scalability, parallel execution, and resource efficiency.
- **Adjustment 5:** Redesigned the final project (beginning after Week 8) as an AI + HPC project requiring students to demonstrate AI/ML, computational resources, and reproducibility.
- **Adjustment 6:** Added explicit HPC and Science Gateway learning outcomes mapped to labs and the final project, so cyberinfrastructure is assessable rather than supplemental.

## Redesigned Student Workflow

```
Define AI Problem → Build Model → Train on HPC/GPU → Run via Science Gateway → Analyze Performance → Publish Reproducible Workflow
```

1. **Define AI Problem** — Identify an AI/ML problem, dataset, and computational workflow.
2. **Build Model** — Develop an AI/ML application using Python, scikit-learn, and TensorFlow/Keras.
3. **Train on HPC/GPU** — Execute experiments using HPC or other high-performance computational resources, comparing CPU and GPU execution.
4. **Run via Science Gateway** — Access computational resources through a gateway: select resources, execute the workflow, monitor the job, and retrieve results.
5. **Analyze Performance** — Evaluate both model performance and computational performance (training time, inference time, utilization, memory, scalability, resource efficiency).
6. **Publish Reproducible Workflow** — Document the workflow using version control, documented computational environments, and automated execution.

## Assessable New Outcomes

Students will be able to:

1. Use HPC resources to execute and evaluate computationally intensive AI/ML workflows;
2. Use a Science Gateway to access computational resources, execute AI/ML workflows, and analyze results; and
3. Develop reproducible AI/ML workflows using version control, documented computational environments, and automated execution.

## Deliverables Checklist

- [Original Syllabus](SyllabusAI.pdf)
- Revised Syllabus `Revised_Syllabus.pdf`
- [Poster SGX3](https://docs.google.com/presentation/d/1uoFkRPRZgVHSBQg5-n6E_laD-BTZjN2M/edit?usp=sharing)
- SGX3 Blog Post Draft `Blog_post`

---

*This curriculum redesign was developed through FacultyHack@Gateways 2026, supported by SGX3, with technical mentorship provided by the science gateways community.*
