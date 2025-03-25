<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>I2P - Invisible Internet Project</title>
</head>
<body>

  <h3>I2P - Invisible Internet Project</h3>

  <p>I2P, or the Invisible Internet Project, is a network layer that
   enables anonymous and censorship-resistant peer-to-peer communication.
   Its primary purpose is to safeguard user privacy by concealing the
   identity and location of those using the network.</p>

  <h3>Table</h3>

  <h3>I2P Info Table</h3>

  <table border="1">
  <tr>
    <th>Category</th>
    <th>Description</th>
    <th>Examples</th>
  </tr>
  <tr>
    <td>Core Implementations</td>
    <td>Software that implements the I2P protocol, providing the foundation for the network</td>
    <td>
      <ul>
        <li><strong>I2P (Java-based)</strong>: Original implementation, widely used and well-established. Introduced in 2003, it supports garlic routing, anonymous websites (Eepsites), messaging, and file sharing.</li>
        <li><strong>i2pd (C++-based)</strong>: Lightweight and efficient implementation, introduced in 2014. Optimized for low-resource environments like IoT devices and routers.</li>
        <li><strong>I2P+</strong>: Enhanced Java implementation introduced in 2019, with improved speed, reliability, and resource management.</li>
        <li><strong>Kovri</strong>: Forked from i2pd in 2015, optimized for anonymous cryptocurrency transactions, particularly for Monero.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>I2P Network</td>
    <td>Characteristics and features of the I2P network</td>
    <td>
      <ul>
        <li>Decentralized and distributed architecture</li>
        <li>Anonymous and end-to-end encrypted communication</li>
        <li>Floodfill mode for increased network participation</li>
        <li>Resilient to censorship and surveillance</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Network Components</td>
    <td>Infrastructure that makes up the I2P network, enabling anonymous and secure communication</td>
    <td>
      <ul>
        <li><strong>Routers</strong>: Nodes that forward traffic within the I2P network.</li>
        <li><strong>Tunnels</strong>: Encrypted pathways for data transmission.</li>
        <li><strong>Destinations</strong>: Cryptographic identifiers for services and users.</li>
        <li><strong>Address Book</strong>: Maps human-readable names to cryptographic destinations.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>I2P vs Tor</td>
    <td>Comparison between I2P and Tor, two anonymous networking technologies</td>
    <td>
      <ul>
        <li>I2P is designed for hidden services and peer-to-peer (P2P) applications.</li>
        <li>Tor is designed for anonymous proxying of regular Internet traffic.</li>
        <li>I2P is decentralized and distributed, while Tor relies on a centralized directory system.</li>
        <li>I2P uses garlic routing, while Tor uses onion routing.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>I2P Protocols</td>
    <td>Protocols used by I2P for communication and data transfer</td>
    <td>
      <ul>
        <li><strong>SAM (Session Establishment and Management)</strong>: Allows applications to interact with I2P.</li>
        <li><strong>I2CP (I2P Control Protocol)</strong>: Used for communication between I2P routers and clients.</li>
        <li><strong>BOB (Basic Open Bridge)</strong>: Provides a simple API for connecting to I2P.</li>
        <li><strong>I2NP (I2P Network Protocol)</strong>: Handles the core routing and encryption of I2P traffic.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Services and Features</td>
    <td>Functionalities provided by the I2P network, including anonymous hosting, encrypted communication, and more</td>
    <td>
      <ul>
        <li>Anonymous hosting of websites (Eepsites)</li>
        <li>Encrypted communication (email, messaging, IRC)</li>
        <li>Resilient and decentralized architecture</li>
        <li>QR Code Generator for sharing I2P addresses</li>
        <li>I2P Hidden Services Manager for hosting anonymous services</li>
        <li>File sharing and torrenting (e.g., I2PSnark, BiglyBT with I2P)</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Anonymous Communication</td>
    <td>Tools and services for anonymous communication, including websites, IRC chats, and instant messaging</td>
    <td>
      <ul>
        <li><strong>Anonymous websites</strong>: Hosted on Eepsites, accessible via I2P.</li>
        <li><strong>Anonymous IRC chats</strong>: Irc2P for secure IRC communication.</li>
        <li><strong>Decentralized instant messaging</strong>: MaladaN-Messenger-Client for secure messaging using the Signal protocol.</li>
        <li><strong>Email</strong>: I2P-Bote for secure, serverless email communication.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Anonymous Filesharing</td>
    <td>Software and tools for anonymous filesharing, including BitTorrent clients and other filesharing platforms</td>
    <td>
      <ul>
        <li><strong>I2PSnark</strong>: Standalone torrent client for I2P.</li>
        <li><strong>BiglyBT with I2P</strong>: Integrated torrent client with I2P support.</li>
        <li><strong>Transmission-I2P</strong>: Anonymous BitTorrent client based on Transmission.</li>
        <li><strong>iMule</strong>: Anonymous file-sharing client based on eMule.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Plugins and Applications</td>
    <td>Software that runs on top of the I2P network, providing various functionalities</td>
    <td>
      <ul>
        <li><strong>I2PSnark</strong>: Torrent client for anonymous file sharing.</li>
        <li><strong>SusiMail</strong>: Secure email client for I2P.</li>
        <li><strong>BiglyBT</strong>: BitTorrent client with I2P integration.</li>
        <li><strong>OpenSSH</strong>: Secure shell access over I2P.</li>
        <li><strong>I2P-Browser</strong>: Browser bundle for accessing I2P services.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Developer Tools</td>
    <td>APIs and tools for developers to create new applications and services on the I2P network</td>
    <td>
      <ul>
        <li><strong>SAM API Bridge</strong>: Allows applications to interact with I2P.</li>
        <li><strong>I2CP API</strong>: Control protocol for I2P routers and clients.</li>
        <li><strong>BOB API Bridge</strong>: Simple API for connecting to I2P.</li>
        <li><strong>py-i2phosts</strong>: Python tool for managing I2P host files.</li>
      </ul>
    </td>
  </tr>
  </table>

  <h3>I2P References</h3>

  <ul>
    <li><a href="https://geti2p.net">https://geti2p.net</a></li>
    <li><a href="https://geti2p.net/en/docs/how/threat-model">https://geti2p.net/en/docs/how/threat-model</a></li>
    <li><a href="https://wiki.debian.org/I2P">https://wiki.debian.org/I2P</a></li>
    <li><a href="https://i2pd.readthedocs.io/en/latest/">https://i2pd.readthedocs.io/en/latest/</a></li>
    <li><a href="https://www.whonix.org/wiki/I2P">https://www.whonix.org/wiki/I2P</a></li>
    <li><a href="https://www.reddit.com/r/i2p">https://www.reddit.com/r/i2p</a></li>
    <li><a href="https://eyedeekay.github.io">https://eyedeekay.github.io</a></li>
  </ul>

  <h3>Interesting Deployment of I2P</h3>

  <ul>
    <li><a href="https://github.com/KabaOS/KabaOS">KabaOS</a> - A Security-Focused Live OS for I2P.</li>
    <li><a href="https://github.com/DoingFedTime/Prestium">Prestium</a> - An linux os that natively runs I2P in live mode.</li>
    <li><a href="https://github.com/Plowsker/tails-i2pd">I2P on Tails</a> - I2P on Tails script v0.1 .</li>
    <li><a href="https://github.com/AmyMoriyama/i2p-browser-maker-linux">I2P Browser Maker Bash Script</a> - Makes it easy to get a preconfigured browser for I2P while on Linux.</li>
  </ul>

  <h3>I2P Links of Interest</h3>

  <h5>Exploring I2P - "Eepsites" (I2P services)</h5>

  <ul>
      <li><a href="http://stats.i2p" target="_blank" rel="noopener noreferrer">I2P Network Statistics</a></li>
      <li><a href="http://identiguy.i2p" target="_blank" rel="noopener noreferrer">Identiguy</a></li>
      <li><a href="http://reg.i2p" target="_blank" rel="noopener noreferrer">I2P Router Registration</a></li>
      <li><a href="http://reg.i2p/alive" target="_blank" rel="noopener noreferrer">I2P Router Alive Check</a></li>
      <li><a href="http://notbob.i2p" target="_blank" rel="noopener noreferrer">NotBob's Site</a></li>
      <li><a href="http://notbob.i2p/cgi-bin/defcon.cgi?category=stats" target="_blank" rel="noopener noreferrer">NotBob's Stats</a></li>
      <li><a href="http://stormycloud.i2p" target="_blank" rel="noopener noreferrer">StormyCloud</a></li>
      <li><a href="http://bote.i2p" target="_blank" rel="noopener noreferrer">I2P-Bote</a></li>
      <li><a href="http://inr.i2p" target="_blank" rel="noopener noreferrer">INR</a></li>
      <li><a href="http://planet.i2p" target="_blank" rel="noopener noreferrer">Planet I2P</a></li>
      <li><a href="http://natter.i2p" target="_blank" rel="noopener noreferrer">Natter</a></li>
  </ul>

  <h5>I2P Search Engines</h5>
  <ul>
      <li><a href="http://duck.i2p" target="_blank" rel="noopener noreferrer">DuckDuckGo (I2P)</a></li>
      <li><a href="http://search.i2p" target="_blank" rel="noopener noreferrer">I2P Search</a></li>
      <li><a href="http://legwork.i2p">Legwork search engine</a></li>
      <li><a href="http://i2pyacy.bandura.i2p">Bandura search engine</a></li>
  </ul>

  <h5>I2P Email Services</h5>
  <ul>
      <li><a href="http://bote.i2p" target="_blank" rel="noopener noreferrer">I2P-Bote</a></li>
      <li><a href="http://postman.i2p" target="_blank" rel="noopener noreferrer">Postman's I2P Email</a></li>
  </ul>

  <h5>File Sharing Services</h5>
  <ul>
      <li><a href="https://geti2p.net/en/docs/applications/i2psnark" target="_blank" rel="noopener noreferrer">I2PSnark</a></li>
      <li><a href="http://fs.i2p">FS</a> Filesharing service</li>
      <li><a href="http://cake.i2p">Cake Pastebin</a> short term filesharing and pastebin</li>
      <li><a href="http://paste.r4sas.i2p/">PrivateBin</a> Encrypted pastebin</li>
      <li><a href="https://paste.idk.i2p">IDK's CowYo pastebin</a>, <a href="https://glue.idk.i2p">Mirror</a>(Requires JS)</li>
  </ul>

  <h5>Chat and Messaging Apps</h5>
  <ul>
      <li><a href="https://geti2p.net/en/docs/applications/i2pchat" target="_blank" rel="noopener noreferrer">I2PChat</a></li>
      <li><a href="irc://127.0.0.1/6668/#i2p-chat">Irc2P</a> (works out of the box)</li>
    </ul>

  <h5>Social Networks</h5>
  <ul>
      <li><a href="http://mu.i2p" target="_blank" rel="noopener noreferrer">Murobbs</a></li>
      <li><a href="http://teddit.i2p">Teddit</a> - Privacy respecting Reddit front end</li>
      <li><a href="http://ramble.i2p">Ramble</a> - Multi-Network reddit alternative</li>
  </ul>

  <h5>Torrents</h5>
  <ul>
      <li><a href="https://rebuildingalexandria.wordpress.com/2012/02/21/secure-and-anonymous-file-sharing-using-torrents-on-the-i2p-network-library-nu-exiles-take-a-look/">Tutorial on eepsites and I2P torrenting</a></li>
      <li><a href="http://tracker2.postman.i2p">PaTracker</a> Main torrent tracker</li>
      <li><a href="http://torrents.chudo.i2p">Chudo's Torrents</a> (French) torrent tracker</li>
  </ul>

  <h5>Syndie</h5>
  <ul>
      <li><a href="http://syndie-project.i2p">Syndie Project</a> Syndie Project Website</li>
      <li><a href="http://fomjl7cori4juycw55kdlczpgzzhme6nox6zykokuiov6t5lxhvq.b32.i2p">Syndie Documentation Project</a></li>
      <li><a href="http://syndie.darrob.i2p">syndie.darrob.i2p</a></li>
      <li><a href="http://syndie.echelon.i2p">syndie.echelon.i2p</a></li>
      <li><a href="http://syndie.inscrutable.i2p">syndie.inscrutable.i2p</a></li>
      <li><a href="http://syndie.killyourtv.i2p">syndie.killyourtv.i2p</a></li>
      <li><a href="http://syndie.meeh.i2p">syndie.meeh.i2p</a></li>
      <li><a href="http://syndie.welterde.i2p">syndie.welterde.i2p</a></li>
  </ul>

  <h5>Inproxies</h5>
  <ul>
      <li><a href="http://i2phides.me">i2phides.me</a> / <a href="http://i2p.mk16.de">i2p.mk16.de</a> (<a href="http://i2p-inproxy.mk16.de">i2p-inproxy.mk16.de</a>)</li>
      <li><a href="http://onion.ly">onion.ly</a></li>
      <li><a href="http://www.darknetproxy.com">www.darknetproxy.com</a></li>
  </ul>

  <h5>I2P Name Registries</h5>
  <ul>
      <li><a href="http://inr.i2p">inr.i2p</a></li>
      <li><a href="http://reg.i2p">reg.i2p</a> operated by PurpleI2P Team</li>
      <li><a href="http://dns.chudo.i2p">dns.chudo.i2p</a></li>
      <li><a href="http://isitup.i2p">isitup.i2p</a> Another I2P Name Registry and checking tools to see if a eepsite is offline.</li>
  </ul>

  <h5>Media</h5>
  <ul>
      <li><a href="http://tube.i2p">Incogtube</a> - Youtube front end</li>
  </ul>

  <h4>Case Studies and Use Cases</h4>
  <ul>
      <li><a href="https://geti2p.net/en/docs/applications" target="_blank" rel="noopener noreferrer">Real-world Applications</a></li>
  </ul>

</body>
</html>