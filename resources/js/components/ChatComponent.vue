<!--Contains two child components that is message and form-->
<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Chats</div>

                    <div class="card-body">
                       Chats 
                       <chat-messages-component></chat-messages-component> 
                       <chat-form-component></chat-form-component>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
