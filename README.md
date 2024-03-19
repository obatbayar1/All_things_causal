# Causal Inference

---
Causal Inference is a great interest of mine. Coming from an Econometrics background, all I ever wanted to eliminate was that error term. Be it with instrumental variables, different research design, difference in difference, prepost analysis, and regression discontinuity, it's safe to say my goal was to observe the real effect. But now, I am thankful for various ML models on the market that would allow me to do much more. Here's something you might find interesting.

<img width="521" alt="image" src="https://github.com/obatbayar1/All_things_causal/assets/136912472/83bbff87-b844-4d90-9a5e-f3e4c6b89384">

---
### Here, I will list my projects related to causal inference, starting with:

### 1. Hillstrom Dataset - Email Market Campaign Effectiveness with S and T learner with Uber's CausalML package.
---

   <img width="687" alt="image" src="https://github.com/obatbayar1/All_things_causal/assets/136912472/e3f14372-2791-40d8-b583-16df388fbd1c">
---
    Some key takeaways:

   <img width="685" alt="image" src="https://github.com/obatbayar1/All_things_causal/assets/136912472/60c9d661-3188-47b8-a7d6-9ef044627c76">
---
  <img width="840" alt="image" src="https://github.com/obatbayar1/All_things_causal/assets/136912472/0e07af37-d227-4d2c-af37-bff9cee68676">

  <img width="827" alt="image" src="https://github.com/obatbayar1/All_things_causal/assets/136912472/b4cb0e67-4e3e-4d03-a4e5-2849b9aed28b">

---
  <img width="825" alt="image" src="https://github.com/obatbayar1/All_things_causal/assets/136912472/1c55fe21-5784-49f4-a988-1d7e79d3f791">
---
  <img width="830" alt="image" src="https://github.com/obatbayar1/All_things_causal/assets/136912472/9824f86a-26b3-4875-b89e-e182f385dcfb">

**For "Mens E-Mail"**:

- History: The most important predictor of men visiting the website after receiving an email is the actual dollar amount they spent in the past year. This suggests that higher spenders are more likely to engage with the website again.
- Womens: The fact that this is a significant predictor indicates that men who have purchased women's merchandise in the past year are also likely to respond to the email campaign by visiting the website.
- Recency: This suggests that the more recently a man has made a purchase, the more likely he is to visit the website after receiving an email campaign.
- Mens: Men who have purchased men's merchandise in the past year have a moderate likelihood of visiting the website in response to the campaign.
- Newbie: New customers are somewhat likely to visit the website, which suggests that the email campaign may be effective in engaging new customers. Other features like the customer's location (zip_code) and the channels they've used (channel) seem to have less influence compared to the aforementioned features.

**For "Womens E-Mail":**

- Womens: The strongest predictor for women visiting the website after receiving an email is whether they have purchased women's merchandise in the past year. This suggests that targeting women with relevant past purchases can be effective.
- History: Similar to the mens' model, the actual dollar amount spent in the past year is a strong predictor of engagement with the website.
- Recency: The timing of the last purchase plays a significant role, with more recent shoppers being more likely to visit the website.
- Newbie: New female customers show moderate responsiveness to the email campaign in terms of website visits. Other features related to merchandise type (mens), location (zip_code), and purchasing channels (channel) are less predictive of website visits in response to the campaign.

In summary, both for men and women, personalized content that aligns with their past purchase behavior, particularly the types of merchandise they have bought and the amount spent, is highly predictive of their likelihood to visit the website following an email campaign. Recency of purchases also plays a crucial role, with more recent customers being more engaged. New customers show some potential for engagement, suggesting that email campaigns can be an effective tool for nurturing these relationships. Location and purchase channel are less indicative of whether an individual will visit the website post-campaign.



