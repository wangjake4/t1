代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtdfcxzyoh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtmrqftelk.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gtucqgsauh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zdqjudy.top/Article/details/gtzbooqszm.html

[U61] PHP：正则
来源：http://dali.nanxuanxn.top/Article/details/gttnhsiyuy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtbnldrsfu.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtyglfjlxf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gtyqhqkvhv.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gtsiiosxgu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gttsqvfgsd.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtjovijxbj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtyyrpxcbc.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gtrthzxvtx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtrdpqgmpn.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gtlbszeent.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258.top/Article/details/gtnfwlozuu.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258.top/Article/details/gteruqwkpp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.havefunace.top/Article/details/gtqxlrtfad.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gtlenwnymd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gtxwwuhiky.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gtspoqtgmv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gthbkfwzhi.html

[U70] PHP：PDO 事务
来源：http://dali.gotoacloud.top/Article/details/gtnimevrvw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gtwpqxonku.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gtvlqyaezq.html

throw new RuntimeException("失败", 500);
来源：http://dali.sweek.top/Article/details/gtptycevfl.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gtoouhmobz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gtdjrfuhty.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenzaomai.com/Article/details/gtalmltlxy.html

parse_ini_file("config.ini", true)
来源：http://dali.cucudq.cn/Article/details/gtptngnqed.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkkopdqa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenjidiqi.icu/Article/details/gtukvrlnga.html

[U75] PHP：依赖注入
来源：http://dali.pycfn.com/Article/details/gtokpgitpt.html

composer require psr/container
来源：http://dali.yangfankeji.com/Article/details/gtlalpivjp.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxwqfcdy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtyzmkvtqv.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtxykbetxp.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtgfcspcgb.html

[U78] PHP：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtnegiwumu.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtolunukfc.html

[U79] PHP：静态分析
来源：http://dali.sufxvd.cn/Article/details/gtvkjcphjv.html

composer require --dev phpstan/phpstan
来源：http://dali.gaohongyu789.top/Article/details/gtsdlucfuu.html

[U80] PHP：代码规范修复
来源：http://dali.cdnleiting.top/Article/details/gtsoxobiur.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gtzeinoksm.html

[U81] JS：初始化项目
来源：http://dali.cqqwz.cn/Article/details/gtrqbhytvn.html

npm init -y;  npm i express
来源：http://dali.jinqigufen.top/Article/details/gtiwdtqpbw.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gthdhyddoq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gtarwsgmde.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrbzfwgb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gteizncedh.html

[U84] JS：CommonJS 写法
来源：http://dali.jlsjyb.cn/Article/details/gtewoizbon.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gtynxvedys.html

[U85] JS：可选链
来源：http://dali.316326.xyz/Article/details/gtrwrnkzbe.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtciuwhrnl.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gtiidzmwzi.html

a ?? b
来源：http://dali.yuanzhike.top/Article/details/gtxpjwtrdm.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtyihbxsje.html

const { a = 1, b = 2 } = obj;
来源：http://dali.quarkkingdee.top/Article/details/gthwqzugvw.html

[U88] JS：对象展开合并
来源：http://dali.shzxlz.cn/Article/details/gtmkxuokbv.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gtlhrnrnzi.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gtlyiapcxt.html

