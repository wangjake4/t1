代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtgxdlkjzd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspgmlpje.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gtfuacogtp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.kuanghao11.cn/Article/details/gtpoexbaob.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gtprvwynzr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtjektzbma.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gtjqrcuysy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sxryk.cn/Article/details/gtwgtqbxys.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gtfalamttj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.snrcjt.cn/Article/details/gtiajxqcph.html

[U68] PHP：PDO 连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwigouqg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.svipenyu.cn/Article/details/gtaogqcqsj.html

[U69] PHP：PDO 预处理
来源：http://dali.yanxiufei.cn/Article/details/gtcznveczy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gtizzjkrsw.html

[U70] PHP：PDO 事务
来源：http://dali.hammf.cn/Article/details/gtkvhdnyhh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gtrnqnxbfq.html

[U71] PHP：抛出异常
来源：http://dali.sysykeji.top/Article/details/gtrwefcrpi.html

throw new RuntimeException("失败", 500);
来源：http://dali.shzxlz.cn/Article/details/gtjapwvwpw.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbflsyqsc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtowphrste.html

[U73] PHP：读取 ini 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtmswhceko.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gteozzunoi.html

[U74] PHP：读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtvlaqyhlw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxuanxn.top/Article/details/gtequldtly.html

[U75] PHP：依赖注入
来源：http://dali.aibaodan.cn/Article/details/gtoqugmucs.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gtpqvfthyd.html

[U76] PHP：简单路由
来源：http://dali.sufxvd.cn/Article/details/gtvzmfsbjc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ydzc1.top/Article/details/gtnauiwhvq.html

[U77] PHP：模板渲染
来源：http://dali.zhengqikj.top/Article/details/gtqfbzxnhc.html

composer require twig/twig
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccehdlci.html

[U78] PHP：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtudncepoe.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gtuomrwupv.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gtqrbvmohn.html

composer require --dev phpstan/phpstan
来源：http://dali.yuanzhike.top/Article/details/gtseedjzca.html

[U80] PHP：代码规范修复
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmkbrltx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daria6918.cn/Article/details/gtwdmkymfo.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gtavmwubzo.html

npm init -y;  npm i express
来源：http://dali.tanke756.top/Article/details/gtrhnwuizv.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gtnukdvcns.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cqqwz.cn/Article/details/gtjnpbvoal.html

[U83] JS：ES Module 导入导出
来源：http://dali.xinyue.icu/Article/details/gttiyrpxom.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtzdtlaijm.html

[U84] JS：CommonJS 写法
来源：http://dali.zdqjudy.top/Article/details/gthnxpcgju.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gtlfgqtbyp.html

[U85] JS：可选链
来源：http://dali.hysaishi.cn/Article/details/gtejvjfyrk.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gtayytvxsx.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gtnxgiuoyd.html

a ?? b
来源：http://dali.tianlin.xyz/Article/details/gtqqvninms.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gtpmytoicz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhiwuduotai.top/Article/details/gtlbtcyjjb.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gtjmfcqkpk.html

{ ...a, ...b }
来源：http://dali.iojbl.cn/Article/details/gtrrapctre.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gtsprwxxiq.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtitdxrkdz.html

[U90] JS：数字数组排序
来源：http://dali.yangfankeji.com/Article/details/gtmgjbjicc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtvtrowbwh.html

[U91] JS：对象键值遍历
来源：http://dali.cucudq.cn/Article/details/gtrynjtxso.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gtuxliunlv.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtggxuumgc.html

structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxldospqg.html

[U93] JS：模板字符串
来源：http://dali.gzhubu.top/Article/details/gtqudhvjor.html

`共 ${n} 条`
来源：http://dali.jinqigufen.top/Article/details/gtuzxwhkbh.html

[U94] JS：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtkcyscmgx.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gtithqadoo.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtapbduzgl.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcifzwjd.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzygaybk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjctthjkw.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gtypazzthb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtybczlwxp.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtnrlfjkdp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shzxlz.cn/Article/details/gtbbkevpfj.html

[U99] JS：事件监听
来源：http://dali.shuidangran.top/Article/details/gtdddwxncq.html

el.addEventListener("click", e => {})
来源：http://dali.nwbrower.top/Article/details/gterbyekiw.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtvtupxjaw.html

document.querySelector(".item")
来源：http://dali.bjfxy.top/Article/details/gtpqlvjeyk.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtpanvcdll.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtvowmckal.html

