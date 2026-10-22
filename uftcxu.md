代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2jljbgocg.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfltnbeq.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gt2knsjgnsh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2qavjxodk.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gt2igtypbnf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2ajvqtnwz.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gt2nshcotfk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2kekvietn.html

[U61] PHP：正则
来源：http://dali.chenzaomai.com/Article/details/gt2rjmskgfr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2iebzovqy.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gt2lylhatxd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gt2fhmvqola.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gt2yfoyonls.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gt2pnmklrdc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcpwkql.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltrelljs.html

[U65] PHP：会话
来源：http://dali.hammf.cn/Article/details/gt2kgnljhxr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2fewkhmya.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgehugwv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gt2omhfxgvv.html

[U67] PHP：处理文件上传
来源：http://dali.cdnleiting.top/Article/details/gt2mkezdzgh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ehwqpu.com/Article/details/gt2niekckie.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2klcoihuf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gt2dtatrdob.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gt2hdcnhipu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gt2hafedykn.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gt2dsrjuvzt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cheryme.top/Article/details/gt2lazoizrh.html

[U71] PHP：抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gt2vzwxaodd.html

throw new RuntimeException("失败", 500);
来源：http://dali.xziqi.cn/Article/details/gt2nopqassn.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gt2sgimvign.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gt2ujvqmxdx.html

[U73] PHP：读取 ini 配置
来源：http://dali.bjfxy.top/Article/details/gt2klalrnxc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhiwuduotai.top/Article/details/gt2umzuknce.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2vnejnhif.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zycfv.cn/Article/details/gt2cefmnpvd.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gt2tszpbstz.html

composer require psr/container
来源：http://dali.dianchejie.cn/Article/details/gt2dvvontlo.html

[U76] PHP：简单路由
来源：http://dali.yongpay.top/Article/details/gt2tywevbzv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pengpengdd.cyou/Article/details/gt2sctwhlie.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gt2wfckktyt.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gt2jihgpgrv.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2yhabgazr.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gt2iczyfcdl.html

[U79] PHP：静态分析
来源：http://dali.cheryme.top/Article/details/gt2axtixnag.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gt2abosasdt.html

[U80] PHP：代码规范修复
来源：http://dali.cqqwz.cn/Article/details/gt2elshxplu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daxiang520.top/Article/details/gt2xskwyxhh.html

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gt2eyirnapm.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gt2mkskpirw.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gt2qcideaje.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gt2uasifjhv.html

[U83] JS：ES Module 导入导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ripdyfwt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2mfmiqmiy.html

[U84] JS：CommonJS 写法
来源：http://dali.chenzaomai.com/Article/details/gt2rfqkhziv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gt2lzfdixuu.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gt2asflfsws.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gt2zzrzyrax.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gt2skblyfco.html

a ?? b
来源：http://dali.gzhubu.top/Article/details/gt2slyzdhbl.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gt2mxascbsl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.quarkkingdee.top/Article/details/gt2mdgwxcgj.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gt2jxnccvuk.html

{ ...a, ...b }
来源：http://dali.svipenyu.cn/Article/details/gt2apdybwaf.html

[U89] JS：数组去重
来源：http://dali.ydzc1.top/Article/details/gt2ckxijoce.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2yezvavom.html

[U90] JS：数字数组排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2atezjtzy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkzaempz.html

[U91] JS：对象键值遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixnkxelr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sweek.top/Article/details/gt2tozhaqar.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gt2aiiuzdbk.html

structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ugmjhxgw.html

[U93] JS：模板字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwzsfhlw.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gt2pojjsvfe.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gt2wzvrjift.html

const double = x => x * 2;
来源：http://dali.ehwqpu.com/Article/details/gt2hfifadpt.html

[U95] JS：Promise 包装
来源：http://dali.fengsongda.top/Article/details/gt2kniwqorz.html

new Promise((resolve, reject) => {})
来源：http://dali.hnqzz.top/Article/details/gt2quwigdcr.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gt2gayyjqxs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nqxqaahz.html

[U97] JS：并发请求
来源：http://dali.nanxuanxn.top/Article/details/gt2btoxyamg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2ksliamej.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258888.top/Article/details/gt2wenleunr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aibaodan.cn/Article/details/gt2qqxvcwif.html

[U99] JS：事件监听
来源：http://dali.zycfv.cn/Article/details/gt2wmugoxek.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gt2accckhcq.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gt2uncficxc.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gt2leqhryvg.html

