	      <div class="mdui-dialog" id="talk">
    <div class="mdui-dialog-title">评论区(需注册github)</div>
    <div class="mdui-dialog-content">
<section id="comments">
  <div id="gitalk_thread">
  </div>
  
  <script>
    const gitalk = new Gitalk({
      clientID: 'c52e147a004d3f9213dc',
      clientSecret: 'a9248fd7b142f970517d311c1a300b0028e3e4d3',
      repo: 'blogtalk',
      owner: 'Acc-36',
      admin: ['Acc-36'],
    })
    gitalk.render('gitalk_thread')
  </script>

	</div>
	
    <div class="mdui-dialog-actions">
      <button class="mdui-btn mdui-ripple" mdui-dialog-close>关闭</button>
    </div>
	</div>
