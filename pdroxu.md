代发 wailian999

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtaesptgdy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtdedlwakr.html

[U64] PHP：目录遍历
来源：http://dali.shzxlz.cn/Article/details/gtrypztywg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.316326.xyz/Article/details/gtbddsgaba.html

[U65] PHP：会话
来源：http://dali.jinqigfzy.top/Article/details/gtjedqibgp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtckdzaojh.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gtdecsmzmc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.kuanghao11.cn/Article/details/gtdutiycsk.html

[U67] PHP：处理文件上传
来源：http://dali.tian-w.cn/Article/details/gtvhqbakvg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gtvjyqieii.html

[U68] PHP：PDO 连接
来源：http://dali.yongpay.top/Article/details/gtlqasmsmp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.iojbl.cn/Article/details/gtjdsqbecr.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gtlfmwghsi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pycfn.com/Article/details/gtbqeidrnb.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gtrzctgfsf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtvepcdlxw.html

[U71] PHP：抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtgjuljqig.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtnvecfwbb.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtgnqjmdux.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gtfgxhjyog.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gtgkeopzvm.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtboikdlie.html

[U74] PHP：读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqzgruql.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gtviopasjh.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtikejndch.html

composer require psr/container
来源：http://dali.sysykeji.top/Article/details/gtioidmdew.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gtisiatskg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.vqdsnc.cn/Article/details/gtbzukvsce.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtreiwqgrz.html

composer require twig/twig
来源：http://dali.zhengqikj.top/Article/details/gtjjwudbeq.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gtrgfcksfl.html

composer require --dev phpunit/phpunit
来源：http://dali.chenzaomai.com/Article/details/gtsmghojoj.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gtgielbxfq.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gtbedkwgdx.html

[U80] PHP：代码规范修复
来源：http://dali.tianlin.xyz/Article/details/gtckqdnykq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gtpqidwpkx.html

[U81] JS：初始化项目
来源：http://dali.feifeiyinyue.top/Article/details/gtcjaxmvub.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtezdeqwfs.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gtdlhpkcmx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gtbkicpftj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gtepeeqeip.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtwbxlnnhu.html

[U84] JS：CommonJS 写法
来源：http://dali.dashuyun.cn/Article/details/gtwnfblfpt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fzhhl.top/Article/details/gtlnnuakmm.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gtsgzrcoov.html

a?.b?.c
来源：http://dali.yvedp.cn/Article/details/gtzcpaqzvm.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gtfclunbji.html

a ?? b
来源：http://dali.vqdsnc.cn/Article/details/gtdayowksb.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gtdrnenqvp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtlwioyfmy.html

[U88] JS：对象展开合并
来源：http://dali.cucudq.cn/Article/details/gtyfgfgcmf.html

{ ...a, ...b }
来源：http://dali.wangshuangyany.cn/Article/details/gtiurixbpt.html

[U89] JS：数组去重
来源：http://dali.guowangkeji.top/Article/details/gtotimdsjg.html

