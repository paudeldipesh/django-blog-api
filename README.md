# Django Blog API

This Django API provides endpoints to manage blog posts. It allows you to create, retrieve, update, and delete blog posts.

## Endpoints

- **GET /api/blog-posts**: Retrieves a list of all blog posts.

- **GET /api/blog-posts/{id}**: Retrieves a specific blog post by its ID.

- **POST /api/blog-posts**: Creates a new blog post. Requires JSON payload with `title`, `content`, and `published_date`.

- **PUT /api/blog-posts/{id}**: Updates an existing blog post. Requires JSON payload with `title`, `content`, and `published_date`.

- **DELETE /api/blog-posts/{id}**: Deletes a blog post by its ID.

## Sample Blog Post JSON Structure

```json
{
        "id": 1,
        "title": "Sample Blog Post",
        "content": "This is the content of the blog post.",
        "published_date": "2024-04-23T11:34:58.357879Z"
    },
```
