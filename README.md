# PClub_SecyRecruitment_Task2

I searched for datasets and found a dataset for lung capacity with only approx 700-800 data points. Since Lung Capacity is related to Tidal Volume by being around 1\10th so we can use this data with some augmentation.

I used GANs which generate and discrimate new data to be similar to original data or not. So, initially i pre-processed the data and and then implimented the generator and discriminator to train the gan eventually and using that to create synthetic data. Now, using the new Augmented data i trained a general neural model and finally calculated the mean square error.

Download the ipynb file and upload it in a colab notebook or run it locally for it to work. Prefer colab because the dataset read in the file is in colab format. Upload the csv file i the upload section of colab
