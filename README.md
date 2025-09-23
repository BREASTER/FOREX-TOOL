const path = require("path");
// Home page (shows dashboard)
app.get("/", (req, res) => {
  res.sendFile(path.join(__dirname, "index.html"));
});

# Forex Tool
A simple Node.js forex analysis app deployed on Render.
