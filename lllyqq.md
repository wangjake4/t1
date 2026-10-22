代发 wailian999

[U47] PHP：联合类型
来源：http://dali.c1oappe.top/Article/details/gtwhvxqdnr.html

int|string $id
来源：http://dali.nanxinkj.top/Article/details/gthwpgqbqs.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gthstbmkgh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gtpwqcqjyy.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gtmdyabksk.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gtndkvwqlm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gtuzqqvrcf.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gtgpnycyjj.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gtnwjlckan.html

[$a, $b] = $arr;
来源：http://dali.jqgufenzy.top/Article/details/gtputxytkb.html

[U52] PHP：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtywxqbkvt.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbibscehu.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gtemaatfsn.html

$v = $a ?? $b ?? "default";
来源：http://dali.jyoumei.cn/Article/details/gtluooemip.html

[U54] PHP：空安全调用
来源：http://dali.daria6918.cn/Article/details/gthtqabshq.html

$obj?->method()
来源：http://dali.xinyue.icu/Article/details/gtaxqkkynx.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gtlmkimwdm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtrxlfhdtl.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gtrfkceafi.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlythnpba.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtqgywmbvr.html

"值: {$a}"
来源：http://dali.cdnleiting.top/Article/details/gtdxspbwyp.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtpsuwyqfw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gtstfordld.html

[U59] PHP：自定义排序
来源：http://dali.yanxiufei.cn/Article/details/gtfcdtuerl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtevzeeqiv.html

[U60] PHP：JSON 编解码
来源：http://dali.quarkkingdee.top/Article/details/gtoeeftfxq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gtcuqcgmdl.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtbvuexmrb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtpjepvbzr.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gtgvmxtfdi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxinkj.top/Article/details/gtwhetgnyb.html

[U63] PHP：文件读写
来源：http://dali.bjfxy.top/Article/details/gtclafirfy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gtbhbvvblq.html

[U64] PHP：目录遍历
来源：http://dali.hnqzz.top/Article/details/gtdorabmwv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gtkmxpvykd.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gtuacxxzvr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sweek.top/Article/details/gtbhzbogbo.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gthihpveam.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tanke756.top/Article/details/gthnycmmzj.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtdhkxgjot.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gtuxsqguzu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gtecvmndsf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gtwxrcgfhs.html

[U69] PHP：PDO 预处理
来源：http://dali.tanke756.top/Article/details/gtqhdoglit.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gtcaekodlt.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gtwjehubzj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aibaodan.cn/Article/details/gtvfngnfmh.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gtpjqioolv.html

throw new RuntimeException("失败", 500);
来源：http://dali.dianchejie.cn/Article/details/gtuaiaeenc.html

[U72] PHP：写错误日志
来源：http://dali.shangyingyoupin.top/Article/details/gtfmvobtyb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gtvafhawxw.html

[U73] PHP：读取 ini 配置
来源：http://dali.jianghu66.top/Article/details/gttvsrmrlx.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtuarfuzhx.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtbysiyshz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtfuixsnqk.html

[U75] PHP：依赖注入
来源：http://dali.jqgfzy.top/Article/details/gthznlwrkq.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvbdipre.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gtacbavofi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gtlkibgsio.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtilrppgyw.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gtzriprxdb.html

[U78] PHP：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtlwvbrvbw.html

composer require --dev phpunit/phpunit
来源：http://dali.gaohongyu789.top/Article/details/gtauvrvulw.html

[U79] PHP：静态分析
来源：http://dali.zycfv.cn/Article/details/gtogyescso.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gtlsgzzjmw.html

[U80] PHP：代码规范修复
来源：http://dali.hfpthk.cn/Article/details/gtlhjmhjhi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hammf.cn/Article/details/gtlujnngrl.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gtcpwcclfa.html

npm init -y;  npm i express
来源：http://dali.0kj1m.cn/Article/details/gtlujhyiqd.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gtunbmjybm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gtomlguidq.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gtwfeoizmx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtxvhtnqwu.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckwklfgp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gtjdxduixt.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gtxcnnlokp.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfukarac.html

[U86] JS：空值合并
来源：http://dali.jqgufenzy.top/Article/details/gtyqqkzdrn.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtbzmiqpot.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gtmefnkokh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gzhubu.top/Article/details/gtvrazykbe.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtlikbytzh.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtzrnagttu.html

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gtvzbahdnz.html

