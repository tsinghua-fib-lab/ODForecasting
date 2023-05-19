# OD forecasting benchmark











| model | RMSE | NRMSE | MAE | MAPE | sMAPE |
| ----- | ----- | ----- | ----- | ----- | ----- | 
| LSTNet  |  |       |24.5363|0.5161|       |
| GCRN  | 120.2321 |       |24.5363|0.5161|       |
| GEML  | 113.8526 |       |39.5888|3.1885|       |
| MPGCN | 1.1421 |       |     |      |       |
| PGCN |      |       |     |      |       |
| ST-GDL |      |       |     |      |       |
| Gallet | 1081.1332|       |355.7162|0.6623|       |
| Hex D-GCN |      |       |     |      |       |
| BGARN | 52.2182|       |10.3148|0.5017|       |
| CMOD |      |       |     |      |       |
| AEST |      |       |     |      |       |
| HMOD |      |       |     |      |       |
| MVPF |      |       |     |      |       |
| DDW |      |       |     |      |       |
| ST-VGCN |      |       |     |      |       |
| C-AHGCSP |      |       |     |      |       |
| ODformer |      |       |     |      |       |
| HIAM |      |       |     |      |       |
| STHAN |      |       |     |      |       |




| model | Spatial Topology Construction | Spatial Feature Modeling | Temporal Modeling | External Features |
| ----- | -----                         | -----                    | -----             | -----             |
| GEML  | grids as nodes <br> geo-adjacency graph <br> POI-similarity graph | GCN                         |  LSTM             | none              |
| Gallet |
