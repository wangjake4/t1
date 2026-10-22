代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gt2yrdocvrl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvsbxflu.html

[U68] PHP：PDO 连接
来源：http://dali.havefunace.top/Article/details/gt2wydaurcx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gt2xvjswvhs.html

[U69] PHP：PDO 预处理
来源：http://dali.shzxlz.cn/Article/details/gt2khoombmy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gt2grrcabol.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gt2twizzbwg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gt2ksmkobqc.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2bofewxsc.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gt2nkgnvkyc.html

[U72] PHP：写错误日志
来源：http://dali.yueranfly.top/Article/details/gt2dpumjadz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.mhx1999.top/Article/details/gt2kagmuzxt.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnqzz.top/Article/details/gt2vugobmmp.html

parse_ini_file("config.ini", true)
来源：http://dali.snrcjt.cn/Article/details/gt2qcsgdgbn.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2rjwpbzne.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xylfe.cn/Article/details/gt2auyzxvdx.html

[U75] PHP：依赖注入
来源：http://dali.gzhubu.top/Article/details/gt2hqiidgwg.html

composer require psr/container
来源：http://dali.aibaodan.cn/Article/details/gt2qmarroiv.html

[U76] PHP：简单路由
来源：http://dali.ybcxt.top/Article/details/gt2beyacakx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2azbibinn.html

[U77] PHP：模板渲染
来源：http://dali.316326.xyz/Article/details/gt2hjodmagd.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gt2pinklarv.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oprmwnze.html

composer require --dev phpunit/phpunit
来源：http://dali.ppjwa.cn/Article/details/gt2gptenyqa.html

[U79] PHP：静态分析
来源：http://dali.redwolf501.top/Article/details/gt2hecmmpvg.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258888.top/Article/details/gt2wkfpmphy.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxbiwndc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gt2giabnmui.html

[U81] JS：初始化项目
来源：http://dali.gaohongyu789.top/Article/details/gt2bxjwxwpw.html

npm init -y;  npm i express
来源：http://dali.zycfv.cn/Article/details/gt2djxnkmch.html

[U82] JS：package.json 脚本
来源：http://dali.yuxming.cn/Article/details/gt2bjvxkjbl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.snrcjt.cn/Article/details/gt2pzghceri.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gt2ojqhvwwc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gt2jqobahbp.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfzhsbak.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ppjwa.cn/Article/details/gt2gvzfeorm.html

[U85] JS：可选链
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfcjjuvz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sksfexks.html

[U86] JS：空值合并
来源：http://dali.ivvv.top/Article/details/gt2yhaotomq.html

a ?? b
来源：http://dali.ehwqpu.com/Article/details/gt2xhtiteox.html

[U87] JS：解构默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcgvwccy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gt2kudnhucc.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gt2ovcgkmjk.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gt2uvfdnmhs.html

[U89] JS：数组去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2sahtvnoz.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlqayffh.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2albjefed.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqqbvtce.html

[U91] JS：对象键值遍历
来源：http://dali.tanke756.top/Article/details/gt2exxybnex.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dashuyun.cn/Article/details/gt2ugidcwyx.html

[U92] JS：深拷贝
来源：http://dali.yvedp.cn/Article/details/gt2gzpluxso.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2avtejmvs.html

[U93] JS：模板字符串
来源：http://dali.smart0.xyz/Article/details/gt2bvpsdfzr.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gt2qhynaoec.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gt2jkdtneiu.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewmwonsm.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dujqkwgm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2syjawmsx.html

[U96] JS：async/await 与异常
来源：http://dali.bjfxy.top/Article/details/gt2dpwerdwp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2helwpzrp.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gt2xeehjjvm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2bvylkurr.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2aejbcmzo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sxryk.cn/Article/details/gt2kdohshag.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gt2tldafubk.html

el.addEventListener("click", e => {})
来源：http://dali.gotoacloud.top/Article/details/gt2raggderx.html

[U100] JS：DOM 查询
来源：http://dali.snrcjt.cn/Article/details/gt2ewuikoqs.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gt2mscegqvf.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gt2zmsmdlel.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2wpzzqpnf.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gt2jprzdsvt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fzhhl.top/Article/details/gt2pwyajpvp.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gt2fsfwtrul.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfydbxig.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2nkssplsc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2axgacjzo.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gt2nbhnpwvh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gt2volsokju.html

[U106] JS：日期格式化
来源：http://dali.cashguo.top/Article/details/gt2arrpkdoi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gt2hkwjmfhk.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2dhupfper.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2aggetttk.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gt2sjnyyxtq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gt2muohybwv.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gt2xptwsomy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2navntxfj.html

[U110] JS：数组分块
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvhkuvwa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gt2pqkrbcyn.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2wqlxlvlg.html

