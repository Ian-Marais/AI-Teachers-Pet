# 🎓 AI Teachers Pet Pro v2.0

## Project Overview

AI Teachers Pet Pro is a comprehensive educational platform designed specifically for South African teachers following the CAPS curriculum. Built as a modern Single Page Application (SPA) using Roselt.js, it provides 21 integrated modules to support lesson planning, assessment creation, learner communication, and personal wellness.

## 🚀 Quick Start

### Prerequisites
- Node.js 14+ (for the development server)
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Anthropic Claude API key (for AI-powered modules)

### Installation

```bash
# Install dependencies
npm install

# Start development server on port 3000
npm start

# Open in browser
http://localhost:3000
```

### First Launch
1. The app will display a welcome overlay on first visit
2. Enter your Anthropic API key (begins with `sk-ant-`)
3. Click "Get Started" to begin exploring

---

## 📚 Module Guide (21 Integrated Modules)

### 🤖 AI & Planning Modules

#### M01 - **Chat Module** (`pages/chat.html`)
- Multi-turn conversational AI assistant
- Context-aware responses using Claude 3.5 Sonnet
- Quick prompt templates for common queries
- Full chat history management

#### M02 - **Lesson Plan Generator** (`pages/lesplan.html`)
- CAPS-aligned lesson planning
- Supports all subjects and grades (R-9)
- Customizable duration (30/45/60/90 min)
- Includes differentiation support and assessment

#### M03 - **Differentiated Worksheet Generator** (`pages/werkkaart.html`)
- 4 difficulty levels (Support/Core/Extended/All)
- Multiple choice, fill-in-the-blank, short answer, creative tasks
- Auto-formatted with name/date/marks header
- Printable output

#### M04 - **Question Paper & Memo Generator** (`pages/vraestel.html`)
- Professional exam format with multiple choice, short answer, and extended response
- Includes model answers and marking memo
- Bloom's taxonomy levels indicated
- Rubric guidelines for fair assessment

#### M05 - **Report Comments Generator** (`pages/rapport.html`)
- Personalized per-learner performance comments
- 7-point scale assessment (Levels 1-7)
- Tone options: Positive/Concerned/Balanced/Formal
- Exportable for end-of-term reports

#### M06 - **Parent Letter Generator** (`pages/ouer.html`)
- WhatsApp-ready message formatting
- 8 letter types: Positive/Academic/Behavior/Attendance/Test/Meeting/Progress/Success
- Multi-language support: Afrikaans/English/isiZulu
- Professional templates with warm tone

#### M07 - **Presentation Outline Generator** (`pages/aanbieding.html`)
- PowerPoint outline creation
- Customizable audiences: Parents/Learners/Staff/Governing Body
- 5-20 slide templates
- Structured speaker notes

#### M08 - **Ideas & Activities Generator** (`pages/idees.html`)
- 6 category types: Classroom Activities/Fundraising/Parent Involvement/Motivation/Technology/Special Events
- 5-20 idea generation
- Style options: Practical/Creative/Quick/Detailed
- Inspiration for diverse classroom needs

#### M09 - **Storybook Creator** (`pages/storie.html`)
- Age-appropriate story generation
- Target grades: R, 1-2, 3-4, 5-7
- Multi-language support: Afrikaans/English/isiZulu/Mixed
- 6-12 page formats with moral lessons

#### M10 - **Song Lyrics Generator** (`pages/lied.html`)
- Educational song creation for concept reinforcement
- 10 genre options: Pop/Rock/Acoustic/Kids/Gospel/Hip-Hop/Folk/R&B/Country/Jazz
- 6 language options with tone settings
- Perfect for memorable learning

#### M11 - **Translation & Language Support** (`pages/vertaling.html`)
- Translate to 12+ languages
- South African focus: isiZulu/isiXhosa/Sesotho/Setswana/Venda/Tsonga
- International: English/French/Portuguese/Spanish/German
- Pronunciation guides included

#### M12 - **Kahoot Quiz Maker** (`pages/kahoot.html`)
- Interactive quiz generator
- Customizable questions (5-20) and time per question
- Kahoot color scheme (red/blue/yellow/green)
- Live classroom engagement tool

#### M13 - **Global Teacher Chat** (`pages/worldchat.html`)
- Connection with educators worldwide (demo mode)
- 9 themed rooms: World/Africa/CAPS SA/Math/Languages/Science/Inclusive/Wellness/AI
- Best practice sharing and resource discussion
- Simulated conversations in demo

### 📖 Resources & Community

#### M14 - **Share Hub** (`pages/deelhub.html`)
- Browse educational resources from teachers
- 4 tabs: Browse/Share/Saved/Top Creators
- Filter by grade, type, subject
- Simulated demo with 8 featured resources

