### Step 1: Clone the Repository

First, clone the `percentage-tool` repository to your local machine:

```bash
git clone https://github.com/Keymoney001/percentage-tool.git
```

### Step 2: Copy Files to Your Repository

Navigate to the cloned repository and copy the necessary files into your current repository. You can do this manually or using command line commands. For example:

```bash
cp -r percentage-tool/* /path/to/your/current/repository/
```

Make sure to copy only the files you need (like HTML, CSS, JS files) and not the `.git` folder.

### Step 3: Integrate into Your Current Repository

1. **Add the Files**: Move the copied files into the appropriate directory in your current repository. If you have a specific folder for pages (like `pages` or `public`), place the files there.

2. **Update Links**: If the `percentage-tool` has any links or references to its own files, update those links to point to the new locations in your current repository.

3. **Modify HTML**: If you want to integrate it as a page, you may need to create a new HTML file that links to the `percentage-tool` functionality. For example, you could create a file called `percentage.html` and include the necessary scripts and styles.

### Step 4: Set Up Routing (if applicable)

If your current repository uses a framework (like React, Vue, or a backend framework), you may need to set up routing to access the new page. For example, in a React app, you would add a route in your `App.js`:

```javascript
import Percentage from './path/to/percentage.html';

function App() {
  return (
    <Router>
      <Route path="/percentage" component={Percentage} />
    </Router>
  );
}
```

### Step 5: Test the Integration

1. **Run Your Application**: Start your application to ensure everything is working correctly.
2. **Access the New Page**: Navigate to the new page (e.g., `/percentage`) in your browser to see if the integration was successful.

### Step 6: Commit Changes

Once everything is working, commit your changes to your repository:

```bash
git add .
git commit -m "Integrated percentage-tool as a new page"
git push origin main
```

### Step 7: Documentation

Update any documentation in your repository to reflect the new page and how to use the percentage tool.

### Conclusion

You have now integrated the `percentage-tool` repository into your current repository and set it up as a page. Make sure to test thoroughly and adjust any styles or scripts as necessary to fit your application's design.