<template>
    <div class="card">
        <div class="card-body">
            <slot></slot>
        </div>
    </div>
</template>

<script>
export default function withCard(ChildComponent){
    return {
        name: 'withCard',
        functional: true,
        render(hoc, context) {
            return hoc('div', { class: 'card' }, [
                hoc('div', { class: 'card-body' }, [
                    hoc(ChildComponent, context.data, context.children)
                ])
            ])
        }
    }
}


</script>