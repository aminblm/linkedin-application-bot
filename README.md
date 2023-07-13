# LinkedIn Application Bot 🤖

![linkedineasyapplygif](https://user-images.githubusercontent.com/34207598/128695728-6efcb457-0f75-42e2-987a-f7a0c239a235.gif)

A python bot to apply all Linkedin Easy Apply jobs based on your preferences.

- Two options are avalible to use this bot, either with entering password or without, fully secure no credentials are stored.
- Export all results and offers as txt file
- Fully customizable job preferences
- Can be used for many job search websites such as Linkedin, Glassdoor, AngelCo, Greenhouse, Monster, GLobalLogic and Djinni.

To modify, use, get documentation or for you enquiries kindly contact me via: <br>
**amin@boulouma.com**

## Donation and Support 🥳

With your support I build, update and work on this project. You can also purchase additional packages, tutorials and materials explaining how this bot is working. <br>

There are several features and simplifications I'd like to add to this project. For that I need your support to cover costs. Your support is keeping this project alive.

[**Donate & support!**](https://commerce.coinbase.com/checkout/576ee011-ba40-47d5-9672-ef7ad29b1e6c)

## Purchase additional materials and guides 😍

You can currently, purchase full in depth detailed tutorial explaining how this bot is working, one hour booking session where i step by step build and run the bot on your machine or 5 videos
showing how this can be used. To buy, support this project and help me add more features. <br>

- [**Purchase working videos for this bot**](https://commerce.coinbase.com/checkout/3958599d-3938-4fb3-86f4-b100c2d7e850)
- [**Purchase online call tech support to install the bot for Windows**](https://commerce.coinbase.com/checkout/638f5582-a750-4374-86ea-82d0445cbe90)
- [**Purchase online call tech support to install the bot for Linux**](https://commerce.coinbase.com/checkout/3ec705fe-2898-4ae8-9f90-73cd1270392f)
- [**Purchase online call tech support to install the bot for Mac OS**](https://commerce.coinbase.com/checkout/cf76021c-53be-42bc-8ae1-2dc75fcd9647)
- [**Purchase documentation of this bot for Windows**](https://commerce.coinbase.com/checkout/ac4212d1-ecb0-4734-8946-f4a9e5c09f45)
- [**Purchase documentation of this bot for Linux**](https://commerce.coinbase.com/checkout/69a1f1b8-3282-4ab6-9383-6ce28aab3274)
- [**Purchase documentation of this bot for Mac OS**](https://commerce.coinbase.com/checkout/c7069064-02ac-4c3b-b980-ae7623bc8139)

## Installation 🔌

- clone the repo `git clone https://github.com/aminblm/linkedin-application-bot`
- Make sure Python and pip is installed
- Install dependencies with `pip3 install -r requirements.yaml`
- Either create firefox Profile and put its path on line 8 of config.py or enter your linkedin credentials line 11 and 12 of config.py.
- Modify config.py according to your demands.
- Run `python3 linkedin.py`
- Check Applied Jobs DATA .txt file is generate under /data folder

## Features 💡

- Ability to filter jobs, by easy apply, by location (Worldwide, Europe, Poland, etc.), by keyword (python, react, node), by experience, position, job type and date posted.
- Apply based on your salary preferance (works best for job offers from States)
- Automatically apply single page jobs in which you need to send your up-to-date CV and contact.
- Automatically apply more than one page long offers with the requirements saved in LinkedIn like experience, legal rights, resume etc.
- Output the results in a data txt file where you can later work on.
- Print the links for the jobs that the bot couldn’t apply for because of extra requirements. (User can manually apply them to optimize the bot)
- Put time breaks in between functions to prevent threshold.
- Automatically apply for jobs.
- Automatically run in the background.
- Compatible with Firefox and Chrome.
- Runs based on your preferences.
- Optional follow or not follow company upon successful application.
- Much more!

## Tests 🔦

There is a specific test folder for you to test the dependencies, the bot and if everything is set up correctly. To do that I recommend,
running below codes,

1. Go to the tests folder run `python3 setupTests.py` this will output if Python,pip,selenium,dotenv and Firefox are installed correctly on your system.
2. Run `python3 seleniumTest.py` this will output if the Selenium and gecko driver is able to retrieve data from a website. If it returns an error make sure you have correctly installed selenium and gecko driver
3. Run `python3 linkedinTest.py` this will try to log in automatically to your Linkedin account based on the path you defined in the .env file. If its giving an error make sure the path exists and you created firefox profile, logged in manually to your Linkedin account once.
   Here is the result you should get after running test files,
   ![test1](https://user-images.githubusercontent.com/34207598/189535308-c2c546de-caec-4460-823d-dd5ca208c480.png)

## How to Set up (long old way) 🛠

This tutorial briefly explains how to set up LinkedIn Easy Apply jobs bot. With few modifications you can make your own bot or try my other bots for other platforms.

1. Install Firefox or Chrome. I was using Firefox for this so I will continue the usage of it on Firefox browser. Process would be similar on Chrome too.
2. Install Python.
3. Download [Geckodriver](https://github.com/mozilla/geckodriver/releases) put it in Python’s installation folder.
4. Install pip, python get-pip.py
5. Install selenium pip install selenium
6. Clone the code
7. Create a profile on Firefox, about:profiles
8. Launch new profile, go Linkedin.com and log in your account
9. Copy the root folder of your new profile, to do that type about:profiles on your Firefox search bar, copy the root folder C:\---\your-profile-name.
10. Paste the root folder on the `config.py` if the `firefoxProfileRootDir` file
11. Modify/adapt the code and run in `config.py` to preferences.
12. After each run check the jobs that the bot didn’t apply automatically, apply them manually by saving your preferences
13. Next time the bot will apply for more jobs based on your saved preferences on Linkedin.
14. Feel free to contact me for any update/request or question.

## Demo 🖥

![banner](https://github.com/aminblm/linkedin-application-bot/assets/25132838/b0dda2f0-b531-48af-b769-fc1370d88fdb)
![1](https://github.com/aminblm/linkedin-application-bot/assets/25132838/1caeeff1-7f70-423a-ae51-ae97ba00bc99)
![2](https://github.com/aminblm/linkedin-application-bot/assets/25132838/3cb59d82-b167-40ad-8fef-d8e1430bf6c1)

## Future Implementations

- Headless browser experience (run the bot without launching the browser)
- More robustness of the bot for different fields
- Blacklist offers in Linkedin
- Output not completed fields in Linkedin
- Add support to other major job seeking websites (Glassdoor, AngelCo, Greenhouse, Monster, GLobalLogic, djinni)
- AngelCo - https://angel.co/l/2xRADV
