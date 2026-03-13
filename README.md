# ASME Marwadi University Student Chapter Website

## 📋 Overview

This is the official website for the **ASME (American Society of Mechanical Engineers) Student Chapter** at **Marwadi University**. The site showcases the chapter's committee members, upcoming and past events, and provides a membership application form.

The website is built with modern web technologies and integrates with **Supabase** for dynamic event management and user registrations.

## 🚀 Features

- **Responsive Design**: Fully responsive across all devices using Tailwind CSS
- **Dynamic Events**: Real-time event fetching from Supabase database with registration modals
- **Committee Showcase**: Styled profiles for all committee members with contact information
- **Membership Registration**: Secure form submission to Supabase
- **Modern UI/UX**: Professional design with smooth animations and hover effects

## 📁 Project Structure

```
├── index.html              # Homepage with hero section
├── committee.html          # Committee members showcase
├── events.html             # Dynamic events page (upcoming + past)
├── join.html               # Membership registration form
├── logo.png                # ASME chapter logo
├── hero-photo.jpg          # Hero background image
├── faculty_karan.jpeg      # Faculty coordinator photo
├── chairman_meet.jpeg      # Chairman photo
├── vice_jaswanth.jpeg      # Vice-chairman photo
├── secretary_krish.jpeg    # Secretary photo
├── treasurer_happy.jpeg    # Treasurer photo
├── media_harsha.jpeg       # Media head photo
├── tech_akash.jpeg         # Technical head photo
├── project_mayank.jpeg     # Project head photo
└── event_sumit.jpeg        # Event head photo
```

## 👥 Committee Members

**Faculty Coordinator**: Karan Motwani

**Student Committee**:
- Meet M Sindhava (Chairman)
- Jaswanth Varadha (Vice-Chairman)
- Krish R. Sanchania (Secretary)
- Happy Maheta (Treasurer)
- Harsha Vardhan Lalam (Media & Marketing Head)
- Akash Suvvari (Technical Head)
- Mayank Gambhir (Project Head)
- Sumit Kumar (Event Head)

## 🛠 Tech Stack

- **Frontend**: HTML5, Tailwind CSS 3, Font Awesome 6
- **Backend/Database**: Supabase (PostgreSQL)
- **Deployment**: Static hosting (Vercel/Netlify recommended)
- **CDN**: jsDelivr for Tailwind and Font Awesome

## 🔗 Supabase Integration

The site connects to a Supabase project for:

### Tables:
```
events - Event listings (title, date, description, winners, etc.)
registrations - Event registrations
applications - Membership applications
```

## 🚀 Quick Start

1. **Clone/Download** the project
2. **Open `index.html`** in your browser
3. **Events require Supabase** - events will show \"Syncing with database...\"
4. **Forms submit to Supabase** - check your Supabase dashboard for data

## 📱 Live Demo

Simply open `index.html` in any modern web browser. No build step required!

## 🎨 Design Features

- **Hero Section**: Full-screen background with gradient overlay
- **Circular Profile Cards**: Custom gradient borders for faculty/students
- **Modal System**: Event details and registration overlays
- **Sticky Navigation**: Persistent navbar with logo
- **Hover Animations**: Smooth scale and color transitions

## 🔄 Database Schema

### Events Table
```
id, title, event_date, description, category, icon_name, is_upcoming, winners, extra_info
```

### Registrations Table  
```
event_title, university_email, phone_number, gr_number, branch, semester
```

### Applications Table
```
email, phone, branch, semester
```

---

*© 2026 ASME Marwadi University Student Chapter. All Rights Reserved.*

---

**Run locally**: `open index.html`  
**Deploy**: Upload to Netlify/Vercel/GitHub Pages

