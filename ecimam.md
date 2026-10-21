代发 wailian999

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gtszudmemt.html

[$a, $b] = $arr;
来源：http://dali.quarkkingdee.top/Article/details/gtdngsrwbl.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtgxljkahl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gtffywpyto.html

[U53] PHP：空合并运算符
来源：http://dali.jiagoushi.top/Article/details/gtvpmuiipg.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgfzy.top/Article/details/gtfxgrjqjt.html

[U54] PHP：空安全调用
来源：http://dali.meibo888.top/Article/details/gttjikqtlr.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gtfiwdjtln.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gtfkcbxtww.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtgloifwbu.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkayltrn.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtksgcgfes.html

[U57] PHP：字符串插值
来源：http://dali.yj20258888.top/Article/details/gthfeectlh.html

"值: {$a}"
来源：http://dali.cqqwz.cn/Article/details/gteaybrvcf.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtupuohdmd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gtkbekwrcg.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gtmyoyjzvs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtamxtcjze.html

[U60] PHP：JSON 编解码
来源：http://dali.wangshuangyany.cn/Article/details/gtzvhuwocl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtmgftcqij.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gtzmrqexlf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtirmmvnqj.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gtrvhlenip.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.c1oappe.top/Article/details/gtojarwmoy.html

[U63] PHP：文件读写
来源：http://dali.smart0.xyz/Article/details/gtejfirctn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yongpay.top/Article/details/gthrihgwxn.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gtoozjlfcd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gttcxwabjl.html

[U65] PHP：会话
来源：http://dali.mhx1999.top/Article/details/gtzsefacul.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtxhfxdgzf.html

[U66] PHP：设置 Cookie
来源：http://dali.vqdsnc.cn/Article/details/gtbkmcbcfu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gtqqfnnvta.html

[U67] PHP：处理文件上传
来源：http://dali.zycfv.cn/Article/details/gtzcmlpycy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gtjdpquvzc.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gtvuuhsbgt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.birdmap.top/Article/details/gtulbflrcb.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gtfpaynczy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtvuyffijy.html

[U70] PHP：PDO 事务
来源：http://dali.daria6918.cn/Article/details/gtedvdovxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gtxvpllerb.html

[U71] PHP：抛出异常
来源：http://dali.ybcxt.top/Article/details/gtuejotsed.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtrincgbog.html

[U72] PHP：写错误日志
来源：http://dali.jyoumei.cn/Article/details/gtqtiaogex.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtmqkneuix.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gttkjvhoxq.html

parse_ini_file("config.ini", true)
来源：http://dali.yueranfly.top/Article/details/gtmtkoutjz.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtsbyprhsu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gtjssekbiy.html

[U75] PHP：依赖注入
来源：http://dali.cucudq.cn/Article/details/gtacqanyno.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gtwblawwsu.html

[U76] PHP：简单路由
来源：http://dali.andypj.xyz/Article/details/gtozjohqcb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gtrgjwkpdo.html

[U77] PHP：模板渲染
来源：http://dali.tanke756.top/Article/details/gtiuizkjdq.html

composer require twig/twig
来源：http://dali.hysaishi.cn/Article/details/gtybjqnffh.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gtkpsgzplz.html

composer require --dev phpunit/phpunit
来源：http://dali.xuanzx.com/Article/details/gtwovakbyr.html

[U79] PHP：静态分析
来源：http://dali.zhengqikj.top/Article/details/gtzptqkgov.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gtummriowl.html

[U80] PHP：代码规范修复
来源：http://dali.kuanghao11.cn/Article/details/gtsweozszw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtahefyhks.html

[U81] JS：初始化项目
来源：http://dali.iojbl.cn/Article/details/gtegfkndlc.html

npm init -y;  npm i express
来源：http://dali.yuxming.cn/Article/details/gtcfchqvtm.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gtymoexunc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yangfankeji.com/Article/details/gtmdyraiot.html

[U83] JS：ES Module 导入导出
来源：http://dali.aibaodan.cn/Article/details/gtnziimezd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtelojfojf.html

[U84] JS：CommonJS 写法
来源：http://dali.cucudq.cn/Article/details/gtbdbupyaa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhixingplan.top/Article/details/gtkagcdmkd.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gtcjjupupf.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtrdzoheca.html

[U86] JS：空值合并
来源：http://dali.yvedp.cn/Article/details/gtznwcdmcc.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gtnicepaqf.html

[U87] JS：解构默认值
来源：http://dali.sxryk.cn/Article/details/gtjlyiryzz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gthfrujulm.html

