# Micro-CMS v1
## Step 1 Inspect the Page

![](./imgs/1.png)

## Step 2 Create a new Page
![](./imgs/2.png)

## Step 3 How are pages indexed?

The URL ends with a numerical parameter representing the page index. Here, the value is 7.

```html
http:// url.ctf.hacker101.com/page/7
```
![](./imgs/3.png)

## Step 4 Look at the sequence of IDs

We can iterate through the pages by changing the last digit of the URL. Start with 1 and increment it up to 7 to replace the current index.
- Pages 1 and 2 and 7 were active
- Pages 3 and 4 and 6 were Not found
- Page 5 was Forbidden

![](./imgs/4.png)
![](./imgs/6.png)

## Step 5 Looking for a way to retrieve page contents from the Forbidden Page 5

Let's try editing it
To edit the page, simply add edit after /page and before the index page 5
```html
http:// url.ctf.hacker101.com/page/edit/5
```

![](./imgs/5.png)

## Step 6 Submit the Flag
