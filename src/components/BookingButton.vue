<template>
    <div class="booking-button">
        <h2>導覽資訊</h2>

        <button>立即預約導覽</button>
    </div>
</template>
<script>
export default {
    name: "BookingButton",
    data() {
        return {};
    },
    methods: {},
};
</script>
<style scoped>
h2 {
    font-size: 45px;
}

button {
    width: 415px;
    height: 85px;
    border-radius: 10px;
    border-color: #b9d2d1;
    padding: 16px 32px;
    color: #fff;
    background-color: #b9d2d1;
    font-size: 24px;
    font-weight: 700;
    line-height: 40px;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    cursor: pointer;
}
</style>
