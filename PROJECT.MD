# PROJECT.MD

## Project Overview
This project is a responsive webpage titled **Satellite To Surface**. It showcases striking satellite images and encourages community events centered around nature and exploration. The project uses HTML and CSS, with Google Fonts for typography.

---

## index.html Breakdown

### 1. HTML Document Structure & Head
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Satellite To Surface</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
  </head>
```
**Description:**  
This section sets up the HTML document type and opens the HTML and head tags. The `<title>` sets the browser tab text. The `link` tags connect the main CSS stylesheet and import the Montserrat font from Google Fonts to enhance typography.

---

### 2. Navigation Bar
```html
<div class="bar">
  <ul>
    <a href=""><li>Events</li></a>
    <a href=""><li>Results</li></a>
    <a href=""><li>Partnering Restaurants</li></a>
  </ul>
</div>
```
**Description:**  
This code block creates the navigation bar, allowing users to quickly access the Events, Results, and Partnering Restaurants sections. The bar appears at the top (and later, the bottom) of the page for easy navigation.

---

### 3. Intro Section
```html
<div class="intro">
  <h1>Satellite To Surface</h1>
</div>
```
**Description:**  
This section displays the main title of the site, making it prominent to visitors as soon as they land on the page.

---

### 4. Summary Section
```html
<div class="summary">
  <h2>Fascinating Pictures Brought To Life.</h2>
  <p>From the wonders of our jungles to the mystery's and spectacular formation of our deserts, picturs from the satilite's orbiting our planet alow us to witnes the beauty of planet earth, our home.</p>
  <p>For the lovers of Mother nature as a specticle<a href="">City Shoes</a>.</p>
</div>
```
**Description:**  
The summary introduces the theme and mission of the site, describing the fascination with satellite imagery and nature. It also includes a link (currently empty) for additional exploration.

---

### 5. First Photo Gallery
```html
<div class="photos">
  <img src="https://static-assets.codecademy.com/Paths/front-end-career-path/responsive-club-website/tunnel-runners.jpg" />
  <img src="https://static-assets.codecademy.com/Paths/front-end-career-path/responsive-club-website/meetup-wine.jpg" />
  <img src="https://static-assets.codecademy.com/Paths/front-end-career-path/responsive-club-website/runners-grayscale.jpg" />
</div>
```
**Description:**  
This block displays a gallery of three engaging images, visually supporting the site's focus on exploration, community, and activity.

---

### 6. Testimonial Section
```html
<div class="testimonial">
  <h1>"I build my weeknight plans around their events. I can exercise and meet new people every week!"</h1>
  <p>-Bryce R. - financial advisor/frequent runner since 2018</p>
</div>
```
**Description:**  
A testimonial from a participant adds credibility and a personal touch, encouraging visitors to join the community events.

---

### 7. Second Photo Gallery
```html
<div class="photos">
  <img src="https://static-assets.codecademy.com/Paths/front-end-career-path/responsive-club-website/coffeshop.jpg" />
  <img src="https://static-assets.codecademy.com/Paths/front-end-career-path/responsive-club-website/marathon-runners.jpg" />
  <img src="https://static-assets.codecademy.com/Paths/front-end-career-path/responsive-club-website/hangouts.jpg" />
</div>
```
**Description:**  
Another set of three images continues the visual storytelling, showcasing the social aspect of the community.

---

### 8. Meetup Invitation
```html
<div class="meetup">
  <h1>Come join the fun!</h1>
  <img src="https://static-assets.codecademy.com/Paths/front-end-career-path/responsive-club-website/runners-church.jpg" />
  <h1>We meet every evening in the city square at 7PM!</h1>
</div>
```
**Description:**  
This section invites users to participate in the regular meetups, reinforcing the community-driven theme.

---

### 9. Footer Navigation
```html
<div class="bar">
  <ul>
    <a href=""><li>Events</li></a>
    <a href=""><li>Results</li></a>
    <a href=""><li>Partnering Restaurants</li></a>
  </ul>
</div>
```
**Description:**  
Repeats the navigation bar at the bottom of the page, ensuring users can easily move between sections from anywhere on the site.

---

### 10. Inline Script (Auto-inserted)
```html
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'92b9862aa86b9586',t:'MTc0Mzg2MTEyNy4wM[...]
</script>
```
**Description:**  
This appears to be an automatically injected script, possibly from a service like Cloudflare. It is not essential to the core functioning of your project.

---

## Notes
- **style.css** handles all the visual styling (not shown here, but equally important).
- All images are sourced externally.
- There are some minor typos in the HTML (e.g., "picturs" instead of "pictures", "satilite's" instead of "satellites", "specticle" instead of "spectacle"); consider correcting these for clarity and professionalism.

---

## How to Use
- Open `index.html` in a browser to view the site.
- Edit `style.css` to change the look and feel.
- Add more content or update sections as your project grows.

---