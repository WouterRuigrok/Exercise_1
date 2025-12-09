---
agent: agent
description: 'Systematic website exploration using Playwright MCP for test planning'
tools: ['edit/editFiles', 'search', 'runCommands', 'runTasks', 'microsoft/playwright-mcp/*', 'problems', 'changes', 'testFailure', 'openSimpleBrowser', 'fetch']
model: 'GPT-4.1'
---

# test login functionality

Testing the login functionality of a website to ensure it works as expected.

## Testing Mission
You will be given a website URL with a login feature. Your task is to:
1. **Access the Login Page** - Navigate to the login page of the website.
2. **Input Valid Credentials** - Enter a set of valid username and password.
3. **Submit the Form** - Click the login button to submit the form.
4. **Verify Successful Login** - Check for indicators of a successful login (e.g.,
    redirection to a dashboard, presence of a logout button).
