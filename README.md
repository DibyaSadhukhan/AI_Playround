# LITA (Love Is The Answer) - Complete Feature List

The LITA project is divided into three distinct applications, all built using the Laravel PHP Framework.

## 1. Social Media Frontend / Mobile Web App (`mob.loveistheanswer.com-master`)

This component acts as the user-facing social media application. It is a mobile-optimized web application (or PWA) that handles the core social network functionalities.

### Core Features:
- **Authentication & Onboarding**
  - Standard Login/Signup
  - Social Login (OAuth)
  - Email verification via OTP
  - Password reset
  - Multi-step onboarding flow (Customizing profile, adding bio, selecting interests, "Build a Following", and "Follow Regions")
- **Social Feeds**
  - **Custom Feed:** Personalized content feed based on followed users/interests.
  - **Popular Feed:** Trending or highly engaged posts.
- **Networking & Connections**
  - Followers and Following lists.
  - Connections system.
  - Regional networks (My Regions, Customize Region).
- **User Profiles**
  - Viewing your own profile.
  - Viewing others' profiles.
  - Editing profile details.
- **Messaging**
  - Real-time Direct Messages (DM) between users.
- **Engagement & Content**
  - Creating, viewing, and saving posts.
  - Private posts (v2 feature).
  - Hashtag support for discovery.
  - Search functionality for finding users and content.
- **Notifications**
  - System to alert users of interactions.
- **Account Management**
  - Verify account.
  - Delete account workflow.

---

## 2. Admin Dashboard / Management Panel (`admin.loveistheanswer.com-main`)

This component is the backend administration portal used by site owners and staff to moderate the social network, manage premium content, and track analytics.

### Core Features:
- **Dashboard & Analytics**
  - Overview of system usage and metrics.
- **User Management**
  - Full CRUD (Create, Read, Update, Delete) for users.
  - Viewing user details and changing user statuses.
- **Content Moderation**
  - Monitoring all user posts.
  - Handling "Flagged Echo posts".
  - Previewing reported content and taking action (delete, undelete, active/inactive).
- **Marketing & Email Automation**
  - Robust built-in email system.
  - Create single emails, draft, schedule, and build multi-step email sequences.
- **App Configuration**
  - Managing the lists of "Regions" and "Interests" that users can select from.
- **Lita Plus (Premium/Ed-Tech Platform)**
  - **Courses:** Creating course categories, course details, lessons, and attachments. Managing Instructors.
  - **Webinars:** Creating free or paid webinars, webinar categories, and attachments.
  - **Bonus Materials:** Managing premium video and non-video content.
  - **E-commerce:** Coupon code generation, order tracking, transaction history (Stripe integration), and membership tracking.
- **Weekly Content Modules**
  - Tools to manage recurring inspirational content features like:
    - Motivation Monday
    - Spiritual Sunday
    - Philosophy Friday

---

## 3. Backend REST API (`api.loveistheanswer.com-main`)

This component is a lightweight REST API. It is likely designed to serve data to a Native Mobile App (e.g., iOS/Android apps built with React Native or Flutter).

### Core Features:
- **Authentication API**
  - Secure API login and registration using Laravel Sanctum.
- **Public Data Endpoints**
  - Endpoints to fetch the master list of Regions and Interests.
- **Profile Management API**
  - Authenticated endpoints for a user to retrieve their data, customize their profile, and update their bio from a native mobile client.
