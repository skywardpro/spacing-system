# Spacing System

This SCSS utility provides a systematic way to manage and apply consistent spacing throughout your web projects using pre-defined spacing values, shorthand notations, and responsive breakpoints.

## Features

- **Pre-defined Spacing Values**: Easy to adjust spacing scales from "auto" to "5xl" ensuring design consistency.
- **Responsive Breakpoints**: Supports multiple devices with predefined breakpoints from `xs` to `fullhd`.
- **Shorthand Notations**: Simplified application of margins and paddings using shorthand notations.

## Getting Started

### Prerequisites

Ensure you have a SCSS compiler installed. You can use [Sass](https://sass-lang.com/install), another compatible compiler, or an online tool like [SassMeister](https://www.sassmeister.com/) to compile the SCSS into CSS.

### Installation

Clone this repository or download the SCSS file directly into your project folder.

```git clone https://github.com/skywardpro/spacing-system.git```

### Usage

**1. Import the `spacing-system.scss` file into your main stylesheet, or compile it into a CSS file and use that instead.**


**2. Use the generated classes in your HTML to manage spacing. For example:**

```
<div class="m-2xl mt-5xl">
  <!-- Your content here -->
</div>
```
_Margin is set to '2xl' for all devices, but margin-top is specifically set to '5xl' for all devices, overriding the general margin._


**3. Responsive classes are also generated and can be used like:**

```
<div class="m-xl mt-2xl__desktop">
  <!-- Your content here -->
</div>
```
_Margin is 'xl' across all devices, but at the 'desktop' breakpoint, margin-top is increased to '2xl'._


## Customization

To customize spacing values or breakpoints, modify the **$space-values** and **$breakpoints** maps in the `spacing.scss` file. Use your preferred SCSS compiler or an online tool like SassMeister to experiment with and generate your custom CSS.

## Contributing

Contributions are welcome! Please open an issue to discuss your ideas or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.