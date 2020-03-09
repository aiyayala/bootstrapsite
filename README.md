 # Memo 
.className:after{
  content: '';
  position: absolute;
  width: 0; height: 3px;
  display: block;
  margin-top: 5px;
  right: 0;
  background: #fff;
  transition: width .2s ease;
  -webkit-transition: width .2s ease;
}
 
a:hover:after{
  width: 100%;
  left: 0;
  background: #fff;
}

