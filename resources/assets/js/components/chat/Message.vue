<template>
    <div class="chat__message">
        message
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss">
    .chat {
        &__message {
            padding: 15px;
            border-bottom: 1px solid #eee;

            &--own {
                background-color: #f0f0f0;
            }

            &-user {
                font-weight: 800;
            }

            &-timestamp {
                color: #aaa;
            }

            &-body {
                margin-bottom: 0;
                white-space: pre-wrap;
            }
        }
    }
</style>
