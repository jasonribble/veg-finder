## Primary Goal

**"Quickly find the perfect place to eat that matches my dietary needs and current situation with minimal effort"**

The app acts as a knowledgeable local friend who understands dietary preferences and immediately suggests relevant options based on context.

---

### Core Use Cases

#### 1. **Find Food Now**
Get immediate recommendations for what's open and nearby right now

#### 2. **Plan Future Meal**
Browse and compare options for upcoming dining occasions

#### 3. **Filter by Context**
Get recommendations that match current needs:
- Location, price, food type, dining style
- Solo vs. group dining (including those without dietary restrictions)
- Specific cravings or mood
- Entertainment/activity pairing

#### 4. **Manage Personal Preferences**
Rate restaurants and receive personalized rankings based on individual taste

#### 5. **Share & Coordinate**
Share dining proposals with friends for group decision-making

#### 6. **Stay Updated**
Receive alerts about new restaurants, menu changes, and quality updates

## Primary Actors

### End Users 

- New Visitor - Someone unfamiliar with the area, needs map views and more detailed guidance
- Vegetarian Diner - Primary target audience
- Local Resident - Knows most restaurants, wants compact views and quick filtering
- Mixed Group Organizer - Vegetarian coordinating with non-vegetarian friends

### Administrators 

- Manages the master restaurant database
- Approves/removes restaurants
- Takes initial photos
- Monitors data quality
- Handles final decisions on contested information

### Trusted Moderator

A small group of trusted users who:

- Update restaurant information (hours, menus, closures)
- Verify crowdsourced data
- Add/update photos
- Flag outdated information
- Act as quality control layer

### Restaurant Owner/Manager

Business owners who:

- Manage their own restaurant profile
- Update menus, hours, photos
- Respond to feedback
- Post special promotions

### Crowdsourced Contributor

General users who:
G
- Submit updates about restaurants
- Report closures or changes
- Add photos
- Provide corrections to data

## Secondary Actors

### Email Service

Purpose: Send notifications and alerts to users

Integration needs:

- New restaurant alerts
- Menu change notifications
- Quality change alerts (restaurant went downhill or improved)
- Badge/achievement notifications
- Account-related communications

### SMS Notification

- See Email Services

### Weather Service API

Purpose: Context-aware recommendations (like Starbucks example)

- Get current weather conditions
- Influence recommendations 
  - hot day:  smoothies/ice cream
  - cold day: soup/coffee 
  - rainy day: nearby options with indoor seating


### Location Services API (Geolocation)

Purpose: Determine user location and calculate distances

- Get user's current location
- Calculate distance to restaurants
- Filter restaurants by proximity
- Provide directions to selected restaurant
- Show "restaurants near me"
- Differentiate between different areas (Prescott vs. Prescott Valley)

