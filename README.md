
# Coming Soon Landing Page  
This project is a "Coming Soon" landing page designed to provide an elegant countdown timer with an engaging gradient animation, all built using modern web technologies.  

## Features  
- **Responsive Design**: Fully responsive layout for mobile, tablet, and desktop devices.  
- **Countdown Timer**: Displays the remaining time in days, hours, minutes, and seconds.  
- **Gradient Animation**: Smoothly transitioning gradient background to add visual appeal.  
- **Modern Frameworks**: Built using **Tailwind CSS** and **Bootstrap** for styling, along with vanilla JavaScript for functionality.  
- **Accessibility**: Ensures legible typography and appropriate color contrast.  

## Technologies Used  
- **HTML5**: For the structure of the page.  
- **CSS (Tailwind CSS & Bootstrap)**: For styling the page with modern and responsive design.  
- **JavaScript**: For implementing the countdown timer functionality.  
- **Custom CSS**: For additional animations like `fadeIn` and `gradientMove`.  

## How to Use  
1. Clone or download this repository to your local machine:  
   ```bash  
   git clone https://github.com/your-username/coming-soon-page.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd coming-soon-page  
   ```  
3. Open the `index.html` file in your browser to view the page.  

## File Structure  
```  
coming-soon-page/  
├── index.html         # Main HTML file for the landing page  
├── README.md          # Project documentation  
```  

## Countdown Timer  
The countdown timer is dynamically updated using JavaScript. You can customize the target date by modifying the `targetDate` variable in the script section of `index.html`:  
```javascript  
const targetDate = new Date("2024-12-31T23:59:59").getTime();  
```  

## Preview  
To view the project, simply open the `index.html` file in any browser, or host the files on a local server to test the functionality.  

## Future Enhancements  
- Add email subscription functionality.  
- Integrate with a backend to store visitor data.  
- Enhance the animation effects for buttons and other elements.  
- Add multi-language support.  

## License  
This project is licensed under the MIT License. Feel free to modify and use it as per your needs.  

## Credits  
- [Tailwind CSS](https://tailwindcss.com)  
- [Bootstrap](https://getbootstrap.com)  
- Designed by **Udavin Wijesundara**.  
