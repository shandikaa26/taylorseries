# taylorseries
Trigonometry Calculation using Taylor Series Method and Rust Language

# Kalkulator Deret Taylor

A desktop application to calculate and visualize trigonometric functions using Taylor series approximations.

## Overview

This application demonstrates the Taylor series approximation for the sine, cosine, and tangent functions. It allows users to input an angle (in degrees or radians), select the number of terms for the approximation, and displays the results alongside the built-in Rust implementations for comparison.

## Features

- Calculate sine, cosine, and tangent using Taylor series
- Compare results with Rust's built-in trigonometric functions
- Display absolute differences between approximations and built-in functions
- Visualize trigonometric functions with an interactive plot
- Show detailed breakdown of Taylor series terms
- Support for both degree and radian input modes

## Mathematical Background

Taylor series are used to approximate functions as infinite sums:

- **Sine**: sin(x) = x - x³/3! + x⁵/5! - x⁷/7! + ...
- **Cosine**: cos(x) = 1 - x²/2! + x⁴/4! - x⁶/6! + ...
- **Tangent**: tan(x) = sin(x)/cos(x)

The accuracy of the approximation increases with the number of terms used.

## Installation

### Prerequisites

- Rust and Cargo (Install from [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install))

### Building and Running

1. Clone this repository
2. Navigate to the project directory
3. Run the application:

```
cargo run --release
```

## Usage

1. Enter an angle in the input field
2. Choose between degree or radian mode
3. Adjust the number of terms using the slider
4. Click "Hitung" (Calculate) to see the results
5. Use the checkboxes to toggle additional information display

## Dependencies

- eframe: Rust framework for creating GUI applications
- egui: Immediate mode GUI library for Rust

## License

This project is open source and available under the MIT License.
