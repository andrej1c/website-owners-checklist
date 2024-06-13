# Website Owner's Checklist

## Domain Registration 

1. Where is your domain registered?
1. Do you know the username/password to your account on the registrar's website?
1. Does the domain registration auto-renew or does it require you to take specific steps every year?
1. Do you know when your credit card on file expires? Will you get an email notification before this happens?
1. What email address is connected to your account on the registrar's website for email notifications?
1. Does your domain registrar disclose your name or contact information? (They shouldn't)

## Hosting

1. Where is your website hosted?
1. Do you know the username/password to access your account with the hosting company? (The account where you configure your hosting plan and configure payment plan)
1. Does the hosting auto-renew?
1. Do you know when your credit card on file expires? Will you get an email notification before this happens?
1. What email address is connected to your account on the hosting company's website for email notifications?

## SSL Certificate 

1. Does your website have an SSL certificate in place?
1. Does it auto-renew? If not, do you know how to renew it manually?
1. If you're not using a free SSL certificate (from Let's Encrypt etc.) but bought one, do you know when your credit card on file expires? Will you get an email notification if this happens?
1. What email address is connected to your account for email notifications about your SSL certificate?

## Access / Security

1. Do you know who all has ftp access to your website?
1. Do they use plain (insecure) FTP or sFTP? Do _they_ know the difference? (FTP should really be disallowed)
1. Do you know who all has access to your WordPress admin? Do they have the minimum possible access that would still allow them to do their job?
1. Do you require and enforce a strong password policy?
1. Do you require all (or at least admin) users to have two factor authentication?
1. Does your team know to never share passwords with anyone?
1. Does your website force https to access WordPress admin?

## 3rd Party Systems

1. Do you have a technical architecture diagram showing all the 3rd party systems your website integrates with that also shows high level detail of what data travels what direction?
1. Do you have access to all related accounts at the 3rd party systems? Are you aware when they renew and at what cost, what credit card is on file etc.?
1. Do you know who all has access to each of these systems?
1. Are the passwords secure?

## Monitoring

1. Do you have monitoring with notifications to let you know when your website is down?
1. Do you have a mechanism protecting your login form from dictionary attacks (automated attacks trying every word in the dictionary as your password)?
1. Do you have a mechanism monitoring file changes to let you know when website files change (meaning, it was possibly hacked)?
1. Would you be notified if Google had an issue indexing content from your website?

## Updates / Security

1. How often do you update WordPress core, plugins and themes? Every time a new security update comes out? (You should)
1. Would you notice if a plugin you're using has been abandoned (no longer maintained for security)?
1. Do you have a staging site where you test updates before installing them on your production site?
1. Do you know what plugins are on your site and what they each do for you? Do you only have plugins that are current, active and actually needed?

## Subscriptions

1. Do you use any paid/premium plugins or themes that require an annual renewal? Are these on auto renew? What credit card? Will you be notified....

## Disaster Recovery

1. Do you have an automatic backup system?
1. How often do you check if it's in fact running?
1. Would you be notified if the automatic backup failed or stopped running?
1. How often do you test restoring from a backup?
1. If your website got hacked and started showing inappropriate content do you have a process in place to restore the site from a backup?
1. If the entire hosting company went dark for several days do you have a process in place to quickly rebuild at another hosting company from backup?
1. Do you have a developer on retainer and on speed dial that you could reach out to?

## Performance

1. Do you know if your website performs well on computers as well as mobile devices?
1. Does Google think your website is fast?

## Tracking / Analytics

1. What tracking/analytics do you have in place?
1. Who is responsible for monitoring each tracker, for reporting and for creating action plans based on the data?
1. Do you have access to all of those systems?

## People

1. If your IT person (or your web contractor) suddenly leaves or falls sick long term, do you have sufficient documentation to quickly onboard someone new?
1. If your IT person (or your web contractor) suddenly leaves, do you have a process in place to remove their access from all your systems?
1. Are any of your accounts (domain registration, hosting, subscriptions...) tied to a specific person's email address? (Hint: use something like licensing@nameofyourcompanywebsitehere.com instead)
