## README

### Overview

This document provides instructions on how to use the virtual tour of the HKUST Guangzhou campus available at [http://yuzheng-chen.top/page.html](http://yuzheng-chen.top/page.html). The tour allows you to explore the campus, view various buildings, and check the status of different facilities and devices.

### Usage

You can embed the virtual tour in your own webpage using an iframe. The iframe URL can be customized to include a session ID by appending `?id=xxx` to the URL.

### Example

To see the virtual tour in action, visit the following URL:
[http://yuzheng-chen.top/page.html](http://yuzheng-chen.top/page.html)

### Embedding the Tour

To embed the virtual tour in your own webpage using an iframe, use the following HTML code:

```html
<iframe
  src="http://yuzheng-chen.top?id=12345"
  width="100%"
  height="600px"
  frameborder="0"
></iframe>
```

### Customizing the Session ID

You can customize the session ID by changing the value of the `id` parameter in the iframe URL. This allows you to assign different session IDs to different instances of the tour.

#### Example with Session ID

To assign a session ID of `12345` to the instance, use the following URL:

```html
<iframe
  src="http://yuzheng-chen.top?id=12345"
  width="100%"
  height="600px"
  frameborder="0"
></iframe>
```

### Detailed Instructions

1. **Visit the Example Page:**

   - Open [http://yuzheng-chen.top/page.html](http://yuzheng-chen.top/page.html) in your web browser to see the virtual tour example.

2. **Embed the Tour:**

   - Copy and paste the iframe code into your HTML file where you want the tour to appear.
   - Example:
     ```html
     <iframe
       src="http://yuzheng-chen.top?id=12345"
       width="100%"
       height="600px"
       frameborder="0"
     ></iframe>
     ```

3. **Customize the Session ID:**
   - Modify the `id` parameter in the iframe URL to set a custom session ID.
   - Example:
     ```html
     <iframe
       src="http://yuzheng-chen.top?id=67890"
       width="100%"
       height="600px"
       frameborder="0"
     ></iframe>
     ```

### Summary

The virtual tour of the HKUST Guangzhou campus can be easily embedded and customized using iframes. By appending the `id` parameter to the URL, you can assign unique session IDs to different instances of the tour.

For more information and to see the example in action, visit [http://yuzheng-chen.top/page.html](http://yuzheng-chen.top/page.html).

Feel free to contact us if you have any questions or need further assistance.
