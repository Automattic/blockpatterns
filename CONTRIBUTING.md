# Content guidelines
1. Make it feel real. Do not use dummy text. Make sure images and text are working well together and make a coherent piece of content. Any media needs to be CC0 licensed.
# Code guidelines
1. If using custom colors, make sure to use actual HEX values, not the theme-defined names (do not click on the color swatches, input HEX values manually instead). Double-check the code – if you input the HEX code of a color defined in the theme, the custom name will be used instead.
2. If using background color, be sure to explicitly define the text color too. This is to ensure that the text remains readable on sites using both light and dark color schemes.
3. For custom font sizes, do not rely on the theme-defined presets, but set the font size explicitly instead. The same thing goes for line height.
4. If the pattern uses images, make sure those images are added to the media library on the pattern source site.
    * **Images should be no bigger than 350Kb with max dimensions 2000px (width or height, whichever is bigger).**
    * Optimize the image with ImageOptim. Enable lossy minification if need be; 80% quality for JPEGs should work fine.
5. Try to make the code as simple as possible by avoiding excessive block nesting.
6. Pay attention to empty paragraphs that sometimes get added to the end. You might need to switch to code editor to get rid of them.
7. Sometimes patterns will generate an error “Attempt block recovery” message on editor reload. This is typically an editor bug. Ask in #dotcom-view in Slack for help with troubleshooting.
# Testing & feedback
1. Test your code on both simple and atomic sites.
2. Test with Twenty Twenty One and Varia child theme(s) using both light and dark color scheme.
3. Create a new issue in the Block Patterns GH repo. The issue should include:
    * A screenshot of the pattern.
    * Code snippet copied directly from the editor. Triple check there aren’t any empty paragraphs in the code (common issue).
    * A few words on your reasoning (nice to have).
4. Gather team feedback. Ping people if necessary. At least one other person should try out the code.
# Launching
1. Add the pattern to the source site as a new post. Make sure to save it as a draft until ready to publish!
2. The post title is the name of the pattern displayed in both pattern and layout selector under the screenshot. Choose wisely!
3. Select the appropriate categories from the list.
    * Use “Pattern” and/or “Layout” as the tag as appropriate.
    * Add is_web and/or is_mobile as the Pattern Meta. (patterns with is_mobile meta tag show up in the mobile app)
4. Add added to dotcompatterns label to the corresponding GH issue. If the feedback is positive and there are no issues with the code…
5. **Hit publish!** The patterns and layouts will be automatically deployed, no need to ping view-engineering.
6. Close the GH issue.
# Editing a Pattern
Do not delete images from the media library of the source site when replacing images in published patterns. Doing so could potentially remove any unreplaced hotlinked image from published posts on customer sites.

# Removing a Pattern
Patterns can be removed from the source site at any time by switching them to draft or “trashing” the pattern post.

When a pattern is in draft mode or trashed on the source site, it is removed from the Editor of all users in all languages. This will not remove it from users Site Content. It will merely no longer be available from the list in the inserter.
