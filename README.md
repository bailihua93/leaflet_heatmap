# leaflet_heatmap
简单的可视化湖州通话数据 假设数据量很大，没法用浏览器直接绘制热力图，把绘制热力图这一步骤放到线下计算分析。使用Apache Spark并行计算数据之后，再使用Apache Spark绘制热力图，然后用leafletjs加载OpenStreetMap图层和热力图图层，以达到良好的交互效果。现在使用Apache Spark实现绘制，可能是Apache Spark不擅长这方面的计算或者是我没有设计好算法，并行计算的速度比不上单机计算。