new Map(Object.entries(obj))
来源：http://dali.hnqzz.top/Article/details/gt2vxrvxnum.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gt2jeierysc.html

"7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2ngagzhai.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofddsczu.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2lnlectwn.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigufen.top/Article/details/gt2lecpnxjh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2lpfyhvxr.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2bkviswlj.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2sakwatac.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gt2poevwqkp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yvedp.cn/Article/details/gt2lvoalica.html

[U117] JS：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnyrjoqn.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gt2dukayoip.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gt2ancjdnsn.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gt2cqljconp.html

[U119] JS：生产构建
来源：http://dali.fzhhl.top/Article/details/gt2ypqtqszs.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gt2kktfhzzv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jlsjyb.cn/Article/details/gt2oenrmntf.html

import.meta.env.VITE_API_URL
来源：http://dali.ybcxt.top/Article/details/gt2gdlcwbgm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssjtmldb.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gt2rczccagx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2gmzliqeu.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gt2qktvxqyn.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gt2rtwasfyw.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2wsahanzm.html

JavaScript ..... 252
来源：http://dali.yongpay.top/Article/details/gt2oxrqnyzn.html

TypeScript ..... 212
来源：http://dali.ydzc1.top/Article/details/gt2qfnrrgvy.html

Java ........... 212
来源：http://dali.andypj.xyz/Article/details/gt2tifprqnr.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2gaehxyhm.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gt2chwjpxmv.html

C# ............. 212
来源：http://dali.xinyue.icu/Article/details/gt2mivhrwxi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2czumgpxj.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gt2gzonstdi.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2baeiivbf.html

Bash ........... 80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpiyeepo.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gt2dcmvgtyd.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gt2jkpyhkpf.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gt2sqemaugo.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gt2rhhojkuu.html

Scala .......... 10
来源：http://dali.svipenyu.cn/Article/details/gt2zunwuzqf.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2sinhgixr.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gt2svqdjtwc.html

按章节统计：
来源：http://dali.ivvv.top/Article/details/gt2ohakbnnn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2jpqnnkde.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gt2vmewaang.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2bsdchasu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gt2zjwejbrn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tanke756.top/Article/details/gt2qxgxbizn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gt2rhnwvfzq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2khhibtgz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2jfbkbfnx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2aeqbzpqi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2gxqusplg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dujtobzi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2tcyqlrlm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2gfbrqhxj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gt2wehparnd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgfzy.top/Article/details/gt2mouwqukg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2warjbitj.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gt2qvpenaow.html

R Bash 专题                             80
来源：http://dali.hammf.cn/Article/details/gt2mawbjmuv.html

S C / C++ 专题                          60
来源：http://dali.chenlongwang.top/Article/details/gt2eajoxbxg.html

T 其他语言补充                          60
来源：http://dali.yanxiufei.cn/Article/details/gt2ibaklofc.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsjinlsz.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2rfhfwxxf.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gt2kszilbui.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2lqmtuuct.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gt2hscymvna.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2rxwqrfvu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gt2lpcalnkq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shzxlz.cn/Article/details/gt2qoteromh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gt2tmiakqrn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gt2qmityegh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gt2cbdhdrqe.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gt2tiquevdt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gtlzccdo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ppjwa.cn/Article/details/gt2ubtiwvhl.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gt2qvdrbtrp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2mwmspazy.html

【收录内容】
来源：http://dali.316326.xyz/Article/details/gt2yjkxzttn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqpqyuij.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tanke756.top/Article/details/gt2xqkjonea.html

SQL · Bash · C · C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uelromuk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daria6918.cn/Article/details/gt2abtcqfdk.html

【使用说明】
来源：http://dali.yvedp.cn/Article/details/gt2fuuflvse.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gt2koahrxde.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.kuanghao11.cn/Article/details/gt2uomhvfuc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.andypj.xyz/Article/details/gt2ypeoajne.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.snrcjt.cn/Article/details/gt2crmatnsl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpbxrnil.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.meibo888.top/Article/details/gt2cwaaxnhf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vldkndpc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj202588.top/Article/details/gt2fcohryel.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dianchejie.cn/Article/details/gt2stgqzkmw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gt2tjmzsrmi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gzhubu.top/Article/details/gt2mqpmlugu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daria6918.cn/Article/details/gt2ojyvrwwj.html

【文件统计】
来源：http://dali.nwbrower.top/Article/details/gt2jtqqbfwg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nwbrower.top/Article/details/gt2styiqmci.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2bhhjdrrm.html

