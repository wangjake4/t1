代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gtcrgjnkfk.html

$v = $a ?? $b ?? "default";
来源：http://dali.jlsjyb.cn/Article/details/gtlpymlqgy.html

[U54] PHP：空安全调用
来源：http://dali.ppjwa.cn/Article/details/gtnbjztymx.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gtifrskbps.html

[U55] PHP：match 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtjhevbqmq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtimtgtzlk.html

[U56] PHP：命名参数
来源：http://dali.snrcjt.cn/Article/details/gtjheazula.html

f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmsrrddcp.html

[U57] PHP：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtkfonxdpz.html

"值: {$a}"
来源：http://dali.cashguo.top/Article/details/gtrmzqpuui.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gtlmbaiqmu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gtkjuruxgv.html

[U59] PHP：自定义排序
来源：http://dali.shangyingyoupin.top/Article/details/gturtkrrhu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvtpvnqz.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gtpcgomvba.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tanke756.top/Article/details/gtwquufeey.html

[U61] PHP：正则
来源：http://dali.kuanghao11.cn/Article/details/gtfmjngexw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gttvchbqfm.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqmfofwx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnqzz.top/Article/details/gtuodttznx.html

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gtpigdfkdc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sweek.top/Article/details/gtxkzhyjro.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtxsuuheeb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shuidangran.top/Article/details/gtzgaxfwjh.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gtoqmkokps.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtmfnparrt.html

[U66] PHP：设置 Cookie
来源：http://dali.pengpengdd.cyou/Article/details/gtlrnxkdcz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtxlidqcqj.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gtjspbbayx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxuanxn.top/Article/details/gtlrwabrdr.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gtntamnrok.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvujitdfz.html

[U69] PHP：PDO 预处理
来源：http://dali.yanxiufei.cn/Article/details/gtofficaqy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gtlluvkzoa.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gtkqaljotl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtajatzpme.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gtsjuyozuh.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtnmvyflya.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtefvxxcem.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gtkmnkyohd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gtkjenuxrr.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gtsaquhkkd.html

[U74] PHP：读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtascbfaod.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pycfn.com/Article/details/gtfypslrjn.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gtddulwaed.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtpfpfymlm.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gtbrwseqnq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gtxcyadtbp.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gtufjahqrk.html

composer require twig/twig
来源：http://dali.xylfe.cn/Article/details/gthaewsghj.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtltuzxzmn.html

composer require --dev phpunit/phpunit
来源：http://dali.xziqi.cn/Article/details/gtbvbyjzjg.html

[U79] PHP：静态分析
来源：http://dali.xziqi.cn/Article/details/gtttegbttl.html

composer require --dev phpstan/phpstan
来源：http://dali.ydzc1.top/Article/details/gtcqthpzsj.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gtdaznobmo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenlongwang.top/Article/details/gtfzbzryur.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gtwrzcuunq.html

npm init -y;  npm i express
来源：http://dali.fengsongda.top/Article/details/gtgfbqfbnr.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gthpozwqfw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtgirpwdls.html

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gtzseejzcb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtqgymmztj.html

[U84] JS：CommonJS 写法
来源：http://dali.chenzaomai.com/Article/details/gtbyufaakl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtswocogzd.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gtnqypeeua.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gtyadtnati.html

[U86] JS：空值合并
来源：http://dali.hfpthk.cn/Article/details/gtkrvsoums.html

a ?? b
来源：http://dali.iojbl.cn/Article/details/gtxxzlstsi.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtgtabfibd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zdqjudy.top/Article/details/gtndmuupwe.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gtfrgdztsv.html

