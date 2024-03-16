# 👋 Welcome to Hardik's Coding Odyssey

Hi there! I'm [@hardikt29](https://github.com/hardikt29), a passionate coder exploring the realms of technology and data science.

## About Me

I'm always on the lookout for new coding challenges and innovative ideas to implement in my projects. Currently, I'm diving deep into the world of **Data Science**, unraveling insights and patterns from data.

## Let's Connect!

You can reach out to me through various channels:

- **Instagram:** <span id="instagram">@hardikktiwari</span> <button onclick="copyToClipboard('instagram')">Copy</button>
- **Twitter:** <span id="twitter">@hardikt29</span> <button onclick="copyToClipboard('twitter')">Copy</button>
- **Email:** <span id="email">hardik@hitekfoundation.co.in</span> <button onclick="copyToClipboard('email')">Copy</button>

Feel free to drop me a message or connect with me on social media. Let's collaborate and create something amazing together! 🚀

<script>
function copyToClipboard(id) {
  var text = document.getElementById(id).innerText;
  var input = document.createElement('textarea');
  input.innerHTML = text;
  document.body.appendChild(input);
  input.select();
  document.execCommand('copy');
  document.body.removeChild(input);
  alert('Copied ' + id + ' to clipboard: ' + text);
}
</script>