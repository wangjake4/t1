代发 wailian999

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorjjcfjz.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gthigbhpok.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gtzuqpqejm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gtjjiswrdk.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjaanerd.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gtofaplyfs.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gtzpbclxnj.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtefvgqdkp.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gtmxtifftr.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtgdbazsiy.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtrnvgawlj.html

$double = fn($x) => $x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtpdxmngyx.html

[U53] PHP：空合并运算符
来源：http://dali.cheryme.top/Article/details/gtfqgqtkjn.html

$v = $a ?? $b ?? "default";
来源：http://dali.xinyue.icu/Article/details/gtqwnvlzbk.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gtyuffzwlp.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtsipcuuyx.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gtdcutyekm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gthgvsbeoa.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyjomezg.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtegpftklw.html

[U57] PHP：字符串插值
来源：http://dali.yonumen.top/Article/details/gtrjvkjqfn.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtlhuclklr.html

[U58] PHP：数组三件套
来源：http://dali.hongshengwenyu.top/Article/details/gtopnwnaoe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtbpmidvle.html

[U59] PHP：自定义排序
来源：http://dali.hysaishi.cn/Article/details/gtyyyyeijj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtrmvfqvdt.html

[U60] PHP：JSON 编解码
来源：http://dali.yueranfly.top/Article/details/gtwudypiwx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gtsistyhcg.html

[U61] PHP：正则
来源：http://dali.316326.xyz/Article/details/gtaqmikscy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gternxuadu.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtxdcvntuz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guowangkeji.top/Article/details/gtwiepyzdv.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtkqgznfcg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fengsongda.top/Article/details/gtaevxnkjr.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gtfpuknfpo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gtftemzzos.html

[U65] PHP：会话
来源：http://dali.fzhhl.top/Article/details/gtgicmyyog.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gteswcttqz.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtvlmytbji.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gtctruvtlg.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gtdefsnctl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtwnfrobos.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258.top/Article/details/gtwmxcqmdu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gtabgmnahr.html

[U69] PHP：PDO 预处理
来源：http://dali.vqdsnc.cn/Article/details/gtyrvscfwy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtmuqlrlro.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtwqsrrqig.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtcxjqixyn.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gtdyozague.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gttiiaeuyq.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gtxkhdadck.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtjbxbmogz.html

[U73] PHP：读取 ini 配置
来源：http://dali.jlsjyb.cn/Article/details/gtapktwblz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gtcbczjdxg.html

[U74] PHP：读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtlwxtykxn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigufen.top/Article/details/gtydiyhfpe.html

[U75] PHP：依赖注入
来源：http://dali.jinqigufen.top/Article/details/gtnduxdnly.html

composer require psr/container
来源：http://dali.pycfn.com/Article/details/gtuvqbxmom.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gttxsizani.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuanzhike.top/Article/details/gtgktvvphg.html

[U77] PHP：模板渲染
来源：http://dali.yueranfly.top/Article/details/gtevoqacgw.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gtxuhsxsqo.html

[U78] PHP：单元测试
来源：http://dali.jiagoushi.top/Article/details/gtmejegvuf.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gtzmesqmex.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavyrsczp.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gtbaqohuky.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gtrcupqijj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtbguhdqly.html

[U81] JS：初始化项目
来源：http://dali.svipenyu.cn/Article/details/gtxvvpiilr.html

npm init -y;  npm i express
来源：http://dali.ppjwa.cn/Article/details/gtgxnlcygd.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gtiwtsuagm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gtzryrfcsk.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gtayxomjln.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtkrlonzac.html

[U84] JS：CommonJS 写法
来源：http://dali.jlsjyb.cn/Article/details/gtnzhqupkd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gtyyltqoct.html

[U85] JS：可选链
来源：http://dali.snrcjt.cn/Article/details/gtsfmkmabg.html

a?.b?.c
来源：http://dali.redwolf501.top/Article/details/gtdgmgieul.html

[U86] JS：空值合并
来源：http://dali.yongpay.top/Article/details/gtrycwqbgb.html

a ?? b
来源：http://dali.yj20258888.top/Article/details/gtolkieqtn.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gtuaxpsrte.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gtkbmjbntz.html

[U88] JS：对象展开合并
来源：http://dali.dianchejie.cn/Article/details/gthsgpiyym.html

{ ...a, ...b }
来源：http://dali.c1oappe.top/Article/details/gtyulceuay.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxrmxuyz.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtnckoeygp.html

[U90] JS：数字数组排序
来源：http://dali.cashguo.top/Article/details/gtogkzpcmq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtqihkaemu.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gttbcbesjk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtvthbuyvu.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gteaxooaqk.html

structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtdsvailnr.html

[U93] JS：模板字符串
来源：http://dali.fzhhl.top/Article/details/gtddhinaae.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gtszvibbsu.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtldppwoye.html

const double = x => x * 2;
来源：http://dali.ybcxt.top/Article/details/gtwkigvojv.html

[U95] JS：Promise 包装
来源：http://dali.cheryme.top/Article/details/gtbcgqfile.html

new Promise((resolve, reject) => {})
来源：http://dali.sweek.top/Article/details/gtxhbggwkg.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gthhbywluv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtrknkmetv.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtziyhodwf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtdxzyzhbr.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gttjhbxmov.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gtdivkgtum.html

[U99] JS：事件监听
来源：http://dali.zhiwuduotai.top/Article/details/gtncdzgcmi.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtpzxfzzev.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gtbtxrmyvb.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gtypwzdgsw.html

[U101] JS：classList 操作
来源：http://dali.yuxming.cn/Article/details/gtsgigtrwc.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gtzlmfsgbf.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtrdrokwfk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtcujvvzui.html

[U103] JS：定时器
来源：http://dali.snrcjt.cn/Article/details/gtdjdeaodr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tianlin.xyz/Article/details/gtgtwkrqry.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gtzpdsklti.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtjcsfdluo.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gtpyncjpko.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aibaodan.cn/Article/details/gtcylfgyzc.html

[U106] JS：日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtxgcuctzd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtfucrfrbw.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtpqgysxox.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtdapjuhjy.html

[U108] JS：随机整数
来源：http://dali.c1oappe.top/Article/details/gtcccadlkr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gthoslnvvx.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtawzgraul.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvsdrdtl.html

[U110] JS：数组分块
来源：http://dali.cashguo.top/Article/details/gtpjrxqwtb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtrcpenprc.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gthaalhsxa.html

new Map(Object.entries(obj))
来源：http://dali.nanxinkj.top/Article/details/gtcdrmgpob.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gtbnxquvuf.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtymdpbbmr.html

[U113] JS：正则替换全部
来源：http://dali.smart0.xyz/Article/details/gtofdwudyz.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtgyhonthv.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gtoiyeltrw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtypfxdxkq.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtdseifcbq.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtgixsrzvu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gtxbbrcfwb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtlothowms.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtqwqndzgg.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtbdkpeloe.html

[U118] JS：开发服务器
来源：http://dali.tianlin.xyz/Article/details/gtzlyzdpii.html

npm i -D vite;  npx vite
来源：http://dali.yueranfly.top/Article/details/gtuelihghw.html

[U119] JS：生产构建
来源：http://dali.xuetiantiany.cn/Article/details/gtwptdgarz.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtyoiddsoq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gthjjbguvv.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtprnlbyzg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttouwadiw.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gtcgapyqzn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttlogelit.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gtsurtvckg.html

Python ......... 252
来源：http://dali.daxiang520.top/Article/details/gtkjbzfvhb.html

PHP ............ 252
来源：http://dali.cqqwz.cn/Article/details/gtgdcxoecm.html

JavaScript ..... 252
来源：http://dali.quarkkingdee.top/Article/details/gtjwtdrvho.html

TypeScript ..... 212
来源：http://dali.jinqigfzy.top/Article/details/gtzhmvselk.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gturigmrlk.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtmodfywrn.html

Ruby ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtqiaucetb.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtohaxxfdp.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gthgrgkslh.html

C++ ............ 30
来源：http://dali.meibo888.top/Article/details/gtrxgiocrd.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gtsgprznze.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gtwmciuryn.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gttxqflmql.html

Swift .......... 15
来源：http://dali.gotoacloud.top/Article/details/gtlnutemjm.html

Lua ............ 10
来源：http://dali.tianlin.xyz/Article/details/gtvweembiv.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gtrpwowqrj.html

Scala .......... 10
来源：http://dali.xylfe.cn/Article/details/gtzwbuapsg.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtaplmssdq.html

合计 ........... 2106 条
来源：http://dali.tianlin.xyz/Article/details/gtwkqtrmnn.html

按章节统计：
来源：http://dali.ivvv.top/Article/details/gtatcivrhm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtarpdqeyn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtftaiwkzs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtweakmpfp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gtyvhqmkcj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jianghu66.top/Article/details/gtmsxouplu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtaanuzwwy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtdatkwcyb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtgqgrlpev.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzjfsqwz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrcurfmy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtxxrsurpa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtzddjlbju.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtnnjqtlms.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtqfkeftjq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shzxlz.cn/Article/details/gtwrvvdipf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtmfnlpcun.html

