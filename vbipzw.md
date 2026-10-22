代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2ctwopunx.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gt2hqexfbys.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gt2alfmztkz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2swcvtnml.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffumnnrj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cljdgoxl.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gt2fdszmfvi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2jezqcibd.html

[U61] PHP：正则
来源：http://dali.cashguo.top/Article/details/gt2ketlecvi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2yiyrazrz.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gt2bpxvtbyt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gt2fchobidk.html

[U63] PHP：文件读写
来源：http://dali.hfpthk.cn/Article/details/gt2qqxuqsgd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gt2okdlirtn.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2wsyhjyfo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gt2pbzndagi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lffyypre.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2rlwrpnoc.html

[U66] PHP：设置 Cookie
来源：http://dali.cdnleiting.top/Article/details/gt2pcphvisi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jianghu66.top/Article/details/gt2dtmbipje.html

[U67] PHP：处理文件上传
来源：http://dali.shuidangran.top/Article/details/gt2mmkpkqzg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gt2biewdjpr.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gt2uehxrwru.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gt2ljeflidd.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2knntoazg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gt2bqqbtljz.html

[U70] PHP：PDO 事务
来源：http://dali.xylfe.cn/Article/details/gt2seflgyab.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gt2luaklfxt.html

[U71] PHP：抛出异常
来源：http://dali.pycfn.com/Article/details/gt2kisgfeli.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gt2enovekog.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gt2wxybdyqb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yueranfly.top/Article/details/gt2uwekkdcg.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gt2qphspooc.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gt2ulvyhttx.html

[U74] PHP：读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2jsmfuihb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gzhubu.top/Article/details/gt2ljjdmryv.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohpxhizf.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gt2kzqvkwau.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gt2grartykw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gt2khowoyqo.html

[U77] PHP：模板渲染
来源：http://dali.fengsongda.top/Article/details/gt2fizejeuo.html

composer require twig/twig
来源：http://dali.yj20258.top/Article/details/gt2qxistjdu.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvnflury.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gt2faeqwuzi.html

[U79] PHP：静态分析
来源：http://dali.ybcxt.top/Article/details/gt2pkjfffxm.html

composer require --dev phpstan/phpstan
来源：http://dali.yangfankeji.com/Article/details/gt2psmfspdw.html

[U80] PHP：代码规范修复
来源：http://dali.cheryme.top/Article/details/gt2yolqnzxs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhaousob.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gt2shtkinug.html

npm init -y;  npm i express
来源：http://dali.jinqigufen.top/Article/details/gt2axpzmrye.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gt2fidqpozs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gt2bsurvaxe.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenzaomai.com/Article/details/gt2xmcpwmbd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gt2ybyotuuy.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gt2noypnivx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shzxlz.cn/Article/details/gt2xppmleik.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gt2ekpcdlaa.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gt2fsexmzbu.html

[U86] JS：空值合并
来源：http://dali.yuxming.cn/Article/details/gt2qaaouscm.html

a ?? b
来源：http://dali.cqqwz.cn/Article/details/gt2iorkenbs.html

[U87] JS：解构默认值
来源：http://dali.ehwqpu.com/Article/details/gt2eoctzett.html

const { a = 1, b = 2 } = obj;
来源：http://dali.c1oappe.top/Article/details/gt2waneqiyz.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gt2stvdfjjx.html

{ ...a, ...b }
来源：http://dali.sweek.top/Article/details/gt2lylnvhae.html

[U89] JS：数组去重
来源：http://dali.tianlin.xyz/Article/details/gt2bhyxiuvr.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2rxofhusu.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gt2xnwqwvsg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2qzshphsb.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gt2zpdescsm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlzxfma.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2ashqtbuq.html

structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2uwdalaqh.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gt2eqftjgib.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soqofvgk.html

[U94] JS：箭头函数
来源：http://dali.shuidangran.top/Article/details/gt2trtbqfio.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rufyzwvg.html

[U95] JS：Promise 包装
来源：http://dali.snrcjt.cn/Article/details/gt2xpyxiqzg.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gt2iutsrkcg.html

[U96] JS：async/await 与异常
来源：http://dali.aibaodan.cn/Article/details/gt2fmdlitky.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2mpgfxhfy.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gt2igdxotps.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2mxhbjwyy.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2qonzccpu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxuanxn.top/Article/details/gt2zqvfyltz.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gt2kflbxrlv.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gt2ldkcapjx.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gt2bbodblol.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gt2wlixkthe.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gt2ynizhagd.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gt2vwldzbgk.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gt2imkpgpjx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gt2qhutxkdt.html

