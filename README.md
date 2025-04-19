# Pet Personality Campaign Dashboard

A gamified project management dashboard for tracking KPIs across different roles in the Pet Personality campaign.

## Overview

This dashboard provides a comprehensive solution for monitoring and tracking KPIs for three key roles:

1. **Social Media Manager** - Track engagement metrics, awareness, follower growth, and content performance
2. **Digital Sales Specialist** - Monitor bundle sales, product sales, and campaign effectiveness
3. **CRM Specialist** - Manage customer relationships, segmentation, and feedback

The dashboard incorporates gamification elements to increase engagement and motivation, with features like points, badges, achievements, and leaderboards. It also provides customization options to tailor the experience for each role.

## Features

### Role-Specific Dashboards

- **Social Media Manager Dashboard**
  - Organic and paid engagement tracking
  - Awareness metrics for different demographics
  - Follower growth across platforms
  - Personality test completion tracking
  - Content performance analysis

- **Digital Sales Dashboard**
  - Bundle sales progress
  - Product sales tracking (Prima cat, cat litter)
  - Campaign effectiveness visualization
  - Tracking plan implementation status
  - Weekly KPI breakdown

- **CRM Specialist Dashboard**
  - Customer retargeting metrics
  - Customer segmentation visualization
  - Automated journey creation progress
  - Push notification plan implementation
  - Customer feedback analysis

### Gamification Elements

- Points system for completing tasks and achieving KPIs
- Badges for specific achievements
- Level progression with increasing difficulty
- Leaderboard for competitive motivation
- Achievement tracking and celebrations
- Rewards system with claimable benefits

### Customization Options

- Theme selection (Default, Ocean, Forest, Sunset, Lavender)
- Layout preferences (Standard, Compact, Focused, Detailed)
- Widget visibility toggles for each role
- Dashboard naming
- Data refresh interval settings

## Technical Implementation

The dashboard is built using:

- **Next.js** - React framework for building the user interface
- **Tailwind CSS** - Utility-first CSS framework for styling
- **React Hooks** - For state management and component logic
- **Mock Data** - Simulated data for demonstration purposes

## Getting Started

### Prerequisites

- Node.js 18.0.0 or later
- npm or pnpm package manager

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/pet-dashboard.git
   ```

2. Navigate to the project directory:
   ```
   cd pet-dashboard
   ```

3. Install dependencies:
   ```
   npm install
   ```
   or
   ```
   pnpm install
   ```

4. Start the development server:
   ```
   npm run dev
   ```
   or
   ```
   pnpm dev
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Usage Guide

### Navigating the Dashboard

1. **Home Page**: The landing page provides access to all role-specific dashboards and features.

2. **Role Selection**: Choose your role (Social Media Manager, Digital Sales, or CRM Specialist) to view relevant KPIs.

3. **KPI Tracking**: Monitor your progress toward targets with visual indicators and progress bars.

4. **Gamification**: Access the gamification page to view your achievements, badges, and position on the leaderboard.

5. **Customization**: Personalize your dashboard experience through the customization page.

### Updating KPIs

In this demonstration version, the data is mocked. In a production environment:

1. KPI data would be updated through API endpoints
2. Real-time updates would be implemented for leaderboards and achievements
3. User authentication would restrict access to role-specific dashboards

## Future Enhancements

Potential improvements for future versions:

1. **Data Integration**: Connect to real data sources and APIs
2. **User Authentication**: Implement role-based access control
3. **Notifications**: Add alerts for important KPI changes
4. **Mobile App**: Develop a companion mobile application
5. **Advanced Analytics**: Incorporate predictive analytics and trend forecasting

## Customization Guide

### Adding New KPIs

To add new KPIs to a role-specific dashboard:

1. Update the mock data in `src/lib/data/mockData.ts`
2. Add the new KPI component to the appropriate role page
3. Update the widget visibility options in the customization page

### Creating New Badges and Achievements

To add new gamification elements:

1. Define new badges in the gamification page
2. Create achievement criteria based on KPI targets
3. Update the rewards system as needed

## Troubleshooting

Common issues and solutions:

- **Dashboard not loading**: Ensure the development server is running
- **KPI data not updating**: Check the mock data implementation
- **Customization settings not saving**: This is expected in the demo version as settings are not persisted

## Contact

For support or feature requests, please contact:
- Email: support@petpointkw.com
