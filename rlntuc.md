代发 wailian999

[U61] PHP：正则
来源：http://dali.yueranfly.top/Article/details/gtzcmxppjp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpahtpwnr.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaptfubf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.iojbl.cn/Article/details/gtaeccmpat.html

[U63] PHP：文件读写
来源：http://dali.cashguo.top/Article/details/gtvctkxycu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gtrzoqoott.html

[U64] PHP：目录遍历
来源：http://dali.xylfe.cn/Article/details/gtiqlfhnkh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gtudovnzgk.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtynzlmyks.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtbbsudwic.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gtjafndqwr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gaohongyu789.top/Article/details/gtsnutytvt.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gtrejgyxns.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gtszmhccpa.html

[U68] PHP：PDO 连接
来源：http://dali.mhx1999.top/Article/details/gtkpycezex.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gtrmfexeem.html

[U69] PHP：PDO 预处理
来源：http://dali.ybcxt.top/Article/details/gtkmdsujfw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gtnjgzbooo.html

[U70] PHP：PDO 事务
来源：http://dali.wangdashe.top/Article/details/gtvuyydpbe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guowangkeji.top/Article/details/gtlagqktol.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtxrzyloqf.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gttbbakgcu.html

[U72] PHP：写错误日志
来源：http://dali.daria6918.cn/Article/details/gtqfndwsaa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnxiangtu.top/Article/details/gtwyympdli.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtriogtgev.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gtfcvhhcqw.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtuowztyvn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtsbjmbgye.html

[U75] PHP：依赖注入
来源：http://dali.jinqigufen.top/Article/details/gtfklgukdu.html

composer require psr/container
来源：http://dali.aizwys.cn/Article/details/gtthlacmzo.html

[U76] PHP：简单路由
来源：http://dali.sufxvd.cn/Article/details/gtrfvuvfri.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.svipenyu.cn/Article/details/gtbiavcwgv.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtzklkovqg.html

composer require twig/twig
来源：http://dali.zdqjudy.top/Article/details/gtuwqwxeln.html

[U78] PHP：单元测试
来源：http://dali.andypj.xyz/Article/details/gteddrqbsd.html

composer require --dev phpunit/phpunit
来源：http://dali.ydzc1.top/Article/details/gtdbjsdvfl.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gttiaqensv.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gtkskinmkx.html

[U80] PHP：代码规范修复
来源：http://dali.bjfxy.top/Article/details/gteglhoiyf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtehcrbjag.html

[U81] JS：初始化项目
来源：http://dali.birdmap.top/Article/details/gtknokwzsp.html

npm init -y;  npm i express
来源：http://dali.zdqjudy.top/Article/details/gtnbpkbqqa.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gtttyrurxg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xziqi.cn/Article/details/gtqpqnhqrt.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgtlfwgb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtgglykiki.html

[U84] JS：CommonJS 写法
来源：http://dali.gogol.net.cn/Article/details/gtwfbjkmuq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.c1oappe.top/Article/details/gtpgqgnwkr.html

[U85] JS：可选链
来源：http://dali.daria6918.cn/Article/details/gtkmusuegt.html

a?.b?.c
来源：http://dali.yanxiufei.cn/Article/details/gttjkvxvhx.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtphxxggem.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gtmvbertbc.html

[U87] JS：解构默认值
来源：http://dali.jqgfzy.top/Article/details/gtodabjqss.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gtwdsozemv.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gtxobrfsxi.html

{ ...a, ...b }
来源：http://dali.yanxiufei.cn/Article/details/gtleazcrrc.html

[U89] JS：数组去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqcgijzl.html

