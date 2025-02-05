# cuddly-octo-lamp
Facebook info
import requests

def get_facebook_user_info(access_token, user_id):
    base_url = "https://graph.facebook.com/"
    url = f"{base_url}{user_id}"
