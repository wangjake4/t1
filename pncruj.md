代发 wailian999

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gtttvtlnuz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtzknpzduf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbnhjoof.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gtqpofexzb.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gtcsvbrsae.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gtutfzbizs.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gtgvsjkpmj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtvflwmftg.html

[U69] PHP：PDO 预处理
来源：http://dali.svipenyu.cn/Article/details/gtnxggzveo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtbfgaxusd.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gtwfaqwyqg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pycfn.com/Article/details/gtywcwpxcw.html

[U71] PHP：抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtrqnolhvj.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtdnqkworv.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gtgrtobaya.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258888.top/Article/details/gtabernens.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtebqbynxv.html

parse_ini_file("config.ini", true)
来源：http://dali.fzhhl.top/Article/details/gtzfjeyoik.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjflpsva.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gtliylsboc.html

[U75] PHP：依赖注入
来源：http://dali.shuidangran.top/Article/details/gtuoyyptre.html

composer require psr/container
来源：http://dali.jinqigfzy.top/Article/details/gtxbsulhvg.html

[U76] PHP：简单路由
来源：http://dali.cheryme.top/Article/details/gtetaseaoo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gtgvcqqysd.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gtsuscyege.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gtipeioejh.html

[U78] PHP：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtcosyhgvm.html

composer require --dev phpunit/phpunit
来源：http://dali.tanke756.top/Article/details/gtclbfyyfj.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gtvavvfqfw.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gtlltwiora.html

[U80] PHP：代码规范修复
来源：http://dali.zhixingplan.top/Article/details/gtprwqithm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.kuanghao11.cn/Article/details/gtdycbkyrs.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtnxcdjmzc.html

npm init -y;  npm i express
来源：http://dali.tian-w.cn/Article/details/gttrnizden.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gtbqnwmknt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenzaomai.com/Article/details/gtooeuxluj.html

[U83] JS：ES Module 导入导出
来源：http://dali.daxiang520.top/Article/details/gtugeghoto.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtllyqnnqp.html

[U84] JS：CommonJS 写法
来源：http://dali.jiagoushi.top/Article/details/gtuashswjh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxvcuirs.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gtlmixfien.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gtktkxtrqt.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtizxcvuuw.html

a ?? b
来源：http://dali.xinyue.icu/Article/details/gtqmmkvbzk.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtukhjryis.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yonumen.top/Article/details/gtlzuwldgn.html

[U88] JS：对象展开合并
来源：http://dali.xinyue.icu/Article/details/gtcgtkzljg.html

{ ...a, ...b }
来源：http://dali.zycfv.cn/Article/details/gtgjrxgyye.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gtyqeeiggu.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gttfwzdqmw.html

[U90] JS：数字数组排序
来源：http://dali.dianchejie.cn/Article/details/gtvijyytmy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtphnqcjtt.html

[U91] JS：对象键值遍历
来源：http://dali.cheryme.top/Article/details/gtqyrodiam.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtdagsqsbd.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gtefffhovu.html

structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gttcsnpjxu.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtpobgkzyq.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gtjgbkogbo.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtmtqfvvwu.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtkajaglcl.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngbywjdi.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtppnsjdzp.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtcpqwskxd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkamyebi.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gtqlfpoidf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtgohsbcwa.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuanzhike.top/Article/details/gtoqzvnrpp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstlbsraa.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtybzspfio.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtdozfhptb.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gtrpapykkd.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gtzrjuwfyr.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtxirvxsrd.html

el.classList.toggle("active")
来源：http://dali.yanxiufei.cn/Article/details/gtbsluckrl.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtluoakeza.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gtesqolgxh.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtpayackzq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gtuygbanyp.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gtrlappzwz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtfbtqfddi.html

[U105] JS：节流
来源：http://dali.jiagoushi.top/Article/details/gtfbyawybu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqajltsj.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gtrkjrwyle.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gtvnskbqup.html

[U107] JS：数字千分位
来源：http://dali.ydzc1.top/Article/details/gtcexsjmpy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtfvuhkuhp.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtnuacfuym.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtesmsucrk.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtpwepzzku.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtfsqhqnju.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gtvfhxmyki.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gteuesxkxg.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjteroew.html

