# Horizon-Ephemeris-Calendar

composed of:
metonic 13-month lunar phase calendar, celestial-heliacal event based calendar, 12h digital clock, 5-mins-ahead 12h "polite cloche" style digital clock, 24h UTC digital clock, "earthly tilt" seasonal calendar

This calendar tool is within the context of a digital almanac that is currently in production. 
At the most simplistic level this is a way for users to plan their planting schedules. 
At a larger level the goal is to begin to get people breaking beyond the confines of 
a 12h / 24h manner of time keeping in an accessible way. This aims to present expanded ways 
of measuring our temporality's texture instead of simply “keeping time”.

For users with astrological literacy, this becomes a nifty tool for ameliorating a few of the 
pain points that come with practicing that craft effectively: having to correct for universal 
time, research specific sunrises and sunsets to deign day charts/night charts, having to head 
scratch when figuring out the movements of specific stars during research... these things get 
clunky so this “calendar” makes grappling with this type of work a bit easier.

This tool inhabits very simple front end/backend paradigm where the frontend serves as a 
graphical display for some quite rich backend libraries. It is ephemeris style, meaning that 
one would be able to query the calendar for specific dates or times. This calendar then renders 
that information visible upon a graphical display. Location data is necessary, of course, to 
take user’s time zones into account plus the specifics about the diurnal sunrise/sunset data.
The calendar would by default run like a “clock” but users can query for specific dates and times.
Above all, this tool is a 13-month lunar calendar, communicating when moon presents as full vs 
when it presents as otherwise. By analyzing, additionally, the season of the upper hemisphere
of the Earth (distance ratio between solstices and equinoxes), this calendar reports to us an 
all-inclusive, percentage-based measure of the earth's tilt in respects to the sun.


GNU GPL 2
This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
