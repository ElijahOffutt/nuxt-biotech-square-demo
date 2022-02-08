<template>
    <v-row>
        <v-col>
            <h2>AI-Powered Regulatory Intelligence</h2>
            <p>Regulatory Foresight is a web-based platform for biopharmaceutical teams to find evidence-backed answers to their most challenging questions. Using artificial intelligence, millions of pages documenting the development and approval of approved drugs and biologics can be searched and analyzed efficiently.</p>
            <p>The technology is helping drug development teams conduct deep searches of the regulatory body of knowledge, identify unique regulatory precedents, properly prepare for regulatory interactions and submissions, and optimize their development strategies.</p>
        </v-col>
        <v-col v-for="(col, i) in columns" :key="i">
            <v-row>
                <v-col>
                    <v-img />
                </v-col>
            </v-row>
            <h5></h5>
            <p></p>
            <v-row>
                <v-col>
                    <v-btn>Learn More ></v-btn>
                </v-col>
            </v-row>
        </v-col>
    </v-row>
</template>