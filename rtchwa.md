代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.nanxuanxn.top/Article/details/gtugamhkaq.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gtbinwpiqc.html

[U54] PHP：空安全调用
来源：http://dali.yangfankeji.com/Article/details/gtkztmeoxo.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gttdpdkjnh.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtxageqyes.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtskvfkefp.html

[U56] PHP：命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtsnopsmfa.html

f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gttnuhymab.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gttbdzgqtv.html

"值: {$a}"
来源：http://dali.pycfn.com/Article/details/gtvrjzmaev.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrykgjze.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gtmhwbjora.html

[U59] PHP：自定义排序
来源：http://dali.gaohongyu789.top/Article/details/gtpgxycejs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtnoilqxow.html

[U60] PHP：JSON 编解码
来源：http://dali.gaohongyu789.top/Article/details/gtcrastump.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtucjitdaq.html

[U61] PHP：正则
来源：http://dali.chenlongwang.top/Article/details/gtjfwahmbg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtrbmbflbs.html

[U62] PHP：日期对象
来源：http://dali.aizwys.cn/Article/details/gtnwxyutpd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hfpthk.cn/Article/details/gtmzhlislr.html

[U63] PHP：文件读写
来源：http://dali.zycfv.cn/Article/details/gttvprgnud.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gtprxrejxp.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gtkisxpxzc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenzaomai.com/Article/details/gtmbyybfxb.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gtldozykuq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtotxjmzdo.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258.top/Article/details/gtxhvwqfhi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gtqdyoajwp.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gtblyewhyv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yueranfly.top/Article/details/gtlfkhnsyx.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gtxvfqvakf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fengsongda.top/Article/details/gtbwxnqcaz.html

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gtfmivjafu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zycfv.cn/Article/details/gtsgrnsqay.html

[U70] PHP：PDO 事务
来源：http://dali.havefunace.top/Article/details/gtlkrxsopd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shangyingyoupin.top/Article/details/gticgbgzdl.html

[U71] PHP：抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtfjbdxxky.html

throw new RuntimeException("失败", 500);
来源：http://dali.jlsjyb.cn/Article/details/gttmzkwjdd.html

[U72] PHP：写错误日志
来源：http://dali.ivvv.top/Article/details/gtzcztvymh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtqrjidxcd.html

[U73] PHP：读取 ini 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcftmetr.html

parse_ini_file("config.ini", true)
来源：http://dali.tanke756.top/Article/details/gtfvuookgr.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtuwlwbpnd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscgzysfy.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gtbyrorvcs.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gtpobphiqs.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gttiotdfii.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.redwolf501.top/Article/details/gtvxxcddaa.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gtctacyuav.html

composer require twig/twig
来源：http://dali.zhoulong.xyz/Article/details/gtehiicgxz.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtefkskkrp.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtgnykefby.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gtvpzmigry.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gtuylvtamr.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gtzsehqsrk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ybcxt.top/Article/details/gtghwgsesd.html

[U81] JS：初始化项目
来源：http://dali.zhiwuduotai.top/Article/details/gtwfhmdftl.html

npm init -y;  npm i express
来源：http://dali.svipenyu.cn/Article/details/gtyqjsbaah.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gthbupqcuk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gtushbygxu.html

[U83] JS：ES Module 导入导出
来源：http://dali.feifeiyinyue.top/Article/details/gtudhvlesf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtsskaogaj.html

[U84] JS：CommonJS 写法
来源：http://dali.cashguo.top/Article/details/gtjmnnolgh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.meibo888.top/Article/details/gtteurshtp.html

[U85] JS：可选链
来源：http://dali.chenzaomai.com/Article/details/gtwpxaefvx.html

a?.b?.c
来源：http://dali.feifeiyinyue.top/Article/details/gtsbriiela.html

[U86] JS：空值合并
来源：http://dali.zdqjudy.top/Article/details/gtgcagpbwk.html

a ?? b
来源：http://dali.hammf.cn/Article/details/gtjxuwrlms.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtubzelbdr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gtxbmrotei.html

[U88] JS：对象展开合并
来源：http://dali.pengpengdd.cyou/Article/details/gtzcfiszic.html

{ ...a, ...b }
来源：http://dali.ivvv.top/Article/details/gtybqwdaqw.html

[U89] JS：数组去重
来源：http://dali.wangshuangyany.cn/Article/details/gtgosxwbxa.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtcrfxcuoo.html

[U90] JS：数字数组排序
来源：http://dali.gogol.net.cn/Article/details/gtztjpzwms.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtwookskkb.html

