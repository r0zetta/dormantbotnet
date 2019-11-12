# dormantbotnet
Twitter user objects from what looks like a botnet that went dormant in 2015

To recreate the associations file, run:
cat egg_associations.json.* > egg_associations.json

associations file contains follower/following mappings of the Twitter objects listed in eggdetails.json. The format is:
{screen_name1: [follower_screen_name1, follower_screen_name2, ..., follower_screen_namen],
 screen_name2: [follower_screen_name1, follower_screen_name2, ..., follower_screen_namen],
 ...,
 screen_namen: [follower_screen_name1, follower_screen_name2, ..., follower_screen_namen]}