new Map(Object.entries(obj))
来源：http://dali.dianchejie.cn/Article/details/gtwrucghqr.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gtiznpiviv.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtevssdpts.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtsjiafbwp.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtrxyzmjoa.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtxbxrnirk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtpyopwnjh.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtdtqoxhel.html

crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtequusvac.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gtnjacpwzx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gtmoleyrjs.html

[U117] JS：单元测试
来源：http://dali.ivvv.top/Article/details/gtdsdkcmfl.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gthlteqopd.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gtdlroxyna.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtrpivyvgq.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtujfbrcsa.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gtfaskqraf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtwgawwcro.html

import.meta.env.VITE_API_URL
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchhsijfq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyugcrlbj.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtusmuajtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtuxopauxe.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gtuyfmiecw.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gtmjuaiybk.html

PHP ............ 252
来源：http://dali.hnxiangtu.top/Article/details/gtnspaovnw.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gtojlfkxgk.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgriuzkh.html

Java ........... 212
来源：http://dali.andypj.xyz/Article/details/gtxkdwgopl.html

Go ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuulalhmz.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtpqyihrcm.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtbwmqrozk.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gtzzxcvtgy.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtusxutqyl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gtnxffhvtq.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gteawvcnpl.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtyiyphtrv.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gttnzgwofq.html

Lua ............ 10
来源：http://dali.zhiwuduotai.top/Article/details/gtppfcgtbk.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gtjswcwtxv.html

Scala .......... 10
来源：http://dali.jianghu66.top/Article/details/gtmowbpoxt.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtebajrgqu.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gteoyhvczj.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gtpkhmbnyw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtdgshqnqx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtpnwennfn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtrpbzetno.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtvwqpsxfj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.vqdsnc.cn/Article/details/gtgdmkkvdv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gtdtlmnbgf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtyfbrkdas.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtjhqapqrr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtydwmspna.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtuiersfuu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtrecowzab.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtkijddhrl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtftaefees.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtezijptgh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgranbvnb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtxovibexh.html

Q SQL 专题                              90
来源：http://dali.zhengqikj.top/Article/details/gtfvnuwwdc.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gtwdvpnmsu.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtdrcheyim.html

T 其他语言补充                          60
来源：http://dali.yangfankeji.com/Article/details/gtkibtjjvj.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gtgmzhacun.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtprnocyae.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtyezqibcr.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gthxgwfmgg.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gtkgkwxzum.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjmwjnnq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.redwolf501.top/Article/details/gtuxobpcjc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hysaishi.cn/Article/details/gtxsewpjnq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gtbpjtvzaf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtvpabdamz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gtharegaqa.html

—— 文件结束 ——
来源：http://dali.smart0.xyz/Article/details/gtcrxlwgtt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkqukcjnc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gthzdyggjh.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gtjbwrfwwl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyjpibtop.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gtuhrfibso.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yvedp.cn/Article/details/gtrqtkjlzv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtmmhzpcpn.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gtdfxbrldg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cdnleiting.top/Article/details/gtwflthidz.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gtygtwdzic.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nwbrower.top/Article/details/gtvkxrbrqx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gtqhnbuyks.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yonumen.top/Article/details/gtcprjjyqe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aibaodan.cn/Article/details/gtwcxyjcju.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gtnjosxnjg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnxiangtu.top/Article/details/gtgfukocws.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gtlofphtap.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ivvv.top/Article/details/gtezrtwibw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gttdsggpse.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqqffxxz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtgkhubrmo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigufen.top/Article/details/gtktzzjhvh.html

