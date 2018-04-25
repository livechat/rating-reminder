# LiveChat Rating Reminder

Simple widget that reminds visitor to rate the chat.

## Getting Started

Rating Reminder is external widget – in order for it to work, you need to add it to your website’s HTML source code. LiveChat tracking code needs to be initialized before the widget. If you have any additional questions, feel free to create [an issue](https://github.com/livechat/rating-reminder/issues) here.

**Note:** Currently Rating Reminder is not supported on mobile devices.

### Prerequisites

To work properly, Rating Reminder requires jQuery libraries. You can use a hosted library like the one below:

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
```

### Installing

Installation of this widget is pretty simple. All you have to do is to:
1. Add content of `rating-reminder.html` file to your HTML source code, **after** LiveChat’s tracking code snippet.
2. Add content of `rating-reminder.css` file to your CSS stylesheet.

Here’s a preview that will show you how our Rating Reminder works: https://livechat.github.io/rating-reminder/

### Supported themes

Currently our Rating Reminder supports 4 themes. Here is a list along with class names (check note below):
1. Classic: `.classic`
2. Modern: `.modern`
3. Circle: `.circle`
4. Smooth: `.smooth`
5. New chat window: `.new`

**Note:** Remember to add theme class to `#lc-rating-reminder` element, like below:

```
<div id="lc-rating-reminder" class="smooth">
    <img src="https://cdn.livechatinc.com/s3/3358262/all/thumbup.gif" alt="Rate us!">
    <span>Rate this chat to help us become better support.</span>
    <span id="lc-rating-reminder-close">+</span>
</div>
```

## Changelog

#### v 1.1.0
- Added support for new LiveChat window

#### v 1.0.0
- First widget version

## License

This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details
