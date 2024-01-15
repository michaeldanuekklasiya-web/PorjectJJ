##CSS

.property-visi-misi {
  height: 794px;
  position: relative;
  width: 1616px;
}

.property-visi-misi .overlap {
  height: 96px;
  left: 0;
  position: absolute;
  top: 474px;
  width: 451px;
}

.property-visi-misi .rectangle {
  background-color: #eaf0ec;
  border-radius: 4px;
  height: 94px;
  left: 0;
  position: absolute;
  top: 1px;
  width: 451px;
}

.property-visi-misi .text-wrapper {
  color: #138c44;
  font-family: "Poppins-SemiBold", Helvetica;
  font-size: 24px;
  font-weight: 600;
  left: 54px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 29px;
}

.property-visi-misi .line {
  height: 96px;
  left: 1px;
  position: absolute;
  top: 0;
  width: 10px;
}

.property-visi-misi .div {
  color: #28292c;
  font-family: "Poppins-SemiBold", Helvetica;
  font-size: 48px;
  font-weight: 600;
  left: 596px;
  letter-spacing: 0;
  line-height: 42px;
  position: absolute;
  top: 27px;
  white-space: nowrap;
}

.property-visi-misi .group {
  height: 786px;
  left: 562px;
  position: absolute;
  top: 118px;
  width: 1060px;
}

.property-visi-misi .overlap-group {
  background-color: #ffffff;
  height: 786px;
  position: relative;
  width: 1054px;
}

.property-visi-misi .in-SAPA {
  color: #28292c;
  font-family: "Poppins-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  left: 117px;
  letter-spacing: 0;
  line-height: 40px;
  position: absolute;
  top: 46px;
  width: 887px;
}

.property-visi-misi .as-a-pioneer-in {
  color: #28292c;
  font-family: "Poppins-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  left: 117px;
  letter-spacing: 0;
  line-height: 40px;
  position: absolute;
  top: 272px;
  width: 887px;
}

.property-visi-misi .p {
  color: #28292c;
  font-family: "Poppins-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  left: 117px;
  letter-spacing: 0;
  line-height: 40px;
  position: absolute;
  top: 537px;
  width: 887px;
}

.property-visi-misi .iconamoon-check-fill {
  height: 42px;
  left: 51px;
  position: absolute;
  top: 45px;
  width: 42px;
}

.property-visi-misi .img {
  height: 42px;
  left: 51px;
  position: absolute;
  top: 270px;
  width: 42px;
}

.property-visi-misi .iconamoon-check-fill-2 {
  height: 42px;
  left: 51px;
  position: absolute;
  top: 536px;
  width: 42px;
}

.property-visi-misi .text-wrapper-2 {
  color: var(--dark);
  font-family: "Poppins-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  left: 54px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 271px;
}

.property-visi-misi .text-wrapper-3 {
  color: var(--dark);
  font-family: "Poppins-Regular", Helvetica;
  font-size: 24px;
  font-weight: 400;
  left: 54px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 387px;
}

.property-visi-misi .our-vision-mission {
  color: transparent;
  font-family: "Poppins-SemiBold", Helvetica;
  font-size: 64px;
  font-weight: 600;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: -1px;
  width: 508px;
}

.property-visi-misi .span {
  color: #28292c;
}

.property-visi-misi .text-wrapper-4 {
  color: #138c44;
}

.property-visi-misi .line-wrapper {
  background-image: url(./line-6.svg);
  background-size: 100% 100%;
  height: 1px;
  left: -14801px;
  position: absolute;
  top: 11554px;
  width: 86px;
}

.property-visi-misi .line-2 {
  height: 1px;
  left: 0;
  position: absolute;
  top: 0;
  width: 86px;
}

.property-visi-misi .line-3 {
  height: 1px;
  left: -14801px;
  position: absolute;
  top: 11669px;
  width: 86px;
}


##CODE
import React from "react";
import "./style.css";

export const PropertyVisiMisi = () => {
  return (
    <div className="property-visi-misi">
      <div className="overlap">
        <div className="rectangle" />
        <div className="text-wrapper">SAPA Vision 2034</div>
        <img className="line" alt="Line" src="line-8.svg" />
      </div>
      <div className="div">SAPA Indonesia Vision 2034</div>
      <div className="group">
        <div className="overlap-group">
          <p className="in-SAPA">
            In 2034, SAPA Indonesia envisions itself as the pinnacle of integrated <br />
            lifestyle solutions, seamlessly enriching the lives of individuals and families across the nation. Our
            commitment to innovation and customer-centricity will have led us to new heights, solidifying our
            application as the go-to platform for easy and fast lifestyle services
          </p>
          <p className="as-a-pioneer-in">
            As a pioneer in digital transformation, SAPA Indonesia envisions playing a <br />
            pivotal role in shaping the future of work, empowering a thriving community of service providers and
            connecting them with individuals seeking meaningful job opportunities. Our platform will not only be a
            facilitator of services but also a catalyst for positive socio-economic impact, fostering a sense of
            community and shared prosperity
          </p>
          <p className="p">
            In 2034, SAPA Indonesia will stand as a beacon of sustainability, <br />
            incorporating eco-friendly practices into our operations and services. Our commitment to corporate social
            responsibility will be ingrained in our DNA, contributing to the well-being of the environment and the
            communities we serve.
          </p>
          <img className="iconamoon-check-fill" alt="Iconamoon check fill" src="iconamoon-check-fill.svg" />
          <img className="img" alt="Iconamoon check fill" src="image.svg" />
          <img className="iconamoon-check-fill-2" alt="Iconamoon check fill" src="iconamoon-check-fill-2.svg" />
        </div>
      </div>
      <div className="text-wrapper-2">Vision</div>
      <div className="text-wrapper-3">Mission</div>
      <p className="our-vision-mission">
        <span className="span">Our</span>
        <span className="text-wrapper-4">
          {" "}
          Vision &amp;
          <br />
          Mission
        </span>
      </p>
      <div className="line-wrapper">
        <img className="line-2" alt="Line" src="line-9.svg" />
      </div>
      <img className="line-3" alt="Line" src="line-7.svg" />
    </div>
  );
};
