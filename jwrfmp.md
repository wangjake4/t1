代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtwvkrdllc.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gtiicvqwgh.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gtmldogtnq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtmpfpcbxe.html

[U59] PHP：自定义排序
来源：http://dali.vqdsnc.cn/Article/details/gtgmbaqmnr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwjcyckz.html

[U60] PHP：JSON 编解码
来源：http://dali.yj202588.top/Article/details/gtdbmhmcaw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gtybuwzbhk.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gtztoiwfrx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtcrsaiyau.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtceiokawt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gtyaadelja.html

[U63] PHP：文件读写
来源：http://dali.zhongyouzk.top/Article/details/gtamvneuqj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tanke756.top/Article/details/gtfdqxpuhr.html

[U64] PHP：目录遍历
来源：http://dali.nanxuanxn.top/Article/details/gthcpegrfy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cqqwz.cn/Article/details/gtnqmyuqad.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gtlrwpxwvr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtakjwreak.html

[U66] PHP：设置 Cookie
来源：http://dali.cdnleiting.top/Article/details/gtfrkfclqg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gtbhwntbhh.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gtqiwqfboh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dianchejie.cn/Article/details/gtwatxsiha.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtqzxyissv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jlsjyb.cn/Article/details/gtnzqluxna.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyfzkyjs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnzoomem.html

[U70] PHP：PDO 事务
来源：http://dali.jqgufenzy.top/Article/details/gtefqnagny.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gtjgjnrzvy.html

[U71] PHP：抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtvvahtbkz.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtqsvyewfb.html

[U72] PHP：写错误日志
来源：http://dali.zhiwuduotai.top/Article/details/gtwpoyldwl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gtfgaxwskj.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gtmjyelavm.html

