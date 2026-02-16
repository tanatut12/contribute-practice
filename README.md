# Contribute Practice Project

This project is an educational project for practicing contributing and git flow.

## 🎯 Objectives

- Learn how to contribute to open source projects
- Practice using git flow and GitHub workflow
- Practice fixing code using Tailwind CSS only

## 📋 How to Claim an Issue

1. **Browse Available Issues**
   - Go to the Issues page of the repository
   - Read the details of the issue you want to fix

2. **Claim the Issue**
   - Comment on the issue saying "I'll take this issue" or similar
   - Wait for the maintainer to assign the issue to you
   - **Important:** Do not start fixing until you have been assigned

3. **Check if Issue is Available**
   - Make sure the issue doesn't have an assignee yet
   - Check comments to ensure no one else has claimed it

## 🔧 How to Practice Fixing Code (Tailwind Only)

### Important Rules
- **Use Tailwind CSS only** - Do not use inline styles or separate CSS files
- Only modify code in the `index.html` file
- Use Tailwind utility classes for styling

### Steps to Fix Code

1. **Fork Repository**
   ```bash
   # Fork the repository to your GitHub account
   ```

2. **Clone Repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/contribute-practice.git
   cd contribute-practice
   ```

3. **Create a New Branch**
   ```bash
   git checkout -b fix/issue-number-description
   # Example: git checkout -b fix/button-styling
   ```

4. **Fix the Code**
   - Open the `index.html` file
   - Modify the code according to the assigned issue
   - Use Tailwind classes only, for example:
     - `bg-blue-500` for background color
     - `text-white` for text color
     - `rounded-lg` for rounded corners
     - `hover:bg-blue-600` for hover effects

5. **Test**
   - Open `index.html` in your browser
   - Verify that your changes work correctly

6. **Commit and Push**
   ```bash
   git add index.html
   git commit -m "fix: description of your fix"
   git push origin fix/issue-number-description
   ```

7. **Create Pull Request**
   - Go to your GitHub repository
   - Click "New Pull Request"
   - Select the branch you created
   - Fill in PR details according to the template (if available)
   - Reference the issue you're fixing, e.g., "Fixes #123"

## 📝 Tailwind CSS Guidelines

### Using Tailwind Classes
- Use Tailwind utility classes only
- Common classes examples:
  - Layout: `flex`, `grid`, `block`, `inline-block`
  - Spacing: `p-4`, `m-2`, `gap-4`, `space-x-2`
  - Colors: `bg-blue-500`, `text-white`, `border-gray-300`
  - Typography: `text-lg`, `font-bold`, `text-center`
  - Effects: `shadow-md`, `rounded-lg`, `hover:bg-blue-600`

### Usage Example
```html
<button class="bg-blue-500 hover:bg-blue-600 text-white font-semibold py-3 px-6 rounded-lg shadow-md transition-colors">
  Button Text
</button>
```

## 🚀 Git Flow

### Branch Naming Convention
- `fix/issue-number-description` - For bug fixes
- `feature/issue-number-description` - For new features
- `update/issue-number-description` - For code updates

### Commit Message Format
```
fix: description of fix
feature: description of feature
update: description of update
```

## 📚 Additional Resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Git Flow Guide](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
- [GitHub Contributing Guide](https://opensource.guide/how-to-contribute/)

## ⚠️ Notes

- This project is for educational purposes only
- Use Tailwind CSS only - do not use other CSS methods
- Only modify the `index.html` file
- Read the issue description carefully before starting to fix

---

Happy Contributing! 🎉
