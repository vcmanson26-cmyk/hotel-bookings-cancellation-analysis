# Hotel Booking Cancellation & Lead-Time Analysis
## Executive Summary
High booking cancellation rates create severe revenue forecasting errors and lead to unfulfilled room capacity in hospitality operations. This project analyzes **119,317 booking records** to evaluate key cancellation drivers, specifically examining the relationship between **booking lead time** and ** cancellation probability**.

---

## Key Findings
* **Direct Lead-Time Correlation:** Cancellation risk scales heavily as booking lead time increases.
*  **0-30 Days : ** **18.6% cancellation rate (strongest guest commitment).
* **31-60 Days : ** **36.4%**
* **61-90 Days : ** **39.5%**
* **91-180 Days : ** **44.7%**
* **180+ Days : ** **57.0%** cancellation rate (over half of 6+ month bookings fail materialize).
* ** The "Ghost Pipeline":** Long lead times create an inflated sense of future occupancy, masking actual revenue risk.

  ---

  ## Dashboard Preview
![Dashboard Preview] (Screenshot%20(1).png)

  ---

  ## Tools & Methodology
  * **Tool:** Microsoft Excel
  * **Data Transformation:** Applied custom data bucketing to structure continuous lead-time figures into 5 distinct operational groups.
  * **Aggregation:** Leveraged Pivot Tables and custom ratio calculations to analyze cancellation rates by group.
  * **Visulaization:**Built a clean, presentation-ready column chart and paired it with executive summary commentary.
 
  ---

  ##Strategic Business Recommendations
  1. **Tiered Deposit Policy:**Require non-refundable deposits or stricter cancellation terms for reservations booked >90 days in advance.
  2. **Early-Bird Rates:**Introduce non-refundable discounted pricing for long-lead bookings to convert speculative bookings into guaranteed revenue.
  3. **Dynamic Overbooking Models:**Adjust automated overbooking caps dynamically based on lead-time distribution rather than relying solely on historical averages.

