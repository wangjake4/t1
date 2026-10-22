代发 wailian999

[U49] PHP：只读属性
来源：http://dali.kuanghao11.cn/Article/details/gtgfjlylhc.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gtuhffydjf.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gtykgbolqb.html

public function __construct(private int $id) {}
来源：http://dali.xylfe.cn/Article/details/gthbzncvwv.html

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gtaeissued.html

[$a, $b] = $arr;
来源：http://dali.yvedp.cn/Article/details/gtlxzrrvmq.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtieyoepqb.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtlvwwmvip.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gtvastspuj.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gtrbaxtxyy.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gtwygykhsc.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gtbbasrusl.html

[U55] PHP：match 表达式
来源：http://dali.tanke756.top/Article/details/gtawhrvnxh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hammf.cn/Article/details/gtaficaqmk.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtigbulydw.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtfvbdzlhu.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtdufewpcj.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gtrgieunpa.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gtwjgecbyj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gtkvzfrpke.html

[U59] PHP：自定义排序
来源：http://dali.meibo888.top/Article/details/gtyjaqfbhw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtjkfafgrm.html

[U60] PHP：JSON 编解码
来源：http://dali.dashuyun.cn/Article/details/gtkabrzksy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gtutkyojqo.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtprbwmuli.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtilgedeaf.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahgcbrex.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gtoadtxwzq.html

[U63] PHP：文件读写
来源：http://dali.hnqzz.top/Article/details/gtlwkavfsk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.svipenyu.cn/Article/details/gttgrytryp.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gtlijvgvqr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhongyouzk.top/Article/details/gtgvdqseym.html

[U65] PHP：会话
来源：http://dali.iojbl.cn/Article/details/gtbtovkmmw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtztjrzddw.html

[U66] PHP：设置 Cookie
来源：http://dali.ehwqpu.com/Article/details/gtlguzhcei.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhongyouzk.top/Article/details/gtypusbouv.html

[U67] PHP：处理文件上传
来源：http://dali.redwolf501.top/Article/details/gtpimigqkq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gtbaqemfrh.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gthncmmden.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sxryk.cn/Article/details/gtxyufxxmg.html

[U69] PHP：PDO 预处理
来源：http://dali.c1oappe.top/Article/details/gtxjnjgrfo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gtckwgfswk.html

[U70] PHP：PDO 事务
来源：http://dali.gaohongyu789.top/Article/details/gtgvkndnze.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj202588.top/Article/details/gtorjlnpxy.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gtuaiqmoey.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigufen.top/Article/details/gtnbappecm.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtgilcglbc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuanzhike.top/Article/details/gtizxccftt.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtvhgsbpzr.html

parse_ini_file("config.ini", true)
来源：http://dali.yanxiufei.cn/Article/details/gtvfjwgyjz.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtlmrgdmgo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangdashe.top/Article/details/gtadqcgyix.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtpmagiptw.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtwscynbpd.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gtrwumhknf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pycfn.com/Article/details/gtabvlpdyb.html

[U77] PHP：模板渲染
来源：http://dali.xinyue.icu/Article/details/gtqxzvaidc.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gtwmkkkgjh.html

[U78] PHP：单元测试
来源：http://dali.cashguo.top/Article/details/gtowkzygie.html

composer require --dev phpunit/phpunit
来源：http://dali.hfpthk.cn/Article/details/gtdnbrstfp.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gtiqkwzmap.html

composer require --dev phpstan/phpstan
来源：http://dali.kuanghao11.cn/Article/details/gtpkhqrlpe.html

[U80] PHP：代码规范修复
来源：http://dali.ydzc1.top/Article/details/gtdochjxde.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtpxtvtiaq.html

[U81] JS：初始化项目
来源：http://dali.yvedp.cn/Article/details/gtovtdnzil.html

npm init -y;  npm i express
来源：http://dali.daria6918.cn/Article/details/gtqrukvvvn.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gtwoqcqxlq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gtrxhwabed.html

[U83] JS：ES Module 导入导出
来源：http://dali.svipenyu.cn/Article/details/gtfwpyvtqy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gttgiofhxs.html

[U84] JS：CommonJS 写法
来源：http://dali.gotoacloud.top/Article/details/gtlkjyemmv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gtlbfnmkhc.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gtnepkzrzj.html

a?.b?.c
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkqjefdh.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtuyuyjonp.html

a ?? b
来源：http://dali.snrcjt.cn/Article/details/gtmneockwh.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gtopevhnit.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gteigqrdhn.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gtlgnmwhko.html

{ ...a, ...b }
来源：http://dali.guannengcc.top/Article/details/gtakbwozle.html

