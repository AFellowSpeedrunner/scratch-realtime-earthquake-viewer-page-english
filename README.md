# scratch-realtime-earthquake-viewer-page

This is the code and English translation of the [Real-time Earthquake Viewer project](https://scratch.mit.edu/projects/636244032) created with Scratch and packaged using the [Turbowarp Packager](https://packager.turbowarp.org/#636244032).
You can easily push to GitHub Pages, so give it a try. Since the materials are shared on Scratch, the images and audio in [/assets](https://github.com/kotoho7/scratch-realtime-earthquake-viewer-page/tree/main/assets) are subject to the [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/deed.ja) license.

## Description in Scratch

You can mainly see the following information.

- **Earthquake information and the details of the last 9 earthquakes**
- **Real-time seismic intensity and Earthquake Early Warning Announcments (EEW)**
- **Tsunami forecast and tsunami observation information**

> Information is received from DM-D.S.S (a service that distributes data directly from the Weather Service Support Center), so the information will arrive faster than from TV or smartphone apps.
> *Data is updated using cloud variables. Please be careful as it may stop or have bugs. (Only on Scratch)
> *It will not work if you are using New Scratcher or are not logged in. (Only on Scratch)

The project works [like this](https://youtu.be/83u_s1SKq1I) (as of v1.3.1). [This is what happens] when there is a deep earthquake (https://youtu.be/n83NO49gfHk/)

## Operation Guide

The screen changes automatically depending on the shindo level of shaking or earthquake information.

|Operation|Method|
|---|---|
|Enlarge/Reduce|Long press from bottom left button or mouse scroll or double tap|
|Camera reset|Bottom left button|
|Switch tabs on the left|Click the tab icon|
|Scroll tabs|Scroll and drag mouse|
|Restart project (in case of a project breaking bug)|Hold down Z and Q|

## Notes on displayed information

### Real-time Seismic Intensity

- This is different from the seismic intensity announced on TV etc. Equivalent values of seismic intensity observed by strong motion observation networks (K-NET, KiK-net) are displayed.
- Earthquakes that occur deep down can cause shaking in areas far from the epicenter because the shaking is transmitted along the tectonic plates (abnormal seismic area).

### Earthquake Early Warning

- Information is created within seconds after an earthquake occurs, so false alarms may occur.
- Information immediately after an earthquake is detected may have low accuracy regarding the epicenter, magnitude, and predicted seismic intensity.
- Even under normal circumstances, the estimated seismic intensity has an error of about 1 class.
- For earthquakes deeper than 150km, the expected maximum seismic intensity will not be announced.
* Announcements may be made based on actual shaking.

## Information Sources

- Real-time seismic intensity
[National Institute of Earth Science and Disaster Prevention Long-period Earthquake Monitor](https://www.lmoni.bosai.go.jp/monitor/)

- Earthquake Early Warning (re-distribution permission obtained) & earthquake information & tsunami information
[Project DM(Disaster Mitigation)-Data Send Service](https://dmdata.jp/docs/telegrams/)
- Earthquake information update (up to 2 days ago)
[Meteorological Agency seismic intensity database search](https://www.data.jma.go.jp/svd/eqdb/data/shindo/)

- Undersea seismometer
[Marine situation display system (UmiShiru) strong motion information](https://www.msil.go.jp/)

### Referenced explanation

- [Determine numerical data from strong motion monitor images using polynomial interpolation]
<https://qiita.com/NoneType1/items/a4d2cf932e20b56ca444>

### Materials used

#### Map of Japan

- Japan Meteorological Agency GIS data such as forecast areas
Earthquake early warning/prefectural forecast area
Earthquake information/subdivision area
Tsunami forecast area
　<https://www.data.jma.go.jp/developer/gis.html>

- Ministry of Land, Infrastructure, Transport and Tourism National Land Numerical Information Lake Data
<https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W09-v2_2.html>

#### World Map

- Natural Earth 1:10m Cultural Vectors (Japan POV)
<https://www.naturalearthdata.com/downloads/10m-cultural-vectors/>

-NOAA ETOPO
<https://www.ngdc.noaa.gov/mgg/global/>

#### Font

-Akshar
　<https://fonts.google.com/specimen/Akshar>
- BIZ UDPGothic
　<https://fonts.google.com/specimen/BIZ+UDPGothic>

*Both are SIL Open Font License

#### Sound Effects

- OtoLogic news caption
<https://otologic.jp/free/se/news-accent01.html>

*This sound effect selection was based on [BSC24 Earthquake Warning Broadcast 24 Hours](https://ch.nicovideo.jp/bousai-share).
*The sound for seismic intensity detection was created based on the sound effects from the [JQuake application](https://jquake.net/).
