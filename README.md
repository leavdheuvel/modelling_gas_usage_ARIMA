# Modelling_gas_usage_ARIMA
For a school project we had to predict the usage of some type of energy. The data contains gas usage, electricity usage and delivery of electricity from solar panels. I chose to model gas usage since this is what we can to get rid of in the future. This is what the data looks like:
![image](https://user-images.githubusercontent.com/80387555/125467822-4a7d77b4-e676-4d18-859c-df184590c673.png)

After exploring and transforming the data (taking the square root and differencing), I wanted to use an ARIMA model. Because the available data is not over the timespan of two years I added Fourier terms to model the yearly seasonality. The end result looks like this:
![image](https://user-images.githubusercontent.com/80387555/125468569-ecd41c9e-e770-48ba-a672-d60dfc9b27c9.png)

![image](https://user-images.githubusercontent.com/80387555/125468664-d17ed6f1-0010-492e-964f-22d84eddac66.png)
