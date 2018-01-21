# phpfacebookfeed

## Usage
- Change the page id to the facebook page you wish to fetch.
- Change the access token to your developer api access token. *(from registering as a developer on facebook)*
- Edit the limit to the number of posts you wish to display.

If you want to allow your page to fully load before fetching the feed (I found this worked better) then you can create an element with an id:

```
<div id="fb-page">

</div>
```


Then use javascript to load the php file:

```
<script>
	$(document).ready(function(){
		$("#fb-page").load('fbfeed.php');
	});
</script>
```