[U102] JS：本地存储
来源：http://dali.jlsjyb.cn/Article/details/gttalopxwa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtnpssbobq.html

[U103] JS：定时器
来源：http://dali.hnxiangtu.top/Article/details/gtohwppmfv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shangyingyoupin.top/Article/details/gtrmzooelf.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gtzaanrhkg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffdonksa.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gttqwwfboh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gtygiwsoor.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gtzxoizhbd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gtlqghjjgb.html

[U107] JS：数字千分位
来源：http://dali.cheryme.top/Article/details/gtgrxcvgkj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtuwahntwk.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gtewteoyhm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jianghu66.top/Article/details/gtenahqdtj.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gtqljnjqvx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtdomiktxd.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gtfhdbdjvu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guannengcc.top/Article/details/gtrzpebvju.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gtflhfvzog.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gttdjybvib.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gtittdfmyn.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtxegzmhtn.html

[U113] JS：正则替换全部
来源：http://dali.shuidangran.top/Article/details/gtnfmizttf.html

s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtyemluazn.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtlpyuggfy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtefszmdxx.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gtknccehho.html

crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtnoscqwyc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgfzy.top/Article/details/gtlqyudowx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.smart0.xyz/Article/details/gtrsgqchml.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtwpybifxd.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufbjzuhl.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gtkkrorsad.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtuppxtnjf.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtnucxfhgt.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtazqchnvs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gtbzpwuieh.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gtlcofxsln.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbgaikcih.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtbegvslzv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkjrtcwur.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gtlnjzriye.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gtqnyeafzo.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gtvpgnasbu.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gtzvxptjhc.html

TypeScript ..... 212
来源：http://dali.iojbl.cn/Article/details/gtniqfvgeq.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwdksfpk.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtpntjhbdy.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtzofclfzs.html

C# ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtzllcmlfj.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gtgufmnwmo.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtmkycbmqj.html

SQL ............ 90
来源：http://dali.aizwys.cn/Article/details/gtlartkuab.html

Bash ........... 80
来源：http://dali.sweek.top/Article/details/gtdgmgmofk.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gthyqjhdki.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gtlmdbgmsh.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gtehnljvnx.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtgccgdckv.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtcgkbtqqq.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtwqrxelte.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gtidtienyf.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gtbymiehwb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gttrykcvin.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtbblgqcng.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtkjvexzvu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gtpoiiblrg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtqtdpwdly.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtelnpdvnp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gthbbqbifk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtgzlfopin.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtqucckdgx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gtnqddibwn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtsahdztfy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtnmkpkltp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtgwbfasjk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtuymqfymu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgfzy.top/Article/details/gtsmmhpxhq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtjiqwwkdj.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gtventpunb.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gtpkeherrf.html

S C / C++ 专题                          60
来源：http://dali.guowangkeji.top/Article/details/gtefliftmp.html

T 其他语言补充                          60
来源：http://dali.birdmap.top/Article/details/gtyyqysvtk.html

U 高频实用片段                         120
来源：http://dali.yuxming.cn/Article/details/gtlhdcuglp.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtjrtbssru.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gtkcjmhpsf.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiofozpv.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gttlwirykk.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtpefugehg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtctfdkrih.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.birdmap.top/Article/details/gtegrtvqbd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cdnleiting.top/Article/details/gtzyigyqxt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ydzc1.top/Article/details/gtirawnnzx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gotoacloud.top/Article/details/gtqwiwopby.html

—— 文件结束 ——
来源：http://dali.vqdsnc.cn/Article/details/gteayxjxky.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyvohtwrz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gtwjzlcmij.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gtsnnmeswq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzvhyjpmc.html

【收录内容】
来源：http://dali.cheryme.top/Article/details/gtakdvkerp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.haohaochexian.top/Article/details/gtzivfjclf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.birdmap.top/Article/details/gtrzbydprc.html

SQL · Bash · C · C++
来源：http://dali.redwolf501.top/Article/details/gtzyvcspro.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gtriqytodg.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtvbfioeem.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gtlsjshvtn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ydzc1.top/Article/details/gtabbkkocy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gtozxtqzhp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gtmkzjacqm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gtwaaynhoz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sxryk.cn/Article/details/gtkpffbcyj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gtnpbowtkw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.havefunace.top/Article/details/gthzqkscfu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sweek.top/Article/details/gtmdzwpfdy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhengqikj.top/Article/details/gtanikvhwx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gtknfalrev.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigufen.top/Article/details/gtjdqnydzm.html

