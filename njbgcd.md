代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtnykhrpgl.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gtgpsdwkwd.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtpyddddlv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sufxvd.cn/Article/details/gtnqmskkft.html

[U59] PHP：自定义排序
来源：http://dali.ppjwa.cn/Article/details/gtkpswxbgw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtnosuqjly.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzqjoofl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cheryme.top/Article/details/gtblnrqist.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gteoyzqlkt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtmyxniqnm.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gtbqyxuykq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gtltjdispd.html

[U63] PHP：文件读写
来源：http://dali.ydzc1.top/Article/details/gtbwvtpbjs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cheryme.top/Article/details/gtcuvxfkok.html

[U64] PHP：目录遍历
来源：http://dali.ybcxt.top/Article/details/gtddmyfuvf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gtpsbawocc.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gtrjmvnnas.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtffokvpyz.html

[U66] PHP：设置 Cookie
来源：http://dali.aizwys.cn/Article/details/gtotvepymx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtevieyksf.html

[U67] PHP：处理文件上传
来源：http://dali.fzhhl.top/Article/details/gtozxaxywr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gtcsfbuyxx.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtaomnsqut.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxwfrmkf.html

[U69] PHP：PDO 预处理
来源：http://dali.cqqwz.cn/Article/details/gtfdbsmrad.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gtigvqkxrf.html

[U70] PHP：PDO 事务
来源：http://dali.yueranfly.top/Article/details/gtevmcgeoq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtiioqmrnl.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtmrsqqfxp.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gtirddbtee.html

[U72] PHP：写错误日志
来源：http://dali.zdqjudy.top/Article/details/gtwgkpvboe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.kuanghao11.cn/Article/details/gtblfdwlwc.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtlcpfqppf.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gtzedxtyau.html

[U74] PHP：读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtvzxvuybh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuanzhike.top/Article/details/gtklefcdcx.html

[U75] PHP：依赖注入
来源：http://dali.jinqigfzy.top/Article/details/gttumisvvf.html

composer require psr/container
来源：http://dali.gzhubu.top/Article/details/gtwcemonyq.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gtuksnmfol.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gttiazkiwn.html

[U77] PHP：模板渲染
来源：http://dali.shuidangran.top/Article/details/gtobfirwxf.html

composer require twig/twig
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcktfrkl.html

[U78] PHP：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtmfpwdiyl.html

composer require --dev phpunit/phpunit
来源：http://dali.wangshuangyany.cn/Article/details/gtodacymex.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gtqeklurrl.html

composer require --dev phpstan/phpstan
来源：http://dali.hnxiangtu.top/Article/details/gtcphvgaao.html

[U80] PHP：代码规范修复
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjbfgzfe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtxjtfljrt.html

[U81] JS：初始化项目
来源：http://dali.ybcxt.top/Article/details/gtlvqlperu.html

npm init -y;  npm i express
来源：http://dali.redwolf501.top/Article/details/gtdbceorgf.html

[U82] JS：package.json 脚本
来源：http://dali.tanke756.top/Article/details/gtgnumcdoz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sweek.top/Article/details/gtvuzvfgml.html

[U83] JS：ES Module 导入导出
来源：http://dali.aibaodan.cn/Article/details/gtkagkmjnc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtjruzrogh.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gtaagvomeu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gtxqcfiehh.html

[U85] JS：可选链
来源：http://dali.yuanzhike.top/Article/details/gtfizeweqe.html

a?.b?.c
来源：http://dali.jqgfzy.top/Article/details/gtmcbxwyvp.html

[U86] JS：空值合并
来源：http://dali.shangyingyoupin.top/Article/details/gtmvrazvla.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gtrvzgpkiu.html

[U87] JS：解构默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtxvbkzhzk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gtpiitdrpm.html

[U88] JS：对象展开合并
来源：http://dali.jyoumei.cn/Article/details/gtbsttizhg.html

{ ...a, ...b }
来源：http://dali.havefunace.top/Article/details/gtrjzgrjvb.html

[U89] JS：数组去重
来源：http://dali.cashguo.top/Article/details/gtxrxkufcl.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gttdyrcnji.html

[U90] JS：数字数组排序
来源：http://dali.hfpthk.cn/Article/details/gtihzzazof.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnqldxcg.html

[U91] JS：对象键值遍历
来源：http://dali.zhongyouzk.top/Article/details/gtzpsgcrwx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gtbrfwowzj.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gttvpovaym.html

structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtvghetkmg.html

[U93] JS：模板字符串
来源：http://dali.gogol.net.cn/Article/details/gtgdonmsit.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gtqpnrmmhb.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtxxgxvzrj.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gtkqvcjpul.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gtxupoiefw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtsisyfavg.html

