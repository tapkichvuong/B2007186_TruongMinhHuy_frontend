<script>
export default {
    props: {
        contact: {type: Object, required: true},
    },
}
</script>

<template>
    <div>
        <div class="p-1">
            <strong>Tên: </strong>
            {{contact.name}}
        </div>
        <div class="p-1">
            <strong>Email: </strong>
            {{contact.email}}
        </div>
        <div class="p-1">
            <strong>Địa chỉ: </strong>
            {{contact.address}}
        </div>
        <div class="p-1">
            <strong>Điện thoại: </strong>
            {{contact.phone}}
        </div>
        <div class="p-1">
            <strong>liên hệ yêu thích: &nbsp;</strong>
            <font-awesome-icon v-if="contact.favorite" icon="fa-solid fa-check" />
            <font-awesome-icon v-else icon="fa-solid fa-circle-xmark" />
        </div>
    </div>
</template>