# HTML Button Type Attribute Omission

This repository demonstrates a common HTML error: omitting the `type` attribute in a `&lt;button&gt;` element within a form. This can cause unexpected form submission behavior, especially when the button is intended to submit the form. 

The `bug.html` file shows the problematic code, while `bugSolution.html` provides the corrected version.

**The issue:** Without a specified `type`, the browser may default the button to a `type="submit"`, potentially causing unwanted form submissions or interfering with JavaScript-based form handling. 

**The solution:** Always explicitly define the `type` attribute (e.g., `type="submit"`, `type="button"`, `type="reset"`) to ensure predictable and consistent functionality.