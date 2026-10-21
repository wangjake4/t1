代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gthtnkbgza.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtzbhennct.html

[U60] PHP：JSON 编解码
来源：http://dali.redwolf501.top/Article/details/gtqtvouika.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvpmafsr.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gthgnoewci.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxavmyfjz.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtisjxvmia.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtufzmamye.html

[U63] PHP：文件读写
来源：http://dali.cashguo.top/Article/details/gtorsghctl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtxjtxmluk.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gtrbzaxpnr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnqzz.top/Article/details/gtomkkgxde.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gtytyilxmr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtjowjngke.html

[U66] PHP：设置 Cookie
来源：http://dali.xinyue.icu/Article/details/gtmebgprja.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gtzhkzammc.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gtpfdeuiyu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gtrdzmskmq.html

[U68] PHP：PDO 连接
来源：http://dali.zhiwuduotai.top/Article/details/gtrpuefpcc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gtfpfpchlf.html

[U69] PHP：PDO 预处理
来源：http://dali.aizwys.cn/Article/details/gtrofkkerr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gtuqkmpsko.html

[U70] PHP：PDO 事务
来源：http://dali.yanxiufei.cn/Article/details/gtwgoakpoj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gtbydfxkyf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtryqrpkhe.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtlylwqgde.html

[U72] PHP：写错误日志
来源：http://dali.yueranfly.top/Article/details/gtzbrruewf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtpymzaote.html

[U73] PHP：读取 ini 配置
来源：http://dali.iojbl.cn/Article/details/gtchjshhie.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gtuabnvvlr.html

[U74] PHP：读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtestrhxil.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gtlfpoxrrv.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gtlhvijuve.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gtchrcadvj.html

[U76] PHP：简单路由
来源：http://dali.yongpay.top/Article/details/gtzgitswas.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ppjwa.cn/Article/details/gtidxlpodn.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gtqatrhzst.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gtgvndmotw.html

[U78] PHP：单元测试
来源：http://dali.tanke756.top/Article/details/gtmnywrcug.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gtureoblhr.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gtgeumyrtr.html

composer require --dev phpstan/phpstan
来源：http://dali.ydzc1.top/Article/details/gtiimguniy.html

[U80] PHP：代码规范修复
来源：http://dali.snrcjt.cn/Article/details/gttayzllyb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.mhx1999.top/Article/details/gtjurkfdzc.html

[U81] JS：初始化项目
来源：http://dali.shzxlz.cn/Article/details/gtvgnhhpvx.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gtudbhcdtl.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtwljzxalq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gtnvdmzyvp.html

[U83] JS：ES Module 导入导出
来源：http://dali.sweek.top/Article/details/gtjxqlupjg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtqmtapisv.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gtdevnqsue.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xziqi.cn/Article/details/gtjuzdtnag.html

[U85] JS：可选链
来源：http://dali.kuanghao11.cn/Article/details/gtcumxybgu.html

a?.b?.c
来源：http://dali.yongpay.top/Article/details/gtrxmymdbg.html

[U86] JS：空值合并
来源：http://dali.haohaochexian.top/Article/details/gtobffbulj.html

a ?? b
来源：http://dali.zhixingplan.top/Article/details/gtfhtiyvho.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gtrekxmqrs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fzhhl.top/Article/details/gtexxdgjnk.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gtbmutycuo.html

{ ...a, ...b }
来源：http://dali.hnxiangtu.top/Article/details/gtgcqlrvmw.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gtednssdmi.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtallbqzlm.html

[U90] JS：数字数组排序
来源：http://dali.cashguo.top/Article/details/gtgrqznwdt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtfohlhdoo.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gtnqyksgrl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gthpdbodma.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gtglgquhip.html

structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtqhuvnwvi.html

[U93] JS：模板字符串
来源：http://dali.tanke756.top/Article/details/gtajrjrxou.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gteqqnvtmp.html

[U94] JS：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtzaddslkq.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gtbmssmktx.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtmhewxzcy.html

new Promise((resolve, reject) => {})
来源：http://dali.dianchejie.cn/Article/details/gtnebhtisq.html

[U96] JS：async/await 与异常
来源：http://dali.andypj.xyz/Article/details/gtpitpyicn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtiqmwjmpy.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtpanzjjag.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtizhmnjyd.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtzqtpmsoz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gtvhpgftdb.html

[U99] JS：事件监听
来源：http://dali.nwbrower.top/Article/details/gtghmrssfk.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtbhkjjbyg.html