[U103] JS：定时器
来源：http://dali.jqgufenzy.top/Article/details/gt2vohasgra.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gt2szosavnm.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gt2ylcqloeu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdhmpynx.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gt2pkqfshdr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gt2vrkrxnyw.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2oseqruxo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gt2kpravsni.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gt2hopbqyoe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gt2denfwsde.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlloywdv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjohcvvf.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gt2tclrcapv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gt2kducbncq.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gt2swsvkenz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dianchejie.cn/Article/details/gt2mzsyeket.html

[U111] JS：对象转 Map
来源：http://dali.hnqzz.top/Article/details/gt2izvlteyy.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gt2vkrhrnzr.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gt2pmjibvfg.html

"7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2ebitbslj.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gt2ifloqrsn.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2qjftfhjw.html

[U114] JS：JSON 深比较
来源：http://dali.chenzaomai.com/Article/details/gt2ebtvmvtd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2dyivrpqm.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2cdzapzhm.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2slqmmeio.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gt2dvhgkfin.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gt2kcrzceoq.html

[U117] JS：单元测试
来源：http://dali.tanke756.top/Article/details/gt2bzomnndh.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gt2clzyidne.html

[U118] JS：开发服务器
来源：http://dali.gaohongyu789.top/Article/details/gt2gvlxdiuy.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gt2llfbppwe.html

[U119] JS：生产构建
来源：http://dali.yvedp.cn/Article/details/gt2gslbtceu.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gt2blccjilz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gt2pskqkitx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gt2fgebfjpd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hcgwhcjx.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gt2ynrxeixi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2cjcwrqai.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gt2shcnsnly.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gt2jckddhsx.html

PHP ............ 252
来源：http://dali.yj20258.top/Article/details/gt2tjoxvcjl.html

JavaScript ..... 252
来源：http://dali.hnxiangtu.top/Article/details/gt2ykelxovx.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gt2vimesqxv.html

Java ........... 212
来源：http://dali.smart0.xyz/Article/details/gt2sadkavrf.html

Go ............. 212
来源：http://dali.birdmap.top/Article/details/gt2jhchndgz.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2mskblbrj.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gt2fjahqexb.html

C .............. 30
来源：http://dali.jiagoushi.top/Article/details/gt2fpqhlwqx.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gt2lzogcuau.html

SQL ............ 90
来源：http://dali.yj20258888.top/Article/details/gt2shbspzca.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gt2atpennlp.html

Kotlin ......... 15
来源：http://dali.xziqi.cn/Article/details/gt2sydewcap.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2bvmiqfsf.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gt2hkrrbvkx.html

Perl ........... 10
来源：http://dali.smart0.xyz/Article/details/gt2blmoknjw.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2malwwyhz.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gt2rltdfibz.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gt2zpjruooa.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gt2zvdnafkc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfchdeds.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttgzokxs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2tguortou.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gt2notkwvwj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yongpay.top/Article/details/gt2dttrytwl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gt2irryvred.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gt2puchhwdu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gt2pkljyzfh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2loulkvls.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2ecovabza.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gt2gtkkgtdv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gt2wtkyguef.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2dwvzhilb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gt2lciztfgj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gt2gfihyhhj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2tpyuvlhx.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gt2zshcdwwc.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gt2relyotpg.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gt2vydyqubq.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gt2djzwhtxa.html

U 高频实用片段                         120
来源：http://dali.yonumen.top/Article/details/gt2tnskaxxh.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxtwerso.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gt2nmgzmgkp.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gt2bageewbl.html

使用提醒
来源：http://dali.jlsjyb.cn/Article/details/gt2puufrqar.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2sfnmcpko.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gt2abdgjcjb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yangfankeji.com/Article/details/gt2ctvtszjy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiwcmfyb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ehwqpu.com/Article/details/gt2orjkqmzi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ehwqpu.com/Article/details/gt2pumivick.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbymlkvh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2fasrskos.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrxrerv.html

Common Programming Examples Cheat Book
来源：http://dali.haohaochexian.top/Article/details/gt2ypcfaxjr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mlkqwfit.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gt2rijpewjg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guowangkeji.top/Article/details/gt2xuphtjfc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccqobrmr.html

