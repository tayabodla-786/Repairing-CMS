<div align="center">

# 🛠 Repairing CMS — Full-Stack Appliance Repair Platform

Modern MERN stack application for appliance repair services.  
Connects customers, technicians, and admins with secure booking, job management, and dashboard analytics.

</div>

## ✨ Features

**Customer Portal**  
- Browse repair services (AC, fridge, washing machine, etc.)  
- Book repair with date/time picker & address  
- Track booking status in real-time  
- View repair history & profile  

**Technician Dashboard**  
- Assigned jobs list  
- Update status, add notes & upload before/after photos (Cloudinary)  
- Job history  

**Admin Panel**  
- Manage services, technicians, users & bookings (full CRUD)  
- Analytics: total bookings, revenue, pending jobs, technician performance  
- Role management  

**Shared**  
- Secure auth: Google OAuth + JWT  
- Role-based access (customer / technician / admin)  
- Email notifications (Nodemailer)  
- Responsive, mobile-first UI (Tailwind CSS + shadcn/ui)  

## 🛠 Tech Stack

**Frontend**  
- React + Vite  
- Tailwind CSS + shadcn/ui  
- React Router v6  
- Axios + React Hook Form + Zod  

**Backend**  
- Node.js + Express  
- MongoDB + Mongoose  
- JWT + bcrypt  
- Nodemailer (emails)  
- Cloudinary (photo uploads)  

**Deployment**  
- Vercel (frontend + backend serverless)  
- MongoDB Atlas  

## 🚀 Live Links

- **Website (Customer Portal)**: https://repairing-app-cms-4oyk.vercel.app/ 
- **Admin / Technician Dashboard**: https://repairing-app-cms-frre.vercel.app/
