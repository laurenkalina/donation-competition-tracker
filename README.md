# donation-competition-tracker

A lightweight, static webpage to track donation amounts in an office donation competition. In our case, the manager whose employees donated the most "won" a pie in the face. This page is intentionally simple (it must be manually updated as donations come in), but it enables participants to easily check the competition status from their computer or smartphone. You can view a live example [here.](https://laurenkalina.github.io/donation-competition-tracker/)

## Setup Instructions

### 1. Add Images
Place the competitors' photos and your logo image in `images/`.

### 2. Update Competitor Data

Edit competitor names, donation amounts, and image paths directly in `index.html`:

```javascript
    // Define competitor data (name, donation, and image path)
    const competitorData = [
      { name: 'Competitor 1', donation: 1200, image: 'images/competitor.png' },
      { name: 'Competitor 2', donation: 800, image: 'images/competitor.png' },
      { name: 'Competitor 3', donation: 1500, image: 'images/competitor.png' },
      { name: 'Competitor 4', donation: 0, image: 'images/competitor.png' }
    ];
```

### 3. Update Logo, Title, and Subtitle

Modify the header section in `index.html` to match your event:

```html
<img src="images/logo.png" alt="Logo" class="img-fluid">
      </div>
      <div class="col">
        <h1><b>Donation Competition Tracker</b></h1>
        <p>Vote for a competitor to win by donating [here]! The competitor with the highest donations will win [prize]. All donations go to [charity]. This tracker will be updated [frequency].</p>
```

### 4. Customize Styling (optional)

Adjust the colors, fonts, and styles as needed by editing the CSS section in `index.html`.

### 5. Publish Your Tracker

Host the webpage using [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) or another static hosting service.
