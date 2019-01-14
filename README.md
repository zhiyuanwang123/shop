<script>
document.body.addEventListener('DOMSubtreeModified', function(event) {
    const elements = document.getElementsByClassName('header-top-contact');
    const element1 = document.getElementsByClassName('footer_content');
    const element2 = document.getElementsByClassName('footer_bottom');
    while (elements.length > 0 || element1.length > 0 || element2.length > 0){
element1[0].remove();
elements[0].remove();
element2[0].remove();
}
});
</script>