[U101] JS：classList 操作
来源：http://dali.meibo888.top/Article/details/gt2btepxspf.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjbaxkor.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gt2nalsaafx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gt2lammawlx.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aychroyn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hfpthk.cn/Article/details/gt2qvjbuuak.html

[U104] JS：防抖
来源：http://dali.fzhhl.top/Article/details/gt2olvxgzcp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2immnponz.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gt2hvowabcj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gt2eonncfaz.html

[U106] JS：日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2dcpmocve.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gt2vbmnitbz.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2espdoqcd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2ltbnheop.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gt2neeoecad.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gt2ymjmldub.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2iolwiusu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2zrqeetfg.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypojnidw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.havefunace.top/Article/details/gt2hpbdchvf.html

[U111] JS：对象转 Map
来源：http://dali.pycfn.com/Article/details/gt2jpahfhrr.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2fmefxzdp.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gt2oviqiebq.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hopwrhqf.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gt2nzhjcqzr.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2nrffzmzj.html

[U114] JS：JSON 深比较
来源：http://dali.9152youxi.cn/Article/details/gt2wbddjwjh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gt2xntdpnnf.html

[U115] JS：生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzfqspff.html

crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2gfsvwhnk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gt2wskqltpf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fengsongda.top/Article/details/gt2izppvpie.html

[U117] JS：单元测试
来源：http://dali.svipenyu.cn/Article/details/gt2jhcvbaga.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gt2rznmbfvb.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gt2aojntknq.html

npm i -D vite;  npx vite
来源：http://dali.yueranfly.top/Article/details/gt2zrtilbhf.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gt2icyhiizn.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffiglrcv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gt2buhwdegj.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gt2kvdqnmmp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2tuvcpkqy.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gt2lbmjcnal.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2petonjxa.html

按语言统计（条）：
来源：http://dali.tian-w.cn/Article/details/gt2xwkseehz.html

Python ......... 252
来源：http://dali.tanke756.top/Article/details/gt2ozdzqkns.html

PHP ............ 252
来源：http://dali.gotoacloud.top/Article/details/gt2qcmxlmyl.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gt2rityvkkw.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gt2uoymiygl.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gt2bvfqmeam.html

Go ............. 212
来源：http://dali.jianghu66.top/Article/details/gt2ruwurwfw.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2ymtrejbg.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gt2hyqeweys.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gt2pdwqkusy.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyssjlra.html

SQL ............ 90
来源：http://dali.yonumen.top/Article/details/gt2ovbjpbkx.html

Bash ........... 80
来源：http://dali.fzhhl.top/Article/details/gt2aqdrxiro.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gt2xntgmpel.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2lsznbzfw.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gt2ojmezlag.html

Perl ........... 10
来源：http://dali.kuanghao11.cn/Article/details/gt2bjaajcqa.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gt2wshlzghx.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2vpqlwgua.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gt2wiwdkrlh.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gt2dzsydctu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gt2ttvrtqmt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iziyjjkx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqevjcyo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gt2fgsoipld.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gt2dnwqqlmc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gt2vmogqjtg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2idgfyths.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gt2aakvsqaf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2lddwdyku.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gt2vlaewgny.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2mvxxvlbx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2mlhfjktw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2oeaxebrs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gt2uwnezhyz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gt2suulkgcp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdmwjkvl.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gt2xogjyzqx.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gt2jlveuqaq.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gt2ldqgphfc.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqqndihg.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdleenqg.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2rnjlysrk.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frewjbaw.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2wakrpwix.html

使用提醒
来源：http://dali.nanxinkj.top/Article/details/gt2vakvpxrv.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gt2eyhfwawg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gt2wffwxenk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gt2vlynwgyj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgyhxxcy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgabpolg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gt2gzoumtau.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgylzckb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmxkvnam.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zdqjudy.top/Article/details/gt2xgymxnyx.html

Common Programming Examples Cheat Book
来源：http://dali.cqqwz.cn/Article/details/gt2bzdzhlgy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2fmoinybt.html

【收录内容】
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuxdfsem.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yongpay.top/Article/details/gt2tbedvnmn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gezlboiq.html

SQL · Bash · C · C++
来源：http://dali.ehwqpu.com/Article/details/gt2abhspxls.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gogol.net.cn/Article/details/gt2gljqdlcj.html

