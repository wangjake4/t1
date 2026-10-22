代发 wailian999

[U61] PHP：正则
来源：http://dali.andypj.xyz/Article/details/gtbdidhsnw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gtdebpzqdf.html

[U62] PHP：日期对象
来源：http://dali.ydzc1.top/Article/details/gtzomoyxqy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.snrcjt.cn/Article/details/gtbghuryqs.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gtekttbnul.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gtbgknwgop.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gtqyjcmwaa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jiagoushi.top/Article/details/gtxgmpzihu.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gtgjwcebop.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtggubrxdu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhongyouzk.top/Article/details/gticyrfsza.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gtzawdyuzx.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtdgrompll.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtyjrsluve.html

[U68] PHP：PDO 连接
来源：http://dali.jyoumei.cn/Article/details/gturvpxkkh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsakmcaem.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gtzavjtvih.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gtwspiihhs.html

[U70] PHP：PDO 事务
来源：http://dali.gogol.net.cn/Article/details/gtyhoosamn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.iojbl.cn/Article/details/gtldqxdlnh.html

[U71] PHP：抛出异常
来源：http://dali.xylfe.cn/Article/details/gtaiekslay.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtpfjlmmdr.html

[U72] PHP：写错误日志
来源：http://dali.daxiang520.top/Article/details/gtzbtrziag.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuanzhike.top/Article/details/gtljnbxivy.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtmxarauxg.html

parse_ini_file("config.ini", true)
来源：http://dali.meibo888.top/Article/details/gtykwicawa.html

[U74] PHP：读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gttxhhjbtv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenjidiqi.icu/Article/details/gtdtjgcboj.html

[U75] PHP：依赖注入
来源：http://dali.tian-w.cn/Article/details/gtymsbkhao.html

composer require psr/container
来源：http://dali.gzhubu.top/Article/details/gtpjitdimk.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gtfrsjejyz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gtruoviebb.html

[U77] PHP：模板渲染
来源：http://dali.chenzaomai.com/Article/details/gtxrcxaxnu.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gtquajmqyf.html

[U78] PHP：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtypcxapts.html

composer require --dev phpunit/phpunit
来源：http://dali.hywenlv.cn/Article/details/gtxwqvtyrk.html

[U79] PHP：静态分析
来源：http://dali.yangfankeji.com/Article/details/gtwluskrqx.html

composer require --dev phpstan/phpstan
来源：http://dali.cashguo.top/Article/details/gteqgadvvs.html

[U80] PHP：代码规范修复
来源：http://dali.gaohongyu789.top/Article/details/gtejdizxqf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gtjyhgqnnr.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysnzicqq.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gtfdelrkrt.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gtcjiuslsg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gtjjzjpdlh.html

[U83] JS：ES Module 导入导出
来源：http://dali.feifeiyinyue.top/Article/details/gtbcuswbth.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtfhwyyhcj.html

[U84] JS：CommonJS 写法
来源：http://dali.jyoumei.cn/Article/details/gtlmkfhauo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gtrtmwlrlq.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtoxcrayuh.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtiusgpdzu.html

[U86] JS：空值合并
来源：http://dali.hammf.cn/Article/details/gtgpdpnutc.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gtsfsakjbu.html

[U87] JS：解构默认值
来源：http://dali.sxryk.cn/Article/details/gtluolulmf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gteusdtgjl.html

[U88] JS：对象展开合并
来源：http://dali.guowangkeji.top/Article/details/gtlmmkeegy.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gtyckwbuwa.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gtkifwalry.html

