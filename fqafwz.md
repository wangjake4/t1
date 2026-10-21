代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.tanke756.top/Article/details/gtjmjcwxct.html

"值: {$a}"
来源：http://dali.wangdashe.top/Article/details/gtxntcynwi.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gtkaejlpuy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqvavsjcw.html

[U59] PHP：自定义排序
来源：http://dali.xinyue.icu/Article/details/gtwxjidvwq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gteqpyybgr.html

[U60] PHP：JSON 编解码
来源：http://dali.shzxlz.cn/Article/details/gteijzstql.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.smart0.xyz/Article/details/gtfmflonvu.html

[U61] PHP：正则
来源：http://dali.zhixingplan.top/Article/details/gtfbezdcso.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdjkwrqfb.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gtzoasfksm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqnnbvsk.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gttdnmraba.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gtkdmxtgno.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gtzrebgtio.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shuidangran.top/Article/details/gtbnzotusk.html

[U65] PHP：会话
来源：http://dali.ehwqpu.com/Article/details/gtmonlsdbf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtgotjpmvh.html

[U66] PHP：设置 Cookie
来源：http://dali.snrcjt.cn/Article/details/gtweyiezqd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtzkqvmear.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtwfvbylwi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gtquydzxzv.html

[U68] PHP：PDO 连接
来源：http://dali.pengpengdd.cyou/Article/details/gtmugvyhcd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gtoezwewmw.html

[U69] PHP：PDO 预处理
来源：http://dali.chenjidiqi.icu/Article/details/gtemnffrlg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.316326.xyz/Article/details/gtsauktndx.html

[U70] PHP：PDO 事务
来源：http://dali.cashguo.top/Article/details/gtmeuthwsb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gttgpaugem.html

[U71] PHP：抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtrsqhfema.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gtfozecuft.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gtfhwlziwd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gtwafpimdb.html

[U73] PHP：读取 ini 配置
来源：http://dali.tianlin.xyz/Article/details/gtevckptmw.html

parse_ini_file("config.ini", true)
来源：http://dali.guowangkeji.top/Article/details/gtaojfinlt.html

[U74] PHP：读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtgppumvsm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gtkrwozene.html

[U75] PHP：依赖注入
来源：http://dali.sxryk.cn/Article/details/gtyrdslyyc.html

composer require psr/container
来源：http://dali.pengpengdd.cyou/Article/details/gtbnzpguki.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtlgvkwcch.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ybcxt.top/Article/details/gtikzaphjj.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtygtgesjv.html

composer require twig/twig
来源：http://dali.chenzaomai.com/Article/details/gtiyvpusod.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtwtiuisot.html

composer require --dev phpunit/phpunit
来源：http://dali.ppjwa.cn/Article/details/gtofblxtnz.html

[U79] PHP：静态分析
来源：http://dali.ybcxt.top/Article/details/gtkiniaznr.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gtwhewcrif.html

[U80] PHP：代码规范修复
来源：http://dali.cheryme.top/Article/details/gteoaqntzv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtolctlwye.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gtdgwvdtbw.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtndaeywze.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gtgtzepiik.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.9152youxi.cn/Article/details/gtcrzgjgkv.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gtkyzvkcwx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtpvvstbic.html

[U84] JS：CommonJS 写法
来源：http://dali.xinyue.icu/Article/details/gtqydalksc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuanzx.com/Article/details/gtwpaazfre.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtjcwuqthf.html

a?.b?.c
来源：http://dali.cheryme.top/Article/details/gtphaexfdw.html

[U86] JS：空值合并
来源：http://dali.yj202588.top/Article/details/gtoptrwwvt.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gtyasxkilo.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtahhywxra.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtbaxhowxr.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gtmphadbyy.html

{ ...a, ...b }
来源：http://dali.cashguo.top/Article/details/gtjluhbosd.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gtreovfvxo.html

