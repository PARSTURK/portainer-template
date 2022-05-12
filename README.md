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

## Planned Apps
- [ ] Wekan (https://wekan.github.io/)
- [ ] Mattermost (https://mattermost.com/)
- [ ] Dokuwiki (https://www.dokuwiki.org/)
- [ ] Grafana (https://grafana.com/)
- [ ] Grav (https://getgrav.org/)
- [ ] Yourls (https://yourls.org/)
- [ ] Standard Notes (https://standardnotes.com/)
- [ ] Docusaurus (https://docusaurus.io/)
- [ ] Are We Down (https://github.com/shukriadams/arewedown)
- [ ] PingMe (https://pingme.lmno.pk/)
- [ ] KeeWeb (https://keeweb.info/)
- [ ] Bitwarden (https://bitwarden.com/)
- [ ] Focalboard (https://www.focalboard.com/)
- [ ] Change Detection (https://github.com/dgtlmoon/changedetection.io)

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

## Original Portainer Template
If you don't like my template, I'm leaving the address here so you can revert to the original Portainer template.

url: `https://raw.githubusercontent.com/portainer/templates/master/templates-2.0.json`

---
## TR

# Kendi Kendine Barındırılan Projeler için Portainer V2 Şablonları

Bu, insanların Portainer kullanarak kendi kendine barındırılan hizmetleri başlatmasına yardımcı olmaya odaklanan bir şablondur.

url: `https://raw.githubusercontent.com/PARSTURK/portainer-template/master/Template/template-v2.json`

### Önkoşullar

1. Docker'ın kurulu olduğu bir sunucu/NAS
2. Bir Portainer kurulumu.

*Bizde olmayan bir şey mi istiyorsunuz? Bir sorun oluşturun ve eklemeye çalışalım*

### Yükleme
1. Portainer kurulumunuza giriş yapın, ayarlara gidin
2. Harici şablonları kullan'ı etkinleştirin
3. URL'yi ekleyin: `https://raw.githubusercontent.com/PARSTURK/porttainer-template/master/Template/template-v2.json`, ardından uygulama şablonlarına gidin ve en üstteki yenile düğmesine basın.

### Bilgi
Tüm şablonlar, sürücünüzdeki çeşitli yerlere bağlayacak şekilde yapılandırılmıştır. Bu dal OMV'ye ihtiyaç duymadan çalışır. Aşağıdaki klasörlerin tümü /portiner/ içinde oluşturulur.

* **Files** - Genel dosya depolama.
  * **AppData** - Uygulama verilerinin (sunulan verilerle ilgisi olmayan) depolandığı alt klasör.
    * **Config** - Her kapsayıcı için yapılandırma dosyalarının depolandığı alt klasör.
* **Downloads** - Bittorrent ve usenet indiricilerinin dosyaları indirdiği yer.
* **TV** - TV şovlarının indirildikten sonra depolandığı/taşındığı yer.
* **Movies** - Filmlerin indirildikten sonra depolandığı/taşındığı yer.
* **Music** - Müziğin indirildikten sonra depolandığı/taşındığı yer.
* **Books** - Kitapların indirildikten sonra depolandığı/taşındığı yer.
* **Comics** - Çizgi romanların indirildikten sonra depolandığı/taşındığı yer.
* **Podcasts** - Podcast'lerin indirildikten sonra depolandığı/taşındığı yer.

## Planlanan Uygulamalar
- [ ] Wekan (https://wekan.github.io/)
- [ ] Mattermost (https://mattermost.com/)
- [ ] Dokuwiki (https://www.dokuwiki.org/)
- [ ] Grafana (https://grafana.com/)
- [ ] Grav (https://getgrav.org/)
- [ ] Yourls (https://yourls.org/)
- [ ] Standard Notes (https://standardnotes.com/)
- [ ] Docusaurus (https://docusaurus.io/)
- [ ] Are We Down (https://github.com/shukriadams/arewedown)
- [ ] PingMe (https://pingme.lmno.pk/)
- [ ] KeeWeb (https://keeweb.info/)
- [ ] Bitwarden (https://bitwarden.com/)
- [ ] Focalboard (https://www.focalboard.com/)
- [ ] Change Detection (https://github.com/dgtlmoon/changedetection.io)

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

## Katkı
Katkıda bulunmak istiyorsanız, bir talepte bulunun, bir sorun oluşturun veya bana e-posta gönderin.

## Teşekkür
* Eski Şablon için LinuxServer.io
* Toplulukta harika ürün ve destek için Portainer'ın arkasındaki ekip

## Orjinal Portainer Şablonu
Şablonumu beğenmediyseniz, orijinal Portainer şablonuna dönebilmeniz için adresi buraya bırakıyorum.

url: `https://raw.githubusercontent.com/portainer/templates/master/templates-2.0.json`