[...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtodkvmuod.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gtwermsbnj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtkkreunan.html

[U91] JS：对象键值遍历
来源：http://dali.316326.xyz/Article/details/gtppxnpaxi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gtwciblpza.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtadszmtgj.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtfpfgfagz.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gtkpyqhrxm.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gtjcfxflsf.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtuigbnokt.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtqjkdgdww.html

[U95] JS：Promise 包装
来源：http://dali.xinyue.icu/Article/details/gtgabvowkk.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gtnppbsrwt.html

[U96] JS：async/await 与异常
来源：http://dali.fzhhl.top/Article/details/gttanhmyou.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtospgigob.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtfrzpmsbw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtbuhealvz.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtievuioyv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.kuanghao11.cn/Article/details/gtuxvzyehc.html

[U99] JS：事件监听
来源：http://dali.ehwqpu.com/Article/details/gtnjhvhyri.html

el.addEventListener("click", e => {})
来源：http://dali.wangdashe.top/Article/details/gtijqbtkdu.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gtcufybobp.html

document.querySelector(".item")
来源：http://dali.nanxinkj.top/Article/details/gtingmfobu.html

[U101] JS：classList 操作
来源：http://dali.nanxuanxn.top/Article/details/gtfbobbctz.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtntssauwn.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gtdplqawux.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hywenlv.cn/Article/details/gtaeslcptj.html

[U103] JS：定时器
来源：http://dali.tanke756.top/Article/details/gtndktlwcb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gtibtimzbh.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gthlwigdwu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtgtwshzpl.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gtchnbfrho.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtmshfggsl.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtxxwkrixj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gtdfdvstyo.html

[U107] JS：数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtwkmfgyxe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtxwkciaan.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gtvihsjeac.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gtcesxecgs.html

[U109] JS：数组分组
来源：http://dali.xinyue.icu/Article/details/gtdemvxbwo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtigfqtfdq.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtcuszbnns.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtcubyhjjw.html

[U111] JS：对象转 Map
来源：http://dali.shuidangran.top/Article/details/gtsrklulwo.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gtzpyzdxsz.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gtwpwtjypp.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtvofejmbg.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gtovvpkuwu.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtggvvtdxy.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gtpmsubkdz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtioybmspc.html

[U115] JS：生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtqqmbknxj.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtjftueudy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gtacfqkqnm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtymihvtgj.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gtybwrgdpy.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gtoixycyfo.html

[U118] JS：开发服务器
来源：http://dali.fengsongda.top/Article/details/gtgfxzwxcq.html

npm i -D vite;  npx vite
来源：http://dali.daxiang520.top/Article/details/gtshnvndtf.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gteywnlomi.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazxatidm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gtmzvfoqxd.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtflphofuz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgyftbcqg.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gtyhdweklr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyxwimzi.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gtilxdmlqm.html

Python ......... 252
来源：http://dali.dianchejie.cn/Article/details/gtytcnhlkm.html

PHP ............ 252
来源：http://dali.mhx1999.top/Article/details/gtizyevwya.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gtvxrghmvb.html

TypeScript ..... 212
来源：http://dali.c1oappe.top/Article/details/gtmjedgbqe.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtggphfvsl.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtltqvgxwt.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtucwymrmu.html

C# ............. 212
来源：http://dali.nwbrower.top/Article/details/gtjhfhowjl.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gtxvivbubk.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gtwufazkks.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gtwpppcsdx.html

Bash ........... 80
来源：http://dali.jqgfzy.top/Article/details/gtxngplrry.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtyboplmrr.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gtizgaltzp.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gtqbpbgdmj.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtkdtssglv.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gttcfxqzbq.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtlzygkswh.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gtnfwqyrwb.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtobmijlmh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtjbuwsfjh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtnevxcofz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtdddgsvku.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtikgireps.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gtbarfrwfg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtfvxgkeyv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtimeglftq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gthuvgmejd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiurqdrj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzufrnkcm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtwavtchij.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtbvegryyu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtbchsvnoi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gtgdnlanvm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gtjvubrbon.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtxtrzeytf.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gtdwxqvnba.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gtdwgmekcl.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtzumwhfcz.html

T 其他语言补充                          60
来源：http://dali.0kj1m.cn/Article/details/gtyxodpcfm.html

U 高频实用片段                         120
来源：http://dali.jinqigufen.top/Article/details/gttcncpzsw.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtwwnpvucd.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gtrqllhouv.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtrvpqilem.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtahyzspvq.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtlohumkdr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gtnzyyfxju.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gtqhkgqssv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gtvhriirsl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinghuilouyu.cn/Article/details/gtitybmhcp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ybcxt.top/Article/details/gtrnjvbwzl.html

—— 文件结束 ——
来源：http://dali.ppjwa.cn/Article/details/gtdqclitaf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbnvxitey.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gtxqdzgiwa.html

Common Programming Examples Cheat Book
来源：http://dali.xuanzx.com/Article/details/gtadipsijm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqwicywcu.html

【收录内容】
来源：http://dali.yj20258888.top/Article/details/gtyzwesvuu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hfpthk.cn/Article/details/gtyqfwkpzg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hywenlv.cn/Article/details/gtgjmrfyfk.html

SQL · Bash · C · C++
来源：http://dali.smart0.xyz/Article/details/gtloedjmey.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gtcdwqbwkz.html

【使用说明】
来源：http://dali.sweek.top/Article/details/gtkdcfzvmh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sufxvd.cn/Article/details/gtolesqzye.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj202588.top/Article/details/gtxtpzcbii.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.iojbl.cn/Article/details/gtqsnucbwy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gteizuaqrh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sufxvd.cn/Article/details/gtzhcgdyjm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gtpzvqwujw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.svipenyu.cn/Article/details/gtxtvhadtz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shangyingyoupin.top/Article/details/gtcnejmlos.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtlnryqvtq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtubbdncjl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pycfn.com/Article/details/gtcthkpzgz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.andypj.xyz/Article/details/gteisqsvyh.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtfurnobeo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gtfylhgrpf.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtngjhhfhd.html

目  录
来源：http://dali.hnqzz.top/Article/details/gtieglnhzk.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtftwfertm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gtqizfbfbd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtawsmufpe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtypofmvlz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwuhfzdc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gtxkboxtac.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gtkchkympk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtxyjllfhh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtgnlktzum.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtjowbndxu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtzkrxneck.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtadkyqfin.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtbhjttvee.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtxcftxbza.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtmmklskmu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cucudq.cn/Article/details/gtjzbpflyh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtaqjsbyyu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxuanxn.top/Article/details/gtduatfsan.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtmbnrqdgg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtxypnphfd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtfoxyzxyl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtzqitjdpc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmupdfxkt.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gtgeazesdv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsnbakujz.html

[A01] Hello World
来源：http://dali.hfpthk.cn/Article/details/gtemsgxfwc.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjnbjkmg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gtztlkpyhd.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtlhxfhebg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gtkomaxlna.html

Java: System.out.println("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtgzipdlyp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtyerxqouf.html

Ruby: puts "Hello, World!"
来源：http://dali.cucudq.cn/Article/details/gttomkxewy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtpzzzjuax.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gtedqdjlns.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hysaishi.cn/Article/details/gtvxtwehdb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.c1oappe.top/Article/details/gtvdcgpaqa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gtveayurig.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gtlaslbwjn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtqpfesopv.html

Go:   name := "Alex"; age := 20
来源：http://dali.gotoacloud.top/Article/details/gtcezohfer.html

Ruby: name = "Alex"; age = 20
来源：http://dali.snrcjt.cn/Article/details/gtjlbanjek.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gtkbggfavl.html

[A03] 常量定义
来源：http://dali.jqgufenzy.top/Article/details/gtlkjrdxtn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.feifeiyinyue.top/Article/details/gtuignpupy.html

PHP:  const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtmwfmqawj.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtidgqtwdx.html

TS:   const PI: number = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtuyqyuenz.html

Java: static final double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtyuvjclbx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gttorcvjzg.html

Ruby: PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gtrhvkhiwl.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gttrzlsmgn.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gtlgbdtegq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.redwolf501.top/Article/details/gtasyrefid.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.c1oappe.top/Article/details/gthiukowry.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtuvadfbla.html

TS:   typeof x; x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtwikcymmy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigfzy.top/Article/details/gtlguvmqzp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtzhcehhab.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjngatay.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnqzz.top/Article/details/gtkcvtjpqm.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtmypjtnlg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxuanxn.top/Article/details/gtwkimvflc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtehisepuc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtepdbawza.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtbtlhmtjb.html

Java: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtrtifsmpf.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtghkfxeym.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtnvzjbcdu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtareduflv.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtkleevizk.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdtacmqj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gthyedfpcy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gtclvnkqna.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nwbrower.top/Article/details/gtgqolgwcg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtkfnoyqrg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pycfn.com/Article/details/gtvjywbmvl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gthqbftcxt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtivrghfih.html

[A07] 数字转字符串
来源：http://dali.zycfv.cn/Article/details/gtdqvzjxpj.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gtzwynwurk.html

PHP:  (string) 42; strval(42)
来源：http://dali.sufxvd.cn/Article/details/gtyslirfba.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtbdstnnzf.html

TS:   String(42)
来源：http://dali.gotoacloud.top/Article/details/gtekogrisb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxuanxn.top/Article/details/gtxrkstzui.html

Go:   strconv.Itoa(42)
来源：http://dali.kuanghao11.cn/Article/details/gtwwhxhgzn.html

Ruby: 42.to_s
来源：http://dali.c1oappe.top/Article/details/gtyyrwqxbs.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gtqduucmnd.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gtkdkbhpdv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtywsofqna.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfoapukg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtkgufsiad.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwcydzcb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtgyxgtfgv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtxrpisqcj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gtgtoxtryo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtcbaqgdhc.html

[A09] 绝对值与最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtohrytmaw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtrextvisl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtxqetlulr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtimuqhxkz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtgaqlrpyo.html


<!-- 参考信息 -->