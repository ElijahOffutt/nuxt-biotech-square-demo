<template>
    <v-footer>
        <v-form>
            <h2>Request More Information</h2>
            <v-row>
                <v-col v-for="(input, i) in fields" :key="i">
                    <v-input v-model="input.value" :label="input.title" />
                </v-col>
            </v-row>
            <v-btn type="submit">submit</v-btn>
        </v-form>
    </v-footer>
</template>


<script>
export default {
    data(){return{
        fields: [
            {
                value: '',
                title: 'name',
            },
            {
                value: '',
                title: 'title/role',
            },
            {
                value: '',
                title: 'company name',
            },
            {
                value: '',
                title: 'email',
            },
        ]
    }}
}
</script>