# JShare SDK ErrorCode 定义

以下列表里的 ErrorCode 有可能在 SDK 的调用过程中出现。供参考理解其含义。


<div class="table-d" align="center" >
	<table border="1" width = "100%">
		<tr  bgcolor="#D3D3D3" >
			<th >Code</th>
			<th>Error Message</th>
			<th>说明</th>
		</tr>

    <tr>
      <td>40001</td>
      <td>appid missing</td>
      <td>缺失 appid 参数</td>
    </tr>
    <tr>
      <td>40002</td>
      <td>appkey missing</td>
      <td>缺失 appkey 参数</td>
    </tr>
    <tr>
      <td>40003</td>
      <td>secret missing</td>
      <td>缺失 secret 参数</td>
    </tr>
    <tr>
      <td>40004</td>
      <td>mediaType missing</td>
      <td>缺失 mediaType 参数</td>
    </tr>
    
    <tr>
      <td>40005</td>
      <td>invalid mediaType</td>
      <td>不合法的 mediaType</td>
    </tr>
    <tr>
      <td>40006</td>
      <td>platform missing</td>
      <td>缺失 platform 参数</td>
    </tr>
    <tr>
      <td>40007</td>
      <td>invalid platform</td>
      <td>不合法的 platform</td>
    </tr>
    <tr>
      <td>40009</td>
      <td>not install app</td>
      <td>没安装客户端</td>
    </tr>
    <tr>
      <td>40010</td>
      <td>unfinished initialization</td>
      <td>未完成初始化</td>
    </tr>
    <tr>
      <td>40011</td>
      <td>shareParams missing</td>
      <td>缺少 shareParams</td>
    </tr>
    <tr>
      <td>40012</td>
      <td>platform haven't  configuration</td>
      <td>platform 没配置</td>
    </tr>
    <tr>
      <td>40013</td>
      <td>appname missing</td>
      <td>缺失 appname 参数</td>
    </tr>
    <tr>
      <td>41001</td>
      <td>text size out of limit</td>
      <td>文本参数长度超过限制</td>
    </tr>
    <tr>
      <td>41002</td>
      <td>image url size out of limit</td>
      <td>图片链接字段长度超过限制</td>
    </tr>
    <tr>
      <td>41003</td>
      <td>image size out of limit</td>
      <td>图片大小超过限制</td>
    </tr>
    <tr>
      <td>41004</td>
      <td>url size out of limit	</td>
      <td>url 长度超过限制</td>
    </tr>
    <tr>
      <td>41005</td>
      <td>audio url size out of limit</td>
      <td>音频 url 长度超过限制</td>
    </tr>
    <tr>
      <td>41006</td>
      <td>video url size out of limit</td>
      <td>视频 url 长度超过限制</td>
    </tr>
    <tr>
      <td>41009</td>
      <td>file size out of limit</td>
      <td>文件大小超过限制</td>
    </tr>
    <tr>
      <td>41010</td>
      <td>emotion size out of limit</td>
      <td>emotion 大小超过限制</td>
    </tr>
    <tr>
      <td>41011</td>
      <td>title size out of limit</td>
      <td>title 参数超过限制</td>
    </tr>
    <tr>
      <td>41012</td>
      <td>description size out of limit</td>
      <td>description 参数超过限制</td>
    </tr>
    <tr>
      <td>41013</td>
      <td>thumb size out of limit</td>
      <td>缩略图参数超过限制</td>
    </tr>
    <tr>
      <td>41014</td>
      <td>image is empty</td>
      <td>图片参数为空</td>
    </tr>
    <tr>
      <td>41015</td>
      <td>audio url is empty</td>
      <td>音频 url 参数为空</td>
    </tr>
    <tr>
      <td>41016</td>
      <td>video url is empty</td>
      <td>视频 url 参数为空</td>
    </tr>
    <tr>
      <td>41017</td>
      <td>video url is empty</td>
      <td>视频 path 参数为空</td>
    </tr>

    <tr>
      <td>41018</td>
      <td>emotion is empty</td>
      <td>emotion 参数为空</td>
    </tr>
    <tr>
      <td>41019</td>
      <td>file is empty</td>
      <td>文件参数为空</td>
    </tr>
    <tr>
      <td>41019</td>
      <td>image count out of limit</td>
      <td>图像计数超出限制</td>
    </tr>
    <tr>
      <td>41021</td>
      <td>url is empty</td>
      <td>url 参数为空</td>
    </tr>
        <tr>
      <td>41022</td>
      <td>text is empty	</td>
      <td>文本参数为空</td>
    </tr>

 	 <tr>
      <td>41023</td>
      <td>text and title is empty</td>
      <td>标题和文本都为空</td>
    </tr>

        <tr>
      <td>41025</td>
      <td>title is empty</td>
      <td>title 为空</td>
    </tr>
        <tr>
      <td>41026</td>
      <td>invalid url</td>
      <td>非法 url</td>
    </tr>
        <tr>
      <td>41027</td>
      <td>file not exist</td>
      <td>文件不存在</td>
    </tr>
    <tr>
      <td>41028</td>
      <td>text and url size out of limit</td>
      <td>文本和url长度超过限制</td>
    </tr>
    <tr>
      <td>41029</td>
      <td>can't share image and video together</td>
      <td>不能同时分享图片和视频</td>
    </tr>
    <tr>
      <td>41030</td>
      <td>Mini Program userName is Empty.</td>
      <td>userName 参数为空</td>
    </tr>
    <tr>
      <td>41031</td>
      <td>Mini Program Type Error.</td>
      <td>小程序类型错误</td>
    </tr>
    <tr>
      <td>41032</td>
      <td>thumb size out of limit or thumb is null.</td>
      <td>图片为空或超出限制</td>
    </tr>
    
    <tr>
      <td>42001</td>
      <td>invalid credential</td>
      <td>不合法的调用凭证</td>
    </tr>
        </tr>
        <tr>
      <td>50001</td>
      <td>get access token error</td>
      <td>获取access token 错误</td>
    </tr>
        </tr>
        <tr>
      <td>50002</td>
      <td>share failed</td>
      <td>分享失败</td>
    </tr>
        </tr>
        <tr>
      <td>50003</td>
      <td>get userinfo failed</td>
      <td>获取用户信息失败</td>
    </tr>
        </tr>
        <tr>
      <td>50004</td>
      <td>auth failed</td>
      <td>授权失败</td>
    </tr>
        </tr>
        <tr>
      <td>50005</td>
      <td>this platform unsupported authorize</td>
      <td>平台不支持授权</td>
    </tr>
    
    <tr>
      <td>50006</td>
      <td>Invalid or expired token</td>
      <td>无效或过期的token</td>
    </tr>
    
    <tr>
      <td>50007</td>
      <td>Unable to verify your credentials</td>
      <td>无法验证你的凭证</td>
    </tr>
    
    <tr>
      <td>50008</td>
      <td>Internal error</td>
      <td>发生未知的内部错误</td>
    </tr>
    
    <tr>
      <td>50009</td>
      <td>Status is a duplicate</td>
      <td>该状态的内容已经过验证的帐户发布</td>
    </tr>
    
</table>
</div>
