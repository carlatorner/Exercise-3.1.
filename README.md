# Exercise-3.1.- Robotics Intergration

<h2> Información: </h2>
<p>Este repositorio forma parte del ejercicio 3.1. del MasterUVIC-Robotica para practicar el roslaunch. </p>

<h2> Archivos proporcionados: </h2>
<ol>
  <li> parameters.yaml: un archivo con un parametro:  <dl><dt>  year = 2017</dt> </dl> </li>
  <li> exercise_3_1.launch: un launch file donde se carga el parametro anterior, un rviz node y también se incluye el launch file <a href="http://wiki.ros.org/usb_cam">/usb_cam</a>
  </li>
  </ol>
  
<h4> Parametros launch file <a href="http://wiki.ros.org/usb_cam">/usb_cam</a>: </h4>
<ul>
  <li> video_device = /dev/video0  </li>
  <li> image_width = 640 </li>
  <li> image_height = 480 </li>
  <li> pixel_format = yuyv </li>
  <li> camera_frame_id = usb_cam </li>
  <li> io_method = mmap </li>
  </ul>
