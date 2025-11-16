# SANAD
Sanad is a revolutionary health-tech app designed to help people at risk of seizures stay safe. Using data from your smartwatch, Sanad monitors your heartbeat and detects signs of an upcoming seizure before it happens.
import React from "react";
import {
  Hero,
  HowItWorks,
  Features,
  ForFamilies,
  About,
  Contact,
  Footer,
} from "./sections";

function App() {
  return (
    <div className="font-sans bg-white text-slate-800">
      <Hero />
      <HowItWorks />
      <Features />
      <ForFamilies />
      <About />
      <Contact />
      <Footer />
    </div>
  );
}

export default App;
