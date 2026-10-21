代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.wangdashe.top/Article/details/gtzvbqjleh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gthfkjnprt.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gtdmzugbgc.html

f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtdtmfjlom.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtptbbyewf.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gtfbokqqbq.html

[U58] PHP：数组三件套
来源：http://dali.ybcxt.top/Article/details/gtotkbdugf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtiwdlgxaf.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtxrevptma.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtbhapcbhj.html

[U60] PHP：JSON 编解码
来源：http://dali.gotoacloud.top/Article/details/gtyppfeozk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ybcxt.top/Article/details/gtosnjnbhy.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gtlsrpqfqc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtpcrbmcxj.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gtaicatkch.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gtggsnbpid.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwtezuvf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gtlyjslvjt.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtwyltgmhy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gaohongyu789.top/Article/details/gtkrggfoej.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gtimqufuyl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gturajpilt.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gtittnrxxo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.kuanghao11.cn/Article/details/gtrfyfojms.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gtianzjliz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gtpjdeqsdz.html

[U68] PHP：PDO 连接
来源：http://dali.fzhhl.top/Article/details/gtwlgejrxh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gtxihhmqfc.html

[U69] PHP：PDO 预处理
来源：http://dali.yanxiufei.cn/Article/details/gtxrshpuly.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gtolotukgc.html

[U70] PHP：PDO 事务
来源：http://dali.kuanghao11.cn/Article/details/gtwjqhmbps.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtnhrgbypq.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtwrmnhbua.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyxxfmcc.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtjwnjqgyx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gtezexklec.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtjoqkdccj.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtxuobjjpu.html

[U74] PHP：读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gthiczdqyt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gteoazkxmd.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtgzxxxbwt.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gtpstnwytq.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gtvalauemi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daria6918.cn/Article/details/gtwlbnveti.html

[U77] PHP：模板渲染
来源：http://dali.meibo888.top/Article/details/gtvtuqrbdy.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gtxtfenjhf.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtfhariwpf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gtfmxgedun.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gtpkuexbkx.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gtvazxyjuk.html

[U80] PHP：代码规范修复
来源：http://dali.wangshuangyany.cn/Article/details/gtmikxvpvw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.9152youxi.cn/Article/details/gtanpksefq.html

[U81] JS：初始化项目
来源：http://dali.gzhubu.top/Article/details/gtjswilqct.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gtprgksyoq.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gtssqvnnta.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgufenzy.top/Article/details/gtbruisytf.html

[U83] JS：ES Module 导入导出
来源：http://dali.kuanghao11.cn/Article/details/gtzrtfqhmk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtnhbjqwcm.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gtshirylnc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tanke756.top/Article/details/gtrbhssvpa.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtmxzrykxx.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gtffrvqtkt.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gttkggfcah.html

a ?? b
来源：http://dali.vqdsnc.cn/Article/details/gtzexzqnky.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvqztgcv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.0kj1m.cn/Article/details/gtckleoppz.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gtjcdwqoeh.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtcjindded.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gtmocfavsg.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtwbsddxrb.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtkxuquykw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gthjupxbdk.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gtchhapteq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sweek.top/Article/details/gtvsezyfjh.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtihqrxwnr.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtyvzeppgu.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gtmifsgwmr.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gtnzpxanag.html

[U94] JS：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gtzgkofflx.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtnccepcfb.html

[U95] JS：Promise 包装
来源：http://dali.nanxuanxn.top/Article/details/gtoppshtwu.html

new Promise((resolve, reject) => {})
来源：http://dali.ydzc1.top/Article/details/gtgmenfzyj.html

[U96] JS：async/await 与异常
来源：http://dali.ivvv.top/Article/details/gtvpqhsfkt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtcjuyuupa.html

[U97] JS：并发请求
来源：http://dali.yangfankeji.com/Article/details/gtyhfncllo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtlmkfidhb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtzmmxxjzt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhiwuduotai.top/Article/details/gtmzzozcfo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gtnbvmigdi.html

el.addEventListener("click", e => {})
来源：http://dali.kuanghao11.cn/Article/details/gtygdshioz.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudcuygle.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaisekac.html

