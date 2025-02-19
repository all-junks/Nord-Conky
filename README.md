<h1 align=center>Nord-Conky</h1>
<h3 align=center><img width=400 src="https://github.com/all-junks/Nord-Conky/blob/main/Screenshot%20From%202025-02-19%2014-54-07.png"/></h3>
<h3 align=center><em>Variant 1, "Normal"</em></h3>
<h3 align=center><img width=400 src="https://github.com/all-junks/Nord-Conky/blob/main/Screenshot%20From%202025-02-19%2014-53-41.png"/></h3>
<h3 align=center><em>Variant 2, "Multicolour"</em></h3>
<h2 align=center><em>“Monotonous but simple & glorious„</em></h2>
<h1 align=center>
<img src="https://img.shields.io/badge/Linux_Only-OS?style=for-the-badge&logo=linux&logoColor=ebcb8b&label=os&labelColor=2e3440&color=ebcb8b"/>
<img src="https://img.shields.io/badge/Theme-conky?style=for-the-badge&logoColor=b48ead&label=conky&labelColor=2e3440&color=b48ead"/>
<img src="https://img.shields.io/github/stars/all-junks/Nord-Conky?style=for-the-badge&label=Stars&labelColor=2e3440&color=d08770"/>
<img src="https://img.shields.io/badge/gpl--v3.0-license?style=for-the-badge&logo=gnu&logoColor=bf616a&label=license&labelColor=2e3440&color=bf616a"/>
</h1>

I've switched from XFCE to GNOME desktop environment & I went full Nord on my Manjaro installation & I'm loving it! My dotfiles on how to replicate my theme on GNOME will be coming soon! Now, let's continue to the installation:-

## How to install:-

- Open your terminal & type:-
  <pre>git clone https://github.com/all-junks/Nord-Conky.git; cd Nord-Conky; sudo chmod 755 install.sh; sudo +x install.sh; ./install.sh</pre>

- After installation finishes, open your <code>Conky Manager (2)</code> & open <code>Application Settings</code>

- Enable <code>Run Conky at system startup</code> & change <code>Startup Delay (seconds)</code> to 0

- Change tab to <code>Locations</code> & press the <code>Add</code> button

- Add the <code>~/.config/conky</code> directory & press <code>OK</code>

- If you want to change the weather location (default is Kolkata), select any one of my 2 themes, press <code>Open Theme Directory</code> & open the <code>weather-v2.0.sh</code> inside the <code>scripts</code> folder

- Open [this link](https://openweathermap.org) & search for your city in the website searchbar

- Copy the string of numbers at the absolute right of your browser linkbar

- Change the numbers in the line where <code>city_id=</code> is written to the copied text

- Save the file & press the <code>Start/Restart</code> button in the <code>Conky Manager (2)</code> window

### Enjoy!

## Changelog (v1.0.0):-

- Created repo

<h1 align=center>You can support me by downloading & installing my Conky theme! It means a lot to me!</h1>
