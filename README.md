# getting-started

## Tempus est pecunia; scientia sit potentia

A record of the events surrounding the start of https://harbinger.systems

**We observe** market and trading information from LSE, NASDAQ and cryptocurrency exchanges via a network of continuous, real time suppliers.  Over 250,000 articles a month are processed, usually within two minutes of publication.  Add the news sources that you trust.

**We analyse** whether content is relevant to your portfolio.  Enhance your price charts with news, search and share our analysis.

**We integrate** with your messaging solutions and notify you immediately when we find something relevant for you.

Our capable, effective APIs are available for your applications and products.

## Backlog

  * ~~Relocate to Ireland~~
  * Web Summit in Portugal
  * MoneyConf in Dublin

# Journal

## Monday, October 23rd, 2017

Happy to get a first, refreshing view of the site design.

After a flurry of last minute checks, everything's booked for https://websummit.com.  We just have to charge lots of batteries and get to the airport.

So far, architecture automation has been entirely in Bash and it's been fast and reliable.  To get to the next mangnitude of speed, a choice has to be made between the higher level language API client libraries that are available.   It's possible with Bash, but it's good to take the opportunity to try out a new language once in a while.  After discarding the non-starters - thanks but no thanks .Net - it boils down to a choice between Go and NodeJS.

It's an experiment and we're already using lots of NodeJS so [Go wins this round](https://golang.org) !

## Friday, October 20th, 2017

The tropical storm dropped trees on the power lines and shut down power, water and communications for several days but progress was still made.

Payment features for the API and firehose are in testing and article classification has started, so that neural networks can be trained.

The process of registering the business started.  Registering a new business with the Revenue requires a Personal Public Service Number.  Getting a PPS number feels like a Choose Your Own Adventure book.  The experience serves as a reminder that there are still problems out there that can be resolved with web applications.

Online services can verify a passport in seconds.  Let's compare that with the PPS number experience.

A protracted session with the verbose but thorough 'Starting A Business' section of https://revenue.ie revealed a link to another government site, http://www.welfare.ie at which one can make an appointment with an office to get the form you need to fill in to apply for a PPS number.  'Online appointments' are offered through https://www.mywelfare.ie but without a PPSN you cannot register there to book an appointment.

Digging around on the Welfare site revealed a telephone number for a help desk.  The person who answered the phone was sympathetic but unable to help.  They provided another phone number for a different office who, while unable to actually help, did know who could and provided the telephone number for that office.

After confirming that the office does cover this area and having a little discussion about the reason for getting a PPS number ('I want a PPS number to register a business and register a vehicle' 'Well, which is it - do you want to start a business or register a vehicle ?' 'Both, ideally') an appointment was booked for the middle of next week.  At which an official might be persuaded to provide the PPSN application form.  Maybe.

Some insider advice on navigating these systems will no doubt be beneficial so a meeting with the local enterprise office is in the calendar.

Looking forward to a change of pace and some calm coast air in Lisboa at https://websummit.com !

## Friday, October 13th, 2017

First week in Ireland complete

    $ mv ~ ireland

Packing the house up, loading the van and driving several thousand kilometers with a cat across Spain, France and Ireland was an experience.

Meanwhile, performance improvements have seen the average time to detect news halved from about four minutes to about two.  The platform should be able to cope with enough concurrent users to be viable.

Web Summit is fast approaching, so we're concentrating on getting the site presentable.

## Wednesday, September 13th, 2017

Last day in the office

## Tuesday, September 12th, 2017 

[Hacker News](https://news.ycombinator.com) usually has something interesting.  Today I found a free economics course at https://www.core-econ.org and [a font for placing sparkline graphs in text](http://aftertheflood.co/projects/atf-spark).

Elsewhere, [startup resources](https://www.enterprise-ireland.com/en/Start-a-Business-in-Ireland/Information-Store-for-Start-ups) at Enterprise Ireland, making more revisions to our introductory copy.

## Monday, September 11th, 2017

Search time was reduced from an average of 4000ms to under 200ms !

The next two weeks is going to be a happy kind of chaos, so it's time for a code freeze before we reconnect from a completely different location.

Yoda the cat has *no idea* what's about to happen.

## Friday, September 8th, 2017

Friday evening in Europe was Friday morning for the west coast of North America.  Big thanks to James for spending time on Skype for a motivating and challenging chat about where Harbinger is at the moment, how we got there and where we are heading.

Not sure if the pitch delivery practice is paying off, or if it's standard operating procedure in LA to react with a hearty, enthusiastic "Amen brother !" but the conversation was appreciated.

## You have enough money to trade

Different people say different things about investment.

  * "Don't risk what you can't lose"
  * "Risk everything you can lose"
  * "I don't have enough spare money to invest"

This seems unfair.  Let's let the data decide.

Assuming you have ten to invest.  Euros, dollars, pounds sterling.  Doesn't matter.

Can you make one percent ?  In a day ?

Forex, stocks and shares, cryptocurrency.  Again, it doesn't matter.

If you can do that regularly, you need some dedication.

After ten days of making 1% every day, your 10 becomes 11.05 which hardly seems worth the effort, but keep at it.

After a hundred days of making 1% a day, your 10 becomes 27.05 which is a little disappointing.  A hundred days and it's doubled but not much more.

Let's fast-forward to a year.  After 365 days of making 1%, your 10 becomes 377.83 !  Now that's starting to get interesting but it's like grinding through the early levels of a video game.  Tedious.  Is this worth it ?

After five hundred days, your 10 becomes 1,447.73 which is less tedious.

Day 750 in the 1% a day grind and your 10 becomes 17,419.29.  Do you have motivation yet ?

After 1,000 days of making 1% at a time, your 10 becomes 209,591.56

|Day | Closing balance|
|--|--:|
|0 | 10.00|
|10 | 11.05|
|100 | 27.05|
|365 | 377.83|
|500 | 1,447.73|
|750 | 17,419.29|
|1,000 | 209,591.56|

Time is money, information is power

## What we're starting with

Our initial toolset is designed to keep costs down and to stay out of the way

 * Telegram for day to day conversation and occasional calls
 * Trello for reminders and prioritisation
 * A couple of cloud computing suppliers
 * A Raspberry Pi
 * A couple of domestic ADSL connections
 
Well, I say domestic ADSL.  Mine is via squarial from the top of a nearby mountain, so it's an 'up to' 2 megs deal, depending on weather, which has been workable so far.  SSH connections don't need much bandwidth.

The intermittent and spiky power supply has eaten a UPS, though.  I'm hoping that relocating will bring some stability of power and connectivity.
