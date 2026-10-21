代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtadkwczyh.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtztekcvyt.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtrajpkbwy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcfhykqo.html

[U59] PHP：自定义排序
来源：http://dali.svipenyu.cn/Article/details/gtcweflngy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxfqnwkq.html

[U60] PHP：JSON 编解码
来源：http://dali.fengsongda.top/Article/details/gtttvyqlha.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gtogancslk.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gtrlrfyaep.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtfdjanuxz.html

[U62] PHP：日期对象
来源：http://dali.svipenyu.cn/Article/details/gthgpszevw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gtxjmnswea.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gtsgnuffsk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtimhpvnym.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gtugxpnbgb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gtzdhwubnu.html

[U65] PHP：会话
来源：http://dali.yvedp.cn/Article/details/gtvavwqont.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtvsoywlfz.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gtrejlgeqt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtmtgvwkcy.html

[U67] PHP：处理文件上传
来源：http://dali.aizwys.cn/Article/details/gtxeueetpw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.iojbl.cn/Article/details/gtlloqncrt.html

[U68] PHP：PDO 连接
来源：http://dali.zdqjudy.top/Article/details/gtcqrfgces.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuanzx.com/Article/details/gtjcnyapss.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gtcdlwjcjp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gtpcaoyrpb.html

[U70] PHP：PDO 事务
来源：http://dali.hfpthk.cn/Article/details/gtknqnmiaw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sweek.top/Article/details/gtbcwbdnhg.html

[U71] PHP：抛出异常
来源：http://dali.yvedp.cn/Article/details/gttsqvlaab.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxinkj.top/Article/details/gtgisjwnng.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gtefwwhqjq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gthyxnkkae.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gtegldeogc.html

parse_ini_file("config.ini", true)
来源：http://dali.xuetiantiany.cn/Article/details/gthnwiitvl.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtwytbvwhn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtogvwrtqq.html

[U75] PHP：依赖注入
来源：http://dali.yuxming.cn/Article/details/gtammyeesg.html

composer require psr/container
来源：http://dali.cqqwz.cn/Article/details/gtnvvjcxsx.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gtsgbydels.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtydtfppvh.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtqkwhlvak.html

composer require twig/twig
来源：http://dali.wangdashe.top/Article/details/gtyalvuuzx.html

[U78] PHP：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtijpnrebu.html

composer require --dev phpunit/phpunit
来源：http://dali.xuetiantiany.cn/Article/details/gtmumodssh.html

[U79] PHP：静态分析
来源：http://dali.zhoulong.xyz/Article/details/gticmqzlyo.html

composer require --dev phpstan/phpstan
来源：http://dali.yuanzhike.top/Article/details/gtzpgrtkyb.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gtwcnrfkmp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuxming.cn/Article/details/gtpaerhymm.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gtxjnljidv.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gtqgfgwnhh.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtuisbjgky.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtnkbrnyxi.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtmpxcxpna.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtisjijxhb.html

[U84] JS：CommonJS 写法
来源：http://dali.yj202588.top/Article/details/gtvjmbzfcy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gtdfuewfog.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gtnmwxvtuc.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gtyhyyfkdt.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtpvyylawu.html

a ?? b
来源：http://dali.cdnleiting.top/Article/details/gtvsoztsdj.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gtvsmrqpsq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yvedp.cn/Article/details/gtsalycimg.html

[U88] JS：对象展开合并
来源：http://dali.haohaochexian.top/Article/details/gtbsolxubu.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvmsjgwt.html

[U89] JS：数组去重
来源：http://dali.sufxvd.cn/Article/details/gtyhqsqkgu.html