[...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtticddjus.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gtzrhpgusw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtlwqrgnqm.html

[U91] JS：对象键值遍历
来源：http://dali.fengsongda.top/Article/details/gtkewaqvlc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtwghizdyx.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtgddlhzui.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtnkltfvdh.html

[U93] JS：模板字符串
来源：http://dali.shuidangran.top/Article/details/gtetzbmpcq.html

`共 ${n} 条`
来源：http://dali.chenzaomai.com/Article/details/gtdcmkuwoz.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtpmcjfyts.html

const double = x => x * 2;
来源：http://dali.sxryk.cn/Article/details/gtdlxbemne.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gtxhydgeha.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gtdhbrkfvj.html

[U96] JS：async/await 与异常
来源：http://dali.shangyingyoupin.top/Article/details/gtnnjhzfeo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtwnkytqln.html

[U97] JS：并发请求
来源：http://dali.zhengqikj.top/Article/details/gtmatyzqhx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtngskdyea.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gtgbldttcc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gtzyxuujmi.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gtvunnfwcw.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gtkicegyzt.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtuxudggdm.html

document.querySelector(".item")
来源：http://dali.ppjwa.cn/Article/details/gtdfjuzovy.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gtptwjiywe.html

el.classList.toggle("active")
来源：http://dali.pycfn.com/Article/details/gtfeeythow.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gtpenuzsez.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcptxpxro.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtpoqzfdvw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtmjdwazth.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtkxeamaqa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtjknyksoz.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gtqqwfghdh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtczwsdzmk.html

[U106] JS：日期格式化
来源：http://dali.sysykeji.top/Article/details/gtuytmpfrd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtciiqkkin.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtxniaadjm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmwejpdf.html

[U108] JS：随机整数
来源：http://dali.sufxvd.cn/Article/details/gtvwkvqlmd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtwughkeod.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gtpvpradzd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gthhbcaotv.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtsixitypr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gtyqsplmbb.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtdlpfordc.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtuvimqbiw.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gtzcancgvt.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtudwgldnt.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtwhyageqb.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtaxwhweac.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gtgxtyvpby.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtoxrpftkr.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtmyxtxsqu.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtdicflikl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gtiqupfjwy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gtpqzpwjoz.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtfsphtpwb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gtnljmkwap.html

[U118] JS：开发服务器
来源：http://dali.feifeiyinyue.top/Article/details/gtnsknalpv.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtbtxgxevw.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gtqielorif.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlpewcko.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstszvynp.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gtjnoeyjtr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtoejvyfkm.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtdrzvofib.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxqrpwbma.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtsalfjjtq.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtkexrbjjl.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gtyryrywng.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtqeuifejm.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gtfmrhulfd.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gtxtejqaon.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gttqncflye.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtdqhbluca.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gtnzcwtghg.html

C .............. 30
来源：http://dali.jianghu66.top/Article/details/gtikekdcfw.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gtlpkdwwre.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtckbzviwn.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gthxulskjw.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtlndkarkf.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gtfgunkxie.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gtmsowmdud.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gteiimfjps.html

Scala .......... 10
来源：http://dali.shzxlz.cn/Article/details/gthumewecx.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtkoookctn.html

合计 ........... 2106 条
来源：http://dali.sweek.top/Article/details/gtowuxtipg.html

按章节统计：
来源：http://dali.yuxming.cn/Article/details/gtbfssfwdk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtmemihynm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtjmgrktxw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtoneofdtn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtwfsxbehh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtzptynhth.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtvnpyjqgu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtbiovdhls.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtcolaqoxx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtrmmxpatj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjctschd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtbwyjxfsk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtbyffymdt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtnfjvaqnv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtfjqcabkb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gtfdltcmmo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtbttjyuww.html

Q SQL 专题                              90
来源：http://dali.vqdsnc.cn/Article/details/gtcfgjelhm.html

R Bash 专题                             80
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhavgiwc.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gtmnfvvugt.html

T 其他语言补充                          60
来源：http://dali.aizwys.cn/Article/details/gtqejggjgt.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gtzkkdvelf.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtlyoxhjux.html

合计                                  2106 条
来源：http://dali.ydzc1.top/Article/details/gtectklfqp.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtnyjorzcf.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gttssuleyo.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtccsululj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tian-w.cn/Article/details/gtibailutz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtegaewghf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gtgtzqwrie.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gtyxasdmlx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzthdrdev.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gtbrjohbym.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gturbcoivk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gttqoqyrom.html

Common Programming Examples Cheat Book
来源：http://dali.tian-w.cn/Article/details/gtkebusqmu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtunmoiodz.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gtdmnorcpc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gtbpkobcgg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.smart0.xyz/Article/details/gtxkirnhwx.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gtbhsemeij.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangtech.top/Article/details/gtezxigcja.html

【使用说明】
来源：http://dali.feifeiyinyue.top/Article/details/gtasvbtsxb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gtwwxpsszw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gtjedlgrhd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangdashe.top/Article/details/gtldbasiag.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gtnnzuiqqk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ppjwa.cn/Article/details/gtszshmdvd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hysaishi.cn/Article/details/gtiddemlbu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gtdhvxpmnm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gtxsuxgrol.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xziqi.cn/Article/details/gteatprrau.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.fengsongda.top/Article/details/gttamqjvmg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gotoacloud.top/Article/details/gtkfslstnu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shuidangran.top/Article/details/gthxowkmxx.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtggcreqgk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gtufbpwgdd.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtaytvchnp.html

目  录
来源：http://dali.nanxuanxn.top/Article/details/gttzwiskgh.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtfrygsydz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sweek.top/Article/details/gtlhnffdjz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgxvvhwcy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtwyjhtxym.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtmqbozlzt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ppjwa.cn/Article/details/gtebwpflwq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtmvvyalgw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gthhuhkmbu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtpxcnejvq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtnxlxkkkv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtqznkawxt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtfmnzmaki.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtntycrpja.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtxjlxurht.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtjqjnhylx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ydzc1.top/Article/details/gtwnkecpyz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgwgjbeu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cashguo.top/Article/details/gtxghptjej.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtvhnuqoxh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtarpawuuy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtiitytyru.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtdtoklnsd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjlttrsku.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtpwxmharb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdvabjwbn.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gtyghzmlcc.html

Py:   print("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtxyicuzjo.html

PHP:  echo "Hello, World!";
来源：http://dali.hnqzz.top/Article/details/gtgowsalpf.html

JS:   console.log("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtkuhhrhuh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gtviubnvun.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtlssktosn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtmrkwmneb.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gtjnyigcbs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtowlzxqtd.html

[A02] 变量声明与赋值
来源：http://dali.jianghu66.top/Article/details/gtolpopqwj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsjvxxcw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtchnylnrq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtsgalcvfg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tian-w.cn/Article/details/gtgaroztjj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtlxebjjwp.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtwdwmetaa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ydzc1.top/Article/details/gthyboegll.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtciskgxog.html

[A03] 常量定义
来源：http://dali.wangdashe.top/Article/details/gtjnbmksos.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aibaodan.cn/Article/details/gtwnkpaqxr.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtxywvtagk.html

JS:   const PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtrqpxsjpe.html

TS:   const PI: number = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtpzpazcox.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdtgsgas.html

Go:   const PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gtxbaosggs.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaitlwff.html

C#:   const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtmbdaatpz.html

[A04] 判断变量类型
来源：http://dali.dashuyun.cn/Article/details/gtrfncprjx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gtusnqcqur.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakxqccjy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtdtvltssm.html

TS:   typeof x; x instanceof Date
来源：http://dali.yanxiufei.cn/Article/details/gthilpjlyq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gtkangjfej.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvlvrsnq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zdqjudy.top/Article/details/gtczxgxmcj.html

C#:   x.GetType().Name; x is int
来源：http://dali.kuanghao11.cn/Article/details/gtymmyponw.html

[A05] 整数除法与取模
来源：http://dali.fzhhl.top/Article/details/gthbbntzsw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangshuangyany.cn/Article/details/gtnokvrvta.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtxnnqetvt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gtmoimradv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gthjowfmzf.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtyoswjbif.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtdqvhpjtp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtmlaqhfia.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtxxckmvei.html

[A06] 字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtqodomhxl.html

Py:   int("42"); float("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtngctrkak.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.0kj1m.cn/Article/details/gtumkxhdoc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnqzz.top/Article/details/gtaarmsmah.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gtqwcmehwt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tian-w.cn/Article/details/gtwilyegmj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtipwmweua.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dianchejie.cn/Article/details/gtvrmbzqta.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtmycdrxov.html

[A07] 数字转字符串
来源：http://dali.jianghu66.top/Article/details/gtsfjypjhe.html

Py:   str(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtragqtiwm.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gtbnjvsdlu.html

JS:   String(42); (42).toString()
来源：http://dali.yj202588.top/Article/details/gtavscntsx.html

TS:   String(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiegwziny.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.snrcjt.cn/Article/details/gtsffitrog.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gtasfrjprg.html

Ruby: 42.to_s
来源：http://dali.guowangkeji.top/Article/details/gtligaishf.html

C#:   42.ToString()
来源：http://dali.pycfn.com/Article/details/gtpxgrcnbm.html

[A08] 取整与四舍五入
来源：http://dali.jianghu66.top/Article/details/gtupizjdgu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gttgcbtxmj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.sufxvd.cn/Article/details/gtqbqkexho.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtfywztcwo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuetiantiany.cn/Article/details/gtoixhohiu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtcurrvfdr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtiblplzxu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gtbwullvmb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtiuqlfxxv.html

[A09] 绝对值与最大最小值
来源：http://dali.cucudq.cn/Article/details/gtfheerrzw.html


<!-- 参考信息 -->