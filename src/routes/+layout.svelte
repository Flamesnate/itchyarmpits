<div class="backround">
    <div class="layout">
            <slot />
    </div>
</div>

<style>
    .backround {
        position: absolute;
        inset: 0;
    
        background-color:  #abacc2;
    }

    .layout {
        width: 100%;
        max-width: 900px;
        margin: 0 auto;
    }
</style>