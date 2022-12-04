<h1 align="center">
PWG Password Generator
</h1>

<p align="center">
A simple program to auto-generate a strong password including lower- and uppercase letters, numbers and symbols. Compatible with any device that's able to run `.exe` files properly. Made using Node.JS
</p>

<div align="center">
<a href="https://github.com/Lunahax"><img src="https://img.shields.io/github/stars/lunahax/Password-Generator?color=00dd00&style=for-the-badge"></a>
<a href="https://github.com/Lunahax"><img src="https://img.shields.io/github/repo-size/lunahax/Password-Generator?color=00dd00&label=size&style=for-the-badge"></a>
<a href="https://github.com/Lunahax"><img src="https://img.shields.io/github/downloads/lunahax/Password-Generator/total?color=00dd00&style=for-the-badge"></a>
</div>

---

<h2 align="center">
<a href="#about">About</a>・<a href="https://github.com/Lunahax/Password-Generator/releases">Download</a>・<a href="#usage">Usage</a>・<a href="#support">Help and Support</a>
</h2>

---

## <a id="about"></a>About

PWG works using the following string generator function:
```js
function data(length) {
    var result = '';
    var characters = '1234567890QWERTYUIOPASDFGHJKLZXCVBNM!@#$%^&*()-_=+,<.>/?mnbvcxzlkjhgfdsapoiuytrewq';
    var charactersLength = characters.length;
    for ( var i = 0; i < length; i++ ) {
       result += characters.charAt(Math.floor(Math.random() * charactersLength));
    }
    return result;
}
```
This function will return a random string with the length of property `length`.
The code below would return a 16-letter random string
```js
console.log(data(16))
```

---

## <a id="usage"></a>Usage and Installation

### Installation

1. Under the [Releases](https://github.com/Lunahax/Password-Generator/releases) tab, check for the latest version.

2. Once you've found the latest version, click on it.

3. Read the release notes, there might be important information.

4. Now check for the attached files. You should find a `.exe` file.

5. Click on the `.exe` file and it should download right away.

6. Check for the file in your download folder and run it!

### Exercising

1. Once ran, you should see 2 options. "1) Generate single password" and "2) Generate multiple passwords". Select an option by typing its number (1 / 2) into the "Select option> " field.

![Bild_2022-11-30_163906310](https://user-images.githubusercontent.com/89605624/204841831-2a786fce-14fa-46ed-8dc3-dd45b96c61e3.png)

2. Hit enter and enter a password length (we recommend 16).

![Bild_2022-11-30_164001715](https://user-images.githubusercontent.com/89605624/204842088-017abf15-ae9b-40b5-896e-a16365cf6a8f.png)

3. If you chose "2) Generate multiple passwords" you may need to enter the amount of passwords you would like to generate as well. Confirm with enter.

4. You will now receive a random string. We recommend you to copy it and save your password using the following format in a seperate file.
```
Website: 
Account:
Password:
```
**Example:**
```
Website: https://www.thiswebsitedoesnotexist.zzz/
Account: this_user_does_not_exist
Password: k73WBe8*xCYQW8^Y
```

![Bild_2022-11-30_164459285](https://user-images.githubusercontent.com/89605624/204843338-b56b7ad1-7b04-49aa-ad5e-b5d876553a9d.png)

5. That's it!

---

## <a id="support"></a>Help and Support

<h3><a href="https://discord.gg/cQCkK35FT2">https://discord.gg/cQCkK35FT2</a></h3>
