# Sublist3r

## Task 1 Intro

You can also use this site if you don't want to run Sublist3r: [https://dnsdumpster.com/](https://dnsdumpster.com)

You can find Sublist3r [here](https://github.com/aboul3la/Sublist3r)! We'll install this in the next task.

{% hint style="success" %}
No answer needed
{% endhint %}

## Task 2 Installation

### First, let's change to our opt directory: cd /opt

![](<../.gitbook/assets/image (238).png>)

{% hint style="success" %}
no answer needed
{% endhint %}

### Next, let's clone the Sublist3r repository into opt: git clone [https://github.com/aboul3la/Sublist3r.git](https://github.com/aboul3la/Sublist3r.git)

{% hint style="success" %}
no answer needed
{% endhint %}

### Now let's move into the Sublist3r directory we've just created: cd /opt/Sublist3r

{% hint style="success" %}
no answer needed
{% endhint %}

### Finally, let's install the requirements for running Sublist3r: pip3 install -r requirements.txt

{% hint style="success" %}
no answer needed
{% endhint %}

## Task 3 Switchboard

![](<../.gitbook/assets/image (239).png>)

### What switch can we use to set our target domain to perform recon on?

{% hint style="success" %}
\-d
{% endhint %}

### How about setting which engines we'll use for searching? (i.e. google, bing, etc)

{% hint style="success" %}
\-e
{% endhint %}

### Saving our output is important both so we don't have to run recon again but also so we can return to our returns and review them at a later time. What switch do we use to define an output file?

{% hint style="success" %}
\-o
{% endhint %}

### Sublist3r can sometimes take some time to run but we can speed through up the use of threads. Which switch allows us to set the number of threads?

{% hint style="success" %}
\-t
{% endhint %}

### Last but not least, we can also bruteforce the domains for our target. This isn't always the most useful, however, it can sometimes find a key domain that we might have missed. What switch allows us to enable brute forcing?

{% hint style="success" %}
\-b
{% endhint %}

## Task 4 Scans away!

![](<../.gitbook/assets/image (240).png>)

### Let's run sublist3r now against nbc.com, a fairly large American news company. Run this now with the command: python3 sublist3r.py -d nbc.com -o sub-output-nbc.txt

{% hint style="success" %}
No answer needed
{% endhint %}

### Once that completes open up your results and take a look through them. Email domains are almost always interesting and typically have an email portal (usually Outlook) located at them. Which subdomain is likely the email portal?

{% hint style="success" %}
mail
{% endhint %}

### Administrative control panels should never be exposed to the internet! Which subdomain is exposed that shouldn't be?

{% hint style="success" %}
admin
{% endhint %}

### Company blogs can sometimes reveal information about internal activities, which subdomain has the company blog at it?

{% hint style="success" %}
blog
{% endhint %}

### Development sites are often vulnerable to information disclosure or full-blown attacks. Two developer sites are exposed, which one is associated directly with web development?

{% hint style="success" %}
dev-www
{% endhint %}

### Customer and employee help desk portals can often reveal internal nomenclature and other potentially sensitive information, which dns record might be a helpdesk portal?

{% hint style="success" %}
help
{% endhint %}

### Single sign-on is a feature commonly used in corporate domains, which dns record is directly associated with this feature? Include both parts of this subdomain separated by a period.

{% hint style="success" %}
ssologin.stg
{% endhint %}

### One last one for fun. NBC produced a popular sitcom about typical office work environment, which dns record might be associated with this show?

{% hint style="success" %}
office-words
{% endhint %}
