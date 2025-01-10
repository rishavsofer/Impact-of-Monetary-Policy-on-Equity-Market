# **Impact of Monetary Policy on Equity Markets**

---

### **Project Description**  
This project analyzes the impact of central bank monetary policy announcements on equity markets. Using event studies, it examines stock indices and sectors' performance pre- and post-announcements, providing insights into sectoral sensitivities and market reactions.

---

### **Overview**  
This project investigates how monetary policy decisions (e.g., interest rate changes) announced by central banks affect equity market performance. The analysis includes:
1. **Indices:** S&P 500, Nasdaq, Dow Jones.
2. **Sectors:** Technology, Financials, Healthcare.
3. **Event Window:** -10 to +10 days around policy dates.

---

### **Key Features**
- **Automated Data Sourcing:**
  - Fetches central bank policy dates dynamically (e.g., FOMC meetings).
  - Scrapes websites to ensure real-time updates.
  
- **Stock and Sector Analysis:**
  - Tracks indices and sectoral indices using historical data.
  - Calculates daily and cumulative returns during event windows.

- **Statistical Testing:**
  - Uses T-tests to compare pre- and post-announcement returns.
  - Evaluates statistical significance of market reactions.

- **Visual Insights:**
  - Cumulative return charts show how markets and sectors react.

---

### **Tools and Technologies**
- **Data Sourcing:** `yfinance`, `requests`, `BeautifulSoup`
- **Data Processing:** `pandas`, `numpy`
- **Visualization:** `matplotlib`
- **Statistical Analysis:** `statsmodels`

---

### **How to Run the Project**
1. **Clone Repository:**
   ```bash
   git clone <repository_url>
   cd impact-monetary-policy

