## Color Changer

Color Changer is a solution that aims to be super easy for developers for the template demo.
So, everyone can test and check your demo web template in various logo, color, pattern easily.

## [Demo:](https://asrmahfuz.github.io/Color-Changer/)

## How to use

#### Include CSS
First, include color-changer CSS file into your HTML head:

``` <link rel="stylesheet" href="color-changer.min.css"> ```

#### Include JS
Include color-changer js file into your HTML footer:

``` <link rel="stylesheet" href="color-changer.min.js"> ```

make stylesheet{with logo & pattern} array of objects to colorChanger() method. Here is an example stylesheet array format:

``` 
var dataColor = [
	{ 
		color: "#1abc9c",
		href: "src/colors/1abc9c.css",
		// logo: "plugin/logos/1.jpg",
		pattern: "https://www.toptal.com/designers/subtlepatterns/patterns/upfeathers.png"
	},
	{
		color: "#2C3A47",
		href: "src/colors/2C3A47.css",
		logo: "src/logos/2.jpg",
		pattern: "https://www.toptal.com/designers/subtlepatterns/patterns/restaurant.png"
	},
	{
		color: "#2ecc71",
		href: "src/colors/2ecc71.css",
		logo: "src/logos/3.jpg",
		pattern: "https://www.toptal.com/designers/subtlepatterns/patterns/school.png"
	},
	{
		color: "#9b59b6",
		href: "src/colors/9b59b6.css",
		logo: "src/logos/4.jpg",
		pattern: "https://www.toptal.com/designers/subtlepatterns/patterns/seamless_paper_texture.png"
	},
	{ 
		color: "#3498db",
		href: "src/colors/3498db.css",
		logo: "src/logos/5.jpg"
	},
	{
		color: "#e056fd",
		href: "src/colors/e056fd.css",
		logo: "src/logos/1.jpg"
	},
	{
		color: "#EAB543",
		href: "src/colors/EAB543.css",
		logo: "src/logos/2.jpg"
	},
	{
		color: "#f9ca24",
		href: "src/colors/f9ca24.css",
		logo: "src/logos/3.jpg"
	}
];

colorChanger(dataColor);

```
