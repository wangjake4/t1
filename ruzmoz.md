代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.316326.xyz/Article/details/gtoximjnyf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvidblao.html

[U60] PHP：JSON 编解码
来源：http://dali.gotoacloud.top/Article/details/gtwadbltwj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtzwnvjvkn.html

[U61] PHP：正则
来源：http://dali.zhixingplan.top/Article/details/gtxiplqvyw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtciwybrpt.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtfvrybihz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gogol.net.cn/Article/details/gtmrwbiwpe.html

[U63] PHP：文件读写
来源：http://dali.jinqigfzy.top/Article/details/gtyesfrvaa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gaohongyu789.top/Article/details/gtrsygdwye.html

[U64] PHP：目录遍历
来源：http://dali.hnqzz.top/Article/details/gtennqxdew.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gtukggoprl.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtalcwqmqn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtxynxbsvf.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gtjmyotlvd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgfzy.top/Article/details/gtuumeupec.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gtpiuvcolz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gtmmixmcfc.html

[U68] PHP：PDO 连接
来源：http://dali.xziqi.cn/Article/details/gtbdguoepg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gzhubu.top/Article/details/gthfstjhrk.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gtkwjyxdjt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtsfmnytcf.html

[U70] PHP：PDO 事务
来源：http://dali.cdnleiting.top/Article/details/gtesknbhhx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gtinummwqu.html

[U71] PHP：抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtqcxnicgw.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gtsvoypnsb.html

[U72] PHP：写错误日志
来源：http://dali.sxryk.cn/Article/details/gtutnqjadn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtgnmtdyxo.html

[U73] PHP：读取 ini 配置
来源：http://dali.ybcxt.top/Article/details/gtpeolxfbw.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gtiwedwxyt.html

[U74] PHP：读取环境变量
来源：http://dali.316326.xyz/Article/details/gtpgjxrjas.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxuanxn.top/Article/details/gtzclvnfuf.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gthnisvqlf.html

composer require psr/container
来源：http://dali.bjfxy.top/Article/details/gtognmlwsb.html

[U76] PHP：简单路由
来源：http://dali.hysaishi.cn/Article/details/gthyhizugz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gthmeqyqse.html

[U77] PHP：模板渲染
来源：http://dali.fengsongda.top/Article/details/gtfpqdawmx.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtrjonbyjm.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtusshygji.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gtorknkwhs.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gtrkxzxzme.html

composer require --dev phpstan/phpstan
来源：http://dali.mhx1999.top/Article/details/gtrwvdqhds.html

[U80] PHP：代码规范修复
来源：http://dali.yuxming.cn/Article/details/gtpchtjqil.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gthjrwhkdp.html

[U81] JS：初始化项目
来源：http://dali.yvedp.cn/Article/details/gtclxcjyni.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gtwxfcikmh.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtbhiffnyy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gtyinndrfo.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gtolluuarf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtooprhqew.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gtxkbcnftq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivotgpgd.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtiaqfbtmt.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gtlavvmzml.html

[U86] JS：空值合并
来源：http://dali.smart0.xyz/Article/details/gtkfqnyehg.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtiflwtmkq.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gtzefkijar.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuanzhike.top/Article/details/gtdumvdaln.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvttpihz.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtyqlnquqr.html

[U89] JS：数组去重
来源：http://dali.jianghu66.top/Article/details/gtvcrhnqnu.html

