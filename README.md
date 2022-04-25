# DIY-Entry-Signals
TradingView script for the DIY Entry Signals indicator
This indicator allows you to set up entry signals based on your own conditions.

Note that this indicator DOES NOT give any information about exits. It is not intended to be a signal indicator that someone could blindly follow. It is intended for use in backtesting to help spot entry points more easily.

Also note that this indicator DOES NOT plot anything other than moving averages and entry signals. The other indicators referenced will need to be added on their own to be visible on the chart.

Credit to The_Caretaker for both BBWP and PMARP indicators. For more information on how those work, see their descriptions. Big thanks to him for making them open source, as well.


Instructions for use:

Signal Types:
This section allows you to choose whether you want long, short, or both types of signals.

Moving Averages:
Configure up to 4 moving averages to be plotted on the chart. Options include show/hide, color, length, and type.

RSI:
Choose the period and source used for the Relative Strength Index indicator, a very commonly used momentum oscillator.

Stochastic:
Choose the K, D, smoothing, and source for the Stochastic indicator, a very commonly used momentum oscillator.

BBWP:
Choose settings for the Bollinger Band Width Percentile indicator. This measures volatility based on Bollinger Bands and was created by The_Caretaker. The indicator is free and open source, so definitely check it out.
This section allows the user to choose the price source, basis type ( SMA , EMA , or VWMA ), length, and lookback. It also includes a threshold setting to determine the BBWP requirement used for entry signals.

PMARP:
Choose settings for the Price Moving Average Ratio & Percentile. This calculates the ratio between a source price and moving average over a lookback period. This was also created by The_Caretaker, and it is a free and open source indicator.
This section allows the user to choose price source, lookback, PMAR length, and moving average type.

Long/Short Conditions:
Choose which indicators will be used to determine entry signals, as well as some options for each indicator that is included.

Note: A signal will only be plotted if ALL selected conditions are met.
Options in these sections include:
Faster moving averages above or below slower moving averages (implying a trend direction)
RSI thresholds (separate for long and short)
Stochastic thresholds (separate for long and short)
Whether K should be above or below D (implying trend direction of the Stochastic indicator)
Whether a signal should only be generated on the bar when the Stochastic first crosses the threshold.
BBWP on/off (The threshold for this is determined in the BBWP section of the settings)
PMARP thresholds (separate for long and short)
