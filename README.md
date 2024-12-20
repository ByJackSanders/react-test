# Technical Test: React Frontend Development - Shopify Upsell Analytics Page

## Objective
Build an analytics dashboard in React for a Shopify app that provides insights into upsell performance. The dashboard should display key metrics (`clicks`, `revenue`, and `conversion rate`) and allow filtering by date.

---

## Time Estimate
Approximately **60-120 minutes**

---

## Task Description
You are tasked with creating a simple React analytics page that displays performance metrics for a Shopify upsell app. The metrics include:

- **Clicks**: Number of clicks on upsell offers.
- **Revenue**: Revenue generated from upsell offers.
- **Conversion Rate**: Percentage of clicks that resulted in purchases.

The dashboard should allow merchants to:
1. **View metrics** in a summary section.
2. **Visualize data** using a simple chart.
3. **Filter data** by date range.

---

## Requirements

1. **Summary Section**:
   - Display total clicks.
   - Display total revenue.
   - Display average conversion rate.

2. **Chart**:
   - Include a line chart showing trends for each metric (`Clicks`, `Revenue`, and `Conversion Rate`) over time.

3. **Date Filter**:
   - Add a date range filter to dynamically update the displayed metrics and chart.

4. **Styling**:
   - Ensure the page looks clean and visually appealing (no CSS framework required).

---

## Provided Data

Save the following JSON data in a file named `data.json` and load it in your app:

```json
[
  { "date": "2023-12-01", "clicks": 120, "revenue": 300, "conversionRate": 5 },
  { "date": "2023-12-02", "clicks": 150, "revenue": 400, "conversionRate": 6.67 },
  { "date": "2023-12-03", "clicks": 100, "revenue": 250, "conversionRate": 5.5 },
  { "date": "2023-12-04", "clicks": 180, "revenue": 500, "conversionRate": 7.8 },
  { "date": "2023-12-05", "clicks": 130, "revenue": 350, "conversionRate": 6.5 }
]
```

## Guidelines

1.  Use React to build the application.
2.  Use any charting library (e.g., Chart.js, Recharts, or D3.js) to display the data trends.
3.  Utilize useState and useEffect hooks or any state management library you are comfortable with.
4.  No backend implementation is required. Load the JSON file directly in your React app.


## Bonus Features (Optional)
  - Add a loading spinner while the data is being loaded.
  - Display the percentage change in each metric compared to the previous day.
  - Make the dashboard responsive.

## Submission
Please submit the following:

  - A GitHub repository containing your code.
  - Instructions to run the app locally (e.g., npm install and npm start).

## Evaluation Criteria
  - Functionality: Does the app meet the requirements?
  - Code Quality: Is the code clean, readable, and well-structured?
  - UI/UX: Is the dashboard intuitive and visually appealing?
  - Bonus Features: Are any of the optional features implemented?

## Good luck!
