# Portfolio Images Directory

This directory contains the images for the Bloom3D portfolio section. The website will automatically load and display images from these subfolders.

## Directory Structure

```
images/portfolio/
├── planters/     # Custom planters and vases
├── fixtures/     # Retail fixtures and display models
├── tools/        # Functional business tools
└── prototypes/   # Rapid prototyping projects
```

## How to Add Images

1. **Add your images** to the appropriate category folder
2. **Naming convention**: Use descriptive names like `planter-1.jpg`, `fixture-2.jpg`, etc.
3. **Supported formats**: JPG, PNG, WebP
4. **Recommended size**: 800x600 pixels or larger for best quality

## Image Requirements

- **Format**: JPG, PNG, or WebP
- **Size**: Minimum 400x300px, recommended 800x600px
- **Quality**: High resolution for professional appearance
- **Aspect ratio**: 4:3 or 16:9 work best

## Example Images

The JavaScript expects these image files (add them to see the portfolio):

### Planters
- `planters/planter-1.jpg` - Modern Geometric Planter
- `planters/planter-2.jpg` - Hexagonal Planter Set
- `planters/planter-3.jpg` - Hanging Garden Planter

### Fixtures
- `fixtures/fixture-1.jpg` - Retail Display Stand
- `fixtures/fixture-2.jpg` - Product Showcase Hooks
- `fixtures/fixture-3.jpg` - Shelf Dividers

### Tools
- `tools/tool-1.jpg` - Custom Jigs
- `tools/tool-2.jpg` - Sign Holders
- `tools/tool-3.jpg` - Packaging Aids

### Prototypes
- `prototypes/prototype-1.jpg` - Product Prototype
- `prototypes/prototype-2.jpg` - Mechanical Component
- `prototypes/prototype-3.jpg` - Design Iteration

## Features

- **Automatic loading**: Website checks for images and loads them automatically
- **Filtering**: Visitors can filter by category
- **Lightbox**: Click any image to view in full size
- **Responsive**: Works on all devices
- **Keyboard navigation**: Arrow keys to navigate in lightbox

## Customization

To add new categories or change image metadata, edit the `portfolioData` array in `index.html`. 