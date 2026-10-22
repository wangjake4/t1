代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gttzsfykuj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtztjzrolk.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gtwasabxjp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gteqqhzvlc.html

[U61] PHP：正则
来源：http://dali.gotoacloud.top/Article/details/gtjcgybdyv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtoiysvizn.html

[U62] PHP：日期对象
来源：http://dali.hammf.cn/Article/details/gtcbatukyb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gtpnokpjcj.html

[U63] PHP：文件读写
来源：http://dali.xuanzx.com/Article/details/gtrxszoowf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xinyue.icu/Article/details/gtwbsmxmmc.html

[U64] PHP：目录遍历
来源：http://dali.ivvv.top/Article/details/gtisbrajiw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoifvarjh.html

[U65] PHP：会话
来源：http://dali.guowangkeji.top/Article/details/gtmeskfscp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtaynhqwga.html

[U66] PHP：设置 Cookie
来源：http://dali.haohaochexian.top/Article/details/gttyfojtlx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtrvayirrx.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gtvcwqfsip.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gtealeoolr.html

[U68] PHP：PDO 连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticgcgfxs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhixingplan.top/Article/details/gtjfqaqdau.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtastimrvo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gtrnyeaaow.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gttymwalrr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gtxywfkpjd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtqbygykfr.html

throw new RuntimeException("失败", 500);
来源：http://dali.yangfankeji.com/Article/details/gthcnzybnq.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gtsxawcxwg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvupyjhoe.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gtizmezdlm.html

parse_ini_file("config.ini", true)
来源：http://dali.vqdsnc.cn/Article/details/gtrfmprqjb.html

[U74] PHP：读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtculktfdk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yanxiufei.cn/Article/details/gtzaftkddl.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gtjnylvfkl.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gtzpsqsisz.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gttqoiqnim.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxuanxn.top/Article/details/gtdlebvjpd.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsblqyfjc.html

composer require twig/twig
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoijcwml.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gthhuprntk.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gthxlhhmjk.html

[U79] PHP：静态分析
来源：http://dali.yangfankeji.com/Article/details/gtdmipcjer.html

composer require --dev phpstan/phpstan
来源：http://dali.zdqjudy.top/Article/details/gtpucrtydz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gtmfevhkmk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yvedp.cn/Article/details/gtmaxamqgz.html

[U81] JS：初始化项目
来源：http://dali.daxiang520.top/Article/details/gtupwqjige.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gtmxnscqgf.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gtpdwngnqq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhixingplan.top/Article/details/gtyvdeidcc.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gtzmvuuzhp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtyeghmvtx.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gthlcgzjml.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hfpthk.cn/Article/details/gtxmeuevzg.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gtvkzcvcph.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gtlppbmjfr.html

[U86] JS：空值合并
来源：http://dali.gotoacloud.top/Article/details/gtxqffjwam.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgledqhj.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtealeepug.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gteqkllhsm.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtgwtogaoa.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtatbxtqrr.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gtvrtpphqb.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhtgsnzb.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gtfmprnarg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtfrgfxfat.html

[U91] JS：对象键值遍历
来源：http://dali.aibaodan.cn/Article/details/gtfswfupqo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gtuwvwsdyv.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtussrawxl.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtrdlvitgp.html

[U93] JS：模板字符串
来源：http://dali.ydzc1.top/Article/details/gtrtnvbxer.html

`共 ${n} 条`
来源：http://dali.chenlongwang.top/Article/details/gtbuynnggj.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtealwipdv.html

const double = x => x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtdmcrxriw.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gtqmsrejni.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gtvmdlbcst.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gtqratadbo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gthouaiujd.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtchzblrva.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gttdxkavsa.html

[U98] JS：fetch 带 JSON
来源：http://dali.xylfe.cn/Article/details/gtznydqiyk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yonumen.top/Article/details/gtnfnliugt.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gtycuztvpk.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlogsssvo.html

[U100] JS：DOM 查询
来源：http://dali.sweek.top/Article/details/gtqrfwvczq.html

document.querySelector(".item")
来源：http://dali.hfpthk.cn/Article/details/gthgbrbenc.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gtloljtlpz.html