[U101] JS：classList 操作
来源：http://dali.chenlongwang.top/Article/details/gtbjpandkn.html

el.classList.toggle("active")
来源：http://dali.daxiang520.top/Article/details/gtrfnrmdmb.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gtemvlxnjo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gtqggvffrv.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtlwhktbpw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtsfqcnynh.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gtigijmabu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gthwksfdnu.html

[U105] JS：节流
来源：http://dali.bjfxy.top/Article/details/gtxxqrvppb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sufxvd.cn/Article/details/gtsvjxzkzc.html

[U106] JS：日期格式化
来源：http://dali.iojbl.cn/Article/details/gtswrpcfxf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gtnauaqfwi.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtgueqmiwh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtigmdxzhy.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gtbbrdprji.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gtikedlhlv.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtaxlzrybj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqnakojh.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gteknlusxd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yongpay.top/Article/details/gtwwyjesxz.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gttdprhbcl.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gtwiyvqwvi.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gtyqkguqjc.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtqvabccld.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtdlhzhlcy.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtqfxxxglw.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtcndcziiz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtqszkdhtk.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gthtjlxhjk.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtusfttnud.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtjylesvvc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjgofdvdt.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gtiulifoti.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gtiuqmoexk.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gtfgqbptau.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gtdzcikilt.html

[U119] JS：生产构建
来源：http://dali.guannengcc.top/Article/details/gtoxjqomqn.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gteouwuoel.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ppjwa.cn/Article/details/gtcudhkiaf.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gtdabinzbs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnndojhak.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gtnlwnvcif.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdumonisl.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gtihukgrec.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gtshtpbbtj.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtdpcdbevr.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gtslwzsqbq.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtfobdxuxv.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gtaylhaihb.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkzamrek.html

Ruby ........... 212
来源：http://dali.cucudq.cn/Article/details/gtwvlplbhz.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gtawnzoyuy.html

C .............. 30
来源：http://dali.guowangkeji.top/Article/details/gtukgqfekl.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gtanyysift.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtxxaxjxxe.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gtagykyexf.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtvckilnhx.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gtaexzbhbw.html

Lua ............ 10
来源：http://dali.hongshengwenyu.top/Article/details/gtrkpotxtp.html

Perl ........... 10
来源：http://dali.hnqzz.top/Article/details/gtqjwmlsaq.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtbwioxgzm.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvnjvxxy.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtuejutxmo.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gtxadoxivq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtogcdioxj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtjqpyhpac.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxeoqxgm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtraveuikg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtpybfgafg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtcomphhzv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtlftgqorr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtehctzgud.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtxsagnwim.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtxtqnseqg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtqynitgoa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtkeemizao.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtsavnyjrr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtlknqysit.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtasvclsaj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtcyqbsepb.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtxsvvmvcz.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gtclwafsyn.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gteltcddtr.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbrywdds.html

U 高频实用片段                         120
来源：http://dali.nanxuanxn.top/Article/details/gtugxzwbst.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtkcmowqlj.html

合计                                  2106 条
来源：http://dali.aizwys.cn/Article/details/gtsyymhlqx.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtptzyerss.html

使用提醒
来源：http://dali.zhiwuduotai.top/Article/details/gthcnqkqba.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gthttzwjuf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daxiang520.top/Article/details/gtwwaxgbnp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shangyingyoupin.top/Article/details/gtyoplxbzz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cheryme.top/Article/details/gticfecwyq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtmrjifzad.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gteysuolgg.html

—— 文件结束 ——
来源：http://dali.quarkkingdee.top/Article/details/gtdwhmsqkl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpnajhter.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtikgujohx.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gtiqmunciy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaxuokgtu.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gtqbmkflrp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gtiqmxzccq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtgdfnjiwa.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gtizefjuoy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sxryk.cn/Article/details/gttuhrwfyk.html

