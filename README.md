# Styla

Styla is a versatile CSS library designed to simplify the styling process for *HTML* and *React* elements. 
With Styla, you can effortlessly apply styles to your elements using class (.) and id (#) selectors.


## Features

- **Easy Styling**: Styla provides a straightforward way to style elements, making it simple to apply colors, widths, heights, and all other CSS attributes.
  
- **Flexible Usage**: Whether you're working with traditional HTML or modern React components, Styla seamlessly integrates into your development workflow.

- **Comprehensive Styling**: Styla covers a wide range of styling needs, including fonts, borders, margins, padding, and more, allowing you to customize your elements to perfection.


## Getting Started

To get started with Styla, simply include the library in your project and start applying styles using class and id selectors:


*adding styla to a html document:*

<link rel="stylesheet" href="styla.css">


*adding styla to a jsx document:*

import React from 'react';
import './styla.css'; (replace with the path of your included styla file)

function MyComponent() {
  return (
    <div className="my-element">
      {/* Your content here */}
    </div>
  );
}



## Usage

Once included, you can apply styles using class and id selectors just like you would with regular CSS:


*using styla in html document:*

<div class="styla-class" id="styla-id">
  <!-- Your content here -->
</div>


*using styla in jsx document:*

function MyComponent() {
  return (
    <div class="styla-class" id="styla-id">
      {/* Your content here */}
    </div>
  );
}



## Contributing

Contributions to Styzla are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on GitHub.



## License

Styla is licensed under the MIT License. See the LICENSE file for more details.
