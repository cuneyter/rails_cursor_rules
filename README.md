# Leveraging Cursor AI's 'Cursor Rules' for Ruby on Rails Projects

## Purpose

This repository provides a comprehensive set of structured, machine-readable rules for Ruby on Rails projects. These rules are designed to enhance code navigation, context linking, and best practices enforcement within Rails codebases. The primary audience is developers and teams who use tools that can consume these rules (such as code editors or automation tools) to improve their workflow and maintain consistency across projects.

## Usage

The rules are organized in the `.cursor/rules/` directory, with each `.mdc` file corresponding to a specific Rails concept or component. Each file encodes patterns, context links, and navigation hints relevant to its topic. These rules can be used by compatible tools to:

- Identify and categorize files (e.g., controllers, models, views, specs, services, jobs, mailers, migrations, helpers, routes)
- Link related files and provide context-aware navigation (e.g., connecting controllers to their views, models, and specs)
- Surface best practices and common patterns for each Rails component
- Enable smarter code search, navigation, and automation in large Rails codebases

### Rule File Overview
- **controllers.mdc**: Rules for identifying and navigating Rails controllers and their relationships.
- **models.mdc**: Rules for models, associations, validations, and related files.
- **views.mdc**: Rules for views, layouts, partials, and their connections to controllers and helpers.
- **specs.mdc**: Rules for RSpec files and their links to implementation files.
- **services.mdc**: Rules for service objects and their usage patterns.
- **jobs.mdc**: Rules for background jobs, workers, and related patterns.
- **mailers.mdc**: Rules for mailers and their associated views and jobs.
- **migrate.mdc**: Rules for database migrations and schema-related files.
- **helpers.mdc**: Rules for helper modules and their connections to views and controllers.
- **routes.mdc**: Rules for routing files and their associations with controllers and helpers.
- **general.mdc**: General best practices and methodical approaches for code solutions.

To use these rules, integrate them with a compatible tool or workflow that supports `.mdc` rule files for Rails projects. The rules are intended to be extensible and can be adapted to fit the needs of different teams or projects.

### Generating project specific rules

You can generate rules directly in a conversation using the `/Generate Cursor Rules` command.

```
/Generate Cursor Rules
```

This will generate rules for the current project based on the files in the project.

### Best practices to generate rules

You can see the official documentation for the best practices [here](https://docs.cursor.com/context/rules#best-practices).
