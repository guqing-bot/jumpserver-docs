# JumpServer Documentation (Mintlify)

This directory contains the JumpServer documentation converted to Mintlify format.

## Quick Start

1. **Install Mintlify CLI**:
```bash
npm i -g @mintlify/cli
```

2. **Preview locally**:
```bash
cd jumpserver-docs
mintlify dev
```

3. **Build for production**:
```bash
mintlify build
```

## Structure

- `mint.json` - Main configuration file for Mintlify
- `*.mdx` - Documentation pages in MDX format
- `images/` - Static assets and images
- `favicon.svg` - Site favicon

## Features

- ✅ Fully converted from Nextra to Mintlify format
- ✅ All 52 documentation pages converted
- ✅ Proper navigation structure
- ✅ Mintlify components (Steps, Tabs, Cards, etc.)
- ✅ Image assets copied and properly linked
- ✅ Enterprise Edition indicators
- ✅ Responsive design ready

## Conversion Details

The documentation has been converted from the original Nextra format with the following improvements:

1. **Component Conversion**:
   - `<Steps>` components properly formatted
   - `<Tabs>` for platform-specific content
   - `<CardGroup>` for navigation aids
   - `<Frame>` for images
   - `<Note>`, `<Warning>`, `<Info>`, `<Tip>` callouts

2. **Navigation Structure**:
   - Organized into logical groups
   - Proper hierarchical structure
   - All pages included and properly linked

3. **Content Quality**:
   - Proper frontmatter with titles and descriptions
   - Clean markdown formatting
   - Enterprise Edition features marked with 🎯
   - Consistent styling throughout

## Deployment

To deploy this documentation:

1. Push to a Git repository
2. Connect to Mintlify dashboard
3. Configure domain and settings
4. Deploy automatically on commits

For more information, see [Mintlify documentation](https://mintlify.com/docs).
