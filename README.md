# fbpageremove



**Fb pages remove
**Note: Just a simple thing with console to wipe all my fb pages I liked and followed. Might be not working (with your browsers || with your accounts || in the future || ...)





**Open fb on web

**1. Go to Your profile
**2. Open 'Activity log'(in the [...])
**3. Select 'Connections' => 'Pages, page likes and interests'
**4. Open your console & run this:

async function delay(time) {
  return new Promise(resolve => setTimeout(resolve, time));
}

var doc = document.getElementsByClassName('qi72231t n3hqoq4p r86q59rh b3qcqh3k fq87ekyn fsf7x5fv s5oniofx m8h3af8h l7ghb35v kjdc1dyq kmwttqpk cr00lzj9 rn8ck1ys s3jn8y49 f14ij5to l3ldwz01 icdlwmnq i85zmo3j qmqpeqxj e7u6y3za qwcclf47 nmlomj2f frfouenu bonavkto djs4p424 r7bn319e bdao358l alzwoclg jcxyg2ei srn514ro oxkhqvkx rl78xhln nch0832m om3e55n1 jvc6uz2b g90fjkqk nu7423ey')

var i = doc.length - 1
console.log(i)
while(i > 0){
	doc[i].click()
	await delay(500).then(() => console.log(i + ' clicked'));
	var docs = document.getElementsByClassName('qi72231t nu7423ey n3hqoq4p r86q59rh b3qcqh3k fq87ekyn s5oniofx rn8ck1ys s3jn8y49 o9erhkwx dzqi5evh hupbnkgi hvb2xoa8 f14ij5to l3ldwz01 icdlwmnq qgrdou9d bdao358l fsf7x5fv alzwoclg jl2a5g8c jez8cy9q sb3qexpo l7miuv0d m8h3af8h kjdc1dyq om3e55n1 cr00lzj9 g4tp4svg i85zmo3j q46jt4gp b0eko5f3 r5g9zsuq fwlpnqze');
	docs[0].click()
    i--
	await delay(1500).then(() => console.log(i + ' done'));
}
