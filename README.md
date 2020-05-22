# 2020SW_assimilation_SAMI2

Paper #2020SW  (Journal of Space Weather)

Title: "Regional ionospheric parameter estimation by assimilating the LSTM trained results into the SAMI2 model"

Authors: Jeong-Heon Kim, Young-Sil Kwak, YongHa Kim, Su-In Moon, Se-Heon Jeong, JongYeon Yun

Abstract:

This paper presents a study on the possibility of predicting the regional ionosphere at mid-latitude by assimilating the predicted ionospheric parameters from a neural network (NN) model into the SAMI2 model. The NN model was constructed from the dataset of Jeju ionosonde (33.43˚N, 126.30˚E) for the period of 1 Jan 2011 to 31 Dec 2015 by using the long-short term memory (LSTM) algorithm. The NN model provides 24-hour prediction of the peak density (NmF2) and peak height (hmF2) of the F2 layer over Jeju. The predicted NmF2 and hmF2 were used to compute two ionospheric drivers (total ion density and effective neutral meridional wind), which were assimilated into the SAMI2 model. The SAMI2-LSTM model estimates the ionospheric conditions over the mid-latitude region around Jeju on the same geomagnetic meridional plane. We evaluate the performance of the SAMI2-LSTM by comparing predicted NmF2 and hmF2 values with measured values during the geomagnetic quiet and storm periods. The root mean square error values of NmF2 (hmF2) from Jeju ionosonde measurements are lower by 31%, 22%, and 29% (35%, 24%, and 17%) than those of the SAMI2, TIEGCM, and IRI-2016 models during the geomagnetic quiet periods. However, during the geomagnetic storm periods, the performance of SAMI2-LSTM, like all other models, is significantly worse than during the quiet periods. We discuss the advantage and possible improving strategy on the predictability of the regional mid-latitude ionosphere by utilizing data-assimilated physics models and deep-learning techniques together.


Data:

The uploaded data (Analyzed data_quiet & Analyzed data_storm) are the data used to make the figures of this paper.
I used the correlation coefficient, Root Meas Square Error (RMSE), Mean Absolute Percentage Error (MAPE), and Relative difference (RD) as the performance skill scores. The correlation coefficient values are obtained using the REGRESS function of the IDL program, and the RMSE, MAPE, and RD are calculated using the equations (5), (6), and (7), respectively which were explained in this paper.



