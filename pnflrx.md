代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.nwbrower.top/Article/details/gtqbonrdmq.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtosnvvved.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gtprukiqim.html

declare(strict_types=1);
来源：http://dali.tian-w.cn/Article/details/gtsqekhnnf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtbufquoys.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtmtakgcie.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gthrielptz.html

?string $name = null
来源：http://dali.yueranfly.top/Article/details/gtfztqpcgi.html

[U47] PHP：联合类型
来源：http://dali.0kj1m.cn/Article/details/gtxkgieota.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gtsglpypgh.html

[U48] PHP：纯枚举
来源：http://dali.sxryk.cn/Article/details/gtmjwvzmrf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gtlugxnrgi.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gtwdyeejwd.html

public readonly string $name
来源：http://dali.hfpthk.cn/Article/details/gtnxxqkims.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtzujyqvju.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gtekwmukzb.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gtaurfbvnk.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gtsxyhqzzh.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtcnjjhrwc.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtgkirhiyl.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gtgmpwfnkj.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttntcgctu.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gtnzykhyzu.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gthsuvntml.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtepbhlsqg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtnpqqrjms.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gtuxkakozg.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtgzvyddyr.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtihnfrbqa.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gttlewwqdj.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gtrmwuptyp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.smart0.xyz/Article/details/gtrlaysfkn.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gtzbqomwfa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekmpyadb.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gtmwvcbrfs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yanxiufei.cn/Article/details/gtdegghafk.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gtaikvessy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gthuhlbqkz.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtuacvyzqr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtkifygrct.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gtlqvnrley.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtzegkreiw.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gtesxwnizq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gtnlnlrqvk.html

[U65] PHP：会话
来源：http://dali.cashguo.top/Article/details/gtcdwjasdx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtaudaesya.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gtozpnhjqy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nwbrower.top/Article/details/gtnhjxukzm.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gtsnsrmguh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gtgniclzbz.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gtsbauxfqw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.haohaochexian.top/Article/details/gtgcxjulxx.html

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gteimlhstg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtjkmxhzkk.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtbybjkfpt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gtrysflyjm.html

[U71] PHP：抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwqaecrq.html

throw new RuntimeException("失败", 500);
来源：http://dali.tanke756.top/Article/details/gtlmuirale.html

[U72] PHP：写错误日志
来源：http://dali.zycfv.cn/Article/details/gtqhoeqojp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtrrivficy.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gtlivnkckd.html

parse_ini_file("config.ini", true)
来源：http://dali.smart0.xyz/Article/details/gtzvtvgtlv.html

[U74] PHP：读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtevpmdlbr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtgrxojvsi.html

[U75] PHP：依赖注入
来源：http://dali.jianghu66.top/Article/details/gtcbukzkfe.html

composer require psr/container
来源：http://dali.hysaishi.cn/Article/details/gtwtklxkhz.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gteywbpvmm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gtdbfgzcim.html

[U77] PHP：模板渲染
来源：http://dali.zycfv.cn/Article/details/gtmbtuhdga.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gttwvyppkw.html

[U78] PHP：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gtskjsuspv.html

composer require --dev phpunit/phpunit
来源：http://dali.smart0.xyz/Article/details/gtfndhvlhk.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gtbvlrmmvh.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gturkipunh.html

[U80] PHP：代码规范修复
来源：http://dali.dianchejie.cn/Article/details/gthbbswdfz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gttmmybyjk.html

[U81] JS：初始化项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyjawins.html

npm init -y;  npm i express
来源：http://dali.sweek.top/Article/details/gthsemkhnq.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gtkmjjsqyy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gtaxoydatf.html

[U83] JS：ES Module 导入导出
来源：http://dali.cashguo.top/Article/details/gtsyekjvke.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtqzrujeoq.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgufenzy.top/Article/details/gtbcwhlwxj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gtuniberda.html

[U85] JS：可选链
来源：http://dali.9152youxi.cn/Article/details/gtmlrbipxm.html

a?.b?.c
来源：http://dali.0kj1m.cn/Article/details/gtizdkyodf.html

[U86] JS：空值合并
来源：http://dali.9152youxi.cn/Article/details/gtlqibqsuf.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gtchggtsom.html

