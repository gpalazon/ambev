# Developer Evaluation Project

## 📏 Business Rules

1. **Discount Tiers**:
   - `4+` items → `10%` discount
   - `10-20` items → `20%` discount

2. **Restrictions**:
   - 🚫 **Maximum limit**: `20 items` per product
   - 🚫 **No discounts** below `4 items`

---

## 📁 Project Structure
The project follows a **modular architecture**, separating concerns between domains.


## 🛠 How to Run the Project

### **🔹 Prerequisites**
- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- [Docker & Docker Compose](https://www.docker.com/)
- [PostgreSQL](https://www.postgresql.org/download/)



### **🚀 Running Locally**

1. **Clone the repository**
   ```sh
   git clone https://github.com/YOUR_GITHUB/DeveloperEvaluation.git
   cd DeveloperEvaluation

2. **Run the application using Docker**

	docker-compose up -d --build


3. **Access the API**

	Swagger UI: http://localhost:8080/swagger


## 📌 Testing

Run unit tests using:

dotnet test