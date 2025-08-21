# Pokemon TCG Analyzer

A minimal and elegant web application for analyzing Pokemon Trading Card Game wishlists to find the most valuable card sets.

## Features

- **Excel File Upload**: Import your Pokemon card wishlist from Excel files (.xlsx)
- **Smart Set Analysis**: Automatically calculates which card sets provide the best value
- **Minimal Design**: Clean, modern interface inspired by minimalist design principles
- **Card Details**: View all cards in the best recommended set
- **Sortable Data Table**: Click column headers to sort card data
- **Rarity Color Coding**: Visual distinction between different card rarities
- **Drag & Drop Support**: Easy file upload with drag and drop functionality

## How to Use

1. **Prepare Your Excel File**
   - Create an Excel file with the following columns:
     - `Set`: Card set code (e.g., A1, A1a)
     - `Number`: Card number
     - `Name`: Card name
     - `Rarity`: Card rarity level
     - `RarityCode`: Rarity code
     - `Packs`: Pack name/type
     - `DateAdded`: Date when card was added

2. **Upload and Analyze**
   - Open `index.html` in your web browser
   - Click "เลือกไฟล์" or drag and drop your Excel file
   - The application will automatically analyze and display results

3. **View Results**
   - **Best Set Recommendation**: Shows the most valuable set with all its cards
   - **Set Analysis**: All sets ranked by value score
   - **Data Table**: All cards with sortable columns

## Rarity Types Supported

The application supports the following rarity types with custom color coding:

- Common (Gray)
- Uncommon (Green)
- Rare (Blue)
- Double Rare (Purple)
- Art Rare (Pink)
- Super Rare (Yellow)
- Special Art Rare (Pink)
- Immersive Rare (Orange)
- Crown Rare (Amber)
- Shiny (Teal)
- Shiny Super Rare (Gradient)

## Value Calculation

The application calculates set value based on:
- Total number of cards in the set
- Number of different pack types needed
- Cards per pack efficiency
- High-value card bonuses (Special Art, Double Rare, Super Rare)

## Technical Details

- **Pure JavaScript**: No framework dependencies
- **Tailwind CSS**: For styling (via CDN)
- **SheetJS**: For Excel file processing
- **Responsive Design**: Works on desktop and mobile devices

## Browser Compatibility

Works with all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available for personal use.

## Contributing

Feel free to submit issues and enhancement requests!

## Screenshots

The application features:
- Clean upload interface
- Summary statistics cards
- Best set recommendation with card details
- Sortable data table with rarity badges

---

Made with ❤️ for Pokemon TCG collectors