[U87] JS：解构默认值
来源：http://dali.dashuyun.cn/Article/details/gtdvsuzeoo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gtkbyavjtx.html

[U88] JS：对象展开合并
来源：http://dali.guannengcc.top/Article/details/gtjtywwbyn.html

{ ...a, ...b }
来源：http://dali.jyoumei.cn/Article/details/gtcsjomxwb.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gtlbtrqivc.html

[...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtmeyviyba.html

[U90] JS：数字数组排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdakmmmo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtywizxyhi.html

[U91] JS：对象键值遍历
来源：http://dali.zhoulong.xyz/Article/details/gtvizrjsym.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gtmroxqoad.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtkygavtuh.html

structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtxndvpdlz.html

[U93] JS：模板字符串
来源：http://dali.xuetiantiany.cn/Article/details/gttrfbbccu.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gtodayekxf.html

[U94] JS：箭头函数
来源：http://dali.ybcxt.top/Article/details/gtblgldolt.html

const double = x => x * 2;
来源：http://dali.gogol.net.cn/Article/details/gtrulotfze.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gthharwgov.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gthufqaxxj.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gtikyftjbu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtwnzvvpjv.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gtnozbwncw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtuxepxgnb.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gtkbxvaemj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuetiantiany.cn/Article/details/gthcojjcox.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtsuyacahp.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gtxsocnrye.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gtnnoxcskn.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtgkjbwqdj.html

[U101] JS：classList 操作
来源：http://dali.jiagoushi.top/Article/details/gtckdutoms.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gtgzgordfx.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntwrzeyq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cdnleiting.top/Article/details/gtpklzivgm.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gtocaudkfj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gtkvdclyay.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gtnklzmslb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdxexihz.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gtuqozcffj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwsvbxxn.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxttpecm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gtujoatizd.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtnbpjtrcb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtgiisdbys.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtfnzvmmiy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gtwlunpuvl.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gtbqpnitih.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtfkmtnnvh.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gtbombtbxl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtsmibfuau.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gtogcddilo.html

new Map(Object.entries(obj))
来源：http://dali.cashguo.top/Article/details/gtkxberxpg.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gtqrmbmzjj.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmibbkttl.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gtcjkcgeeo.html

s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtzzcsoxep.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtamapwkpj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtzqluuxat.html

[U115] JS：生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtaanzcfua.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtudwugcci.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtyqevhaec.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gtmacuecko.html

[U117] JS：单元测试
来源：http://dali.gzhubu.top/Article/details/gturwfomro.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gtzuiwqrat.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtaaeaapba.html

npm i -D vite;  npx vite
来源：http://dali.yj20258888.top/Article/details/gtkuwynhlt.html

[U119] JS：生产构建
来源：http://dali.mhx1999.top/Article/details/gtngmquaxw.html

npx vite build
来源：http://dali.haohaochexian.top/Article/details/gtlvpkazst.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gtpmfsjiqm.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtshuzjqqx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwjrpgjww.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gtkcvigkje.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtihxxzoys.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gtvbjlmxgz.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gtaobwxiks.html

PHP ............ 252
来源：http://dali.haohaochexian.top/Article/details/gtlrimkdov.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtojdbphmv.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gtdyrlxyqm.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtxaudikju.html

Go ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhinawjb.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtcoeekxhy.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gtyecusqdy.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gtwmccgplm.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gtjnlucrub.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gthamglbbm.html

Bash ........... 80
来源：http://dali.0kj1m.cn/Article/details/gtunoqwnmz.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtijecqpud.html

Swift .......... 15
来源：http://dali.ivvv.top/Article/details/gtwmxpafwb.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtaveglxmd.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gtowbetpil.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gtlrniulao.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtrkkrtbvk.html

合计 ........... 2106 条
来源：http://dali.hywenlv.cn/Article/details/gtdjyoqetj.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gtoffvwnoo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gteoloqovo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtbsuaeswu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtjdgvckwt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtijzqdrdv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gtwmohcccm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtwggmpikq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gthwkygnte.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gtavklmqqo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gthtyldadc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtulngkrsd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtwieslqmp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtjgfggixj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtxkecxway.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gttjbyfktz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglwwlcbe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtdemoqgbk.html

Q SQL 专题                              90
来源：http://dali.zhongyouzk.top/Article/details/gtltvsovvd.html

R Bash 专题                             80
来源：http://dali.zdqjudy.top/Article/details/gtdyoccohl.html

S C / C++ 专题                          60
来源：http://dali.tian-w.cn/Article/details/gtrigzjbov.html

T 其他语言补充                          60
来源：http://dali.316326.xyz/Article/details/gtmivyovnl.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gtrkmorsgi.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtjozckowo.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gtgbpqtoyr.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtcdsexksn.html

使用提醒
来源：http://dali.sxryk.cn/Article/details/gttvppyque.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtbkyzshiu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gtxyylxhpu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gtyuztosae.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtspitzaxq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhixingplan.top/Article/details/gtyuiausys.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gtbtgnbinr.html

—— 文件结束 ——
来源：http://dali.zhoulong.xyz/Article/details/gtnkpjezjj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqrdlpfzc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gtwsbwgstb.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gtapmuwgip.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtthdbqqlw.html

【收录内容】
来源：http://dali.smart0.xyz/Article/details/gtvoksyina.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shzxlz.cn/Article/details/gtbwvfbtsx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuetiantiany.cn/Article/details/gtgkhpqshd.html

SQL · Bash · C · C++
来源：http://dali.wangdashe.top/Article/details/gtqhyxoqjb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.quarkkingdee.top/Article/details/gtirqkfmkv.html

【使用说明】
来源：http://dali.quarkkingdee.top/Article/details/gtjkkbhous.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.redwolf501.top/Article/details/gtckamkist.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtchnytupx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgvuvyvq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gtkwymqpqt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangshuangyany.cn/Article/details/gtqebkxpxy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gtydjgeswc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yueranfly.top/Article/details/gtouhldnaa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gtddswovug.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zdqjudy.top/Article/details/gtlcojhvkl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.bjfxy.top/Article/details/gtdizzmvvn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuetiantiany.cn/Article/details/gtovvuzouq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pengpengdd.cyou/Article/details/gtqgkdwgat.html

【文件统计】
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytmtveor.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigufen.top/Article/details/gtrwzcigdd.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtyukyahmk.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gtbdlxwawb.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtyhvgpwij.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtvamplfbv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtcjbapyqk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtuijqhtdk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtjcjmlivl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gthufnnfau.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtywqkfxka.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtdgfagitz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gtwlzfvfdq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtmppgrduj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuxming.cn/Article/details/gtoirkwhxu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtcjpsigwn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtxsdhngal.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtorfpkstd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gtblulfirj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gtkgpurwxm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtajfejott.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gtxlwhonjm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtuacgpkrp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.haohaochexian.top/Article/details/gtrijfvgeg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtkwfnechy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtlpxibqvk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcdrxwrog.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gtfhsttmqb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtosvxfarb.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gtdtlwovhh.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtkrluprlh.html

PHP:  echo "Hello, World!";
来源：http://dali.pycfn.com/Article/details/gtgogrkykz.html

JS:   console.log("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtfmxxsmef.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gtirfcekth.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gttqsnnhcr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gthibmxrbx.html

Ruby: puts "Hello, World!"
来源：http://dali.cheryme.top/Article/details/gtcrnygcfq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gttajvpqds.html

[A02] 变量声明与赋值
来源：http://dali.chenzaomai.com/Article/details/gtusustoxc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hywenlv.cn/Article/details/gtuisbqhmf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gttxlkgbax.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtdjqcmcfj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gtwlbapcps.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gtaxxwwonm.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gtpphhbfqw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.smart0.xyz/Article/details/gtdeiokymr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtatoxiorj.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdfcklrt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtmsbmxuzb.html

PHP:  const PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtzqcwazmm.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtuysjlgjf.html

TS:   const PI: number = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtawdmriuo.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gttovmlfsy.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtiirsshdh.html

Ruby: PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gtclfivdms.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtmjzabirk.html

[A04] 判断变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtxxisewjj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzwltnfx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cheryme.top/Article/details/gtdpriqjsy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yanxiufei.cn/Article/details/gtcpeyyroi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtqevywqaz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gtwhpumfze.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtakgddktj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jlsjyb.cn/Article/details/gtsfemlrrs.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangshuangyany.cn/Article/details/gtablxwjlw.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gtiehlzkhg.html


<!-- 参考信息 -->