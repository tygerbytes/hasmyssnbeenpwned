+++
title = "Has my SSN been Pwned?"
outputs = ["Reveal"]
+++


<!-- ## Has my <span style="color: #3e7d95;">SSN</span> been <span style="color: #3e7d95; font-style: italic;">Pwned</span>❓ -->

<img style="border:0; background:none;box-shadow:none;" src="img/hasmyssnbeenpwned.png" alt="Has my SSN been Pwned?">

{{% fragment %}}# <span style="color: red; font-weight: bold;">YES</span>{{% /fragment %}}

---

{{< slide transition="zoom" transition-speed="fast" >}}

## 🤷 Assume your SSN is already <span style="color: red">compromised</span>

<ul>
{{% fragment %}}* [2017 Equifax breach](https://en.wikipedia.org/wiki/2017_Equifax_data_breach) exposes 100M SSN{{% /fragment %}}
{{% fragment %}}* [2021 T-Mobile breach](https://www.t-mobile.com/brand/data-breach-2021) exposes 40M SSN{{% /fragment %}}
{{% fragment %}}* And what about undisclosed breaches?{{% /fragment %}}
{{% fragment %}}* There are only ~330 million US citizens{{% /fragment %}}
</ul>

{{% fragment %}}
> "It's totally reasonable to assume that your social security number has been compromised at least once, if not many times" -- [Mike Chapple](https://www.forbes.com/sites/suzannerowankelleher/2019/08/01/everyones-social-security-number-has-been-compromised-heres-how-to-protect-yourself/?sh=3b2e964a29ac)
{{% /fragment %}}

---

# What can I <span style="font-style: italic;">do?

---

{{< slide id="freeze" transition="zoom" transition-speed="fast" >}}

## ❄️ <span style="color: red;">Freeze</span> your credit ❄️

Make it harder for scammers to open accounts in your name.

* [Equifax](https://my.equifax.com/consumer-registration/UCSC/#/personal-info) - 800-685-1111
* [Experian](https://www.experian.com/freeze/center.html) - 888‑397‑3742
* [Transunion](https://www.transunion.com/credit-freeze) - 888-909-8872

<small>⚠ They may try to sell you "boosts" and "locks" but a credit freeze should be **free**. ⚠</small>

<small>🎗 You will need to temporarily lift freezes to apply for credit. 🎗</small>

---

{{< slide id="socialsecurityaccount" >}}

## Setup a "<span style="color: red; font-style: italic;">my</span> Social Security" account 💳

Set up an [account at ssa.gov account](https://secure.ssa.gov/RIL/SiView.action) so that a bad actor can't get there first and impersonate you.

---

{{< slide id="phishing" >}}

## Assume *every* email, call, text message is a <span style="color: red;">scam</span> 🎭

<small>They may already have your SSN, name, DoB, drivers license, address. They want that **last bit of info** to take over your accounts.</small>

* 📵 Don't click links 
* 📵 Don't call phone numbers
* 📵 Don't respond to text messages

e.g. "Credit card company" calls about some fraudulant activity. **Hang up** and call the number on the back of your credit card

---

{{< slide id="simswap" >}}

## Beware the <span style="color: red">SIM swap</span>

<small>A scammer convinces your wireless carrier to transfer your number to their device. Now they receive your account verification text messages</small>

* Call your carrier and ask to set up a "**Port Freeze**".
* You will need to create a PIN. Make it long, unique, include letters if possible, and save it somewhere safe.

---

{{< slide id="better2fa" >}}

## Get better <span style="color: red">MFA</span>

<small>A SIM swap only helps a scammer if you are using your cell service to prove your identity.</small>

Wherever possible, use an authenticator app instead of your email or cell phone.

* [Google authenticator](https://support.google.com/accounts/answer/1066447)
* [Microsoft Authenticator](https://www.microsoft.com/en-us/security/mobile-authenticator-app)
* [Authy](https://authy.com/)



---

{{< slide id="nossn" >}}

## 🚫 Stop giving out SSN 🚫

* Most websites and paper forms **don't need** your SSN. Make them prove their need.
* You *may* be able to use an [EIN](https://www.irs.gov/businesses/small-businesses-self-employed/how-to-apply-for-an-ein) instead, but talk to lawyer / accountant first.

---

{{< slide id="changessn" >}}

## Can I <span style="color: red">change</span> my SSN? 🤔

Even if your SSN has appeared in a data breach, you can only [get a new number](https://faq.ssa.gov/en-us/Topic/article/KA-02220) if you have already been victim of identity theft and that you *continue* to be "disadvantaged" by using the original number. 


---

{{< slide id="contactftc" >}}

## Contact the <span style="color: red">FTC</span> 📞

If you're a victim of identity thieves, call the Federal Trade Commission at (877) 382-4357 and visit their [identity theft page](https://www.consumer.ftc.gov/features/feature-0014-identity-theft).

---

{{< slide id="donate" background-color="#026724" transition="zoom" transition-speed="fast" >}}

# Stay safe!

[hasmySSNbeenpwned](https://www.hasmyssnbeenpwned.com) brought to you courtesy of **[tygertec](https://www.tygertec.com)**.

{{< donate >}}

Even $1 really helps keep this content updated.

---

{{< slide id="disclaimer" >}}

### Disclaimer
#### This site...

1. does *not* maintain a list of compromised SSN
1. is educational and meant to raise awareness
1. has no relationship with the US government or Social Security Administration
1. provides no guarantees or warranties

View the [source code](https://github.com/tygerbytes/hasmyssnbeenpwned) on GitHub


---

{{< slide id="credits" >}}

### Credits

* Inspired by Troy Hunt's [haveibeenpwned.com](https://haveibeenpwned.com)
* Hugo [theme](https://themes.gohugo.io/themes/reveal-hugo/) by Josh Dzielak
* [Reveal.js](https://revealjs.com/) HTML presentation framework, by Hakim El Hattab