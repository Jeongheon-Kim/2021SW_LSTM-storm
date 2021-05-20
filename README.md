# 2021SW_LSTM-storm

Paper #2021SW (Journal of Space Weather)

Title: "Potential of regional ionosphere prediction using a long short-term memory (LSTM) deep-learning algorithm specialized for geomagnetic storm period"

Authors: Jeong-Heon Kim, Young-Sil Kwak, YongHa Kim, Su-In Moon, Se-Heon Jeong, JongYeon Yun

Abstract:

In our previous study (Moon et al., 2020), we developed a Long Short Term Memory (LSTM) deep-learning model for geomagnetic quiet days (LSTM-quiet) to perform effective long-term predictions for the regional ionosphere. However, their model could not predict geomagnetic storm days effectively at all. This study developed an LSTM model suitable for geomagnetic storms using the new training data set and re-designing input parameters and hyper-parameters. We collected 131 days of geomagnetic storm cases from 1 January 2009 to 31 December 2019, provided by the Japan Meteorological Agency's Kakioka Magnetic Observatory, and obtained the IMF Bz, Dst, Kp, and AE indices related to the geomagnetic storm corresponding to each storm date from the OMNI database. These indices and F2 parameters (foF2 and hmF2) of Jeju ionosonde (33.43˚N, 126.30˚E) were used as input parameters for the LSTM model. To test and verify the predictive performance and the usability of the LSTM model for geomagnetic storms developed in this manner, we created and diagnosed the 0.5, 1, 2, 3, 6, 12, and 24-hour predictive LSTM models. According to the results of this study, the LSTM storm model for 24-hour developed in this study achieved a predictive performance during the five geomagnetic storms about 21.2% (0.3%), 14.8% (2.7%), and 8.4% (-0.6%)  better in RMSE of foF2 (hmF2) than the LSTM quiet model (Moon et al., 2020), SAMI2, and IRI-2016 models. We propose that the short-term predictions of less than 3 hours are sufficiently competitive than other traditional ionospheric models. Thus, this study suggests that our model can be used for short-term prediction and monitoring of the regional mid-latitude ionosphere.

Data:

The uploaded data (Optimal hyper parameters, PN ratio data Test #1~#5 data) are the data used to make the figures of this paper. I used the correlation coefficient, Root Meas Square Error (RMSE), and Mean Absolute Percentage Error (MAPE) as the performance skill scores. The correlation coefficient values are obtained using the REGRESS function of the IDL program, and the RMSE, MAPE, and RD are calculated using the equations as described in paper, respectively.

Data Target : https://doi.org/10.5281/zenodo.4776395
              https://zenodo.org/badge/DOI/10.5281/zenodo.4776395.svg
