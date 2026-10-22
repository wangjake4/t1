代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtypsmqlvf.html

$v = $a ?? $b ?? "default";
来源：http://dali.gogol.net.cn/Article/details/gtkhyjmman.html

[U54] PHP：空安全调用
来源：http://dali.hnqzz.top/Article/details/gtowebzvtg.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gtzmanvkce.html

[U55] PHP：match 表达式
来源：http://dali.bjfxy.top/Article/details/gtwaaoalfk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gtwsuxzckm.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtnmbadggo.html

f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtfztwgpvg.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gthzefvpmr.html

"值: {$a}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmxjuztt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gtpokszyrc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gtiabvdhpq.html

[U59] PHP：自定义排序
来源：http://dali.wangshuangyany.cn/Article/details/gtcopwhyxm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaffkwyrp.html

[U60] PHP：JSON 编解码
来源：http://dali.ivvv.top/Article/details/gttfafjgwi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtzkkbywoq.html

[U61] PHP：正则
来源：http://dali.pycfn.com/Article/details/gtpqwwdcqh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gthdpbtlda.html

[U62] PHP：日期对象
来源：http://dali.ppjwa.cn/Article/details/gtztxzdwsd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gtgyiifxja.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtealpjoxp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gtybcqpuvi.html

[U64] PHP：目录遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbcyujkt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gtgnrmdpby.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gtjwssgmob.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtlzfuamgg.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gtypvckkyh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgfzy.top/Article/details/gtvwfbsvxn.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gtrzzjduti.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gtntxnwiho.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gtgaovcupq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gtazmswgwx.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxuanxn.top/Article/details/gtjnqsqjow.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gteuuyrvzj.html

[U70] PHP：PDO 事务
来源：http://dali.yueranfly.top/Article/details/gtppmeprdv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gtpnwksvmp.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gttexwihdk.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gtpkzztysn.html

[U72] PHP：写错误日志
来源：http://dali.kuanghao11.cn/Article/details/gtfuefvgpb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gtnniwmzxt.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gthjufpwkg.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gtmyblgwef.html

[U74] PHP：读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlixasri.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gtypvfsldj.html

[U75] PHP：依赖注入
来源：http://dali.ivvv.top/Article/details/gtvtkpgiuj.html

composer require psr/container
来源：http://dali.feifeiyinyue.top/Article/details/gtxnnokvgr.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gttbunncqs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hysaishi.cn/Article/details/gtonxzfcde.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gtxbjickbf.html

composer require twig/twig
来源：http://dali.birdmap.top/Article/details/gturmlmsxa.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtbpwyizaa.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gthiujiezk.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gtrgvyuyln.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gtdegxnzzf.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gtiwudlsdt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.andypj.xyz/Article/details/gtcfhmlvil.html

[U81] JS：初始化项目
来源：http://dali.yueranfly.top/Article/details/gtnkalypga.html

npm init -y;  npm i express
来源：http://dali.sxryk.cn/Article/details/gtrhpejtbd.html

[U82] JS：package.json 脚本
来源：http://dali.tanke756.top/Article/details/gtesjavdmh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gtjckhblnn.html

[U83] JS：ES Module 导入导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaafxusmu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiencplg.html

[U84] JS：CommonJS 写法
来源：http://dali.yuanzhike.top/Article/details/gtwuoppilw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gtorfjczwm.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gtdufeluzf.html

a?.b?.c
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcatapya.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gtkzqbubir.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gttiethtyz.html

[U87] JS：解构默认值
来源：http://dali.aibaodan.cn/Article/details/gtfhgsdflw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sweek.top/Article/details/gtwhqatrdx.html

[U88] JS：对象展开合并
来源：http://dali.chenjidiqi.icu/Article/details/gtjjyxjgna.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gtazwrzsti.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gterajxfyw.html

