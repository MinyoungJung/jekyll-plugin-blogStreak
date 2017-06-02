# Jekyll Plugin - Blog Streak

Jekyll Tagging Plugin which shows How many days you've written a blog in a row.


## Usage
1. Make a `_plugins` directory in your jekyll site, and put `blog_streak.rb` there.
2. In any of your pages, using `{% tag_name %}`  
Example : `{% total_blogging_date %}`
3. Each Tags refer to:  
**total_blogging_date** : Total blogging date from your first post date, Counts from 1 to today  
(For example, 5/28(First posting date) ~ 5/31(Today) returns 4)  
**current_date_streak** : Posting date streak including today's post(if it has, or including yesterday's post)  
**longest_date_streak** : Longest date streak in whole blogging day

## Got Questions?

Open an issue! Go to https://github.com/MinyoungJung/jekyll-plugin-blogStreak/issues

## Contribution
Any contribution will be very pleased.

