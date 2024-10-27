# Virtual Joystick

## How to Set-Up

### in designer setup

{% hint style="info" %}
you can either follow the video bellow or the instructions
{% endhint %}

**1 -** open your [Widget Blueprint](../creating-hud-widget-blueprint.md)

**2 -** Go to designer mode

**3 -** In palette window under user created section locate `WBP_MCK_JoystickComponent` or type directly in the search bar&#x20;

&#x20;**4-** After locating it drag it into the hierarchy under[ ](../tutorial/)[CanvasPanel](../info.md) ... ⓘ[^1]

&#x20;**5-** in the hierarchy select the `WBP_MCK_JoystickComponent` then in the Details window :

* check the `is variable` box
* &#x20;name the component to any thing that make sense for you (name it Joystick1 for this docs example)

**6 -** anchor it to any place you want , by pressing control and left click on one of the anchors pin and drag (better set all offsets to 0)

<figure><img src="../.gitbook/assets/image_2024-10-15_215609509.png" alt=""><figcaption></figcaption></figure>

**7 -** in the details window go to appearance dropdown then to Color And Opacity and set the Alpha to 0 To make the component invisible&#x20;

**8 -** in details window setup the properties that appear :

* **required :** these are important to set
  * joystick background :&#x20;
  * joystick thumb :&#x20;
  * joystick sprint thumb :&#x20;
* **For Customization Component :** if you are using HUD customization component it's important to set these values
  * Min Opacity : player can't go bellow this opacity when editing HUD(set something between 0-1)
  * Min [Sprint length](#user-content-fn-2)[^2] : the minimum sprint length that player can set when editing
  * Max [Sprint length](#user-content-fn-3)[^3] : the maximum sprint length that player can set when editing
  * Min Joystick [size ](#user-content-fn-4)[^4]: the minimum joystick size that player can set when editing
  * Max Joystick [size ](#user-content-fn-5)[^5]: the maximum joystick size that player can set when editing



{% embed url="https://youtu.be/G5VI1B_coDg" %}

### in graph setup

after setting the joystick component in the designer view switch to Graph editor and follow the instructions bellow





<iframe src="https://blueprintue.com/render/0c7wrbl8/" scrolling="no" width="100%" height="400px" border="0"></iframe>

{% embed url="https://blueprintue.com/render/muzau6x1/" %}

1. select

[^1]: it is important to have Canvas Panel . click  on the link for more info

[^2]: is the length the player need to swipe his thumb to start sprinting "from center of joystick to top middle is 1 unit "

[^3]: is the length the player need to swipe his thumb to start sprinting "from center of joystick to top middle is 1 unit "

[^4]: NOTE : this size is same size that you can edit when setting button inside canvas panel that is anchored to one point

[^5]: NOTE : this size is same size that you can edit when setting button inside canvas panel that is anchored to one point
