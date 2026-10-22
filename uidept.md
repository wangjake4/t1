代发 wailian999

[U47] PHP：联合类型
来源：http://dali.bjfxy.top/Article/details/gtmblzzers.html

int|string $id
来源：http://dali.yj202588.top/Article/details/gttanwmlij.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gtlclxwnia.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuescugpa.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gtcjwrazbt.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gtcyaijpwc.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtvscvmlhf.html

public function __construct(private int $id) {}
来源：http://dali.iojbl.cn/Article/details/gtusymkhev.html

[U51] PHP：数组解构
来源：http://dali.shzxlz.cn/Article/details/gtoncwvnbb.html

[$a, $b] = $arr;
来源：http://dali.sxryk.cn/Article/details/gtccezzvby.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtiyrnrlvc.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtwuftbjrk.html

[U53] PHP：空合并运算符
来源：http://dali.aizwys.cn/Article/details/gtywmizvef.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gtoqcovhoz.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtzwyqzbzu.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gtetdjpdkd.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gtoybramou.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtjbnpgdqm.html

[U56] PHP：命名参数
来源：http://dali.yangfankeji.com/Article/details/gtajclrifs.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtwwuyvjpt.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtwszxfgwh.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gtqoqqcjti.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gtzajlbrge.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtjqjseqea.html

[U59] PHP：自定义排序
来源：http://dali.pengpengdd.cyou/Article/details/gtceolaeks.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglsxygjb.html

[U60] PHP：JSON 编解码
来源：http://dali.vqdsnc.cn/Article/details/gtcfrkfmyc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtotnmxrue.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gteocrfext.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtamvlbhnt.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gtsmbfunph.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gtiwscqoxx.html

[U63] PHP：文件读写
来源：http://dali.chenjidiqi.icu/Article/details/gtbxrtigdb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhoulong.xyz/Article/details/gtlhhdhljw.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gtqbrxhfyf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yueranfly.top/Article/details/gtlqfzwuxv.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gtmlfvszor.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtnobcqoas.html

[U66] PHP：设置 Cookie
来源：http://dali.zhoulong.xyz/Article/details/gtudcgkdim.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.iojbl.cn/Article/details/gtrxsiawvq.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuyzanyk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fzhhl.top/Article/details/gtvireuaoh.html

[U68] PHP：PDO 连接
来源：http://dali.snrcjt.cn/Article/details/gtjrvadrhu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtxpnsuvcs.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiguyswl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gtizfaoudc.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzukbtyr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gtizimdnpz.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtuxbiezlf.html