Q SQL 专题                              90
来源：http://dali.aizwys.cn/Article/details/gtkczaywqo.html

R Bash 专题                             80
来源：http://dali.shangyingyoupin.top/Article/details/gtdnwotdwb.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gtqbglhnyl.html

T 其他语言补充                          60
来源：http://dali.gogol.net.cn/Article/details/gtsochlugc.html

U 高频实用片段                         120
来源：http://dali.cashguo.top/Article/details/gtnanknqoa.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtwgealpjd.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gtxcvwyenb.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtjygfcasf.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gtbnenqdnp.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtgozefmvc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shuidangran.top/Article/details/gtnvuxbcqo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxuqtvzb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.feifeiyinyue.top/Article/details/gteqnttcia.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtooibirgk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cqqwz.cn/Article/details/gtibkozvxa.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtmcnotlkk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjniulqir.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sweek.top/Article/details/gtxyqzmutc.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gturadrsyo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteyqpaban.html

【收录内容】
来源：http://dali.jinyuanbaomall.cn/Article/details/gttehcdizr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gtwhwlwssf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gtfftcvpoz.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gtqihhlwja.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gtgxwbzyda.html

【使用说明】
来源：http://dali.quarkkingdee.top/Article/details/gtosdhlavt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gtdapzprzb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yanxiufei.cn/Article/details/gtmmdbhnky.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangdashe.top/Article/details/gtrztngrkm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gtzifdipll.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aibaodan.cn/Article/details/gtgdnnahal.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shzxlz.cn/Article/details/gtryowftxx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gtsdkgmpyl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.andypj.xyz/Article/details/gtjcfcqtkx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cqqwz.cn/Article/details/gtaesqxyhb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuetiantiany.cn/Article/details/gtcanvculk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktudltbe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yongpay.top/Article/details/gtfolxmvhq.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtvazqlqqe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cdnleiting.top/Article/details/gtbdozmrse.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtclmgazov.html

目  录
来源：http://dali.ppjwa.cn/Article/details/gtbrxynsfc.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptllmxkv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gthdidasvh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtizagajpj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtyxwynwog.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.9152youxi.cn/Article/details/gtcuhtznad.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gttudtznwz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gttfspelch.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbwppcho.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtlbmvsnvt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtntquqjaf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gteygbzeek.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtrqitteud.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbnjhuoi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtywpovlgb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gtitcqbnmi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aizwys.cn/Article/details/gtgklcbrlo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsairlent.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.birdmap.top/Article/details/gtfuidwevt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zdqjudy.top/Article/details/gtywzjhbgw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gtohvjccfl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtjtwgdcvn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtqgsffjuy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkooksjyx.html

A. 基础语法与类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvkjtfiw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthtmjecxc.html

[A01] Hello World
来源：http://dali.shuidangran.top/Article/details/gtfvzwvqsj.html

Py:   print("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtafyotsyj.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gtjaaineuw.html

JS:   console.log("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gthnxcohwe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gtzkumbsmg.html

Java: System.out.println("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtmmwbdryy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtrkfiamdv.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gtxugyaxqs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtclgnmgai.html

[A02] 变量声明与赋值
来源：http://dali.0kj1m.cn/Article/details/gtlyndzios.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtrhqrqkij.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtlmsxavyp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtghpwsfax.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dianchejie.cn/Article/details/gtgsjjeufl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtqpanhdrg.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangdashe.top/Article/details/gthxlcmbjy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzadqwgh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtgrukccyv.html

[A03] 常量定义
来源：http://dali.yongpay.top/Article/details/gtyjdovonj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenzaomai.com/Article/details/gtizzzypgd.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzryoeeqk.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtjphpbgay.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtcyishjpx.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfevuywhp.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gtmmsiopoy.html

Ruby: PI = 3.14159
来源：http://dali.xuanzx.com/Article/details/gteuopymbs.html

C#:   const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtiulsmjtf.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gtioqpjzwh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gteingjlil.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jianghu66.top/Article/details/gtxbbukijs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtfvmtevup.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gtnmcscxwc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daria6918.cn/Article/details/gtbtkzfafb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gttzdtdcnp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gtmrjxevfx.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gtpktgnnnh.html

[A05] 整数除法与取模
来源：http://dali.hongshengwenyu.top/Article/details/gtzjvmisga.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tianlin.xyz/Article/details/gtonqrcvwd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtzqvtempx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtpyydmyay.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gttvstzpgn.html

Java: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtypcvsprd.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtosakhlcx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtcykytedx.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtohmrnmlr.html


<!-- 参考信息 -->