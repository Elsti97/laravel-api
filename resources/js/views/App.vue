<template>
    <div>

        <div>
            <WorkInProgress />
        </div>
        <div>
            <PostsList />
        </div>
    </div>
</template>

<script>

import WorkInProgress from "../components/WorkInProgress.vue"
import PostsList from "../components/posts/PostsList.vue"

export default {
    name: "App",
    components: {
        WorkInProgress,
        PostsList
    },
    data(){
        return{

        }
    },
    methods: {

    }
}
</script>
