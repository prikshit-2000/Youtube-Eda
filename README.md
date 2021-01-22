# Youtube-Eda

<i>YouTube (the world -famous video sharing website) maintains a list of the top trending videos on the platform . According to Variety magazine , to determine the year's top trending videos , YouTube uses a combination of factors including measuring users interactions (number of views , shares , comments and likes) .Note : that they're not the most - viewed videos overall for the calendar year<i>

## Problem Statement

<i>Read the youtube data and perform exploratory data analysis<i>

## Dataset Information

This dataset is the daily record from the top trending YouTube videos . Top 200 trending videos of a given day. Original Data was collected during 14th 
November 2017 & 5th March 2018(though, data for January 10th & 11th of 2017 is missing). Original dataset was collected by Youtube API.

## Variable Description

<table>
    <tr><th>Column</th><th>Description</th></tr>
    <tr><td>Video_Id</td><td>Unique Indentity which tells the video_id of each subscribed video </td></tr>
    <tr><td>Category_Id</td><td>Unique number assigned to each category of the video</td></tr>
    <tr><td>Channel_Title</td><td>Title of youtube channel of the video</td></tr>
    <tr><td>Subscriber</td><td>Count of all subscribers for the respective video</td></tr>
    <tr><td>Title</td><td>Title of the video</td></tr>
    <tr><td>Tags</td><td>Tags are descriptive keywords you can add to your video to help viewers find your content</td></tr>
    <tr><td>Description</td><td>Description of the respective video</td></tr>
    <tr><td>Trend_day_count</td><td>Trending day count for respective video</td></tr>
    <tr><td>Tag_count</td><td>Tag count for the respective video </td></tr>
    <tr><td>Trend_tag_count</td><td>Tag count for respective trending video</td></tr>
    <tr><td>Comment_count</td><td>Count of Comments for particular video</td></tr>
    <tr><td>Comment_disabled</td><td>It represents the boolean value . True represents comments are enabled and False represents comments are disabled</td></tr>
    <tr><td>Like dislike disabled</td><td>It represents the boolean value . True represents like and dislike are enabled and False represents comments are disabled</td></tr>
    <tr><td>Likes</td><td>Number of Likes for particular video</td></tr>
    <tr><td>Dislikes</td><td>Number of Disikes for particular video</td></tr>
    <tr><td>Tag appeared in Title</td><td>It represents the boolean value . True represents that the respective tag has appeared in a particular video. False represents that the respective tag has not appeared in particular video</td></tr>
    <tr><td>views</td><td>Target variable . Number of veiws for  particular video</td></tr>
</table>