throw new RuntimeException("失败", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkdrcyui.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gtldjiienj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gtncwiomch.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gtqdizxhkl.html

parse_ini_file("config.ini", true)
来源：http://dali.zycfv.cn/Article/details/gttcljfqvs.html

[U74] PHP：读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtbpeqxgxl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gtpystgrkr.html

[U75] PHP：依赖注入
来源：http://dali.yuanzhike.top/Article/details/gtavbjlpqa.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtmolmjbwz.html

[U76] PHP：简单路由
来源：http://dali.meibo888.top/Article/details/gteiybcuhq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.vqdsnc.cn/Article/details/gtmprspubc.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gtqrgunjkn.html

composer require twig/twig
来源：http://dali.jqgufenzy.top/Article/details/gtzfnezcce.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtykaybqja.html

composer require --dev phpunit/phpunit
来源：http://dali.jlsjyb.cn/Article/details/gtfnxctnus.html

[U79] PHP：静态分析
来源：http://dali.wangdashe.top/Article/details/gtsyzovzou.html

composer require --dev phpstan/phpstan
来源：http://dali.haohaochexian.top/Article/details/gtpplkcljx.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvyfgyxp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigufen.top/Article/details/gtkpravsdc.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gtznypsjmx.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gtyxrwherg.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gthdjltaii.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtucjfuzpi.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gtxzzfxsqu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtbylcqcil.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gtjhvwrkhx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtcuegovca.html

[U85] JS：可选链
来源：http://dali.kuanghao11.cn/Article/details/gtwpomrdpn.html

a?.b?.c
来源：http://dali.snrcjt.cn/Article/details/gtlijucsgo.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtirhpxeev.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtmlzqwumr.html

[U87] JS：解构默认值
来源：http://dali.aibaodan.cn/Article/details/gtqicwlgub.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gtotxcrgzq.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gtekpwvgfu.html

{ ...a, ...b }
来源：http://dali.gzhubu.top/Article/details/gtjbhmvhqy.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gtmhoktztr.html

[...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtrnnpxzxv.html

[U90] JS：数字数组排序
来源：http://dali.jinqigfzy.top/Article/details/gtdhmqhlpl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtnockglpu.html

[U91] JS：对象键值遍历
来源：http://dali.cheryme.top/Article/details/gtojqmensu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tanke756.top/Article/details/gtiytgnqaj.html

[U92] JS：深拷贝
来源：http://dali.dianchejie.cn/Article/details/gtotrqhwot.html

structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtsuauljyq.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gtmjcxpryx.html

`共 ${n} 条`
来源：http://dali.jlsjyb.cn/Article/details/gtogzyvppg.html

[U94] JS：箭头函数
来源：http://dali.zhoulong.xyz/Article/details/gtybecawpk.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gtevrdowzw.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtjfsncshq.html

new Promise((resolve, reject) => {})
来源：http://dali.daria6918.cn/Article/details/gtvhbqauyc.html

[U96] JS：async/await 与异常
来源：http://dali.9152youxi.cn/Article/details/gthdphrzzi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtyairkcut.html

[U97] JS：并发请求
来源：http://dali.svipenyu.cn/Article/details/gtwlymgjjz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtkgljpbzf.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdimtanqm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtqjzsflvq.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtdlqbnewx.html

el.addEventListener("click", e => {})
来源：http://dali.jqgufenzy.top/Article/details/gtakshwokx.html

[U100] JS：DOM 查询
来源：http://dali.daria6918.cn/Article/details/gtrfbcywmj.html

document.querySelector(".item")
来源：http://dali.ehwqpu.com/Article/details/gtaslrgiew.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwremqjf.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtwowwdqsd.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtveluhglc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzeyxkaw.html

[U103] JS：定时器
来源：http://dali.hongshengwenyu.top/Article/details/gtfnsakgnp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gtxpktnfhd.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtkhsqihbp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtwpyimyhp.html

[U105] JS：节流
来源：http://dali.nanxinkj.top/Article/details/gtsrfgmxfm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gtyttyzmgy.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtsalimjcn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gtftewfaia.html

[U107] JS：数字千分位
来源：http://dali.xinyue.icu/Article/details/gtxsysvwdh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gtkfhuaamb.html

[U108] JS：随机整数
来源：http://dali.shuidangran.top/Article/details/gtgwyaqoem.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtkpltnbat.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gteccoodxf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtusoczilj.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gtvgmffigh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gtermjclax.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtwnnocbcr.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gthxqcexiz.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gtxekysfbr.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtcycbyyra.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gtcxjpdigz.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtabtzpybr.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258888.top/Article/details/gtnbikimep.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gteqgthesc.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtiejyofuz.html

crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkirwzwqq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gtxizpprkg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fengsongda.top/Article/details/gtyifyhdur.html

[U117] JS：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtjjrbjmky.html

npm i -D vitest;  npx vitest
来源：http://dali.316326.xyz/Article/details/gtswmubtwb.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gtwolsxmwz.html

npm i -D vite;  npx vite
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywikgkai.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gtxrxuzipa.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtakprqsmg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258888.top/Article/details/gtqsvuvbni.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gteizadpqm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyhuxosgs.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gthjzdqixo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvxkodids.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gtijsdbxnk.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gtraijlwdc.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gtqaunwblz.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gtkyrjojro.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gtcdumlngw.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtchofcwab.html

Go ............. 212
来源：http://dali.yueranfly.top/Article/details/gtyldwmsbh.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gtsbkmgwmg.html

C# ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtarxljdmy.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gtmqcplhuz.html

C++ ............ 30
来源：http://dali.chenlongwang.top/Article/details/gtigvngicq.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtxwtgikjj.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtqsxkzule.html

Kotlin ......... 15
来源：http://dali.daxiang520.top/Article/details/gttofvjqxl.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gtyanjulpw.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gtagvroxdy.html

Perl ........... 10
来源：http://dali.yongpay.top/Article/details/gtwbrkzsrc.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gthsooaics.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtuqrtsrgv.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtwgamaabf.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gtqcxuasxa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gtynxwmjbb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtegzainkx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtkccfbnby.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtbqokuhmz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtbxsgskzp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtpglujjen.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtglcayzyd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtkwikizxb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtkodbwqvu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtmyxdoary.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtrsabulcs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtmzmelnnl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtzihtdjfh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtaygeqxjf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tian-w.cn/Article/details/gtugczanvc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtxxeovzli.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gtcltqcney.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gtkozhkpoe.html

S C / C++ 专题                          60
来源：http://dali.cucudq.cn/Article/details/gtleylxoce.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gtzbincpux.html

U 高频实用片段                         120
来源：http://dali.dianchejie.cn/Article/details/gtipybuiaz.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtiqtmdore.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtvrtdvgyb.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtannkqbbs.html

使用提醒
来源：http://dali.svipenyu.cn/Article/details/gtdunooioz.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtueuxvcuq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gtvufredef.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.feifeiyinyue.top/Article/details/gtaogvizah.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtbsdsaeug.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gtyisvksze.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.bjfxy.top/Article/details/gtovobluwu.html

—— 文件结束 ——
来源：http://dali.shuidangran.top/Article/details/gtlkivqvww.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttpkhtckv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpcgvesz.html

Common Programming Examples Cheat Book
来源：http://dali.yongpay.top/Article/details/gtgzbuanbb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrtxvwlgh.html

【收录内容】
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkuarvgw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sweek.top/Article/details/gtqmiuzxkx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.meibo888.top/Article/details/gtzotxgptj.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gtcatyenli.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jyoumei.cn/Article/details/gtgmmjutop.html

【使用说明】
来源：http://dali.cucudq.cn/Article/details/gtquxvlwqg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuxming.cn/Article/details/gtazpuzben.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tianlin.xyz/Article/details/gtdddidptc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxuanxn.top/Article/details/gtpgelkwrs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangshuangyany.cn/Article/details/gttclyhlap.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdatuxwq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pycfn.com/Article/details/gtsjetrqgd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gaohongyu789.top/Article/details/gttyckraej.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gtcgypkgox.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cqqwz.cn/Article/details/gtialpnueo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sxryk.cn/Article/details/gtjojdfjup.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guannengcc.top/Article/details/gtqyfozowy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yangfankeji.com/Article/details/gtauecbwyw.html

【文件统计】
来源：http://dali.bjfxy.top/Article/details/gtumnknwsx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sxryk.cn/Article/details/gthwxbaghr.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtvmjairug.html

目  录
来源：http://dali.yj20258.top/Article/details/gtawvbgtbb.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtkbraidyn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjpexmie.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtiettxatv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtqshdlkql.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtxfnrjqeu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jianghu66.top/Article/details/gtpezforep.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gtiqmicpai.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gteznpnate.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtgwsmchul.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtysvctixn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtlhrzeuzu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtvgboztaz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtnidkaqkt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtisvcrsdi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtdzksetsz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gtyufvkmoo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtygxkhjuo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuxming.cn/Article/details/gtcnissmmp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gthmzijqpu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.birdmap.top/Article/details/gtzwyobpgb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtmfnjxqij.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtwgojeicu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjgctrkdc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gtprdcrsfo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkcstnhyf.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gtxdtgmgzn.html

Py:   print("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtdjxlnjon.html

PHP:  echo "Hello, World!";
来源：http://dali.jianghu66.top/Article/details/gtknbcezrq.html

JS:   console.log("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gtlxgddyjd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jianghu66.top/Article/details/gtrkboltck.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtfxjktnnc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtrjfwhihz.html

Ruby: puts "Hello, World!"
来源：http://dali.pycfn.com/Article/details/gthtnapybh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtbfdbngkm.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gtbaksehbp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gtyujsryvu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfeemxyi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtarjjvxxy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtbkpaxeek.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtuhsiqvnk.html

Go:   name := "Alex"; age := 20
来源：http://dali.havefunace.top/Article/details/gthgpfnnpv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.0kj1m.cn/Article/details/gtqdcjvinz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtabixfgpl.html

[A03] 常量定义
来源：http://dali.pengpengdd.cyou/Article/details/gtrwwyjkfo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gtckuscnfq.html

PHP:  const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gttmikyarx.html

JS:   const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtbyorxufu.html

TS:   const PI: number = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtknwxahqg.html

Java: static final double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtcuzfnvzd.html

Go:   const PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtmnnxslnx.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gthoxtbqhd.html

C#:   const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtrvzmywxp.html

[A04] 判断变量类型
来源：http://dali.pycfn.com/Article/details/gttthinief.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvxjifsz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fzhhl.top/Article/details/gtufauvlzc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtrupkfdam.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtkgkenagi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gttgtxkmjm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gthyjxqlcq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jianghu66.top/Article/details/gtagbihigb.html

C#:   x.GetType().Name; x is int
来源：http://dali.meibo888.top/Article/details/gtmptkqxun.html

[A05] 整数除法与取模
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttztfzysi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuanzx.com/Article/details/gtkmzadvsx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrsmxppx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtllinjzlx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtlgmzgkeu.html

Java: 7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtnzfqdqzn.html

Go:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtfhdhtnvd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtybzpdncc.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtvrhpoqid.html


<!-- 参考信息 -->