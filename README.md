import praw

reddit = praw.Reddit(client_id='2GqglMhxQwBi4hYel6UyRw',
                     client_secret='wUIa5hGW6-AsNnMoA_tPI5HRb5vTqg',
                     user_agent='your_user_agent',
                     username='Long-Guarantee-2247',
                     password='Afaq0147')

subreddit = reddit.subreddit('https://www.reddit.com/r/Guarantee22/comments/1ezpm00/sophie_rain_spiderman_leaked_sophie_rain/')

for submission in subreddit.new(limit=20):
    submission.reply('sophie rain spiderman leak.')
