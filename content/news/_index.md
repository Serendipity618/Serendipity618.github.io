---
title: "News"
type: "landing"
show_title: false
show_breadcrumb: false
backlinks: false

sections:
  - block: "markdown"
    id: "news-timeline"
    content:
      title: "News & Milestones"
      text: |
        <style>
          .timeline-container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
          }
          
          .timeline-item {
            display: flex;
            gap: 24px;
            margin-bottom: 45px;
            position: relative;
          }
          
          .timeline-item:not(:last-child)::after {
            content: '';
            position: absolute;
            left: 19px;
            top: 48px;
            width: 2px;
            height: calc(100% - 8px);
            background: #e5e7eb;
          }
          
          .timeline-icon {
            flex-shrink: 0;
            width: 40px;
            height: 40px;
            background: #fff;
            border: 2px solid #e5e7eb;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 16px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.06);
            position: relative;
            z-index: 1;
          }
          
          .timeline-icon.workshop { 
            color: #dc2626;
            border-color: #fecaca;
            background: #fef2f2;
          }
          
          .timeline-icon.job { 
            color: #2563eb;
            border-color: #bfdbfe;
            background: #eff6ff;
          }
          
          .timeline-icon.degree { 
            color: #059669;
            border-color: #a7f3d0;
            background: #f0fdf4;
          }
          
          .timeline-icon.paper { 
            color: #7c3aed;
            border-color: #ddd6fe;
            background: #faf5ff;
          }
          
          .timeline-icon.milestone { 
            color: #ea580c;
            border-color: #fed7aa;
            background: #fff7ed;
          }
          
          .timeline-content {
            flex: 1;
            padding-top: 2px;
          }
          
          .timeline-content h3 {
            margin: 0 0 8px 0;
            font-size: 1.2rem;
            font-weight: 600;
            color: #111827;
            line-height: 1.4;
          }
          
          .timeline-date {
            display: block;
            font-size: 0.875rem;
            color: #6b7280;
            margin-bottom: 10px;
            font-weight: 500;
          }
          
          .timeline-location {
            color: #2563eb;
            font-weight: 500;
          }
          
          .timeline-content p {
            margin: 0;
            color: #4b5563;
            font-size: 0.95rem;
            line-height: 1.65;
          }
          
          .timeline-content strong {
            color: #374151;
            font-weight: 600;
          }
          
          @media (max-width: 768px) {
            .timeline-item {
              gap: 18px;
            }
            .timeline-icon {
              width: 36px;
              height: 36px;
              font-size: 14px;
            }
            .timeline-item:not(:last-child)::after {
              left: 17px;
            }
            .timeline-content h3 {
              font-size: 1.1rem;
            }
          }
        </style>
        
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
        
        <div class="timeline-container">
          <div class="timeline-item">
            <div class="timeline-icon workshop">
              <i class="fas fa-award"></i>
            </div>
            <div class="timeline-content">
              <h3>Workshop Abstract Accepted — AMIA 2025 NLP Workshop</h3>
              <div class="timeline-date">Atlanta, GA • September 12, 2025</div>
              <p>Excited to present our work on biomedical knowledge graph applications at the AMIA Natural Language Processing Workshop. This research explores novel approaches to clinical NLP using large language models and structured medical knowledge representations.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon job">
              <i class="fas fa-briefcase"></i>
            </div>
            <div class="timeline-content">
              <h3>Postdoctoral Researcher Position — CU Anschutz Medical Campus</h3>
              <div class="timeline-date">July 2025 – Present</div>
              <p>Joined the <span class="timeline-location">Department of Biomedical Informatics</span> working with Dr. Yanjun Gao. Research focuses on large-scale biomedical knowledge graphs, clinical natural language processing, and LLM reasoning for healthcare applications. Developing interpretable AI systems for clinical decision support and medical knowledge extraction.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon degree">
              <i class="fas fa-graduation-cap"></i>
            </div>
            <div class="timeline-content">
              <h3>Ph.D. in Computer Science — Completed</h3>
              <div class="timeline-date">Utah State University • December 2024</div>
              <p>Successfully defended dissertation on anomaly detection, interpretable machine learning, and adversarial robustness. Conducted extensive research on backdoor attack detection and published multiple papers in top-tier conferences including ECML-PKDD, PAKDD, IJCNN, and IEEE Big Data. Grateful for the mentorship and collaboration throughout this journey.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon paper">
              <i class="fas fa-file-alt"></i>
            </div>
            <div class="timeline-content">
              <h3>Paper Accepted — ECML-PKDD 2024</h3>
              <div class="timeline-date">August 22, 2024</div>
              <p>Our paper on <strong>interpretable anomaly detection</strong> was accepted to the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD 2024). This work presents a novel framework for understanding and explaining anomalous patterns in complex datasets with applications to cybersecurity and fraud detection.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon paper">
              <i class="fas fa-file-alt"></i>
            </div>
            <div class="timeline-content">
              <h3>Paper Accepted — PAKDD 2024</h3>
              <div class="timeline-date">April 25, 2024</div>
              <p>Research on <strong>robustness against backdoor attacks</strong> accepted to the Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD 2024). The paper introduces innovative defense mechanisms for detecting and mitigating backdoor vulnerabilities in machine learning models, with implications for secure AI deployment.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon milestone">
              <i class="fas fa-check-circle"></i>
            </div>
            <div class="timeline-content">
              <h3>Ph.D. Proposal Defense — Passed</h3>
              <div class="timeline-date">Utah State University • March 2024</div>
              <p>Successfully defended doctoral research proposal focusing on trustworthy machine learning systems. The proposal outlined comprehensive research directions in anomaly detection, model interpretability, and adversarial robustness with both theoretical foundations and practical applications across multiple domains.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon paper">
              <i class="fas fa-file-alt"></i>
            </div>
            <div class="timeline-content">
              <h3>Paper Accepted — IJCNN 2023</h3>
              <div class="timeline-date">June 18, 2023</div>
              <p>Presented research at the International Joint Conference on Neural Networks (IJCNN 2023). This work explored <strong>deep learning approaches for anomaly detection</strong> in streaming data environments, introducing efficient online learning algorithms with theoretical convergence guarantees.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon paper">
              <i class="fas fa-file-alt"></i>
            </div>
            <div class="timeline-content">
              <h3>Paper Accepted — IEEE Big Data 2022</h3>
              <div class="timeline-date">December 17, 2022</div>
              <p>Published findings on <strong>scalable machine learning for large-scale datasets</strong> at IEEE Big Data Conference 2022. The research addressed computational challenges in processing massive data streams while maintaining model accuracy and interpretability.</p>
            </div>
          </div>
          
          <div class="timeline-item">
            <div class="timeline-icon paper">
              <i class="fas fa-file-alt"></i>
            </div>
            <div class="timeline-content">
              <h3>Paper Accepted — IEEE Big Data 2021</h3>
              <div class="timeline-date">December 15, 2021</div>
              <p>First major conference publication exploring <strong>neural network robustness and security vulnerabilities</strong>. This foundational work established research directions that would continue throughout the doctoral program, focusing on trustworthy AI systems.</p>
            </div>
          </div>
        </div>
    design:
      columns: 1
---