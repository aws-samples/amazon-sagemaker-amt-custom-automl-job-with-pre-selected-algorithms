# Prerequisites 

The following are prerequisites for completing the walkthrough explained in next sections: 
- An [AWS account](https://portal.aws.amazon.com/billing/signup#/start/email)
- A [SageMaker notebook instance](https://docs.aws.amazon.com/sagemaker/latest/dg/nbi.html) to run the code
- SageMaker training job service quota increase (optional)
- Familiarity with SageMaker concepts, such as: Estimator, Training job, HPO job
- Familiarity with [Amazon SageMaker Python SDK](https://sagemaker.readthedocs.io/en/stable/)
- Python programming knowledge

This notebook is tested on SageMaker Notebook instance type: ml.t3.medium, Elastic Inference: none, Platform identifier: Amazon Linux 2, Jupyter Lab 3 and conda_python3 kernel.
# TODOs:

- Check Pipe mode for input

# Resources: 

- [Using Scikit-learn with the SageMaker Python SDK](https://sagemaker.readthedocs.io/en/v1.72.1/frameworks/sklearn/using_sklearn.html)
- [Develop, Train, Optimize and Deploy Scikit-Learn Random Forest](https://sagemaker-examples.readthedocs.io/en/latest/sagemaker-python-sdk/scikit_learn_randomforest/Sklearn_on_SageMaker_end2end.html)
- [Amazon SageMaker Automatic Model Tuning now supports three new completion criteria for hyperparameter optimization](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-automatic-model-tuning-now-supports-three-new-completion-criteria-for-hyperparameter-optimization/)
- [Best Practices for Hyperparameter Tuning](https://docs.amazonaws.cn/en_us/sagemaker/latest/dg/automatic-model-tuning-considerations.html)

# Follow-up:
- `TuningJobCompletionCriteriaConfig` is not in the online documentation Python SDK

# BUGs:
- https://github.com/aws/sagemaker-python-sdk/issues/3743 & https://github.com/aws/sagemaker-python-sdk/pull/3744
