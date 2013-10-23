nodejsdublin.com
================
Website for the Node.js Dublin meetup group.   
[@nodejsdublin](https://twitter.com/nodejsdublin)

Powered by [calipso](http://calip.so/).

### Adding info for the next event

* Create an event page for the previous event
  * Content Management -> Content -> Create
  * Select type 'Event'
  * Edit any of the other content items with type 'Event' and copy the format for the Teaser and Content sections
  * On the Status tab, set status to Published
* Get speaker images
  * On speaker twitter profile, right-click the avatar -> 'Open image in new tab'. The image filename should end with `_bigger`.
  * Add speaker images to `/nodejsdublin/themes/downloaded/nodejsdublin/public/images/speakers`.
  * Push to Github.
  * SSH to site server and pull.
* [Log in to the site](http://www.nodejsdublin.com/user/login)
* Double-click the event info to edit ([direct link](http://www.nodejsdublin.com/content/edit/4fa12ab8ad6bb6a123000173))
* Update the event date, tito link and lineup (content should correspond with the template below)

```HTML
<div class="row alpha omega"> 

  <div style="text-align: center">

    <h1>Next Event</h1>

    <h2>6.30pm, Thursday 25th July<br>
      Engine Yard<br>
      Barrow St. Dublin 4
    </h2>

    <h3>
      <a href="https://tito.io/nodejsdublin-1/node-js-dublin-25th-july-2013" target="_blank" style="text-decoration: underline">Request Tickets</a>
    </h3>

  </div>

  <div class="lineup">

    <ul>

      <li style="min-width: 250px">
        <img src="/images/speakers/speakerimage.jpeg" alt="Speaker Name">
        <h3>Speaker Name</h3>
        <a href='http://twitter.com/speaker' target='_blank'>@speaker</a>
        <br><br />
        Info about the speaker / talk
      </li>

      <li style="min-width: 250px; border-style: dashed">
        <h3>Break: Pizza and Beer!</h3>
      </li>

    </ul>

  </div>

  <h3>Sponsors</h3>
  <a href="http://www.engineyard.com"><img src="/images/badge-engineyard-sponsored.png" alt="Engine Yard Sponsored"/></a>
  <a href="http://www.nearform.com"><img src="/images/nearform-logo.png" alt="Sponsored by nearForm"/></a>

</div>
```
