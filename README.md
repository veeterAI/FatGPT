Destroy minified chatbots with a single line of code!

![Before](https://github.com/veeterAI/FatGPT/blob/main/Screenshot%202024-12-02%20at%2019-37-27%20Bookmarklet%20to%20Resize%20Chat.png)

Copy the contents of bookmarklet.js into the "URL" section of your favorite browser's bookmarks, click on it when you're inside ChatGPT's chat window, and enjoy!

```
javascript:(function(){
    document.querySelectorAll('.md\\:max-w-3xl').forEach(el => el.style.maxWidth = 'none');
})();
```

![After](https://github.com/veeterAI/FatGPT/blob/main/Screenshot%202024-12-02%20at%2019-37-56%20Bookmarklet%20to%20Resize%20Chat.png)