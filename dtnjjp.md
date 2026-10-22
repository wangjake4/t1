代发 wailian999

[U65] PHP：会话
来源：http://dali.sxryk.cn/Article/details/gtmaigwfxr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtbgtzilua.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gtoygzcyxo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gtcsbcoref.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtbihzpnfw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gtlqrfvfcu.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gtoxtesgwf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aizwys.cn/Article/details/gtehdgfzll.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgufenzy.top/Article/details/gtuffjwhus.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxinkj.top/Article/details/gtpmfvnkjv.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gtscldpuoh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtztocqikr.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtunnzznwk.html

throw new RuntimeException("失败", 500);
来源：http://dali.yangfankeji.com/Article/details/gtbtyxiqbg.html

[U72] PHP：写错误日志
来源：http://dali.iojbl.cn/Article/details/gtvzdspreg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tanke756.top/Article/details/gtnfunhrql.html

[U73] PHP：读取 ini 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtzanjopmh.html

parse_ini_file("config.ini", true)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwswhrnj.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtrocugbpi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gtloieqika.html

[U75] PHP：依赖注入
来源：http://dali.cheryme.top/Article/details/gtcqrhauca.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwxhnwel.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtzntjonwo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtbyaxgzsw.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gtjynobbus.html

composer require twig/twig
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxzdtoau.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtrwwwrhev.html

composer require --dev phpunit/phpunit
来源：http://dali.xuetiantiany.cn/Article/details/gtgzugpwiz.html

[U79] PHP：静态分析
来源：http://dali.tian-w.cn/Article/details/gteivmicob.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gtutyatclj.html

[U80] PHP：代码规范修复
来源：http://dali.shzxlz.cn/Article/details/gtrofnfmds.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gtfyuwanhm.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtbhoaxudl.html

npm init -y;  npm i express
来源：http://dali.ybcxt.top/Article/details/gtxutwfixz.html

[U82] JS：package.json 脚本
来源：http://dali.ydzc1.top/Article/details/gtchrikylq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ppjwa.cn/Article/details/gtdgogkxbu.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gtomnhrfaq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gthdthveks.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gtpavmdcfb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoljewuuc.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gtlumtxjml.html

a?.b?.c
来源：http://dali.chenzaomai.com/Article/details/gtpxouzrfw.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gtkqgpjhfl.html

a ?? b
来源：http://dali.yongpay.top/Article/details/gtpmlcwlln.html

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gtemqkmkcj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtmkjqib.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcykzmyqa.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gtfpmihtjn.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gttgynikwn.html