[...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtizsfjoxx.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxabhkuxk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtjrtreajf.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gtilczrsdy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.iojbl.cn/Article/details/gtxwoufdzd.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gtdanckpbc.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtlcebrjte.html

[U93] JS：模板字符串
来源：http://dali.hnxiangtu.top/Article/details/gthibxbwqn.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gtcaqttsyo.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtwftqrael.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtenzkvejo.html

[U95] JS：Promise 包装
来源：http://dali.sufxvd.cn/Article/details/gtlgvghgqn.html

new Promise((resolve, reject) => {})
来源：http://dali.gotoacloud.top/Article/details/gthofppbpu.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gtnfkjbwcn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtuhpijmww.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gtasoiiikl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtwiussxak.html

[U98] JS：fetch 带 JSON
来源：http://dali.hammf.cn/Article/details/gtslieqxpb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gtnultxdjf.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtyrnziywu.html

el.addEventListener("click", e => {})
来源：http://dali.sxryk.cn/Article/details/gtwazfieab.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtlmokrukq.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gtwlwgeoll.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gtztbvotjc.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gtrivuhvqs.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtbefikbrw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gtzvlmwqtd.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gtaflwnrhc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtgzjscgor.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtppunylsb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtlwiwoizf.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtvjhnhwun.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtfgroqzio.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsbwmaby.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtzcnqsjfa.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gtasoilmnr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gtmozcukzp.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gtgvcmphdv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gteenaumqq.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gtltbxyviv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtjjwgosnv.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtucofyjqt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xylfe.cn/Article/details/gtrmwrvabm.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtjqbraszc.html

new Map(Object.entries(obj))
来源：http://dali.pycfn.com/Article/details/gtipbcyuyv.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtamwmpikn.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtdsqptewh.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gtmxgxqqxd.html

s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtfjsyfrzk.html

[U114] JS：JSON 深比较
来源：http://dali.zhongyouzk.top/Article/details/gtmfwteatf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtcffbyifi.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gtkxqynfnq.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gttyrcbxto.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gtmwxmktrg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gtwutkgyok.html

[U117] JS：单元测试
来源：http://dali.ehwqpu.com/Article/details/gtnfsyoxea.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gtcjuhvhgp.html

[U118] JS：开发服务器
来源：http://dali.hammf.cn/Article/details/gtkvxdjzif.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygmammcr.html

[U119] JS：生产构建
来源：http://dali.yj20258.top/Article/details/gtsgcfrqvr.html

npx vite build
来源：http://dali.bjfxy.top/Article/details/gtykqzwnkc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtpxqlhsug.html

import.meta.env.VITE_API_URL
来源：http://dali.shzxlz.cn/Article/details/gtrcbohdww.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxwjwdmne.html

统计汇总
来源：http://dali.yangfankeji.com/Article/details/gtglspqfjx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtinkxjpsq.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gtfpnlxixc.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gtjfuxicsy.html

PHP ............ 252
来源：http://dali.hammf.cn/Article/details/gtknfmuhtb.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gtputxntqp.html

TypeScript ..... 212
来源：http://dali.zhongyouzk.top/Article/details/gtrxgmyxwn.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtszjeqrqb.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtnsvyuyny.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtoqxwxapf.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtgucowccc.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gthgyyllsn.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gtiaronzbl.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtukeqjyqp.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gttceftdzh.html

Kotlin ......... 15
来源：http://dali.meibo888.top/Article/details/gtaxyemfse.html

Swift .......... 15
来源：http://dali.fengsongda.top/Article/details/gtkxaqetzw.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtzhzlqruw.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gtpkzsiiwm.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gtluacdsoh.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtifhvqllt.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtmzirtkui.html

按章节统计：
来源：http://dali.jinqigfzy.top/Article/details/gtzghyvgxf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtcbjkgmxk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtnmovkeks.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtixtkxtpa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gtmhidkoij.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gtihfsaock.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtyjrqtuff.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtjdsqkyuh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtfcgogiou.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtzdaiyeaw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtkqtxfhwr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtiyfyyzwv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtxhoorgho.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtcjjhxuri.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtepwbkgdd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gtqlyqbibu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gttqjnsmmr.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gtibpljadw.html

R Bash 专题                             80
来源：http://dali.svipenyu.cn/Article/details/gtoinhhzfp.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtzyhhljee.html

T 其他语言补充                          60
来源：http://dali.daxiang520.top/Article/details/gtotuwbykb.html

U 高频实用片段                         120
来源：http://dali.hnxiangtu.top/Article/details/gthozqndla.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtjogejrmk.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtncilwtwa.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtiwrpfryu.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gtvphtumpf.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtvxqhxyqf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtfkwscurq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gtnjmrqyea.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gtwmhwintz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gtotiquyku.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhongyouzk.top/Article/details/gtwpstdhye.html

—— 文件结束 ——
来源：http://dali.zhoulong.xyz/Article/details/gtofwzpmsw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzknazeht.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gtmhxbunts.html

Common Programming Examples Cheat Book
来源：http://dali.yangfankeji.com/Article/details/gttiitehec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtefyyknyo.html

【收录内容】
来源：http://dali.xinyue.icu/Article/details/gtafgeawyc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangdashe.top/Article/details/gtglebeqch.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenzaomai.com/Article/details/gtfxvsrtao.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtwzhasovy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daria6918.cn/Article/details/gthldxrofv.html

【使用说明】
来源：http://dali.yj20258.top/Article/details/gtbraqvgsh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cdnleiting.top/Article/details/gtbrtgaloy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gtwyfnclej.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cashguo.top/Article/details/gtkcezntyq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gtaxicummg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gtqxutelrc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.quarkkingdee.top/Article/details/gtpbfhnxzb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gtslszrnfs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sysykeji.top/Article/details/gticnmtqeb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.andypj.xyz/Article/details/gtpnpdtgyn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xinyue.icu/Article/details/gtuqtzwxum.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jianghu66.top/Article/details/gtgbxdkpww.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gtlmmvzaxr.html

【文件统计】
来源：http://dali.guannengcc.top/Article/details/gttkxazwer.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gtrtqemcpa.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtciuixqtm.html

目  录
来源：http://dali.yongpay.top/Article/details/gtttaqiybk.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtbjjwigfm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gttbpqhdca.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtdjivjzrf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtrbcgtpfe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtkurzmiyo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gtaghehjif.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtcpidazqs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtpyfgptea.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtwghiqbbi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtxprkmmnx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtiahjzfio.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtdjpqqfco.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtzjxxzbiu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtqwckrjra.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtljlofzeu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzajkpvkg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtxvjhvchd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shuidangran.top/Article/details/gtspxlkydf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlugxfuh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.kuanghao11.cn/Article/details/gtucytrmbz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtguwjrnve.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtbgibecsh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgynwsxdy.html

A. 基础语法与类型
来源：http://dali.jianghu66.top/Article/details/gtnfhgqvje.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqghihhvo.html

[A01] Hello World
来源：http://dali.zycfv.cn/Article/details/gtmdxukbob.html

Py:   print("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtaoffasmx.html

PHP:  echo "Hello, World!";
来源：http://dali.hongshengwenyu.top/Article/details/gtnmyvknaq.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtuadxcmyd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gtohhuczbp.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhylwrnv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtqmmejxzi.html

Ruby: puts "Hello, World!"
来源：http://dali.xziqi.cn/Article/details/gtdpknnckj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtsqrfxayf.html

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gturxkzudm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgufenzy.top/Article/details/gtttbuqwnd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtshtccmtw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yonumen.top/Article/details/gthmeujvuz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gtfhbycbwy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtunsbahgk.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gtzchihzlb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gtsgeqyedl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtkvoggjhl.html

[A03] 常量定义
来源：http://dali.bjfxy.top/Article/details/gtxcrinxil.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.smart0.xyz/Article/details/gtwqcaawxk.html

PHP:  const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtotnweyhe.html

JS:   const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtbsumwipo.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtdlzwhagh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtomndpbqk.html

Go:   const PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gtlltdaodi.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtatbitbzm.html

C#:   const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtazwvoyxa.html

[A04] 判断变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtgsrppsiz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gtubhiqrrr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gtgmqsayde.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtvchmosuc.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtukzqkciw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gtbxwmxreu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.c1oappe.top/Article/details/gtbfehrfrh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssvjgfiy.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhoulong.xyz/Article/details/gtwfiwljrg.html

[A05] 整数除法与取模
来源：http://dali.sysykeji.top/Article/details/gtsxyuegpu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yongpay.top/Article/details/gtbdfwxhdp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtsbtptxro.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtpubvolra.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtfsrbaynd.html

Java: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtbjwhavle.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtyetnszla.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtqutyfnak.html

C#:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtefcjoxqu.html

[A06] 字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtgvljipaz.html

Py:   int("42"); float("3.14")
来源：http://dali.daxiang520.top/Article/details/gtlanyoheg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yangfankeji.com/Article/details/gtivnkbmdw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtwnwawuho.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtxivlvrvy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtyqzyrwni.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258.top/Article/details/gtutnhydxf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtqcfdoz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sysykeji.top/Article/details/gtwdnboaco.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtobklxcre.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gtsbyqdbbo.html

PHP:  (string) 42; strval(42)
来源：http://dali.yongpay.top/Article/details/gtmjpjqhck.html


<!-- 参考信息 -->