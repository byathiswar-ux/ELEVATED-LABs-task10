
# KNN – Handwritten Digit Classification


## Dataset
- **Sklearn Digits Dataset** (`load_digits()`)
- Contains 1,797 samples of handwritten digits (0–9)
- Each image is of size 8x8 pixels (64 features)

## Tools & Libraries Used
- Python
- Scikit-learn
- Matplotlib
- Google Colab

## Steps Followed
1. Loaded the digits dataset and verified data shapes
2. Visualized sample digit images
3. Split data into training and testing sets
4. Applied feature scaling using `StandardScaler`
5. Trained KNN model with K=3
6. Tested multiple K values (3, 5, 7, 9)
7. Plotted Accuracy vs K graph
8. Generated confusion matrix
9. Displayed test images with predicted labels

## Results
- Achieved high accuracy on test data
- Optimal K value chosen using Accuracy vs K plot
- Confusion matrix highlights classification performance for each digit



## Conclusion
This task provides practical exposure to KNN classification and highlights the importance of distance metrics and parameter tuning in machine learning.

## Output
<img width="1131" height="439" alt="Image" src="https://github.com/user-attachments/assets/ff7c16e8-9a6e-43ef-a4d9-6b8415ccd523" />
<img width="1011" height="646" alt="Image" src="https://github.com/user-attachments/assets/06222c4e-114e-4bb6-8efe-674459024d91" />
<img width="938" height="641" alt="Image" src="https://github.com/user-attachments/assets/613e6276-906f-4d56-b80f-6a89e8566426" />
<img width="1189" height="441" alt="Image" src="https://github.com/user-attachments/assets/eed9f072-00f8-4a06-8721-afa9fd4d17ee" />