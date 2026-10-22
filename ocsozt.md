代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.hnqzz.top/Article/details/gt2rbvtrpih.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2miacjkbh.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gt2bzndcyhr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gt2ywcwieqh.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gt2qdjleeby.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gt2hlluxqct.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2zviunxtt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daria6918.cn/Article/details/gt2bcjgneyi.html

[U63] PHP：文件读写
来源：http://dali.yj20258.top/Article/details/gt2jundfwjl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gt2ifhfgqxl.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkmzfedb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gt2ctwuxtjv.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhfhmkkm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbhithxn.html

[U66] PHP：设置 Cookie
来源：http://dali.cdnleiting.top/Article/details/gt2cpbwertx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gt2pnpisayz.html

[U67] PHP：处理文件上传
来源：http://dali.tian-w.cn/Article/details/gt2ooqhftvf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gt2swxpxfnf.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gt2jaciqsss.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gt2xrvpaakh.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gt2uxuqcosg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hywenlv.cn/Article/details/gt2zwduqsez.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gt2icdzcujw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbfydhch.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2xfvtnkso.html

throw new RuntimeException("失败", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2ohplwndi.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gt2mvtssdtj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gt2xsajorwk.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenzaomai.com/Article/details/gt2hyppwrnm.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gt2rzytulvh.html

[U74] PHP：读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2werporpi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldvfveaw.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gt2vcqjdvfk.html

composer require psr/container
来源：http://dali.aizwys.cn/Article/details/gt2fllhsfdn.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gt2xlzpymur.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxinkj.top/Article/details/gt2uwdwolee.html

[U77] PHP：模板渲染
来源：http://dali.jianghu66.top/Article/details/gt2zpmbfndl.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gt2uzmkwhtr.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gt2gwmuymiv.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gt2ucvjcena.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2valvjuwe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xisihate.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gt2hgyfemxc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gt2snulblkh.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gt2equcopzo.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gt2usjmhgsh.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gt2mpwzlcnn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jyoumei.cn/Article/details/gt2utwdjlwi.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gt2tyrhpgpd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2iozaoefi.html

[U84] JS：CommonJS 写法
来源：http://dali.zycfv.cn/Article/details/gt2ikpojlac.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gt2raohaqpd.html

[U85] JS：可选链
来源：http://dali.cdnleiting.top/Article/details/gt2sokgznlb.html

a?.b?.c
来源：http://dali.yj20258888.top/Article/details/gt2nvqirixe.html

[U86] JS：空值合并
来源：http://dali.gogol.net.cn/Article/details/gt2lwkpqsxh.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gt2ipdcriya.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gt2nqbjhwfv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.redwolf501.top/Article/details/gt2vbuhxjua.html

[U88] JS：对象展开合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnuezewg.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gt2rdyjbkhu.html

[U89] JS：数组去重
来源：http://dali.tianlin.xyz/Article/details/gt2hhmknmnc.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2iofrvqkp.html

[U90] JS：数字数组排序
来源：http://dali.316326.xyz/Article/details/gt2ylzesahd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjrisha.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigufen.top/Article/details/gt2oxekbdfq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sweek.top/Article/details/gt2xiaazynk.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gt2nmjovjgp.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2qdogxvvb.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gt2rancdlmm.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gt2epknrskw.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gt2tirodfjx.html

const double = x => x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzqsmgvj.html

[U95] JS：Promise 包装
来源：http://dali.dianchejie.cn/Article/details/gt2cdkbihzt.html

new Promise((resolve, reject) => {})
来源：http://dali.c1oappe.top/Article/details/gt2knscdmfk.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gt2bqxencni.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zxpihnpv.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gt2crzugmdn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2dsnqyhtd.html

[U98] JS：fetch 带 JSON
来源：http://dali.ybcxt.top/Article/details/gt2pqsubacs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gt2kgobaphi.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gt2rpxpgadh.html

el.addEventListener("click", e => {})
来源：http://dali.gzhubu.top/Article/details/gt2moulbtob.html

[U100] JS：DOM 查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2khzdmims.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gt2empdvblk.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gt2qzbqsxjv.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gt2sexwagdz.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gt2afkmmqsf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhixingplan.top/Article/details/gt2hdqczurf.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gt2aiopxkie.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258888.top/Article/details/gt2bfqtfcin.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gt2snoeesyn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2yqzxpypm.html

[U105] JS：节流
来源：http://dali.nanxinkj.top/Article/details/gt2cxsajmes.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2wsvbqduw.html

[U106] JS：日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2nsvwonym.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gt2jpsjyxgj.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gt2suuaebya.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2pkpntabe.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gt2hlbcbnaa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gt2tjwcvudp.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gt2iezsisry.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gt2tbjupvla.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gt2oxljeyfr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gt2atbvyffx.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gt2msohvsfl.html

new Map(Object.entries(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2fkvwiqlk.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gt2nkpobxor.html

"7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2mevhzjhy.html

[U113] JS：正则替换全部
来源：http://dali.fzhhl.top/Article/details/gt2nbrstlsi.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2sgnxfjtz.html

[U114] JS：JSON 深比较
来源：http://dali.0kj1m.cn/Article/details/gt2cioiipsr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gt2zafshvct.html

[U115] JS：生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gt2tylktrqj.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2vadgchlw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gt2tfgjqcfg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shuidangran.top/Article/details/gt2xxwiwoqk.html

[U117] JS：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgdjqeay.html

npm i -D vitest;  npx vitest
来源：http://dali.yonumen.top/Article/details/gt2rrxevmky.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gt2zicidvmw.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwmeeoee.html

[U119] JS：生产构建
来源：http://dali.cheryme.top/Article/details/gt2kutjjcim.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hscgktor.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gt2dmqwkfcr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhengqikj.top/Article/details/gt2cywzjlta.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2oudmsbrl.html

统计汇总
来源：http://dali.yj20258888.top/Article/details/gt2icufjhyh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jekgjpoq.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqksfiiq.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2vlykrpmz.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gt2qskmgqgz.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gt2gzioresp.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gt2jtlwbqbz.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gt2yocfcnca.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftbgoouw.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gt2prwxyola.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gt2kvjdpbgw.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gt2kfdoylaa.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvurrfdk.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gt2cxauviad.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gt2xwnrnucc.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gt2etjefaxg.html

Swift .......... 15
来源：http://dali.hnqzz.top/Article/details/gt2mktsbudy.html

Lua ............ 10
来源：http://dali.jyoumei.cn/Article/details/gt2gdcatswn.html

Perl ........... 10
来源：http://dali.guannengcc.top/Article/details/gt2dpwskiog.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2rfbrvcra.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojawbuem.html

合计 ........... 2106 条
来源：http://dali.meibo888.top/Article/details/gt2clbxstiw.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gt2uewsjrcl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzoxvlc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxypyqdj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2efbubxup.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gt2qlsgdohf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppdbxbob.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gt2mbuqqbuy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2cuykinoe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gt2cayrixpt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2kfjglghd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gt2ibeoqguz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2jmvuqrht.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2dxekbabt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glmiqhmx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gt2vrxbfino.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.mhx1999.top/Article/details/gt2jnfonaay.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2pnvmjutj.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gt2zrjvipgu.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gt2wxhbyyro.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obfjgpvf.html

T 其他语言补充                          60
来源：http://dali.yueranfly.top/Article/details/gt2ynoemjrp.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gt2nipgvgvw.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2uoyoltdg.html

合计                                  2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqhevhmo.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhiebriw.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhutnbmr.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2zrvnmgyp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gt2kkwpytfl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gt2ldiogooo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cozakyto.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuxming.cn/Article/details/gt2qcvmtbaj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gt2tqjsieab.html

—— 文件结束 ——
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxxivgdy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2tiomnfpv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cqqwz.cn/Article/details/gt2nbtdcrzb.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gt2nvybexjr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2opokdaen.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gt2obrlyvfv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuanzhike.top/Article/details/gt2otjixmrt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fzhhl.top/Article/details/gt2bbiggkuv.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gt2sfhgngba.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yangfankeji.com/Article/details/gt2ttiufmgq.html

【使用说明】
来源：http://dali.hfpthk.cn/Article/details/gt2pjnrmbjs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zycfv.cn/Article/details/gt2phxxlmxg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daxiang520.top/Article/details/gt2xisovfob.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aujllxdf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aibaodan.cn/Article/details/gt2vgpjeyym.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gt2psynhsbk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gt2uenwkyne.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jiagoushi.top/Article/details/gt2eiubgfuh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhongyouzk.top/Article/details/gt2ufbuihuo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daria6918.cn/Article/details/gt2qchgyzix.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gt2evxumhet.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrsmijw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangdashe.top/Article/details/gt2qxytlvow.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqnkeke.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tianlin.xyz/Article/details/gt2xxuhpmsr.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2zkvadyhf.html

目  录
来源：http://dali.xuanzx.com/Article/details/gt2gbahtcjd.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2xwcyfobn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gt2zarprwib.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2llrhovtm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gt2vxksslfy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2pzurnolt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gt2fxcfrdpz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gt2dmmjunrm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gt2gbwhtlft.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2tunqjcvh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2nplwrsah.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzyhykaf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2glftdghp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2hmnnjhsk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2gdnanbjc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpdjjnye.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gt2azcfjgpe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2acycwgsr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gt2gcqnxcri.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2xlrwgcqt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.iojbl.cn/Article/details/gt2owqgpsbg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2evnjtwoe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2efxbfbpc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbuyxqcj.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gt2chadmhft.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ayzgjkor.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gt2apefrtzw.html

Py:   print("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipaychmo.html

PHP:  echo "Hello, World!";
来源：http://dali.tianlin.xyz/Article/details/gt2djmmdwtx.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2zlvmnaal.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258888.top/Article/details/gt2ointpysd.html

Java: System.out.println("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swissbaa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gt2zkizmygs.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gt2hutlmyxz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gt2ltzreejr.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gt2cpsbxblv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogdmxulp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2iniekrrj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2qgwyftkm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.c1oappe.top/Article/details/gt2sqxmakyk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gt2kqtqebra.html

Go:   name := "Alex"; age := 20
来源：http://dali.316326.xyz/Article/details/gt2ysjwptgq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgfzy.top/Article/details/gt2nerrxqgb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2pfznnebq.html

[A03] 常量定义
来源：http://dali.jqgufenzy.top/Article/details/gt2qqbxhovc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fengsongda.top/Article/details/gt2yifxtyhe.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2aparjkjf.html

JS:   const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgieprpd.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2taxskkgt.html

Java: static final double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2stycmder.html

Go:   const PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gt2dfnfqcph.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2xoxljign.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pszmdeik.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gt2bksbuvel.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gt2hcluamhv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sweek.top/Article/details/gt2tegofowv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gt2ppwapcyz.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcefctfd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gt2kiyswnfi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ivvv.top/Article/details/gt2ivcxhdug.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gt2raxwentb.html

C#:   x.GetType().Name; x is int
来源：http://dali.gaohongyu789.top/Article/details/gt2gwjfsppq.html

[A05] 整数除法与取模
来源：http://dali.0kj1m.cn/Article/details/gt2mrtyunrm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2pesqxyty.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2bngldmwu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2gwlbxmgk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2vnoclrnt.html

Java: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2rhnxwmpd.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2jpxxyqba.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2hhzanera.html

C#:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2rspfmuio.html

[A06] 字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2ezsxupgu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dungqqvg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gt2qdtdgema.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gt2ibqpnrgh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2qrzmuvsw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.snrcjt.cn/Article/details/gt2rmuhpzte.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yongpay.top/Article/details/gt2nrobfjbt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gt2ctpwveoi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2hpsxgszw.html

[A07] 数字转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezjxrsyx.html

Py:   str(42)
来源：http://dali.daria6918.cn/Article/details/gt2fnfglkoj.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gt2gofqubue.html

JS:   String(42); (42).toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpgwrpqd.html

TS:   String(42)
来源：http://dali.meibo888.top/Article/details/gt2ihcvubtl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.haohaochexian.top/Article/details/gt2awpnsmer.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigufen.top/Article/details/gt2yluegzyx.html

Ruby: 42.to_s
来源：http://dali.jqgfzy.top/Article/details/gt2xjiouyyq.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gt2phusbiul.html

[A08] 取整与四舍五入
来源：http://dali.yj20258.top/Article/details/gt2swxydrvj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bshhycap.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gt2brbdqbaf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gt2ibjszjom.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.aizwys.cn/Article/details/gt2hyklmjoc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gt2lceekkes.html


<!-- 参考信息 -->