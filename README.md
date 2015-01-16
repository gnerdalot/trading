# trading

bdaysago - business days ago
tc2000-formulae - tc2000 condition generator

lib - for Calendar::Profiles - cause cpan was hard.


tc2000-formulae.pl <sub> --span <int> --tol <float> --start <int> --end <int>

Options:

Start/End/Span: counts backwards from today (zero).
--start 0 --end 200 means start today, go 200 days back

Subs:
base          : keeps within a band for some days
bowtie        : 10sma, 20ema, 30ema cross over, forming a bowtie (Dave Landry)
bullishrevbar : higher close, lower low. http://www.tradingsetupsreview.com/10-price-action-bar-patterns-must-know/
daylight      : 20+ lows are above 10SMA - creating daylight between the candle and first MA line
dns           : dns system - Dans New system - combines 8 indicators into a binary signal - http://www.tradeon.com/tradeon/tc2000/dns.html
dns2          : DNS, version 2: same web page towards end
ema           : ema, width, and how far back. --ma 72 --end 200 what was the 72day EMA, 200 days ago
gaps          : look for gaps
help          : help
layered       : same as sandwich, but in order 10sma, 20ema, 30ema
linreg        : http://forums.worden.com/default.aspx?g=posts&t=56359
macdcrossup   : where macd crosses 0, up, 12-day EMA - 26-day EMA
pullback      : short run of lower highs and lower lows
rsi           : rsi cross
sandwich      : 10sma, 20ema, 30ema sandwiched together, perhaps mixed
sma           : sma, width, and how far back. --ma 50 --end 100 what was the 50day SMA, 100 days ago
trending      : higher highs and higher lows OR lower highs and lower lows
trendingmin   : min of close over long-term spans
tripletap     : look for tripletaps
turtle        : http://www.bizmove.com/trade/binary-options-strategy.htm


