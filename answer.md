answers.md questions:
1. In one sentence: What does res.render(view, data) do?
    => it renders an EJS template and sends the generated HTML to the browser using the provided data.

2. What is the difference between <%= %> and <%- %>?
    => the <%= %> outputs escaped HTML for safety but <%- %> outputs unescaped HTML and is used when rendering HTML content like partials.

3. Where does Express look for EJS templates (folder path)?
    => Express looks for EJS templates in the views folder that you set using app.set("views", ...).
