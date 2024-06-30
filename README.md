# My codes for my honors thesis.

### Definitions:

  _Ionosphere:_ Layer in the Earth's atmosphere with free electrons and ions lying at 50-1000km [1] above Earth's surface. Have sub-regions
              D, E, and F layers. I focused on the D and E layers. The ionosphere makes long distance communication possible.
  
  _Ionosonde:_ Radar system looking vertically upwards [2] that measures the electron density of the ionosphere. It sends radio signals 
             vertically and derives information from the time taken for waves to reflect back and the frequency shifts experience 
             by signals.
  
  _Riometer:_ An instrument that measures the amount of cosmic radio noise that can pass through the ionosphere [3]. The power the riometer 
            receives change with the ionospheric electron density
  
  _Appleton-Hartree equation:_ Equation describing how the absorption of high frequency (HF) signals are affected by the rate of
                             collision of ionized particles with neutral particles in the ionosphere

### Goal:

  Missing/fill values were detected in the Gakona, Alaska ionosonde's data in the Global Ionosphere Radio Observatory database. 
      Missing values might have a link to riometer activity at Dawson, Yukon. My goal was to find correlations between Dawson, YK 
      riometer and Gakona, AK ionosonde during specific occasions (concluded it is during high absorption events. Consistent with high 
      frequency (HF) wave absorption interfering with the ionosonde's sounding technique where the ionosonde might not be receiving 
      reflected waves back during high absorptions)

### Brief overview of method:

  Chose the year 2012's data to look into after having plotted ionosonde data from 2012-2022. 2012 provided consistent data. Then, I
  focused on one day in 2012 that has absorption values greater than 3dB (looking for higher absorption events because the riometer
  does not detect low absorption events, so there will be nothing to compare the ionosonde data with). Compared riometer and ionosonde
  data by plotting using matplotlib and noticed ionosonde data drops when absorption values peak in riometer. 
  Then, I chose 12 days in 2012 with the most count of absorption measurements greater than 3dB. Observed the same trend as before.
  There was more plotting done with many different metrics to find consistency with the Appleton-Hartree equation.

### Citations:

  [1] McElroy, M. B. (2023), Ionosphere and magnetosphere, Encyclopædia Britannica.  Available from: 
      https://www.britannica.com/science/ionosphere-and-magnetosphere
      
  [2] Anon (n.d.), Ionosonde, PITHIA. Available from: https://pithia-nrf.eu/activities-results/outreach/space-weather-research-instruments/ionosonde

  [3] R.A.D. Fiori, and D.W. Danskin (2016), Examination of the relationship between riometer-derived absorption and the integral proton 
  flux in the context of modeling polar cap absorption, AGU Publications from: https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2016SW001461