{ ...a, ...b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhuicfaj.html

[U89] JS：数组去重
来源：http://dali.zhiwuduotai.top/Article/details/gtqsaahzaq.html

[...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtrzxdycbi.html

[U90] JS：数字数组排序
来源：http://dali.sweek.top/Article/details/gtxzpsqptu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtrtcwrjgv.html

[U91] JS：对象键值遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhfcenwb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gtrsyituga.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gthvekigfw.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtvdzdxiqk.html

[U93] JS：模板字符串
来源：http://dali.pengpengdd.cyou/Article/details/gttauqcoww.html

`共 ${n} 条`
来源：http://dali.cashguo.top/Article/details/gtfwvnmraa.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtwoysuada.html

const double = x => x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gtywgckcgv.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtuyjfyotu.html

new Promise((resolve, reject) => {})
来源：http://dali.yongpay.top/Article/details/gtdjvnyyvq.html

[U96] JS：async/await 与异常
来源：http://dali.xinyue.icu/Article/details/gtlmluqkdz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiffself.html

[U97] JS：并发请求
来源：http://dali.ehwqpu.com/Article/details/gtjeigveef.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtkxfjkihz.html

[U98] JS：fetch 带 JSON
来源：http://dali.hammf.cn/Article/details/gttelcwagp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzaymlgb.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtptipohez.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvhiwzhp.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gtpbdvyfzg.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gtvrrvdydp.html

[U101] JS：classList 操作
来源：http://dali.redwolf501.top/Article/details/gtuywbmiuu.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gtkszpgdzm.html

[U102] JS：本地存储
来源：http://dali.chenjidiqi.icu/Article/details/gtmnaampxc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gtltrvwmlm.html

[U103] JS：定时器
来源：http://dali.snrcjt.cn/Article/details/gtrdmdurnr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gtnzqbhxwa.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqewmfyrm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtgpzqzrvj.html

[U105] JS：节流
来源：http://dali.havefunace.top/Article/details/gtrzeizuyz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhixingplan.top/Article/details/gtnnympvwr.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtrhdmcssj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtlvdimmpe.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gtnkqnldac.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtfyowirps.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtczpwxciq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gthncvsfix.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gthbenplqx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtcdndksvd.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gtmlklcwaq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgufenzy.top/Article/details/gtyloswufk.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtmwvewkht.html

new Map(Object.entries(obj))
来源：http://dali.guannengcc.top/Article/details/gtxgchlbsp.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gteamjcrrw.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavxwwinn.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gtbxufxwig.html

s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtwrrlbkue.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gtudrhnomw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtyvqooqwg.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gtyqzatctu.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtvjchuszh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigufen.top/Article/details/gtpmhdrcnk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tianlin.xyz/Article/details/gteuxdgiis.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gtaihewsft.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gtqtwkomdm.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gtwtbrovvj.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtllpkpcxn.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtlpvtjaxr.html

npx vite build
来源：http://dali.c1oappe.top/Article/details/gtkzcrctjq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.snrcjt.cn/Article/details/gtpoucdrek.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gtodyoltmk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgcqdtoaq.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilxmvdtu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyxorsnrb.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gtsitwxcmx.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gtogniquxr.html

PHP ............ 252
来源：http://dali.nwbrower.top/Article/details/gtvlghydnh.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gtsljcsomd.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gtwwstpupp.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gtocxhfkrg.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtgpclnydx.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gtqsnbftns.html

C# ............. 212
来源：http://dali.ydzc1.top/Article/details/gtqvkrugcn.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gtdlukboim.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtzvesluff.html

SQL ............ 90
来源：http://dali.havefunace.top/Article/details/gtnfnibbpp.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gtvtkogqwi.html

Kotlin ......... 15
来源：http://dali.hammf.cn/Article/details/gtslrlishx.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtvbwtfcpi.html

Lua ............ 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoomvrun.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtgmohamlm.html

Scala .......... 10
来源：http://dali.cucudq.cn/Article/details/gturuhssmi.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtxuizkobd.html

合计 ........... 2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtcztqrkim.html

按章节统计：
来源：http://dali.xziqi.cn/Article/details/gtsnakcwxo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtdsqbekvv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtnccupbbk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtyjyxziwo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtlecpwlbk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gtcmvfakvg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtznhtibsz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtofdteidd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtibcfskjw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtbiiuiadk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gtztvhmooi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtlduefwil.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtkgunhnsr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtwydhzplh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtofkyxmju.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gtcotugssz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtriibqfvf.html

Q SQL 专题                              90
来源：http://dali.jinqigufen.top/Article/details/gtwslluuvs.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gtmdijnjpl.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrajqewl.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gtkwpkeygd.html

U 高频实用片段                         120
来源：http://dali.sxryk.cn/Article/details/gtyyhobvcr.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtpfxbwyeq.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gtqutdqjej.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqwgktzz.html

使用提醒
来源：http://dali.9152youxi.cn/Article/details/gtiduqrxrs.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtzufvzobq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gtellvwtvo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gzhubu.top/Article/details/gtzgyvmxhr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gtclbzovil.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shangyingyoupin.top/Article/details/gtyzuypzlj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gtspqtvlmu.html

—— 文件结束 ——
来源：http://dali.wangshuangyany.cn/Article/details/gtipilvpil.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttleegqdf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pycfn.com/Article/details/gtswgfeugm.html

Common Programming Examples Cheat Book
来源：http://dali.jlsjyb.cn/Article/details/gtoiaiamll.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfvxqkgur.html

【收录内容】
来源：http://dali.ivvv.top/Article/details/gtjukhjymh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nwbrower.top/Article/details/gtagmldcxo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gthqawzyir.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gtqfeahbup.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jqgfzy.top/Article/details/gtckpkxmtz.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtdumyritn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jlsjyb.cn/Article/details/gtskyhsuqt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj202588.top/Article/details/gtioatgupv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtootecmik.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dashuyun.cn/Article/details/gtfaiwpwnw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cashguo.top/Article/details/gtsqpdkvxx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gtsyjlernk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hywenlv.cn/Article/details/gtdktynmku.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yanxiufei.cn/Article/details/gtjzumlsat.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gtwzcqtovx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtutgmkg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ydzc1.top/Article/details/gtazqodsas.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yangfankeji.com/Article/details/gtpigexnpy.html

【文件统计】
来源：http://dali.meibo888.top/Article/details/gttsnuynja.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gtptlbviqw.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtxhmcdrgq.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gtyzyrmciv.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngbvrgpu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gtqdukefxi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gttfjsyswc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtqttavblu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gteapkyfag.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gtqlgevbky.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gttrlrfocr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudrfshdc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtqzskukin.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtfwkbuxnm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtbtgdtfjk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtgptwvmym.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gteyfdijbj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtmkikouhl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtanelzlmj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcadrzabl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtamarhwis.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jyoumei.cn/Article/details/gtnlrfqmzc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtjxxlbzvm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hywenlv.cn/Article/details/gtdjkpesmc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtoeadxhtn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtttubxtje.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkrvnqjex.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gtywkqafqc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmwqsxymv.html

[A01] Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtytzctttw.html

Py:   print("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtapaqdkph.html

PHP:  echo "Hello, World!";
来源：http://dali.haohaochexian.top/Article/details/gthwptgdlb.html

JS:   console.log("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtvylhrequ.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gtxlskgxpv.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtpwsehspz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtrqwighxe.html

Ruby: puts "Hello, World!"
来源：http://dali.316326.xyz/Article/details/gtdbpyvzzx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtcaudtqeb.html

[A02] 变量声明与赋值
来源：http://dali.guannengcc.top/Article/details/gtaxeierql.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnqzz.top/Article/details/gtxqkgbtiu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtmptndala.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtpsiusebr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtqwydfwhq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtbekkrkek.html

Go:   name := "Alex"; age := 20
来源：http://dali.xziqi.cn/Article/details/gtfpuhsonm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pengpengdd.cyou/Article/details/gtkfboiyvk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtzqzqbojq.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gtzgwzyayv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigufen.top/Article/details/gtzocuptnv.html

PHP:  const PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtverhzmtx.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtzuuwvmfj.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtitjlovcs.html

Java: static final double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtojiedzdy.html

Go:   const PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtshkwjezs.html

Ruby: PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gthxrzzado.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gturptfmgr.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhqkpqvp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gaohongyu789.top/Article/details/gtfmguxymy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.iojbl.cn/Article/details/gtzpckfbvv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.meibo888.top/Article/details/gtlmqtyqsf.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtvcqkbbuw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhoulong.xyz/Article/details/gteulktuwh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhoulong.xyz/Article/details/gtsidtouvf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.vqdsnc.cn/Article/details/gtacoewhiu.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gtkcakmmrk.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gtlctfiifd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuetiantiany.cn/Article/details/gtyzloecla.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gthwgnygkc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtywwfkfjz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtvjynfvot.html

Java: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtdwkgeaql.html

Go:   7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtcmmbdawi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtsfrvzzwa.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtpsvizeqt.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gtxyzmybbk.html

Py:   int("42"); float("3.14")
来源：http://dali.yonumen.top/Article/details/gtcaqztpsi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gthdjiqqla.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cheryme.top/Article/details/gtutlnlzra.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtwchwtcfk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtunwnyvwy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jyoumei.cn/Article/details/gtvhhgxbyz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gtvgfwlcap.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtfwrutdht.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gtxmrcwlin.html

Py:   str(42)
来源：http://dali.guowangkeji.top/Article/details/gtqlqugdra.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gtptroivov.html


<!-- 参考信息 -->