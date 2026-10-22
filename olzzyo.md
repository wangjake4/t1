代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2qyuvuafz.html

"值: {$a}"
来源：http://dali.jlsjyb.cn/Article/details/gt2tuufkyog.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gt2htquendo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfeorbxl.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gt2bjypumjy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2davohgkd.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gt2ilujvghp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hywenlv.cn/Article/details/gt2qiihqosk.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gt2ownydgji.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2gercoutz.html

[U62] PHP：日期对象
来源：http://dali.vqdsnc.cn/Article/details/gt2erjzzgzw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gt2xzgngago.html

[U63] PHP：文件读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofnnbdml.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ehwqpu.com/Article/details/gt2jdkpsldr.html

[U64] PHP：目录遍历
来源：http://dali.zhixingplan.top/Article/details/gt2ojaccyot.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xziqi.cn/Article/details/gt2zrhonyry.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gt2mduoxldq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2jtyjhhip.html

[U66] PHP：设置 Cookie
来源：http://dali.ehwqpu.com/Article/details/gt2inuxzhab.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgyoott.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gt2pslwkfrq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sssbvmfr.html

[U68] PHP：PDO 连接
来源：http://dali.tian-w.cn/Article/details/gt2lafuvkfu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cdnleiting.top/Article/details/gt2jrjxucwr.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gt2fpfgesik.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gt2tzmyvupf.html

[U70] PHP：PDO 事务
来源：http://dali.dashuyun.cn/Article/details/gt2ddyulbvh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gt2sosinvxz.html

[U71] PHP：抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2rioihiir.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2ampnnvop.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gt2njlhgevh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gt2ilnkbxmd.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gt2rhrmozef.html

parse_ini_file("config.ini", true)
来源：http://dali.andypj.xyz/Article/details/gt2tmjxopig.html

[U74] PHP：读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2xemjemps.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gt2uergyrif.html

[U75] PHP：依赖注入
来源：http://dali.xuanzx.com/Article/details/gt2myljripg.html

composer require psr/container
来源：http://dali.shuidangran.top/Article/details/gt2rmjefuas.html

[U76] PHP：简单路由
来源：http://dali.yanxiufei.cn/Article/details/gt2fkoyodyn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dianchejie.cn/Article/details/gt2astaxuef.html

[U77] PHP：模板渲染
来源：http://dali.tanke756.top/Article/details/gt2jrjsnyeq.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gt2rydhtilg.html

[U78] PHP：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2ukzbsuxy.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gt2shswrjkk.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gt2czgacoep.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigfzy.top/Article/details/gt2auhgtadg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxhamii.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gt2qogmqetc.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gt2mkxxrabv.html

npm init -y;  npm i express
来源：http://dali.gotoacloud.top/Article/details/gt2bfsjdmxi.html

[U82] JS：package.json 脚本
来源：http://dali.xziqi.cn/Article/details/gt2ntqpnuuk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.quarkkingdee.top/Article/details/gt2sgsrtnsx.html

[U83] JS：ES Module 导入导出
来源：http://dali.guannengcc.top/Article/details/gt2yenuvmpd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.316326.xyz/Article/details/gt2youdluph.html

[U84] JS：CommonJS 写法
来源：http://dali.yj202588.top/Article/details/gt2pscupuyt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dashuyun.cn/Article/details/gt2jcttvutu.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulmqgvij.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gt2eqvwabni.html

[U86] JS：空值合并
来源：http://dali.nanxinkj.top/Article/details/gt2hfosenig.html

a ?? b
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgyzvfgp.html

[U87] JS：解构默认值
来源：http://dali.sweek.top/Article/details/gt2fnwwmwvx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thydqugw.html

[U88] JS：对象展开合并
来源：http://dali.ppjwa.cn/Article/details/gt2qruxycbs.html

{ ...a, ...b }
来源：http://dali.nanxuanxn.top/Article/details/gt2qlfbpeqg.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gt2exycukwi.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2kpzyavwv.html

[U90] JS：数字数组排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khugvdww.html

