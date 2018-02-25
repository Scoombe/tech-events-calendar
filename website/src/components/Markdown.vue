 <script>
 import MarkdownIt from 'markdown-it'
 const md = MarkdownIt()
 export default {
     markdown (markdown) {
        return md.render(markdown);         
     } 
 }
 </script>
 