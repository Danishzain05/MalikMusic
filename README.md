<h2 align="center">Delivering Superior Music Experience To Telegram</h2>

---

### 🌟 Features

- 🎵 **Multiple Sources:** Play Music From Various Platforms.
- 📃 **Queue System:** Line Up Your Favorite Songs.
- 🔀 **Advanced Controls:** Shuffle, Repeat, And More.
- 🎛 **Customizable Settings:** From Equalizer To Normalization.
- 📢 **Crystal Clear Audio:** High-Quality Playback.
- 🎚 **Volume Mastery:** Adjust To Your Preferred Loudness.

---


<h3 align="center">
      ─「 <\> Deploy On Heroku <\> 」─
</h3>

<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/Danishzain05/MalikMusic"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>


### 🔧 Quick Setup

1. **Upgrade & Update:**
   ```bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```

2. **Install Required Packages:**
   ```bash
   sudo apt-get install python3-pip ffmpeg -y
   ```
3. **Setting up PIP**
   ```bash
   sudo pip3 install -U pip
   ```
4. **Installing Node**
   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash && source ~/.bashrc && nvm install v18
   ```
5. **Clone the Repository**
   ```bash
   git clone https://github.com/Danishzain05/MalikMusic && cd MalikMusic
   ```
6. **Install Requirements**
   ```bash
   pip3 install -U -r requirements.txt
   ```
7. **Create .env  with sample.env**
   ```bash
   cp sample.env .env
   ```
   - Edit .env with your vars
8. **Editing Vars:**
   ```bash
   vi .env
   ```
   - Press `I` Button On Keyboard To Start Editing.
   - Edit .env With Your Values.
   - Press `Ctrl + C`  Once You Are Done With Editing Vars And Type `:wq` To Save .env Or `:qa` To Exit Editing.
10. **Installing tmux**
    ```bash
    sudo apt install tmux -y && tmux
    ```
11. **Run The Bot**
    ```bash
    bash start
    ```

---

### 🛠 Commands & Usage

The Inflex Music Bot Offers A Range Of Commands To Enhance Your Music Listening Experience On Telegram:

| Command                 | Description                                 |
|-------------------------|---------------------------------------------|
| `/play <song name>`     | Play The Requested Song.                    |
| `/pause`                | Pause The Currently Playing Song.           |
| `/resume`               | Resume The Paused Song.                     |
| `/skip`                 | Move To The Next Song In The Queue.         |
| `/stop`                 | Stop The Bot And Clear The Queue.           |
| `/queue`                | Display The List Of Songs In The Queue.     |

For A Full List Of Commands, Use `/help` in [Telegram](https://t.me/ZainMusic5_bot).

---
