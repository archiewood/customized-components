<script>
    import { LineChart } from "@evidence-dev/core-components";
</script>

 <!-- $$restProps passes all the props defined in the markdown to the LineChart component -->
<LineChart 
    {...$$restProps}
    title='Custom Title'
    labels=true
/>