#### M15 - **Library** (`pages/bibliotheek.html`)
- Centralized storage for all generated content
- Search and filter by type/date
- Quick copy, view, delete operations
- Session-persistent storage

### 🎮 Wellness & Customization

#### M16 - **Relax & Games** (`pages/ontspan.html`)
- 10 brain break games:
  - Word Search (10x10)
  - Memory Match (4x4 pairs)
  - Sudoku (6x6)
  - Coloring Studio
  - Teacher's Pet (virtual pet)
  - Breathing Exercises (3 types)
  - Humor (12 jokes database)
  - Chaos Simulator
  - Win Tracker
  - Leaderboard

#### M17 - **Growth & Wellness Dashboard** (`pages/groei.html`)
- **Badges System**: 9 unlockable achievement badges
- **Daily Goals**: Rotating 8-item pool of daily objectives
- **Class Progress**: 5-subject percentage tracking
- **Wellness Mood Tracker**: 5 mood options with 14-day graph
- **SACE Portfolio**: Automatic wins documentation

#### M18 - **Daily Messages & Motivation** (`pages/dagboodskap.html`)
- 7 message categories: Motivation/Humor/Tips/Self-Care/Inspiration/SA Pride/Surprise
- 30+ curated messages database
- AI-generated unique daily messages
- WhatsApp share functionality
- Message history archive

#### M19 - **Themes & Customization** (`pages/temas.html`)
- **8 Color Themes**:
  - Teal & Grey (Default)
  - Deep Ocean
  - Bushveld Green
  - SA Sunset
  - Lavender Night
  - Rose Petal
  - Slate Dark
  - Midnight Blue
- **6 Font Families**: Plus Jakarta Sans/Nunito/Poppins/Lato/Ubuntu/Raleway
- **Text Size Slider**: 85-125%
- Live preview updates

#### M20 - **Professional Journal & Reflection** (`pages/dagboek.html`)
- **Mood Tracking**: 5 emoji-based mood options
- **Reflection Prompts**: 15 rotating daily questions
- **Tag System**: 8 reflection tags
- **AI Feedback**: On-demand reflection analysis
- **SACE Portfolio**: Victory documentation
- **Search**: By mood/keyword
- **Export**: For professional development portfolios

### 📊 Home Page

#### **Home Dashboard** (`pages/home.html`)
- Feature overview with 3 key benefits
- Quick start guide
- Statistics showcase (21 modules, 8 themes, 12 languages, infinite possibilities)

---

## 🏗️ Architecture

### Technology Stack
- **Framework**: Roselt.js (file-based routing SPA)
- **Languages**: HTML5, CSS3, JavaScript ES2022+
- **Styling**: Custom CSS with CSS variables (no build process)
- **APIs**: Anthropic Claude 3.5 Sonnet
- **Icons**: Bootstrap Icons v1.11.3
- **Fonts**: Google Fonts (Plus Jakarta Sans, Fraunces)
- **Storage**: sessionStorage (temporary) + localStorage (persistent)

### Project Structure

```
project-root/
├── index.html                 # Main SPA entry point
├── app.js                     # Core state management & API integration
├── styles/
│   └── main.css              # Complete design system (900+ lines)
├── pages/                    # Roselt.js routing directory
│   ├── home.html             # M00 - Home/Dashboard
│   ├── chat.html             # M01 - AI Chat
│   ├── lesplan.html          # M02 - Lesson Planning
│   ├── werkkaart.html        # M03 - Worksheets
│   ├── vraestel.html         # M04 - Question Papers
│   ├── rapport.html          # M05 - Report Comments
│   ├── ouer.html             # M06 - Parent Letters
│   ├── aanbieding.html       # M07 - Presentations
│   ├── idees.html            # M08 - Ideas Generator
│   ├── storie.html           # M09 - Storybook Creator
│   ├── lied.html             # M10 - Song Lyrics
│   ├── vertaling.html        # M11 - Translation
│   ├── kahoot.html           # M12 - Kahoot Quiz
│   ├── worldchat.html        # M13 - Global Chat
│   ├── deelhub.html          # M14 - Share Hub
│   ├── bibliotheek.html      # M15 - Library
│   ├── ontspan.html          # M16 - Games & Relax
│   ├── groei.html            # M17 - Growth Dashboard
│   ├── dagboodskap.html      # M18 - Daily Messages
│   ├── temas.html            # M19 - Themes
│   └── dagboek.html          # M20 - Journal
├── assets/
│   └── images/
│       └── mascot/           # Wolletjie mascot images
├── package.json              # NPM configuration
└── README.md                 # This file
```

