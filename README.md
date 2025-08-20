# My Reading Tracker

A beautiful, feature-rich personal reading progress tracker built with vanilla HTML, CSS, and JavaScript. Track your reading journey with an elegant, library-inspired interface that keeps all your data completely private in your browser.

## Features

### Core Reading Management
- **Book Library**: Add, edit, and delete books with title, author, pages, and optional cover images
- **Progress Tracking**: Update reading progress with number inputs and interactive sliders
- **Visual Progress**: Color-coded progress bars showing reading status at a glance
- **Status Management**: Automatic categorization (Not Started, In Progress, Completed)

### Organization & Discovery
- **Smart Search**: Find books by title or author with instant filtering
- **Flexible Filtering**: Filter by reading status or custom tags
- **Multiple Sort Options**: Sort by title, author, progress, pages, or date added
- **Tag System**: Organize books with custom tags for easy categorization
- **Tag-based Filtering**: Click tag chips to quickly filter your library

### Reading Sessions & Analytics
- **Session Tracking**: Log reading sessions with date, duration, and pages read
- **Reading Timeline**: View your reading history with expandable session summaries
- **Statistics Dashboard**: Track total books, pages read, completion rates, and status breakdowns
- **Progress Analytics**: Visual insights into your reading habits and completion trends

### Personal Touch
- **Favorites System**: Mark books as favorites with star toggle
- **5-Star Rating**: Rate completed books from 1-5 stars
- **Personal Notes**: Add thoughts, intentions, or reminders for each book
- **Progress Milestones**: Track progress toward completion goals

### User Experience
- **Dark Mode**: Toggle between light and dark themes with automatic persistence
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Accessible Interface**: Screen reader friendly with proper ARIA labels and semantic HTML
- **Cozy Aesthetic**: Library-inspired design with warm colors and elegant typography
- **Interactive Controls**: Smooth animations and hover effects for engaging experience

### Data Management & Privacy
- **Import/Export**: Backup and share your library with JSON export/import functionality
- **Local Storage**: All data stays completely private in your browser - no accounts or servers
- **Data Persistence**: Your library is automatically saved locally across sessions
- **Cross-Device Sync**: Export from one device, import on another for manual synchronization
- **Data Integrity**: Robust error handling and data validation on import

## Quick Start

1. **Download** the complete application (single `index.html` file)
2. **Open** the file in any modern web browser (Chrome, Firefox, Safari, Edge)
3. **Add your first book** by clicking the "Add book" button in the toolbar
4. **Start tracking** your reading progress immediately with sliders and quick actions

No installation required, no accounts needed, works completely offline!

## Screenshots

<img width="2976" height="1468" alt="Screenshot 2025-08-20 at 10 19 30 AM" src="https://github.com/user-attachments/assets/977ba2de-4026-423c-b54d-c410d7c86f90" />


<img width="2978" height="1454" alt="Screenshot 2025-08-20 at 10 19 36 AM" src="https://github.com/user-attachments/assets/e5843d19-354b-47e7-9972-d61ae3c14e2f" />


## Detailed Usage Guide

### Adding Books
1. Click "Add book" button in the toolbar
2. Fill in required fields: title, author, and total pages
3. Optionally add:
   - Cover image URL for visual appeal
   - Comma-separated tags for organization
   - Starting progress if already reading
   - Personal notes or reading intentions
4. Click "Save" to add to your library

### Tracking Progress
- **Number Input**: Directly enter pages read
- **Interactive Slider**: Drag to adjust progress with live updates
- **Quick Actions**: Use +10, -5, Mark Done, or Reset buttons
- **Real-time Updates**: Progress bars and statistics update instantly
- **Session Logging**: Record reading sessions with time and page details

### Organization Features
- **Search**: Type in search box to find books by title or author
- **Status Filter**: Use dropdown to show only books with specific status
- **Tag Filtering**: Click tag chips to filter by categories you've created
- **Sorting**: Choose from multiple sort options (recent, alphabetical, progress, etc.)
- **Multi-level Organization**: Combine search, filters, and tags for precise book discovery

