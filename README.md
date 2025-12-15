# Collection of Fake CAPTCHAs for Scambaiters
A collection of fake CAPTCHAs for scambaiters to use on their fake Bitcoin websites.
ChatGPT created most of the code for these (I just made a few changes).

## Classic but Endless
**File:** `Endless.html`

<img width="1268" height="814" alt="screenshot" src="https://github.com/user-attachments/assets/c62cb64d-8414-4126-afee-1da8dea38634" />\
This looks and behaves just like an average image-based CAPTCHA, but it never ends. The _Next_ button doesn't turn into a _Verify_ button.\
It connects to an external website, so you don't need to provide the images. If you want to provide images, feel free to modify the program.

_Formerly [AnonymousUser98/EndlessCaptcha](https://github.com/AnonymousUser98/EndlessCaptcha)_

## The Confidence Bar
**File:** `ConfidenceBar.html`

<img width="745" height="743" alt="screenshot" src="https://github.com/user-attachments/assets/483e5f89-3eeb-4419-aed0-48e094b03a40" />\
This fake CAPTCHA asks you to type a word (or some random text), click all the squares that feel "intentionally placed", or just wait for a few seconds. Each time you do an action, the confidence level goes up. Once it reaches 95%, it starts randomly jumping between 80% and 95%. It never reaches 100%.

## It's Almost Done
**File:** `NeverFinish.html`

<img width="674" height="391" alt="screenshot" src="https://github.com/user-attachments/assets/43f6dac5-1c92-43ac-8a24-2408e1a18d34" />\
This one is pretty simple: you click a button, it does some "verification checks", it tells you it's almost done, and the cycle repeats.

## Super-Slow Slider
**File:** `SlowSlider.html`

<img width="656" height="366" alt="screenshot" src="https://github.com/user-attachments/assets/ffa3dcd7-daeb-41ad-9eb3-c9557db97a7d" />\
This one is just like a slider CAPTCHA (where you need to slide the slider from left to right). The only difference is that you need to move the slider **very slowly**. If you're too fast, you need to start over.

## Whack-a-Mole
**File:** `Whack-a-Mole.html`

<img width="791" height="455" alt="screenshot" src="https://github.com/user-attachments/assets/0ad338e3-4c84-4977-9975-f452b3e929d6" />\
It asks you to click a button, you move your cursor near the button, and the button moves to a random position. Unless you have a touchscreen, it's impossible to actually click the button (and when you do, it doesn't do anything).

## Are we there yet?
**File:** `AreWeThereYet.html`

<img width="810" height="519" alt="screenshot" src="https://github.com/user-attachments/assets/354795ba-2902-4ada-bb59-6b0d9b4c63f0" />\
Don't worry, you just need to do 5 simple tasks. Oh wait, make that 6 simple tasks. Or is it 8 simple tasks?
This fake CAPTCHA looks like a simple 5-step process, but it keeps adding more steps.

## Maybe Pictures
**File:** `InstructionDrift.html`

<img width="760" height="928" alt="screenshot" src="https://github.com/user-attachments/assets/102dd9b4-de63-4925-9bdc-6cc6ef5ea9ac" />\
Just like an endless image CAPTCHA, but with some interesting questions. Please select all the images that are remotely related to something that might contain a dog.

## Impossible Typing Test
**File:** `TypingTest.html`

<img width="872" height="762" alt="screenshot" src="https://github.com/user-attachments/assets/0263f151-2746-48a8-8125-b4993258e57f" />\
Type the words that appear before they reach the bottom of the screen. It starts out simple, but you'll eventually find yourself trying to type "pneumonoultramicroscopicsilicovolcanoconiosis" in less than 10 seconds.

# Other Information
The name _CoFaCaFo-SB_ stands for **Co**llection of **Fa**ke **CA**PTCHAs **fo**r **S**cam**b**aiters. The letter _O_ is pronounced like the one in "code", and the _A_ is pronounced like the one in "hat". The _SB_ letters at the end are pronounced individually (you say each letter).

If you have any improvements, please feel free to contribute to this repository.

This project is available under the MIT license, so anyone can use it. Scambaiters, feel free to use these in your fake websites. You can modify them however you want.\
Any copyright or trademark text that appears in within the webpages is purely visual and has nothing to do with the rights of this project. It's only there to make it more convincing to scammers.
