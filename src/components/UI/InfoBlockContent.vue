<template>
    <div class="info-block__content-main">
        <div v-if="!courses" class="info-block__left-column">
            <p class="info-block__time-text">
                {{ time }}
            </p>

        </div>

        <div v-if="!courses" class="info-block__right-column">
            <h4 class="info-block__h4">
                {{ workList.workName }}
            </h4>
            <p class="info-block__job-title">{{ workList.jobTitle }}</p>

            <h5 class="info-block__job-responsibilities-title">
                {{ workList.responsibilitiesTitle }}
            </h5>

            <ul class="info-block__job-responsibilities">
                <li class="info-block__job-responsibilities-item" v-for="responsibility in jobResponsibilities"
                    :key="responsibility">
                    <img class="info-block__list-img" src="../../img/dot.svg" alt="list">
                    {{ responsibility }}
                </li>
            </ul>

            <div v-if="workList.achievements">
                <h5 class="info-block__job-responsibilities-title">
                    {{ workList.achievements.achievementsTitle }}
                </h5>

                <ul class="info-block__job-responsibilities">
                    <li class="info-block__job-responsibilities-item"
                        v-for="achievement in workList.achievements.achievementsText" :key="achievement">
                        <img class="info-block__list-img" src="../../img/dot.svg" alt="list">
                        {{ achievement }}
                    </li>
                </ul>
            </div>
        </div>

        <div v-if="courses">
            <div class="info-block__content-main" v-for="course in courses" :key="course.id">
                <div class="info-block__left-column">
                    <p class="info-block__time-text">
                        {{ course.time }}
                    </p>

                </div>
                <div class="info-block__right-column">
                    <h5 class="info-block__job-responsibilities-title">
                        {{ course.courseName }}
                    </h5>

                    <p class="info-block__course-text">
                        {{ course.cousrseText }}
                    </p>
                </div>

            </div>

        </div>



    </div>
</template>
  
<script>


export default {
    name: 'InfoBlockContent',
    props: [
        'time',
        'workList',
        'jobResponsibilities',
        'courses'
    ]
}
</script>