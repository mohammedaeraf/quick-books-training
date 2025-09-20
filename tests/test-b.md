# 📝 **Test B – Expenses Workflow**

---

## 🎯 **Objective**

Evaluate the learner’s ability to manage the **Expenses workflow** in QuickBooks, including **customers, products, purchase orders, bills, inventory updates, and bill payments**.

---

## ✅ **Test Steps**

---

### 🧱 **1️⃣ Add a Customer**

- Go to **Sales → Customers → New Customer**.
- Add the following details:

| Field        | Sample Data                                           |
| ------------ | ----------------------------------------------------- |
| Name         | FutureTech Electronics                                |
| Email        | [support@futuretech.ae](mailto:support@futuretech.ae) |
| Phone        | +971 50 222 3344                                      |
| Company Name | FutureTech Electronics LLC                            |

✔️ Save the customer.

---

### 🧱 **2️⃣ Add Products as Inventory Items**

- Go to **Sales → Products and Services → New → Inventory Item**.
- Add the following products:

| Product Name      | SKU        | Initial Quantity | Cost Price | Sales Price | Income Account | Expense Account |
| ----------------- | ---------- | ---------------- | ---------- | ----------- | -------------- | --------------- |
| Lenovo ThinkPad   | LAP-LEN-01 | 5                | AED 2,200  | AED 3,000   | Sales Income   | Inventory Asset |
| Wireless Mouse HP | MOU-HP-01  | 40               | AED 60     | AED 100     | Sales Income   | Inventory Asset |
| External Monitor  | MON-SAM-01 | 20               | AED 700    | AED 1,000   | Sales Income   | Inventory Asset |

✔️ Save each product.

---

### 🧱 **3️⃣ Create a Purchase Order (PO)**

- Go to **+ New → Purchase Order**.
- Enter:

| Field      | Sample Data         |
| ---------- | ------------------- |
| Supplier   | Lenovo UAE Supplier |
| Date       | 2025-09-20          |
| Product    | Lenovo ThinkPad     |
| Quantity   | 3                   |
| Cost Price | AED 2,200           |

✔️ Save the PO.

---

### 🧱 **4️⃣ Convert Purchase Order to Bill**

- Go to **Expenses → Purchase Orders**.
- Locate the PO created in Step 3.
- Click **Create Bill from Purchase Order** → Confirm details → Save.

---

### 🧱 **5️⃣ Observe Inventory Quantity**

- Go to **Sales → Products and Services**.
- Check stock for **Lenovo ThinkPad**.
- ✔️ Quantity should have increased by **3 units**.

---

### 🧱 **6️⃣ Record Payment for the Bill**

- Go to **+ New → Pay Bills**.
- Select the created Bill.
- Enter details:

  - Payment Method: **Bank Transfer**
  - Payment Date: Today’s date
  - Amount: Full bill amount

- Save the payment.

---

## ✅ **Expected Outcome**

| Step            | Outcome                                                   |
| --------------- | --------------------------------------------------------- |
| Customer        | FutureTech Electronics added                              |
| Products        | Inventory items set up with initial stock                 |
| PO → Bill       | Bill successfully created from PO                         |
| Inventory Stock | Stock of Lenovo ThinkPad increased by 3                   |
| Bill Payment    | Bill marked Paid → Bank account reduced by payment amount |

---

## 📌 **Submission Requirement**

- Submit **screenshots** of:

  1. Customer profile
  2. Products list
  3. Purchase Order
  4. Bill
  5. Inventory showing updated stock
  6. Bill payment confirmation
