代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.iojbl.cn/Article/details/gt2bryjjtnb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nemogxlt.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehqhywbj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.bjfxy.top/Article/details/gt2zjjotubc.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gt2qlvlhukw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2tqgrhecs.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gt2krsopfpb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gt2ryrynpad.html

[U63] PHP：文件读写
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjhxnuhs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258888.top/Article/details/gt2kswunkcx.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gt2vobqzprj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gt2kqeleckq.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gt2yzekjfkv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2yungkslq.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gt2jczlrdre.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.meibo888.top/Article/details/gt2ivcrasjb.html

[U67] PHP：处理文件上传
来源：http://dali.yongpay.top/Article/details/gt2fxagovyz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenlongwang.top/Article/details/gt2tluhfubq.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gt2yoqizdkk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sysykeji.top/Article/details/gt2yttdlhnp.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncgzdpih.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gt2vivffzvd.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gt2zlkdpunf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gt2obakwgxb.html

[U71] PHP：抛出异常
来源：http://dali.316326.xyz/Article/details/gt2auunbknh.html

throw new RuntimeException("失败", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2nyqzzlyz.html

[U72] PHP：写错误日志
来源：http://dali.quarkkingdee.top/Article/details/gt2vhohujed.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2giuajtnb.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtphormb.html

parse_ini_file("config.ini", true)
来源：http://dali.haohaochexian.top/Article/details/gt2lxxepegg.html

[U74] PHP：读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2mpujzupj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gt2fxhgoagh.html

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gt2nbyiueds.html

composer require psr/container
来源：http://dali.shuidangran.top/Article/details/gt2iepjxnrq.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gt2plfjyjin.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gt2uzremvky.html

[U77] PHP：模板渲染
来源：http://dali.ivvv.top/Article/details/gt2ykvznmbt.html

composer require twig/twig
来源：http://dali.ydzc1.top/Article/details/gt2vnhgncvf.html

[U78] PHP：单元测试
来源：http://dali.hammf.cn/Article/details/gt2giowulfq.html

composer require --dev phpunit/phpunit
来源：http://dali.birdmap.top/Article/details/gt2tkgruezy.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gt2nbnitlor.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gt2tcashtna.html

[U80] PHP：代码规范修复
来源：http://dali.316326.xyz/Article/details/gt2cnafiqrj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gt2ysldgjou.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxcctyau.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gt2umjaohss.html

[U82] JS：package.json 脚本
来源：http://dali.aizwys.cn/Article/details/gt2wgpridqs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gaohongyu789.top/Article/details/gt2frnpohjn.html

[U83] JS：ES Module 导入导出
来源：http://dali.jlsjyb.cn/Article/details/gt2mogklikd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gt2odavzsls.html

[U84] JS：CommonJS 写法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgigqeqq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnxiangtu.top/Article/details/gt2iggoqwrh.html

[U85] JS：可选链
来源：http://dali.cheryme.top/Article/details/gt2blyumhjq.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcznypcn.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gt2tpmwcoft.html

a ?? b
来源：http://dali.sufxvd.cn/Article/details/gt2ufoyrwyy.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gt2mpbxwqta.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gt2wpffkcyw.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gt2efgpgwce.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gt2hojqxiod.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gt2ifrmmlxk.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2evergwjc.html

[U90] JS：数字数组排序
来源：http://dali.9152youxi.cn/Article/details/gt2bwcgbizm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2oszusaoy.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gt2ayarubkg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fengsongda.top/Article/details/gt2igbtbowm.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gt2wswscoac.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2wyzrccgv.html

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gt2lkkburyi.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gt2jkoidmoi.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gt2aqeeykxe.html

const double = x => x * 2;
来源：http://dali.ydzc1.top/Article/details/gt2nlucoypt.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gt2ichiawbo.html

new Promise((resolve, reject) => {})
来源：http://dali.guowangkeji.top/Article/details/gt2gkhuuciv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvfynoc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2rhtqmcrc.html

[U97] JS：并发请求
来源：http://dali.snrcjt.cn/Article/details/gt2qvnyxdrb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2dvffhcph.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gt2fopjvrju.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gt2sumzygdg.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gt2npdoyolf.html

el.addEventListener("click", e => {})
来源：http://dali.meibo888.top/Article/details/gt2qcolfoso.html

[U100] JS：DOM 查询
来源：http://dali.xziqi.cn/Article/details/gt2awsqclfd.html

document.querySelector(".item")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvfzkniu.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gt2ugflnbmk.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gt2vqteewnu.html

[U102] JS：本地存储
来源：http://dali.nanxinkj.top/Article/details/gt2dccqjlly.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gt2ckyxftli.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gt2iuvstlml.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gt2uxaejxfc.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqcxmddd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2mfqvwvxk.html

[U105] JS：节流
来源：http://dali.aibaodan.cn/Article/details/gt2jfpcfvmq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gt2viyfcnwk.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2wwcifwwz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gt2tdbfhdks.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2cjagskqn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2qifvjxua.html

[U108] JS：随机整数
来源：http://dali.9152youxi.cn/Article/details/gt2cuvrxbwc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gt2nszvbpwc.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gt2aaaxcxtl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2yvtoibpw.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gt2evcwfjqo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqgbzive.html

[U111] JS：对象转 Map
来源：http://dali.cashguo.top/Article/details/gt2lxqkslbu.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gt2wnihfxea.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gt2hhyohgjm.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2hhyeblgu.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gt2jpytfadw.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2bzqtfxyz.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gt2aulmhfjo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2baxygdpa.html

[U115] JS：生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqwqvdoe.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2yntalivf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gt2ncamqamn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2nntpcbdh.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gt2osxksizr.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgufenzy.top/Article/details/gt2tvbtfcab.html

[U118] JS：开发服务器
来源：http://dali.cucudq.cn/Article/details/gt2gqyqghjk.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gt2iyuboxkn.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gt2tecbbfsz.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gt2muhqsuwc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2vttmprgj.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gt2llxzeukd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmiwxoil.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gt2xkaipepp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2mqwvvoua.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gt2rxdkkpac.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gt2ibuukury.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjyxxzvj.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gt2rwxehcrc.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gt2rrcxaxlr.html

Java ........... 212
来源：http://dali.sufxvd.cn/Article/details/gt2imtyqjrz.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gt2fyutldqq.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gt2idecqczr.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gt2xvhbkfbg.html

C .............. 30
来源：http://dali.redwolf501.top/Article/details/gt2lpkjhjhn.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2qowcaihz.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gt2krovovyj.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gt2dhetiguz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrbsbqx.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gt2ffxaefme.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gt2htlahgtl.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gt2xsmnlfwi.html

Scala .......... 10
来源：http://dali.yongpay.top/Article/details/gt2pymfojaa.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2zvusigts.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gt2apfsprhj.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gt2rhyldxes.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2amgpwpjs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2gitcninj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gt2qdfgfuop.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gt2epnkoaaw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gt2opnfvzjk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gt2smjwugku.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2spqooeyy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gt2msznnezu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2jwvgepah.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gt2whkzpptu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2evipjtgp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2tazfllpz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gt2wexlgmfd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfixovid.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fzhhl.top/Article/details/gt2zorarxtm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2pdulssrr.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gt2mikuquul.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gt2jwrqeknm.html

S C / C++ 专题                          60
来源：http://dali.birdmap.top/Article/details/gt2qcgqfgfu.html

T 其他语言补充                          60
来源：http://dali.hfpthk.cn/Article/details/gt2mtbvxjkp.html

U 高频实用片段                         120
来源：http://dali.xuanzx.com/Article/details/gt2xzccfabz.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2rosrnfai.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gt2lygzmelp.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2cajawabh.html

使用提醒
来源：http://dali.dashuyun.cn/Article/details/gt2jilsdxkn.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2sxmnglcs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gt2tyytbkaz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258.top/Article/details/gt2gzxjsgyd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gt2jfzkvuuu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gt2tnfivrtx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aibaodan.cn/Article/details/gt2vdbrkxxi.html

—— 文件结束 ——
来源：http://dali.smart0.xyz/Article/details/gt2oiqzrblh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hnnjeqwf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.0kj1m.cn/Article/details/gt2rfcfkiuy.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gt2zzjjclix.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyqkfbsp.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gt2urdzceyq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zycfv.cn/Article/details/gt2goacdkcm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.birdmap.top/Article/details/gt2pcyothrp.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gt2rypmjlil.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gotoacloud.top/Article/details/gt2wteowymq.html

【使用说明】
来源：http://dali.gogol.net.cn/Article/details/gt2fxrhybkm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nwbrower.top/Article/details/gt2ldxgzbic.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.0kj1m.cn/Article/details/gt2mnujdeoo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dianchejie.cn/Article/details/gt2colpqcvb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tanke756.top/Article/details/gt2ekigsudn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.havefunace.top/Article/details/gt2blmtedpp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnxiangtu.top/Article/details/gt2bcsnzzcj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jyoumei.cn/Article/details/gt2dglxgzty.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2dvpklzsa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shuidangran.top/Article/details/gt2umabssuk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gt2lkbrrujm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tian-w.cn/Article/details/gt2wehhdbmm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndwvpqgc.html

【文件统计】
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbpkggxo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gt2fngiguvl.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2pzlrpgoq.html

目  录
来源：http://dali.gotoacloud.top/Article/details/gt2klramabv.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2yrnkctiy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gt2hhmfleii.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gt2mprcbhgt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtlmpizs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gt2barvmqcs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gt2xvnfuckq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gt2jiigmnue.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2uqpjjpsz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gt2lvgnejto.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2epqgmyai.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2upwbmdrt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2yiteeihl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkxpsmkg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2kceendiy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gt2eakdrifi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gt2vhognfke.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2vogugbme.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gotoacloud.top/Article/details/gt2sltfqtus.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258.top/Article/details/gt2fqpvxgcs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.9152youxi.cn/Article/details/gt2mvdzrazw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gt2yladlada.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2ukmjjias.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ocmknpsz.html

A. 基础语法与类型
来源：http://dali.ydzc1.top/Article/details/gt2qovztsxx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2sgoewsud.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gt2vdknapwa.html

Py:   print("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gt2pddpntrp.html

PHP:  echo "Hello, World!";
来源：http://dali.yongpay.top/Article/details/gt2nwwvdcox.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gt2zgpxjoku.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gt2xdtpkarl.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2djzlenig.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gt2muzqkjak.html

Ruby: puts "Hello, World!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgyulvvo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2jpnuypmc.html

[A02] 变量声明与赋值
来源：http://dali.316326.xyz/Article/details/gt2aubcxgeb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.mhx1999.top/Article/details/gt2yrcholge.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2iywmpjcc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sxryk.cn/Article/details/gt2iwxbllgk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2rbzbcqsm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gt2agevwsmm.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gt2nemijdoy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gt2ajkguiqs.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2dvtsvanz.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gt2slybvlvs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiwixbvp.html

PHP:  const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2mgrrgpan.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2nqhjyymu.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2drpipcfy.html

Java: static final double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2xfjbcsgl.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gt2nfwziiex.html

Ruby: PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gt2eobcriwv.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2xipzsbjs.html

[A04] 判断变量类型
来源：http://dali.c1oappe.top/Article/details/gt2vqumucac.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangdashe.top/Article/details/gt2szyugmgr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ptmpfymp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2plmsclpy.html

TS:   typeof x; x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gt2ivarmdjq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgfzy.top/Article/details/gt2gycsyutj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gt2xsfgjtme.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dianchejie.cn/Article/details/gt2scekokhq.html

C#:   x.GetType().Name; x is int
来源：http://dali.0kj1m.cn/Article/details/gt2jaygpkmm.html

[A05] 整数除法与取模
来源：http://dali.sxryk.cn/Article/details/gt2fcnqnycd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gt2sfynqoha.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2tsyyazdx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2wxqxbbfu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2ekmbsjgc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2doqfxhyn.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2jmwmhotn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2fttzckbw.html

C#:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2vqsutvqp.html

[A06] 字符串转数字
来源：http://dali.daria6918.cn/Article/details/gt2bcocxqtk.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gt2lmzqxkln.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhoulong.xyz/Article/details/gt2hbexjonf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bylclpcz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ivvv.top/Article/details/gt2zfggeoms.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gt2xpsqjham.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qztvmxyl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gt2sjjxxaey.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.bjfxy.top/Article/details/gt2ncamopqo.html

[A07] 数字转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2kzixlcqp.html

Py:   str(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uslazqha.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenzaomai.com/Article/details/gt2yntnwtie.html

JS:   String(42); (42).toString()
来源：http://dali.xinyue.icu/Article/details/gt2phapclxi.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2qknpkfsp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gt2ehxraees.html

Go:   strconv.Itoa(42)
来源：http://dali.yvedp.cn/Article/details/gt2nauwscoo.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gt2tdduywoc.html

C#:   42.ToString()
来源：http://dali.jqgfzy.top/Article/details/gt2pjmvspim.html

[A08] 取整与四舍五入
来源：http://dali.havefunace.top/Article/details/gt2mkdvrqdf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2jxppzzbh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shuidangran.top/Article/details/gt2cwyopjvw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcmmruog.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yonumen.top/Article/details/gt2qguhmjpu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2ajsaidep.html


<!-- 参考信息 -->