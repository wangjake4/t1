代发 wailian999

[U51] PHP：数组解构
来源：http://dali.9152youxi.cn/Article/details/gtkfotdxiu.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gtrytwuzxb.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtludoimjl.html

$double = fn($x) => $x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtnkemnbkl.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gtsrmvamwc.html

$v = $a ?? $b ?? "default";
来源：http://dali.sufxvd.cn/Article/details/gtpzyrezwz.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gteejwviml.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtqngyxxqo.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gtaiatadgv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtjerdizbb.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gtqmzymcgu.html

f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtmlwnxkzx.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtawuggwnz.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtcuyodwgj.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtzqdalxoa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jiagoushi.top/Article/details/gtopponvsf.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gtuoxhzkdz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtivwrwyft.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gtmripicgn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gtqkxugqgy.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gtxxdgywtb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtgsgefznf.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gtgoeplkmp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gthythpbay.html

[U63] PHP：文件读写
来源：http://dali.quarkkingdee.top/Article/details/gtooidqadr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ydzc1.top/Article/details/gtibndxrkb.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gtzpnndexh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtcfgoulcy.html

[U65] PHP：会话
来源：http://dali.cashguo.top/Article/details/gtnalmcnbd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtbtuuzvsp.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gtjiooolis.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxdfoevc.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gtvklvrcpu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gtaztpoexf.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gtjlihccva.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhongyouzk.top/Article/details/gtoquerscm.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtngdxyyia.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gtxezvgdfu.html

[U70] PHP：PDO 事务
来源：http://dali.haohaochexian.top/Article/details/gtvdqoruot.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhoulong.xyz/Article/details/gtoqqmqglo.html

[U71] PHP：抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtnhfmvdlr.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllndfjwm.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtkswpjjjr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gtcweattlr.html

[U73] PHP：读取 ini 配置
来源：http://dali.nwbrower.top/Article/details/gtwqrzvozo.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnqhwzls.html

[U74] PHP：读取环境变量
来源：http://dali.sysykeji.top/Article/details/gthfifbkij.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gtfcmwzpsf.html

[U75] PHP：依赖注入
来源：http://dali.yonumen.top/Article/details/gtmxtgbmau.html

composer require psr/container
来源：http://dali.pycfn.com/Article/details/gtdvngdqvs.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtmdwfigrj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhongyouzk.top/Article/details/gtmhsawlxl.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtpcxzhwsu.html

composer require twig/twig
来源：http://dali.shanyushiyangtech.top/Article/details/gtucslwrgf.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtpxphovzb.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gtrorhzinf.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtlvzavyor.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gtykcvmzua.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtwoyjdfmn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daria6918.cn/Article/details/gtznadrtoi.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtkktwxyve.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gtttzogzeh.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gtkvuawjok.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigufen.top/Article/details/gtxpdcfnrh.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gtogqipyqm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtowhxqeuv.html

[U84] JS：CommonJS 写法
来源：http://dali.yangfankeji.com/Article/details/gtzaobjeqm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhiwuduotai.top/Article/details/gtvxfyzdsq.html

[U85] JS：可选链
来源：http://dali.zhoulong.xyz/Article/details/gtwiwquavu.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gtqssnonle.html

[U86] JS：空值合并
来源：http://dali.yuxming.cn/Article/details/gtpadlytpc.html

a ?? b
来源：http://dali.yj202588.top/Article/details/gtmaphfjha.html

[U87] JS：解构默认值
来源：http://dali.yangfankeji.com/Article/details/gtvdvprryr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhiwuduotai.top/Article/details/gtiksbkiqb.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gtuuqeoyui.html

{ ...a, ...b }
来源：http://dali.yj20258888.top/Article/details/gtdmxrzknl.html

[U89] JS：数组去重
来源：http://dali.nanxinkj.top/Article/details/gtvuvhifdr.html

