#Метрики в задачах классификации

from sklearn.metrics import accuracy_score, precision_recall_curve, classification_report
 
	metrics.accuracy_score(y_true, y_pred[, …])
	metrics.auc(x, y)  
	metrics.classification_report(y_true, y_pred)
	metrics.precision_score(y_true, y_pred[, …])
	metrics.recall_score(y_true, y_pred[, …])

#Метрики в задачах регрессии

	metrics.max_error(y_true, y_pred)
	metrics.mean_absolute_error(y_true, y_pred)
	metrics.mean_squared_error(y_true, y_pred[, …])
	metrics.mean_squared_log_error(y_true, y_pred)