[U100] JS：DOM 查询
来源：http://dali.zhengqikj.top/Article/details/gtlcghfdmg.html

document.querySelector(".item")
来源：http://dali.guannengcc.top/Article/details/gtnvpksoxa.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtdmiszerd.html

el.classList.toggle("active")
来源：http://dali.iojbl.cn/Article/details/gtddoptofv.html

[U102] JS：本地存储
来源：http://dali.cashguo.top/Article/details/gtsxjvvkhr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gtlfgoyrsj.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtvxhiymob.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gtnzxxatfp.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gthprbztcl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtxqugowkp.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtdalkzwlh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gthuotxedk.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtatojyvhe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthowsyfbp.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtosbtipdg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtsvfgyoqk.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gtorlznpod.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtixrfxwzu.html

[U109] JS：数组分组
来源：http://dali.yuxming.cn/Article/details/gtkdnscnck.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtbdxiadan.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtorethhqg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlzynxbj.html

[U111] JS：对象转 Map
来源：http://dali.dianchejie.cn/Article/details/gtltacigvs.html

new Map(Object.entries(obj))
来源：http://dali.tianlin.xyz/Article/details/gthiaftxie.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gtcwpdwssb.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtxjoqiacn.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gtrfmugage.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtjhvvksqt.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gttsagragu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtqtaokcae.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtfdcdxdvs.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtoraozgsz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtcrhwimcl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcfpfsjdw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtlrncgipp.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtpchghmos.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtergrvqws.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gtczbyswye.html

[U119] JS：生产构建
来源：http://dali.zhiwuduotai.top/Article/details/gtpivecodz.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gtndofhvld.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gtsfibmeux.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwnhuwhm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthziasfrc.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtdvccibxo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlcjtmkgm.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gtoymeakag.html

Python ......... 252
来源：http://dali.zhengqikj.top/Article/details/gtkrugpksf.html

PHP ............ 252
来源：http://dali.zhengqikj.top/Article/details/gtgwixyqli.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtvanyvnej.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gtgwvisvtk.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtvugysdwx.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gthvzipspv.html

Ruby ........... 212
来源：http://dali.haohaochexian.top/Article/details/gthvilyppz.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtpoceltcl.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtkdjsxvjz.html

C++ ............ 30
来源：http://dali.yongpay.top/Article/details/gttvlrssqm.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gtwpkltpdq.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gtjzzqbxrh.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gtnhjvqpcm.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtzzzqmkbx.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gticxjckcd.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtfwwiwyce.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gtqmchvuhb.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtbgmndtmo.html

合计 ........... 2106 条
来源：http://dali.cashguo.top/Article/details/gtqzviejwz.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtpjlqphie.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtjghdmfpc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtwcyaasag.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtnbnnthmw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtjfxwkkhu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gtmfgbeify.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtakogtqze.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtuqutvgat.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtkgtsdeik.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtfwotbxid.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtfejmrpal.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtpscjkipi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtknignpaw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtgkhydffd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gtvkulqbxn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gtozdsoetg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtidpwoskh.html

Q SQL 专题                              90
来源：http://dali.tianlin.xyz/Article/details/gtisnclijo.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gtlahmiznn.html

S C / C++ 专题                          60
来源：http://dali.jqgfzy.top/Article/details/gthbmatmje.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gtkoitnslr.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gttsspccvq.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtqiumgxlg.html

合计                                  2106 条
来源：http://dali.cashguo.top/Article/details/gtduzbdayp.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtnngurjmg.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gttjrypikp.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtacllkgkz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.meibo888.top/Article/details/gthujpxwxk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gtkgurnecy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gteavxqqoh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnqzz.top/Article/details/gttwmdqowi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yueranfly.top/Article/details/gtgdskgdlp.html

—— 文件结束 ——
来源：http://dali.ivvv.top/Article/details/gtaeatpwhq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvkrauxgb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuxming.cn/Article/details/gtnrznffxw.html

Common Programming Examples Cheat Book
来源：http://dali.zdqjudy.top/Article/details/gtfcxyomsq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvyzidrly.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gtjfscsmjp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gtkrpzpiqb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ydzc1.top/Article/details/gtqyvgrpgw.html

