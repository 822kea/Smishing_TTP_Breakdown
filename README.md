# Analyzing Signs of a Smishing Attempt  

## The Message:  

<img src="SMSPhoto/smishing_photo.PNG" alt="Smishing Attempt Example" width="300" />



I recently received an iMessage from an unknown Hotmail address:  

`korhsrd427@hotmail.com`  

They were offering me a job 🎉! Unfortunately for them, the red flags were blazing, and I wasn’t falling for it.  

For those who might not recognize the signs of a smishing attempt, here’s a breakdown of the **red flags** and the **TTPs** the threat actor employed:  

## Red Flags  

1. **Free Email Domain**:  
   - Legitimate businesses typically use a corporate email domain (e.g., `@temu.com`), not free providers like `@hotmail.com`. This indicates the sender is unprofessional—or fraudulent.  

2. **No Personalization**:  
   - The message didn’t address me by name, which is a common sign of phishing or smishing. Personalized messages are less likely to be ignored but harder for scammers to generate at scale.  

3. **I Didn’t Apply to TEMU**:  
   - Always be skeptical of unsolicited offers, especially for positions you didn’t apply for.  

4. **Poor Grammar and Execution**:  
   - The text was riddled with errors and run-on sentences. Professional communication would be polished and concise.  

5. **WhatsApp Contact Information**:  
   - Businesses typically direct you to professional channels like corporate email, LinkedIn, or an official website. Including a WhatsApp number is a major red flag.  

---

## Threat Actor TTPs  

Here’s a breakdown of the **Tactics, Techniques, and Procedures (TTPs)** used by this threat actor:  

1. **Delivery Mechanism**:  
   - **Tactic**: *Social engineering via SMS (smishing)*  
   - The threat actor used iMessage to deliver the bait, exploiting the instant and personal nature of mobile communication.  

2. **Impersonation**:  
   - **Technique**: *Fake job opportunity from a well-known brand*  
   - By referencing TEMU, they aimed to exploit the trust and familiarity associated with a recognizable company.  

3. **Urgency and Exploitation of Emotions**:  
   - **Procedure**: *Preying on job seekers’ desperation*  
   - The message capitalized on economic uncertainty and the natural excitement of receiving a job offer, pushing recipients to act without thinking.  

4. **Use of a Free Email Domain**:  
   - **Technique**: *Anonymity via non-attributable email*  
   - Using a Hotmail account obscures their identity, making it difficult to trace the message back to them.  

5. **Push to Third-Party Messaging Platforms**:  
   - **Procedure**: *Move communication to less secure channels*  
   - Directing targets to WhatsApp likely reduces scrutiny from email spam filters and gives the attacker more control over the interaction.  

---

## Conclusion  

This smishing attempt highlights how threat actors adapt their methods to exploit vulnerable individuals. By using impersonation, social engineering, and urgency, they aim to manipulate recipients into disclosing personal information or sending money.  

If you encounter a message like this, remember the red flags and **pause before you engage**. Threat actors count on you reacting emotionally rather than rationally. Stay vigilant, and don’t let them catch you slipping!  
