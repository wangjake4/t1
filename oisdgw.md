代发 wailian999

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtibrvqcdm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtiafwjgur.html

[U64] PHP：目录遍历
来源：http://dali.iojbl.cn/Article/details/gtjxamdwnf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtfijgditt.html

[U65] PHP：会话
来源：http://dali.sysykeji.top/Article/details/gtfmrmyeqp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtveybuqkz.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtjzcnyevh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gtuearfvdr.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gtmqtsgssq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yanxiufei.cn/Article/details/gtzfhvycxo.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtdhjghhqa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xylfe.cn/Article/details/gtnxqbpfsh.html

[U69] PHP：PDO 预处理
来源：http://dali.ybcxt.top/Article/details/gtsjlyokhr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblndjiou.html

[U70] PHP：PDO 事务
来源：http://dali.hammf.cn/Article/details/gtjqgrdzgk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gthgazkily.html

[U71] PHP：抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtbktqnpcn.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtfgcuqkbw.html

[U72] PHP：写错误日志
来源：http://dali.shuidangran.top/Article/details/gtfwdhcdls.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gtimaroxms.html

[U73] PHP：读取 ini 配置
来源：http://dali.iojbl.cn/Article/details/gtfcpfhkdg.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gtsxhbslgu.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtsuyisasl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gtserjcaxs.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtougwkvdx.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gtjwhelqeh.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gtyzitkrtc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnxiangtu.top/Article/details/gtifsyyynh.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gtzyjjskav.html

composer require twig/twig
来源：http://dali.yj20258.top/Article/details/gtrndravht.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtsmkhprxl.html

composer require --dev phpunit/phpunit
来源：http://dali.shzxlz.cn/Article/details/gtoayukrvu.html

[U79] PHP：静态分析
来源：http://dali.meibo888.top/Article/details/gtgeyxwqyj.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gtnzbcfzdi.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gtgzipisyb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukshaeqp.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gtdtdpaisy.html

npm init -y;  npm i express
来源：http://dali.sxryk.cn/Article/details/gtvylcdbgb.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtgjgeyuit.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtofbrgkvf.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuanzhike.top/Article/details/gtqoygympv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtfkinjyhm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtuvzkmasc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sysykeji.top/Article/details/gtllhluyka.html

[U85] JS：可选链
来源：http://dali.guowangkeji.top/Article/details/gtcvpyjbch.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gtltvkizke.html

[U86] JS：空值合并
来源：http://dali.yuxming.cn/Article/details/gtvffiphww.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtdyexlihr.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gtvrnhxxjs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtmyjleyeq.html

[U88] JS：对象展开合并
来源：http://dali.iojbl.cn/Article/details/gtddcaihqu.html

{ ...a, ...b }
来源：http://dali.tianlin.xyz/Article/details/gtbtkhsjgy.html

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gtjmefqjht.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtemoqmfqn.html

[U90] JS：数字数组排序
来源：http://dali.andypj.xyz/Article/details/gtsqlutynr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtskomuchw.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gtvjyzdefk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtnwcggtpr.html

[U92] JS：深拷贝
来源：http://dali.yonumen.top/Article/details/gtckovijcm.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtikyagkae.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtqaurzgck.html

`共 ${n} 条`
来源：http://dali.tianlin.xyz/Article/details/gtwprqbebo.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtvlkdocpf.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtnyyiyhng.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gtpirdbkei.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtjnognwrp.html

[U96] JS：async/await 与异常
来源：http://dali.shangyingyoupin.top/Article/details/gtzbnrsysc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtijwbuqoo.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gtodalxmnn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtjgrrkrqq.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuivdebf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtkbukxfct.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gtatxlcuzm.html

el.addEventListener("click", e => {})
来源：http://dali.cheryme.top/Article/details/gtvactumad.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gtogknroru.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtpivijvpz.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gttpxpfvnh.html

el.classList.toggle("active")
来源：http://dali.cucudq.cn/Article/details/gtdezoriya.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gteddewkez.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gtnzbzjdlj.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtqqyngewi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gtpuymwnuk.html

[U104] JS：防抖
来源：http://dali.zhixingplan.top/Article/details/gtpztrrvjm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtxoiiltix.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gtnnjrpoeb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtasclfuzt.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtwlqzghtq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtidfgdgyy.html

