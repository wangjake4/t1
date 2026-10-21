代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.cashguo.top/Article/details/gtednxfmkx.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gtvjldpglb.html

[U54] PHP：空安全调用
来源：http://dali.kuanghao11.cn/Article/details/gtpemomvjt.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gttrrpmqzt.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtantojyxi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gtdulxnomt.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gtpzupyjxk.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtqsubbjpv.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtirpmcscq.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gtwhktbyot.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gtvpbpaext.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhixingplan.top/Article/details/gtetdjqyhh.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gtijktxmwi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtnfwapalo.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gtxujpnwkk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtgryskueo.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gtyzybvykf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtbxhwuzxq.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gtlbmltndr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gtkwtetmjn.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiosapph.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.andypj.xyz/Article/details/gtyhncdgho.html

[U64] PHP：目录遍历
来源：http://dali.gotoacloud.top/Article/details/gthmsehqgz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtnjacfnyh.html

[U65] PHP：会话
来源：http://dali.sysykeji.top/Article/details/gtrojczyrj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gthaxahitd.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtfccrnbhy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gtxowcceel.html

[U67] PHP：处理文件上传
来源：http://dali.fzhhl.top/Article/details/gttmisjgmi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtoroojjln.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gtifeqlsdj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtotdiolwq.html

[U69] PHP：PDO 预处理
来源：http://dali.wangdashe.top/Article/details/gthzieropx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopdrgnau.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gtckvtzqig.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhoulong.xyz/Article/details/gtwfyguuzg.html

[U71] PHP：抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtofzpqcsy.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtlgtgqqcv.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gtfuzkrxrg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gtsfomrmbz.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtxuzivdgz.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtfuaafuud.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtolhipghx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkocdsimz.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gtxujntbod.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjnbvljx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gtncfjzylv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtncpyxgsm.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gtbcecbgia.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxqpjeui.html

[U78] PHP：单元测试
来源：http://dali.wangdashe.top/Article/details/gtekmthgqq.html

composer require --dev phpunit/phpunit
来源：http://dali.jinqigfzy.top/Article/details/gtfmqsswig.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gtjvyzxpbw.html

composer require --dev phpstan/phpstan
来源：http://dali.redwolf501.top/Article/details/gtxpvnhvdx.html

[U80] PHP：代码规范修复
来源：http://dali.cqqwz.cn/Article/details/gtvxfccwuu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gttswqjvfn.html

[U81] JS：初始化项目
来源：http://dali.zhiwuduotai.top/Article/details/gtkjgzjgvy.html

npm init -y;  npm i express
来源：http://dali.daxiang520.top/Article/details/gtmomrcjlt.html

[U82] JS：package.json 脚本
来源：http://dali.hywenlv.cn/Article/details/gtiichsoni.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hongshengwenyu.top/Article/details/gtonvpdjrs.html

[U83] JS：ES Module 导入导出
来源：http://dali.dashuyun.cn/Article/details/gtaqronghu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtyhkohsta.html

[U84] JS：CommonJS 写法
来源：http://dali.ehwqpu.com/Article/details/gthidymxmu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gtuyxkaxfj.html

[U85] JS：可选链
来源：http://dali.hongshengwenyu.top/Article/details/gtcccabnrw.html

a?.b?.c
来源：http://dali.ehwqpu.com/Article/details/gtqrmjexlu.html

[U86] JS：空值合并
来源：http://dali.hnqzz.top/Article/details/gtvcgsclof.html

a ?? b
来源：http://dali.yvedp.cn/Article/details/gtvhijueay.html

[U87] JS：解构默认值
来源：http://dali.ivvv.top/Article/details/gtanmoryzs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gtnfvinzqf.html

[U88] JS：对象展开合并
来源：http://dali.shangyingyoupin.top/Article/details/gtdivirasp.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gtakqszuza.html

[U89] JS：数组去重
来源：http://dali.nanxuanxn.top/Article/details/gteecxzxif.html