### Key Files Explained

#### `index.html`
- SPA shell with Roselt router
- Welcome overlay with API key input
- Navigation bar with 21 module buttons
- Main content area and toast notification system
- Responsive layout for mobile/tablet/desktop

#### `app.js`
- **STATE Management**: Centralized app state object
- **API Integration**: callAI() function for Anthropic API
- **Initialization**: Welcome flow, navigation setup, API dropdown
- **Utilities**: Toast notifications, library management, status indicators

#### `styles/main.css`
- **Design System**: 
  - CSS custom properties (--teal, --txt, --bg, etc.)
  - Component library (.btn, .card, .panel, .form-*)
  - Animations (@keyframes for transitions)
  - Responsive breakpoints (768px, 480px)
  - Print styles for exam papers

#### `pages/*.html`
- Each page is a self-contained module
- Inline JavaScript for module-specific logic
- Consistent form → generate → result pattern
- Integration with STATE.library for saving

---

## 🎨 Design System

### Color Palette
```css
--teal: #0D9488           /* Primary brand color */
--teal-d: #0F766E         /* Dark teal for text */
--teal-l: #CCFBF1         /* Light teal for backgrounds */
--teal-ll: #F0FDFA        /* Extra light teal */
--bg: #F8FAFC             /* Main background */
--bg2: #F1F5F9            /* Secondary background */
--txt: #0F172A            /* Primary text */
--txt2: #475569           /* Secondary text */
--txt3: #94A3B8           /* Tertiary text (hints) */
--card: white             /* Card background */
--border: #E2E8F0         /* Border color */
--error: #DC2626          /* Error state */
--success: #16A34A        /* Success state */
```

### Typography
- **Heading Font**: Fraunces (700-900 weight) - Professional, distinctive
- **Body Font**: Plus Jakarta Sans (400-800 weight) - Clean, readable
- **Scale**: 12px (captions) → 18px (body) → 32px (large headings)

### Spacing System
```css
--sp-sm: 8px
--sp-md: 16px
--sp-lg: 24px
--sp-xl: 32px
--sp-2xl: 48px
```

### Component Classes
- `.btn` (primary/secondary/ghost variants)
- `.card` (content containers)
- `.panel` (page sections)
- `.form-*` (input styling)
- `.grid` (1-4 column layouts)
- `.tn` (navigation buttons)
- `.toast` (notifications)

---

## 🔐 Security & Privacy

### API Key Management
- API key stored in `sessionStorage` (cleared on browser close)
- Optional `localStorage` for persistent settings only
- **Never** stores sensitive data permanently
- HTTPS-ready for production deployment

### Data Privacy
- All AI requests go directly to Anthropic API
- No content stored on external servers except:
  - Generated content (user chooses to save)
  - Chat history (session-only, cleared on close)
- Library saved items stay in user's browser

---

## 🌍 Localization Support

### Languages Supported
- **UI**: English (primary), with Afrikaans labels for modules
- **Content Generation**: 
  - South African: Afrikaans, English, isiZulu, isiXhosa, Sesotho, Setswana, Venda, Tsonga
  - International: French, Portuguese, Spanish, German, German, Swahili

### CAPS Curriculum Alignment
- All lesson plans follow South African National Curriculum Statement
- Grade levels R-9 with age-appropriate content
- Subject areas: Math, Languages, Natural Sciences, Social Sciences, Life Orientation
- Assessment rubrics aligned with CAPS standards

---

## 📱 Responsive Design

### Breakpoints
- **Desktop**: 1024px+ (full navigation, multi-column layouts)
- **Tablet**: 768px - 1023px (adjusted spacing, 2-column grids)
- **Mobile**: < 768px (single column, vertical navigation buttons)
- **Extra Small**: < 480px (compact mode, touch-optimized)

### Mobile Optimization
- Touch-friendly button sizes (min 44px)
- Readable text without zoom (16px base)
- Optimized for portrait and landscape
- Print-friendly stylesheets for exam papers

---

## 🚀 Development & Customization

### Running the Development Server

```bash
# Start server on port 3000
npm start

# Server runs indefinitely; press Ctrl+C to stop
```

### Adding a New Module

1. **Create the page file**: `pages/module-name.html`
2. **Follow the pattern**:
   ```html
   <section id="panel-name" class="panel">
     <!-- Content here -->
   </section>
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       // Module logic
     });
   </script>
   ```
3. **Use existing utilities**:
   - `callAI(systemPrompt, userMessage)` - API calls
   - `saveToLibrary(item)` - Save to library
   - `showToast(message, type, duration)` - Notifications
   - `STATE` object - Centralized state

