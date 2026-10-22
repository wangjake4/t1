代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gtpynzzdze.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gtngfwgucv.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gtoqtzcmwb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtmuvemlqe.html

[U59] PHP：自定义排序
来源：http://dali.zycfv.cn/Article/details/gtdiitwufk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gttmmhjssv.html

[U60] PHP：JSON 编解码
来源：http://dali.birdmap.top/Article/details/gtfzygwxjr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.kuanghao11.cn/Article/details/gttvgelzku.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gthesmfagk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtlrqohmru.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gthxcemuas.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gtzkyugpcp.html

[U63] PHP：文件读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbglhezze.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gtalcrtdmg.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gttsgkuflp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtsjzooizv.html

[U65] PHP：会话
来源：http://dali.shanyushiyangtech.top/Article/details/gtznjrovau.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkndjuhsp.html

[U66] PHP：设置 Cookie
来源：http://dali.xziqi.cn/Article/details/gtgsehpuvd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gtorwczcyx.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gtgdsmukpl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gtszsmqcba.html

[U68] PHP：PDO 连接
来源：http://dali.cqqwz.cn/Article/details/gtuwjxqigu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daxiang520.top/Article/details/gtmubhpoya.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gtpvqjdrex.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gtbytflgpq.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtyrbrymuj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.316326.xyz/Article/details/gtltfqpent.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtoylnebtv.html

throw new RuntimeException("失败", 500);
来源：http://dali.sxryk.cn/Article/details/gtzjlkvibv.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtnnieoynu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gtzdspvvwm.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtfqijjboc.html

parse_ini_file("config.ini", true)
来源：http://dali.ivvv.top/Article/details/gtnyeubqos.html

[U74] PHP：读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtgfdiwvkv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtfmzkacty.html

[U75] PHP：依赖注入
来源：http://dali.daria6918.cn/Article/details/gtrngvobqb.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtglfzwvni.html

[U76] PHP：简单路由
来源：http://dali.vqdsnc.cn/Article/details/gtfaejcksz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgfzy.top/Article/details/gtaecukyfd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gtjezkbtrm.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gtixwqkcho.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtriqmcuhq.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhnoiwpi.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gteyvzagir.html

composer require --dev phpstan/phpstan
来源：http://dali.vqdsnc.cn/Article/details/gtutygtegf.html

[U80] PHP：代码规范修复
来源：http://dali.ydzc1.top/Article/details/gtcfjpjcea.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pycfn.com/Article/details/gtmtqsvewx.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gtqlftouwc.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gtkhgmjjjh.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gtyfrutntw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gteyqmqyxz.html

[U83] JS：ES Module 导入导出
来源：http://dali.quarkkingdee.top/Article/details/gtnkdkhinf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtscuuracb.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigfzy.top/Article/details/gtpamfztnz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gtprhdvwpg.html

[U85] JS：可选链
来源：http://dali.yanxiufei.cn/Article/details/gtktfujwxp.html

a?.b?.c
来源：http://dali.nanxinkj.top/Article/details/gtfosmmpxq.html

[U86] JS：空值合并
来源：http://dali.sxryk.cn/Article/details/gtvbengkje.html

a ?? b
来源：http://dali.cdnleiting.top/Article/details/gtorwlwfyy.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gtlgoiuomj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfecilbh.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gtrojyurlu.html

{ ...a, ...b }
来源：http://dali.c1oappe.top/Article/details/gtiyvuvwhm.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gtqbeqcnor.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlljcrfdx.html

[U90] JS：数字数组排序
来源：http://dali.dashuyun.cn/Article/details/gttjoemaeg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtwvdklrrq.html

[U91] JS：对象键值遍历
来源：http://dali.yvedp.cn/Article/details/gtkabypqod.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.iojbl.cn/Article/details/gtvwneflxp.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtycvakcda.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtpquwmhzq.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gtzuymmiyw.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gtjcfslzok.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gtbrjvrdmq.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtvzkvqouz.html

[U95] JS：Promise 包装
来源：http://dali.zhiwuduotai.top/Article/details/gtigtlmrbe.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtftuuyotv.html

[U96] JS：async/await 与异常
来源：http://dali.tanke756.top/Article/details/gtksycqcym.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtxgojokcr.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdnhqbsh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanvayoys.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gtqglrdafz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zdqjudy.top/Article/details/gtrlccpufp.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gtnytigdhp.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gtntxbcnfo.html

[U100] JS：DOM 查询
来源：http://dali.hnqzz.top/Article/details/gtmmcdbtfl.html

document.querySelector(".item")
来源：http://dali.nanxuanxn.top/Article/details/gtqohozgjn.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gtfmulrofo.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmefngyg.html

