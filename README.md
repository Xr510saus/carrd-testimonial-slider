# Carrd Testimonial Slider
A template for creating a testimonial slider embed on Carrd websites. Embeds are only available for those who have at least a Pro Standard subscription plan.

## Adding the Slider to Your Website
Please reference the following video for a guide on how to add the slider to your website. Text instructions are after the video.

<p align="center" width="100%">
<video src="https://github.com/user-attachments/assets/df60e0ea-e1f8-4d49-8513-ca310617a58d" width="80%" controls></video>
</p>

1. Go to your [Dashboard](https://carrd.co/dashboard) and Edit the page you want to edit.
2. Click the "+" button, then click the "Embed" option to add an embed to your website.
3. Move the embed to wherever you want it.
4. Click on the embed to open up its Properties window.
5. You may give it a title if you wish.
6. Copy the code in the HTML file into the "Code" text box.
7. Click "Done" to finalize your changes.
8. Publish your website to have the embed appear publicly.

## Template Preview
The following video shows the template as is. Text is selectable, the left and right arrow buttons can be used to navigate between testimonials, and the dots at the bottom show which testimonial is currently active (the template will always start at the first testimonial, or the leftmost dot). When you only have one testimonial, the buttons and dots disappear.

<p align="center" width="100%">
<video src="https://github.com/user-attachments/assets/56209fb8-5d92-46b8-a849-0cbdddc861df" width="80%" controls></video>
</p>

## Editing the Code
The following sections describe how to customize the template to better match your website. It is highly recommended to use a separate text editor / IDE when changing the code, to have a backup and because Carrd gets rid of tabs after pasting the code.

### Changing the Testimonials
Near the top of the code is the HTML section, which contains the testimonial information. Below is the "template code" for one testimonial:
```HTML
    <div class="testimonial">
      <p class="quote">"quote"</p>
      <div class="author">
        <span>name, production company</span>
      </div>
    </div>
```
To add a new testimonial, simply copy the above code block and add it below the other testimonials, if there are any. Make sure the added code block falls within the testimonial-container section, as outlined below
```HTML
  <div class="testimonial-container">
  ...
  ADD TESTIMONIAL CODE BLOCK HERE
  ...
  </div>
```
To modify the contents of a testimonial, simply put your testimonial information as outlined below
```HTML
      <p class="quote">PUT YOUR TESTIMONIAL QUOTE HERE, ADD QUOTATION MARKS IF YOU WANT</p>
      <div class="author">
        <span>PUT THE TESTIMONIAL GIVER'S INFORMATION HERE</span>
      </div>
```
To remove a testimonial, simply delete the corresponding code block.

### Changing the Appearance of the Slider
The middle section is the CSS section, where you can edit the appearance of each element. Everything within
```HTML
<style>
...
</style>
```
can be modified to change the appearance of the slider.

### Adding Custom Code
If you're interested in this section, I don't really need to explain anything to you. All the Javascript is at the bottom. Have fun.
