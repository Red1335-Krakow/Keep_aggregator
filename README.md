# Keep_aggregator

This project was created for KEEP community. It forwards messages from multiple telegram channels to Keep Aggregator Summary channel chat or channel, so you can be aware of last news and updates in KEEP World!

Aggregator consists of 2 parts:
1. Forwards ALL messages from Keep Network and KEEP_Network_ann_RU groups (Keep_telegramparser_bygroup.py)
2. Forwards messages of specific users (admins) from Keep Network Ru and tBTC groups (Keep_telegramparser_byuser.py)

More telegram KEEP groups will be created worldwide - more content will be forwarded. 


# Prerequisites

Fill out configuration file with API id and API hash. (more info here https://core.telegram.org/api/obtaining_api_id)

# Run

python3 Keep_telegramparser_bygroup.py config_keep.yml-sample and Keep_telegramparser_byuser.py config_keep.yml-sample 
Please note that in the first time initializing the script, you will be requried to validate your phone number using telegram API.