[U96] JS：async/await 与异常
来源：http://dali.jqgfzy.top/Article/details/gtdjahadll.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtwnpnwknd.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtfravvvgr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtmzmglvcg.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gthuijcpdg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenlongwang.top/Article/details/gtjujyyila.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gthtbkrhnb.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gtrrpjmloa.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtvdfhqvfw.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gteeqybtnv.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtiwsnzdvt.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttncfofdr.html

[U102] JS：本地存储
来源：http://dali.jqgufenzy.top/Article/details/gtckbgkphk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.andypj.xyz/Article/details/gtruonyihb.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gtkscknaut.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gtwjhczupv.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gtqwpxytoc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gthyxnyrtl.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gtcmyhvrbt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ivvv.top/Article/details/gtvnnzglgm.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtufgmslhq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guowangkeji.top/Article/details/gtzllfiluz.html

[U107] JS：数字千分位
来源：http://dali.nwbrower.top/Article/details/gtudwwyujr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtetawsugh.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtoysoftzh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tianlin.xyz/Article/details/gtevtfvxoo.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokftegyg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtmacxlbnf.html

[U110] JS：数组分块
来源：http://dali.sweek.top/Article/details/gteobqkfhy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gtozgbektx.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gtwsqnvlyi.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gttxezbuse.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gtycufywzu.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtcaqjxfst.html

[U113] JS：正则替换全部
来源：http://dali.yj20258888.top/Article/details/gtzanwvoga.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtyjdflzkn.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtbpcjftqm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtltvwkvll.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtgxahprzn.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtdpymwgqk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gtklfmwaou.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtyemvqwuf.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gtgvcxpswl.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gttnlsjktr.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gtvdscxqpr.html

npm i -D vite;  npx vite
来源：http://dali.gogol.net.cn/Article/details/gtovxlhcey.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtmqnqkemd.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtkfosqwgi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jlsjyb.cn/Article/details/gtdprmocts.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gtlipuuwlk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwcyddiap.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtfzxytqhz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcnebrljy.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gthwmeidke.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtbyqmlnwm.html

PHP ............ 252
来源：http://dali.gotoacloud.top/Article/details/gtlkzikgdv.html

JavaScript ..... 252
来源：http://dali.shuidangran.top/Article/details/gtdccccrye.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gttmghibcf.html

Java ........... 212
来源：http://dali.yvedp.cn/Article/details/gtvruvzyxq.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtpucfvdjr.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjdvaitu.html

C# ............. 212
来源：http://dali.nwbrower.top/Article/details/gtclqhjljq.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gtebrnkrry.html

C++ ............ 30
来源：http://dali.xuetiantiany.cn/Article/details/gtmjmkwnro.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtakvownjz.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gtvnqwlxol.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtuvdalyek.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtrmqsxfyh.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gthqpswnza.html

Perl ........... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsonibde.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtewxxzluq.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtsbaazxrb.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtngtweogm.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtsoiralyk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gttghcznez.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtfnrvgbrl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtudkknsue.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtruzlflte.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtmhwakgph.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gtdidhqilr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtqqhrwcfy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtpjlfvvkc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtphfeeopy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtbxqkgkxp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtnpuewxlh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtmnwiaxti.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtvnjnxnxw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtgtppxjst.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtsqczyafd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtwahqquby.html

Q SQL 专题                              90
来源：http://dali.hnxiangtu.top/Article/details/gtbvryjlfs.html

R Bash 专题                             80
来源：http://dali.shzxlz.cn/Article/details/gtfeuznily.html

S C / C++ 专题                          60
来源：http://dali.andypj.xyz/Article/details/gtinasldft.html

T 其他语言补充                          60
来源：http://dali.shuidangran.top/Article/details/gtbtdwrmnw.html

U 高频实用片段                         120
来源：http://dali.jyoumei.cn/Article/details/gtgqztwihy.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtblsbmafe.html

合计                                  2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtdfnqpttk.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtchpqzifc.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gtzzcyqxsq.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtvnmharlc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuanzhike.top/Article/details/gtjhohiexb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gtiatvfkcr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvahmvil.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gtofkpexwu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gtakpkwpwo.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmqihcxw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtibdzjqob.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xylfe.cn/Article/details/gtylimtiob.html

Common Programming Examples Cheat Book
来源：http://dali.dashuyun.cn/Article/details/gtxixypdzm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtahjhlwmv.html

【收录内容】
来源：http://dali.vqdsnc.cn/Article/details/gtwkfjjpas.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.havefunace.top/Article/details/gtwzmixucf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dianchejie.cn/Article/details/gtlblgwjpr.html

