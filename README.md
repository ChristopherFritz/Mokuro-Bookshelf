# Mokuro Bookshelf

Web page for tracking progress in reading manga via Mokuro.

All Mokuro HTML files that have been opened in the browser appear on the page.

Items on page 1 show under "Future".  Items on the final page show under "Finished".  All other items show under "Reading".

Remaining page count and percentage progress increment in real-time while advancing pages in a Mokuro HTML file.

## Sample Bookshelf
![](Sample%20Bookshelf%203.png)

## Dependencies

Relies on Mokuro HTML files generated using my [Mokuro fork](https://github.com/ChristopherFritz/mokuro), which adds extra information (page count and path to cover image) to the local storage.

## Browser Support

This has been developed and texted on Chromium on Linux.

Firefox does not appear to allow local storage to be visible across different file: documents, which prevents the bookshelf from being able to see Mokuro information.
