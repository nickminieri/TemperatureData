This MATLAB code was developed to analyze temperature data collected from sensors placed on cars to identify heat signatures and patterns over time. The data, stored in a CSV file, includes temperature readings from multiple devices, along with timestamps. The primary goal of this analysis is to detect anomalies, evaluate heat distribution, and identify potential issues, such as overheating or irregular behavior in specific devices.

The code begins by loading the CSV data and converting the timestamps to a MATLAB-compatible datetime format while handling timezone information. It removes the highest temperature data point, assuming it represents a heat source or an outlier, to focus on the broader temperature trends. It then divides the data into ten-minute intervals and calculates the average temperature for each device within those intervals.

Various visualizations are generated to analyze the data:
1. Heatmap: Displays the average temperature of each device across time intervals, providing a clear visual representation of temperature variations and potential hotspots.
2. Line Plot: Illustrates the temperature trends over time for each device, making tracking changes and detecting spikes or drops easier.
3. Box Plot: Summarizes the temperature distribution for each device, highlighting the spread and any outliers.
4. Histogram: Shows the overall frequency distribution of temperature values, offering insights into common temperature ranges.
5. Scatter Plot: Plots individual temperature readings over time, providing a detailed view of the data points and their dispersion.
6. Bar Plot: Displays the average temperature for each device, enabling a quick comparison of performance across devices.

This analysis helps identify heat signatures and assess the thermal behavior of cars equipped with sensors. It supports research on thermal management, ensuring safety and reliability by detecting potential overheating or irregular temperature behavior. This process is critical for understanding and mitigating risks, particularly in automotive applications where heat distribution and management are vital.
