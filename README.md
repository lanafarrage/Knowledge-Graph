# 📞 Call Center Knowledge Graph

This project visualizes a **mini knowledge graph** for a fictional call center using `NetworkX` and `Matplotlib`.

It shows how various services, departments, employees, and customer issues are connected within an organization like **Ogero**.

## 📊 What It Includes

- Relations between employees and departments
- How services are forwarded to the help desk
- Customer-reported issues and how they're handled
- A visual graph that maps all of these connections

## 🧠 Example Data Represented in the Graph

- **Lana** is an employer at **Ogero**
- Different types of services (Online, Hybrid, In-Person) are handled and forwarded to the **Help Desk**
- The **Help Desk** routes cases to departments like **Customer Service** and **Technical Support**
- **Employees** work in specific departments
- **Customers** report issues (e.g., *Late Delivery*) that are handled by the appropriate department

## 🛠️ Requirements

To run this code, you need:

- Python 3.x
- [networkx](https://networkx.org/)
- [matplotlib](https://matplotlib.org/)

Install them using:

```bash
pip install networkx matplotlib