[U88] JS：对象展开合并
来源：http://dali.c1oappe.top/Article/details/gtkwzheqzh.html

{ ...a, ...b }
来源：http://dali.quarkkingdee.top/Article/details/gtbimpuwer.html

[U89] JS：数组去重
来源：http://dali.yongpay.top/Article/details/gtuzpgyhok.html

[...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtnpysdzpf.html

[U90] JS：数字数组排序
来源：http://dali.yangfankeji.com/Article/details/gtcilzjzlm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtspgqxybz.html

[U91] JS：对象键值遍历
来源：http://dali.guowangkeji.top/Article/details/gthwsjpthz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nanxinkj.top/Article/details/gtqscohvcb.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gtyrldgghc.html

structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtfqrlvuqu.html

[U93] JS：模板字符串
来源：http://dali.sxryk.cn/Article/details/gtiyibwyvx.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gtpkbfmmuc.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtqsiirmwl.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gtrmqwfrow.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gtzszfjstv.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtmaiyalrh.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gtutqyzztk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtlrlmlnsb.html

[U97] JS：并发请求
来源：http://dali.cashguo.top/Article/details/gtbqizxciw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtcrpkravx.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtzwoufump.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ydzc1.top/Article/details/gtnoqtwqet.html

[U99] JS：事件监听
来源：http://dali.gzhubu.top/Article/details/gtjfjpjkzn.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gtygxqshia.html

[U100] JS：DOM 查询
来源：http://dali.yj20258.top/Article/details/gtezeqhrrm.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gtzdmdvtpk.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gtnkqjfikf.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gtxtxbhezf.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gtvodzykxv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gtevochocr.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gtnlfgbifs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gtuwpmmpso.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gtqdwrrtus.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtscyeakyg.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gtcadjdrtl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbksofiz.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtvlalqyzl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gthgaeqffj.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtyvvaccsv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gteghkoqci.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtucmabxbt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gteomryolv.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtichxeqku.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtncocfbww.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gtfftbqygt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtdkzotppj.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtlxgfkaqn.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtnntjdcgu.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtrxnmvqjd.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtheuatmzl.html

[U113] JS：正则替换全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmpblgue.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtdkaxcxiu.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtnimwrmep.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtlafjepjo.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtvkygjinx.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtwyepxkco.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gtnkaeeumc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.haohaochexian.top/Article/details/gthbbyngtg.html

[U117] JS：单元测试
来源：http://dali.yueranfly.top/Article/details/gtsaaeapko.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtcekcpsxk.html

[U118] JS：开发服务器
来源：http://dali.cdnleiting.top/Article/details/gtkclfcfwz.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtiojcbjrl.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gtiwqxfqrb.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtlinfcnme.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhixingplan.top/Article/details/gtlqeqtbvy.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gtunrtmcfy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqgjcfthi.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtsperwdre.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtszlscioq.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gttfjkboaf.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmckpjvgy.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gthlqbdufo.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtbktquazx.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gtkmwjsuae.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtqfeszrps.html

Go ............. 212
来源：http://dali.cheryme.top/Article/details/gtfukbtrsn.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gtsbwkbtcy.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gtndyuuikf.html

C .............. 30
来源：http://dali.redwolf501.top/Article/details/gtptthcjci.html

C++ ............ 30
来源：http://dali.dashuyun.cn/Article/details/gtzyotusgw.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gtwkqjgmpx.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gtqcpqzikd.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gtqcuicvtk.html

Swift .......... 15
来源：http://dali.kuanghao11.cn/Article/details/gtcovzonhv.html

Lua ............ 10
来源：http://dali.dashuyun.cn/Article/details/gthdfiscbe.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gtsyswvibt.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtsvumddib.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsstwaua.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtasqfvpue.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gtiqaxamsf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtijulfdxb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtcbbfiqsn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtbqesidcw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtxjslgouj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gteghhbopg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtrywmqczl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtnacmuaoz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gtuvxoartx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtxwdazocr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gtmhbeewks.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtfitrrvat.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtkqvbzfjp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtlrwvaaij.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmknxraa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtsivxhruu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtudpntxud.html

Q SQL 专题                              90
来源：http://dali.aibaodan.cn/Article/details/gtkpvsubfm.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtaafwdjkz.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gtfitaeyeh.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gtjiunufhk.html

U 高频实用片段                         120
来源：http://dali.fzhhl.top/Article/details/gtwocknjvt.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtunezljpp.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtouafissw.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtxlpauabd.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gttlwisxks.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtguqxdwpq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gtaeojjztc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guowangkeji.top/Article/details/gtpclivaqr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangshuangyany.cn/Article/details/gtmcxsnakz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gtpioarkku.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhiwuduotai.top/Article/details/gtnmnzhkko.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtdjidlrbg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbnprbrwc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dashuyun.cn/Article/details/gtiyuwmgyy.html

Common Programming Examples Cheat Book
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbnlnpif.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbexpxonj.html

【收录内容】
来源：http://dali.jlsjyb.cn/Article/details/gtuxdadjzl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyhnlfkr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gtujfiluze.html

SQL · Bash · C · C++
来源：http://dali.birdmap.top/Article/details/gthdvlmkye.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cqqwz.cn/Article/details/gtzpbdfpad.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gtttoytemk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gtcppbtncr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fzhhl.top/Article/details/gtrmwjphto.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gttzwqthrt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiggcjien.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gtcbagodrd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmcdshqs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangshuangyany.cn/Article/details/gtdmldzdjx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hysaishi.cn/Article/details/gtshadvjwh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cdnleiting.top/Article/details/gtihovcxfr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pengpengdd.cyou/Article/details/gtknydxjsd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shangyingyoupin.top/Article/details/gtnkjsyhsg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shzxlz.cn/Article/details/gtflmoexzm.html

【文件统计】
来源：http://dali.quarkkingdee.top/Article/details/gtavshsbhq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dashuyun.cn/Article/details/gtplnwbhdi.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtwrpgcgzq.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gttiiwbeda.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtnvtrqyrj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gtdiwzzdsc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtstoykhvi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtwtjxngen.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtddhmlkem.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtebomepah.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtsvsooqmg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtljfzhevs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtjztcwftz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxfmgcvf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtaglppxny.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtlzqsggid.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtadrelmlq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtlbgxvxtg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtuoobvjwt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtitdzcphm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gthjgsxrff.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shzxlz.cn/Article/details/gttsldmhrc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtnzwuhyku.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gtisbrhlip.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtddxzlwta.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtsqcisygs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtytfrhpld.html

A. 基础语法与类型
来源：http://dali.hfpthk.cn/Article/details/gtriohiwtj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxytmjyzz.html

[A01] Hello World
来源：http://dali.ybcxt.top/Article/details/gtkbmprwfu.html

Py:   print("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtvfbkvoao.html

PHP:  echo "Hello, World!";
来源：http://dali.zhoulong.xyz/Article/details/gtrgandhkm.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtemsgeujd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj202588.top/Article/details/gtuntsqlqu.html

Java: System.out.println("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtbrzdollc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gtvwgbuwnx.html

Ruby: puts "Hello, World!"
来源：http://dali.svipenyu.cn/Article/details/gtutyegykb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtzqgzhqmq.html

[A02] 变量声明与赋值
来源：http://dali.yueranfly.top/Article/details/gtkvxnepyn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guowangkeji.top/Article/details/gtmlnlgupf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guannengcc.top/Article/details/gtxjbwiqcw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtrwfhyjla.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gtmdjjpiyf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtmjubxxjt.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenzaomai.com/Article/details/gtrwrvgvgt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pycfn.com/Article/details/gtuvpmgwnt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtzccigtrw.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtbxxfxtcg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ehwqpu.com/Article/details/gthgetslen.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtxjzyvfkq.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtwifvktrv.html

TS:   const PI: number = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtikpwhoqa.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtjrsmingj.html

Go:   const PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gtgsazsknm.html

Ruby: PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtqkixdcwy.html

C#:   const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtvtnhzkgg.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gteqoryrib.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dianchejie.cn/Article/details/gtvelapoca.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sufxvd.cn/Article/details/gtivopwlaq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtaomrpeiw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtjorgpqbo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgfzy.top/Article/details/gtxeqruhim.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gtigypkefi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.quarkkingdee.top/Article/details/gtqqarfoqg.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gtvivvwebz.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gtrihowiiz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gtnmwegfvd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtbsdphagg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtobrrxduk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtznjbkesl.html

Java: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtkyfkvosa.html

Go:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtuyejvyzy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtkzoullfd.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxikmcej.html

[A06] 字符串转数字
来源：http://dali.havefunace.top/Article/details/gtwgsfkupo.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gtrrufgvby.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daxiang520.top/Article/details/gtwkyharcz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gtmsnqqwxi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gtlgcgucff.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ivvv.top/Article/details/gtpmjruuxq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtyeuamcdj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gtpdzrpulb.html


<!-- 参考信息 -->