# Heikin-Ashi Candlesticks
Heikin-Ashi candlesticks for pandas dataframe.

## Dependencies
*  pandas

### Installing Dependencies

#### Anaconda
If you use Anaconda, you don't have to do anything for installing pandas. It is preinstalled.

#### Miniconda
`conda install pandas`

#### Pip
`pip install pandas`

## Usage

```
git clone https://github.com/emreturan/heikin-ashi
```

```
from heikin_ashi import heikin_ashi
heikin_ashi_df = heikin_ashi(df)
```

Example **df** dataframe structure (_date_ column is index of **df**):

| date                | close     | high      | low       | open      |
| --------------------| ----------| ----------| ----------| ----------|
| 2017-09-26 21:00:00 | 0.188900  | 0.188900  | 0.188900  | 0.188900  |
| 2017-09-27 00:00:00 | 0.191329  | 0.191329  | 0.187700  | 0.189458  |
| 2017-09-27 04:00:00 | 0.196000  | 0.196000  | 0.188336  | 0.191329  |
| 2017-09-27 08:00:00 | 0.207500  | 0.211200  | 0.194900  | 0.196000  |
| 2017-09-27 12:00:00 | 0.210000  | 0.215600  | 0.204200  | 0.207374  |
| 2017-09-27 16:00:00 | 0.213951  | 0.214318  | 0.207575  | 0.210560  |
| 2017-09-27 20:00:00 | 0.210080  | 0.213950  | 0.208500  | 0.213950  |
| 2017-09-28 00:00:00 | 0.204230  | 0.210875  | 0.204230  | 0.210010  |
| 2017-09-28 04:00:00 | 0.201309  | 0.210017  | 0.201100  | 0.204230  |
| 2017-09-28 08:00:00 | 0.200795  | 0.206510  | 0.196500  | 0.201210  |
