## Facebook-Live-Chat

Facebook Live Chat is a short code allow put your facebook live chat box on your website, visitors can chat with you via Facebook Messenger. This is easy way to support and keep contact with your customers.

## Getting Started

Add these files to your project:

-JS

* fb-live-chat.min.js
* fb-live-chat-init.js

-CSS

* pulse-button.css

## Customize

In the file fb-live-chat-init.js, You can change the field to the desired language. 
Be sure to change the address of the page on facebook (the field "facebook_page").

```
fbLiveChat.init({
    sdk_locale: 'en_EN',
    facebook_page: 'Nikita-Kulish-1949081661986810', 
    position: 'right',
    header_text: 'Fast contact',
    header_background_color: '#4267b2',
    show_close_btn: false,
    animation_speed: 400,
    auto_show_delay: 0
});
```

## Result

Enjoy live communication with your customers


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
