
# Supply Chain Management and Logistics System

## Project Overview
The Supply Chain Management and Logistics System is a web-based application developed using Python and Django. It helps manage the complete supply chain process, including product inventory, warehouse management, supplier management, customer orders, shipment management, and delivery tracking.

The system provides different dashboards for administrators, suppliers, customers, and logistics partners to manage their respective activities efficiently.

## Features

### Admin Module
- Admin dashboard with order and shipment statistics.
- Manage suppliers and logistics partners.
- Add, update, and delete products.
- Manage warehouse information.
- View and manage customer orders.
- Assign logistics partners to shipments.
- Monitor inventory and stock movements.

### Supplier Module
- Supplier registration and login.
- Manage supplier-related activities.
- Monitor product information and inventory.

### Customer Module
- Customer registration and login.
- Browse available products.
- Place product orders.
- View order details and status.
- Track shipments using an interactive map.

### Logistics Partner Module
- Logistics partner dashboard.
- View assigned shipments.
- Update shipment status.
- Monitor delivery information.

### Inventory Management
- Track product quantities.
- Maintain stock movement records.
- Configure product restock thresholds.
- Identify products requiring restocking.

### Shipment Tracking
- Track order locations using Leaflet.js.
- Display delivery locations on OpenStreetMap.
- Simulate delivery movement using geographical coordinates.
- Update order delivery status.

### Payment Management
- Maintain payment transactions.
- Support UPI, credit card, bank transfer, and cash on delivery payment methods.
- Track pending and completed payment statuses.

## Technologies Used

- Backend: Python, Django
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Database: SQLite
- Map Integration: Leaflet.js, OpenStreetMap
- Version Control: Git, GitHub

## Project Structure

supply1/
├── abcd/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
├── supply1/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── manage.py

## Installation and Setup

1. Clone the repository:

   git clone https://github.com/YOUR_USERNAME/supply-chain-management-system.git

2. Navigate to the project folder:

   cd supply1

3. Create a virtual environment:

   python -m venv venv

4. Activate the virtual environment:

   Windows:
   venv\Scripts\activate

5. Install dependencies:

   pip install -r requirements.txt

6. Apply migrations:

   python manage.py migrate

7. Run the development server:

   python manage.py runserver

8. Open in your browser:

   http://127.0.0.1:8000/

## Key Learning Outcomes

- Full-stack web application development.
- Django MVC/MVT architecture.
- Database design and ORM operations.
- User authentication and role-based access.
- Inventory and shipment management.
- Map integration and location tracking.
- Building dynamic web applications.

## Author

Adarsh S Pattanashetti

MCA Graduate | Python Django Developer

GitHub: https://github.com/YOUR_USERNAME
