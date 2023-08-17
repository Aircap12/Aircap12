import matplotlib.pyplot as plt

segments = ['Mobility Solutions', 'Industrial Technology', 'Consumer Goods']
revenue = [revenue_mobility, revenue_industrial, revenue_consumer]  # Replace with actual data

plt.bar(segments, revenue)
plt.xlabel('Segments')
plt.ylabel('Revenue')
plt.title('Bosch Segment Revenue Analysis')
plt.show()