SQL · Bash · C · C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2psgvyyzk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gt2hpkomqug.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gt2keoqxoyf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gt2pzvmexqp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuanzx.com/Article/details/gt2ociyxwoe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuanzhike.top/Article/details/gt2hmjmsmbp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgufenzy.top/Article/details/gt2olayfdvs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xinyue.icu/Article/details/gt2cxygvqin.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gt2wwxkowzu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gt2pzbhiilv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daxiang520.top/Article/details/gt2bfmwzdbe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gt2ikdvfrdy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guowangkeji.top/Article/details/gt2cqdxxrws.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aibaodan.cn/Article/details/gt2xofghxet.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gt2xhlmtkjb.html

【文件统计】
来源：http://dali.zycfv.cn/Article/details/gt2ghcyifia.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gt2ypuzqfql.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2lcltqmep.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gt2rtyaifdc.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2utcuchzr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gt2irifskmv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnzwegyh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gt2ephqulfa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gt2tixsgozs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gt2wsbvuenp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2yqlrhywg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjtvqjcd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gt2dbwqklxl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2jtlzghpr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gt2snuwqtxw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gt2vedyphuo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2vqlvkeyz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2yhjcprpk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gt2necessnf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtvwquac.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2wpggwmor.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gt2ndrcpvrg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gt2dzkuzkpv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jyoumei.cn/Article/details/gt2inpwtvfn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2zsvqfoom.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gt2gszfoukd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2sknnxteg.html

A. 基础语法与类型
来源：http://dali.hysaishi.cn/Article/details/gt2cdavulfn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2kzjvyqzh.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wafccuqj.html

Py:   print("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gt2cotxybok.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gt2mjspvutr.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gt2ohpszamt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkkoxvks.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gt2vwddxtqn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gt2wnvnxtmh.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gt2wbyenryf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2qipwweqc.html

[A02] 变量声明与赋值
来源：http://dali.jianghu66.top/Article/details/gt2oymcrpwv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gt2zxuiosfz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2rutchxfh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gt2uxszgynx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywizedxt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gt2giwfxxez.html

Go:   name := "Alex"; age := 20
来源：http://dali.jiagoushi.top/Article/details/gt2qeywvrlw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gt2ujzqvfqd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2qquglhfx.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvvklfrx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.kuanghao11.cn/Article/details/gt2eodflwxs.html

PHP:  const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2ahlxatkb.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2eisorcie.html

TS:   const PI: number = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2homcyjft.html

Java: static final double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2eqhcckxq.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gt2dwlfgvod.html

Ruby: PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gt2isgtpsqq.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbarjabd.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qihbnljt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sysykeji.top/Article/details/gt2jlyixbxe.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gt2nqgmdhus.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2ozrmdwkr.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gt2kgxenich.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjmrcdae.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvaesrxm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gt2gthvlxmz.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gt2vsflgqpm.html

[A05] 整数除法与取模
来源：http://dali.sweek.top/Article/details/gt2hkfyudif.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigufen.top/Article/details/gt2mcazzayr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2uqmbigwo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2naeqdgmu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2siwlreqj.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2zkettvvp.html

Go:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2yizhrlii.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2brgxkpxn.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2nxmyawxb.html

[A06] 字符串转数字
来源：http://dali.xinyue.icu/Article/details/gt2hxbbzngr.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gt2qhmsabhz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjechabl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aizwys.cn/Article/details/gt2dydzbobp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gt2fjtkybqh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gt2yndjotxk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aibaodan.cn/Article/details/gt2jyyodgsc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gt2jefiaebl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2lhybsbby.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gt2cuhnnvin.html

Py:   str(42)
来源：http://dali.cdnleiting.top/Article/details/gt2cknzvasi.html

PHP:  (string) 42; strval(42)
来源：http://dali.bjfxy.top/Article/details/gt2cexgvjzz.html

JS:   String(42); (42).toString()
来源：http://dali.yuanzhike.top/Article/details/gt2isxipnbw.html

TS:   String(42)
来源：http://dali.daria6918.cn/Article/details/gt2ugjdmoeh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2whjtqonw.html

Go:   strconv.Itoa(42)
来源：http://dali.gotoacloud.top/Article/details/gt2atinyokh.html

Ruby: 42.to_s
来源：http://dali.chenjidiqi.icu/Article/details/gt2wstfnopk.html

C#:   42.ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywoeqrom.html

[A08] 取整与四舍五入
来源：http://dali.hnqzz.top/Article/details/gt2foahdobv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2rhvvbnrw.html


<!-- 参考信息 -->