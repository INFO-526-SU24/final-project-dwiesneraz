# Data

**Trash Collection Wheels**: This dataset provides information about four trash collection wheels around the Harbor of Baltimore, Maryland. The trash category counts are extrapolated from samples from periodic manual counts of each category of trash on the wheel's conveyor paddles.

Much of this data is quantitative, providing the counts of the various categories of trash for each collection wheel at each manual check, labeled by date and dumpster load which is a separate count for each wheel.

# Codebook for Trash Collection Wheels Dataset

## Variable Names and Descriptions:

`ID` - Shortened name of the trash collection wheel.

`Name` - Full name of the trash collection wheel.

`Dumpster` - Number of dumpster load that the record counts were extrapolated from (counted independently for each wheel).

`Month` - Written out month of record.

`Year` - Written out year of record.

`Date` - Full date in m/dd/yyyy format.

`Weight` - Weight in tons.

`Volume` - Volume in cubic yards.

`{PlasticBottles, Polystyrene, CigaretteButts, GlassBottles, PlasticBags, Wrappers, SportsBalls}` - Number of each of the seven categories of trash respectively.

`HomesPowered` - Number of homes powered by burning of the trash (\~500 kilowatts per ton of trash).

## Data Types:

`{ID, Name, Month, Date}` - `chr`

`{Dumpster, Year, Weight, Volume, PlasticBottles .. SportsBalls, HomesPowered}` - `dbl`