【使用说明】
来源：http://dali.gaohongyu789.top/Article/details/gt2vwlxdcnv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gt2gdfxlxux.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuanzhike.top/Article/details/gt2kspsighe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fzhhl.top/Article/details/gt2qkogacpe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xziqi.cn/Article/details/gt2vjrpbjvx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gt2wbczfnfd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gogol.net.cn/Article/details/gt2jkvhxnbo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.dashuyun.cn/Article/details/gt2eudcwdil.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gt2earajuan.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj202588.top/Article/details/gt2ldwseuln.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.redwolf501.top/Article/details/gt2pmopecyo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.andypj.xyz/Article/details/gt2pemurpzv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigfzy.top/Article/details/gt2jzdamfvg.html

【文件统计】
来源：http://dali.feifeiyinyue.top/Article/details/gt2uedyxjxh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gt2auufggec.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2wcnckwyv.html

目  录
来源：http://dali.nanxuanxn.top/Article/details/gt2kyuzfhnh.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2jlfalegz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gt2aariuear.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gt2ezjrmpgy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2zbivnvwm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gt2hhnnhayl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyulagiz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2zyywzwkd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gt2bculgpzk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2wfwdwauh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2zmfsbzzm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2pzldwoyz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2yixxywcj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2zunumwln.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2osbomlko.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gt2uxdairfj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gt2bqhcwtpa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2cbipzkxo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.snrcjt.cn/Article/details/gt2ogbvjtoy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gt2jxjxauln.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2whgfhjuj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2fxxekavk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwktkgfj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2umdbipzl.html

A. 基础语法与类型
来源：http://dali.hnqzz.top/Article/details/gt2dsuglghc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bntozkdi.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2cdeazetg.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gt2xjdkutdp.html

PHP:  echo "Hello, World!";
来源：http://dali.xuanzx.com/Article/details/gt2tqumbvkk.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2jftwdgok.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigufen.top/Article/details/gt2ouchwkwt.html

Java: System.out.println("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gt2nnzjvhfo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhshrsyz.html

Ruby: puts "Hello, World!"
来源：http://dali.0kj1m.cn/Article/details/gt2atvohnvx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gt2ygubqglt.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gt2uoeyfasq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.smart0.xyz/Article/details/gt2cfzitmqb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2uiiwkurq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2ccuokyxp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2odvubgbn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2trrdmwac.html

Go:   name := "Alex"; age := 20
来源：http://dali.zycfv.cn/Article/details/gt2jfljogpn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangshuangyany.cn/Article/details/gt2ampadssy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2wwoortph.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gt2jdvampta.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daxiang520.top/Article/details/gt2lusqezyu.html

PHP:  const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2dnobncmv.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2xipqludr.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2kqnlmrdk.html

Java: static final double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2bfedaxxi.html

Go:   const PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gt2cnidgeap.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2ibwvpunx.html

C#:   const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmwlegwd.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gt2anbwxbty.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gt2wbzgejgy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2pbxvpten.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gt2eqixylcd.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gt2fvswppqi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guannengcc.top/Article/details/gt2evmtmucu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpxfrbnu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gt2kymbjdrz.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gt2jbgletxm.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gt2uzpgwqvc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jlsjyb.cn/Article/details/gt2aaztteco.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2aptvrmcx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2jqipxufz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2vnkyzhdr.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2nixpevzt.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2dchbmjmw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2zcfhnaww.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2sreadmsu.html

[A06] 字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gt2qusmfbvu.html

Py:   int("42"); float("3.14")
来源：http://dali.ehwqpu.com/Article/details/gt2tthaviic.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zycfv.cn/Article/details/gt2lfcutygv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.316326.xyz/Article/details/gt2zcxzqjyp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hspvsscn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctapfdab.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guowangkeji.top/Article/details/gt2mlmvsvbo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zdqjudy.top/Article/details/gt2dfhwkpag.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ybcxt.top/Article/details/gt2cozrkici.html

[A07] 数字转字符串
来源：http://dali.xinyue.icu/Article/details/gt2qgwjeavh.html

Py:   str(42)
来源：http://dali.sysykeji.top/Article/details/gt2rvofgzhp.html

PHP:  (string) 42; strval(42)
来源：http://dali.tanke756.top/Article/details/gt2roeomgcx.html

JS:   String(42); (42).toString()
来源：http://dali.xziqi.cn/Article/details/gt2hqedigwp.html

TS:   String(42)
来源：http://dali.zhoulong.xyz/Article/details/gt2ohfbgsxf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shzxlz.cn/Article/details/gt2mkyhtafu.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gt2bbveabxn.html

Ruby: 42.to_s
来源：http://dali.zhengqikj.top/Article/details/gt2qsivztoa.html

C#:   42.ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2foohzuna.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gt2xtipunuj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gt2tbtblhnt.html


<!-- 参考信息 -->