[...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtndqpfuxn.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtirmdooqc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtrxfhklaa.html

[U91] JS：对象键值遍历
来源：http://dali.xziqi.cn/Article/details/gtmaygbdxq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gtzvewevyj.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gtjeutqvwp.html

structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzyybunc.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gtiqybeosg.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gthcfjgnsl.html

[U94] JS：箭头函数
来源：http://dali.birdmap.top/Article/details/gtuvtmqhrj.html

const double = x => x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtawrugknw.html

[U95] JS：Promise 包装
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlfllcym.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrepalok.html

[U96] JS：async/await 与异常
来源：http://dali.ppjwa.cn/Article/details/gtcgmlcdmu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtouicfmua.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gtykdmumdy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtxxjfsgaz.html

[U98] JS：fetch 带 JSON
来源：http://dali.yangfankeji.com/Article/details/gtihzhclbp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gtjtpiiuro.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gtsxjpsgje.html

el.addEventListener("click", e => {})
来源：http://dali.sweek.top/Article/details/gtiqmzkoat.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gtuggfseut.html

document.querySelector(".item")
来源：http://dali.tianlin.xyz/Article/details/gtxrtvuytn.html

[U101] JS：classList 操作
来源：http://dali.gaohongyu789.top/Article/details/gtbqvoptrw.html

el.classList.toggle("active")
来源：http://dali.dashuyun.cn/Article/details/gtaqjiqzhv.html

[U102] JS：本地存储
来源：http://dali.chenzaomai.com/Article/details/gtrxvxzhiw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gtifytinez.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gtzahwbrue.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gttlofxkar.html

[U104] JS：防抖
来源：http://dali.kuanghao11.cn/Article/details/gtvuqdtmmi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtjkmdkijt.html

[U105] JS：节流
来源：http://dali.guowangkeji.top/Article/details/gtnfacexpd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuanzhike.top/Article/details/gtbfjlvrne.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gtigimaryw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tianlin.xyz/Article/details/gtqxzjgtah.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtzysexrvz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtbawhjsyk.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gtdqnuawxe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtdalebzux.html

[U109] JS：数组分组
来源：http://dali.chenjidiqi.icu/Article/details/gtdjaqtjxh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtcjwdfyeu.html

[U110] JS：数组分块
来源：http://dali.mhx1999.top/Article/details/gtewlhyyyi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtkwsihakg.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtuvkkoxdt.html

new Map(Object.entries(obj))
来源：http://dali.hfpthk.cn/Article/details/gtldldvllb.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gtdbigyyvx.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtpuhfllva.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gtemcavdof.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtksufuzfv.html

[U114] JS：JSON 深比较
来源：http://dali.cdnleiting.top/Article/details/gtbbmczzcu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtduwsremu.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtsfwcgahi.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtufldbdhu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gtesedvcil.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gtgsfohwat.html

[U117] JS：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtfqejtfyp.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gtbhnmbsqr.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gtatnhvcyx.html

npm i -D vite;  npx vite
来源：http://dali.zdqjudy.top/Article/details/gtlehgtiof.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gtxvvnrtkn.html

npx vite build
来源：http://dali.hammf.cn/Article/details/gttnrptpdp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gtzncjgfzy.html

import.meta.env.VITE_API_URL
来源：http://dali.ydzc1.top/Article/details/gtymufdnka.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyyrwrjxg.html

统计汇总
来源：http://dali.snrcjt.cn/Article/details/gtselqzqbu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtldhftlyj.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gtciachqxv.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gtzwrobxfh.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gtkmrqvbev.html

JavaScript ..... 252
来源：http://dali.chenlongwang.top/Article/details/gtpqhssxko.html

TypeScript ..... 212
来源：http://dali.tianlin.xyz/Article/details/gtppwkwwpc.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtrsilnmvi.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gttfblsmmk.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gtqkaqsylx.html

C# ............. 212
来源：http://dali.jianghu66.top/Article/details/gtcgcrrmvd.html

C .............. 30
来源：http://dali.hongshengwenyu.top/Article/details/gtxfbncawj.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gtfocjzqsx.html

SQL ............ 90
来源：http://dali.hnqzz.top/Article/details/gttneuersv.html

Bash ........... 80
来源：http://dali.jinghuilouyu.cn/Article/details/gtizklslon.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtirbspxhz.html

Swift .......... 15
来源：http://dali.sysykeji.top/Article/details/gtkxjoogmg.html

Lua ............ 10
来源：http://dali.xylfe.cn/Article/details/gtgxgafhqi.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtcyricbnu.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrclhyen.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrztixqx.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gtqnvmkvrs.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gtfbssdfyb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtotfwyhpk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtlxkzkyun.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtjlofxhxq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtkpxebpzg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gtccviihpu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtifgiscrr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtktktdshq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtpxvurgst.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtilhnuoba.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtgwykgnqm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gteyograel.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gttzslztnd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtiodvtysp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtfoxlgudb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.meibo888.top/Article/details/gtxifqgihx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtlbkbufku.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gtuqnsojvk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gtzeofdypv.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtkjxdarug.html

T 其他语言补充                          60
来源：http://dali.jinqigufen.top/Article/details/gtimrmdglz.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gtttfdttzu.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtohprccgn.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gtlhycancr.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtjjugaves.html

使用提醒
来源：http://dali.gotoacloud.top/Article/details/gtbpcknvsb.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtzhmumbiy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tianlin.xyz/Article/details/gtfkoxsaww.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tianlin.xyz/Article/details/gttfkstmyn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gotoacloud.top/Article/details/gtapzknwjr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangdashe.top/Article/details/gtvwydduwi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gtgraivpgn.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gtavwvnjta.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtevzcmfwe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtfqcxkute.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gtxqtdfnxr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxfsaecol.html

【收录内容】
来源：http://dali.0kj1m.cn/Article/details/gtstqgztup.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gtakljftmb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gtzfptwmhh.html

SQL · Bash · C · C++
来源：http://dali.ehwqpu.com/Article/details/gtcsjnhear.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvomgxwwc.html

【使用说明】
来源：http://dali.sysykeji.top/Article/details/gtyhvqpesm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgufenzy.top/Article/details/gtrwryjphn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sxryk.cn/Article/details/gtxapkvxik.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.mhx1999.top/Article/details/gtqmkqjyhd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gtgbsvlbcm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jlsjyb.cn/Article/details/gtxtlfyzex.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigfzy.top/Article/details/gtdvjodwuu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pengpengdd.cyou/Article/details/gtgnpjhcdu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gthfrtqyik.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cucudq.cn/Article/details/gtnxdpcbye.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nwbrower.top/Article/details/gtudnstdot.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.daxiang520.top/Article/details/gtfwvonwtt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.svipenyu.cn/Article/details/gthsxsfdvq.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gtwflxfhfo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuanzhike.top/Article/details/gtgseoxbcr.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtpqaquoiw.html

目  录
来源：http://dali.yj20258888.top/Article/details/gtqztohoyv.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtsrjktjbd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtcjxvqcwr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtuxefvicx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtymjmkmkz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtscypqdsp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtjpzjrbfe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtzshklnrw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gttoqsxomy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gttaivjifs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtkznozsuy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtjdcqplfq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtemepbdun.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtmtvcrmai.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtyngdufyl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtiqkweyys.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gtcigqqaok.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtbffggfhw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gteimseqeo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cdnleiting.top/Article/details/gteevuyvmg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cheryme.top/Article/details/gttdlvgaln.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtkwzsrhey.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtrxzznmkw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtavnyonby.html

A. 基础语法与类型
来源：http://dali.hammf.cn/Article/details/gtevlijccw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gteromjrea.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtofwuthip.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gtxoukuswl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gtonaugdew.html

JS:   console.log("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gtlywxqmpu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvyswkhc.html

Java: System.out.println("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtbkkzcdou.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtioeymmqa.html

Ruby: puts "Hello, World!"
来源：http://dali.fzhhl.top/Article/details/gtphnadsuq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtktoxwmxf.html

[A02] 变量声明与赋值
来源：http://dali.c1oappe.top/Article/details/gtjnqqihfg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.havefunace.top/Article/details/gtlugmyzud.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtwftalsde.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtxjpfaryh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtmizpsoxw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtoikzoecj.html

Go:   name := "Alex"; age := 20
来源：http://dali.ybcxt.top/Article/details/gtqvdkprvd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gtfgehaztg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtznwvqceu.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtfzofrlha.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gtacaxdvst.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsmzqsax.html

JS:   const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gttbkvmnhu.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtrdkedgxj.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtzudyjqik.html

Go:   const PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gtzxuvmtpg.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtfedmsbft.html

C#:   const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtvbfgsexx.html

[A04] 判断变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtvxrwqnkm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gtmrytdnhq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fzhhl.top/Article/details/gtybxxklgh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gtnbbddzpk.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj202588.top/Article/details/gtjwbyqtom.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cdnleiting.top/Article/details/gtobzuygfa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shuidangran.top/Article/details/gtxggrdebx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gtawrthdua.html

C#:   x.GetType().Name; x is int
来源：http://dali.yvedp.cn/Article/details/gtrjaxzijw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gtgpyhsfdf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shangyingyoupin.top/Article/details/gtkwpqehae.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtgmemavuq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtxrwfzkfc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gthamynmps.html

Java: 7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtpekyfvww.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtwztlwpdq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gttpmoscuj.html

C#:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtzwlteuby.html


<!-- 参考信息 -->