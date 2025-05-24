# Course Assets

Public assets repository for Math 253 (Calculus III) course materials. This repository serves static assets via GitHub Pages for integration with Blackboard Ultra.

## Structure

```
math253/
├── images/          # Course images, icons, figures
└── interactive/     # Interactive widgets and demos
```

## GitHub Pages URL

All assets are served from: `https://jjohnson-47.github.io/course-assets/`

### Image Usage in Blackboard

```html
<img src="https://jjohnson-47.github.io/course-assets/math253/images/vector-icon.svg"
     alt="Vector icon" style="max-width:100%;" />
```

### Interactive Widget Usage

```html
<iframe src="https://jjohnson-47.github.io/course-assets/math253/interactive/demo-name/"
        width="100%" height="600" loading="lazy" style="border:none;"></iframe>
```

## Available Assets

### Icons
- `vector-icon.svg` - Vector mathematics icon
- `partial-derivatives-icon.svg` - Partial derivatives icon  
- `vector-analysis-icon.svg` - Vector analysis icon

## Notes

- This repo includes `.nojekyll` to bypass Jekyll processing
- All assets must use absolute URLs when embedded in Blackboard
- GitHub Pages has 1 GB storage and ~100 GB/month bandwidth limits
