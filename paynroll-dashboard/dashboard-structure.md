# PayNRoll Dashboard Structure Design

## Overview
The PayNRoll dashboard is an admission tracking system with multiple views including document uploads, updates/messages, scheduling, and profile management. The design must be responsive, adapting between mobile and desktop layouts.

## Color Scheme
- Primary: #9B0000 (dark red/maroon)
- Secondary: #F5F5F5 (light gray)
- Background: #f8f0f0 (light pink/gray)
- Text: #333333 (dark gray)
- Accent: #FFFFFF (white)

## Common Elements

### Header
- **Desktop**: Fixed at top with university logo on left, user name and ID on right
- **Mobile**: Fixed at top with university logo, student ID, and name centered

### Navigation
- **Desktop**: Vertical sidebar on left with home, messages, calendar, and profile icons
- **Mobile**: Horizontal bar at bottom with same icons

### Container Structure
- **Desktop**: Main content area with white background and rounded corners
- **Mobile**: Full-width cards with white background and rounded corners

## Page Layouts

### Dashboard (Home) Page
- **Components**:
  - Admission Status Tracker (progress steps)
  - Document Upload Cards
  - Mini Calendar (desktop only)
  
- **Desktop Layout**:
  - Left sidebar (20% width)
  - Main content area (80% width)
  - Status tracker at top (full width of content area)
  - Document uploads (60% width) and calendar (40% width) side by side
  
- **Mobile Layout**:
  - Full width status tracker at top
  - Stacked document upload cards
  - Bottom navigation bar

### Updates/Messages Page
- **Components**:
  - Search bar
  - Message list with timestamps
  - Conversation view
  
- **Desktop Layout**:
  - Left sidebar (20% width)
  - Message list (30% width)
  - Conversation view (50% width)
  
- **Mobile Layout**:
  - Full width message list
  - Bottom navigation bar
  - Separate conversation view (not shown in reference)

### Schedule/Calendar Page
- **Components**:
  - Date input field
  - Month/year selector with navigation arrows
  - Calendar grid
  
- **Desktop Layout**:
  - Left sidebar (20% width)
  - Full width date input at top
  - Calendar grid below
  
- **Mobile Layout**:
  - Full width date input at top
  - Calendar grid below
  - Bottom navigation bar

### Profile Page
- **Components**:
  - Profile picture
  - User information fields
  - Logout button
  
- **Desktop Layout**:
  - Left sidebar (20% width)
  - Profile picture and name at top
  - Information fields below
  - Logout button at bottom
  
- **Mobile Layout**:
  - Profile picture and name at top
  - Stacked information fields
  - Logout button
  - Bottom navigation bar

### Document Upload Page
- **Components**:
  - Back button
  - Upload area with drag and drop
  - Required documents list
  - Instructions
  
- **Desktop Layout**:
  - Left sidebar (20% width)
  - Upload area (60% width)
  - Required documents and instructions (40% width)
  
- **Mobile Layout**:
  - Back button at top
  - Full width upload area
  - Instructions below

## Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1023px
- Desktop: >= 1024px

## Component Styling

### Admission Status Tracker
- Horizontal progress bar with numbered circles
- Active step in primary color, completed steps in primary color, upcoming steps in light gray
- Text labels below steps

### Document Upload Cards
- White cards with box shadow
- Document icon on left
- Document name and status in center
- Upload button on right

### Navigation Icons
- Simple line icons
- Active icon in primary color
- Inactive icons in gray

### Buttons
- Primary buttons: Primary color background, white text
- Secondary buttons: Light gray background, dark text
- Rounded corners on all buttons

### Form Fields
- Light background
- Dark text
- Subtle border
- Clear labels

## State Management
- Active navigation item highlighted
- Current step in admission process highlighted
- Document upload status (pending/complete)
- Form validation states