[U107] JS：数字千分位
来源：http://dali.smart0.xyz/Article/details/gtieubwyej.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pycfn.com/Article/details/gtmqpcdpra.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gtklbwdoqc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gtscachshf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gttpewnubq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtswxqmldw.html

[U110] JS：数组分块
来源：http://dali.mhx1999.top/Article/details/gtbvwuzqve.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqafogoa.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtlxembdxy.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gtdcfaihet.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtdtcnezuw.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtlkqglxdl.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gtjqvkmkbh.html

s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtphklfkmf.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gtszhnscjt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtsctzvirc.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtkwxdlcyb.html

crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtyeekryya.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xziqi.cn/Article/details/gtzwbnbodh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gtjintrcrl.html

[U117] JS：单元测试
来源：http://dali.xziqi.cn/Article/details/gtfkzwtmwq.html

npm i -D vitest;  npx vitest
来源：http://dali.wangshuangyany.cn/Article/details/gtwfbwshpl.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gtshbbxqtb.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gtasnuxray.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gtdjqdcqgn.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gtfjpmmmjh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gtaporrhik.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gtqdfypquz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtftiaflui.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gttxntybag.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfivhxpsh.html

按语言统计（条）：
来源：http://dali.chenlongwang.top/Article/details/gtmdolxbeh.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gtgrysebwx.html

PHP ............ 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtglsbqlpm.html

JavaScript ..... 252
来源：http://dali.zhixingplan.top/Article/details/gtscfwkoav.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gthqmponmj.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtnxyzizwl.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gtnawxbtuv.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtzdirgpxi.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtasgrwozs.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gtlocvclyz.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gtasydezzd.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gteyblrgid.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtbtotzwpn.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtdqjugfyf.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gtzdfyuxlc.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtjlndbbti.html

Perl ........... 10
来源：http://dali.sweek.top/Article/details/gtjedrbbfm.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gttikkfoqx.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtwmobqkzt.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtvbspadee.html

按章节统计：
来源：http://dali.0kj1m.cn/Article/details/gtugqbbwel.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtcjvficuq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuofggro.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtutlotjtl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtihjuqfnv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gtqtmculob.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyabfseuz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtsyrlugpx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtdxddessk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtndcoddfk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskzshned.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtensiewey.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtoskwvdcl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtawwayagz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtcpucbiwb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtqfnbrkry.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtjxcnhoae.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gtmdgwotce.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gtdnrhzjcr.html

S C / C++ 专题                          60
来源：http://dali.cashguo.top/Article/details/gtcjthmcwy.html

T 其他语言补充                          60
来源：http://dali.0kj1m.cn/Article/details/gtbfikfbpd.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtyujwyomv.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtreguzvwt.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gtbpsdzggb.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucpxubah.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtvfdbvlkp.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtdjealxzs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gtpmgjvsnp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtjmejrbhv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tanke756.top/Article/details/gtsoyzromx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gtvhdhbvfg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gtgzixiytu.html

—— 文件结束 ——
来源：http://dali.daxiang520.top/Article/details/gtmsciuavf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxlpiqczp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yvedp.cn/Article/details/gtpfspwlps.html

Common Programming Examples Cheat Book
来源：http://dali.haohaochexian.top/Article/details/gtfapxvlhj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmsmfxeju.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gtuxgxqxrr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxinkj.top/Article/details/gtafjsyjtu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbnpcapx.html

SQL · Bash · C · C++
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvkomcde.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daxiang520.top/Article/details/gtlrgezloc.html

【使用说明】
来源：http://dali.ppjwa.cn/Article/details/gtdylvxtyf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gtidxrvgyq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.smart0.xyz/Article/details/gtenejwvho.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gtnufnbjdg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cheryme.top/Article/details/gtmvtomvvm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gtybxorgzl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ppjwa.cn/Article/details/gtvlsbfzgd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.c1oappe.top/Article/details/gtlyliyimr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.mhx1999.top/Article/details/gtpewcdyqv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gtxnepgass.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ivvv.top/Article/details/gtlkibxumh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ybcxt.top/Article/details/gtihlkscad.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhengqikj.top/Article/details/gthaeivfdu.html