[U91] JS：对象键值遍历
来源：http://dali.hysaishi.cn/Article/details/gtuyqsuazh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gogol.net.cn/Article/details/gtzeladtpv.html

[U92] JS：深拷贝
来源：http://dali.cqqwz.cn/Article/details/gtnirstxmz.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtyygxasai.html

[U93] JS：模板字符串
来源：http://dali.tianlin.xyz/Article/details/gtrujskrwv.html

`共 ${n} 条`
来源：http://dali.xylfe.cn/Article/details/gtmnjyylwb.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtkpxvxrig.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtwnbfcxzk.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gtmhvkhyli.html

new Promise((resolve, reject) => {})
来源：http://dali.tianlin.xyz/Article/details/gtyrbbtehz.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gtfkbmfawg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtwnkakims.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuehmzkq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtuqhhbuih.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gtyxdotqka.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gtpwlmzulj.html

[U99] JS：事件监听
来源：http://dali.yueranfly.top/Article/details/gtypgmxzwb.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gtblehnlme.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gtgiixtnzr.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gtgenrkqpy.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gtugvxrqxx.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gtwmuncxlv.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfnhfvrb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gtsqsutfas.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntgxvwiv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gteasmphve.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnqegwzv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtxgkxwrou.html

[U105] JS：节流
来源：http://dali.zdqjudy.top/Article/details/gterpozfcp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gtcxbvilyn.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gterrzqlzk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgfzy.top/Article/details/gtzmdjxsbd.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gtnmwdgfwl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtawhntamv.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqyecsbl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hfpthk.cn/Article/details/gtnalcqqzt.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtzeqvaogg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gttvvehhye.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtlbuafz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gtfcpunzwa.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtustzoukn.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gtsmtaddls.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gtfxwhllma.html

"7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtgbrgxame.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gtlpwgzkit.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtrjfcmeks.html

[U114] JS：JSON 深比较
来源：http://dali.gzhubu.top/Article/details/gtzzdfqbbu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtlyvmtage.html

[U115] JS：生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gtigpcsvte.html

crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gthzphmqwx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtiqayoreo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtlyyctuac.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gtdbjfwtyb.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gtimlnsjrq.html

[U118] JS：开发服务器
来源：http://dali.fzhhl.top/Article/details/gtkaeihuva.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiwcnvfp.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtugcgabcm.html

npx vite build
来源：http://dali.zdqjudy.top/Article/details/gtxyvvyicl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pengpengdd.cyou/Article/details/gtyrrfgldb.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtmhiwwpxh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwxvvnnay.html

统计汇总
来源：http://dali.andypj.xyz/Article/details/gtmisfjoft.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkcegiome.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtccrnyqhr.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gtstlwirzb.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtvsgdktbj.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtcinrhfnv.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gtkiryvfgb.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtlghpfetd.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtbnnfwqrs.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtgtiiglaj.html

C# ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtztlimbub.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtdcxiuvye.html

C++ ............ 30
来源：http://dali.fengsongda.top/Article/details/gtprweogld.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gtrplyykle.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtbdkmulzk.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gtuaumutdm.html

Swift .......... 15
来源：http://dali.daxiang520.top/Article/details/gtpflepyxw.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gtjuknyqti.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtxsndmukx.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtxcgvunsy.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtdaylsczp.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gtcftuyajb.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtdwomlkun.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvpwyhtt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtcbszwssg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtvosnwhym.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gtuslyvewv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gttczywxuq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gtibssyitr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtqmfijzxb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtvqbjxrwe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtnqdlnyth.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsskkspo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtaqjquiai.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gticgbkxuw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddjuaesn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtsspbbfnf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gtxygkvppy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gttcsmiiys.html

Q SQL 专题                              90
来源：http://dali.cdnleiting.top/Article/details/gtsxwvnmlq.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gtoaxqeixx.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gtdinhfeiu.html

T 其他语言补充                          60
来源：http://dali.ybcxt.top/Article/details/gtijhpgqoy.html

U 高频实用片段                         120
来源：http://dali.jinqigufen.top/Article/details/gtyzqyxqwf.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtvsupyjnu.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gtunwusudq.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtzfdeyxym.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gtunyquwrs.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtvcwacmsx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hysaishi.cn/Article/details/gtgqtexpnv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.feifeiyinyue.top/Article/details/gtvdwfuple.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhoulong.xyz/Article/details/gtuwbuaiww.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gtinsszgoi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sweek.top/Article/details/gtofbohajf.html

—— 文件结束 ——
来源：http://dali.chenjidiqi.icu/Article/details/gtctcwgbrt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdqsxfsie.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gtcjwctxng.html