[U102] JS：本地存储
来源：http://dali.zhixingplan.top/Article/details/gtxbjglwsi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhiwuduotai.top/Article/details/gtddmjzbfr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gtxlnbzulb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gtovjnhqir.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gtdladthti.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtueiqoehx.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtzovfmzgp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tanke756.top/Article/details/gtlzngqpmu.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtibazbbls.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxuanxn.top/Article/details/gthulqeqpx.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdkqxjug.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtvhzrpiig.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gtwzdsokln.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gtcvonplve.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gtdjsdofwb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtpukmjicu.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtqnvqsymj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gtrpngvpdd.html

[U111] JS：对象转 Map
来源：http://dali.gogol.net.cn/Article/details/gtypwlcodx.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gtbydgiuqu.html

[U112] JS：字符串补位
来源：http://dali.jyoumei.cn/Article/details/gtefcfvbpg.html

"7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtxbwsdbvb.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gtdmlwfbtb.html

s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtyftjfjju.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gtrrsvhhyb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtirltguva.html

[U115] JS：生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtnfmtnxjh.html

crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtvlcdxfus.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gtnjkeyrcs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtjrcqhklx.html

[U117] JS：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtziuvsgqj.html

npm i -D vitest;  npx vitest
来源：http://dali.pycfn.com/Article/details/gtxarwvkmm.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtgmmjjbur.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gteyknpaaj.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtekvjbuoh.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gtcoriowsq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fzhhl.top/Article/details/gtmbkkacny.html

import.meta.env.VITE_API_URL
来源：http://dali.hfpthk.cn/Article/details/gttdrupavm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnxcxmfad.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbngagom.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtscphabsf.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtgnaynsma.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gtkgyqcxlm.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gtbnevuxug.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gticcaqfgf.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gteupuarqt.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtswianlsf.html

Go ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtwsgyqblz.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpqxwiiq.html

C# ............. 212
来源：http://dali.andypj.xyz/Article/details/gtsxdnxujh.html

C .............. 30
来源：http://dali.sweek.top/Article/details/gtdlwozbjz.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtjhhjgnxt.html

SQL ............ 90
来源：http://dali.jinghuilouyu.cn/Article/details/gthggfqvri.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gtxngnbkrb.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtzaytxsmy.html

Swift .......... 15
来源：http://dali.sysykeji.top/Article/details/gtwvtrsgsl.html

Lua ............ 10
来源：http://dali.gaohongyu789.top/Article/details/gtilgqglaf.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gtedykyknr.html

Scala .......... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrazkoxo.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtchgmnetm.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gtkzvrqgdf.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gtmrrsmgxc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtenwcppme.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtyguorrsx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtwkjnssyr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtvtpqidmk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gtiyzskefq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gtodmoiybd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtshruvmrg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gtwtnncfjd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtwfztibhz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtnhtelhhl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtjwgfcdjf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtcehhsfeq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtqytrgenm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkqtudtm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtyqtudbxu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtfitaeotf.html

Q SQL 专题                              90
来源：http://dali.jinqigfzy.top/Article/details/gtuhncsybj.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gtdhskxmwb.html

S C / C++ 专题                          60
来源：http://dali.jyoumei.cn/Article/details/gtxozbzkse.html

T 其他语言补充                          60
来源：http://dali.yangfankeji.com/Article/details/gtsgcrirwh.html

U 高频实用片段                         120
来源：http://dali.pycfn.com/Article/details/gttzhjiwlz.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtqbhfljoz.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtkriwtxdr.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtulcctjtv.html

使用提醒
来源：http://dali.xinyue.icu/Article/details/gttfmrempo.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtpbvseyee.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gotoacloud.top/Article/details/gtihdrmboy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtzahiwycj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigufen.top/Article/details/gtkdidaxir.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gtmhsaeeis.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jiagoushi.top/Article/details/gttglmgoez.html

—— 文件结束 ——
来源：http://dali.gaohongyu789.top/Article/details/gtkeieovwx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtiysrriqs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ydzc1.top/Article/details/gtdwgxtiwj.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gtvukerklr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpwvdzxnm.html

【收录内容】
来源：http://dali.nwbrower.top/Article/details/gtfymdljsb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfldscok.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sufxvd.cn/Article/details/gtkyrmlerw.html

