ubuntu18.04：

安装Sublime text3：

     
    wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
     
    echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
     
    sudo apt-get update
     
    sudo apt-get install sublime-text

安装Package Control插件：

安装成功后打开sublime text3，按ctrl + ~，在控制台中输入（一行一行输入）：

    import urllib.request, os;
     
    pf = 'Package Control.sublime-package';
     
    ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) );
     
    open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())

即可按成Package Control插件的安装。