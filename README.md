<details>
<summary>**NodeJs To Python(Bonus-Engine APi)**</summary>:
    
- **1)Get Intro Banners for User :**

    ```jsx
    {
                    "url":"https://stagebonus.rummy777.com/bonus/api/get_active_banners_for_user/",
                    method: 'POST',
                    headers: { accept: 'application/json', 'content-type': 'application/json' },
                    body: JSON.stringify({
                        "event_type": "show_intro_banners",
                        "new_user": false,
                        "timestamp": "2023-08-17T06:35:25.449Z",
                        "brand_id": "jaqk"
                    })
    }
    ```
    
- **2)Get Active Main Banner for User :**
    
    ```jsx
    {
    				"url":"https://stagebonus.rummy777.com/bonus/api/get_active_banners_for_user/"
    				method: 'POST',
    				headers: { accept: 'application/json', 'content-type': 'application/json' },
    				body: JSON.stringify({
    					"platform": "rmg",
    					"visible_screen": "lobby_home",
    					"event_type": "show_banners",
    					"lt_deposit_count": 0,
    					"club_level_id": 0,
    					"new_user": false,
    					"brand_id": "jaqk"
    		})
    }
    ```
    
- **3)Get Loyalty Points after GamePlay :**
    
    ```jsx
    {
    				url:"https://stagebonus.rummy777.com/api/loyalty_points_config/",
    				method: 'POST',
    				headers: { accept: 'application/json', 'content-type': 'application/json' },
    				body: JSON.stringify({
    					"event_type": "loyalty_points_onwinloss",
    					"game_type": "rummy",
    					"user_level": 0,
    					"game_result": "win",
    					"amount": 100,
    					"brand_id" : "fas_fas"
    				})
    }
    ```
    
- **4)Get Loyalty Journey :**
    
    ```jsx
    {
    				url:"https://stagebonus.rummy777.com/api/get_active_bonus_for_user/",
    				method: 'POST',
    				headers: { accept: 'application/json', 'content-type': 'application/json' },
    				body: JSON.stringify({ "event_type": "loyalty_journey", "brand_id": "jaqk" })
    }
    ```
    
- **5)Get PowerCoins Config :**
    
    ```jsx
    {
    				url:"https://stagebonus.rummy777.com/api/get_powercoins_config_summary/",
    				method: 'POST', 
    				headers: {accept: 'application/json'},
                    body: JSON.stringify({                        
                        "brand_id": "jaqk"
                    })
    					
    }
    ```
    
- **6)Get Coin Burn Bonus For User:**
    
    ```jsx
    {
    				url:"https://stagebonus.rummy777.com/api/get_active_bonus_for_user/",
    				method: 'POST',
    				headers: { accept: 'application/json', 'content-type': 'application/json' },
    				body: JSON.stringify({
    					"reward_points_burned_timestamp": "2023-07-23T22:15:00Z",
    					"club_level_id": 0,
    					"event_type": "reward_burn",
    					"brand_id":"fas_fas",
    					"reward_points_burned": "10"
    				})
    	}
    ```
    
- **7)Get Signup Bonus for User:**
    
    ```jsx
    {
    				url:"https://stagebonus.rummy777.com/api/get_active_bonus_for_user/",
    				method: 'POST',
    				headers: { accept: 'application/json', 'content-type': 'application/json' },
    				body: JSON.stringify({
    					"signup_timestamp": "2023-07-23T22:15:00Z",
    					"platform": "rmg",
    					"used_referral_code": false,
    					"referral_code_type": "normal",
    					"deviceid_count": 1,
    					"mobile_number": "0000002323",
    					"event_type": "signup",
    					"brand_id": "jaqk"
    				})
    	}
    ```
    
- **8)Get Referrer Signup Bonus For User:**
    
    ```jsx
    {
    				url:"https://stagebonus.rummy777.com/api/get_active_bonus_for_user/",
    				method: 'POST',
    				headers: { accept: 'application/json', 'content-type': 'application/json' },
    				body: JSON.stringify({
    					"signup_timestamp": "2021-09-17T05:01:34+00:00",
    					"user_id": null,
    					"referral_code": "nldi7r",
    					"friend_user_id": "6143139caa1c45e237c81009",
    					"friend_user_level": 6,
    					"friend_user_count": 0,
    					"platform": "rmg",
    					"event_type": "referee_signup",
    					"brand_id": "jaqk"
    				})
    }
    ```
    
- **9)Get Purchase Bonus For User:**
    
    ```jsx
    {
    				url:"https://stagebonus.rummy777.com/bonus/api/get_active_bonus_for_user/",
    				method: 'GET',
    				headers: { accept: 'application/json', 'content-type': 'application/json' },
    				body: JSON.stringify({
    					"used_referral_code": false,
    					"referral_code_type": "normal",
    					"lt_deposit_count": 0,
    					"lt_deposit_amount": 0,
    					"add_cash_click_timestamp": "2023-08-16T05:45:52.919Z",
    					"user_signup_timestamp": "2023-07-16T05:45:52.919Z",
    					"user_id": 100,
    					"club_level_id": 0,
    					"event_type": "add_cash",
    					"brand_id": "jaqk"
    				})
    			}
    ```
    
- **10)Get All Referrer Purchase Bonus:**
    
    ```jsx
    { 
    			url:"https://stagebonus.rummy777.com/api/referrer_purchase_bonus/",
    			method: 'GET', 
    			headers: { accept: 'application/json' } 
    			body: JSON.stringify({                        
                          "referral_code_type": "user_linked",
                          "user_deposit_amount": 100,
                          "user_deposit_timestamp": "2021-09-17T05:01:34+00:00",
                          "referral_code": "nldi7r",
                          "user_id": "6143139caa1c45e237c81009",
                          "user_lt_deposit_count": 0,
                          "friend_user_id": "6143139caa1c45e237c81009",
                          "friend_club_level_id": 6,
                          "friend_lt_referral_bonus": 100,
                          "event_type": "referee_signup",
                          "brand_id": "fas_fas"
                })
    }
    ```
</details>
