# webtorrent_tui
Small TUI for downloading torrents with the webtorrent client.

![Example](https://i.imgur.com/9bH1t5F.gif)

## Usage
    torrent <query> [args]   : Makes a query
    torrent download <index> : Downloads a query index
    torrent deluge <index>   : Add the index to deluge's query
    torrent magnet <index>   : Prints the magnet of an index to the terminal
    torrent deleteTmp        : Deletes temporary files

    Arguments:
        --n    : Number of files to be shown
        --site : The site to be queried
        --page : The number of the page