[...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtzlbhpqzt.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gtpvgvuzut.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtfenvvssb.html

[U91] JS：对象键值遍历
来源：http://dali.chenlongwang.top/Article/details/gttnszcupr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gtdbnuwkex.html

[U92] JS：深拷贝
来源：http://dali.andypj.xyz/Article/details/gtshfogzdr.html

structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtggowvegx.html

[U93] JS：模板字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtvreyvbch.html

`共 ${n} 条`
来源：http://dali.ybcxt.top/Article/details/gtqtwabfrc.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtvshncmqc.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmvmphof.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtkoynhror.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtgfqqbrdb.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gtdpqssirw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gttlbdagcr.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gtfkutkhas.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigyfdznq.html

[U98] JS：fetch 带 JSON
来源：http://dali.aibaodan.cn/Article/details/gtmehroauc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenjidiqi.icu/Article/details/gtqxfnitwc.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtbwhoepli.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtthkpadon.html

[U100] JS：DOM 查询
来源：http://dali.pycfn.com/Article/details/gtnyuxszha.html

document.querySelector(".item")
来源：http://dali.zhongyouzk.top/Article/details/gthlfimpgq.html

[U101] JS：classList 操作
来源：http://dali.sxryk.cn/Article/details/gtgoyvwixb.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtlsjnpgtn.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gtjzlswbwb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gtelrbpsdq.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gtaalwxjvi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gtqvofzaqn.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpvrbxmi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtuxupcfzz.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gtsejrizon.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtfidnyyei.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtqvzciimi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.meibo888.top/Article/details/gtqmrqkehs.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtmqstioft.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtgzbfniam.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtehpthymy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangdashe.top/Article/details/gtkqrichiq.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gttmdinjec.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtkghfixqv.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gtvsnwtntv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.haohaochexian.top/Article/details/gtqnnmhsyq.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gtmeytxgif.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gtpasmmnei.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gttefdirat.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtodgwxwtu.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gtvuoqttbv.html

s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtigbfgaox.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gtophjizkt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtpuzdvtec.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtrktjuote.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtzqlwcysq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gtzbzkqvom.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gttxtiolno.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gtnerecbbl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gtoznkdewm.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtbejnrett.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gtzkmsxqrw.html

[U119] JS：生产构建
来源：http://dali.wangshuangyany.cn/Article/details/gtasckatag.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gthfsensxs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yueranfly.top/Article/details/gtdhkutayk.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gthcvsgsqf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjzdkndwm.html

统计汇总
来源：http://dali.daria6918.cn/Article/details/gtrncnlxvy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqdegcwfw.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gtgpaxvsqq.html

Python ......... 252
来源：http://dali.c1oappe.top/Article/details/gtcnswgnvk.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gtzxbwodjo.html

JavaScript ..... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtpedfywnb.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gtvdckskdq.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gtgxigoiba.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gtngmfehwo.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtjahgqbxv.html

C# ............. 212
来源：http://dali.bjfxy.top/Article/details/gtzagmonfr.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gtmteorgrx.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gtouupgtpz.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gtnyzervya.html

Bash ........... 80
来源：http://dali.yj20258.top/Article/details/gtnapzrura.html

Kotlin ......... 15
来源：http://dali.yuanzhike.top/Article/details/gtotpdnxcu.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtavlwwaoz.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtwdskdoud.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gtbompkhul.html

Scala .......... 10
来源：http://dali.svipenyu.cn/Article/details/gtsfwpprvg.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtemlsqtvo.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gtepocptbb.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtzgawuzma.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtxleznrcf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtqvfleqxp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtsmsozueu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtrqcvndxe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqvkibbz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtbpoklzga.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtjpwdopdl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtqzngothp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtsnrxxgek.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gtcwaxyxnk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtsvexfrim.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtlrjhqxqa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtobnvzmhy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gtogepncbw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gtrhwblsdj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtnthtwocx.html

Q SQL 专题                              90
来源：http://dali.fengsongda.top/Article/details/gtwuexsbdv.html

R Bash 专题                             80
来源：http://dali.cucudq.cn/Article/details/gtaybvtnwv.html

S C / C++ 专题                          60
来源：http://dali.kuanghao11.cn/Article/details/gtbdzpkfrs.html

T 其他语言补充                          60
来源：http://dali.ybcxt.top/Article/details/gtanorvnfk.html

U 高频实用片段                         120
来源：http://dali.dashuyun.cn/Article/details/gtmlqtmzaq.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtqaafmjhd.html

合计                                  2106 条
来源：http://dali.quarkkingdee.top/Article/details/gtfmsravwx.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtmqujosez.html

使用提醒
来源：http://dali.vqdsnc.cn/Article/details/gtppmdfxyr.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtrjrlrzde.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gtqanryjcw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fzhhl.top/Article/details/gtzggzdhje.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gtquaheqhw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gaohongyu789.top/Article/details/gtbrxmmubd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gtoepxdceg.html

—— 文件结束 ——
来源：http://dali.yuanzhike.top/Article/details/gttphxsxvy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthzfslhvz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtpchbdfmn.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gtbvzzfscv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzgoxxdvu.html

【收录内容】
来源：http://dali.316326.xyz/Article/details/gtoeokpahi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangshuangyany.cn/Article/details/gtkjfhbnug.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pycfn.com/Article/details/gtefjzsrvi.html

SQL · Bash · C · C++
来源：http://dali.pengpengdd.cyou/Article/details/gtwnuxcjew.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sysykeji.top/Article/details/gtpdssniaa.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gtwqflqcrd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gtbndusiqe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hongshengwenyu.top/Article/details/gthoihyxdz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.9152youxi.cn/Article/details/gtllpoyqud.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzdbwxwq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenzaomai.com/Article/details/gtekpvyojf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gtqszbyzzg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gtpzagyzgb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gtclltnrgf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhengqikj.top/Article/details/gtwjwupnva.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtqvglhvfe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sxryk.cn/Article/details/gtqtdfhlmw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shzxlz.cn/Article/details/gtqmwtufod.html

【文件统计】
来源：http://dali.gaohongyu789.top/Article/details/gtfukspzie.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gtxpcjilxs.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtegyzvwtm.html

目  录
来源：http://dali.yvedp.cn/Article/details/gtmrjrolub.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtmqdzuiin.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtcinazogo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gticqbiqoe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtvcekbqqi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gtqrkjdinr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.birdmap.top/Article/details/gtjdrqiiqu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gthqpjgqgx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtorwtgydn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtmijnmmdu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtddzayawf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtzxmwsdij.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtjmnvakec.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtpobafexf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtansahvqk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtybepgyju.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtirovorsq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtylfxxruw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gtwgwwtivo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtgexxhqfd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yueranfly.top/Article/details/gtxfhqovkj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtaaxlvkme.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtsqfiqegy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxejbywje.html

A. 基础语法与类型
来源：http://dali.ppjwa.cn/Article/details/gtgekspuvh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmxgjyawz.html

[A01] Hello World
来源：http://dali.yj20258888.top/Article/details/gtjlnsgrot.html

Py:   print("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtvfrmploz.html

PHP:  echo "Hello, World!";
来源：http://dali.feifeiyinyue.top/Article/details/gtkmdcqpzx.html

JS:   console.log("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtnjibilhw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gtocwsjxtc.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtjelblpeh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gtlqqvziet.html

Ruby: puts "Hello, World!"
来源：http://dali.snrcjt.cn/Article/details/gtonmwcofb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtjvggintk.html

[A02] 变量声明与赋值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfphqnfrw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gtvfhqckqp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gtmfhaarwg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtyhfwscsw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenlongwang.top/Article/details/gtdnqtbipk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gterbaflsk.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gtrgcxttlv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.9152youxi.cn/Article/details/gtzcmvtgdm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gthnxgummi.html

[A03] 常量定义
来源：http://dali.zhoulong.xyz/Article/details/gtssrecsmp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yvedp.cn/Article/details/gtuwwqrzxy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdwexzwh.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtuxniniwx.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtftbxvfwy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtqpklcaom.html

Go:   const PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtgislruea.html

Ruby: PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gteswgvjdk.html

C#:   const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtdekqmokt.html

[A04] 判断变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtewpfnamx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnqzz.top/Article/details/gtlxaamnsg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gtojudqbjd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtwflcwzei.html

TS:   typeof x; x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtdqfldcxi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gteqdoxatz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gtctmziktw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yonumen.top/Article/details/gtlgljbmob.html

C#:   x.GetType().Name; x is int
来源：http://dali.iojbl.cn/Article/details/gtfgoiczuj.html

[A05] 整数除法与取模
来源：http://dali.havefunace.top/Article/details/gtveryxyqc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gtzoeecqyh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gttscrqvqw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtmvkqoapu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtlaygovae.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqiqwqbk.html

Go:   7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtjcspjnxv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtpsheriin.html

C#:   7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtkatohdlm.html

[A06] 字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtmhyqtzpv.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gtgkxsphye.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtlutarnzw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yvedp.cn/Article/details/gtyltptmkb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sweek.top/Article/details/gtksodmghk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.birdmap.top/Article/details/gtdussalyw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gtvalbubyq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tanke756.top/Article/details/gtfjwbhpab.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gtmhuivdzy.html

[A07] 数字转字符串
来源：http://dali.cheryme.top/Article/details/gtqxhlbzix.html

Py:   str(42)
来源：http://dali.svipenyu.cn/Article/details/gtzlrbyehi.html

PHP:  (string) 42; strval(42)
来源：http://dali.fengsongda.top/Article/details/gtszfyyhql.html

JS:   String(42); (42).toString()
来源：http://dali.quarkkingdee.top/Article/details/gtkpcvirgw.html

TS:   String(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtiaesalek.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgufenzy.top/Article/details/gtidqxbeia.html

Go:   strconv.Itoa(42)
来源：http://dali.bjfxy.top/Article/details/gtzjzyunjl.html

Ruby: 42.to_s
来源：http://dali.yanxiufei.cn/Article/details/gtprvbkhxp.html

C#:   42.ToString()
来源：http://dali.birdmap.top/Article/details/gtcoqaqsmu.html

[A08] 取整与四舍五入
来源：http://dali.andypj.xyz/Article/details/gtajdrkeug.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gttirjqids.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigfzy.top/Article/details/gtmpgomrdy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtakddwerc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gtaascucjl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtawydndfg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtawpolpux.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhiwuduotai.top/Article/details/gtphvxsepw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtbtczgbvp.html

[A09] 绝对值与最大最小值
来源：http://dali.zycfv.cn/Article/details/gtobcvdzum.html


<!-- 参考信息 -->