[...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gttgfzixfy.html

[U90] JS：数字数组排序
来源：http://dali.yangfankeji.com/Article/details/gtruyogojh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtkmbvadfm.html

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gtsmpbkcuc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtbjlccabg.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gtbekffaus.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkxuabiwd.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gtbwrmdsxv.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gtmbeocafz.html

[U94] JS：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtonkoxiqz.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gtdomjrctn.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gtfuqcblvr.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtpxtzkdsf.html

[U96] JS：async/await 与异常
来源：http://dali.aizwys.cn/Article/details/gtknsdxfez.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtexkpxqyn.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gtririheyb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtherrharb.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtwoijxyss.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gtiopckutg.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gtbvlelyyg.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtyvrauykf.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gtuulvykar.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gttnbmoxgr.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtlnskdpcj.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gtudjrvrrz.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gtwfrpogca.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtsjckszps.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gtyfapcvyn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtxqshgcyb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gtungohyig.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtleocoixe.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtzslwzeym.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gtaszqtjyk.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gtdpdczuct.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.316326.xyz/Article/details/gtogapicdh.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtjjbwiiku.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gtdrvjexhy.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gtdoufquci.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cashguo.top/Article/details/gtqdyeudzs.html

[U109] JS：数组分组
来源：http://dali.daria6918.cn/Article/details/gtmczzmffw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtpjhdnbdo.html

[U110] JS：数组分块
来源：http://dali.jqgufenzy.top/Article/details/gtiswcvzhp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gttnbzzjst.html

[U111] JS：对象转 Map
来源：http://dali.daria6918.cn/Article/details/gtzrtikvem.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtfgwdpocs.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gtzjoljzlb.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gthxeimmbg.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtxzxpseue.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtkflarnxg.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gteyjktlnd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtaoailwbi.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtmeieekxd.html

crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtxaasjrev.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuanzhike.top/Article/details/gtgjefpmla.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtphdruzlb.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtxunolrgp.html

npm i -D vitest;  npx vitest
来源：http://dali.ehwqpu.com/Article/details/gtxhlmztot.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gtzjozeybo.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtlfshxwhr.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexafeoxa.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtqmypfped.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hysaishi.cn/Article/details/gtpevnilye.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxhdnbrt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvoscjjku.html

统计汇总
来源：http://dali.yuxming.cn/Article/details/gtpzelqhfd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwluptoqu.html

按语言统计（条）：
来源：http://dali.zhoulong.xyz/Article/details/gtajgesqfd.html

Python ......... 252
来源：http://dali.zhiwuduotai.top/Article/details/gtmayoxqrw.html

PHP ............ 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaafzlxit.html

JavaScript ..... 252
来源：http://dali.jinqigufen.top/Article/details/gtysndhzaa.html

TypeScript ..... 212
来源：http://dali.yueranfly.top/Article/details/gtsaqelwwp.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgudkmlh.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtyicujixo.html

Ruby ........... 212
来源：http://dali.sufxvd.cn/Article/details/gtitzxtwet.html

C# ............. 212
来源：http://dali.gzhubu.top/Article/details/gthmseeiln.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gttlwmjtao.html

C++ ............ 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzbtgqfn.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gtutnyegza.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtqnehedln.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtglrcidyv.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtdeohzpcl.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtdbkxevar.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gtqazvtmzx.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gtecqncyue.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gteikdzodl.html

合计 ........... 2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtobqsgjsz.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gtnyqkrjxm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtunymftum.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gthihvrbrk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtypdmkiod.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtiwilhzjt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gtmmvgmqtk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtrfrpklmd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtiopykzvh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtrntftyzb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtgbfofdsw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtmkzfijoq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtsnjcylpo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtyvthauoe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtvsyhunjy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtlzitujeg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gtxewrzmtg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtuitygmye.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gtoxoxvfol.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gtjxdqyppz.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gtknhnpuzd.html

T 其他语言补充                          60
来源：http://dali.zhixingplan.top/Article/details/gtbfjpplty.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtmbuyxs.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtcdkdxorx.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gttxixgncz.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtuiphcbvg.html

使用提醒
来源：http://dali.dashuyun.cn/Article/details/gtonkolson.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtqktkjliz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gtvntieedm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhsmrdiv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cashguo.top/Article/details/gtdpaujioe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gtizduitty.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.feifeiyinyue.top/Article/details/gtglfsgdlq.html

—— 文件结束 ——
来源：http://dali.hysaishi.cn/Article/details/gttxcgnsuv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtufvjffbd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fzhhl.top/Article/details/gtndwkwvbl.html

Common Programming Examples Cheat Book
来源：http://dali.mhx1999.top/Article/details/gtulsuiprf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtaamuwkok.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gtawizfkkh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogjbtgue.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yonumen.top/Article/details/gtvdspyjws.html

SQL · Bash · C · C++
来源：http://dali.pengpengdd.cyou/Article/details/gtsfrnphvy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xylfe.cn/Article/details/gtbbffurzc.html

【使用说明】
来源：http://dali.ehwqpu.com/Article/details/gtsbzlpgoz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ivvv.top/Article/details/gtbsenfvhe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gtthucaswe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabhlaqct.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gtloimlipi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gtsrnbthjl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jianghu66.top/Article/details/gtjsplctlp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daria6918.cn/Article/details/gtkvufqylc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtywaaucqm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hysaishi.cn/Article/details/gtxqohqatv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtlernykkz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gtfhlbmbat.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gtrhfqarnd.html

【文件统计】
来源：http://dali.andypj.xyz/Article/details/gtbcdkhnqk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tianlin.xyz/Article/details/gtotnhezoy.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtyanujmao.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtssvbkxgo.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtdabrvwko.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenzaomai.com/Article/details/gtgdenwtyr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtoemcwqfj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtydxtrmpt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gtrjletzln.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtmklzngvm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtbaknilnx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtmnzwbzin.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtzpszajvr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnfmyeic.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gteesydvow.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtpljfbofh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqxurbytu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtcunbzlbl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtcnpvknbu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxuanxn.top/Article/details/gtuhkwwgzr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtcyqjonxe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gtrocugrxb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtycxerokk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sysykeji.top/Article/details/gttannivou.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtrtbjgvcy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtkrnkktaw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtszkmybgm.html

A. 基础语法与类型
来源：http://dali.svipenyu.cn/Article/details/gtxkvvmkmn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmqwhpawj.html

[A01] Hello World
来源：http://dali.yonumen.top/Article/details/gtdvgnpqxe.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtmbxefhpj.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtfxkbbyhq.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswhwvhbz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gtkfmhavlm.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtctfwzxni.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gtqeyxonhu.html

Ruby: puts "Hello, World!"
来源：http://dali.sysykeji.top/Article/details/gtdlupghqv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtquqvzqvx.html

[A02] 变量声明与赋值
来源：http://dali.haohaochexian.top/Article/details/gtzmmnvfbn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gtyeibhtbc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtvnlvyebd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gthnvajalb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczajvycw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtqklopbiw.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gtheltsxae.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj202588.top/Article/details/gtnqzkgvpf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtuducizco.html

[A03] 常量定义
来源：http://dali.ivvv.top/Article/details/gttahivpbi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.haohaochexian.top/Article/details/gtdyvkzrdt.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtnewzjmkl.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtmfhntesa.html

TS:   const PI: number = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtaqjqlnfu.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtdmtgbvmo.html

Go:   const PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtbelkvvpy.html

Ruby: PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gtdtvwbndg.html

C#:   const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtlniiflie.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gtskntfdnb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxhwezqa.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtczbzhkvy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtyejcmgri.html

TS:   typeof x; x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtwuzazstr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xylfe.cn/Article/details/gtjvduoyfo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gzhubu.top/Article/details/gtjnefcriu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gtjehwywkt.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gtzfttxsmx.html

[A05] 整数除法与取模
来源：http://dali.nanxuanxn.top/Article/details/gtesdrqzev.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hammf.cn/Article/details/gtmchpxaei.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtgwsozjbk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtdapztiov.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gtbuzxztdn.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtnilsakpe.html

Go:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtmhuybusg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtzqolautg.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtxdsthymu.html

[A06] 字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtocptvaye.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtujcpndsd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ybcxt.top/Article/details/gttpbhnuuy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gtaggyfufa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258.top/Article/details/gtinbhmmlg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtpufyejpi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.smart0.xyz/Article/details/gtjmktvplp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gtgiwyhoik.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtdaluyamh.html

[A07] 数字转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtmuinqobr.html

Py:   str(42)
来源：http://dali.zhongyouzk.top/Article/details/gtrdtqddig.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhengqikj.top/Article/details/gtexdwggnt.html

JS:   String(42); (42).toString()
来源：http://dali.cucudq.cn/Article/details/gtblocgkbo.html

TS:   String(42)
来源：http://dali.daria6918.cn/Article/details/gtdohluzbr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtuxkknygy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhixingplan.top/Article/details/gtcfcmveid.html

Ruby: 42.to_s
来源：http://dali.daxiang520.top/Article/details/gtuvoexqnl.html

C#:   42.ToString()
来源：http://dali.jinqigufen.top/Article/details/gtmeaacefk.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gtnuatfmdn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gtrucugedh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gtjfhfchhw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtthzkhvjw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhengqikj.top/Article/details/gtwxpaarzg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtbkydyiso.html


<!-- 参考信息 -->