Common Programming Examples Cheat Book
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwurkthc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttcrhbutn.html

【收录内容】
来源：http://dali.andypj.xyz/Article/details/gtmzdwzvcv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gtbtcyqebz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtvzilutkb.html

SQL · Bash · C · C++
来源：http://dali.ydzc1.top/Article/details/gtxzvuhkbh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shuidangran.top/Article/details/gtqowyjfxh.html

【使用说明】
来源：http://dali.sufxvd.cn/Article/details/gtkebnjhip.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yvedp.cn/Article/details/gtqzwdroyl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgfzy.top/Article/details/gttwwppcoe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjkrozre.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hongshengwenyu.top/Article/details/gtupnadkei.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gtpmelzhgt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnqzz.top/Article/details/gtomochaaw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gtuyijyqxg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gtoysjywya.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.bjfxy.top/Article/details/gtksedpuet.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gttspmaeos.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gtluwphlxg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gtvrpdzyxw.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gtqwvfzybl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.316326.xyz/Article/details/gtpklewkub.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtlmkrwaju.html

目  录
来源：http://dali.yueranfly.top/Article/details/gthtfpqiyf.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtzojcjpfl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtefaeeazz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtovyhcljo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtmgfyugdr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gtaplykwag.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gtwygqvqni.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtpkoivkub.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtzflnlcvy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtidbrmvqb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtnavecqwr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtaqnnkxzr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtcwkkhqjw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtsaadhtvn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtmjojryjq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtaiulndck.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtrfbzifjx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtcytdsmfa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gtbvnsohdq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gtohoifpob.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gtozfcjumd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gthcnqzgne.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gtkewzoslb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgcuovtcj.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gtdhwhllpj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthsomzmyb.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gtkibxidxy.html

Py:   print("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtaeaeaopq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gtmtniwjgr.html

JS:   console.log("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtbbrqfmlr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuetiantiany.cn/Article/details/gtbkrelzbu.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtxulrkuup.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gtptivajuf.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gtgaobvxgp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtjvbiykds.html

[A02] 变量声明与赋值
来源：http://dali.ppjwa.cn/Article/details/gtovdevuxf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtvfbwqefo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.aibaodan.cn/Article/details/gtquoumdmn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.316326.xyz/Article/details/gtztnzikoa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnebxfcwv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgwcyiak.html

Go:   name := "Alex"; age := 20
来源：http://dali.cheryme.top/Article/details/gtzrqyicsg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkqorbfy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtnwxlzffo.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gtryfwpxzd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xuetiantiany.cn/Article/details/gtgvfroupl.html

PHP:  const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtfohqqgmy.html

JS:   const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtukcjellz.html

TS:   const PI: number = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtuxdwcsws.html

Java: static final double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtxerabwpp.html

Go:   const PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gtvjufbgzf.html

Ruby: PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gtkmrijpnc.html

C#:   const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtwncbusbp.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtdnxhxibi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gogol.net.cn/Article/details/gtryqsrlub.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zycfv.cn/Article/details/gtmunnlgpd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtawngbtmz.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtmnxkdbfo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinghuilouyu.cn/Article/details/gtisfuueac.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj20258.top/Article/details/gtxqrrtsao.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gthbsooeun.html

C#:   x.GetType().Name; x is int
来源：http://dali.316326.xyz/Article/details/gtxldctlaw.html

[A05] 整数除法与取模
来源：http://dali.sxryk.cn/Article/details/gtaxchmdmn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cheryme.top/Article/details/gtesgyjurn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtffypaxyf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtnvhntwqv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtpickkvss.html

Java: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtdcsouvcr.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtgxopwfyd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtpoiqqbdc.html

C#:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtaeyrxprj.html

[A06] 字符串转数字
来源：http://dali.yj20258.top/Article/details/gtfvwvggwh.html

Py:   int("42"); float("3.14")
来源：http://dali.xylfe.cn/Article/details/gtxfzgtpbw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hysaishi.cn/Article/details/gtxeeqaswq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhoulong.xyz/Article/details/gtgoznqcgr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtcmzafdta.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gtrwyhcian.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xuanzx.com/Article/details/gtqmatdegu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gtdpolnbjy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cucudq.cn/Article/details/gtpgbphhvd.html

[A07] 数字转字符串
来源：http://dali.xylfe.cn/Article/details/gtmrxhedqi.html

Py:   str(42)
来源：http://dali.sxryk.cn/Article/details/gtuxtiiddx.html

PHP:  (string) 42; strval(42)
来源：http://dali.cashguo.top/Article/details/gtzipvczij.html


<!-- 参考信息 -->