目  录
来源：http://dali.hywenlv.cn/Article/details/gt2jnfhpnvn.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2teedjrgo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2zuymqmdr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gt2ezowcwdu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2qtznjabk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2fojjattc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gt2zgqzvlwv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gt2opfivfkx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gt2isgfvtqb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nwbrower.top/Article/details/gt2hihbblgj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2woukgqsp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2wbarboyt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2fsemsqip.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2mxegzfjg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gt2lzgcwjxt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gt2pbsqcalc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.0kj1m.cn/Article/details/gt2woglscnz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2uppbvohs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guannengcc.top/Article/details/gt2filxxooy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yvedp.cn/Article/details/gt2zbsgyxyy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hammf.cn/Article/details/gt2pszlspji.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2inaeaynp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gt2vgwmxbmb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fngtjvjs.html

A. 基础语法与类型
来源：http://dali.dianchejie.cn/Article/details/gt2atbhjtkv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dimxfimm.html

[A01] Hello World
来源：http://dali.316326.xyz/Article/details/gt2leklyjve.html

Py:   print("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gt2xvhrrajb.html

PHP:  echo "Hello, World!";
来源：http://dali.andypj.xyz/Article/details/gt2qzzoylxe.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gt2ffhglhvv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2woiwectq.html

Java: System.out.println("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2vnnrukhn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gt2wdwtgygw.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gt2jobzypsb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gt2jjdgclof.html

[A02] 变量声明与赋值
来源：http://dali.iojbl.cn/Article/details/gt2niliasqs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xylfe.cn/Article/details/gt2gfevtqfn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2icgkgcmx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2osnugwnb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yongpay.top/Article/details/gt2bkdwevyz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2koevtoao.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gt2khqikysc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xinyue.icu/Article/details/gt2eumyhltg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gt2bbmxilys.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gt2gmgslzor.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxuanxn.top/Article/details/gt2lbbiucej.html

PHP:  const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2trkfelgo.html

JS:   const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2tzyrdcdw.html

TS:   const PI: number = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2huywelnu.html

Java: static final double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2ocpgroyw.html

Go:   const PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gt2xqffqeto.html

Ruby: PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gt2dnqhyhso.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2plmbvnwh.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gt2zhxjznqd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daxiang520.top/Article/details/gt2zqeajmrh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nwbrower.top/Article/details/gt2qavaybky.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xccplldc.html

TS:   typeof x; x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gt2avfdpspr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gt2zuibqygv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gaohongyu789.top/Article/details/gt2ekmhktbw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxinkj.top/Article/details/gt2razhvsug.html

C#:   x.GetType().Name; x is int
来源：http://dali.aibaodan.cn/Article/details/gt2deyqrlsd.html

[A05] 整数除法与取模
来源：http://dali.yj20258.top/Article/details/gt2xieufibg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.snrcjt.cn/Article/details/gt2mqzhzedn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2dpmjzfxb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2vbuvksea.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2lgisayqn.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2kekjjaug.html

Go:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2vdluurtc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlvywzs.html

C#:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2gpslghun.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gt2eghlscbp.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpnoxdjg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gt2olrlojor.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gt2pobqfudr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2eyiutwuw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hywenlv.cn/Article/details/gt2anjaheln.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258.top/Article/details/gt2zzzskqjm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpnbmakz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkhbaeak.html

[A07] 数字转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ahpskbvr.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gt2tclscdlj.html

PHP:  (string) 42; strval(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2hjrjtajl.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gt2axzmppba.html

TS:   String(42)
来源：http://dali.cdnleiting.top/Article/details/gt2lcvlhwvj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.svipenyu.cn/Article/details/gt2xrqlnuym.html

Go:   strconv.Itoa(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggrmgxzl.html

Ruby: 42.to_s
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgabgpar.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gt2reuhsjvw.html

[A08] 取整与四舍五入
来源：http://dali.pycfn.com/Article/details/gt2ijuqqmzc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gt2qojpwvri.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.bjfxy.top/Article/details/gt2xpqkydsi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gt2kdgkgbsu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hywenlv.cn/Article/details/gt2tzphimda.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2gxljfufq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2lnylajfq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gt2pnxianmx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2qatcwjxs.html

[A09] 绝对值与最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2nyaqbyrs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2aqzonmev.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2vhvsvwpd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2jlfsltkx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2qeflbxxc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2pbwvvteo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gogol.net.cn/Article/details/gt2posouytl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.fzhhl.top/Article/details/gt2mqfgfqry.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2sbrnzaoe.html

[A10] 生成随机数
来源：http://dali.chenlongwang.top/Article/details/gt2qbdlmgij.html

Py:   import random; random.randint(1, 100)
来源：http://dali.andypj.xyz/Article/details/gt2kovbdqic.html

PHP:  random_int(1, 100);
来源：http://dali.daria6918.cn/Article/details/gt2jakqhbtb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoycluwa.html


<!-- 参考信息 -->