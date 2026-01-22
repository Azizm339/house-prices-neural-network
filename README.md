# house-prices-neural-network
Neural network regression model for Kaggle House Prices competition — achieved ~19.4k MAE on validation

Feed-forward neural network (MLP) for predicting house sale prices using the Ames Housing dataset (Kaggle House Prices - Advanced Regression Techniques).

### Results
- **Validation MAE**: 19,380 $  
- **Validation RMSE**: ~28,300 $  
Strong performance for a pure neural network approach without heavy feature engineering.

### Notebook
Main implementation, preprocessing, training and evaluation:  
[house_price_model.ipynb](house_price_model.ipynb)
### Technologies
- Python  
- pandas, numpy  
- scikit-learn  
- tensorflow.keras  
- matplotlib

### How to run
1. Download `train.csv` and `test.csv` from the [Kaggle competition page](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)  
2. Place them in the same folder as the notebook  
3. Open `house_price_model.ipynb` in Jupyter, Google Colab or VS Code  
4. Run all cells sequentially

### Model file
Trained model weights (`house_price_model.h5`) not included due to size.  
Re-train the model by running the notebook.

Feel free to ⭐ the repo or fork it!