[...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gteopefowo.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gtvoseuzmp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtrmqwhcjb.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gtgjxtkeuo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtsdooaoqo.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtecocjkdq.html

structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtstkudmko.html

[U93] JS：模板字符串
来源：http://dali.dashuyun.cn/Article/details/gtzqsygwxf.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtaythgaoc.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtmumtplal.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtpehdclup.html

[U95] JS：Promise 包装
来源：http://dali.redwolf501.top/Article/details/gtiosebvhx.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtbmjkidpv.html

[U96] JS：async/await 与异常
来源：http://dali.c1oappe.top/Article/details/gttjsnqcgt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtoxvnsuof.html

[U97] JS：并发请求
来源：http://dali.hysaishi.cn/Article/details/gtlvlyidwn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtpmvvipsl.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigufen.top/Article/details/gtonqounfs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gtsoplfewo.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gtqmbthggr.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtdswwjnoe.html

[U100] JS：DOM 查询
来源：http://dali.zhiwuduotai.top/Article/details/gtbkloccse.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtlrycwiex.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gtqipgopai.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggwhexya.html

[U102] JS：本地存储
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevrwekzo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.vqdsnc.cn/Article/details/gtlbscnrxj.html

[U103] JS：定时器
来源：http://dali.xuanzx.com/Article/details/gttshkdidg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gtrfwygpii.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gtsyqqbyyv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtmrykiykx.html

[U105] JS：节流
来源：http://dali.fzhhl.top/Article/details/gtgmrmemlq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gtcroxmxtn.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtvmerlhap.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtwkvciraj.html

[U107] JS：数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtxfxdkdum.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtuqgytstn.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gtcbvuaepb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cashguo.top/Article/details/gteticeden.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtsvjzveii.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gttlgmjovm.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtjozzpwgc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gtdtcgdyiy.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gtffezqwvc.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gtfaybibpy.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gtaojyhfvp.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtnwwnpphu.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gtabvyktlg.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtcsugpile.html

[U114] JS：JSON 深比较
来源：http://dali.hysaishi.cn/Article/details/gtitiehvbe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtvstkrccu.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtxocyyqjf.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpkoiqci.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gtlgifwrfk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtjplstqce.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtjyiqziti.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gthwquiiib.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gtnaxdgvym.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gtyrosfqmz.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gtveqgepmk.html

npx vite build
来源：http://dali.xuanzx.com/Article/details/gtzghlkikg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtwbewbtnd.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtzygaplsv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzrozuuvd.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gtalwyvhsz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteevnhjjl.html

按语言统计（条）：
来源：http://dali.redwolf501.top/Article/details/gtifaqnahs.html

Python ......... 252
来源：http://dali.0kj1m.cn/Article/details/gtikxkgrqc.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gtzrvhuony.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gtasumssob.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gthnpshiwt.html

Java ........... 212
来源：http://dali.cashguo.top/Article/details/gtxbqbyyez.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gtligpveuy.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtfnpgeggi.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtmugzrjgm.html

C .............. 30
来源：http://dali.yj20258888.top/Article/details/gthczzvkgi.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtclquxgcq.html

SQL ............ 90
来源：http://dali.hnxiangtu.top/Article/details/gtdcfygdth.html

Bash ........... 80
来源：http://dali.yvedp.cn/Article/details/gtgbxaumco.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtppwuiino.html

Swift .......... 15
来源：http://dali.snrcjt.cn/Article/details/gtnlgtnnwt.html

Lua ............ 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbzrdocp.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gttqnzsogt.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gtsanfdqzv.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gttkkipuat.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gtqdnsolik.html

按章节统计：
来源：http://dali.hongshengwenyu.top/Article/details/gtgpnboiuh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtlbelcfcm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtycowkaxc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtffktqesf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtdwdsqadp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gtmguhvlsl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gtsqlafnzi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtsvuhkegf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtvakeaiij.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtdzhadqcm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtzofkeium.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtyehpkndp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtyjagjzos.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtqanjeukc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gteywgevxi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gtiginxlua.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gthaqoxxsp.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gtmxyiyxkg.html

R Bash 专题                             80
来源：http://dali.yongpay.top/Article/details/gtvijzzwie.html

S C / C++ 专题                          60
来源：http://dali.ehwqpu.com/Article/details/gtwcdamndb.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gtcgknoboy.html

U 高频实用片段                         120
来源：http://dali.yj20258.top/Article/details/gtqbjwzbfy.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtsruazcyd.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtrzpndncl.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtshgkcuge.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gtkzcoxxqv.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtatkihuwn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.svipenyu.cn/Article/details/gtfjkvuwbt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxrdexqn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcgfrcax.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhixingplan.top/Article/details/gtncksrahk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gtkupnumjt.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gtkpqljfqt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlpddugzm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtxljcjtwo.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gtsmcioswd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpgbtlfst.html

【收录内容】
来源：http://dali.quarkkingdee.top/Article/details/gthqxamplp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwuyrcnf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gtpspnzkmr.html

SQL · Bash · C · C++
来源：http://dali.sysykeji.top/Article/details/gthyolkxdu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tanke756.top/Article/details/gtarebwhmf.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gtpkcjycxg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gtlgwvkslc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzwbgnal.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hongshengwenyu.top/Article/details/gtzzruvhtv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nwbrower.top/Article/details/gtjbzludyq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtmjszhqcj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gtedqywngt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gtptdipegg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gtseukzwlf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xylfe.cn/Article/details/gtpyvvpsjh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cashguo.top/Article/details/gttmxyrbjy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfxwuwim.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.bjfxy.top/Article/details/gtoknvyevo.html

【文件统计】
来源：http://dali.daria6918.cn/Article/details/gtseodcxpd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gtmegrpeej.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtzlayxzdd.html

目  录
来源：http://dali.fengsongda.top/Article/details/gtsbttmttc.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtffjlxunx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gtzugjeyuc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtscjyxewo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtdwnufiho.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjbmtlpp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gttpgrsdbf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtphlepyet.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbcywuba.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gttxlqwhjg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtnuppjixa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gtxhkbdetq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gttihpajjm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtsvfioiqn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtowrxfqzf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtmwubyfco.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gtchnydmyw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtncebozac.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daxiang520.top/Article/details/gtvqzkdkwx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtgcfsivaq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gtfuqnctqy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtirqdlumx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbaxqqgo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkgeebkau.html

A. 基础语法与类型
来源：http://dali.yanxiufei.cn/Article/details/gtlyvukbvk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbzrhasxv.html

[A01] Hello World
来源：http://dali.yuxming.cn/Article/details/gtdjovywvn.html

Py:   print("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gthgntwcoo.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gtnuzmmueu.html

JS:   console.log("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtblasvhqn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtaejsrqux.html

Java: System.out.println("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gteotattmz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gtzszczmcv.html

Ruby: puts "Hello, World!"
来源：http://dali.sufxvd.cn/Article/details/gtmzlyhbye.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtpjhhsbem.html

[A02] 变量声明与赋值
来源：http://dali.gaohongyu789.top/Article/details/gtlgdnrguf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gtbjzjjuoe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangdashe.top/Article/details/gtdxinlgyb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gtazuzqmsy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ydzc1.top/Article/details/gtwemfrzed.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjghvhzmx.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuanzx.com/Article/details/gtoimhmuzp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daria6918.cn/Article/details/gtigeldblo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtmrydwzkt.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteejzvvgi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.birdmap.top/Article/details/gtdeexqqcs.html

PHP:  const PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtwferyimg.html

JS:   const PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtntdsdbmf.html

TS:   const PI: number = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtghecuuwi.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtsmiynork.html

Go:   const PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gtudejoqtb.html

Ruby: PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gtifmmxarj.html

C#:   const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtlchcvyjk.html

[A04] 判断变量类型
来源：http://dali.sufxvd.cn/Article/details/gtugxoaqxc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnwgmysu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gtrmusbdlo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gtqbdvsjam.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtlwrncyuj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yanxiufei.cn/Article/details/gtquruazdq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ppjwa.cn/Article/details/gtvxqamuim.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shzxlz.cn/Article/details/gtlqnmsnkn.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgufenzy.top/Article/details/gtnkhqwtok.html

[A05] 整数除法与取模
来源：http://dali.daria6918.cn/Article/details/gthmpnchcv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyhddlmc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtgxgtttxw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtonaibnnm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtvsntlcxs.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gthukdztip.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtonxktqvr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtjgitwqoy.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtbasmrsal.html

[A06] 字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtkwveyaat.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtifptrbql.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ybcxt.top/Article/details/gtfwmleyav.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtnilnervw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtgqzewdwj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.snrcjt.cn/Article/details/gthqsjeqmv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtqidvsfai.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhiwuduotai.top/Article/details/gtnyhuzunb.html


<!-- 参考信息 -->