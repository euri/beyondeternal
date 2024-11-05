# Instructions

## Step 1:

Upload the `snow.js` script and images to your own server.

## Step 2:
In your html web page, add this line of code inside the `<head>` tag.

Change the `[your_website_path]` with the correct path of your website.

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.3.2/jquery.min.js"></script>
<script src="[your_website_path]/snow.js" type="text/javascript"></script>
```

## Step 3:
Then, before the `</body>` of your web page, add this code below:

```
<script type="text/javascript">
$(document).ready(function () {
    $('#wrapper').snow({
        Quantity: 20,
        SnowImage: [
            "images/snow/1.gif",
            "images/snow/2.gif",
            "images/snow/3.gif",
            "images/snow/4.gif",
            "images/snow/5.gif",
        ]
    });
});
</script>
```
`Quantity` -- You can increase or decrease this depending on how many snowflakes you want to fall in a screen.
`SnowImage` -- You can add as many images you want to fall.