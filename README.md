## EN

# Portainer V2 Templates for Selfhosted Projects

This is a template focused on helping people spin up selfhosted services using Portainer.

url: `https://raw.githubusercontent.com/PARSTURK/portainer-template/master/Template/template-v2.json`

### Prerequisites

1. A server/NAS with docker installed
2. A Portainer setup.

*Want something we don't have? Make an issue and we'll work on adding it*

### Installing
1. Login to your portainer setup go to settings
2. Enable Use external templates
3. Add the url: `https://raw.githubusercontent.com/PARSTURK/portainer-template/master/Template/template-v2.json` then go to app templates and hit refresh at the top.

### Information
All templates are already configured to bind mount to various places on your drive. This branch works without the need for OMV. The following folders are all created in /portainer/
* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.


## App List
  - Adguard
  - Airsonic
  - Authelia
  - Bazarr
  - Beets
  - Vaultwarden
  - Booksonic
  - Cops
  - Calibre-web
  - Chevereto
  - Chowdown
  - Code-server
  - Codiad
  - Couchpotato
  - Daapd
  - Dashmachine
  - Davos
  - Deemix
  - Domoticz
  - Duckdns
  - Duplicati
  - Emby
  - EmbyStat
  - Filebrowser
  - Freshrss
  - Gazee
  - Guacamole
  - Grocy
  - Htpcmanager
  - Headphones
  - Heimdall
  - Homer
  - Huginn
  - Invoice_ninja
  - Jackett
  - Jellyfin
  - kodi-headless
  - Lazylibrarian
  - Letsencrypt / SWAG
  - Librespeed
  - Lidarr
  - Lychee
  - Mariadb
  - Mcmyadmin2
  - Medusa
  - Minetest
  - Minisatip
  - Mstream
  - Murmur
  - Musicbrainz
  - Muximux
  - Mylar
  - Nzbget
  - Nzbhydra2
  - Nextcloud
  - Nginx
  - Nginx-proxy-manager
  - Oscam
  - Ombi
  - Openvpn-as
  - Organizr-v2
  - Overseerr
  - Owncloud
  - Petio
  - Photoshow
  - Pihole
  - Piwigo
  - Plex
  - Plexrequests
  - Projectsend
  - Protonmail-bridge
  - Prowlarr
  - Pydio
  - Qbittorrent
  - Quassel-core
  - Radarr
  - Reactive-resume
  - Resilio-sync
  - Rutorrent
  - Sabnzbd
  - Shiori
  - Sickchill
  - Sickgear
  - Smokeping
  - Snibox
  - Sonarr
  - Syncthing
  - Tautulli
  - Thelounge
  - Tiddlywiki
  - Tt-rss
  - Transmission
  - Transmission-openvpn
  - Tvheadend
  - Ubooquity
  - Unifi-controller
  - Watchtower
  - Webgrabplus
  - Whoogle
  - Wikijs
  - Yacht
  - Youtubedl-material
  - Znc

## Contributing
If you wish to contribute make a pull request, create an issue, or email me.


## Acknowledgments
* LinuxServer.io for the old Template
* The team behind Portainer for there awesome product and support in the community

### Original Portainer Template
If you don't like my template, I'm leaving the address here so you can revert to the original Portainer template.

url: `https://raw.githubusercontent.com/portainer/templates/master/templates-2.0.json`

---
## TR

# Kendi Kendine Barýndýrýlan Projeler için Portainer V2 Þablonlarý

Bu, insanlarýn Portainer kullanarak kendi kendine barýndýrýlan hizmetleri baþlatmasýna yardýmcý olmaya odaklanan bir þablondur.

url: `https://raw.githubusercontent.com/PARSTURK/portainer-template/master/Template/template-v2.json`

### Önkoþullar

1. Docker'ýn kurulu olduðu bir sunucu/NAS
2. Bir Portainer kurulumu.

*Bizde olmayan bir þey mi istiyorsunuz? Bir sorun oluþturun ve eklemeye çalýþalým*

### Yükleme
1. Portainer kurulumunuza giriþ yapýn, ayarlara gidin
2. Harici þablonlarý kullan'ý etkinleþtirin
3. URL'yi ekleyin: `https://raw.githubusercontent.com/PARSTURK/porttainer-template/master/Template/template-v2.json`, ardýndan uygulama þablonlarýna gidin ve en üstteki yenile düðmesine basýn.