SQL · Bash · C · C++
来源：http://dali.yueranfly.top/Article/details/gtowbznesj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hysaishi.cn/Article/details/gtqesnylco.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gtmhjznlcg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gtjriiazdh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gthplgzihh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gtuczslogt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gtdlzwckpy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hywenlv.cn/Article/details/gtbpzdggmn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.andypj.xyz/Article/details/gtkprmhuek.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cqqwz.cn/Article/details/gtxjkxoaph.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.vqdsnc.cn/Article/details/gtyvevdlnb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.vqdsnc.cn/Article/details/gtacbwxkok.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guowangkeji.top/Article/details/gtsturuvuj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gtoovilkdd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.kuanghao11.cn/Article/details/gtvvpcgoil.html

【文件统计】
来源：http://dali.aibaodan.cn/Article/details/gtahutccqp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgfzy.top/Article/details/gtebyksuxh.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtubklvens.html

目  录
来源：http://dali.yj20258.top/Article/details/gtbhhpxrhg.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtvpkuodva.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gthmniahas.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtzyutkxux.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtoinhzkib.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hfpthk.cn/Article/details/gteqrbtfgg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hywenlv.cn/Article/details/gtbpazyezc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gterqitdhv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtczaplecr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gthgsdyenh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtywqfqmcy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gtjcxglfgq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtyjqlsjmo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtstekoumo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtisfxtsuo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtuzbrdply.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guowangkeji.top/Article/details/gtpczoiydi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtokideowh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aibaodan.cn/Article/details/gtdcosfxnu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sysykeji.top/Article/details/gtewuyngdt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jlsjyb.cn/Article/details/gtjemtcyjw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtmztxtgch.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtqixxumal.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxyisnhuu.html

A. 基础语法与类型
来源：http://dali.sweek.top/Article/details/gtotaeyuln.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfxnqnlte.html

[A01] Hello World
来源：http://dali.havefunace.top/Article/details/gtbxmqltmy.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gtgurrqdpw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhixingplan.top/Article/details/gtvvwvvkqx.html

JS:   console.log("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtqjpymcbv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gtnubdawvn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtisxxcrtm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtyczdyhzr.html

Ruby: puts "Hello, World!"
来源：http://dali.chenjidiqi.icu/Article/details/gttguntwng.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtcfdzgpuk.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gtorbocykp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guannengcc.top/Article/details/gtnmtdclvj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gzhubu.top/Article/details/gtqzsiltid.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbudbuqc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pycfn.com/Article/details/gtxhprjtkc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtxizduvgh.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gtunxuiorl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gtyhkkdkzc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtrcpltjdm.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gthptaoywd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gtvfmidyfo.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtuulxyvsw.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtlbmobcjp.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtucopqkgx.html

Java: static final double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtpcgranhq.html

Go:   const PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gtpavqrvqw.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtahlidl.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtfbhilifg.html

[A04] 判断变量类型
来源：http://dali.316326.xyz/Article/details/gtendgxwcp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cashguo.top/Article/details/gtppelewgg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cucudq.cn/Article/details/gtdpgdpbfa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtuxiqtpvk.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtsiqfirxr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gtnrlijdex.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gtzvffmdac.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gtrpwilaxm.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gtzbpqendg.html

[A05] 整数除法与取模
来源：http://dali.xinyue.icu/Article/details/gtpqvmykwg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gtmuujagpu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gttecsupex.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtxxlwagcy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtbyzeuqms.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtxdkosojh.html

Go:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtncwdrgsh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtomszynqg.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtphnpimky.html

[A06] 字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtwnxiorpd.html

Py:   int("42"); float("3.14")
来源：http://dali.fengsongda.top/Article/details/gtvtkbqrep.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shzxlz.cn/Article/details/gtswmnagcn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gtpbswmpao.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtquovjrjf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtrqloefgg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sufxvd.cn/Article/details/gtfutizqef.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sxryk.cn/Article/details/gtzsktegky.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtkaoxscal.html

[A07] 数字转字符串
来源：http://dali.yj20258888.top/Article/details/gtwbzctkcs.html

Py:   str(42)
来源：http://dali.aizwys.cn/Article/details/gteascbbzp.html

PHP:  (string) 42; strval(42)
来源：http://dali.0kj1m.cn/Article/details/gtxywrrzpi.html

JS:   String(42); (42).toString()
来源：http://dali.ybcxt.top/Article/details/gtsstgpzkp.html

TS:   String(42)
来源：http://dali.pycfn.com/Article/details/gtghvwcxwa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258.top/Article/details/gtbdonfmgs.html

Go:   strconv.Itoa(42)
来源：http://dali.quarkkingdee.top/Article/details/gtedunsgqf.html

Ruby: 42.to_s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiclyivq.html

C#:   42.ToString()
来源：http://dali.cucudq.cn/Article/details/gtvphqclnw.html

[A08] 取整与四舍五入
来源：http://dali.daxiang520.top/Article/details/gtvkskzvhl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtfojwovcp.html


<!-- 参考信息 -->