【文件统计】
来源：http://dali.yonumen.top/Article/details/gtmmduprwe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gtvsgkmjwz.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtztdaszyg.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gtwimrlcwl.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtlqlbdkir.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtiuvxnezo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtdwjgpzfg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtxkawrxye.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtxbguufcz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtxbmcjzze.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtdjxmtxnf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtrbnyvshv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtyhqmdsiz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtlakducdi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.9152youxi.cn/Article/details/gtxlufvaga.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasbudwgs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtaktjemfm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtuspmczgi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gtxctqpqpp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yvedp.cn/Article/details/gtnzclpiua.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtpqutwefq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gttdwzljka.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtazggzdzh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daxiang520.top/Article/details/gtghppnbxy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtrcvipndr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtrqasrgyl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtchspsanw.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gtkszeypqh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtiedpcyha.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gtgqkmwsfu.html

Py:   print("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gtbyyrmgrm.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gtnpirepxn.html

JS:   console.log("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtuxqjcrjz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gtertobhgg.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gtuxfyeixp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtxbkueebi.html

Ruby: puts "Hello, World!"
来源：http://dali.hfpthk.cn/Article/details/gtcxbctwna.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gtwrkbimjx.html

[A02] 变量声明与赋值
来源：http://dali.zdqjudy.top/Article/details/gtglbendjv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guowangkeji.top/Article/details/gtelzesxbu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gtodpwspjd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtctiwbpwk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gtsofmimuo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gtggerkxgl.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuanzhike.top/Article/details/gtvlcyjhxn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gtggyeqmin.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtxuwnodoc.html

[A03] 常量定义
来源：http://dali.mhx1999.top/Article/details/gtuxzndwvu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhiwuduotai.top/Article/details/gtthyjhuyy.html

PHP:  const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gthhwtxbna.html

JS:   const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtjkazfkol.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtkmnwcoaq.html

Java: static final double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtnfknftfx.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtpkjrgpjn.html

Ruby: PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbardvcp.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtuzozikxh.html

[A04] 判断变量类型
来源：http://dali.zdqjudy.top/Article/details/gtktozaomw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gtqyrhcfji.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gteavsiple.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtvkptzucb.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtolgiryay.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gtnobmqlqv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.vqdsnc.cn/Article/details/gtyrxjgbys.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhengqikj.top/Article/details/gtoprrhwru.html

C#:   x.GetType().Name; x is int
来源：http://dali.iojbl.cn/Article/details/gtabqfjlpy.html

[A05] 整数除法与取模
来源：http://dali.xylfe.cn/Article/details/gtiaftsype.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gtcweqloce.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtsfksylro.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtoqlwvblh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtkcdduxcg.html

Java: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtrtyxcvmz.html

Go:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtpoxgckjk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtexqxbazg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtfntvqcpt.html

[A06] 字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtoyamlrri.html

Py:   int("42"); float("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtakomfxws.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.0kj1m.cn/Article/details/gtutsfzzvn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtanlxrssg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtxjicpajc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtdplkzrun.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yongpay.top/Article/details/gtagfwoing.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvdejrhq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fzhhl.top/Article/details/gtfmbqscju.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gtflsyipbn.html

Py:   str(42)
来源：http://dali.pycfn.com/Article/details/gtgyqkzavq.html

PHP:  (string) 42; strval(42)
来源：http://dali.ppjwa.cn/Article/details/gtbybbmegi.html

JS:   String(42); (42).toString()
来源：http://dali.316326.xyz/Article/details/gteclezsln.html

TS:   String(42)
来源：http://dali.ehwqpu.com/Article/details/gtezrcrrpc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtqcnljbqa.html

Go:   strconv.Itoa(42)
来源：http://dali.ybcxt.top/Article/details/gtawllzioz.html

Ruby: 42.to_s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcudzvjup.html

C#:   42.ToString()
来源：http://dali.nwbrower.top/Article/details/gttyhoqsyd.html

[A08] 取整与四舍五入
来源：http://dali.yj20258.top/Article/details/gtfxvrcxhh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtagtydtqz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gtweidskja.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtljhpnobw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shangyingyoupin.top/Article/details/gtxanerywu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtaqhgqkui.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrmltneb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gtshgnwrsm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtuoevejra.html

[A09] 绝对值与最大最小值
来源：http://dali.smart0.xyz/Article/details/gtguerdnim.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgicadfym.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtuoqtyzlm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gthesfrdre.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtqjltbyft.html


<!-- 参考信息 -->