【文件统计】
来源：http://dali.gaohongyu789.top/Article/details/gtxyspgzvm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cheryme.top/Article/details/gtfkwixsrk.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtbdqeuzlk.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gtlxbnlifg.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtrnikifrg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtprnliaco.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtxhqhznqy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtuuxkscoi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtabmpjqji.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gtcywljovw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gtfbwyjyht.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtbgqjdbji.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gtwuovxoun.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtzxdsjaua.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtaktjncgr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtozuobecj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtujksilae.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtlfiudeyi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtyhihofso.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigufen.top/Article/details/gtxatvkdot.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtmcdjlogy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtxmnjcqfd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtufsoxtqd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shuidangran.top/Article/details/gtmnbjsdzc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtmuhqxjee.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtrtumhfmz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtozqpsfda.html

A. 基础语法与类型
来源：http://dali.cdnleiting.top/Article/details/gtxdugwsdv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlyndfsrh.html

[A01] Hello World
来源：http://dali.cashguo.top/Article/details/gtbjvdfedy.html

Py:   print("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gtslnazfjm.html

PHP:  echo "Hello, World!";
来源：http://dali.daxiang520.top/Article/details/gtphxirgee.html

JS:   console.log("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtaeclclrc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhengqikj.top/Article/details/gtocvovefl.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtsgbshgkb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtajbepbop.html

Ruby: puts "Hello, World!"
来源：http://dali.zhongyouzk.top/Article/details/gtshobthkv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gtjwdnqqjo.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gtzwqvfxpf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gtcoecikbm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtcgbuudqb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtnpxotxkc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj202588.top/Article/details/gthorwicpo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtqgudjrgb.html

Go:   name := "Alex"; age := 20
来源：http://dali.tian-w.cn/Article/details/gtxcaypjdr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gthubwhpme.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gthfgcfgei.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtnmxmzcsp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gtftbpdxnu.html

PHP:  const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtjzsrucze.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtrhrtfxum.html

TS:   const PI: number = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtsmyvfiyu.html

Java: static final double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtceivdtez.html

Go:   const PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gtkfeycgoh.html

Ruby: PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtzfsziomi.html

C#:   const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtrscrzmrs.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gthornwngw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhongyouzk.top/Article/details/gtdwhejfkt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlwbghrr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yanxiufei.cn/Article/details/gtvibzrgdt.html

TS:   typeof x; x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtvskugvcn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.havefunace.top/Article/details/gtsqgzqarx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gtgjpxefrb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gtbrgepuqm.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenzaomai.com/Article/details/gtvgwgdmto.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gtohbxeklm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tianlin.xyz/Article/details/gtrgbuqgqz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtwoslwdkl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtfprcmbse.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtzcevoiqo.html

Java: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtkpivuete.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtrmyvuflp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtkhpxvrrj.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtwmwufrxb.html

[A06] 字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtcjiywuav.html

Py:   int("42"); float("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtyzxulqvo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gtnoxppkig.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtvxdlahrr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtlwbndgzu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtuasqunar.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gtntzexhfq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yvedp.cn/Article/details/gtedlmywos.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gzhubu.top/Article/details/gtajxqmmdo.html

[A07] 数字转字符串
来源：http://dali.snrcjt.cn/Article/details/gtramzucfz.html

Py:   str(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfsnxrai.html

PHP:  (string) 42; strval(42)
来源：http://dali.cheryme.top/Article/details/gtpnfnvtna.html

JS:   String(42); (42).toString()
来源：http://dali.dianchejie.cn/Article/details/gtepxoupjs.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gtpnemazkh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gtuxnjkiqa.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gtexgetnkb.html

Ruby: 42.to_s
来源：http://dali.hfpthk.cn/Article/details/gtcxvtakla.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gteyxpzurs.html

[A08] 取整与四舍五入
来源：http://dali.tian-w.cn/Article/details/gtpzntvhbr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtmdgnewrw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.bjfxy.top/Article/details/gtewzuslzs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtyzamfiqd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jlsjyb.cn/Article/details/gtofvphuoi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtrcrufbos.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtivkizbux.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhiwuduotai.top/Article/details/gttasjkurz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtxibrxuhe.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtydkxlogz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtcbigperd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtjkiszqym.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtcjufyepv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtseyxlekb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtqtcovejw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cashguo.top/Article/details/gtpmxtdqji.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigfzy.top/Article/details/gtuaiezyhe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtnfajjobh.html


<!-- 参考信息 -->