【文件统计】
来源：http://dali.0kj1m.cn/Article/details/gtmdmiwpwn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hammf.cn/Article/details/gtpizilmre.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtizheudkk.html

目  录
来源：http://dali.bjfxy.top/Article/details/gtpbnipncv.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gttlkhfoub.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtunzoireo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gttmmotjip.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtjqiorwxl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtosviacev.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gtwaxmecrb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gthyshplkc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtfyiaqttf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gthbeiotls.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtxlefnhfb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtslyngwdo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gttavsjfjl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtwvbnrufx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtnebjzalo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gthuptussw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtghmrskuw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtpalatipk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.kuanghao11.cn/Article/details/gteucouryl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gtyblmydag.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gtsxcqncfr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtzhmzespl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gttxckakbx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyvyrutzc.html

A. 基础语法与类型
来源：http://dali.gzhubu.top/Article/details/gtniwoygon.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gteedhqeeo.html

[A01] Hello World
来源：http://dali.xinyue.icu/Article/details/gtolqaqodr.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtwnxqocbd.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsohgamki.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtnbsxgwjb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hammf.cn/Article/details/gtxahrkwdl.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtbnbuazfm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtqnizvogx.html

Ruby: puts "Hello, World!"
来源：http://dali.yanxiufei.cn/Article/details/gtnuhueutp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtzlpedaef.html

[A02] 变量声明与赋值
来源：http://dali.yangfankeji.com/Article/details/gttgmbsdkv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gthwqzbyon.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtqejlscny.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.c1oappe.top/Article/details/gtxcvtfydh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtchnpvagt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtovcowkfj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhengqikj.top/Article/details/gtxlnihlid.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gtpvrnkjpf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtbcknwggk.html

[A03] 常量定义
来源：http://dali.sweek.top/Article/details/gtfzuxdzda.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gtjyavitug.html

PHP:  const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtqbdjdett.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtogjiwbcs.html

TS:   const PI: number = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtqbrtmfdu.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtwezmuwcv.html

Go:   const PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gtejwsfbzl.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtilqfwdyc.html

C#:   const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtqhntaard.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gthhtrvwis.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtrijljsni.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmnmjnla.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtrzbrgdhc.html

TS:   typeof x; x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gtppjgamrm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hysaishi.cn/Article/details/gtqweotvuc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ydzc1.top/Article/details/gtasnfghaf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gtbrqeniox.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gtdsskpyht.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gtqzdzhbon.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gtogfouvou.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtlbjculqi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtvbxkemei.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtntsncywl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtjmcvqonl.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gthdbjicjy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtzwsfdqxa.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtfciqsorg.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtaspryiyr.html

Py:   int("42"); float("3.14")
来源：http://dali.hywenlv.cn/Article/details/gthxsuwkgl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sysykeji.top/Article/details/gtyywmctvb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtcxakxamr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gtnngxghki.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtqpdbkepx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xinyue.icu/Article/details/gtzqzeijog.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruswszma.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtkktuizus.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtbjobybcc.html

Py:   str(42)
来源：http://dali.gotoacloud.top/Article/details/gtousywefp.html

PHP:  (string) 42; strval(42)
来源：http://dali.yanxiufei.cn/Article/details/gtlioyvasv.html

JS:   String(42); (42).toString()
来源：http://dali.kuanghao11.cn/Article/details/gtmcwwtwgn.html

TS:   String(42)
来源：http://dali.aizwys.cn/Article/details/gtzcdrrcyy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.svipenyu.cn/Article/details/gtcujpopmu.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gtkehnwrgf.html

Ruby: 42.to_s
来源：http://dali.chenlongwang.top/Article/details/gttqdyropy.html

C#:   42.ToString()
来源：http://dali.chenlongwang.top/Article/details/gtfjxqxcsc.html

[A08] 取整与四舍五入
来源：http://dali.dianchejie.cn/Article/details/gtqitllrda.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtmrzvlftx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gtgubpdgvw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtoqmnbeuo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gaohongyu789.top/Article/details/gtbrttgyck.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtfugdskit.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtqhrcwpaa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jianghu66.top/Article/details/gtzznchplm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gttyrvngng.html

[A09] 绝对值与最大最小值
来源：http://dali.mhx1999.top/Article/details/gtnvigeqvq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtlpoblwoy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtcquolras.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmheocdkb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tanke756.top/Article/details/gtufyuijpw.html


<!-- 参考信息 -->