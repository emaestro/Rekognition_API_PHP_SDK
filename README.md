Current Version: 1.0
=======================

The folder contains our PHP SDKs and simple examples to demo the SDK.

The SDK contains the following functions:

// ReKognition Face Detect Function

<pre><code>public function RkFaceDetect($req, $scale, $request_mode = Rekognition_API::REQUEST_UNDEFINED,
                            $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Add Function

<pre><code>public function RkFaceAdd($req, $name, $scale, $request_mode = Rekognition_API::REQUEST_UNDEFINED, 
                            $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Train Function

<pre><code>public function RkFaceTrain($return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Recognize Function

<pre><code>
public function RkFaceRecognize($req, $scale, $request_mode = Rekognition_API::REQUEST_UNDEFINED, $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Rename Function

<pre><code>
public function RkFaceRename($tag, $new_tag, $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Crawl Function

<pre><code>
public function RkFaceCrawl($access_token,$fb_id,$friend_id,$return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Visualize Function

<pre><code>
public function RkFaceVisualize($name_list, $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Search Function

<pre><code>
public function RkFaceSearch($req, $scale, $request_mode = Rekognition_API::REQUEST_UNDEFINED, $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Delete Function

<pre><code>
public function RkFaceDelete($name, $id_list, $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Face Stats Function

<pre><code>
public function RkFaceStats($return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

// ReKognition Scene Understadning Function

<pre><code>
public function RkSceneUnderstanding($req, $scale, $request_mode = Rekognition_API::REQUEST_UNDEFINED, $return_mode = Rekognition_API::RETURN_JSON);
</code></pre>

Configuration:
=======================
(a) Register an API Key from https://www.rekognition.com/register/, and you will receive API key and secret by email.

(b) Use your own API Key, Secret, Name space and User id in config.php

$rekognition_api_key = '1234';
$rekognition_api_secret = '5678';
$rekognition_name_space = '';
$rekognition_user_id = ''; 

The ReKo SDK example:
=======================
(a) Image Request Example: Require the server with example/dataset and get the result back;

(b) Recognize the image using the our face detection and scene understanding functions;

For any questions, please contact eng@orbe.us