[...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtufdegqfj.html

[U90] JS：数字数组排序
来源：http://dali.yj20258.top/Article/details/gttkfnljgk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtuikxpygi.html

[U91] JS：对象键值遍历
来源：http://dali.cashguo.top/Article/details/gtgakeupjm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gtubsmqjmc.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtzmtuvbbm.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtgjjjhzgc.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gtputsvwlx.html

`共 ${n} 条`
来源：http://dali.dashuyun.cn/Article/details/gtxdhzhyxi.html

[U94] JS：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtovlocysg.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtlhnbhudd.html

[U95] JS：Promise 包装
来源：http://dali.hfpthk.cn/Article/details/gtylymyycl.html

new Promise((resolve, reject) => {})
来源：http://dali.daria6918.cn/Article/details/gtqtvobfqr.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigufen.top/Article/details/gtjpfktmjl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtrdvxeofb.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gtrctrlihu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtyqgrdwpf.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gtcqquxkrc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gtsujllddp.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gtufqlnzsr.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gtayumezlv.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gtrwecizzo.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtdtlqqabm.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtxqcpqdln.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruenqsyk.html

[U102] JS：本地存储
来源：http://dali.fzhhl.top/Article/details/gtmdurrixw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gtkoohwpun.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtbrwovyfw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtlbkowruj.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gtcyginlus.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtnttvnlpz.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gthofriemu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sufxvd.cn/Article/details/gtwfmqelvf.html

[U106] JS：日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkdnoehnj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gaohongyu789.top/Article/details/gtvonftjhl.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gtdodtyias.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pycfn.com/Article/details/gtdbwrxvef.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgbgtdnn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hysaishi.cn/Article/details/gtbifjcadq.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtwckbfhwz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gttatroypk.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtmytzxqjl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gtlyjjlaho.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtpvkttxgk.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtzcgnappz.html

[U112] JS：字符串补位
来源：http://dali.yanxiufei.cn/Article/details/gttuuriiji.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtnwhpoirw.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gtuphgnodb.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtmznvhzea.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gtyocinjlc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtwlipemlm.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtquhtrjxp.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtetcnqurz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gtuxwwkvan.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtrdlmfebs.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gtcxmoelnj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gthvaxjalh.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gtwyfkgryg.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtspwmumfi.html

[U119] JS：生产构建
来源：http://dali.nanxuanxn.top/Article/details/gtrnvzwnni.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gtsvkolalv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gtcpeexvfu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gthitwoqlg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtltukicoa.html

统计汇总
来源：http://dali.snrcjt.cn/Article/details/gtzteihmcz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnobbtsyl.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtwvkejdlw.html

Python ......... 252
来源：http://dali.tianlin.xyz/Article/details/gthcjxwmjz.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gtygdnscgs.html

JavaScript ..... 252
来源：http://dali.jinqigufen.top/Article/details/gtlpdqpxmo.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gtbrzyynoa.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftnbniow.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtzziedjzj.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtrkpgnyte.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gtrfszaqem.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gteztjmacz.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gtopmxuehs.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtjdxkmwct.html

Bash ........... 80
来源：http://dali.shanyushiyangtech.top/Article/details/gtzquhgolt.html

Kotlin ......... 15
来源：http://dali.hywenlv.cn/Article/details/gtoewdjwuo.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtgeqczcae.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gtpkxgwjtj.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtvllrluhv.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhstxkbz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtqhqddrkl.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtepnptmwj.html

按章节统计：
来源：http://dali.jinqigfzy.top/Article/details/gtucfxlzfr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtsdtokhwm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiwzhinp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtnnzpajsm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gtazsqjpfp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gtkfyxbwgg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtajhzbivg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtzsrjdcni.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaokrngn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gttuvitjom.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtkfnwyvks.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtovmrnobj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtidnhnifi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtfrzsbdsr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gtgugtgkkn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tianlin.xyz/Article/details/gtbiehaoqu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtqwbbakam.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gtbseerghg.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gtnljnpbkk.html

S C / C++ 专题                          60
来源：http://dali.haohaochexian.top/Article/details/gtjxpzitny.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gtnvpcgvka.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gtifkxorgl.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtlimqdjpl.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gtgqviyqjg.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gthjwxeozd.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gtfoyftqpy.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtiilquhvv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.snrcjt.cn/Article/details/gtlshmpabb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shuidangran.top/Article/details/gtchodwfan.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daxiang520.top/Article/details/gtzjfolgbb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.birdmap.top/Article/details/gtgpfsyvhw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtbrdcbglj.html

—— 文件结束 ——
来源：http://dali.jlsjyb.cn/Article/details/gtcwehwbtb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfrugcpa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gogol.net.cn/Article/details/gtytdhirpe.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gtdmzyyrqc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtourfpuhg.html

【收录内容】
来源：http://dali.zycfv.cn/Article/details/gtfjocdgdi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevfvxazi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gtspabyexv.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gtubmmsqol.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.c1oappe.top/Article/details/gtrffsryvi.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gttnrgqprr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiabashb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenjidiqi.icu/Article/details/gtnwnjfalq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shuidangran.top/Article/details/gtafyvlcbf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ppjwa.cn/Article/details/gtgcvlwycc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigfzy.top/Article/details/gtbmtimvjt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ydzc1.top/Article/details/gtjwefwznb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gtodqsjimc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnxiangtu.top/Article/details/gtqaikimci.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.9152youxi.cn/Article/details/gttgbecgkn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhiwuduotai.top/Article/details/gtggdphhzu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sweek.top/Article/details/gtluifkgnb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtmnmmjdvw.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtmggolxoh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258.top/Article/details/gtacbycrgh.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gthofrmilk.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtlumobbuk.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtngxqnpla.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtejyfrazr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtpplmvtth.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtspabygpj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtxsjvhhiu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtjibqahas.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtbpzuzptw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtzzpdffeq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtiniickrn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtwktumfgx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gtqmkldssa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtvldzkabt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtmxrgjtlf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtazugeicr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtdvjcwbxc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenlongwang.top/Article/details/gtdpimsxxm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtornnqnbn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrkuvpdz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuxming.cn/Article/details/gtewftjeda.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gtqjrejxss.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtugnuvdou.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtwarejslj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmylrfpaj.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gtfdbzodej.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtimthlkaj.html

[A01] Hello World
来源：http://dali.nanxinkj.top/Article/details/gtsbpmejhi.html

Py:   print("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gtfiufjlci.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gtxrxhnxcq.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtszwtujzb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gzhubu.top/Article/details/gtbtunostq.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtdanauzpo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gtqglfxoiz.html

Ruby: puts "Hello, World!"
来源：http://dali.sysykeji.top/Article/details/gtoqvtakuf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtwbgzinbz.html

[A02] 变量声明与赋值
来源：http://dali.zhoulong.xyz/Article/details/gthgaedsxr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtdbbeqqdd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtiiprqfdy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtyeepzdux.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtbjxfvxsf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtkdvjposo.html

Go:   name := "Alex"; age := 20
来源：http://dali.fengsongda.top/Article/details/gtspcupmxr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.smart0.xyz/Article/details/gtpbqnjhvb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fzhhl.top/Article/details/gttabqezur.html

[A03] 常量定义
来源：http://dali.guowangkeji.top/Article/details/gtqdziidbh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jiagoushi.top/Article/details/gthwnsazgt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtqtrzxvxb.html

JS:   const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtlljcgyqr.html

TS:   const PI: number = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtkfdoiobl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gthxoofnvt.html

Go:   const PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gtsbnrvznz.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtgykjiypm.html

C#:   const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtjgpomgzp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtdzqpzojy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhixingplan.top/Article/details/gtwbmafqek.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.iojbl.cn/Article/details/gtexchvkuj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtjkkotrly.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtdhhtrnga.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.iojbl.cn/Article/details/gtqdddnxhg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cdnleiting.top/Article/details/gttrljbhbp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nwbrower.top/Article/details/gtpkagddpe.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxwsaied.html

[A05] 整数除法与取模
来源：http://dali.tian-w.cn/Article/details/gtilcdvplv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ybcxt.top/Article/details/gtszxyrntr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtzdowawvr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtqmfybvnz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtepqvctqm.html

Java: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtoszdited.html

Go:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtzxrpbqeo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtxcrbtsgz.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtbktostvg.html

[A06] 字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gttktfadne.html

Py:   int("42"); float("3.14")
来源：http://dali.gzhubu.top/Article/details/gtktxvipbk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guannengcc.top/Article/details/gtuzythixj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.havefunace.top/Article/details/gtxshrdwcc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtzcvnxdwy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtmziyrmgk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.9152youxi.cn/Article/details/gtsqwvgqtu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ivvv.top/Article/details/gtwpgomclp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zycfv.cn/Article/details/gtybmhicqa.html

[A07] 数字转字符串
来源：http://dali.zdqjudy.top/Article/details/gtdokcolsc.html

Py:   str(42)
来源：http://dali.haohaochexian.top/Article/details/gtljomwuah.html

PHP:  (string) 42; strval(42)
来源：http://dali.hfpthk.cn/Article/details/gtkxmmcgjq.html

JS:   String(42); (42).toString()
来源：http://dali.vqdsnc.cn/Article/details/gtrguatgaz.html

TS:   String(42)
来源：http://dali.nwbrower.top/Article/details/gtrenyrbgz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.snrcjt.cn/Article/details/gtuxxjwqac.html

Go:   strconv.Itoa(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtvlcvlrlb.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gtygmvtvnf.html

C#:   42.ToString()
来源：http://dali.jiagoushi.top/Article/details/gtyfmbflfh.html

[A08] 取整与四舍五入
来源：http://dali.vqdsnc.cn/Article/details/gtvjinecek.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtlfdtczep.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daria6918.cn/Article/details/gtdeatsvhs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclgvmxue.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gaohongyu789.top/Article/details/gtsbfcgkaq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtppbptqes.html


<!-- 参考信息 -->