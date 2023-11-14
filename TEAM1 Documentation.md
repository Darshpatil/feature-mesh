# TEAM 1
| Names |  |
| ---- |--- |
| Kunal Bandyopadhyay | Pawan Singh | 
|  Bhumika Manchikanti | Anand Balagar |




## Purpose and Scope

The main purpose of the Feature Mesh software system is to empower data scientists and data engineers by providing a cloud-native feature store. This system serves as a centralized platform where features, can be efficiently created, stored, updated, deleted and retrieved . It simplifies the feature engineering process by offering a user-friendly interface and a library for seamless interaction. With capabilities for publishing, retrieving, updating, and deleting features, the Feature Mesh system optimizes the workflow of data scientists, ensuring easy access to valuable features for model training and reusability within the data science community. Ultimately, its goal is to maximize productivity, streamline feature management, and enhance the overall efficiency of data science endeavors.

The scope of data scientists revolves around their interaction with the Feature Mesh system and how it positively impacts their workflow. It includes user Interface and Experience which contains the detailed exploration of the graphical user interface, emphasizing its intuitiveness and user-friendly design to facilitate easy feature publishing and retrieval. The Feature Retrieval Options which enables the data scientist for thorough coverage of the different options available for searching and selecting features, catering to data scientists preferences in terms of feature names, keywords, timestamps, etc.

## Intended Audience

Understanding the target users is crucial for tailoring the user experience, providing relevant features, and ensuring the effective utilization of the application. The intended audience of this document are Data Scientists and Machine Learning Engineers. Data scientists and machine learning engineers are primary users of the Feature Store application. They utilize the application to access, explore, and manage features for developing and deploying machine learning models. And the Data engineers play a crucial role in the data pipeline and integration process. They use the Feature Store application to ensure a seamless flow of features from diverse sources to the centralized repository and consume it to train their respective models.

## Business Context
>###  Stakeholders

This documentation outlines the various stakeholders involved in the Feature Store application. Stakeholders are individuals or groups who have an interest, influence, or involvement in the development, implementation, and use of the Feature Store. The involved stakeholders for the proposed application are “Data scientist”. Data scientists are pivotal stakeholders in the Feature Store application, as they are primarily responsible for leveraging features in the development and deployment of machine learning models. Their role extends across various stages of the machine learning lifecycle.
And they are also responsible for publishing features. Their role involves selecting, preparing, and documenting features for model development. Through the Feature Store, data scientists ensure seamless access to curated features, streamlining the machine learning workflow for predictive modeling and analysis. And they are also responsible for Model development and training.

>### Business Goals

These goals collectively aim to position the Feature Mesh software system as a valuable asset for organizations looking to optimize their data science workflows, improve collaboration, and achieve better outcomes in machine learning projects.

- Enhance Data Scientist Productivity: Increase the efficiency of data scientists by providing a user-friendly platform for seamless feature engineering, reducing the time and effort required for model development.
- Facilitate Collaboration: Foster collaboration among data scientists and data engineers by offering a centralized feature store where they can easily share, discover, and reuse features, promoting a more efficient and collaborative work environment.
- Optimize Model Training: Improve the quality of machine learning models by ensuring easy access to high-quality features, allowing data scientists to focus on model training rather than spending excessive time on feature engineering.
- Accelerate Time-to-Market: Speed up the development lifecycle of machine learning projects by streamlining feature management processes, reducing bottlenecks, and facilitating quicker iterations from idea to deployment.
- Increase Reusability of Features: Encourage the creation of reusable and standardized features, reducing redundancy and enhancing the scalability of machine learning projects across different teams and projects.
- Reduce Data Redundancy and Inconsistency: Minimize data redundancy and inconsistency by centralizing feature storage and management, ensuring that features are maintained consistently across different projects.
- Drive Innovation in Data Science: Stimulate innovation in data science by providing a platform that encourages experimentation, exploration, and the sharing of novel features, contributing to continuous improvement and advancement in machine learning practices.
 


## Architecturally Significant Requirements
>### Use Case Diagram

![alt text](https://github.com/fnf-tritech/feature-mesh/blob/main/859cbfde-633b-4e57-93d2-9b812eea2ef2.jpg?raw=true)

>### Functional Requirements
- Feature Publishing: The system should allow Data Scientists to publish the built feature on the platform. It should allow users to specify metadata for the features that would be used while searching.
- Feature Pushing: The system should provide a GUI or a library to push the developed feature onto the platform. It should display the status message of the push operation to the user.
- Feature Searching: The system should allow Data Scientists to search for the intended feature from the platform. It should provide options to search by feature name, keyword, timestamp etc.
- Feature Selection: The system should display the choices to the user and allow them to select the desired feature from the search results. It should present the abstract of the feature to the user.
- Model Training: The system should allow Data Scientists to use the published feature for model training using the offline store within the platform. It should provide a built library from featuremesh to get the values of a feature for training the analytical model in the user’s environment (i.e: Jupyter-Notebook etc)
- Accessibility: The software will be providing user friendly interactive UI and API libraies for the users to perform their activities like create, delete, update, retrieve.

>### Non Functional Requirements

- Usability: The system should be easy to understand and use. It should be designed to maximize the Data Scientists’ and Data Engineers’ work efficiency and production.
- Performance: The system should be able to handle large volumes of data and process requests in a timely manner.
- Scalability: The system should be able to scale to accommodate a growing number of users and data.
- Reliability: The system should be reliable and provide accurate and consistent results.
- Security: The system should ensure the security of the data and protect against unauthorized access.
- Cloud Native: The system should be a Cloud native feature store, designed to take full advantage of the benefits of cloud computing.
- Interoperability: The system should be able to interact with other systems, such as Jupyter Notebook, and support various data formats.


