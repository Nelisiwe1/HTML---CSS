

# HTML Working with Graphics and Images.

The img element: The img element is used to insert images in an HTML document.

### Main attributes that need to be included for every image:
•	The src attribute: Specifies the URL or path to the image file.
•	The alt attribute: Provides alternative text for the image, which is displayed if the image fails to load or for accessibility purposes (screen readers).
•	The width and height attributes determine the size of the image.
Four main file formats.

### JPEG (Joint Photographic Experts Group):
•	File Extension: .jpg, .jpeg
•	For Photographs and images with lots of color gradients.
•	Find balance between high-quality images, supports millions of colors, and uses lossy compression to achieve smaller file sizes.
•	Does not support transparency, not suitable for images with sharp edges or text

### PNG (Portable Network Graphics):
•	File Extension: .png
•	newer format that works well when you need transparency in a photograph.
•	Supports lossless compression, preserves image quality, and allows transparent backgrounds.
•	Larger file sizes compared to JPEG for photographs.

### GIF (Graphics Interchange Format):
•	File Extension: .gif
•	Simple animations, icons, and graphics with limited colors.
•	It Supports animations and transparency (limited to one-bit transparency).
•	 Limited color support (256 colors), not suitable for high-quality photographs.

### SVG (Scalable Vector Graphics):
•	File Extension: .svg
•	 Icons, logos, and illustrations that require scalability without losing quality.
•	 It is a vector format, scalable without loss of quality, and supports interactivity.
•	Not suitable for complex photographs or images with many colors/gradients.


Responsive images are images that adapt and scale appropriately to different screen sizes and resolutions, providing an optimal viewing experience across various devices, including desktops, laptops, tablets, and smartphones. The goal is to ensure that images look good and load quickly on any device, regardless of its screen size or pixel density.

## Techniques and HTML attributes used to implement responsive images:

srcset attribute: The srcset attribute allows you to provide multiple image sources and their corresponding sizes.
<picture> element: The <picture> element allows you to specify multiple sources for an image, along with media queries, to load different images based on various conditions.
Responsive width
Responsive width refers to the ability of an element (such as an image or a container) to automatically adjust its width based on the screen size or the width of its parent container. This ensures that the element's size scales appropriately to fit various screen resolutions and device sizes.
Figcaption and figure.
<figure> and <figcaption> elements: These elements are used together to create a caption for an image.

### Working with media in HTML.
Audio element contain the opening and closing tag.
The reason both an opening and closing tag for the audio element. Well, that is because the source element can be used to specify multiple audio files, similar to how the picture element was used.

### Working with video in html.
The video element has an opening and closing tag. To display a video, use the source attribute to specify the video file. And if the controls attribute is added, the browser will automatically create a video player.
•	Video codecs used for web content, like H.264, have raised concerns due to their proprietary nature and licensing fees, leading to efforts to develop open and non-patented codecs like AV1. HTML's video element allows flexibility by supporting multiple codec formats such as H.264, WebM, and AV1, enabling browsers to play the first compatible file they recognize.
•	To cater to users with different screen sizes and network connections, adaptive bitrate streaming employed by major platforms like Netflix and YouTube dynamically adjusts video resolution, ensuring optimal viewing experiences, but for simplicity, many websites utilize embed codes from video hosting services instead of directly using the video element.

### Working With Captions and Subtitles
It's essential to make web content accessible to all users, including those with hearing impairments or other difficulties in understanding audio and video. Captions offer a solution to this challenge by providing text-based representations of audio content.
To add captions to a video, you can use the HTML <track> element and link it to a text file in the Web Video Text Tracks (VTT) format. This text file contains time-coded lines of text that correspond to when they should be displayed in the video.

For example, within the <video> element, you can insert a <track> element with attributes like src for the file path, kind set to "captions" or "subtitles," label to display the caption option, and default to make it the default choice when captions are enabled.
By using this approach, users can toggle captions on and off, select different language options, or even access audio descriptions for visually impaired users. Including captions in your videos not only enhances accessibility but also expands your audience reach, making your content more inclusive and compliant with accessibility standards. Major video platforms like YouTube and Vimeo also support caption uploads, enabling a broader audience to engage with your content.


Embedding videos from video hosting services, like YouTube or Vimeo, involves using the <iframe> element to display their video player on your webpage seamlessly. You can adjust the size of the embedded content using attributes like height and width, and the src attribute specifies the video source.
Example of embedding a YouTube video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Example of embedding a Vimeo video:
<iframe src="https://player.vimeo.com/video/VIDEO_ID" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
To consider security when using iframes, especially when allowing multiple contributors to embed content on your website. Always follow your content management system's guidelines to ensure safe embedding practices.

### HTML Language Support

In HTML, it is essential to indicate the language of your content using the lang attribute. This helps search engines, spell checkers, and screen readers understand and process the content correctly. Specify the language at the top-level HTML element or on specific elements for different parts of the content. Additionally, use the dir attribute to indicate content direction (left-to-right or right-to-left) if needed. It is very crucial to set the character set (charset) to ensure proper character encoding, typically using UTF-8 for comprehensive language support. By using these attributes, you contribute to a more inclusive and multilingual web.

the <div> and <span> elements are two commonly used generic container elements that help structure and style content on a web page.

<div> Element: The <div> element is a block-level container that is used to group and organize content into logical sections. It does not have any specific meaning or styling by itself.

Eg. <div> 
<h1>Heading</h1>
 <p>Paragraph 1</p>
 <p>Paragraph 2</p> 
</div>

<span> Element: The <span> element is an inline-level container used to apply styles or target specific parts of content within a larger block of text. It does not add any structural meaning to the content and is often used to apply CSS styles to individual words or characters.
Eg. <p>This is a <span style="color: blue;">blue</span> text.</p>