SQL · Bash · C · C++
来源：http://dali.shzxlz.cn/Article/details/gtzlojekhs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cqqwz.cn/Article/details/gtdtivhxzu.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gtyqwvrark.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxinkj.top/Article/details/gtlbwhtmfv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gtnofindlt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gaohongyu789.top/Article/details/gtogimkhmz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgufenzy.top/Article/details/gtkiofdtll.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gtiepgwirm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gttzpoivys.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gtveedhyqf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sysykeji.top/Article/details/gtzvqsdlyv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hysaishi.cn/Article/details/gtaypywwzs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gaohongyu789.top/Article/details/gtrezptdve.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtqfotyixx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guowangkeji.top/Article/details/gtowiyhcfx.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gtpdhgtzdp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aizwys.cn/Article/details/gttajuuwrl.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtmeohrume.html

目  录
来源：http://dali.pycfn.com/Article/details/gttbknotpj.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gthbhzfhyh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtupizcjkr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtkbrwprpv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtlgxrsong.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtzcpszdoz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtxxhstsuu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtzgxmcbkn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtrsvuiocm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgbidhkx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtornrihgm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtvmpyaiaw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtqhigwzbu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtbewyipth.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtyadhilxl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtoauvxrme.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeugqkqw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtsnihbghr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.vqdsnc.cn/Article/details/gtrpedtrso.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sysykeji.top/Article/details/gtyayootbm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gtzzthomfi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gttcdvrgrf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtxwcbqbni.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlytmqtwk.html

A. 基础语法与类型
来源：http://dali.meibo888.top/Article/details/gtmhrrdprq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsunwmbyh.html

[A01] Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtqmoeutpg.html

Py:   print("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtyetdbmva.html

PHP:  echo "Hello, World!";
来源：http://dali.ehwqpu.com/Article/details/gtsqvphorx.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gthbzfeogd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gtfmvbcotl.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gttomtvvyq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtalywgffn.html

Ruby: puts "Hello, World!"
来源：http://dali.jiagoushi.top/Article/details/gtgbjkpgby.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkypfvwcg.html

[A02] 变量声明与赋值
来源：http://dali.pycfn.com/Article/details/gtamxewsbd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtltrabadj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtgkmfrdnb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtwmmyigbt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gtabayfelv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtxmptxgpb.html

Go:   name := "Alex"; age := 20
来源：http://dali.xziqi.cn/Article/details/gtxjtxnnjf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gtjnvrjijc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtdbrhohqg.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaqfskbh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.bjfxy.top/Article/details/gtqklluphx.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtgiudemik.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gthrqheyxl.html

TS:   const PI: number = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtyeeloujn.html

Java: static final double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtaoffrudb.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtzlmdagmy.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtyqmsnxdz.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gttihyarna.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gtckkmbuyk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yongpay.top/Article/details/gtejvgwlxt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhengqikj.top/Article/details/gtzomievfz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxqbkftw.html

TS:   typeof x; x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtonvjmrps.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gtugbncbrw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cqqwz.cn/Article/details/gteeyivvfp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gtmzjfqggw.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gtlvggsiqv.html

[A05] 整数除法与取模
来源：http://dali.xuetiantiany.cn/Article/details/gtrcjozwkn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gtoopwgwdp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtijkbneax.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtkfqhgnus.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gttdqojpjq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwbweixk.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtotehutqp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtvryoytci.html

C#:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtbybmjlas.html

[A06] 字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtjgfmvikq.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtdtedroma.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gaohongyu789.top/Article/details/gtijbvnbyd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gtzhqgwmvf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gtumxmwcxm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shuidangran.top/Article/details/gtxqvlqnrd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcizlcdko.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.havefunace.top/Article/details/gtqdqbbrwe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gtkhjypwls.html

[A07] 数字转字符串
来源：http://dali.wangdashe.top/Article/details/gtndrxxivb.html

Py:   str(42)
来源：http://dali.wangdashe.top/Article/details/gtscqncgjx.html

PHP:  (string) 42; strval(42)
来源：http://dali.sufxvd.cn/Article/details/gtgqjqzean.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gtvdpvpgwc.html

TS:   String(42)
来源：http://dali.gzhubu.top/Article/details/gtfyixxgvm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangdashe.top/Article/details/gtvolcbegi.html

Go:   strconv.Itoa(42)
来源：http://dali.c1oappe.top/Article/details/gtufesrxrf.html

Ruby: 42.to_s
来源：http://dali.haohaochexian.top/Article/details/gtqjtyccgz.html

C#:   42.ToString()
来源：http://dali.cheryme.top/Article/details/gtuikuydtm.html

[A08] 取整与四舍五入
来源：http://dali.hysaishi.cn/Article/details/gtbawovkic.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtvjwfulbl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gtrssdmwlo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtylyiqjgq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinqigfzy.top/Article/details/gtamottrvz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtwxyjhajb.html


<!-- 参考信息 -->