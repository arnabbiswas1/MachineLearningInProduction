# Machine Learning In Production

### First Thing First - What does it mean by ML In Production?
- How do you take a machine learning model to production? Håkon Hapnes Strand's answer in Quora - [Here](http://qr.ae/TUI7Cc) & [There](https://www.quora.com/Do-most-machine-learning-algorithms-run-in-batch-or-do-they-run-every-time-they-get-a-new-bit-of-data/answer/H%C3%A5kon-Hapnes-Strand)

- When Models Go Rogue: Hard Earned Lessons About Using Machine Learning in Production - [Slides](https://www.slideshare.net/DavidTalby/when-models-go-rogue-hard-earned-lessons-about-using-machine-learning-in-production), [Talk](https://www.infoq.com/presentations/practices-lessons-ml-systems), [Talk at Strata Data Conference 2017](https://www.safaribooksonline.com/videos/strata-data-conference/9781491976241/9781491976241-video308850)

- What does your production machine learning pipeline look like? - [Hacker News Thread](https://news.ycombinator.com/item?id=13821217)

- What is the process of deploying machine learning models in production (For any ML library)? - [Reddit Thread](https://www.reddit.com/r/MachineLearning/comments/6tu9gu/what_is_the_process_of_deploying_machine_learning/)

- Quest to understand Machine Learning in Production & Notes - Towards Data Science Blog - [Part 1](https://towardsdatascience.com/quest-to-understand-machine-learning-in-production-notes-part-i-c9364eb4616) and [Part 2](https://towardsdatascience.com/quest-to-understand-machine-learning-in-production-notes-part-ii-a72bdde60f4c)


### Use Cases & Papers
- Michelangelo: Uber’s Machine Learning Platform - [Blog](https://eng.uber.com/michelangelo/), [Paper](http://proceedings.mlr.press/v67/li17a/li17a.pdf)

- TFX: A TensorFlow-Based Production-Scale Machine Learning Platform (by Google) - [Paper](http://www.kdd.org/kdd2017/papers/view/tfx-a-tensorflow-based-production-scale-machine-learning-platform)

- Meson: Workflow Orchestration for Netflix Recommendations - [Blog](https://medium.com/netflix-techblog/meson-workflow-orchestration-for-netflix-recommendations-fc932625c1d9), [Video](https://medium.com/netflix-techblog/meson-workflow-orchestration-for-netflix-recommendations-fc932625c1d9)

- Airbnb's End-to-End Machine Learning Infrastructure - [Slides](https://www.slideshare.net/FeiChen29/ml-platform-q1-meetup-airbnbs-endtoend-machine-learning-infrastructure), [Video](https://databricks.com/session/bighead-airbnbs-end-to-end-machine-learning-platform)

### Best Practices
- Rules of Machine Learning: Best Practices for ML Engineering - [Document](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf), [Video](https://sites.google.com/site/wildml2016nips/schedule)

- What’s your ML Test Score? A rubric for ML production systems - [Paper](https://sites.google.com/site/wildml2016nips/SculleyPaper1.pdf), [Slides](https://sites.google.com/site/wildml2016nips/SculleySlides1.pdf), [Video](https://sites.google.com/site/wildml2016nips/schedule)

- Hidden Technical Debt in Machine Learning Systems - [Paper](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf)

- Machine Learning: The High Interest Credit Card of Technical Debt - [Paper](https://ai.google/research/pubs/pub43146)

- Practical Methodology from Deep Learning Book - [Chapter](http://www.deeplearningbook.org/contents/guidelines.html)

### Courses

- The Facebook Field Guide to Machine Learning - [Videos](https://research.fb.com/the-facebook-field-guide-to-machine-learning-video-series/)

- Machine Learning Crash Course (by Google)
  - Production ML Systems - [Link](https://developers.google.com/machine-learning/crash-course/production-ml-systems)
  - Static vs. Dynamic Training - [Link](https://developers.google.com/machine-learning/crash-course/static-vs-dynamic-training/video-lecture)
  - Static vs. Dynamic Inference - [Link](https://developers.google.com/machine-learning/crash-course/static-vs-dynamic-inference/video-lecture)
  - Data Dependencies - [Link](https://developers.google.com/machine-learning/crash-course/data-dependencies/video-lecture)

### End to End Machine Learning (As a Service)
- Amazon Sagemaker - [Feature List](https://aws.amazon.com/sagemaker/features/), [Documentation](https://aws.amazon.com/sagemaker/developer-resources/)

- Azure Machine Learning Service (Not Azure Machine Studio) - [Link](https://azure.microsoft.com/en-in/services/machine-learning-services/)
  - Experimentation service
  - Model management
  - Workbench

- Google Cloud Machine Learning Engine - [Link](https://cloud.google.com/ml-engine/docs/tensorflow/technical-overview)

- Domino's DataLab -  [Link](https://www.dominodatalab.com/product/)

### Machine Learing Server / Model Servers
- prediction.io - [Link](http://predictionio.apache.org/index.html)
- SKIL - Skymind Intelligence Layer - [Link](https://deeplearning4j.org/machine-learning-server.html#skymind-intelligence-layer-skil)
- MLFlow (Alpha) - [Link](https://databricks.com/blog/2018/06/05/introducing-mlflow-an-open-source-machine-learning-platform.html)

### Model Management
- How do you version control models? - Quora Answer by Anand Sampat, Co-Founder & CEO @ Datmo - [Link](http://qr.ae/TUI7bo)

- H2O Steam - No Active Development. Open Source Version is still available - [Documentation](), [github](https://github.com/h2oai/steam) 

- ModelDB - Supports spark-ml, scikit-learn out of the box. Can be used with any ML environment via the ModelDB Light API. [Link](https://github.com/mitdbg/modeldb)

- comet.ml - [Available as a service](https://www.comet.ml/)

- studio.ml - [Link](https://www.studio.ml/)

- Michelangelo: Uber’s Machine Learning Platform - [Blog](https://eng.uber.com/michelangelo/), [Paper](http://proceedings.mlr.press/v67/li17a/li17a.pdf)

### Data Versioning
- Data Version Control Blog - [Link](https://blog.dataversioncontrol.com/data-version-control-in-analytics-devops-paradigm-35a880e99133)

### Quick Start
- Blog : A Guide to Scaling Machine Learning Models in Production - [Link](https://hackernoon.com/a-guide-to-scaling-machine-learning-models-in-production-aa8831163846)

### Performance Benchmarking For Machine Learning Libraries
- benchm-ml : Benchmark for scalability, speed, accuracy of commonly used open source implementations of the top machine learning algorithms (using binary classification) - [github](https://github.com/szilard/benchm-ml#summary), (talks)[https://github.com/szilard/talks]

- MLPerf (Work In Progress)- ML benchmark suite for measuring performance of ML software frameworks, ML hardware accelerators, and ML cloud platforms - [Link](https://mlperf.org/)

