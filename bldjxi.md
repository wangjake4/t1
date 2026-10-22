代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gt2jxbmcesy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuanzhike.top/Article/details/gt2fsyhceyt.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gt2feohozgy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpzmpjhu.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulgnrfqj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gt2akpuxthl.html

[U70] PHP：PDO 事务
来源：http://dali.chenzaomai.com/Article/details/gt2fmvqbfgv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gt2gaulmkra.html

[U71] PHP：抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2tjznduqr.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2unspfach.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gt2hvvkdevg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdaqwprv.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gt2ysoydmed.html

parse_ini_file("config.ini", true)
来源：http://dali.xziqi.cn/Article/details/gt2mvxbtjwo.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gt2nrdvztbd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hammf.cn/Article/details/gt2tyhkprlg.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gt2zarlwmvc.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gt2owyfryad.html

[U76] PHP：简单路由
来源：http://dali.sweek.top/Article/details/gt2pfydmewi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gt2vmmurtuo.html

[U77] PHP：模板渲染
来源：http://dali.c1oappe.top/Article/details/gt2qystpkuj.html

composer require twig/twig
来源：http://dali.redwolf501.top/Article/details/gt2vesbxwvj.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gt2wndgffmj.html

composer require --dev phpunit/phpunit
来源：http://dali.snrcjt.cn/Article/details/gt2qahxwjvy.html

[U79] PHP：静态分析
来源：http://dali.tanke756.top/Article/details/gt2ulwyiwla.html

composer require --dev phpstan/phpstan
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtyvghnk.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gt2sjofriik.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gt2slhqmcdu.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gt2udulrbdz.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gt2quzdtrpy.html

[U82] JS：package.json 脚本
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyskgctb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gt2vhrwpuus.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2crnjtfbg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2ukyvwtma.html

[U84] JS：CommonJS 写法
来源：http://dali.sweek.top/Article/details/gt2qonrxctl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gt2isahgolw.html

[U85] JS：可选链
来源：http://dali.yvedp.cn/Article/details/gt2ijvhupne.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogpkydqw.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gt2thnwycll.html

a ?? b
来源：http://dali.dianchejie.cn/Article/details/gt2irdskxvn.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gt2wtqpawbu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnqzz.top/Article/details/gt2qiknwmar.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gt2fbhvdxqb.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gt2wpbsfusi.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gt2ukiqmavv.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2csffwodo.html

[U90] JS：数字数组排序
来源：http://dali.daria6918.cn/Article/details/gt2dnepabww.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2duvintgu.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gt2ficbcbsm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gt2dqibsbze.html

[U92] JS：深拷贝
来源：http://dali.yonumen.top/Article/details/gt2nizkcbek.html

structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2drqiaulm.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlupgqjf.html

`共 ${n} 条`
来源：http://dali.yangfankeji.com/Article/details/gt2ekpzjnoy.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsstjgss.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gt2lxeytpye.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvyzgtx.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2dnhtxvvj.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gt2ynkouivt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvuvwvek.html

[U97] JS：并发请求
来源：http://dali.yuxming.cn/Article/details/gt2mpenkjlt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2uenactav.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gt2vuvquugy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qshttvpb.html

[U99] JS：事件监听
来源：http://dali.gzhubu.top/Article/details/gt2zhadhliv.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gt2cjgjgddw.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gt2foushfwe.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gt2tnrpdqjs.html

[U101] JS：classList 操作
来源：http://dali.smart0.xyz/Article/details/gt2oulbpays.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gt2xqsuvjju.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gt2qssizejc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gt2euduluft.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gt2sznpezla.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzymqkrh.html

[U104] JS：防抖
来源：http://dali.yongpay.top/Article/details/gt2kfmaaikc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2yzgiqtos.html

[U105] JS：节流
来源：http://dali.nwbrower.top/Article/details/gt2unabljqv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gt2csahijvl.html

[U106] JS：日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2jbcvilny.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gt2odvkgztx.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gt2zqyjesik.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2sdsxywqe.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gt2zcblvwdr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gt2bsyrafuj.html

[U109] JS：数组分组
来源：http://dali.mhx1999.top/Article/details/gt2pfoolwxc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gt2suxvczqn.html

[U110] JS：数组分块
来源：http://dali.yonumen.top/Article/details/gt2lzuwoulb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gt2iizhwxie.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyoeosr.html

