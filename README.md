# HU-601 Study Portal

An interactive study portal for Engineering Economics and Accountancy (HU-601) course materials.

## Features

- 📚 **4 Complete Units**: Economics, Management, Marketing, and Financial Accounting
- 📝 **Interactive Notes**: Click "View Notes" to see detailed content with charts
- 📊 **Visual Charts**: Interactive charts using Chart.js for better understanding
- 🔍 **Search Functionality**: Search across all topics and content
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile devices
- 📄 **Model Papers**: Sample question and answer papers included

## Units Covered

### Unit 1: Economics
- Demand (Definition, Law, Exceptions)
- Supply (Definition, Law, Factors)
- Market Structures (Perfect Competition, Monopoly, Oligopoly)
- Elasticity of Demand

### Unit 2: Management
- Introduction to Management
- Principles of Management (Fayol's 14 Principles)
- Organizational Structure
- Motivation (Maslow's Hierarchy)
- Leadership Styles

### Unit 3: Marketing
- Introduction to Marketing
- Consumer Behavior
- Product Life Cycle
- Pricing Methods

### Unit 4: Financial Accounting
- Introduction to Accounting
- Accounting Concepts
- Bookkeeping Fundamentals
- Books of Accounts (Journal, Ledger, Trial Balance)

## How to Deploy on Netlify

### Option 1: Drag and Drop
1. Open [Netlify](https://www.netlify.com/)
2. Sign up or log in to your account
3. Drag and drop the `index.html` file directly onto the Netlify dashboard
4. Your site will be deployed instantly with a random URL
5. You can customize the URL in site settings

### Option 2: GitHub + Netlify (Recommended)
1. Create a new repository on GitHub
2. Upload the `index.html` file to your repository
3. Go to [Netlify](https://www.netlify.com/) and sign in
4. Click "New site from Git"
5. Connect your GitHub account and select your repository
6. Deploy settings:
   - Build command: (leave empty)
   - Publish directory: (leave empty or put `/`)
7. Click "Deploy site"

### Option 3: Git-based Deployment
```bash
# Create a new repository
git init
git add index.html README.md
git commit -m "Initial commit"

# Push to GitHub (replace with your repository URL)
git remote add origin https://github.com/yourusername/hu601-study-portal.git
git push -u origin main

# Then follow Option 2 steps 3-7
```

## Alternative Deployment Platforms

### Vercel
1. Go to [Vercel](https://vercel.com/)
2. Import your GitHub repository
3. Deploy with default settings

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Firebase Hosting
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase init hosting`
4. Deploy: `firebase deploy`

## Local Development

To run locally, simply open the `index.html` file in any modern web browser. No build process required!

## Technologies Used

- **HTML5**: Structure and content
- **Tailwind CSS**: Styling and responsive design (via CDN)
- **Vanilla JavaScript**: Interactivity and functionality
- **Chart.js**: Interactive charts and visualizations
- **Google Fonts**: Inter font family

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

This project is for educational purposes. Feel free to use and modify for your studies.

## Contributing

If you find any errors or want to add more content, feel free to:
1. Fork the repository
2. Make your changes
3. Submit a pull request

## Support

For any questions or issues, please create an issue in the GitHub repository.

---

**Happy Studying! 📚✨**