[...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtaqahqlfn.html

[U90] JS：数字数组排序
来源：http://dali.jqgufenzy.top/Article/details/gtwkblyenk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtutyyfetv.html

[U91] JS：对象键值遍历
来源：http://dali.smart0.xyz/Article/details/gtzkjitelh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gthskfbbrt.html

[U92] JS：深拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzltniryx.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtnbpxiaku.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtnquhlrxb.html

`共 ${n} 条`
来源：http://dali.xuetiantiany.cn/Article/details/gtoocqncoo.html

[U94] JS：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtcapnoazp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtjrbjryee.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gtghingbvk.html

new Promise((resolve, reject) => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtbvzmvrge.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gtoyagjzga.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtxenuepam.html

[U97] JS：并发请求
来源：http://dali.yanxiufei.cn/Article/details/gtgkiicjsq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaconwib.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gtxtpzjxgm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtylcypwmc.html

[U99] JS：事件监听
来源：http://dali.ydzc1.top/Article/details/gtpreqlzey.html

el.addEventListener("click", e => {})
来源：http://dali.jqgufenzy.top/Article/details/gtcqtsnriu.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gtfvashrun.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gtvjydycqb.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gttmbnwtot.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gtxfzeqqti.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gtlbqznthf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtrnhwafim.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtbcooqavm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gthmgcqchb.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gtnadrosgj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtbomhbxrq.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gtalmaahbh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtjmkdxjqt.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gtiwuqfgwa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaeacokb.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtsgjnkvkt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtgrbclpsx.html

[U108] JS：随机整数
来源：http://dali.nanxuanxn.top/Article/details/gtddnzrcgx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gturdnucvy.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gtzysctuxu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtioxnioah.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gtoetngvqs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jlsjyb.cn/Article/details/gtwoqxrejc.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gtfschsugv.html

new Map(Object.entries(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtmooblfdt.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gthhesgtee.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtbafvhida.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gtgmuxrbcu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtdskzgvgt.html

[U114] JS：JSON 深比较
来源：http://dali.zhongyouzk.top/Article/details/gtkhjayowl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizdlgjqh.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtpgaaqdsz.html

crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtsemiwhic.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gtdoowencj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gtsxpoggon.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtbytxbfek.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtbhuwywwg.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gtcvlptudv.html

npm i -D vite;  npx vite
来源：http://dali.shangyingyoupin.top/Article/details/gtuqjbwper.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gtrurmtslv.html

npx vite build
来源：http://dali.c1oappe.top/Article/details/gtlxhhxjln.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtyftpcsov.html

import.meta.env.VITE_API_URL
来源：http://dali.cheryme.top/Article/details/gtktsxhcnp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyodkvong.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvsobumd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiottodxp.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtahkpgvja.html

Python ......... 252
来源：http://dali.meibo888.top/Article/details/gtbneiphnn.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gtqvscaxsy.html

JavaScript ..... 252
来源：http://dali.sweek.top/Article/details/gtzxxhctwa.html

TypeScript ..... 212
来源：http://dali.svipenyu.cn/Article/details/gtekvewuar.html

Java ........... 212
来源：http://dali.daxiang520.top/Article/details/gtfdjyoocd.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gtsnpelojw.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtjxovprhl.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtgsgrswwh.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtzhaglowj.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtjyszotuu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gtvzzbmgfh.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gtppzbhloy.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gtsrvocajm.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gtjitrdxhz.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gtvtvbsqth.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtmwcdmizl.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gtbjxtlmjw.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgayfchd.html

合计 ........... 2106 条
来源：http://dali.hywenlv.cn/Article/details/gthxkbsuih.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtzsgeceay.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtjjetdvep.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfejcsaob.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawkfwiwv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gtiasthniq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gtgnxjrgmi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtrbbblkee.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtzgmhdviy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtlxgbesag.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtkouwiupm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtyjgengwq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtlobcgndv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtzvyczoys.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtcnlgrguo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gtoidzubnf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.snrcjt.cn/Article/details/gtszxfnyjc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtqctawbsp.html

Q SQL 专题                              90
来源：http://dali.aizwys.cn/Article/details/gtehqiotav.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gtbdcawjfa.html

S C / C++ 专题                          60
来源：http://dali.pengpengdd.cyou/Article/details/gtrqjlskki.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gtmewsssgc.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gtukgghvjb.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtlkdbmrok.html

合计                                  2106 条
来源：http://dali.haohaochexian.top/Article/details/gthfrhkfof.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtrkhyrsdh.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gtiwrytfar.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtiinoqbzn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gtjnsmousi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gtryxwhtcl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenlongwang.top/Article/details/gtzdxymnny.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gtvtuxiosy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gtlthjfcvk.html

—— 文件结束 ——
来源：http://dali.xinyue.icu/Article/details/gthpwepgqd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwubwnixx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yonumen.top/Article/details/gtkbldrwxi.html

Common Programming Examples Cheat Book
来源：http://dali.zhixingplan.top/Article/details/gthvewsame.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtadmnnjch.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gtusgerojz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guannengcc.top/Article/details/gtmprwmfzn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gtstexdskk.html

SQL · Bash · C · C++
来源：http://dali.zhoulong.xyz/Article/details/gtjrsuvrik.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258.top/Article/details/gtqnuhiwtl.html

【使用说明】
来源：http://dali.cashguo.top/Article/details/gtblcixnqw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gtresanzdi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ydzc1.top/Article/details/gtpdcedcuw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fzhhl.top/Article/details/gtbayzsvve.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sufxvd.cn/Article/details/gtrfluqjpa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gtgiqamyny.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gtrqjobkch.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtbxtjcsak.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdgjefqs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gthjysjwig.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yvedp.cn/Article/details/gtdwnrltim.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gtrfeurfpw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqhptyrk.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gtleqlwnaj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gtipzkowag.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtskckogzi.html

目  录
来源：http://dali.sxryk.cn/Article/details/gtxbxpikxf.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtjhendhgz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtlrdisyrv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtqmcasgwl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gttnamzfxa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtttbmfejd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtjjeiookr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtjqmawydl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtfgeuswtl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gttoypncvq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gthqjsjkiu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtqmpctelw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtxtcpxdcn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtceixvwic.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtjocjcwot.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtskqkloyl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ivvv.top/Article/details/gtmsxzklod.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtegqeenpk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gtqnwjlbel.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccmytkkk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ybcxt.top/Article/details/gtppqrnqdy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtkubddrhs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtqtztqeia.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfisekkbj.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtwofngdxx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiieiplwc.html

[A01] Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzjqucml.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtafvucsbx.html

PHP:  echo "Hello, World!";
来源：http://dali.hfpthk.cn/Article/details/gtueqhjtgl.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gthtpikdco.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gtgljjwhaf.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtqdmveany.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.wangdashe.top/Article/details/gtsntlxxff.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gtqqkntuis.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtmcmcnjxr.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gtpomtblvx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtylnnrmxg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.aizwys.cn/Article/details/gtmarsbkxv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtsphxnyct.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gtkzxritll.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gtoagksxyd.html

Go:   name := "Alex"; age := 20
来源：http://dali.9152youxi.cn/Article/details/gtlljivfwb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pycfn.com/Article/details/gtcnvgwbnw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtammpprom.html

[A03] 常量定义
来源：http://dali.haohaochexian.top/Article/details/gthevtsiyj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yongpay.top/Article/details/gtedmmigok.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtidtxolyo.html

JS:   const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtgjwiujlf.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtchvnaxxk.html

Java: static final double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtuzzoomvm.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtwuorpdrr.html

Ruby: PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gtpfjetass.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtgmtdrmob.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gtcrujqujy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gtdezkmobg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gtwmzsosah.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtnicfdfum.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gttselqzkg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigfzy.top/Article/details/gtftqpnpok.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gtxmwmwrum.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrswqevp.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gtbhtkwcsy.html

[A05] 整数除法与取模
来源：http://dali.jinqigufen.top/Article/details/gttamojuag.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavnmwgpv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtaunnjhsh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtlfdajoix.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxjwbjil.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtrbzzxp.html

Go:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtcoffvtnt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtwheyopcv.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtijqutcec.html

[A06] 字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtwjgfntay.html

Py:   int("42"); float("3.14")
来源：http://dali.daxiang520.top/Article/details/gtoizcpqjh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkuepnbu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.smart0.xyz/Article/details/gtaqsipmoy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.bjfxy.top/Article/details/gtdvslcunc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ivvv.top/Article/details/gtrbnnncvi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fengsongda.top/Article/details/gtxdrhimhf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pycfn.com/Article/details/gtxkpoinlj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtmmthydih.html

[A07] 数字转字符串
来源：http://dali.chenzaomai.com/Article/details/gtrcutbwcc.html

Py:   str(42)
来源：http://dali.aibaodan.cn/Article/details/gtfayjonsd.html

PHP:  (string) 42; strval(42)
来源：http://dali.sysykeji.top/Article/details/gtjqkppcqq.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gtaqtwtwmf.html

TS:   String(42)
来源：http://dali.redwolf501.top/Article/details/gtuteqkxpa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sxryk.cn/Article/details/gtgwsopxwr.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gtnxqgnesf.html

Ruby: 42.to_s
来源：http://dali.feifeiyinyue.top/Article/details/gtovcwfxwo.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtjadegmtw.html

[A08] 取整与四舍五入
来源：http://dali.wangdashe.top/Article/details/gtnyaqpmbw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtdjyoksku.html


<!-- 参考信息 -->