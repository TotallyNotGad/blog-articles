A public comment section, what could possibly go wrong?

---
HI, not an article, but i thought it would be cool to make a guestbook for people to post on.

Comments are currently moderated manually, so it might take some time for your comment to appear, and its not the most robust thing in the world.

But maybe ill upgrade it later, or just take it down, who knows.

Anyways, have fun!

# Comments

> **Gad:** <br>
> First! :P


<style>
    #commentForm input {
        width: 100%;
        margin: 0px;
        margin-bottom: 20px;
    }

    #commentForm button {
        width: 10%;
    }
</style>

<form id="commentForm">
    <input name="name" placeholder="Name:"/>
    <input name="comment" placeholder="Comment:"/>
    <button type="submit">Send</button>
</form>

  

<script>
    // yes this is a monstrosity, but comon, its free! and thats my maximum budget right now, free
    let commentForm = document.getElementById('commentForm')
    commentForm.addEventListener('submit', event => {
        event.preventDefault()
        let data = new FormData(commentForm)
        commentForm.reset()
        fetch(`https://docs.google.com/forms/d/e/1FAIpQLSd3hMuPkowtgGKXBPhy2yj38aH2mNCodqt5jQx8-pByGvu-8g/formResponse?&submit=?usp=pp_url&entry.83592019=${data.get('name')}&entry.389176920=${data.get('comment')}`, {method: "GET"})
    })
</script>