### Bilgi
Tüm þablonlar, sürücünüzdeki çeþitli yerlere baðlayacak þekilde yapýlandýrýlmýþtýr. Bu dal OMV'ye ihtiyaç duymadan çalýþýr. Aþaðýdaki klasörlerin tümü /portiner/ içinde oluþturulur.

* **Files** - Genel dosya depolama.
  * **AppData** - Uygulama verilerinin (sunulan verilerle ilgisi olmayan) depolandýðý alt klasör.
    * **Config** - Her kapsayýcý için yapýlandýrma dosyalarýnýn depolandýðý alt klasör.
* **Downloads** - Bittorrent ve usenet indiricilerinin dosyalarý indirdiði yer.
* **TV** - TV þovlarýnýn indirildikten sonra depolandýðý/taþýndýðý yer.
* **Movies** - Filmlerin indirildikten sonra depolandýðý/taþýndýðý yer.
* **Music** - Müziðin indirildikten sonra depolandýðý/taþýndýðý yer.
* **Books** - Kitaplarýn indirildikten sonra depolandýðý/taþýndýðý yer.
* **Comics** - Çizgi romanlarýn indirildikten sonra depolandýðý/taþýndýðý yer.
* **Podcasts** - Podcast'lerin indirildikten sonra depolandýðý/taþýndýðý yer.


## Uygulama Listesi
  - Adguard
  - Airsonic
  - Authelia
  - Bazarr
  - Beets
  - Vaultwarden
  - Booksonic
  - Cops
  - Calibre-web
  - Chevereto
  - Chowdown
  - Code-server
  - Codiad
  - Couchpotato
  - Daapd
  - Dashmachine
  - Davos
  - Deemix
  - Domoticz
  - Duckdns
  - Duplicati
  - Emby
  - EmbyStat
  - Filebrowser
  - Freshrss
  - Gazee
  - Guacamole
  - Grocy
  - Htpcmanager
  - Headphones
  - Heimdall
  - Homer
  - Huginn
  - Invoice_ninja
  - Jackett
  - Jellyfin
  - kodi-headless
  - Lazylibrarian
  - Letsencrypt / SWAG
  - Librespeed
  - Lidarr
  - Lychee
  - Mariadb
  - Mcmyadmin2
  - Medusa
  - Minetest
  - Minisatip
  - Mstream
  - Murmur
  - Musicbrainz
  - Muximux
  - Mylar
  - Nzbget
  - Nzbhydra2
  - Nextcloud
  - Nginx
  - Nginx-proxy-manager
  - Oscam
  - Ombi
  - Openvpn-as
  - Organizr-v2
  - Overseerr
  - Owncloud
  - Petio
  - Photoshow
  - Pihole
  - Piwigo
  - Plex
  - Plexrequests
  - Projectsend
  - Protonmail-bridge
  - Prowlarr
  - Pydio
  - Qbittorrent
  - Quassel-core
  - Radarr
  - Reactive-resume
  - Resilio-sync
  - Rutorrent
  - Sabnzbd
  - Shiori
  - Sickchill
  - Sickgear
  - Smokeping
  - Snibox
  - Sonarr
  - Syncthing
  - Tautulli
  - Thelounge
  - Tiddlywiki
  - Tt-rss
  - Transmission
  - Transmission-openvpn
  - Tvheadend
  - Ubooquity
  - Unifi-controller
  - Watchtower
  - Webgrabplus
  - Whoogle
  - Wikijs
  - Yacht
  - Youtubedl-material
  - Znc

## Katký
Katkýda bulunmak istiyorsanýz, bir talepte bulunun, bir sorun oluþturun veya bana e-posta gönderin.

## Teþekkür
* Eski Þablon için LinuxServer.io
* Toplulukta harika ürün ve destek için Portainer'ýn arkasýndaki ekip

### Orjinal Portainer Þablonu
Þablonumu beðenmediyseniz, orijinal Portainer þablonuna dönebilmeniz için adresi buraya býrakýyorum.

url: `https://raw.githubusercontent.com/portainer/templates/master/templates-2.0.json`