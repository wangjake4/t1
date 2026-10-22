代发 wailian999

[U61] PHP：正则
来源：http://dali.havefunace.top/Article/details/gt2cmybteei.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2jgpwfvnz.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gt2drzpjyxs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.bjfxy.top/Article/details/gt2ouxzpyps.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gt2bwspyfbf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.quarkkingdee.top/Article/details/gt2okhlshga.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gt2xydnqkdp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hfpthk.cn/Article/details/gt2gckhnkfr.html

[U65] PHP：会话
来源：http://dali.jinqigfzy.top/Article/details/gt2woplellw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2ihomsupa.html

[U66] PHP：设置 Cookie
来源：http://dali.havefunace.top/Article/details/gt2fcthcwww.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnsrbchn.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gt2wesvlnhv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gt2dwjjgnyw.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gt2buehslcx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gt2slcfstqy.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gt2mkktoziy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gt2gyluzind.html

[U70] PHP：PDO 事务
来源：http://dali.gotoacloud.top/Article/details/gt2oepazkpf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gt2livasuek.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2hcmxhzfo.html

throw new RuntimeException("失败", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2sgskeooc.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gt2kxyrqwkm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.iojbl.cn/Article/details/gt2yiiswpse.html

[U73] PHP：读取 ini 配置
来源：http://dali.cheryme.top/Article/details/gt2imqufgim.html

parse_ini_file("config.ini", true)
来源：http://dali.dashuyun.cn/Article/details/gt2hlafqhfh.html

[U74] PHP：读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2dapqnocf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hysaishi.cn/Article/details/gt2wvlyztpi.html

[U75] PHP：依赖注入
来源：http://dali.redwolf501.top/Article/details/gt2qnnesbnb.html

composer require psr/container
来源：http://dali.ivvv.top/Article/details/gt2ogwtckuw.html

[U76] PHP：简单路由
来源：http://dali.zhengqikj.top/Article/details/gt2laewonsa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gt2wlfzghuy.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gt2dspnpyqd.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gt2sbxgyzei.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2fqecrqcp.html

composer require --dev phpunit/phpunit
来源：http://dali.aibaodan.cn/Article/details/gt2wserprce.html

[U79] PHP：静态分析
来源：http://dali.guowangkeji.top/Article/details/gt2sfwaolzp.html

composer require --dev phpstan/phpstan
来源：http://dali.ehwqpu.com/Article/details/gt2vkggwgrw.html

[U80] PHP：代码规范修复
来源：http://dali.cheryme.top/Article/details/gt2euflxirj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gt2pgijeykb.html

[U81] JS：初始化项目
来源：http://dali.shangyingyoupin.top/Article/details/gt2azmzppio.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gt2hbfzrhur.html

[U82] JS：package.json 脚本
来源：http://dali.ybcxt.top/Article/details/gt2lhghivue.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnqmobvj.html

[U83] JS：ES Module 导入导出
来源：http://dali.bjfxy.top/Article/details/gt2mlwprjha.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2xlqbdmip.html

[U84] JS：CommonJS 写法
来源：http://dali.yangfankeji.com/Article/details/gt2vquxmiia.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gt2ylwbajao.html

[U85] JS：可选链
来源：http://dali.nanxuanxn.top/Article/details/gt2ohfmaxka.html

a?.b?.c
来源：http://dali.guowangkeji.top/Article/details/gt2tdmadcfb.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gt2iycxjvpg.html

a ?? b
来源：http://dali.tian-w.cn/Article/details/gt2ywyjaxqc.html

[U87] JS：解构默认值
来源：http://dali.sxryk.cn/Article/details/gt2rfavoaao.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yongpay.top/Article/details/gt2cmpfiutx.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gt2mxilazln.html

{ ...a, ...b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htyzfmia.html

[U89] JS：数组去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibughomm.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2eullenap.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gt2iqdijqfe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmimmctx.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krulahko.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jiagoushi.top/Article/details/gt2jtpjvwgo.html

[U92] JS：深拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzxwgdvm.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2kkbkelbj.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfpwsstj.html

`共 ${n} 条`
来源：http://dali.ybcxt.top/Article/details/gt2ovowmpzx.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2inmzvbgo.html

const double = x => x * 2;
来源：http://dali.zhengqikj.top/Article/details/gt2uzeqwpat.html

[U95] JS：Promise 包装
来源：http://dali.hysaishi.cn/Article/details/gt2abxyoopv.html

new Promise((resolve, reject) => {})
来源：http://dali.ydzc1.top/Article/details/gt2ivrjxgts.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gt2npmaluvf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2mbiypeby.html

[U97] JS：并发请求
来源：http://dali.yanxiufei.cn/Article/details/gt2ilstvenq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gt2vikycrnb.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gt2loshyugg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gt2fccnyzkr.html

[U99] JS：事件监听
来源：http://dali.redwolf501.top/Article/details/gt2bdxywnnv.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iormyqrl.html

[U100] JS：DOM 查询
来源：http://dali.xziqi.cn/Article/details/gt2pmrgydca.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gt2ynudhtjc.html

[U101] JS：classList 操作
来源：http://dali.redwolf501.top/Article/details/gt2fyuwdsrl.html

el.classList.toggle("active")
来源：http://dali.xinyue.icu/Article/details/gt2chdqeauj.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gt2ydsylumq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gt2meehsjtb.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gt2ogtvxhpu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuanzhike.top/Article/details/gt2ogubuquw.html

[U104] JS：防抖
来源：http://dali.svipenyu.cn/Article/details/gt2adfjaddg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2vppoiquj.html

[U105] JS：节流
来源：http://dali.birdmap.top/Article/details/gt2tcjkdhjf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gt2osqveexw.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2zolrbwze.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gt2pokkmgds.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2dzeuenzr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2fraawdeo.html

[U108] JS：随机整数
来源：http://dali.ivvv.top/Article/details/gt2jnexjuyl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gt2hvcreief.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gt2ikagcaod.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtmladrj.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gt2koqxosye.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gt2znziivtl.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gt2smqskady.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gt2sqpkutlv.html

[U112] JS：字符串补位
来源：http://dali.havefunace.top/Article/details/gt2zkofngbo.html

"7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2fautcssc.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gt2nimstivi.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2ibuhdmzn.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258888.top/Article/details/gt2gzxnbihg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwwecyoq.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2cwtmsvlm.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2dcyxfhis.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gt2ttmsueqd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gt2rjhmbcde.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2jdxnumje.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gt2bkehrnmh.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gt2hriuqnuk.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gt2gtjjmbuj.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gt2curlelwe.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnakdvwk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrhcjamq.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gt2kgomdyby.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wbcpxjhh.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gt2atpozhni.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2kcwhqgys.html

按语言统计（条）：
来源：http://dali.yuxming.cn/Article/details/gt2yfiskttm.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gt2wmezrvsp.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2odaizowo.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gt2uigtdbnn.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gt2nepjdkmn.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gt2sgjntkwl.html

Go ............. 212
来源：http://dali.andypj.xyz/Article/details/gt2tyhxbcsw.html

Ruby ........... 212
来源：http://dali.pycfn.com/Article/details/gt2aoerymne.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gt2wyrqbmqm.html

C .............. 30
来源：http://dali.sysykeji.top/Article/details/gt2lajiqslo.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gt2ukcukwps.html

SQL ............ 90
来源：http://dali.birdmap.top/Article/details/gt2qrbpjxog.html

Bash ........... 80
来源：http://dali.yonumen.top/Article/details/gt2plosfczb.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2diszljbh.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gt2uevjxdvg.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gt2lseyfloh.html

Perl ........... 10
来源：http://dali.cdnleiting.top/Article/details/gt2kynzmlff.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gt2bnoaapvv.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2jzuomltm.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gt2ewmcxlbi.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gt2lropqunb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gt2obecctuw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpojdokd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfldokfb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgnotsuo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258888.top/Article/details/gt2mpynqknh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2tpduydvk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gt2erocixih.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gt2msovwlvs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2bgbthazd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrfsryyw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2fdtqhfeu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2golheuxb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2jvwwihsw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2hprbufnk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jianghu66.top/Article/details/gt2xbsranxa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gt2nkvbogyy.html

Q SQL 专题                              90
来源：http://dali.ehwqpu.com/Article/details/gt2ixoypurn.html

R Bash 专题                             80
来源：http://dali.birdmap.top/Article/details/gt2mfgwzkba.html

S C / C++ 专题                          60
来源：http://dali.jinqigfzy.top/Article/details/gt2zwvzfbzq.html

T 其他语言补充                          60
来源：http://dali.jiagoushi.top/Article/details/gt2pgpnscax.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gt2ciqcmril.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2tycbgsch.html

合计                                  2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2yyvyfkop.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2kihocqla.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gt2rzyoyrhu.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2syyrsfib.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ehwqpu.com/Article/details/gt2bqxgwcya.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gt2huyfihni.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gt2zewodqly.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuanzhike.top/Article/details/gt2zjtyhrwj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gt2tazvnzwm.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gt2wizkesgt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2dofdpabj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzligbyi.html

Common Programming Examples Cheat Book
来源：http://dali.zhixingplan.top/Article/details/gt2jtbbxrob.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2utekckfd.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gt2fuuqufmh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gt2ewfcapuc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gt2nmoozccg.html

SQL · Bash · C · C++
来源：http://dali.jyoumei.cn/Article/details/gt2eamgbgsx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gt2tpznvzac.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gt2szcrhger.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gt2sdvraigm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj202588.top/Article/details/gt2tmqzicwe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.9152youxi.cn/Article/details/gt2ugttosur.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jiagoushi.top/Article/details/gt2zuhlbxzq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258.top/Article/details/gt2vugpsfwi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gt2kkftawca.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhongyouzk.top/Article/details/gt2aiiwgznb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.c1oappe.top/Article/details/gt2itizigou.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gt2kixdyzuc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gt2kblefaha.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuxming.cn/Article/details/gt2mbvonurd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmjgyags.html

【文件统计】
来源：http://dali.cashguo.top/Article/details/gt2nhxyuvfk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gzhubu.top/Article/details/gt2egcvuxdr.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2vigetppe.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gt2vktwuequ.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2aocfdaiv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gt2awnwtxft.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gt2lgkmvwdl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2verktndg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2ptwfjcsz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gt2ctxnxjzp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gt2iqqmddyb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2yhxqejcm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2voeixbyt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2ofltmvco.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2tccobkes.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2dykfqruy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2izxdlqrk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2kulyeylv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gt2bnbjfvhv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.birdmap.top/Article/details/gt2xrrmdrkc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdezymym.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuanzx.com/Article/details/gt2ycnhhezq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2nakffvfi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gt2tvakrgyh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2eqvnsyfb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2jprqctbq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xhwmjyxq.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sverysdd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2acspmmtk.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2cvvutbmd.html

Py:   print("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gt2mcdxirln.html

PHP:  echo "Hello, World!";
来源：http://dali.hfpthk.cn/Article/details/gt2fewcniup.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zepuhmbg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gt2agvjzvee.html

Java: System.out.println("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtpndkff.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcrgohxa.html

Ruby: puts "Hello, World!"
来源：http://dali.pycfn.com/Article/details/gt2leoxpzbv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gt2pyoegeyi.html

[A02] 变量声明与赋值
来源：http://dali.birdmap.top/Article/details/gt2vlibbpcs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gt2drjcctoa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2gpipppnu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shuidangran.top/Article/details/gt2mfkguvkq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2setzsuya.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2vvyeenbo.html

Go:   name := "Alex"; age := 20
来源：http://dali.tianlin.xyz/Article/details/gt2yvbopsme.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gt2dywcrxuh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2lexwzhec.html

[A03] 常量定义
来源：http://dali.cashguo.top/Article/details/gt2kwgdgdae.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sufxvd.cn/Article/details/gt2uuixfbvk.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2fvgmbzos.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2vbxbzdym.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dflwwwck.html

Java: static final double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2lgpohdqz.html

Go:   const PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gt2tnlejmfj.html

Ruby: PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gt2cfnyegad.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpakyds.html

[A04] 判断变量类型
来源：http://dali.yvedp.cn/Article/details/gt2nnonajdt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gt2eolzheit.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2gfjmkubi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gt2dwnwvtwl.html

TS:   typeof x; x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2wmnphuxc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yueranfly.top/Article/details/gt2tjsozgvk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangdashe.top/Article/details/gt2hfbmwbpc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gt2luyoyjbc.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gt2isonyqiw.html

[A05] 整数除法与取模
来源：http://dali.dashuyun.cn/Article/details/gt2cunlykna.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhiulxyy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2hqghraca.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wutqbetx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjclxgbh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2vumyqtqw.html

Go:   7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2djtofaxf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsgssobd.html

C#:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2meosmsca.html

[A06] 字符串转数字
来源：http://dali.ivvv.top/Article/details/gt2befrewbs.html

Py:   int("42"); float("3.14")
来源：http://dali.gogol.net.cn/Article/details/gt2izssuvvx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ybcxt.top/Article/details/gt2zrxsquoq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gt2rmhvikrz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gt2ngsoxgjz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gt2fmedaoyo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2jtjwnvim.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gt2mpanrbna.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.birdmap.top/Article/details/gt2pmcgtsth.html

[A07] 数字转字符串
来源：http://dali.ydzc1.top/Article/details/gt2htzskhxd.html

Py:   str(42)
来源：http://dali.hysaishi.cn/Article/details/gt2rvndmycw.html

PHP:  (string) 42; strval(42)
来源：http://dali.sweek.top/Article/details/gt2klxlrlqv.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gt2qxzilhfv.html

TS:   String(42)
来源：http://dali.hnqzz.top/Article/details/gt2pprzugoz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuanzhike.top/Article/details/gt2ashttxjj.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gt2ixpopmps.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gt2faeimjje.html

C#:   42.ToString()
来源：http://dali.cheryme.top/Article/details/gt2fhznfdpk.html

[A08] 取整与四舍五入
来源：http://dali.kuanghao11.cn/Article/details/gt2cspakcuz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gt2huhqseql.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gt2bsejogei.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2dwlquuef.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xylfe.cn/Article/details/gt2hbexyylm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2udnfiifr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2qrqdhzjs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gt2tuqmjvxs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gt2vztcxdrg.html

[A09] 绝对值与最大最小值
来源：http://dali.tianlin.xyz/Article/details/gt2gytjragx.html


<!-- 参考信息 -->