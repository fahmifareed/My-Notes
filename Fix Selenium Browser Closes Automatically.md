## chrome options for keeping the [browser open]

### Here Are The Steps to Fix Selenium Browser Closes Automatically & Immediately After Test Without Calling Quit or Close()
1. Type options = webdriver.ChromeOptions()
2. Now Type options.add_experimental_option("detach", True)
3. Now Type options=options inside webdriver.Chrome if You Already have Parameter You Can Seprate it By Comma (,)
4. Now Save The Project By Pressing Ctrl+S on Your Keyboard
5. Now Run The Program
6. Done!

## Code:
```ruby
options = webdriver.ChromeOptions()
options.add_experimental_option("detach", True)
driver = webdriver.Chrome(options=options)
```
