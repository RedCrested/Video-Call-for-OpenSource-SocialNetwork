# Video Call on message chat for OpenSource-SocialNetwork

This component adds a button to send a video call invitation on the Message system. The meeting is provided by Jitsi Meet, a fully encrypted, 100% open-source video conferencing solution that you can use all day, every day, for free — with no account needed. There is no requirement to install another app and/or plugin. 

Jitsi is a trademark of © 8x8, Inc. and if you won't create your own Jitsi Server, you can use the 8x8 Jitsi as a Service. To see details about the service, plans and prices, go to [https://jaas.8x8.vc/](https://jaas.8x8.vc/). If you use the default configurations of the component, the meetings are limited to 5 minutes by jitsi.org.  However, there are many free Jitsi mirrors around the world. If you're looking for free mirrors of the Jitsi server, [take a look here](https://jitsi.github.io/handbook/docs/community/community-instances/). Use this option at your own risk.

The Jitsi Meet toolbar is customizable by editing the file toolbar_items.php. Some options require additional configurations on the server or the purchasing of extra features if you're using 8x8 JaaS service.

![Video Call invitation](https://www.redcrested.net/components/JitsiMeetButton/JitsiMeetButton-1.jpg)

![Video call between users](https://www.redcrested.net/components/JitsiMeetButton/JitsiMeetButton-2.jpg)

![Video Call Configurations](https://www.redcrested.net/components/JitsiMeetButton/JitsiMeetButton-3.jpg)

**Attention**

 I found a post on the [Jitsi blog](https://jitsi.org/blog/authentication-on-meet-jit-si/) that explains that after August 24th, Jitsi closed anonymous meet registration on the https://meet.jit.si server. It means that at least one of the participants must have a Jitsi Account (or connect the third-party accounts in the Jitsi). The solution to avoid this is:
1) Create your jitsi server
2) Use 8x8.vc JaaS server
3) Use some of the [Jitsi Free server](https://jitsi.github.io/handbook/docs/community/community-instances/). 

## How to buy
I am selling this component for US$39.00 through the Buy me a coffee website. To purchase, visit [https://www.buymeacoffee.com/redcrested/e/147939](https://www.buymeacoffee.com/redcrested/e/147939) or click on button

[![](https://redcrested.net/res/img/button.png)](https://www.buymeacoffee.com/redcrested/e/147939)

## Limitations

The component was tested in the free version of OSSN 6.6 and 7.0, in the GoBlue theme. Maybe some adjustments are required in older versions and/or other themes. 

## Supported Browsers

[Source](https://jitsi.github.io/handbook/docs/user-guide/supported-browsers)

## Desktop browsers

| Browser | Support | Versions | Notes |
|---|:---:|:---:|---|
| <i class="fa-brands fa-chrome"></i> Chrome [^1] | ✅ | >= 72 | Best results with >= 96 |
| <i class="fa-brands fa-firefox-browser"></i> Firefox | ✅ | >= 68 | Best results with >= 101 |
| <i class="fa-brands fa-safari"></i> Safari | ✅ | >= 14 | Best results with >= 15, output device selection unsupported |
| <i class="fa-brands fa-edge"></i> Edge | ✅ | >= 79 | Edge Legacy is unsupported |
| <i class="fa-brands fa-internet-explorer"></i> Internet Explorer | ❌ | | |

## Mobile browsers

### Android

| Browser | Support | Versions | Notes |
|---|:---:|:---:|---|
| <i class="fa-brands fa-chrome"></i> Chrome [^1] | ✅ | | Same support as the desktop version |
| <i class="fa-brands fa-firefox-browser"></i> Firefox | ✅ | | Same support as the desktop version |

:::note
For a better mobile experience (background support, Bluetooth support, etc.) we recommend using a
native app instead. We provide a [native Android SDK](/handbook/docs/dev-guide/dev-guide-android-sdk).
:::

### iOS

| Browser | Support | Versions | Notes |
|---|:---:|:---:|---|
| <i class="fa-brands fa-chrome"></i> Chrome | ✅ | | Same support as Safari as they share the engine |
| <i class="fa-brands fa-firefox-browser"></i> Firefox | ✅ | | Same support as Safari as they share the engine |
| <i class="fa-brands fa-safari"></i> Safari | ✅ | >= 14.3 | Best results with 15.4 |
| <i class="fa-brands fa-edge"></i> Edge | ✅ | | Same support as Safari as they share the engine |

:::note
On iOS all browsers share the same engine, Safari. As such all features and limitations on all iOS
browsers are those of Safari.

For a better mobile experience (background support, CallKit integration, etc.) we recommend using a
native app instead. We provide a [native iOS SDK](/handbook/docs/dev-guide/dev-guide-ios-sdk).
:::

[^1]: This also applies to all Chromium-based browsers such as Brave, (current) Edge, Opera, Vivaldi and others.

## Version

- 2.2
    - The user who invited the call has the moderator privilegies
    - Added support to allow to Admin use the Jitsi's autheticated session 
    - Added support to Giphy icons if the OssnGiphy is configured. Giphy icons are available in the raise hand menu.
    - Added option to close or keep the window when meet is ended. 
    - Added page to inform user that the meeting has ended, when window isn't closed automatically.
- 2.1
    - Improved admin form
    - Fixed a conflict found with OssnSmilies component
- 2.0
    - Added panel in Administrator section to add some configurations, such as Jitsi Server, secret room code and Jitsi as a Service (JaaS) key
    - Full language support
- 1.0
    - Initial version, developed under the demands of a customer.

    
## Contributing

Send an email to [contact@redcrested.net](contact@redcrested.net).

## License

Go to [Red Crested License](http://www.redcrested.net/license) to read the last version of our terms.
