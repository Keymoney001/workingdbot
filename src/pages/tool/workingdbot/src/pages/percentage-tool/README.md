### Step 1: Clone the Repository

First, clone the `percentage-tool` repository to your local machine:

```bash
git clone https://github.com/Keymoney001/percentage-tool.git
```

### Step 2: Copy Files to Your Repository

Navigate to the cloned repository and copy the necessary files into your current repository. You might want to copy the entire contents or just specific files depending on your needs.

```bash
cd percentage-tool
# Copy files to your current repository
cp -r * /path/to/your/current/repository/
```

### Step 3: Integrate into Your Current Repository

1. **Navigate to Your Current Repository:**

   ```bash
   cd /path/to/your/current/repository/
   ```

2. **Add the Copied Files:**

   If you copied the files directly, you can now add them to your repository:

   ```bash
   git add .
   ```

3. **Commit the Changes:**

   Commit the changes with a meaningful message:

   ```bash
   git commit -m "Integrated percentage-tool into the repository"
   ```

### Step 4: Set Up as a Page

If you are using a static site generator (like Jekyll, Hugo, etc.) or a framework (like React, Vue, etc.), you will need to set up a route or page to access the percentage tool.

1. **Create a New Page:**

   Depending on your setup, create a new HTML or markdown file for the percentage tool. For example, if you are using Jekyll, you might create a new file in the `_pages` directory:

   ```markdown
   ---
   layout: page
   title: Percentage Tool
   permalink: /percentage-tool/
   ---

   <h1>Percentage Tool</h1>
   <div id="percentage-tool"></div>
   <script src="path/to/percentage-tool.js"></script>
   ```

2. **Link to the Page:**

   Make sure to link to this new page from your main navigation or wherever appropriate in your site.

### Step 5: Test Locally

Run your local server to test the integration:

```bash
# For example, if using Jekyll
jekyll serve
```

Visit `http://localhost:4000/percentage-tool/` to see if the percentage tool is working as expected.

### Step 6: Push Changes to Remote Repository

Once everything is working correctly, push your changes to the remote repository:

```bash
git push origin main
```

### Additional Notes

- Ensure that any dependencies required by the percentage tool are also included in your project.
- If the percentage tool uses any specific libraries or frameworks, make sure they are compatible with your current setup.
- You may need to adjust styles or scripts to fit the design of your current repository.

By following these steps, you should be able to successfully integrate the percentage tool into your current repository and set it up as a page.