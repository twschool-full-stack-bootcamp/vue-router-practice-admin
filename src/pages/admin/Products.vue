<template>
    <div>
        Products
1
        <ul>
            <li v-for="product in products" :key="product.id">
                <!-- the link can be clicked and redirect to detail page with parameter -->
                <a href="#">{{product.name}}</a>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'Products',
        components: {},
        data: function () {
            return {
                products: [
                    {id: 'xxx1', name: 'Soda', price: 2},
                    {id: 'xxx2', name: 'Cola', price: 2},
                    {id: 'xxx3', name: 'Pure Water', price: 1}
                ]
            }
        }
    }
</script>