【使用说明】
来源：http://dali.shuidangran.top/Article/details/gtmenzloll.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gtnphgiyhs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtjmvgnodo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.bjfxy.top/Article/details/gtfsrzpihp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gtbplqnvhc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtzwrlqgrp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gtxytyxhqd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gtkrjmprhy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sufxvd.cn/Article/details/gtxizcjvrh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuetiantiany.cn/Article/details/gtnedjkhma.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pengpengdd.cyou/Article/details/gtizuvmqcg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvptxdjh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtaronjzwj.html

【文件统计】
来源：http://dali.vqdsnc.cn/Article/details/gtxzdtnfhx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtjzpmejgs.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtbltyaoze.html

目  录
来源：http://dali.meibo888.top/Article/details/gtucbiihcl.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtfgwpotkq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtrvajjhdu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gtedlwoqsj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtagaurmah.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtrsffosps.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.kuanghao11.cn/Article/details/gtfezapxwl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtggejmskh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtxqjiwcsr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtzgvsxalk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtdxsgpxgi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtxrrtzbtx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtidfgqdyq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtfzxsqepo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvbmjtdg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gtrtfgzpff.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hfpthk.cn/Article/details/gttwtnmekz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtssqncnqm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.dianchejie.cn/Article/details/gtuchwxmvm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.meibo888.top/Article/details/gtjrpyptux.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.redwolf501.top/Article/details/gtyhmhhtds.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gthkfaahie.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtdqxdwivd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcdgmzdbr.html

A. 基础语法与类型
来源：http://dali.yangfankeji.com/Article/details/gtncsfgwzm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguqfqfod.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gtdkbizmog.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtudmerkqj.html

PHP:  echo "Hello, World!";
来源：http://dali.ehwqpu.com/Article/details/gthonqtbey.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtvinnekxl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.pengpengdd.cyou/Article/details/gtpmfwashw.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtnuugoels.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj20258.top/Article/details/gtthzivipt.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gtlyegkjlj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtiarzhdon.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gtriznzekm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.birdmap.top/Article/details/gtaftuospj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gtysruoskr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtykcvvkbb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtrviphfax.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtdskzccpn.html

Go:   name := "Alex"; age := 20
来源：http://dali.hongshengwenyu.top/Article/details/gtghcvjmxs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gtasbblenm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtqwhsiyod.html

[A03] 常量定义
来源：http://dali.dianchejie.cn/Article/details/gtzzayrrmk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtqschzugw.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtieekwbnj.html

JS:   const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtxafhcycz.html

TS:   const PI: number = 3.14159;
来源：http://dali.tanke756.top/Article/details/gteyckqdln.html

Java: static final double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtiggnxgwg.html

Go:   const PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtvgttsehb.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtedwtzcvp.html

C#:   const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtbtysveeg.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkxhzgfq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtklxakntk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gtrdbjhomw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtgfaoldoc.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtpqdpvxhs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gtkmzyhpby.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cheryme.top/Article/details/gtykszxavf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cqqwz.cn/Article/details/gttlyxubor.html

C#:   x.GetType().Name; x is int
来源：http://dali.jiagoushi.top/Article/details/gtvjnzonld.html

[A05] 整数除法与取模
来源：http://dali.yongpay.top/Article/details/gthywbilzh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangshuangyany.cn/Article/details/gteqavykrv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtsdtdymkk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtlrusrbag.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtrpifclep.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gttewhrutk.html

Go:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gttsosfprw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtvicncjgn.html

C#:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtpgaerokr.html

[A06] 字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtmpcsskry.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gtsokgzmxp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenlongwang.top/Article/details/gtbjnwtcbt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtyusmayfy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtcdlncqck.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gtybuzjwxo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gthzvfufms.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gtdoswrvom.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hnqzz.top/Article/details/gtsyctiafc.html

[A07] 数字转字符串
来源：http://dali.nanxinkj.top/Article/details/gtmpfuzcco.html

Py:   str(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmnudfsy.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsujjnctm.html

JS:   String(42); (42).toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtqgbtdpiu.html

TS:   String(42)
来源：http://dali.tianlin.xyz/Article/details/gtmslzwirw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.vqdsnc.cn/Article/details/gteqxlbdob.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gtzivqncpk.html


<!-- 参考信息 -->