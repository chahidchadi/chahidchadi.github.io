---
ident: 2-bio
layout: page
title:  CV
lang: en
---
## Full CV

<embed src="/cv/Curriculum vitæ.pdf" width="100%" height="600px" type="application/pdf">


<script>
    // URL of PDF document
    var url = '/cv/Curriculum vitæ.pdf';

    // Load the PDF document
    pdfjsLib.getDocument(url).promise.then(function(pdf) {
        // Get the first page
        pdf.getPage(1).then(function(page) {
            var scale = 1.5;
            var viewport = page.getViewport({scale: scale});

            // Get canvas element
            var canvas = document.getElementById('pdf-canvas');
            var context = canvas.getContext('2d');
            canvas.height = viewport.height;
            canvas.width = viewport.width;

            // Render PDF page into canvas context
            var renderContext = {
                canvasContext: context,
                viewport: viewport
            };
            page.render(renderContext);
        });
    });
</script>

