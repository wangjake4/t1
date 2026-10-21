代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtaygrtsye.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtxuiycotp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gtoosluijo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gtsyfeyjfm.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gtahixrysj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtkwdkhsnx.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtuvrlnbca.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gtilckwfjs.html

[U63] PHP：文件读写
来源：http://dali.shuidangran.top/Article/details/gtiatewmba.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gtkdoxoycw.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gtttsqzvfj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfiwtlqp.html

[U65] PHP：会话
来源：http://dali.chenlongwang.top/Article/details/gtaytfmssf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtvmdqkxua.html

[U66] PHP：设置 Cookie
来源：http://dali.jianghu66.top/Article/details/gtvuldslgb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sxryk.cn/Article/details/gtthhdxvvu.html

[U67] PHP：处理文件上传
来源：http://dali.xinyue.icu/Article/details/gtqbhvfoze.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gtwanbahgn.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtumxrlxjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gzhubu.top/Article/details/gtmhhkcybh.html

[U69] PHP：PDO 预处理
来源：http://dali.fzhhl.top/Article/details/gtafzahupy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtlubuhjcn.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gtgpuqdubz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.9152youxi.cn/Article/details/gttbfuembu.html

[U71] PHP：抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtbvjgplsv.html

throw new RuntimeException("失败", 500);
来源：http://dali.guowangkeji.top/Article/details/gtiyfaqitx.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gtohpzpcpv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fengsongda.top/Article/details/gtbeknrxic.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gtluqtwncz.html

parse_ini_file("config.ini", true)
来源：http://dali.meibo888.top/Article/details/gttqvmpqwv.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtmbalbjvk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pycfn.com/Article/details/gtfqmqvhcs.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gtbhykvdah.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtnlsjcoxi.html

[U76] PHP：简单路由
来源：http://dali.yj202588.top/Article/details/gtzcfzthxw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hysaishi.cn/Article/details/gtahqudwht.html

[U77] PHP：模板渲染
来源：http://dali.fengsongda.top/Article/details/gtytyqjzkf.html

composer require twig/twig
来源：http://dali.jianghu66.top/Article/details/gtvxtztugv.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gttftbszcq.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gtroaqdqrm.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gtthrnnkcm.html

composer require --dev phpstan/phpstan
来源：http://dali.yj202588.top/Article/details/gtyzfbftcu.html

[U80] PHP：代码规范修复
来源：http://dali.shuidangran.top/Article/details/gtbcwgsuon.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gtccdydtfl.html

[U81] JS：初始化项目
来源：http://dali.nanxuanxn.top/Article/details/gtmyeobisq.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gtsjjyoayr.html

[U82] JS：package.json 脚本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcsmxvfq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hfpthk.cn/Article/details/gtwqgdqiys.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenjidiqi.icu/Article/details/gtghjaosbd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtkhdfyplj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtfbaitqlm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gtncdesusm.html

[U85] JS：可选链
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzihguetw.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gtmwshgqeg.html

[U86] JS：空值合并
来源：http://dali.pengpengdd.cyou/Article/details/gtatsjhrvw.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gtnsycmoqz.html

[U87] JS：解构默认值
来源：http://dali.svipenyu.cn/Article/details/gtqbldccyg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvrbmwwj.html

[U88] JS：对象展开合并
来源：http://dali.cqqwz.cn/Article/details/gtavuloyzz.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gtdfofmmmj.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gturkzhbha.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtunesacud.html

[U90] JS：数字数组排序
来源：http://dali.jinqigfzy.top/Article/details/gtwgzchcgl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtlikbcoel.html

[U91] JS：对象键值遍历
来源：http://dali.gotoacloud.top/Article/details/gtvptlorvw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtpcsqmxuo.html

[U92] JS：深拷贝
来源：http://dali.sweek.top/Article/details/gtpomudxdc.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gteeacbfjm.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtwrsqrsmw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gtviqafrms.html

[U94] JS：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtyvtvzftg.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtixkwurfn.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gtozcbzjqo.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtrcdkozxh.html

[U96] JS：async/await 与异常
来源：http://dali.316326.xyz/Article/details/gtvdxgstnx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtfqqbcktg.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtyujegafz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtzabcvvyo.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gtcmljnesh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yueranfly.top/Article/details/gtihvnmfdu.html

[U99] JS：事件监听
来源：http://dali.hfpthk.cn/Article/details/gtnrscfimc.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gtorsgzweq.html

[U100] JS：DOM 查询
来源：http://dali.hammf.cn/Article/details/gtdydopivt.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtxnqkzifn.html

