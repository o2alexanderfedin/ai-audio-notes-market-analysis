# Document Organization Rules

## Directory Structure

### 1. Requirements
- `/requirements/` - All requirement documents
  - `/requirements/functional/` - Functional requirements
  - `/requirements/technical/` - Technical requirements
  - `/requirements/business/` - Business requirements

### 2. Documentation
- `/docs/` - General documentation
  - `/docs/api/` - API documentation
  - `/docs/user/` - User guides and manuals
  - `/docs/technical/` - Technical specifications

### 3. Design
- `/design/` - Design documents
  - `/design/architecture/` - System architecture
  - `/design/ui-ux/` - UI/UX designs
  - `/design/database/` - Database schemas

### 4. Analysis
- `/analysis/` - Analysis documents
  - `/analysis/market/` - Market analysis
  - `/analysis/competitive/` - Competitive analysis
  - `/analysis/feasibility/` - Feasibility studies

### 5. Reports
- `/reports/` - Various reports
  - `/reports/progress/` - Progress reports
  - `/reports/testing/` - Test reports
  - `/reports/performance/` - Performance reports

### 6. Meeting Notes
- `/meetings/` - Meeting documentation
  - `/meetings/YYYY-MM/` - Organized by year and month

### 7. Resources
- `/resources/` - Reference materials
  - `/resources/templates/` - Document templates
  - `/resources/guides/` - Process guides
  - `/resources/standards/` - Coding standards, style guides

## Naming Conventions

1. Use lowercase with hyphens for directories: `user-guides`
2. For documents: `YYYY-MM-DD-document-name.md`
3. Version documents: `document-name-v1.0.md`
4. Use descriptive names that indicate content

## File Formats

- Markdown (`.md`) for text documents
- PDF for final/signed documents
- Draw.io or similar for diagrams (with exported images)
- Keep source files alongside exported versions

## Organization Rules

1. Always place documents in the most specific applicable directory
2. Create subdirectories when a category has 5+ files
3. Maintain an index file in each major directory
4. Archive outdated documents to `/archive/YYYY/`
5. Keep active documents at the top level of their category
6. **Personality Profiles**: When creating target audience analysis, always generate detailed personality profiles in a `/personality-profiles/` subdirectory within the target audience folder. Each profile should include:
   - MBTI type distribution
   - Big Five personality traits
   - Core psychological drivers
   - Cognitive patterns
   - Emotional profiles
   - Social dynamics
   - Work style preferences