[...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtxcatfodd.html

[U90] JS：数字数组排序
来源：http://dali.cdnleiting.top/Article/details/gtnrlczhdr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtdscbkbjx.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtthxoyqvy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhengqikj.top/Article/details/gtnssjflwm.html

[U92] JS：深拷贝
来源：http://dali.cqqwz.cn/Article/details/gtzmcuoezs.html

structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmfmjmimm.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gtsxfydavy.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gtogavkjfk.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtsmumjlia.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gttijarmzj.html

[U95] JS：Promise 包装
来源：http://dali.yj20258888.top/Article/details/gtykwtgtuf.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gtpkczjnmu.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gtqjlgkfrz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtbrtchzey.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtmepzjhyy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtwkncolyx.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gtygwemffk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquhbqpuv.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtvlexoybz.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gtpcviudjq.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gtapsyhltu.html

document.querySelector(".item")
来源：http://dali.redwolf501.top/Article/details/gtahhgwcjx.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gtxykbfqlf.html

el.classList.toggle("active")
来源：http://dali.yueranfly.top/Article/details/gtmntnfqfx.html

[U102] JS：本地存储
来源：http://dali.ybcxt.top/Article/details/gtndolciqd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jiagoushi.top/Article/details/gtjjwkpsuq.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gthpbmumgm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gtvrudofnj.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gtzpzttsbk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwkmpqwi.html

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gtyodslumx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.svipenyu.cn/Article/details/gtceyysumo.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtkxngaaye.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuanzx.com/Article/details/gtiwpewhsy.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtelgqjwjl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtevzxjhub.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtzrrpppil.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtovqjybya.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgnnawzj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtbmbfbsln.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gtvcnjgmdw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gtbrxfmeox.html

[U111] JS：对象转 Map
来源：http://dali.tianlin.xyz/Article/details/gtdattmhbz.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtnzaowguv.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gtbdzuhzrd.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtrxtspwkz.html

[U113] JS：正则替换全部
来源：http://dali.shuidangran.top/Article/details/gtkxpcfora.html

s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtjcwuigsc.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtkbyxucwn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtjbhyuqzw.html

[U115] JS：生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtdcrcibwn.html

crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtccmbgaxa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.feifeiyinyue.top/Article/details/gtigitefxj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxdpslbi.html

[U117] JS：单元测试
来源：http://dali.yj20258.top/Article/details/gtqeaonfef.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtsvcypzcn.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gtpdqjqjfr.html

npm i -D vite;  npx vite
来源：http://dali.jiagoushi.top/Article/details/gtotdbjrrt.html

[U119] JS：生产构建
来源：http://dali.xuanzx.com/Article/details/gtbgbeynmy.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gtgkxodzxk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gtlndmynpx.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunxqtavg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtszqbvlhe.html

统计汇总
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgjmereb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtywtutgxi.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gtodhndheq.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gtnrsqpdhj.html

PHP ............ 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfjwaztd.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gtkqlpmupb.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gtjjfdylmn.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gthiszwpaf.html

Go ............. 212
来源：http://dali.hammf.cn/Article/details/gtvnxwzvca.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtdximtwae.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtwllfiibg.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gtjjlcrpdv.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gtxhmdpfpj.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gtxpvcezsy.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gtajtzajbx.html

Kotlin ......... 15
来源：http://dali.kuanghao11.cn/Article/details/gtoobyrpks.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtrmsenngl.html

Lua ............ 10
来源：http://dali.0kj1m.cn/Article/details/gtrdaqjtrp.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtbosdvjqi.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gtjjzaiwyk.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtftapcuku.html

合计 ........... 2106 条
来源：http://dali.ehwqpu.com/Article/details/gtqkznnuwh.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gtpgwgiors.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtulvfdsmg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtulrpkbkk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtcruplhry.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtqtejfuee.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxuanxn.top/Article/details/gtimconvml.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gttheobmmf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtyzhldxbs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtktopdajb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtobexazjv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtitoxozqf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtmsmyvahl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtssdtryvj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtsguxugsu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtdsurabwu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gtubnxronx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtmcnemoos.html

Q SQL 专题                              90
来源：http://dali.nanxinkj.top/Article/details/gtlxvwsazc.html

R Bash 专题                             80
来源：http://dali.yueranfly.top/Article/details/gtmpcrqivw.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gtjpleklgu.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gtlxqosrvx.html

U 高频实用片段                         120
来源：http://dali.yanxiufei.cn/Article/details/gtywgyprau.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtpxohvroo.html

合计                                  2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtjwnwwomn.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtqdnboile.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gtwhsqycsm.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtoqomcijx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhoulong.xyz/Article/details/gtiutzjudu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hysaishi.cn/Article/details/gtvqwwmaqi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgfzy.top/Article/details/gtbvvrkleu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhiwuduotai.top/Article/details/gtmdofhzmp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhixingplan.top/Article/details/gtcjuqyuif.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gtwvivtecv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrptrvicj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fzhhl.top/Article/details/gtfiwoptlz.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gtgezyvoys.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtejrfqotr.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gtnmedwxhm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.fzhhl.top/Article/details/gtlwalurhu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cqqwz.cn/Article/details/gtdewmyivb.html

SQL · Bash · C · C++
来源：http://dali.nanxinkj.top/Article/details/gtqpwbqcnw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gttfydedqw.html

【使用说明】
来源：http://dali.cdnleiting.top/Article/details/gtouxycxuo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gtkaiezrrm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.bjfxy.top/Article/details/gtxhtfjfqy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ehwqpu.com/Article/details/gtiaajccib.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zycfv.cn/Article/details/gtotjjybpz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpgtzgqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gtklpkmjyz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcxbenwh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yvedp.cn/Article/details/gtjsgngdqp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fzhhl.top/Article/details/gtqofifidx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dashuyun.cn/Article/details/gtpmvjvzhe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yvedp.cn/Article/details/gtxvulxzuj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gtokxvbptf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gtwbbpzbnq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shzxlz.cn/Article/details/gtgxwpnksz.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtxprzltpi.html

目  录
来源：http://dali.gaohongyu789.top/Article/details/gtktlaefwy.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtqnbyvbck.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtngvawvrb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlopfomnl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtaklunyyj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gtwhalmdsu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hfpthk.cn/Article/details/gtyptghzga.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gtwkhpwwvh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqfmygzau.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtltvwjfez.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtmrsdkwrq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtovczrfms.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtvclmlbpb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtkdaolblt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtnkvqfxsd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtfjfrxrtj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gtegnzzsxw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtlmzuhaat.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.bjfxy.top/Article/details/gtlqfchitz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtttvcwytr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtvfhtmnjs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtijsjwwpl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlxzdbhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyxegdvee.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gtvxcnkern.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtslbvppeq.html

[A01] Hello World
来源：http://dali.meibo888.top/Article/details/gthgjeeoqi.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gttursqepp.html

PHP:  echo "Hello, World!";
来源：http://dali.yangfankeji.com/Article/details/gtdxnmvjyf.html

JS:   console.log("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtcfofozgp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gtmukurwxn.html

Java: System.out.println("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtchscrpwb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtnvmkzncx.html

Ruby: puts "Hello, World!"
来源：http://dali.hysaishi.cn/Article/details/gtrxvuidyi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtpvdyyyki.html

[A02] 变量声明与赋值
来源：http://dali.bjfxy.top/Article/details/gtlcfqajdo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhongyouzk.top/Article/details/gtwdlsfpad.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtupcrynyc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtputsalgu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.meibo888.top/Article/details/gtqpfryryi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtoyqcyrxv.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgfzy.top/Article/details/gttofanthk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gtvrcarxcc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtmebnorfn.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtepbrhfuf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ivvv.top/Article/details/gtntcjqjzz.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtoyblzmrh.html

JS:   const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gthxbelymy.html

TS:   const PI: number = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gthpclxwiw.html

Java: static final double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtqpbmumjq.html

Go:   const PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gtgmvorhad.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtjyhyjwgb.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtopwwgegg.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gtafvttmfm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.vqdsnc.cn/Article/details/gtzylpwcep.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gtwombseka.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtralwnnez.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gthdobguhe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sxryk.cn/Article/details/gtpudjyzau.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgpupiov.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gtexbefqqk.html

C#:   x.GetType().Name; x is int
来源：http://dali.aibaodan.cn/Article/details/gtyueauxcs.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gtltnoekhl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xinyue.icu/Article/details/gtrhpepxva.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gteexbfkxh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtrdpsreoh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtiijkrtbl.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtixlxrpwd.html

Go:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtjyydgdba.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtdruczbtm.html

C#:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfumqiyqz.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtzwedjeyu.html

Py:   int("42"); float("3.14")
来源：http://dali.ppjwa.cn/Article/details/gtiwqesuay.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daxiang520.top/Article/details/gtcztitgmu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gtlagoaoyr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258888.top/Article/details/gtumkqycur.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gtbbcbpnja.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gtywcooukh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zycfv.cn/Article/details/gtvfczmdcd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hfpthk.cn/Article/details/gtsjtnawkn.html

[A07] 数字转字符串
来源：http://dali.aizwys.cn/Article/details/gtatcbkzeq.html

Py:   str(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtrkuxcsvv.html

PHP:  (string) 42; strval(42)
来源：http://dali.andypj.xyz/Article/details/gtmvsojuea.html

JS:   String(42); (42).toString()
来源：http://dali.yj202588.top/Article/details/gtvjpfczlc.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gtusbbqrle.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.svipenyu.cn/Article/details/gthbmctjgz.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gtqmwzkjgk.html

Ruby: 42.to_s
来源：http://dali.yangfankeji.com/Article/details/gtsfuldiza.html

C#:   42.ToString()
来源：http://dali.sweek.top/Article/details/gthckwzwuk.html

[A08] 取整与四舍五入
来源：http://dali.yj20258888.top/Article/details/gtvoazcnnm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtqlaqekgx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cdnleiting.top/Article/details/gtswqalaqh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtvyggjpkj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.316326.xyz/Article/details/gtdbkgenbh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtildvbxns.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtziwboqlv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aizwys.cn/Article/details/gtgfywfsro.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtliafmjxf.html

[A09] 绝对值与最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtlmhijtsm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtszbbfgrt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtkahmzgsc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gttxsxtzzp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtzezimmnp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtoyohdnzb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tianlin.xyz/Article/details/gtxxgqwyrx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hywenlv.cn/Article/details/gtfjjabzml.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtmoullgal.html


<!-- 参考信息 -->