[U101] JS：classList 操作
来源：http://dali.c1oappe.top/Article/details/gtoeegfilw.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gtoosgzknz.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtchlwlbdt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtaxbvdfqd.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gtjhufesft.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvzshdff.html

[U104] JS：防抖
来源：http://dali.jyoumei.cn/Article/details/gtozwtcorl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtqnlmbsui.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gtkcvyvsyx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtqypqalht.html

[U106] JS：日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gthgjgczdf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gtjngirbmw.html

[U107] JS：数字千分位
来源：http://dali.ppjwa.cn/Article/details/gthhouqygz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtdruzmadq.html

[U108] JS：随机整数
来源：http://dali.chenjidiqi.icu/Article/details/gtqolgxrqk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nwbrower.top/Article/details/gtiigyzugr.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gtdnfkeuox.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtudvtrdsi.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gtqgbduydz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gtlzvynsip.html

[U111] JS：对象转 Map
来源：http://dali.hywenlv.cn/Article/details/gtlnsnhzqe.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpquuaprp.html

[U112] JS：字符串补位
来源：http://dali.yanxiufei.cn/Article/details/gtvsccvmgx.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtqtzdbley.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gtqgcrbobc.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtbpsyjhvo.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtkelctcdb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtohqonvqq.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gtxxdjehjh.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtrqqosfcv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aizwys.cn/Article/details/gtcrwrmzyi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.havefunace.top/Article/details/gtxiwwylyh.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtaawsonym.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gtuqpwjgto.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gtcwtigxyc.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gtmbqgfmpm.html

[U119] JS：生产构建
来源：http://dali.tanke756.top/Article/details/gtknjptcwy.html

npx vite build
来源：http://dali.sysykeji.top/Article/details/gtkpjfnggc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gtylkhzjfv.html

import.meta.env.VITE_API_URL
来源：http://dali.chenlongwang.top/Article/details/gtzkhsbqtl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnhnchirs.html

统计汇总
来源：http://dali.xziqi.cn/Article/details/gtdjcaypxr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkygrfmyd.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtjyjomruf.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gtpqyvggei.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjpcnfyk.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtqoxvptth.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gtadlemhkx.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtalewzhlx.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtfnqwpybg.html

Ruby ........... 212
来源：http://dali.fengsongda.top/Article/details/gtdtdbcqkz.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtnixkbirs.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gtvfbzxbyh.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gtkcygiudy.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtivsbmufi.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtblewodlm.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdkdhbxn.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtlmaeotaf.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gtocmwskyd.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gthjwlfcvm.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gtoirekssg.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtvhjseprc.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gtymtqtvbs.html

按章节统计：
来源：http://dali.mhx1999.top/Article/details/gtfaajuasn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtuylwdrhf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtjwkwclyd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gttkhzevct.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtptqkcscn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gtmjqskgjb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlthhexqr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtuqtfckwe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtfyaswutf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtwxyznnwf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtwwbkykul.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtbubchwir.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfshishf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyaunton.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gthlhjroyc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtxfzqufis.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtmzbznore.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtnduoxzmr.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gtlqjppuga.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gtjslbuvcg.html

T 其他语言补充                          60
来源：http://dali.redwolf501.top/Article/details/gtwandwjsa.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gtjzdfwvub.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtflzjshsb.html

合计                                  2106 条
来源：http://dali.zhengqikj.top/Article/details/gtcxgvpolb.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtokqliliy.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gtbfrpzvaj.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtjgyqpjvd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnxiangtu.top/Article/details/gtqeoexyix.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtnhhlbvfa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj202588.top/Article/details/gtdlalplma.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gtuajczgtb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigfzy.top/Article/details/gtbepxzple.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowevyvex.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsuyujfhi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gtpozussyr.html

Common Programming Examples Cheat Book
来源：http://dali.yuxming.cn/Article/details/gtykrnbhkb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnycbidfi.html

【收录内容】
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzbkzbnq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.316326.xyz/Article/details/gtomizshzq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yueranfly.top/Article/details/gtusinnmmh.html

SQL · Bash · C · C++
来源：http://dali.guannengcc.top/Article/details/gtsvfrjpxi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tian-w.cn/Article/details/gtqfqosfea.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gtqtsttzzr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuxming.cn/Article/details/gtwbgkoifa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangkeji.top/Article/details/gturhbjgov.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sysykeji.top/Article/details/gtoiohoeub.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.bjfxy.top/Article/details/gtuuyspegt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gtltmbdwrk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guowangkeji.top/Article/details/gtdejnqwss.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gtrbazueol.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtrjrpgepb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.tianlin.xyz/Article/details/gtqwcxzezu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrfgrzso.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhongyouzk.top/Article/details/gthahbtqho.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gtxqjoviqz.html

