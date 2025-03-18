import React from "react";
import Slider from "react-slick";
import "slick-carousel/slick/slick.css";
import "slick-carousel/slick/slick-theme.css";

const Home = () => (
  <div className="h-screen flex items-center justify-center bg-gradient-to-r from-blue-500 to-indigo-500 text-white text-4xl font-bold">
    Welcome to My Website
  </div>
);

const AboutMe = () => (
  <div className="h-screen flex items-center justify-center bg-gradient-to-r from-green-500 to-teal-500 text-white text-4xl font-bold">
    About Me
  </div>
);

const ContactUs = () => (
  <div className="h-screen flex items-center justify-center bg-gradient-to-r from-red-500 to-pink-500 text-white text-4xl font-bold">
    Contact Us
  </div>
);

const App = () => {
  const settings = {
    dots: true,
    infinite: true,
    speed: 500,
    slidesToShow: 1,
    slidesToScroll: 1,
    autoplay: true,
    autoplaySpeed: 3000,
  };

  return (
    <Slider {...settings}>
      <Home />
      <AboutMe />
      <ContactUs />
    </Slider>
  );
};

export default App;
