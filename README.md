# 2021SW_LSTM-storm

https://zenodo.org/badge/327795171.svg
https://zenodo.org/badge/latestdoi/327795171

Paper #2021SW (Journal of Space Weather)

Title: "Potential of regional ionosphere prediction using a long short-term memory (LSTM) deep-learning algorithm specialized for geomagnetic storm period"

Authors: Jeong-Heon Kim, Young-Sil Kwak, YongHa Kim, Su-In Moon, Se-Heon Jeong, JongYeon Yun

Abstract:

In our previous study (Moon et al., 2020), we developed a Long Short Term Memory (LSTM) deep-learning model for geomagnetic quiet days (LSTM-quiet) to perform effective long-term predictions for the regional ionosphere. However, their model could not predict geomagnetic storm days effectively at all. This study developed an LSTM model suitable for geomagnetic storms using the new training data set and re-designing input parameters and hyper-parameters. We collected 131 days of geomagnetic storm cases from 1 January 2009 to 31 December 2019, provided by the Japan Meteorological Agency's Kakioka Magnetic Observatory, and obtained the IMF Bz, Dst, Kp, and AE indices related to the geomagnetic storm corresponding to each storm date from the OMNI database. These indices and F2 parameters (foF2 and hmF2) of Jeju ionosonde (33.43˚N, 126.30˚E) were used as input parameters for the LSTM model. To test and verify the predictive performance and the usability of the LSTM model for geomagnetic storms developed in this manner, we created and diagnosed the 0.5, 1, 2, 3, 6, 12, and 24-hour predictive LSTM models. According to the results of this study, the LSTM storm model for 24-hour developed in this study achieved a predictive performance during the geomagnetic storms about 32% better in RMSE of foF2 than the LSTM quiet model (Moon et al., 2020). It also showed predictive performance for 24 hours that was 34% better than the widely used SAMI2 model and 37% better than the IRI-2016 model. In hmF2, the LSTM storm model calculated an RMSE that is approximately 10%, 17%, and 5% better than the LSTM quiet, SAMI2, and IRI-2016 models. Meanwhile, in our previous study, long-term predictions of more than half a day were not easy. However, we propose that the short-term predictions of less than 3 hours, which show an RMSE of less than ~1MHz for foF2 and 25 km for hmF2, are sufficiently competitive compared to other traditional ionospheric models. Because our study is the first attempt to collect and train only geomagnetic cases and then develop deep learning models, we believe it has great significance. Thus, this study suggests that our model can be used for short-term prediction and monitoring of the regional mid-latitude ionosphere.

Data:

The uploaded data (Optimal hyper parameters, PN ratio data Test #1~#3 data) are the data used to make the figures of this paper. I used the correlation coefficient, Root Meas Square Error (RMSE), and Mean Absolute Percentage Error (MAPE) as the performance skill scores. The correlation coefficient values are obtained using the REGRESS function of the IDL program, and the RMSE, MAPE, and RD are calculated using the equations as described in paper, respectively.
