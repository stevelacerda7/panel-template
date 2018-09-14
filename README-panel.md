Configuration options include:
  consts at top of CONFIG_ALERTS
  CONFIG_SCRIPT
    - constants used throughout for intervals, dateFormats, and history

  CONFIG_ALERTS
    objectnames: list of strings, a list of objectNames to display alerts for
    primaryfield: string, shown on main line as headline of alert
    number: int, number of alerts to display
    backgroundcolor: string, this is actually the font color for the title in hex
    color: string, general color for all the metric fonts in hex

  CONFIG
    uielements - string, can be comma-separated with no spaces after comma
      ex. 'lights-gps,env-gps';
    backgroundcolor: string, color value in hex
    color: string, color value in hex of font color
    imagesrc: string, url of image to use for buttons on top of panel
    title: string, title that is displayed at the top of the panel

  Style variables
    --triangle-color: #00000098 // color used for triangle under images at top of panel
    --alerts-title-background: #ff0000 // background color of alerts title and used for font color of alerts headlines