4. **Add navigation button** in `index.html`:
   ```html
   <button class="tn" data-panel="module-name">
     <i class="bi bi-icon-name"></i> Module Name
   </button>
   ```

### Styling Custom Components

Use CSS custom properties for consistency:

```css
.custom-card {
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: var(--radius-md);
  padding: var(--sp-lg);
  color: var(--txt);
}
```

### Testing in Different Environments

- **Local**: `npm start` opens http://localhost:3000
- **Network**: Access via `http://[your-ip]:3000` for testing on other devices
- **Production**: Deploy to any static hosting (Vercel, Netlify, GitHub Pages)

---

## 📦 Building for Production / Apps

### Deployment Options

1. **Web Hosting** (Vercel, Netlify, GitHub Pages):
   - No build step required
   - Simply upload project files
   - Works immediately

2. **Desktop Apps** (Electron):
   - Wrap this project with Electron
   - Target: macOS, Windows, Linux
   - API key can be embedded or prompted

3. **Mobile Apps** (Capacitor/React Native):
   - Convert to TypeScript React wrapper
   - Target: iOS, Android
   - Progressive Web App (PWA) ready

### Environment Variables (for future API changes)

Create a `.env.local` file (not committed):
```
VITE_API_KEY=your-api-key-here
VITE_API_ENDPOINT=https://api.anthropic.com/v1/messages
```

---

## 🐛 Troubleshooting

### "API Connection Failed"
- Verify API key starts with `sk-ant-`
- Check internet connection
- Ensure API key has credits remaining
- Check browser console for detailed error messages

### Module Not Loading
- Verify page file exists in `pages/` directory
- Check browser console for JavaScript errors
- Ensure Roselt.js is properly loaded from CDN
- Clear browser cache and reload

### Styles Not Applying
- Check CSS variables are defined in `:root`
- Verify no conflicting browser extensions
- Try in incognito/private mode
- Clear browser cache

### Memory/Performance Issues
- Clear chat history periodically
- Archive old library items
- Use browser DevTools to check memory usage
- Consider session storage limits

---

## 📚 API Documentation

### Anthropic Claude Integration

**Endpoint**: `https://api.anthropic.com/v1/messages`
**Model**: `claude-3-5-sonnet-20241022`
**Max Tokens**: 1024 (per request)
**Authentication**: API key in header

**Example Usage** (in app.js):
```javascript
const response = await callAI(
  'You are a helpful teacher assistant.',
  'Generate 5 worksheet questions about fractions'
);
```

### STATE Object Structure

```javascript
window.STATE = {
  apiKey: 'sk-ant-...',           // Anthropic API key
  isConnected: true,              // API connection status
  library: [                       // Saved items
    { id, title, content, type, date, time, icon }
  ],
  chatHistory: [],                // Current chat messages
  currentTheme: 'teal',           // Active theme
  currentFont: 'plus-jakarta',    // Active font family
  textSize: 100                   // Text size percentage
}
```

---

## 📞 Support & Contributing

### Common Questions

**Q: Can I use this offline?**
A: Most modules work offline once loaded. AI-powered modules (Chat, Planning, etc.) require internet for API calls.

**Q: How do I backup my generated content?**
A: Use the "Save to Library" button on each module, then export from Library or print directly.

**Q: Can I customize the design?**
A: Yes! Edit `styles/main.css` to change colors, fonts, or layouts. All design is in CSS variables.

**Q: Will this work on my iPad?**
A: Yes! The app is fully responsive and touch-optimized for tablets.

**Q: How do I export my journal entries?**
A: From the Journal module, use browser's print function or copy entries manually.

---

## 📄 License & Attribution

- **Roselt.js**: Used under its open-source license
- **Bootstrap Icons**: Free icons under MIT license
- **Google Fonts**: Open source fonts under SIL license
- **Anthropic API**: Commercial service with terms of use

---

## 🎯 Future Enhancements (Roadmap)

- [ ] Offline service worker for offline-first architecture
- [ ] Real-time multiplayer lesson planning
- [ ] Advanced analytics dashboard for learner progress
- [ ] Integration with school management systems (ITS, IBIS)
- [ ] Video lesson generation with AI narration
- [ ] Automated class performance reports
- [ ] Integration with WhatsApp Business API
- [ ] Mobile app versions (iOS, Android)
- [ ] Collaborative features for teacher teams
- [ ] Integration with assessment platforms

---

## 👨‍💻 Development Team

Built with ❤️ for South African educators by [Ian Marais]

**Version**: 2.0.0
**Last Updated**: 2024
**Status**: Production Ready

---

## 📧 Contact & Feedback

For bugs, feature requests, or general feedback, please open an issue or contact support.

**Made with passion for South African Teachers ✨**