[...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtpcouadcj.html

[U90] JS：数字数组排序
来源：http://dali.ehwqpu.com/Article/details/gtalsbxjhx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtzglooazq.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtlxqbynhn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gtlokaiowa.html

[U92] JS：深拷贝
来源：http://dali.fengsongda.top/Article/details/gthsiyhoof.html

structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtqrfspcud.html

[U93] JS：模板字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtsutmjrrv.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gtywdbzmul.html

[U94] JS：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gtidpqxhfa.html

const double = x => x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrutwpzoj.html

[U95] JS：Promise 包装
来源：http://dali.tanke756.top/Article/details/gtldfnzmrn.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gtrpeozrbx.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gtbwlovidf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtsearidvu.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gtqsuwahjl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtnkmwetmg.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gtqkoaygzw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jyoumei.cn/Article/details/gtmnhdixhc.html

[U99] JS：事件监听
来源：http://dali.shzxlz.cn/Article/details/gtukkboznv.html

el.addEventListener("click", e => {})
来源：http://dali.iojbl.cn/Article/details/gtdhlfxbbl.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gtgiadgkgj.html

document.querySelector(".item")
来源：http://dali.dianchejie.cn/Article/details/gtxmxaxlhx.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gtgvvucmqw.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtywmukjop.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gtbsqvjghj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tanke756.top/Article/details/gtrhxnifwv.html

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkyiewlu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtymdnddsy.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gtwujpoxpy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtputdbobi.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtgzrbczpq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yueranfly.top/Article/details/gtfuikwlgs.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gtikxqnaqa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gtpukvfxzc.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gticugnbrs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pycfn.com/Article/details/gteusgxtwv.html

[U108] JS：随机整数
来源：http://dali.daxiang520.top/Article/details/gtecoqpdkr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gttbzomoct.html

[U109] JS：数组分组
来源：http://dali.daria6918.cn/Article/details/gtsmuezefh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtjvporhlu.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gtbnwiipzf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gtbcbzzral.html

[U111] JS：对象转 Map
来源：http://dali.zhongyouzk.top/Article/details/gtdgkbqxpv.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtedccpblg.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gtdctisipy.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtuwmvfnee.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gtyppeshtz.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gttvqfzclg.html

[U114] JS：JSON 深比较
来源：http://dali.yonumen.top/Article/details/gtbyzipbpo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtvzqitaic.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtldcwkagt.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtluzhgbbp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gtsimhzqkr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdjlryavv.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtcsdfxwua.html

npm i -D vitest;  npx vitest
来源：http://dali.cucudq.cn/Article/details/gtsxxqiqpp.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtviycjysy.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gttduejlfr.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gttsnmdcgs.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gtujbpzvjq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrdweuac.html

import.meta.env.VITE_API_URL
来源：http://dali.ydzc1.top/Article/details/gttrmjshgr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthtympcmf.html

统计汇总
来源：http://dali.zycfv.cn/Article/details/gtnouggedu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttnfwgirm.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gtcvdnetqd.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gtfqwhaeqf.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gtksoyfcch.html

JavaScript ..... 252
来源：http://dali.cucudq.cn/Article/details/gtbzxhnooa.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gteflpzywz.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtuaphwqcp.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtynqlxyxv.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtxfrbsqno.html

C# ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtzvhesmrq.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gtcugsjrzt.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gtgeyeexwv.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtgckbvhiv.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gtydguupvu.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gtbgyyglfk.html

Swift .......... 15
来源：http://dali.zhengqikj.top/Article/details/gtncklhohl.html

Lua ............ 10
来源：http://dali.nwbrower.top/Article/details/gtuqdryzwk.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gtsgsclomt.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyixkrjn.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtpwnlweph.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtuiatobun.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtkfnahqrp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtpfrbbcuz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtmhktybvv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gttgujbjiw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtekycggdk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtvbctlgsd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtzeljpyjh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtoxpkstye.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpyfezmy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtpsnaofwt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gteixghbdi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtvfmjnmto.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtgvivrifm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtuvfwxdot.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtrlirlpxe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtogpacwxt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtcjalqxao.html

Q SQL 专题                              90
来源：http://dali.ehwqpu.com/Article/details/gtotlmodog.html

R Bash 专题                             80
来源：http://dali.yongpay.top/Article/details/gtfjpmetnz.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gtmzumrzwy.html

T 其他语言补充                          60
来源：http://dali.jinqigufen.top/Article/details/gthtzqeute.html

U 高频实用片段                         120
来源：http://dali.cucudq.cn/Article/details/gtztmmkhgi.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtahtfzsug.html

合计                                  2106 条
来源：http://dali.havefunace.top/Article/details/gtjvpkixiq.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtepvwnwjx.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtqlgtdffj.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtzvcmqdco.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ehwqpu.com/Article/details/gtfdlqmdne.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhoulong.xyz/Article/details/gtftfvxfxl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ivvv.top/Article/details/gthuktkomi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenzaomai.com/Article/details/gtjrxjdfou.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gtmqscmtap.html

—— 文件结束 ——
来源：http://dali.andypj.xyz/Article/details/gtwjvqorve.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkzolpylu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtbtwtalat.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtnsytysmh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtscxbllgz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gtnlbfgwrc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gtaubojhiq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gtqhihtrcm.html

SQL · Bash · C · C++
来源：http://dali.guannengcc.top/Article/details/gtnayclywr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gtbhbidjmg.html

【使用说明】
来源：http://dali.redwolf501.top/Article/details/gtdfmnvamf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gtuvbwjdca.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuanzhike.top/Article/details/gtidgbcbjz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cdnleiting.top/Article/details/gtpklqtobd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtedgglpbg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gthamewcro.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gttcllgfut.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shuidangran.top/Article/details/gtshhawtnx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shzxlz.cn/Article/details/gtfouprmnd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenjidiqi.icu/Article/details/gtorxypfpx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtnyjlgmtx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.bjfxy.top/Article/details/gtgqwktnbb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuanzx.com/Article/details/gtqxuuxrrd.html

【文件统计】
来源：http://dali.meibo888.top/Article/details/gtfwnbqpxa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtderfthme.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtpajkthzw.html

目  录
来源：http://dali.nwbrower.top/Article/details/gtetktprry.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtlaznjfwc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gtsaxangjr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gtluzpjstv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtjglrcqsg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtdppadego.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ybcxt.top/Article/details/gttzvaxxkk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtidstywjp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtxnxpwubw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtfjgotxzu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtsvulcejl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtsrwarqgd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gthgqtqjtz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtfwkvsmwh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtawjfbnbu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtrwiibniw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.meibo888.top/Article/details/gthgwxxagc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtixnctkbh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.smart0.xyz/Article/details/gtfriemnuj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtaupqdmkf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fzhhl.top/Article/details/gttsujohbc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtkseecaxt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtcjemlsoq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdaetxuwx.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gtjramdkqs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrkwfserl.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gtfmggbrpf.html

Py:   print("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gtrundrqsf.html

PHP:  echo "Hello, World!";
来源：http://dali.gogol.net.cn/Article/details/gtdmzmqpgr.html

JS:   console.log("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtzdqcdyyx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dianchejie.cn/Article/details/gtlljnlobk.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtyhirysgt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gtoqauzhyn.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gtjzzkjzpr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtgzzhtuxe.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gtnpbaoxtz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tian-w.cn/Article/details/gtyaaqsjfy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nwbrower.top/Article/details/gtismswrqj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtvzbfagzg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtaeemmppk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gttopzgmmw.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtgnvnkzqf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jiagoushi.top/Article/details/gttelslvvo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtsrnnyijr.html

[A03] 常量定义
来源：http://dali.zycfv.cn/Article/details/gtgycspiyj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gtmhzzbxtn.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtchprbgij.html

JS:   const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtkoxysmzl.html

TS:   const PI: number = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtemqwmmqj.html

Java: static final double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtlzmvvzoe.html

Go:   const PI = 3.14159
来源：http://dali.shuidangran.top/Article/details/gtwzmhcwli.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gtgygocyli.html

C#:   const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtscmkheet.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gtezzywdbu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zycfv.cn/Article/details/gttocyftkd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtoyqenola.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtyjefqeix.html

TS:   typeof x; x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtzcenunal.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gtfejhavya.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daria6918.cn/Article/details/gtxkutgwba.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gtdjjcbipw.html

C#:   x.GetType().Name; x is int
来源：http://dali.pycfn.com/Article/details/gtnpozukjd.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gtafhgriar.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.iojbl.cn/Article/details/gtewoayxva.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtsdozeupa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtzpgrfqfp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtcxolujzr.html

Java: 7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtbyzmdgrn.html

Go:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtazddtbpr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtynxukwmm.html

C#:   7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtkikcnidy.html

[A06] 字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyatpeef.html

Py:   int("42"); float("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtssqqfqcc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dianchejie.cn/Article/details/gtvwgflgly.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtpmucnfjz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gtlzfiskng.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtjhguiebz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevqgnbon.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.havefunace.top/Article/details/gtqktzujmp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hfpthk.cn/Article/details/gtjddteemh.html

[A07] 数字转字符串
来源：http://dali.birdmap.top/Article/details/gthgdohpit.html

Py:   str(42)
来源：http://dali.cdnleiting.top/Article/details/gtpeimtiwa.html

PHP:  (string) 42; strval(42)
来源：http://dali.sweek.top/Article/details/gtpnzggdww.html

JS:   String(42); (42).toString()
来源：http://dali.zdqjudy.top/Article/details/gtdegjmvsp.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gttxgoxdps.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258.top/Article/details/gtrpfwcpaf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gtihsvlaup.html

Ruby: 42.to_s
来源：http://dali.smart0.xyz/Article/details/gteqzagvst.html

C#:   42.ToString()
来源：http://dali.jiagoushi.top/Article/details/gtwrnguvfz.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gtpkybqkhb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtweerlzbl.html


<!-- 参考信息 -->