# Robot-Learning
This repository serves as a record of my academic experience in ENPM690 during the Spring of 2024. It includes my code submissions for projects and assignments. Each assignment is organized within its respective folder, complete with accompanying documentation and any necessary resources.

## 📚 Course Overview
This course offers a comprehensive exploration of the intersection between machine learning and robotics, aimed at enhancing the capabilities of robotic systems. The course is structured into several modules, each addressing fundamental concepts and advanced techniques in robot learning:

1. **Foundations of Robot Learning:** Introduction to machine learning paradigms applicable to robotics, including Reinforcement Learning, Learning from Demonstration, and Robot Shaping. Discussion on the importance of adaptation and learning for autonomous robots operating in dynamic environments.

2. **Learning Techniques and Paradigms:** Examination of various machine learning paradigms such as CMAC, KNN, MLP, lazy learning, LWR, RBF, and deep networks. Exploration of how these techniques generate models that enable robots to perform tasks efficiently.

3. **Integration with Robotic Control:** Integration of machine learning techniques with traditional robotic control approaches such as motor schema, behavior-based, and direct and inverse methods. Emphasis on creating controllers capable of operating robots effectively in real-world environments.

4. **Advanced Applications:** Application of state-of-the-art machine learning techniques, including reinforcement learning, imitation learning, and deep networks, to extend the capabilities of robotic systems. Discussion on useful representations and model building techniques for nonstationary robotic systems.

By the end of the course, it is expected for me to be able to design and implement machine learning solutions for robotics applications.

## 📄 Project List

### [Assignment 1](https://github.com/Rishikesh-Jadhav/Robot-Learning/blob/main/Assignment1): Time-Series Prediction with LSTMs and RNNs

### [Results](https://github.com/Rishikesh-Jadhav/Robot-Learning/blob/main/Assignment1/RL_Assignment1.ipynb) : Contains the notebook wih the outputs of the given task.

- **Implementation and Learnings from Assignment 1**:

1. **Dataset**: Utilized a dataset for international airline passengers prediction problem, focusing on forecasting the number of passengers in units of 1,000 based on the year and month.

2. **Data Preprocessing**:
   - Implemented a dataloader to preprocess the dataset into PyTorch tensors, enabling efficient handling and manipulation of the temporal data.

3. **Model Creation**:
   - Developed two models using PyTorch: one based on Long-Short Term Memory (LSTM) architecture and another based on Recurrent Neural Network (RNN) architecture. These models were designed to learn temporal patterns in the data and make predictions based on sequential information.

4. **Evaluation and Comparison**:
   - Evaluated the performance of both LSTM and RNN models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE). Justified the choice of metrics based on their ability to assess accuracy, precision, and generalization performance of the models.

5. **Bonus**:
   - Provided suggestions for improving the results, including hyperparameter tuning, feature engineering, regularization, ensemble methods, and exploring additional applications in robotics beyond the scope of the assignment.

This assignment provided practical experience in applying deep learning techniques to time-series forecasting tasks, with a focus on LSTM and RNN architectures. Additionally, it explored strategies for improving model performance and discussed real-world applications of time-series prediction in robotics.

     
## Additional Resources
- [Course related resources](https://mage.umd.edu/enpm690)