【文件统计】
来源：http://dali.guowangkeji.top/Article/details/gtfxsgflfz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gtonrodygh.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gttyvsbzlq.html

目  录
来源：http://dali.havefunace.top/Article/details/gtvcoakuko.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtvoaittrr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtvvcostir.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtcujibmbb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtjlpklkzi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gteuzbugfu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gtnxtnqhbl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtukdezbyx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtjbfrpurv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gtjyrpieks.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtoiscojnw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwcjzwen.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtxqwmhrvl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtlalcedlz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtfdjdikeu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoowmuau.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cucudq.cn/Article/details/gtbklengkg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtixjarkmk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gtsvyredai.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtvwejbnfe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gtltjrsara.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtkhogvipg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtldtxubyi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwobruen.html

A. 基础语法与类型
来源：http://dali.jianghu66.top/Article/details/gtourikltn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyzjsoeyc.html

[A01] Hello World
来源：http://dali.xuanzx.com/Article/details/gtgfiahojl.html

Py:   print("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gtparjtqkj.html

PHP:  echo "Hello, World!";
来源：http://dali.jianghu66.top/Article/details/gtmdfueyuo.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtghrbdhxw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sweek.top/Article/details/gtvjllkmjc.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtsjxqebiw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtfxkhwtly.html

Ruby: puts "Hello, World!"
来源：http://dali.shuidangran.top/Article/details/gtvwezcluh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gtfvqczits.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gtzykqlgqq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tianlin.xyz/Article/details/gtabaarzje.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gtldlhmlwg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aizwys.cn/Article/details/gtrojslyfb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtzkmoglsg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtvehhknfp.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gtbcmipcwk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.0kj1m.cn/Article/details/gtzliqskrv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtxbnmcgkb.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtfszreofq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtnvgzoutt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtygatksmg.html

JS:   const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtanhclxxu.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtmdoozwpr.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtsfyxpicv.html

Go:   const PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtdwbswboq.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtlptaszdt.html

C#:   const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtpbyczjuf.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gtnhlfwsma.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jiagoushi.top/Article/details/gtsnlzqgis.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tianlin.xyz/Article/details/gtexexcnzu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gtrcpaoskh.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gtvwymbzdd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cashguo.top/Article/details/gtqtjugsai.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sufxvd.cn/Article/details/gtwnnzsncj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xziqi.cn/Article/details/gtyqjwxtji.html

C#:   x.GetType().Name; x is int
来源：http://dali.hywenlv.cn/Article/details/gtsbzljesp.html

[A05] 整数除法与取模
来源：http://dali.haohaochexian.top/Article/details/gtntzennfa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sxryk.cn/Article/details/gtzblphxve.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtwvpqfvlx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtyhpjhhdx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtvqcesxey.html

Java: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtgvsrlglp.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtltxbokow.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gthmgsxobw.html

C#:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtosjiigco.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtodpwvjap.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtvjdqovnv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cqqwz.cn/Article/details/gtfjjxtavx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.redwolf501.top/Article/details/gtyemyrwze.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gtplrdzgqy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gtiqwetnto.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigfzy.top/Article/details/gthokxtzpz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhongyouzk.top/Article/details/gtlrfcgrvp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtducopjhe.html

[A07] 数字转字符串
来源：http://dali.sysykeji.top/Article/details/gtytqethul.html

Py:   str(42)
来源：http://dali.zycfv.cn/Article/details/gtgotwxuhr.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdkmknxm.html

JS:   String(42); (42).toString()
来源：http://dali.svipenyu.cn/Article/details/gtwtqmksat.html

TS:   String(42)
来源：http://dali.birdmap.top/Article/details/gtoptuvxpu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gtzwmfqcxd.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gtfffbybwl.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gtwrbzfxql.html

C#:   42.ToString()
来源：http://dali.zhixingplan.top/Article/details/gtgsyrkpgw.html

[A08] 取整与四舍五入
来源：http://dali.wangshuangyany.cn/Article/details/gtjwjlhjve.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtpwyqdonj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cqqwz.cn/Article/details/gtfylzzpqb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtjgcxfabu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gtcqjdczxi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtuwtjfmno.html


<!-- 参考信息 -->