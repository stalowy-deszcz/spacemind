# spacemind

something {
position: relative;
}

something::after {
  content: "";
  position: absolute;
  top: 0; 
  left: 0;
  bottom: 0;
  right: 0;
  opacity: .4; 
  z-index: -1;
  background: url();
}

(background transparency) 
i can make a div before it with background-color: rgba (x,x,x,0.4); + div::after
and then it makes a color filter. :D 