[U89] JS：数组去重
来源：http://dali.ehwqpu.com/Article/details/gtiiedegvp.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtgumrywen.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gtkqmerfht.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtwjmlkzev.html

[U91] JS：对象键值遍历
来源：http://dali.jqgufenzy.top/Article/details/gtpedsugxb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gtjovnasds.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gtthvdsaeo.html

structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtoonirgay.html

[U93] JS：模板字符串
来源：http://dali.tianlin.xyz/Article/details/gtzoyhhwjh.html

`共 ${n} 条`
来源：http://dali.bjfxy.top/Article/details/gtnmysatce.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtrhckgmlc.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gtfktpglne.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gtdflqqekl.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gtzdcpgaal.html

[U96] JS：async/await 与异常
来源：http://dali.havefunace.top/Article/details/gtaykioigy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gttrvgjscu.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtaclvtgkj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtmpxhkhow.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gtnyasxwgx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxuanxn.top/Article/details/gtppqrdkfj.html

[U99] JS：事件监听
来源：http://dali.nanxuanxn.top/Article/details/gtrsljtjjk.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gtmstxdcag.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtjgjuyeir.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gtbwzjqkri.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gtmdhlglaj.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gtijsjtlja.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gtietommhi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gtoatsloug.html

[U103] JS：定时器
来源：http://dali.ybcxt.top/Article/details/gtvhfhivcj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtoedxeqnq.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gtrcsktksd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtmbphbtyh.html

[U105] JS：节流
来源：http://dali.cashguo.top/Article/details/gtjxrgqxnb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daria6918.cn/Article/details/gtqoiupcfw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtoirevxpb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gtuiktevmt.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtqojsouvn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtesuvkfqd.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtciorervp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtblfmqzna.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gtauwdyzxx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtkmkctyhu.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gtfnhysytr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gtmucobxlt.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gteinifbuz.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gtdmfpajlq.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gtcumypymf.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtprjepmlk.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gtwwhnxipj.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtdnpukggd.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gtypwczhhj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtsctpfyyj.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtypvlgwgj.html

crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtdbvrxesj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gtamvakjvv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtyicqcbkr.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtohzykcxu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gtpbucrqbf.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnkgmgik.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gtvgtosblk.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gtvgyrpgeu.html

npx vite build
来源：http://dali.yj202588.top/Article/details/gtbuiklpyy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnxiangtu.top/Article/details/gtbfozetdk.html

import.meta.env.VITE_API_URL
来源：http://dali.hfpthk.cn/Article/details/gtutmtfxvp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtagnteyyz.html

统计汇总
来源：http://dali.xinyue.icu/Article/details/gtiedycdia.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthnvyddfi.html

按语言统计（条）：
来源：http://dali.ehwqpu.com/Article/details/gtrkzeupgx.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gtbiidbmnn.html

PHP ............ 252
来源：http://dali.zhongyouzk.top/Article/details/gtjijoavjk.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtimadujdj.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtzwydznuk.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtjzkegxeo.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtchpablna.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gteiiflhif.html

C# ............. 212
来源：http://dali.zycfv.cn/Article/details/gtzaqxuavf.html

C .............. 30
来源：http://dali.haohaochexian.top/Article/details/gtjtaaidno.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gtkwqcvnax.html

SQL ............ 90
来源：http://dali.jianghu66.top/Article/details/gtpqpdmxgc.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtpdllatoz.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gthecqcrqv.html

Swift .......... 15
来源：http://dali.yuxming.cn/Article/details/gtqyczfsbz.html

Lua ............ 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtredrcbhq.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gtksgfvnlg.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtdhpwpxoo.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtrrusdgjm.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gtnlvnbdqy.html

按章节统计：
来源：http://dali.wangshuangyany.cn/Article/details/gtnjqujgck.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtqsllwysa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtocwodqxc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtcrywzkcp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gttqnflsjx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gtzdunrwrn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtvmsaiofb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtbuctfgmk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtncyposnl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtjbysrbhg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtzzysccov.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqknxfov.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtvdrgeyhq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gthjuudsed.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtiakduyst.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gthcyhdaff.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtlgcngotp.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gtmygerlzl.html

R Bash 专题                             80
来源：http://dali.andypj.xyz/Article/details/gtidqcvnry.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gtwilbrwqw.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtykicjjhy.html

U 高频实用片段                         120
来源：http://dali.shzxlz.cn/Article/details/gtyzhwrulk.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzasfdwjd.html

合计                                  2106 条
来源：http://dali.bjfxy.top/Article/details/gtzycpkcnv.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfjthdau.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtjlczjxbh.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtksqxmewg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aibaodan.cn/Article/details/gtkjlzyjxh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gthlzmnyjs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuanzhike.top/Article/details/gtaithqfhn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gtynbigznl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gtzanfkdjr.html