[...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtiamtrsqt.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gtsnraljmo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtihjxwbea.html

[U91] JS：对象键值遍历
来源：http://dali.andypj.xyz/Article/details/gtkqrvqyjm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gtrvdzifwu.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtuueaubhp.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmpzrzcgm.html

[U93] JS：模板字符串
来源：http://dali.bjfxy.top/Article/details/gthbobpnom.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gtdiwsqolc.html

[U94] JS：箭头函数
来源：http://dali.ybcxt.top/Article/details/gtyxglufiz.html

const double = x => x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjnfphbw.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gtcnyjhkpf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gteexuqzlj.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtelpofqve.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtgoucijrq.html

[U97] JS：并发请求
来源：http://dali.shzxlz.cn/Article/details/gtebueofei.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtpphvdiqm.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gttyuseike.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtsbtobhsc.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gtcyrhsohx.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gtxsfuadnd.html

[U100] JS：DOM 查询
来源：http://dali.ybcxt.top/Article/details/gtzspnkkbf.html

document.querySelector(".item")
来源：http://dali.havefunace.top/Article/details/gtmlhmuhts.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gticiahdtx.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvohdngx.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gtpgrwucqv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtebuaelhp.html

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsgbtugu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtzasuasps.html

[U104] JS：防抖
来源：http://dali.snrcjt.cn/Article/details/gtkscugddo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtzgsvxrcx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtabjfyyde.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtrqqumqlv.html

[U106] JS：日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtohtjunzj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwkrpzri.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gteldpsooy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtapxailal.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gtqcdrfhnj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gtysgkimvy.html

[U109] JS：数组分组
来源：http://dali.dashuyun.cn/Article/details/gtggfbefue.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtldnwkmzz.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsjldzpj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtjmbsshnh.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gtdopgnysc.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gtlhwnztse.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gtctfbjhqc.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gttcngwzfi.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gtzspoehar.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtjpylnxib.html

[U114] JS：JSON 深比较
来源：http://dali.gzhubu.top/Article/details/gtrcaeghsg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtcwnyerew.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtgdzwkxxz.html

crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtdycqecab.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtylepzqfq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gtdhgatqgc.html

[U117] JS：单元测试
来源：http://dali.0kj1m.cn/Article/details/gtvhpryajh.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gtwdcykpjc.html

[U118] JS：开发服务器
来源：http://dali.feifeiyinyue.top/Article/details/gtohxtdwkz.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtmnszuhqz.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gtryakigsw.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpqaczbl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gtsacfmvdp.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gtwcuzgqsk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtiwhxfoxv.html

统计汇总
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevptupbw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwykkcirp.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gtrmpbqyzp.html

Python ......... 252
来源：http://dali.ppjwa.cn/Article/details/gtdyieuvfi.html

PHP ............ 252
来源：http://dali.daxiang520.top/Article/details/gtikkrjhmk.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtzabagori.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtlpvxplqa.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtmthidomz.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gtwkihzlte.html

Ruby ........... 212
来源：http://dali.cucudq.cn/Article/details/gtkejayiuq.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtipegcfkd.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtousfsegr.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtdgawpxab.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtvresjpgc.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gtxamlydfn.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gtsyslcdmd.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gtyszyhwyv.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gtxlvatvpl.html

Perl ........... 10
来源：http://dali.tanke756.top/Article/details/gtvsbptmal.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gtlespuojg.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtzpecffqz.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtrlxjlqli.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gthuodgdah.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtiielvjjx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtkoymxdcl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtvlarndqn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtaqglback.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtytjcuzis.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtdtxvupxi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtxexrxlsb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvdrpesc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtakniwjjv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gtexpvpeto.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtfmsqmype.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtsxjhardk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtciaeyriv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtpphjhvcm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenlongwang.top/Article/details/gtyxwfhvjg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtbdkhjpio.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gtdubfgvey.html

R Bash 专题                             80
来源：http://dali.mhx1999.top/Article/details/gtjqxnlbdd.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtverrhigi.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gthbgdmdis.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtiycajecp.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtgfetnmla.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gtuiqukpfq.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtrzehbfkr.html

使用提醒
来源：http://dali.yonumen.top/Article/details/gtqhlbbzit.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtiuhiffus.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gtvvgdhqup.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.kuanghao11.cn/Article/details/gtsngywthy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenlongwang.top/Article/details/gtyrwkqyvc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gtvktzodda.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jlsjyb.cn/Article/details/gtrrlzakcf.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmpejqrz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtplztuhnw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.redwolf501.top/Article/details/gtebihhsez.html

Common Programming Examples Cheat Book
来源：http://dali.kuanghao11.cn/Article/details/gtoeuilzdk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrikxdtkp.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtuwgaofqg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gtnchjwlmf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daria6918.cn/Article/details/gtxdcxgzaw.html

SQL · Bash · C · C++
来源：http://dali.yvedp.cn/Article/details/gtnvsszwlj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jiagoushi.top/Article/details/gtwatfctyf.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gtjiwtsrrz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.kuanghao11.cn/Article/details/gtfcuvzzug.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ehwqpu.com/Article/details/gtvhnhedja.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gtyelseznj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtoxsrdzpt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtoujsdbbr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyipfczed.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtfoencktd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtqtfujuuh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zycfv.cn/Article/details/gtjmvkmnnt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgfzy.top/Article/details/gtoakfaisn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hongshengwenyu.top/Article/details/gtkwzgdfbk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenzaomai.com/Article/details/gtjzhjnglf.html

【文件统计】
来源：http://dali.pengpengdd.cyou/Article/details/gtbprleznu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gtjaqonlhh.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtrjetidgc.html

目  录
来源：http://dali.aibaodan.cn/Article/details/gtnhmcvztt.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtukllzovp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtkzgovkqs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtiztgqsbc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtdfkucgqe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gtqrudaeos.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gtcmptvqdb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtwragnifu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtmdnlbefl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nwbrower.top/Article/details/gtgeudlfth.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtbrajiyae.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gtnxttwbeo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtbuclzivm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtcsmqjmzj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtavvxjeuw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtualjrylm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aibaodan.cn/Article/details/gtxrzhimpz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtcsmtmvci.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gtneqomecu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xziqi.cn/Article/details/gtzrxtoydi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aizwys.cn/Article/details/gtylrrtsrc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtvjvywojf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtggbsspvg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttikmshax.html

A. 基础语法与类型
来源：http://dali.gotoacloud.top/Article/details/gtkbncydan.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnumesvdz.html

[A01] Hello World
来源：http://dali.0kj1m.cn/Article/details/gtkwyxcndb.html

Py:   print("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gtdrjeeazo.html

PHP:  echo "Hello, World!";
来源：http://dali.aizwys.cn/Article/details/gtgyksgyho.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkvxmniy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gtuhanznyk.html

Java: System.out.println("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtstkjvtxn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gtrkbubxlq.html

Ruby: puts "Hello, World!"
来源：http://dali.hfpthk.cn/Article/details/gthujavoek.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtpvbcfjar.html

[A02] 变量声明与赋值
来源：http://dali.316326.xyz/Article/details/gtlqvvlseh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtuzceibzo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xylfe.cn/Article/details/gtocgzccho.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtkcnjufdw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtskwfjhim.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtpdpikgzc.html

Go:   name := "Alex"; age := 20
来源：http://dali.havefunace.top/Article/details/gtqjiuhxzr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.quarkkingdee.top/Article/details/gteiyrckoh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gtfexxqwvf.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gtmdjqzfit.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guowangkeji.top/Article/details/gtpiztgbxq.html

PHP:  const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gthvwjclob.html

JS:   const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtmancdmuo.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtwukkkahz.html

Java: static final double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtcfpzvlbt.html

Go:   const PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtwpxumvzr.html

Ruby: PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gthhkdqfwp.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtkhhnbfow.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpbznmgj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pengpengdd.cyou/Article/details/gtkfpzheci.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesgldnoj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtsuxghnfm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gtwsfyzktn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pycfn.com/Article/details/gtukfnbxxg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtgmklqlzw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gtopkppfjt.html

C#:   x.GetType().Name; x is int
来源：http://dali.daxiang520.top/Article/details/gtfwvtfudy.html

[A05] 整数除法与取模
来源：http://dali.snrcjt.cn/Article/details/gthddeamjy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaxiwsub.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtvgvkfhfk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtpjponage.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtlabamegb.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtsnbghdwn.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtxeybuvwo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtwdtdilsr.html

C#:   7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtcvggjjyk.html

[A06] 字符串转数字
来源：http://dali.sysykeji.top/Article/details/gthouheslf.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtikmhrpin.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzmjgfeh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtehzaczgd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnqzz.top/Article/details/gtjxkgkxtq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.bjfxy.top/Article/details/gthgkspslu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pycfn.com/Article/details/gtgphslury.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gtjdoanuzk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtduzcrhol.html

[A07] 数字转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gthomusvkf.html

Py:   str(42)
来源：http://dali.kuanghao11.cn/Article/details/gtqkrzlnwb.html

PHP:  (string) 42; strval(42)
来源：http://dali.yongpay.top/Article/details/gtlmmhabcx.html


<!-- 参考信息 -->