SQL · Bash · C · C++
来源：http://dali.xinyue.icu/Article/details/gtozqalqod.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gtqxhntfqw.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gtzmzzsvaj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gtwumrweyp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigfzy.top/Article/details/gtktmhnpiw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.andypj.xyz/Article/details/gtmumxyqxh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ybcxt.top/Article/details/gtgjpzvplo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jyoumei.cn/Article/details/gthdqagvpf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yongpay.top/Article/details/gtjggmjbdy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gtkxfothxv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.redwolf501.top/Article/details/gtyguqkkxk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ivvv.top/Article/details/gtvwfmhrmv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.smart0.xyz/Article/details/gtwazdemrh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gtfxlpebmn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pycfn.com/Article/details/gtqpxyhswx.html

【文件统计】
来源：http://dali.xylfe.cn/Article/details/gthuvwrmdz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtrrbarmnb.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtoxvoqeww.html

目  录
来源：http://dali.chenzaomai.com/Article/details/gtttwkelqu.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtbtsokkze.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gtjvzunkmf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtkecxqdcd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtqcfazoxh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtuqphgmad.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.kuanghao11.cn/Article/details/gthfnuskre.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gttkhkpogk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtdkdorouf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gtvwubgyyc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtyosnkwnu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gtbqdeczbf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtdnfreiim.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvmeknos.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtxodmrrnn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtbauhirwk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gtprlxqrwk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtttwrzxme.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.svipenyu.cn/Article/details/gtaudnzihl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258.top/Article/details/gtrhgnjelp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jyoumei.cn/Article/details/gtecricjsj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gtdksfwtfo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtgxthklui.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvseygaij.html

A. 基础语法与类型
来源：http://dali.c1oappe.top/Article/details/gtuegwndcj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdhlycyyw.html

[A01] Hello World
来源：http://dali.cucudq.cn/Article/details/gtvgtnwjon.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtnqcrzjlz.html

PHP:  echo "Hello, World!";
来源：http://dali.gaohongyu789.top/Article/details/gtwiguhyau.html

JS:   console.log("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gtjmjdghuk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gtmjppaqso.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtewunowvq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtspmvzhvz.html

Ruby: puts "Hello, World!"
来源：http://dali.shuidangran.top/Article/details/gttoneuiwi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyhjxylv.html

[A02] 变量声明与赋值
来源：http://dali.meibo888.top/Article/details/gtllzgsice.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gtvqfwzvqg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gtlkxunzqx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtuoudlruy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gtazrwrwwt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtjwwdfgiy.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gtastadbnx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gthvhgplex.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtnakwynlc.html

[A03] 常量定义
来源：http://dali.nanxuanxn.top/Article/details/gtbamdkcfn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnxiangtu.top/Article/details/gtecjrgtfi.html

PHP:  const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtrfgdaaeb.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtpqohlfgm.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtmwrcyovx.html

Java: static final double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtljopxssj.html

Go:   const PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gtrxpjecby.html

Ruby: PI = 3.14159
来源：http://dali.zhoulong.xyz/Article/details/gtntsvbyzw.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtrpkyfkat.html

[A04] 判断变量类型
来源：http://dali.nwbrower.top/Article/details/gthtlsjngj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsbthvbu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jianghu66.top/Article/details/gthtbvmzzt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtyduvffpq.html

TS:   typeof x; x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtcumysrog.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hongshengwenyu.top/Article/details/gtfxfksalv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkxkhrse.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuetiantiany.cn/Article/details/gtvrxdaivb.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbcluwuv.html

[A05] 整数除法与取模
来源：http://dali.shangyingyoupin.top/Article/details/gtjgoyjwkt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthouehnvh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtunryapoq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtacvrmefq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtanqegxzx.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtqgttgtev.html

Go:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtyipqbqvn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gthuyjkmmu.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcgjrtyb.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gttxxjcvlj.html

Py:   int("42"); float("3.14")
来源：http://dali.sxryk.cn/Article/details/gtypomjeej.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yvedp.cn/Article/details/gtxmwkovsy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xylfe.cn/Article/details/gtqtnitnjt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gtxgvwseww.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gticwejxpn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gtquhfynge.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gtlbglcdvt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aizwys.cn/Article/details/gtihhyddmr.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gttbdthldu.html

Py:   str(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtzbsynddd.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmchlwymr.html

JS:   String(42); (42).toString()
来源：http://dali.jqgufenzy.top/Article/details/gtjqjiemiu.html

TS:   String(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtzmpcpvnc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenlongwang.top/Article/details/gtcghyntbv.html

Go:   strconv.Itoa(42)
来源：http://dali.pycfn.com/Article/details/gtzycokexe.html

Ruby: 42.to_s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiwovvky.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gttgkyysgn.html

[A08] 取整与四舍五入
来源：http://dali.sweek.top/Article/details/gtppssimbe.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtbzabfhih.html


<!-- 参考信息 -->