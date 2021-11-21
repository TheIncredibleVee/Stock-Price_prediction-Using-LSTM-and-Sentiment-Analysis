# Stock-Price_prediction-Using-LSTM-and-Sentiment-Analysis
Through  this  project  we  will  be  trying  to  predict  the  stock  price  for  the  upcoming  few  days  after  feeding  in  the  historical  data  and  also  headlines  of  a  particular  stock  and  do  sentiment  analysis  on  it.  Mainly  we  will  be  using  LSTM  which  is  an  advanced  form  of  RNN,  one  of  the  most  important  aspect  of  deep  learning.
Our  main  objective  through  this  project  is  to:
Build  a  model  to  predict  future  stock  prices  using  efficient  Deep  Learning  models  like  LSTM
Next  we  use  sentimental  analysis  to  get  analyse  the  sentiments  of  the  market  
We  try  to  combine  the  above  two  results  into  one  model  that  can  better  predict  the  stock  prices  that  each  one  of  them  along
We  then  try  to  optimize  the  whole  model  try  out  the  latest  models  like  transform  neural  networks.

Dataset:
  historic_prices.pkl : Historic Prices of the stocks analysed.
  Custom.pkl, custom_intel.pkl, custom_cisco.pkl: Headlines mined, whose code is in the files mentioned in later section.
  Msft_senti.pkl, intel_senti.pkl, cisco_senti,pkl: Sentiment Analysis results stored in this dataset.
  Msft_with_time.pkl, intel_with_time_pkl, cisco_with_time.pkl: Sentiment analysis with time stamps.
  Msft_importable.pkl, intel_importable.pkl, cisco_importable.pkl: Combining the dataset with historical data.

Note: The data mining took about 6-10 hours for preparation of the dataset (On GTX 1650Ti GPU with Ryzen -7 4600H CPU), so keep in mind that similar time will be required to generate it again. Also, this was made using Anaconda with python 3.10 and may cause problems while running in google colab as it has 3.06.

There are are total of 6 python notebooks:
Data Mining: MSFT_DATA_MINING.ipynb, INTEL_DATA_MINING.ipynb, CISCO_DATA_MINING.ipynb
Modelling: MSFT.ipynb, Intel.ipynb, CISCO.ipynb

