# sublime-config

## install Package Control

use ctrl+`

```
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```


## sublime web plugin

	+ Emmet use key  ctrl + alt + enter

	+ DocBlockr 

	+ Alignment  代码对齐（Ctrl + Alt + A）

	+ BracketHighlighter（该插件提供行数列高亮的各种配对的语法符号。（注：就是将配对的括号等显示在行数列上））

	+ Sublime Prefixr（Prefixr，CSS3 私有前缀自动补全插件，显然也很有用哇。）

	+ JS Format（一个JS代码格式化插件。）

	+ SublimeLinter（一个支持lint语法的插件，可以高亮linter认为有错误的代码行，也支持高亮一些特别的注释，比如“TODO”，这样就可以被快速定位。（IntelliJ IDEA的TODO功能很赞，这个插件虽然比不上，但是也够用了吧））

	+ JsMinifier（该插件基于Google Closure compiler，自动压缩js文件。）

	+ jQuery（Sublime Text3支持jQuery。）

	+ CSSComb（这是用来给CSS属性进行排序的格式化插件。如果你想保持的代码干净整洁，并且希望按一定的顺序排列（是不是有点强迫症了？），那么这个插件是一种有效解决的方案。特别是当你和其他有自己代码编写风格的开发者一同协作的时候。）

	+ MarkDown Editing（SublimeText不仅仅是能够查看和编辑 Markdown 文件，但它会视它们为格式很糟糕的纯文本。这个插件通过适当的颜色高亮和其它功能来更好地完成这些任务）


	+ Git

	+ FileDiffs（查找文档不同。）

	+ ColorPicker（如果你经常要查看或设置颜色值，这个插件可以很方便地调用你本机的调色板应用。这是一个双向的功能，你既可以在调色板中选择一个颜色，然后按“确定”按钮把该值填写到 SublimeText 中活动文档的当前位置，也可以在活动文档中选择一个颜色的值，按此插件的快捷键就会在显示的调色板中定位到该值所对应的颜色。）

	+ CanIUse（如果您想检查浏览器是否支持你包括在你的代码中的CSS和HTML元素，那么这是你需要的插件。所有您需要做的就是选择有疑问的元素，插件将为你做其余的事情。）

	+ ConvertToUTF8

	+ AutoFileName：自动完成文件名的输入，如图片选取

	+ Sublime CodeIntel：代码自动提示

	+ SideBarEnhancements(SideBarEnhancements是一款很实用的右键菜单增强插件；在安装该插件前，在Sublime Text左侧FOLDERS栏中点击右键，只有寥寥几个简单的功能；安装了就相当于给其丰了大胸一般。)

	+ HTML-CSS-JS Prettify(一款集成了格式化（美化）html、css、js三种文件类型的插件，即便html,js写在PHP文件之内。插件依赖于nodejs，因此需要事先安装nodejs，然后才可以正常运行。插件安装完成后，快捷键ctrl+shift+H完成当前文件的美化操作。插件对html、css文件的美化不是非常满意，但还可以，后面将说明如何修改css美化脚本)

	+ SublimeREPL(这可能是对程序员很有用的插件。SublimeREPL 允许你在 Sublime Text 中运行各种语言（NodeJS ， Python，Ruby， Scala 和 Haskell 等等）。)

	+ Ctags(https://github.com/SublimeText/CTags)
	{
		"command": "D:/ctags/ctags.exe",
	}

	+ SublimeTmpl()

	+ Javascript-Completions(支持Javascript、JQuery、Twitter Bootstrap框架、HTML5标签属性提示的插件，是少数支持sublime text 3的后缀提示的插件，HTML5标签提示sublime text3自带，不过JQuery提示还是很有用处的，也可设置要提示的语言)

	+ WakaTime

	+ advancedNewFile(快速创建文件 当我们在 Sublime Text 编辑器里我们可以通过快捷键command+n(win: ctrl+n),来新建一个文件，然后command+s(Win:ctrl+s)进行弹出保存框，填写文件名进行保存。还是老问题，麻烦！！我们接下来就通过安装advancedNewFile插件来提升我们在Sublime Text编辑器下的创建文件速度。)

	+ GitGutter

	+ Soda theme

	+ TrailingSpaces(显示多余的空格)

	+ Compare Side-By-Side(两个文件的对比)

	+ weappSnippet(微信小程序插件)![详情](https://github.com/Abbotton/weapp-snippet-for-sublime-text-2-3)

	+ A File Icon