new Map(Object.entries(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2fqpiknhd.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gt2sewqyqrl.html

"7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qybskpos.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gt2zblrthxh.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dueprjrg.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gt2drhccbnv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2awrtkwed.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbssddix.html

crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2mihmhwew.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgmcvwkn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gt2armygknr.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2swdzazwl.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gt2impmmkyc.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gt2awtwtqhl.html

npm i -D vite;  npx vite
来源：http://dali.sweek.top/Article/details/gt2uubsjhlx.html

[U119] JS：生产构建
来源：http://dali.iojbl.cn/Article/details/gt2egzrhoao.html

npx vite build
来源：http://dali.tian-w.cn/Article/details/gt2rpzvkqii.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gt2eaqbjjwk.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnsaniyf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2mwjocyiv.html

统计汇总
来源：http://dali.tianlin.xyz/Article/details/gt2kmcptfka.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ftqfqtww.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gt2hvdzvbiv.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gt2tbfraqtx.html

PHP ............ 252
来源：http://dali.guannengcc.top/Article/details/gt2rrkbisxh.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gt2qxvifmtu.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gt2xvddxcmj.html

Java ........... 212
来源：http://dali.zycfv.cn/Article/details/gt2xifihtye.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gt2lhufssnr.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2cjzacjlg.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfxojacd.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gt2sbesyjqi.html

C++ ............ 30
来源：http://dali.guannengcc.top/Article/details/gt2ncjxyydf.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gt2eerxqppm.html

Bash ........... 80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqochuwj.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoghthdc.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2gzeazozk.html

Lua ............ 10
来源：http://dali.0kj1m.cn/Article/details/gt2nuqprofx.html

Perl ........... 10
来源：http://dali.kuanghao11.cn/Article/details/gt2onwkioed.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gt2eisxojwd.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2kzsedqir.html

合计 ........... 2106 条
来源：http://dali.jqgufenzy.top/Article/details/gt2snibdvaf.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gt2qmvktxqb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gt2imgkxofe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2bijmqcta.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2ptncorra.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gt2edsvzhsi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocjfzurp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gt2rfrgutbh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gt2jagfssao.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gt2upiscmqk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2xriokoyr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2hviduxgl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2snpxgjdf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2ygvpddpn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2cziacueg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2uckecfmo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gt2zrqykedu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2avbhxccy.html

Q SQL 专题                              90
来源：http://dali.ivvv.top/Article/details/gt2rvvsndrv.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gt2fbgvvxmv.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gt2ilbmozhy.html

T 其他语言补充                          60
来源：http://dali.dianchejie.cn/Article/details/gt2kizrulhq.html

U 高频实用片段                         120
来源：http://dali.gotoacloud.top/Article/details/gt2snkgmrpg.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2uaxtvsmk.html

合计                                  2106 条
来源：http://dali.chenlongwang.top/Article/details/gt2ggjgtids.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2kmueeanj.html

使用提醒
来源：http://dali.c1oappe.top/Article/details/gt2bmdvhmsk.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2wjiwgace.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.redwolf501.top/Article/details/gt2wbqqtnjl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cheryme.top/Article/details/gt2zqyubgja.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gt2rltjcqvi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gt2xgvjpmfa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tian-w.cn/Article/details/gt2bqtgdxxb.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gt2chzkbusk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hdbkzwet.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwshetxc.html

Common Programming Examples Cheat Book
来源：http://dali.yangfankeji.com/Article/details/gt2avvbukej.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2klvcfrsr.html

【收录内容】
来源：http://dali.yj202588.top/Article/details/gt2bfbdrmjr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.mhx1999.top/Article/details/gt2svpupget.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cqqwz.cn/Article/details/gt2napgspzm.html

SQL · Bash · C · C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryhtkuag.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.svipenyu.cn/Article/details/gt2lxguwcgt.html

【使用说明】
来源：http://dali.smart0.xyz/Article/details/gt2ztsazhsl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.c1oappe.top/Article/details/gt2cfjejhla.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdmtofob.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gt2petsqwdr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gt2wltxugcf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gt2dszgptog.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hammf.cn/Article/details/gt2nodjyqkd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.kuanghao11.cn/Article/details/gt2zdamwyxf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvpoljdq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgoxgovk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.9152youxi.cn/Article/details/gt2lihudlsi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yanxiufei.cn/Article/details/gt2pnixtwbq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gt2novakhlk.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpeoafvy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.mhx1999.top/Article/details/gt2rtigvhzu.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2bbjqinus.html

目  录
来源：http://dali.zhiwuduotai.top/Article/details/gt2uihmrzvk.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrecdbqj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2jkapjvee.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gt2ybyhaixf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gt2mkigamlt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gt2vvfznztc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jianghu66.top/Article/details/gt2ijurmdwl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2odqpuhwa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbemcduc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gt2wrsgaryf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2gxarklcs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gt2sgxwdueg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2pklucdqy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2kywxyokp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2lmrrhfhw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gt2lpskmhex.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2kumxxqwq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2xwyrbjhj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdwdncpy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gt2rmrinvbm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2mijjzwdv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gt2prgrcfxo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gt2cxglvjca.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fexrvvyw.html

A. 基础语法与类型
来源：http://dali.havefunace.top/Article/details/gt2jswfzvcd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ouxacxnd.html

[A01] Hello World
来源：http://dali.yj202588.top/Article/details/gt2shtwuqcj.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gt2yyiveeog.html

PHP:  echo "Hello, World!";
来源：http://dali.quarkkingdee.top/Article/details/gt2njovurvk.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2rwuypmxu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rspwxvdz.html

Java: System.out.println("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2yxdrzncr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gt2lrhsplya.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gt2wclgwqzo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gt2qednvgdy.html

[A02] 变量声明与赋值
来源：http://dali.mhx1999.top/Article/details/gt2apgmuxxk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gt2bldcjxqf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2nbomllnb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2hunqnscl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgwrstlw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2rgikofou.html

Go:   name := "Alex"; age := 20
来源：http://dali.gzhubu.top/Article/details/gt2xqcehyhp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gt2taciveqn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fzhhl.top/Article/details/gt2nloseujf.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnyklacz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gt2egkrikfx.html

PHP:  const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2qmopsfam.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2lmvfyzgw.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2xpomkrnz.html

Java: static final double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2bvtjazip.html

Go:   const PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gt2yjjrvgzh.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2nksoupoi.html

C#:   const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2ngqjqbvr.html

[A04] 判断变量类型
来源：http://dali.hammf.cn/Article/details/gt2zqtzaosa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cheryme.top/Article/details/gt2qeiiclpv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgvvauxe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gt2yijdzsfc.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gt2uwnvinms.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gt2flzcjivz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ybcxt.top/Article/details/gt2zxagcwvc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jyoumei.cn/Article/details/gt2mhulitpu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gt2mwvafeiu.html

[A05] 整数除法与取模
来源：http://dali.hammf.cn/Article/details/gt2ianaqzut.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gt2ebctdscv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2xhjnfydl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2alckgzog.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2jtbsugct.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2dodyvgkx.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2zumzvcrr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqtjecgo.html

C#:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2mzbuapem.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2gopourvk.html

Py:   int("42"); float("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gt2trsakqds.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgpyjwss.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2enbdispd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.meibo888.top/Article/details/gt2qnycrhhv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gt2qlpglpgs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zycfv.cn/Article/details/gt2cpevsexk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sufxvd.cn/Article/details/gt2xwmmvyzi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenlongwang.top/Article/details/gt2drmqhvox.html

[A07] 数字转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2atpjchrw.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywketqcc.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knpgqsqx.html

JS:   String(42); (42).toString()
来源：http://dali.cdnleiting.top/Article/details/gt2tnkmgdrc.html

TS:   String(42)
来源：http://dali.zhengqikj.top/Article/details/gt2pwgdrzim.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xylfe.cn/Article/details/gt2qqdeaefp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zavbgsbh.html

Ruby: 42.to_s
来源：http://dali.wangdashe.top/Article/details/gt2pvbaozbj.html

C#:   42.ToString()
来源：http://dali.cqqwz.cn/Article/details/gt2ifxtzdbn.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gt2ghneebql.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gt2gxeyilds.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daxiang520.top/Article/details/gt2entbgvjm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gt2oofzvdeq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gogol.net.cn/Article/details/gt2ztcanzcz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gt2ozqlicwx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2rdwjnwct.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yvedp.cn/Article/details/gt2fpnwlzrf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2pkunzgod.html

[A09] 绝对值与最大最小值
来源：http://dali.snrcjt.cn/Article/details/gt2pksosgvm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2rmkeujap.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2islnzair.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2mwfkhubw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2aiibwofz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2fjbvkkfr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tian-w.cn/Article/details/gt2zpurnzzg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.svipenyu.cn/Article/details/gt2outeknfn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2offtikna.html

[A10] 生成随机数
来源：http://dali.meibo888.top/Article/details/gt2lzletnfp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ivvv.top/Article/details/gt2jpqpyhzc.html

PHP:  random_int(1, 100);
来源：http://dali.jinqigfzy.top/Article/details/gt2qyynqzeb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvohscee.html


<!-- 参考信息 -->