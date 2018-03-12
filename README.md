# LiveChat Rating Reminder

Simple widget that reminds visitor to rate the chat.

## Getting Started

Rating Reminder is external widget that you need to add to your website HTML source code. LiveChat tracking code has to be initialised before the widget. If you have any additional questions feel free to create [an issue](https://github.com/livechat/rating-reminder/issues) here.

### Prerequisites

Rating Reminder requires jQuery to work, you can add hosted library like below:

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
```

### Installing

Installation of this widget is pretty simple. All you have to do is to 
1. Add content of `rating-reminder.html` file to your HTML source code AFTER LiveChat tracking code snippet.
2. Add content of `rating-reminder.css` file to your CSS stylesheet. 

Here you can see little demo of Rating Reminder: https://livechat.github.io/rating-reminder/

### Supported themes

Currently Rating Reminder support 4 themes:
1. Classic - `.classic`
2. Modern - `.modern`
3. Circle - `.circle`
4. Smooth - `.smooth`

Remember to add theme-class to `#lc-rating-reminder` element, like below:

```
<div id="lc-rating-reminder" class="smooth">
    <img src="https://cdn.livechatinc.com/s3/3358262/all/thumbup.gif" alt="Rate us!">
    <span>Rate this chat to help us become better support.</span>
    <span id="lc-rating-reminder-close">+</span>
</div>
```

## Changelog

#### v 1.0.0
- First widget version

## License

This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details
