
# spotify-nowplay-profile

This is a tool that posts the currently playing song on Spotify on your webpage or profile.
Please paste the URL generated by running Go and Vue using Vercel or a self-hosted server into your profile using an iframe etc...

## How to use

Plz place the .env file in the directory where `backend` is located.
What you need .env is Spotify's ClientID and ClientSecret not necessary confirm REFRESH.
(Confirm it using env.example)
Please set the redirect URL to `http://localhost4400`. There is no problem in filling in the rest in text.

## others

I'm currently learning Go and Vue, so I think there are a lot of flaws. I'd be very thanksful if the developers could give me any corrections or advice.😊

![artworks](https://github.com/CAT5NEKO/spotify-nowplay-profile/assets/111590457/ff24d97e-e50b-46da-abf9-32bf7f48442d)


## Change log
2024/05/05
カードの見た目をスリムにしました。
異常終了しないようにしました。

やりたいこと
- やっぱりSpotifyに埋め込めるようにしたい
- CloudFlareTunnnel経由で公開できるようにしたい（vue.config.jsを弄ればどうにかなるのかな？）
