# AI-Blockchain

# here we fetch the data from etherscan.io
This Node.js script fetches Ethereum block data from the Etherscan API for a range of block numbers. It retrieves information such as the timestamp and block reward for each block and stores it in an array of Block objects. The data is then exported to a CSV file named "block_data.csv" using the csv-writer library. The script utilizes the axios library to make HTTP requests to the API and ethers library to convert the block reward from wei to Ether. The server runs on port 3000, and when executed, it fetches the data, exports it to the CSV file, and starts the server to listen for incoming requests.

# And this fetching data giving to AI for training purpose
#futher procedure i.e to train the AI with the help of Google colab 
https://colab.research.google.com/drive/1vGiPphqbvP9lfcUP-5h0HEfwMZMRGMXe#scrollTo=M_P80vhgpKK0


This Python script loads block data from a CSV file into a pandas DataFrame and then visualizes the relationship between timestamps and corresponding block rewards using a scatter plot. It employs a RandomForestRegressor from scikit-learn to create a regression model that can predict block rewards based on timestamps. The model is trained on the existing data, and a new timestamp is used to predict a future block reward, which is then plotted on the scatter plot. The script showcases how machine learning techniques like Random Forest can be applied to predict future values based on historical data patterns.

The purpose of this code is to fetch Ethereum block data from the Etherscan API for a range of block numbers and store the relevant information, including timestamps and block rewards, in a CSV file named "block_data.csv". It then uses the pandas library to read the data from the CSV file and matplotlib to create a scatter plot to visualize the relationship between timestamps and block rewards.

Additionally, the script utilizes scikit-learn's RandomForestRegressor to create a regression model based on the data. The model is trained using the timestamps as features and the corresponding block rewards as the target variable. Once the model is trained, it is used to predict the block reward for a new timestamp (1686641571 seconds) and plot the predicted value on the scatter plot.

The overall goal of this code is to demonstrate how to fetch data from an API, preprocess and save it, visualize the data using a scatter plot, and apply a regression model to predict future values based on historical data patterns. In this specific case, it's used for predicting future Ethereum block rewards based on timestamps.
