Bronze Bucket name - yt-project-bronze
Silver Bucket name - yt-project-silver
gold bucket name - yt-project-gold

scripts bucket name - yt-project-scripts

SNS arn : arn:aws:sns:eu-north-1:296886268943:yt-data-pipeline-alerts-dev:119e81ee-06b6-4787-92ef-471f79e6a4cc

youtube api = AIzaSyCr8pZ-ttyRc04jJ_cmYFFyvpFMeBVP8zI


Glue bronze - yt-pipeline-bronze-dev
Glue silver - yt-pipeline-silver-dev
Glue gold - yt-pipeline-gold-dev



    --bronze_database            — yt-pipeline-bronze-dev
    --bronze_table               — raw
    --silver_bucket              — yt-project-silver
    --silver_database            — yt-pipeline-silver-dev
    --silver_table               — cleaned_statistics



silver_to_gold


--silver_database = yt-pipeline-silver-dev
--gold_bucket =  yt-project-gold
--gold_database =  yt-pipeline-gold-dev