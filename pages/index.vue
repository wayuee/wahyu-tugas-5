<template>
  <Data
    :data-daniel="dataDaniel"
    :data-jonathan="dataJonathan"
    :data-kira="dataKira"
    :data-jeanette="dataJeanette"
    :data-patrick="dataPatrick"
  />
</template>

<script>
import Data from "~/components/DataFromIndex";
export default {
  components: {
    Data,
  },
  data() {
    return {
      dataDaniel: {
        name: "Daniel Clifford",
        img: "/image-daniel.jpg",
        graduate: "Verified Graduate",
        bio: "I received a job offer mid-course, and the subjects  I learned were current, if not more so, in the company I joined. I honestly feel I got every pennys worth",
        text: "“ I was an EMT for many years before I joined the bootcamp. Ive been looking to make a transition and have heard some people who had an amazing experience here. I signed up for the free intro course and found it incredibly fun! I enrolled shortly thereafter.  The next 12 weeks was the best - and most grueling - time of my life. Since completing the course, Ive successfully switched careers, working as a Software Engineer at a VR startup. ”",
      },
      dataJonathan: {
        name: "Jonathan Walters",
        img: "/image-jonathan.jpg",
        graduate: "Verified Graduate",
        bio: "The team was very supportive and kept me motivated",
        text: "“ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer  for a big company. This was one of the best investments Ive made in myself. ”",
      },
      dataKira: {
        name: "Kira Whittle",
        img: "/image-kira.jpg",
        graduate: "Verified Graduate",
        bio: "Such a life-changing experience. Highly recommended!",
        text: "“ Before joining the bootcamp, Ive never written a line of code. I needed structure from professionals who can help me learn programming step by step. I was encouraged to enroll by a former student of theirs who can only say wonderful things about the program. The entire curriculum and staff did not disappoint. They were very hands-on and I never had to wait long for assistance. The agile team project, in particular, was outstanding. It took my learning to the next level in a way that no tutorial could ever have. In fact, Ive often referred to it during interviews as an example of my developent experience. It certainly helped me land a job as a full-stack developer after receiving multiple offers. 100% recommend!",
      },
      dataJeanette: {
        name: "Jeanette Harmon",
        img: "/image-jeanette.jpg",
        graduate: "Verified Graduate",
        bio: "An overall wonderful and rewarding experience",
        text: "“ Thank you for the wonderful experience! I now have a job I really enjoy, and make a good living while doing something I love. ”",
      },
      dataPatrick: {
        name: "Patrick Abrams",
        img: "/image-patrick.jpg",
        graduate: "Verified Graduate",
        bio: "Awesome teaching support from TAs who did the bootcamp themselves. Getting guidance from them and learning from their experiences was easy.",
        text: "“ The staff seem genuinely concerned about my progress which I find really refreshing. The program gave me the confidence necessary to be able to go out in the world and present myself as a capable junior developer. The standard is above the rest. You will get the personal attention you need from an incredible community of smart and amazing people. ”",
      },
    };
  },
};
</script>

<style></style>