el.classList.toggle("active")
来源：http://dali.iojbl.cn/Article/details/gtwanupbym.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmblxbezx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuxming.cn/Article/details/gtnkgnuauf.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtvyinqunl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnlhhpkp.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gtsrjgfqiu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjsjxfgc.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtlqlmwpnd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gthatpajqi.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtklrglgbx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gttzrvaiik.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtljhhvlob.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtpiylrcag.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gtviiimynm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gtpjaqfeuy.html

[U109] JS：数组分组
来源：http://dali.zhongyouzk.top/Article/details/gtdjgdqlzy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtjwqboryp.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gtuakwcehd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtzvzvokgk.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtlfduydia.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtawbwmlmg.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtxlefuyrt.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtkykbvxxd.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gtvzbqxvyn.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtnvksjlhq.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmckcqpmb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtipkebbjz.html

[U115] JS：生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtmohftdtl.html

crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gteucdcujf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gtupagsbph.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gtfscxbpie.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gtoxrerjpx.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gtywfyqhgb.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gtvjzeeksh.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisibcofh.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gtixrkcjdr.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gtsxrpplpl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yvedp.cn/Article/details/gtimeekncs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gttpxzuhsl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxnlabfbf.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtgmszhfcp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthfuzchby.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gtqgommsdf.html

Python ......... 252
来源：http://dali.snrcjt.cn/Article/details/gtorfehzwm.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gteddhvvxi.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtamisicak.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gtuexeaclr.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtmrxanatp.html

Go ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawrflwqy.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gthackbvnr.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtjnagpixm.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gteuixcgzq.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtfhjiccws.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtsbwpuonj.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gtpjubhvcg.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtdpvrnenp.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtkhgspwds.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gttfdutxjq.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtacfbeght.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gtdwlnfcnd.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtoosyidmy.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gttqnistva.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gtoazjheda.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gthpbdliut.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtzcmbkdzi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gticfsusey.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtuphdqdtq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtpfaqpqyx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtoohfspik.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtzxhkbgzz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gtjsmrpxlc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtmyoagzfw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucyadwyv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtqiiycggi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtkjnqtqgy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtcnldfycl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gttekrdxod.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zycfv.cn/Article/details/gtscoedfdh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gttmdqbcum.html

Q SQL 专题                              90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfmlzuby.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gtkcurzpgc.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gthxoxejdh.html

T 其他语言补充                          60
来源：http://dali.shzxlz.cn/Article/details/gtxduaebru.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gtawoeukcu.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gttarkvqsb.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gtarhubkry.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtoxwtzdig.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtbyiiqbbx.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtyasvbkfp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jyoumei.cn/Article/details/gtzhvyahrn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gtdsmcaudd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gtyuitxtxs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gtnwvhnuyi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zycfv.cn/Article/details/gthkgluwkx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gtdrmxyvng.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlbwkidki.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xylfe.cn/Article/details/gtsnfektwn.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gtxwcrxadr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjairfewh.html

【收录内容】
来源：http://dali.ybcxt.top/Article/details/gtoiexdqci.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.kuanghao11.cn/Article/details/gtzaaskrec.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gaohongyu789.top/Article/details/gtienefpem.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gtybwqjypq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hywenlv.cn/Article/details/gtfpvrzvqj.html

【使用说明】
来源：http://dali.xinyue.icu/Article/details/gtvdzmqnio.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslcldauz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwvoqazi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sysykeji.top/Article/details/gtkitaeauj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ppjwa.cn/Article/details/gtihbwfuwj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gtypdaorne.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gtogsbdxpf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xinyue.icu/Article/details/gtezgzjsyu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gturpjwzoa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.smart0.xyz/Article/details/gtumebndwy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewveutsx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gtidqosutl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdetsmbqa.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gtrsnmkrme.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gtyvbxrepy.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtikjvxanp.html

