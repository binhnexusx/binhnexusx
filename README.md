type Bio = {
  name: string;
  age: number;
  hometown: string;
  currentRole: string;
  goals: string[];
  skills: string[];
  hobbies: string[];
  funFact?: string;
};

const myBio: Bio = {
  name: "Hoàng Thanh Bình",
  age: 20, 
  hometown: "Quang Tri, Vietnam",
  currentRole: "Second-year Web Development student at PNV",
  goals: [
    "Become a professional Web Developer in a reputable company",
    "Improve English and soft skills",
    "Join internships and work on real-world projects"
  ],
  skills: [
    "HTML", "CSS", "JavaScript", "Laravel", "React.js", "Node.js", "Java", "MySQL"
  ],
  hobbies: [
    "Playing football (goalkeeper )", 
    "Watching the sunrise ", 
    "Listening to music in the shower", 
    "Playing with cats and dogs"
  ],
  funFact: "I really enjoy front-end development but I'm also exploring back-end to become a full-stack developer!"
};
