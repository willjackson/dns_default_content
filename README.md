# Drupal NextJS Starter - Default Content Recipe

Default content recipe for the Drupal NextJS Starter project providing sample content types and content for headless CMS development.

## What's Included

- **3 Content Types**: Articles, Events, and Basic Pages with headless-optimized fields
- **24+ Sample Content Items**: Real-world examples for development and demonstration
- **Tags Taxonomy**: Content categorization system
- **JSON:API Configuration**: Ready for NextJS frontend consumption

## Installation

```bash
# Download the recipe
composer require willjackson/dns_default_content

# Install the recipe
drush recipe ../recipes/dns_default_content

# Clear caches
drush cache:rebuild
```

## Content Types

### Article
- Blog posts and editorial content
- Fields: title, body, hero image, tags, comments
- 10 sample articles included

### Event  
- Conferences, meetups, and community events
- Fields: title, body, event date, location, virtual flag, hero image
- 13 sample events included

### Basic Page
- Static pages and landing pages
- Fields: title, body, optional image
- Essential pages included

### Tags Vocabulary
10 taxonomy terms for content organization: AI, Community, Decoupled, Drupal, NextJS, and more.

