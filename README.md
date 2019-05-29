use this css who give below and remove alt tag

////////////////////////////////////////////////////////////////////////////////:)
img[alt]:after {  
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom:0;
  width: 100%;
  height: 100%;
  background-color: #fff;
  font-family: 'Helvetica';
  font-weight: 300;
  line-height: 2;  
  text-align: center;
  content: attr(alt);
  text-indent: -9999px;
}