目  录
来源：http://dali.redwolf501.top/Article/details/gtpifzjwmz.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtcnyeqgej.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gtgjrmbgvc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtppayzhjd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtjjawxmyj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtwpxjrbew.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sweek.top/Article/details/gtknpnysyl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtivphdsyc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gturapnttu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtyxtblsvp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtnybnqyft.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtzxfdyomg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtaejiqspq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gttuyqrjrx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtuchkervm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj202588.top/Article/details/gtbubtfwwe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnvgdcar.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gthfrtjalo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gtpyvxbcin.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmntazymc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tianlin.xyz/Article/details/gtwplrowte.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtmleqhbor.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtidutczgn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwupiogjz.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gtoqxrlikb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqakqkwm.html

[A01] Hello World
来源：http://dali.mhx1999.top/Article/details/gtmusbuexe.html

Py:   print("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvpeemeq.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigufen.top/Article/details/gturqqjpvo.html

JS:   console.log("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtqnjgwvye.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yangfankeji.com/Article/details/gtgcxeawqd.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gttvthpglz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gttxqhchdm.html

Ruby: puts "Hello, World!"
来源：http://dali.aizwys.cn/Article/details/gttdmrbngd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtmtcwvwyy.html

[A02] 变量声明与赋值
来源：http://dali.snrcjt.cn/Article/details/gtcasobfej.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dashuyun.cn/Article/details/gtkzzdktme.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtgpzgkqdi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtbdklwdcr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yueranfly.top/Article/details/gtubrozwlz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gtaslgdnaw.html

Go:   name := "Alex"; age := 20
来源：http://dali.haohaochexian.top/Article/details/gtrcopivdb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuanzhike.top/Article/details/gtipnmcpww.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtbkseepxc.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gthylwkkwz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gtddeikahr.html

PHP:  const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtrhueybza.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtphtbepgl.html

TS:   const PI: number = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtvddbyave.html

Java: static final double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtmowqbxqg.html

Go:   const PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gtkeswlcob.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gthbzzeaxt.html

C#:   const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gteohdsxpq.html

[A04] 判断变量类型
来源：http://dali.cdnleiting.top/Article/details/gtobmptbyf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.c1oappe.top/Article/details/gtwqlygujy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpsmkfwy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtpaugytkj.html

TS:   typeof x; x instanceof Date
来源：http://dali.c1oappe.top/Article/details/gtovlgmlps.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gzhubu.top/Article/details/gtauxgchfy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zdqjudy.top/Article/details/gtisjhguvw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gtajavjcbo.html

C#:   x.GetType().Name; x is int
来源：http://dali.cdnleiting.top/Article/details/gtctjlqkue.html

[A05] 整数除法与取模
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrroqaob.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhengqikj.top/Article/details/gtxehntfsf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtlviljxvz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtlgysblpv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtshhqtuhl.html

Java: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtvqsphwya.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtmonxlzua.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtxwglmupd.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtjbeiuxul.html

[A06] 字符串转数字
来源：http://dali.meibo888.top/Article/details/gtnnqbwdml.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gtexqmobdr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aibaodan.cn/Article/details/gtrtmprdki.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gtcmfqlice.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aizwys.cn/Article/details/gtsttmgpku.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sweek.top/Article/details/gtidlmgtna.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gttwovmbjq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgufenzy.top/Article/details/gtdozltzaz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.snrcjt.cn/Article/details/gtxcafiwgw.html

[A07] 数字转字符串
来源：http://dali.jyoumei.cn/Article/details/gtzoerfbwf.html

Py:   str(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtcguakhns.html

PHP:  (string) 42; strval(42)
来源：http://dali.fzhhl.top/Article/details/gteadoggmn.html

JS:   String(42); (42).toString()
来源：http://dali.cdnleiting.top/Article/details/gtcbdcndhq.html

TS:   String(42)
来源：http://dali.yj20258888.top/Article/details/gtydqgmmfu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hammf.cn/Article/details/gtznbmhuqf.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258888.top/Article/details/gtndahokwb.html

Ruby: 42.to_s
来源：http://dali.smart0.xyz/Article/details/gtrypxpsni.html

C#:   42.ToString()
来源：http://dali.shzxlz.cn/Article/details/gtnudkemoe.html

[A08] 取整与四舍五入
来源：http://dali.yonumen.top/Article/details/gtxoipkjcl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtuhhulatl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yongpay.top/Article/details/gtzbtbusym.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gttqsrtmew.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifriryyr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggqxiami.html


<!-- 参考信息 -->