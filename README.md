#### Conversion Rate

   
The table is conversion_data. It has information about signed-in users during one session. Each row is a user session.
Columns:

    country : user country based on the IP address
    age : user age. Self-reported at sign-in step
    new_user : whether the user created the account during this session or had already an account and simply came back to the site
    source : marketing channel source
    Ads: came to the site by clicking on an advertisement
    Seo: came to the site by clicking on search results
    Direct: came to the site by directly typing the URL on the browser
    total_pages_visited: number of total pages visited during the session. This is a proxy for time spent on site and engagement during the session.
    converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything. The company goal is to increase conversion rate: # conversions / total sessions.