### Reading Sessions
1. Click "Session" button on any book card
2. Set date, reading duration (minutes), and pages covered
3. Sessions automatically update your overall progress
4. View session history by expanding the sessions list
5. Sessions are sorted chronologically for easy tracking

### Data Management
- **Export**: Click "Export" to download complete library as JSON file
- **Import**: Click "Import" and select previously exported JSON file
- **Backup Strategy**: Regular exports serve as backups of your reading data
- **Data Portability**: JSON format ensures data can be used with other applications

## Browser Compatibility

Fully supported in all modern browsers:
- **Chrome/Chromium** 90+
- **Firefox** 88+
- **Safari** 14+
- **Microsoft Edge** 90+
- **Mobile browsers** (iOS Safari, Chrome Mobile, Samsung Internet)

## Privacy & Security Features

- **100% Client-Side**: No data ever leaves your browser or device
- **No Tracking**: Zero analytics, cookies, or tracking scripts
- **Offline Capable**: Works completely offline after initial page load
- **Local Storage Only**: Data stored securely in browser's localStorage API
- **No Network Requests**: No external API calls or data transmission
- **Self-Contained**: Single file contains entire application

## Technical Implementation

### Architecture
- **Vanilla JavaScript**: No frameworks or external dependencies
- **Progressive Enhancement**: Graceful degradation for accessibility
- **Semantic HTML5**: Proper document structure and ARIA labels
- **CSS Custom Properties**: Modern styling with comprehensive theme support
- **Event-Driven Architecture**: Efficient DOM manipulation and state management

### Key Technologies
- **LocalStorage API**: Persistent data storage
- **File API**: Import/export functionality
- **CSS Grid & Flexbox**: Responsive layout system
- **CSS Transitions**: Smooth animations and interactions
- **ES6+ Features**: Modern JavaScript with proper error handling

### Performance Optimizations
- **Efficient Rendering**: Minimal DOM manipulation with targeted updates
- **Debounced Search**: Optimized search input with 120ms debounce
- **Lazy Rendering**: Smart re-rendering only when necessary
- **Memory Management**: Proper cleanup and garbage collection

## File Structure

```
reading-tracker/
├── index.html          # Complete single-file application
│                       # Contains HTML structure, CSS styles, and JavaScript logic
├── README.md          # This documentation
└── examples/          # Optional: Sample export files for testing
    └── sample-library.json
```

## Customization Options

The application uses CSS custom properties for easy theming. Key customization areas:

### Color Themes
Modify the `:root` and `body.dark` CSS variables:
- Primary colors for branding
- Background and surface colors
- Text and accent colors
- Progress bar colors

### Layout Adjustments
- Grid breakpoints for responsive design
- Card spacing and sizing
- Typography scale and fonts

### Feature Extensions
The modular JavaScript architecture allows for easy feature additions:
- Additional book metadata fields
- Advanced filtering options
- Reading goal tracking
- Statistical visualizations

## Contributing

This single-file application is designed for simplicity and portability. To contribute:

1. **Test thoroughly** across different browsers and screen sizes
2. **Maintain accessibility** standards and ARIA compliance
3. **Preserve privacy** - no external dependencies or network calls
4. **Keep it self-contained** - everything must remain in the single HTML file
5. **Follow coding standards** - consistent formatting and commenting

### Reporting Issues
When reporting bugs or requesting features:
- Include browser version and operating system
- Provide steps to reproduce the issue
- Verify localStorage is enabled in your browser
- Check browser console for error messages

## License

MIT License - Free to use, modify, and distribute. See the full license text for details.

## Acknowledgments

- Inspired by the cozy aesthetics of personal libraries and bookshops
- Design influenced by modern reading applications and book management tools
- Built with accessibility, privacy, and user experience as core principles
- Typography and color palette designed for comfortable long-term use

---

**Ready to start your reading journey?** Download the HTML file and begin tracking your literary adventures today. Your books, your data, your privacy - all in one beautiful, self-contained application.