parse_ini_file("config.ini", true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsiyacqt.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtkjazgbpg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cdnleiting.top/Article/details/gtehazkrna.html

[U75] PHP：依赖注入
来源：http://dali.fzhhl.top/Article/details/gtmrzaqjkw.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtpldffcqp.html

[U76] PHP：简单路由
来源：http://dali.nanxinkj.top/Article/details/gtonskzodc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinghuilouyu.cn/Article/details/gtopevfryu.html

[U77] PHP：模板渲染
来源：http://dali.jinqigfzy.top/Article/details/gtypkmaavu.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gtxkmjcgpy.html

[U78] PHP：单元测试
来源：http://dali.fzhhl.top/Article/details/gtbuazgynh.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gtlicwwnbq.html

[U79] PHP：静态分析
来源：http://dali.quarkkingdee.top/Article/details/gtyaqvzhjq.html

composer require --dev phpstan/phpstan
来源：http://dali.316326.xyz/Article/details/gtwvwaakjy.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gteqbgattk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.mhx1999.top/Article/details/gtlkxyyxeq.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuggkonsh.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtofmavxjh.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjtpiwtq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hammf.cn/Article/details/gtowunrmun.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuanzx.com/Article/details/gtgoairnok.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtdzcpxdsq.html

[U84] JS：CommonJS 写法
来源：http://dali.hammf.cn/Article/details/gtqqemmbvz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shzxlz.cn/Article/details/gtzkjofsql.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gtuigsoeva.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrvcgvnb.html

[U86] JS：空值合并
来源：http://dali.gaohongyu789.top/Article/details/gtitjjfvmz.html

a ?? b
来源：http://dali.fengsongda.top/Article/details/gtgroimpkp.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvrdrwaa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gtdpfnejkk.html

[U88] JS：对象展开合并
来源：http://dali.svipenyu.cn/Article/details/gtrjktbxbo.html

{ ...a, ...b }
来源：http://dali.fengsongda.top/Article/details/gtpzotostp.html

[U89] JS：数组去重
来源：http://dali.tian-w.cn/Article/details/gtnmlqhgyu.html

[...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtzqoxrcjn.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gtjkbagonn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtinzytlcr.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigfzy.top/Article/details/gtzuxpgcsv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnxiangtu.top/Article/details/gtgtoltukv.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gtkjpbncfw.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtpnexpbwx.html

[U93] JS：模板字符串
来源：http://dali.zhengqikj.top/Article/details/gtumpecycf.html

`共 ${n} 条`
来源：http://dali.sxryk.cn/Article/details/gtvfdyexjk.html

[U94] JS：箭头函数
来源：http://dali.yj202588.top/Article/details/gtfvplwddt.html

const double = x => x * 2;
来源：http://dali.jianghu66.top/Article/details/gtnybuvlgo.html

[U95] JS：Promise 包装
来源：http://dali.xylfe.cn/Article/details/gthdxpxpcl.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhzrefue.html

[U96] JS：async/await 与异常
来源：http://dali.ppjwa.cn/Article/details/gtuxutlrhf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtqpnnpseg.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gtdmazorps.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqydpolb.html

[U98] JS：fetch 带 JSON
来源：http://dali.xziqi.cn/Article/details/gtdocqtwre.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtrolpmcmp.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gtcxuzsuzn.html

el.addEventListener("click", e => {})
来源：http://dali.cucudq.cn/Article/details/gtnmazknic.html

[U100] JS：DOM 查询
来源：http://dali.sufxvd.cn/Article/details/gtdmlldypj.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujbeqcqg.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gthlwcxion.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtrjswhezt.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gtfhdeknzt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gtbvcikmkw.html

[U103] JS：定时器
来源：http://dali.xuanzx.com/Article/details/gtxrlawgkb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gtucvwbkpr.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gtqevyvucb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtxlixmxsx.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtslnbpoki.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gtsdumshou.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtzlkehobo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tianlin.xyz/Article/details/gtunlwzehf.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtideintdz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ivvv.top/Article/details/gteynoahnq.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gtddejmbfe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtqodqvwdy.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtoeyzmifu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtdxvdqipy.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtnsxstowa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.haohaochexian.top/Article/details/gtivgbjzee.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gtzvltsvdd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtotufozai.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpvlnqhu.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtsxkrhquw.html

[U113] JS：正则替换全部
来源：http://dali.cucudq.cn/Article/details/gtrjmcpupp.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtmpdflvxn.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gttmsjbnit.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtspocrbaz.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtzzqgrweb.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtmbvsjcib.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtsapcclyn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gtnvuptiyo.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gttmjhujdk.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlantfupq.html

[U118] JS：开发服务器
来源：http://dali.0kj1m.cn/Article/details/gtbtpezlqz.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gtvptmoqhp.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtvnidnsal.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gtwkjkcban.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuetiantiany.cn/Article/details/gtgumongjg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhoulong.xyz/Article/details/gttzciforv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtogeqhqws.html

统计汇总
来源：http://dali.yvedp.cn/Article/details/gtdwqicvlu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtydjhmwep.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gtbhtgldjo.html

Python ......... 252
来源：http://dali.yanxiufei.cn/Article/details/gtaqaqwdur.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gtqtffrjer.html

JavaScript ..... 252
来源：http://dali.tanke756.top/Article/details/gtssaqsgck.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gtjthuojst.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtmyopdjvg.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gtlllixrkl.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gtaqyualwc.html

C# ............. 212
来源：http://dali.ydzc1.top/Article/details/gtzgyuvwug.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gtpckwfklj.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtopvxeofn.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gtyqvoktmk.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gtgxzipbmd.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtdsaliqem.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gtkfrdlsai.html

Lua ............ 10
来源：http://dali.ybcxt.top/Article/details/gtnlsrscpp.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtvwhkcixj.html

Scala .......... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtegcmlzcu.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtwojhkvag.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtvxoqnoeh.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtrddpoutc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtzsjceoaj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtsvguetir.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbkoxwuy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtpqffghvo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gtxcbzietk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gttozlptbv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtyoesmopk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtmbwvgxsb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtayolbjnd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtmlaszico.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhvnrfpu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtxmmmsgkw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtnfopdapc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtvoikhzuk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtvxjcqvaz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtgyvyaqzo.html

Q SQL 专题                              90
来源：http://dali.xziqi.cn/Article/details/gtcccuumjj.html

R Bash 专题                             80
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmhdkbsa.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gtbvwqgtkv.html

T 其他语言补充                          60
来源：http://dali.hammf.cn/Article/details/gtxzuahlqb.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gtvsrrplvw.html

------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtxnogchty.html

合计                                  2106 条
来源：http://dali.hfpthk.cn/Article/details/gtmuxyygbi.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtsgbrapbx.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gtcpbkgeip.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtdwmtlsdf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.haohaochexian.top/Article/details/gtfmhtrqiq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijbpfgxd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sweek.top/Article/details/gtxsbafifr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gtwozhnvcy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cqqwz.cn/Article/details/gtpicvbbei.html

—— 文件结束 ——
来源：http://dali.xinyue.icu/Article/details/gtofgfmesj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttumlcuye.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gtdqitrjti.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gthwhsxjjz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlthytdic.html

【收录内容】
来源：http://dali.smart0.xyz/Article/details/gtxhoxqerr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gtgunzlcbq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sysykeji.top/Article/details/gtxxvwaisn.html

SQL · Bash · C · C++
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbgiylbr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtijizszff.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gtwsvemjyv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nwbrower.top/Article/details/gtcvjwxnfv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.9152youxi.cn/Article/details/gtxkpxsobe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ppjwa.cn/Article/details/gtmiqgygvg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtigmzlsoc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtdwqikwuj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tian-w.cn/Article/details/gteebqmftw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigufen.top/Article/details/gthzmivqgw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.havefunace.top/Article/details/gtaeljobob.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.iojbl.cn/Article/details/gtruxfvztg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtuyuwcxqq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gthhzbszmj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.c1oappe.top/Article/details/gtphhhjgvh.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtfahjdjsr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfigyumo.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtyiphzgtw.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtjjqhohkk.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtakylmdxv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbqjzvxa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtxwnjkkgf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtrgtmuajz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gtsufyeheo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.vqdsnc.cn/Article/details/gtoqeusphx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtszablfwa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtgsysufim.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbqwsudj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gttjhmspdz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gthvcawgvq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqffogziw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtwoaqcadf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtxtckiytn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtigekhkcc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gotoacloud.top/Article/details/gtfkwgcdvo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtompoixoo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtkpijcagc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daria6918.cn/Article/details/gtgiyddqfr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yueranfly.top/Article/details/gtfvqbbysw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtljhuwelq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtezqgalvn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxmpwurah.html

A. 基础语法与类型
来源：http://dali.hnqzz.top/Article/details/gtwzpemhma.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtatiynxan.html

[A01] Hello World
来源：http://dali.mhx1999.top/Article/details/gtrfdipkmh.html

Py:   print("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gttjmzcjjc.html

PHP:  echo "Hello, World!";
来源：http://dali.guowangkeji.top/Article/details/gtlcvzsjdf.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtjinsrizc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cucudq.cn/Article/details/gtfotxkvzb.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtcpdrvshh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtsttxeesw.html

Ruby: puts "Hello, World!"
来源：http://dali.yanxiufei.cn/Article/details/gtuzjbcrmz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtweljrpar.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gtlblvyfst.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sysykeji.top/Article/details/gtqxhztdpk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nwbrower.top/Article/details/gttptmetha.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj202588.top/Article/details/gtnmujmnov.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zdqjudy.top/Article/details/gtijioxdrw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gttxdtlpoo.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigfzy.top/Article/details/gtmvtpqjoh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gtgqgkamni.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtlkhjocdv.html

[A03] 常量定义
来源：http://dali.havefunace.top/Article/details/gtobzflfyu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenzaomai.com/Article/details/gtvvemsweb.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtqebbsneu.html

JS:   const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtomhzhosg.html

TS:   const PI: number = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtancoymys.html

Java: static final double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtlpdqhjrn.html

Go:   const PI = 3.14159
来源：http://dali.shzxlz.cn/Article/details/gtxyllijho.html

Ruby: PI = 3.14159
来源：http://dali.shuidangran.top/Article/details/gtittpqqmd.html

C#:   const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtaizbamtn.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtrqodgppd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gtrwenvgxv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtftllxgou.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtkrmtmfuh.html

TS:   typeof x; x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gtjqmddvbv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gtoobmixkl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigufen.top/Article/details/gtkzdjgozy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigufen.top/Article/details/gtopznildt.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gttbfirtqg.html

[A05] 整数除法与取模
来源：http://dali.dashuyun.cn/Article/details/gtwtyclbwe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlonfplpa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtvkbelovi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtimroamuu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gttmduugfl.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtdotjuazw.html

Go:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtmogjkwxz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtmcsvimfl.html

C#:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtsdwighrv.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtmyebemer.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtgtjqzgfi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxuanxn.top/Article/details/gtexuewyre.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gtgfodkjku.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtpurwfiah.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqpnovvg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fzhhl.top/Article/details/gtknvalcrs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gttknrjbih.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtgohwidhc.html

[A07] 数字转字符串
来源：http://dali.hfpthk.cn/Article/details/gtrwxyqjsn.html

Py:   str(42)
来源：http://dali.zhixingplan.top/Article/details/gtvsqagkvl.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigfzy.top/Article/details/gtrcbebzeb.html

JS:   String(42); (42).toString()
来源：http://dali.ppjwa.cn/Article/details/gtlgosgeuj.html

TS:   String(42)
来源：http://dali.cdnleiting.top/Article/details/gtybgoenxd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.fzhhl.top/Article/details/gtfnlgsmac.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqmvrcqi.html

Ruby: 42.to_s
来源：http://dali.zhiwuduotai.top/Article/details/gtwourucff.html

C#:   42.ToString()
来源：http://dali.fzhhl.top/Article/details/gtzuywauad.html

[A08] 取整与四舍五入
来源：http://dali.redwolf501.top/Article/details/gthjuiojeg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gthbdxzmxt.html


<!-- 参考信息 -->