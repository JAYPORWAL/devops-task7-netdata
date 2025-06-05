**# Task 7 - Netdata Monitoring

## ✅ Objective
Install Netdata using Docker and visualize system metrics to understand server performance and health in real-time.

---

## 🔧 Tools Used
- Docker
- Netdata (Open-source monitoring tool)

---

## 🧪 Steps Performed

1. **Pulled Netdata image using Docker:**

   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
**
