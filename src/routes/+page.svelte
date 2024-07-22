<script>
async function(key ,url) {
const params = {method : "POST", body : JSON.stringify({key:key,url:url})};
const baseURL = "https://xn--s7y.xn--tckwe/api/short"
return await fetch(params,baseURL);
}
</script>


