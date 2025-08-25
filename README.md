# Southwest Concrete Paving Knowledge Base

This repository contains the **internal knowledge base documentation** for Southwest Concrete Paving Co.  
It is intended for use by employees and authorized contractors.  

All changes are submitted through GitHub pull requests and reviewed by the repository maintainer before being merged into `main`.  

This knowledge base is proprietary and intended for internal use only by employees and authorized contractors.

## Getting started

1. **Create a GitHub account**: If you don't already have a GitHub account, [sign up here](https://github.com/join).

2. **Familiarize yourself with GitHub**: If you're new to GitHub, take some time to understand the basics of Git and GitHub. [GitHub's Quickstart Guide](https://docs.github.com/en/get-started/quickstart) is a great resource.

## Making contributions

### Editing content

1. **Navigate to the repository**: Go to the [Southwest Concrete Paving Knowledge Base repository](https://github.com/spizeck/SWCP).

2. **Find the file you want to edit**: The content is organized in Markdown files. Navigate to the specific file you want to update. The markdown files are located in the `docs` folder.

3. **Edit the file**:
   - Click the pencil icon (Edit this file) on the top right of the file view.
   - Make your changes directly in the GitHub editor.
   - You can use the `Preview` tab to check your changes.

### Creating a pull request

After editing the content:

1. **Scroll down to 'propose changes'**:
   - Add a brief but descriptive title for your changes.
   - Optionally, add a more detailed description.

2. **Click 'Propose Changes'**: This will create a new branch in the repository and take you to the 'Open a pull request' page.

3. **Open a pull request**:
   - Review your changes.
   - Click 'Create pull request'.
   - This allows repository maintainers to review your changes before merging them into the main content.

## Adding new content

### Adding a new Markdown file

1. **Create a new file**:
   - In the appropriate directory within the `docs` folder, click 'Add file' and then 'Create new file'.
   - For example, to add a new file in the Equipment section: navigate to `docs/Equipment/`, then create your file (e.g., `new-equipment-guide.md`).

2. **Write your content**:
   - Use Markdown to write your content. If you’re new to Markdown, here's a [basic guide](https://www.markdownguide.org/basic-syntax/).

3. **Save and propose the new file**:
   - Name your file at the top (ensure it ends with `.md`).
   - Scroll down, add a commit message, and propose the new file.

### Linking the new file in `mkdocs.yml`

1. **Edit `mkdocs.yml`**:
   - Navigate to the root of the repository and open `mkdocs.yml`.
   - Click the pencil icon to edit.

2. **Add your new file to the navigation**:
   - In the `nav` section, add a link to your new Markdown file under the appropriate category.
   - Follow the existing format. For example:
     ```yaml
     - Equipment:
       - New Equipment Guide: Equipment/new-equipment-guide.md
     ```

3. **Propose the Change**:
   - Scroll down, add a commit message, and propose the change.

### Adding images

1. **Place images in the correct directory**:
   - Images should be placed in an `Images` folder within the relevant section.
   - For example, for equipment-related images, use `docs/Equipment/Images/`.

2. **Add images to your Markdown file**:
   - Use the Markdown syntax to add images. For example:
     ```markdown
     ![Alt text for the image](Equipment/Images/your-image.jpg)
     ```
   - Replace `your-image.jpg` with the name of your image file.

3. **Commit and propose the changes**:
   - After adding images to the `Images` folder and referencing them in your Markdown file, commit and propose these changes as described earlier.

## Creating pull requests for new content

After adding new content or making changes:

1. **Follow the same process**: As with editing content, scroll down to 'Propose changes', add a descriptive title and description, and create a pull request.

2. **Review and approval**:
   - The repository maintainers will review your pull request.
   - If changes are approved, they will be merged into the main content.

Remember, quality and clarity are key in your contributions. If you’re adding new sections or significant content, consider discussing it with the team or the repository maintainers first.


## Best practices for contributions

- **Clear and concise writing**: Keep your contributions clear, concise, and factual.  
- **Check grammar and spelling**: Ensure your text is free of errors. Use available tools (such as grammar checkers) to help with this.  
- **Stick to the format**: Follow the existing structure and formatting of the documents.  
- **Be respectful and constructive**: When providing feedback on others' contributions, be respectful and constructive.  

## Writing in Markdown

Markdown is a lightweight and easy-to-use syntax for styling text on the web. If you are not familiar with Markdown, here is a resource to get you started:

- [Markdown Guide](https://www.markdownguide.org/basic-syntax/): A comprehensive guide to Markdown syntax, covering everything from basic to advanced usage.

We recommend familiarizing yourself with the basics of Markdown to ensure your contributions are formatted correctly.

## Need help?

If you have any questions or need assistance with the contribution process, please reach out to the repository maintainer ([@spizeck](https://github.com/spizeck)).

## License

See [LICENSE.md](LICENSE.md) for license details.

Thank you for helping improve the Southwest Concrete Paving Knowledge Base!