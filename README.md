# 🛍️ Django E-commerce Payment App

This is a simple Django-based e-commerce app integrated with Razorpay for handling online payments. Users can view products, proceed to checkout, and pay securely using Razorpay.

---

## 🚀 Features

- 🔐 User authentication  
- 🛒 Product listing  
- 💳 Razorpay payment gateway integration  
- ✅ Success and failure handling for payments  
- 📦 Order management  

---

## 🖥️ Tech Stack

- **Backend:** Django  
- **Frontend:** HTML, TailwindCSS (optional), JavaScript  
- **Database:** SQLite (default)  
- **Payment Integration:** Razorpay  

---

## 🔧 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Add your Razorpay credentials
In your Django `settings.py`, add:

```python
RAZORPAY_KEY_ID = "your_razorpay_key_id"
RAZORPAY_KEY_SECRET = "your_razorpay_key_secret"
```
> 🔐 Tip: Use environment variables or `.env` to hide secret keys.

### 5. Run migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create a superuser (for admin access)
```bash
python manage.py createsuperuser
```

### 7. Start the development server
```bash
python manage.py runserver