[...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2dnzhevra.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gt2uxemulyy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xinyue.icu/Article/details/gt2bfraaitx.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gt2iokhxqtl.html

structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2yuroukeh.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gt2vjmckhhn.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gt2rcwgdvym.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2yivfdidk.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvoiqnna.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gt2ggomnlni.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gt2lfsenhin.html

[U96] JS：async/await 与异常
来源：http://dali.jianghu66.top/Article/details/gt2qekjmoxy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2wiemfcsz.html

[U97] JS：并发请求
来源：http://dali.wangdashe.top/Article/details/gt2fjootvfj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpkskdih.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2rbbiczbq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gt2zzpzouxw.html

[U99] JS：事件监听
来源：http://dali.hysaishi.cn/Article/details/gt2akujmppg.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gt2prsxbhti.html

[U100] JS：DOM 查询
来源：http://dali.xziqi.cn/Article/details/gt2sayyokxm.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecewavmt.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gt2vrbscecx.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwtmrnoz.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzkficwd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cskrnugk.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gt2judymqaa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gt2grslmowz.html

[U104] JS：防抖
来源：http://dali.cqqwz.cn/Article/details/gt2pldyjrto.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2bqcjmzsu.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gt2tsudvcwk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gt2jtsbdlvk.html

[U106] JS：日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2dbrfzppz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jianghu66.top/Article/details/gt2iatfikvz.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gt2zonqriph.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gt2vtcgsvhq.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gt2scbhbnis.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jyoumei.cn/Article/details/gt2nqvzmgwo.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2anfvmppx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2okkypucv.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gt2qgivwjgx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangdashe.top/Article/details/gt2rbcuzamu.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyjjdwii.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2taigylur.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gt2dzyszszc.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2udlelsnm.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gt2ubwgkzel.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atmlkkcw.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gt2eucgyczl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2zhefmsnz.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2zfkcbqxy.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egggwblk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pycfn.com/Article/details/gt2tdwekmzn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ifsrsdyx.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gt2vaciuljc.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gt2rwcrwevn.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gt2lcpdsgxt.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gt2icqhnuku.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gt2oaiolher.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gedhkzdd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhoulong.xyz/Article/details/gt2rrvzehup.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gt2geipoqkf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2pupmidsx.html

统计汇总
来源：http://dali.xinyue.icu/Article/details/gt2ftyaaluk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2gwcvpycq.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gt2acpxdinl.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gt2lkwixutk.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gt2txfshznd.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gt2xnagkizp.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gt2abfccisg.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gt2fykokbkt.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gt2yqnyymkf.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2tflfkhxo.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gt2wcqepzdd.html

C .............. 30
来源：http://dali.cdnleiting.top/Article/details/gt2rmdbvzcz.html

C++ ............ 30
来源：http://dali.sufxvd.cn/Article/details/gt2qxrgohsa.html

SQL ............ 90
来源：http://dali.pycfn.com/Article/details/gt2zvhimxhb.html

Bash ........... 80
来源：http://dali.guowangkeji.top/Article/details/gt2jgcqzhxb.html

Kotlin ......... 15
来源：http://dali.zycfv.cn/Article/details/gt2ugfgzrer.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2gzbrllzx.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gt2bbdngjhv.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gt2nkbwnwxf.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gt2gdgiqflw.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltdufmlu.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gt2qhvxrcxm.html

按章节统计：
来源：http://dali.zycfv.cn/Article/details/gt2zckxoxxd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gt2eqgqfzza.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2jsalnoos.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2cjgmazhr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2zvzkqgze.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gt2csftsjrn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2oraarapg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gt2nnqnlovt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gt2yvkeibge.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtxktvdx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gt2xqpwgtem.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2zalzyzqn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2nanargzv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2ssaypdzx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gt2zsvflmsy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gt2cvjgyaal.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2zpzolnqb.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gt2lelxqmkw.html

R Bash 专题                             80
来源：http://dali.jinqigfzy.top/Article/details/gt2pncpelni.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gt2lrtiowwk.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2azrnpbwm.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gt2aaeoemsp.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thtywvue.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gt2tkaszqcw.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2wuhiocnx.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gt2kperqkvt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxmedbw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daxiang520.top/Article/details/gt2ezuzoyzg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gt2mnhyrpwh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gt2xreljves.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gt2ctazwnjg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gt2utjzhnrl.html

—— 文件结束 ——
来源：http://dali.yonumen.top/Article/details/gt2ernyaeia.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2wwxjafxq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yangfankeji.com/Article/details/gt2ziwecmij.html

Common Programming Examples Cheat Book
来源：http://dali.zhixingplan.top/Article/details/gt2zyxofykm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2fajeaavb.html

【收录内容】
来源：http://dali.jqgufenzy.top/Article/details/gt2wfmyhyub.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.andypj.xyz/Article/details/gt2nuzkltme.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yanxiufei.cn/Article/details/gt2kfszngjy.html

SQL · Bash · C · C++
来源：http://dali.snrcjt.cn/Article/details/gt2vxyhvuag.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pycfn.com/Article/details/gt2oqguywjt.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gt2tisuwqqn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sufxvd.cn/Article/details/gt2egomufhr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigfzy.top/Article/details/gt2epbttdta.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhoulong.xyz/Article/details/gt2nyjkxvcc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gt2jbotwltb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gt2efwckeas.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gt2iparhxhp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gt2kmmtbdel.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gt2cchtnhbp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.vqdsnc.cn/Article/details/gt2rjjvavaj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gt2vkvytxib.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ivvv.top/Article/details/gt2ebnamlyr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gt2piwrbtgg.html

【文件统计】
来源：http://dali.jinqigfzy.top/Article/details/gt2daxalaky.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dashuyun.cn/Article/details/gt2xdkqheqc.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkshglek.html

目  录
来源：http://dali.redwolf501.top/Article/details/gt2rmdylrtb.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqtuvnfi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkukpvbs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gt2eycxkvhh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gt2xpoojnlx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gt2lwbdmref.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ydzc1.top/Article/details/gt2taajtxab.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj20258888.top/Article/details/gt2gjfiwfds.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gt2peevnyrc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nghajfka.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2erfmafzw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gt2gorwzbmr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2wwcfxlwa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2govddxhy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gt2cwrfvaqu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoqvcjvp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ppjwa.cn/Article/details/gt2cmawrlvk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gt2pyvnrpvh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gt2oyjdhtxh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hfpthk.cn/Article/details/gt2ttxbvfyp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajfgnhuy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gt2plojcear.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2iizzfvjs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2mzvyeusi.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gt2vftooeqw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2czrnwbtz.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2ouhfobic.html

Py:   print("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gt2chxnndsg.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gt2pbcywmsv.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gt2flskmwmi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj202588.top/Article/details/gt2jfmzrlmo.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2alhdlgom.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gt2xaukbxpf.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjshupfe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2hvlwdnch.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gt2nhnqblab.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.smart0.xyz/Article/details/gt2tbcwcbvw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2jaaaudio.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2lcianeah.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gt2jpgmlgwh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2xbptzern.html

Go:   name := "Alex"; age := 20
来源：http://dali.guannengcc.top/Article/details/gt2nxwwnohg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pycfn.com/Article/details/gt2vdokfhcg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2uqtmmuoe.html

[A03] 常量定义
来源：http://dali.nanxinkj.top/Article/details/gt2mqmjwmcy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenlongwang.top/Article/details/gt2ykxcmaty.html

PHP:  const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2kbhfjxkj.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2xfzsstjq.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2uaqsxygh.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2hfpjeset.html

Go:   const PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gt2vtqzhahs.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gt2blzrreak.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2mvawbqkt.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gt2ugnnhblv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gt2iwgvymyr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odsoavqn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhpsugzk.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gt2maqdmfpj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gt2zcvmhljo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtgdugdm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sysykeji.top/Article/details/gt2stybnxxn.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnqzz.top/Article/details/gt2xlemyshr.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gt2pqpntubc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gt2wnlrvkhp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2qaonofwh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2sveblnns.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2zplvbctk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2ykqeunob.html

Go:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2speuiriu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2zokhyszh.html

C#:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2rweohprm.html

[A06] 字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gt2njwvopqd.html

Py:   int("42"); float("3.14")
来源：http://dali.ydzc1.top/Article/details/gt2ofoqsbwc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gzhubu.top/Article/details/gt2wtbatysb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gt2bkqjdepe.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.bjfxy.top/Article/details/gt2lqqupmpp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2vinlxqek.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gt2vzbcaoln.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gt2ccrgmmlv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ydzc1.top/Article/details/gt2gzcjgxcp.html

[A07] 数字转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ictivfie.html

Py:   str(42)
来源：http://dali.zhixingplan.top/Article/details/gt2jejsmhag.html

PHP:  (string) 42; strval(42)
来源：http://dali.316326.xyz/Article/details/gt2uojwrfqh.html

JS:   String(42); (42).toString()
来源：http://dali.andypj.xyz/Article/details/gt2hdapvtdh.html

TS:   String(42)
来源：http://dali.haohaochexian.top/Article/details/gt2arpolngr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gt2fcomhflp.html

Go:   strconv.Itoa(42)
来源：http://dali.iojbl.cn/Article/details/gt2xypaukpw.html

Ruby: 42.to_s
来源：http://dali.shuidangran.top/Article/details/gt2xynewdjk.html

C#:   42.ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2lnybbvrm.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gt2xckhjhbe.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2oqbxdihn.html


<!-- 参考信息 -->