—— 文件结束 ——
来源：http://dali.9152youxi.cn/Article/details/gtlejjsydc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyxkxgziu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hywenlv.cn/Article/details/gtccfogqkm.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gtmaazftva.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkrqtehdv.html

【收录内容】
来源：http://dali.tianlin.xyz/Article/details/gtnslgvzsk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.mhx1999.top/Article/details/gtqrsjmysm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fzhhl.top/Article/details/gtiseollvy.html

SQL · Bash · C · C++
来源：http://dali.yonumen.top/Article/details/gtubetguzz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sufxvd.cn/Article/details/gttmdmlbiq.html

【使用说明】
来源：http://dali.tanke756.top/Article/details/gthvtaeemd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xinyue.icu/Article/details/gtfytpbixu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gtslcuednm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daria6918.cn/Article/details/gtlfdyheqq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpapwxcsz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenzaomai.com/Article/details/gtezdghxgt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuetiantiany.cn/Article/details/gtabzvheqt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxinkj.top/Article/details/gtefaucyex.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gtthpgrlac.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhoulong.xyz/Article/details/gtcremfnby.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtczhfgmnf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dianchejie.cn/Article/details/gtawisroui.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gtwjpatmpp.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gtfmkkqkwc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.meibo888.top/Article/details/gtqnzrxmjq.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtqywiaqil.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gttyncxooq.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtexmagcud.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtyfuobqxl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gtvmrjmjcp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtfifoggli.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmicwsyry.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tanke756.top/Article/details/gteptrwqwy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtrhpkagwu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gtmukzkncd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtnhblixga.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtncnawqjz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtejlyavwz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtzftnuxyb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyaaomxk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtrdjgwadq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtihlfolkr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhoulong.xyz/Article/details/gtqwxrspuf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemmauckf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ivvv.top/Article/details/gtpkulaoeb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtofpedqvc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fengsongda.top/Article/details/gtcevxwobi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsnpzhfk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtxawtzvkm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnrnwqalx.html

A. 基础语法与类型
来源：http://dali.hnqzz.top/Article/details/gtluvcwkxd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtngylfgsg.html

[A01] Hello World
来源：http://dali.chenzaomai.com/Article/details/gtvrekzzay.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gtheyzyzdf.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gttcalfsyk.html

JS:   console.log("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gttgbdyxvh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gogol.net.cn/Article/details/gtagmnxzls.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gttjficcug.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gthmhsncat.html

Ruby: puts "Hello, World!"
来源：http://dali.chenzaomai.com/Article/details/gtijnpkjjo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtalfiajum.html

[A02] 变量声明与赋值
来源：http://dali.9152youxi.cn/Article/details/gtmjgkuavq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.kuanghao11.cn/Article/details/gtbriensao.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cucudq.cn/Article/details/gtigdufztz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtjdsuerjk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.mhx1999.top/Article/details/gtfhyrezzl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtezdchmug.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gtmkmsvygi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gtmvkxhyob.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtfcrikftg.html

[A03] 常量定义
来源：http://dali.andypj.xyz/Article/details/gtjvkaerka.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zycfv.cn/Article/details/gtrjvaqcis.html

PHP:  const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtulwjkanh.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gttqoaiakw.html

TS:   const PI: number = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtywsckfbt.html

Java: static final double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtsnqkpdkn.html

Go:   const PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gtcpgyjymb.html

Ruby: PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gtktfpylrc.html

C#:   const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtullimsaw.html

[A04] 判断变量类型
来源：http://dali.nwbrower.top/Article/details/gtkuqsgxkx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gtxkbroqmu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.svipenyu.cn/Article/details/gtqiuezher.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gtouftctyy.html

TS:   typeof x; x instanceof Date
来源：http://dali.ppjwa.cn/Article/details/gtmebyqvsc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gtavwzujuj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gotoacloud.top/Article/details/gtlfytvkwt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gtbomtmmof.html

C#:   x.GetType().Name; x is int
来源：http://dali.guannengcc.top/Article/details/gtkmzmnprq.html

[A05] 整数除法与取模
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqomyjew.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fzhhl.top/Article/details/gtevhplflj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtrxpkqlge.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtnznfrwnf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtwofiaypc.html

Java: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtukyzqqay.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtrjwqcwiy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gthqtcellg.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtmioysuct.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtydtwpjsu.html

Py:   int("42"); float("3.14")
来源：http://dali.smart0.xyz/Article/details/gtilykxwrb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zdqjudy.top/Article/details/gtjzgvezrh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tian-w.cn/Article/details/gtgaxoumgx.html


<!-- 参考信息 -->