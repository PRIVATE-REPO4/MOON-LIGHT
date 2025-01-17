

[![Deploy On Heroku](https://www.herokucdn.com/deploy/button.svg)](https://www.heroku.com/deploy?template=https://github.com/PRIVATE-REPO4/MOON-LIGHT)


**1. At First Copy & Paste Below Command.**

```apt update -y && apt install sudo -y && sudo apt install curl ffmpeg git nano python3-pip screen -y && cd && rm -rf AdityaPlayer && git clone https://github.com/AdityaHalder/AdityaPlayer && cd AdityaPlayer && pip3 install -r requirements.txt --force-reinstall && screen -R AdityaPlayer```


**2. Now Run This Command & Add Your Variables.**

```nano Config.env```


**Required Variables !**

`API_ID`

`API_HASH`

`BOT_TOKEN`

`STRING_SESSION`

`MONGO_DB_URL`

`OWNER_ID`

`LOG_GROUP_ID`

`START_IMAGE_URL`


**3. After That Save and Exit By Below Buttons.**

```ctrl + s```

```ctrl + x```


**4. Now Run Your Bot in Background.**

```python3 -m MOON-LIGHT```


**5. Now Exit From Screen & Close Your Vps & Enjoy**

```ctrl + a + d```
