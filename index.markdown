---
layout: page
title: Welcome to The Odd Foundation
---

The Odd Foundation is a unique and innovative organization that supports small and unconventional projects that might not receive funding from traditional sources. The foundation focuses on projects that are intriguing, creative, and unique, with a budget of under $1000. By providing financial support for these projects, the Odd Foundation aims to encourage and nurture the exploration of new ideas and innovative approaches. Whether it's an art installation, a community event, or a social experiment, the Odd Foundation is committed to funding projects that challenge the status quo and expand our understanding of the world around us. With a mission to empower and support the next generation of unconventional thinkers, the Odd Foundation is a valuable resource for anyone looking to bring their unusual and creative ideas to life.

### Random Hack
<ul>
<div id="hack-title"></div>
</ul>
<ul>
<i><div id="hack-desc"></div></i>
</ul>

## Resources

Check out our resources page for more information about The Odd Foundation.

<script>
const hh = {{ site.data.happinesshacks| jsonify }};
const randomIndex = Math.floor(Math.random() * hh.length);
document.getElementById("hack-title").innerHTML = hh[randomIndex].title;
document.getElementById("hack-desc").innerHTML = hh[randomIndex].description;
</script>
