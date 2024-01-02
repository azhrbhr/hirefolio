<template>
    <div class="bg-white shadow-lg rounded-lg p-8 max-w-2xl mx-auto">
        <!-- Header - Photo and Basic Info -->
        <div class="flex items-center mb-6">
            <!-- Avatar Placeholder (dummy link) -->
            <img src="https://i.pravatar.cc/150?img=32" alt="Profile" class="w-20 h-20 rounded-full mr-6">

            <!-- Basic Info -->
            <div>
                <h1 class="text-2xl font-bold mb-2">John Doe</h1>
                <p class="text-gray-600 text-sm">Web Developer</p>
                <div class="flex mt-2 justify-center items-center">
                    <!-- Email Icon and Address -->
                    <div class="flex items-center mr-4">
                        <!-- Replace 'email-icon.png' with your actual PNG icon path for email -->
                        <img src="@/assets/envelope-solid.svg" alt="Email" class="h-5 w-5 text-gray-600 mr-1">
                        <a href="mailto:john.doe@example.com"
                            class="text-gray-600 hover:text-gray-900">john.doe@example.com</a>
                    </div>
                    <!-- Phone Icon and Number -->
                    <div class="flex items-center">
                        <!-- Replace 'phone-icon.png' with your actual PNG icon path for phone -->
                        <img src="@/assets/phone-solid.svg" alt="Phone" class="h-5 w-5 text-gray-600 mr-1">
                        <a href="tel:+1234567890" class="text-gray-600 hover:text-gray-900">+1 234 567 890</a>
                    </div>
                </div>
                <!-- Objective Section -->

                <!-- Social Links -->
                <div class="flex mt-2">
                    <!-- GitHub Icon Link -->
                    <a href="https://github.com/johndoe" target="_blank" rel="noopener noreferrer"
                        class="text-gray-600 hover:text-gray-900 mr-4">
                        <!-- Replace 'github-icon.png' with your actual downloaded GitHub PNG icon path -->
                        <img src="@/assets/github.svg" alt="GitHub" class="h-6 w-6 inline-block" />
                    </a>
                    <!-- LinkedIn Icon Link -->
                    <a href="https://www.linkedin.com/in/johndoe" target="_blank" rel="noopener noreferrer"
                        class="text-gray-600 hover:text-gray-900 mr-4">
                        <!-- Replace 'linkedin-icon.png' with your actual downloaded LinkedIn PNG icon path -->
                        <img src="@/assets/linkedin.svg" alt="LinkedIn" class="h-6 w-6 inline-block" />
                    </a>
                    <!-- Personal Website Icon Link -->
                    <!-- <a href="https://www.johndoe.com" target="_blank" rel="noopener noreferrer"
                        class="text-gray-600 hover:text-gray-900">
                        <img src="website-icon.pn" alt="Personal Website" class="h-6 w-6 inline-block" />
                    </a> -->
                    <!-- Add more social links/icons as needed -->
                </div>
            </div>
        </div>

        <!-- Objective Section -->
        <div class="mb-4">
            <p class="text-sm text-gray-600">
                Results-driven web developer with a passion for creating efficient and user-friendly applications.
                Seeking opportunities to leverage technical skills and innovative thinking in a challenging role.
            </p>
        </div>

        <!-- Experience Section -->
        <div>
            <h2 class="text-lg font-semibold mb-4">Experience</h2>
            <!-- Experience Item - Repeat for each experience -->
            <div class="mb-4">
                <h3 class="text-md font-semibold">Senior Web Developer</h3>
                <p class="text-sm text-gray-600">ABC Company - Jan 2018 to Present</p>
                <ul class="list-disc list-inside mt-2 text-sm text-gray-600">
                    <li>Developed responsive web applications using Vue.js and Tailwind CSS.</li>
                    <li>Collaborated with cross-functional teams to achieve project goals.</li>
                    <!-- Add more points as needed -->
                </ul>
            </div>
            <!-- Add more experience sections as needed -->
        </div>

        <!-- Education Section -->
        <div class="mt-6">
            <h2 class="text-lg font-semibold mb-4">Education</h2>
            <!-- Education Item - Repeat for each education -->
            <div class="mb-4">
                <h3 class="text-md font-semibold">Bachelor's Degree in Computer Science</h3>
                <p class="text-sm text-gray-600">XYZ University - Graduated in 2017</p>
                <!-- Add more details like GPA, honors, etc. -->
            </div>
            <!-- Add more education sections as needed -->
        </div>

        <!-- Skills Section -->
        <div class="mt-6">
            <h2 class="text-lg font-semibold mb-4">Skills</h2>
            <ul class="flex flex-wrap gap-2">
                <!-- Skills Chips - Repeat for each skill -->
                <li class="bg-gray-200 py-1 px-3 rounded-full text-sm">JavaScript</li>
                <li class="bg-gray-200 py-1 px-3 rounded-full text-sm">Vue.js</li>
                <li class="bg-gray-200 py-1 px-3 rounded-full text-sm">HTML</li>
                <li class="bg-gray-200 py-1 px-3 rounded-full text-sm">CSS</li>
                <!-- Add more skills as needed -->
            </ul>
        </div>


        <!-- Projects Section -->
        <div class="mt-6">
            <h2 class="text-lg font-semibold mb-4">Projects</h2>
            <!-- Project Item - Repeat for each project -->
            <div class="mb-4">
                <h3 class="text-md font-semibold">Project Name</h3>
                <p class="text-sm text-gray-600">Description of the project goes here.</p>
                <!-- Add more project details, links, etc. -->
            </div>
            <!-- Add more project sections as needed -->
        </div>

        <!-- Personal Section -->
        <div class="mt-6">
            <h2 class="text-lg font-semibold mb-4">Personal</h2>
            <p class="text-sm text-gray-600">
                A brief personal statement or summary can go here.
                Mention hobbies, interests, volunteering experiences, etc.
            </p>
        </div>
    </div>
    <p class="text-center my-4">
        <a href="#" @click="printResume" class="text-blue-500 hover:underline">Print Resume</a>
    </p>
</template>
  
<script setup lang="ts">

// Function to handle printing
const printResume = () => {
    window.print(); // Trigger browser's print functionality
};

</script>