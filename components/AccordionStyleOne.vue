<template>
    <div class="accordion">
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-1 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                    How do I get this book?
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-1" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry has industry's standard dummy text ever since the 1500s, when an unknown printer took of type and scrambled it to make a type specimen book. It has survived not only centuries, but also the leap into electronic.
                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-2 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                    Do you have an E-Book Format?
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-2" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry has industry's standard dummy text ever since the 1500s, when an unknown printer took of type and scrambled it to make a type specimen book. It has survived not only centuries, but also the leap into electronic.
                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-3 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                    What can I learn from this book?
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-3" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry has industry's standard dummy text ever since the 1500s, when an unknown printer took of type and scrambled it to make a type specimen book. It has survived not only centuries, but also the leap into electronic.
                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
        <b-card no-body>
            <b-card-header header-tag="header">
                <b-button block v-b-toggle.accordion-4 class="accordion-button">
                    <span class="icon-box">
                        <i class="icon icofont-plus"></i>
                        <i class="icon icofont-minus"></i>
                    </span>
                    Do you ship internationally?
                </b-button>
            </b-card-header>
            <b-collapse id="accordion-4" visible accordion="my-accordion">
                <b-card-body>
                    <b-card-text>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry has industry's standard dummy text ever since the 1500s, when an unknown printer took of type and scrambled it to make a type specimen book. It has survived not only centuries, but also the leap into electronic.
                    </b-card-text>
                </b-card-body>
            </b-collapse>
        </b-card>
    </div>
</template>