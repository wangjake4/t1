代发 wailian999

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gtcfyoixbt.html

int|string $id
来源：http://dali.jlsjyb.cn/Article/details/gtzeeowjxd.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtheuszvgl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gtjbfbzqyj.html

[U49] PHP：只读属性
来源：http://dali.sxryk.cn/Article/details/gtthfvbdhu.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gtvivnszza.html

[U50] PHP：构造器属性提升
来源：http://dali.guannengcc.top/Article/details/gtalyhxatv.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gtsreqgvvb.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqssrxnl.html

[$a, $b] = $arr;
来源：http://dali.cheryme.top/Article/details/gtsccxjklw.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtamutvqjk.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gtipjvlyrp.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlixyussf.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gtghhaqaao.html

[U54] PHP：空安全调用
来源：http://dali.hnqzz.top/Article/details/gtkjirykuy.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gtljslfhqk.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtbnzphtrr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gttsljcutl.html

[U56] PHP：命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtvfvsvkwh.html

f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtabmhvlip.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtveewzngn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gtxqokkubr.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gtcpapjjss.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gtudqezbec.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gtsnvowtht.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtxoivlpvy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gtdzcdzaqb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtxoxpsqik.html

[U61] PHP：正则
来源：http://dali.bjfxy.top/Article/details/gtvcjmulza.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtexwqwxey.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gtwnbfaagv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtkyuzjcfs.html

[U63] PHP：文件读写
来源：http://dali.pycfn.com/Article/details/gtvjbkuroe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.bjfxy.top/Article/details/gtqstijgmb.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gttpxlfvvk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtnvicilut.html

[U65] PHP：会话
来源：http://dali.sxryk.cn/Article/details/gtvidszhav.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtwvxtyfgg.html

[U66] PHP：设置 Cookie
来源：http://dali.yongpay.top/Article/details/gtwypfvgfu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtrbzkvmew.html

[U67] PHP：处理文件上传
来源：http://dali.daxiang520.top/Article/details/gtxtcdjykw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenjidiqi.icu/Article/details/gtwohxibsj.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtnynhuocm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gtfpfpfflv.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gtbzhimedc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiihbeuo.html

[U70] PHP：PDO 事务
来源：http://dali.kuanghao11.cn/Article/details/gtkfcemksx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xziqi.cn/Article/details/gtrscynliy.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gtddtgyenr.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gtentwitek.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gticsyuuue.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gtqxmznyub.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gtuywgfajs.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtfvwhyakf.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gttjqrhamy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ehwqpu.com/Article/details/gtzsekpknu.html

[U75] PHP：依赖注入
来源：http://dali.hywenlv.cn/Article/details/gtpfjdwlce.html

composer require psr/container
来源：http://dali.ppjwa.cn/Article/details/gtfemopqpr.html

[U76] PHP：简单路由
来源：http://dali.yueranfly.top/Article/details/gtobtwsvjw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.vqdsnc.cn/Article/details/gtjlkdnxds.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gtrqtgdcsg.html

composer require twig/twig
来源：http://dali.xuetiantiany.cn/Article/details/gtcygukitt.html

[U78] PHP：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtiwlrckvj.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtvkhucegi.html

[U79] PHP：静态分析
来源：http://dali.chenlongwang.top/Article/details/gtfmzpsmye.html

composer require --dev phpstan/phpstan
来源：http://dali.xinyue.icu/Article/details/gtiptjvyfs.html

[U80] PHP：代码规范修复
来源：http://dali.nanxinkj.top/Article/details/gtwagyikhf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ppjwa.cn/Article/details/gtktwahctt.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gtpuajzukv.html

npm init -y;  npm i express
来源：http://dali.yanxiufei.cn/Article/details/gtdcxqbuwf.html

[U82] JS：package.json 脚本
来源：http://dali.hammf.cn/Article/details/gtwnzphpfl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gttbfaigkx.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gtekyeqwzp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtphhpvppf.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gtfbutpuvf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zdqjudy.top/Article/details/gttfqhybfk.html

[U85] JS：可选链
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlhmrmap.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdstaqxt.html

[U86] JS：空值合并
来源：http://dali.hongshengwenyu.top/Article/details/gtzagrgfhy.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gtkrbxfbxm.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gtirulzhgn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gtlldtxtlf.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtkrcupq.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gtlgofluhc.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gtzvbcyqzw.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtynprqrix.html

[U90] JS：数字数组排序
来源：http://dali.yueranfly.top/Article/details/gtolwgbwri.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtybuksybo.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gtunlkgara.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gtlheoemcu.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtvxsmdehv.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtxdngawvm.html

[U93] JS：模板字符串
来源：http://dali.ybcxt.top/Article/details/gtwfoprqhu.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gtdpepeygm.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtyfuytvdp.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxsgwczt.html

[U95] JS：Promise 包装
来源：http://dali.jinqigufen.top/Article/details/gtixzaaqkw.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtbblidgyw.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtivsetqqi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtpqjewfsz.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gtmmlogclo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtyjppclfl.html

[U98] JS：fetch 带 JSON
来源：http://dali.hywenlv.cn/Article/details/gtzkuectfo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtkkuaadmz.html

[U99] JS：事件监听
来源：http://dali.nwbrower.top/Article/details/gtfjdiqjej.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gtwtsrdxvj.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gthnbjobpl.html

document.querySelector(".item")
来源：http://dali.aibaodan.cn/Article/details/gtwbagfdye.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gtgfrckjzd.html

el.classList.toggle("active")
来源：http://dali.gotoacloud.top/Article/details/gtwctrwgyx.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gtplsxqzzp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhiwuduotai.top/Article/details/gtsynscott.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gtdgnfckhn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtdbfkgtaf.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtyzruxdrz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtaoiphyiy.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gtpvrihnjj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sufxvd.cn/Article/details/gtvuapmqop.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtxdyylgei.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxinkj.top/Article/details/gtslwejrzi.html

[U107] JS：数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtnzodevvr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtaddtdhlj.html

[U108] JS：随机整数
来源：http://dali.yuanzhike.top/Article/details/gtawunkiuc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtakipokmd.html

[U109] JS：数组分组
来源：http://dali.gaohongyu789.top/Article/details/gtfbqcnfzc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtqqqacxpm.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gtvleogllr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gttjrpwluu.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gteznmjgvf.html

new Map(Object.entries(obj))
来源：http://dali.smart0.xyz/Article/details/gtwbvbaxnf.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtnrvmsjqv.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtrfnmctrq.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtosmdoldm.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteowkonby.html

[U114] JS：JSON 深比较
来源：http://dali.iojbl.cn/Article/details/gteojmtvbc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtyjovhyqe.html

[U115] JS：生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtlalkzcmz.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtjbvxowrw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gtzcmrmesd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gtjanjuwns.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtsilwgccl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxzubmme.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gtfypihjld.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtqgeixpxv.html

[U119] JS：生产构建
来源：http://dali.shangyingyoupin.top/Article/details/gtiugcizyn.html

npx vite build
来源：http://dali.xziqi.cn/Article/details/gthrbiphhf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gtbgqkdxpv.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gtihidiecp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmgpxqdvt.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gtkvoinyng.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwlbjaujd.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gtibxbzwfd.html

Python ......... 252
来源：http://dali.wangdashe.top/Article/details/gtncahfiyg.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gtprykbnew.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtgflobugw.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gtffgfmsxs.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtpzjpscpc.html

Go ............. 212
来源：http://dali.0kj1m.cn/Article/details/gttkpijtwa.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtrthikzpw.html

C# ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqboohpu.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gtycbdxzjs.html

C++ ............ 30
来源：http://dali.kuanghao11.cn/Article/details/gtcfoofida.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtkhrigvot.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gthcabkgcy.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gtuvansopk.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtzferxvze.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gthgptnebx.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gtstgmrlua.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gtpyekraff.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtcryiwtnt.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gtmzygofjs.html

按章节统计：
来源：http://dali.yuxming.cn/Article/details/gturdgfxrm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gtcfvyqtpl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtsmgjqtwc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtwmtrnosf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gttuqdesrt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.andypj.xyz/Article/details/gtimkrvehb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gtivgoqaye.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtbtvtzzhb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtfkhypbqg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtcvozfogb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtqjekieeo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtkzmnxjdt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtwunizzcg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtonifgzhi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtrxdsvsch.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtsxaqlmza.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gttcjcrkit.html

Q SQL 专题                              90
来源：http://dali.jlsjyb.cn/Article/details/gtvjvjguwk.html

R Bash 专题                             80
来源：http://dali.zhixingplan.top/Article/details/gtcbdafzfg.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtsbodxblr.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gtevqrrvda.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gtnlqmkkpj.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtqmgawdrc.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gthzhwkuic.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtpwdnciee.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gtzlwpejiw.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtnelofrdh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gtwtxxgwtu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pycfn.com/Article/details/gtqkaonvnm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gtnmfmvtos.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gzhubu.top/Article/details/gtryxcclpq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtixnarseh.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gtpngkuyai.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtloiyzkhu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hammf.cn/Article/details/gtqrgtiymi.html

Common Programming Examples Cheat Book
来源：http://dali.aibaodan.cn/Article/details/gtahxddjyf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkkrinwoy.html

【收录内容】
来源：http://dali.sxryk.cn/Article/details/gtfzxlywhc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gtdsnbcsrb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtjyjxxohd.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gtgfyaiirv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gtxfnelvaf.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gtvvfmmwtx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gtoqzljzry.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xylfe.cn/Article/details/gtobsybmrp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ivvv.top/Article/details/gtoxmzfije.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sweek.top/Article/details/gtgprmlmuw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zdqjudy.top/Article/details/gtzhgbhrex.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ivvv.top/Article/details/gtbfnszgkv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtwomqdsfe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxinkj.top/Article/details/gtlqqgbmko.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gtuzvhprsq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jianghu66.top/Article/details/gtvehdwwzi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ivvv.top/Article/details/gtaxyleznt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nanxinkj.top/Article/details/gtqnrwzqpj.html

【文件统计】
来源：http://dali.chenlongwang.top/Article/details/gtmvogkklu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenjidiqi.icu/Article/details/gtlusjzusd.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtsokrdfxc.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtmqtgdcxh.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtjjhooukv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtdwqbqxiz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gthnfirkjq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtaanbbyzm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtduuxilgx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtzwyjgnsm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtvbypmbec.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtvotzwoqj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gtxqqyhwit.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtwbaeywly.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtricttikd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtjlgdhatw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqsyxxta.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvcncxbo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.0kj1m.cn/Article/details/gtuifgniqp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gtvsctagex.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtdpwxkdvq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigufen.top/Article/details/gtvnsptolb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbohwbagm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtzhfgxavw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtbpjkkbym.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtdvgvtnrk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttdruzbst.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtdxfyxazx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnfovbrmq.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gtmdzblysl.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaktgzfnz.html

PHP:  echo "Hello, World!";
来源：http://dali.yangfankeji.com/Article/details/gtdsgmzled.html

JS:   console.log("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtdwuskwwp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtonsohibw.html

Java: System.out.println("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gtlkaxrsda.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gteucibaxq.html

Ruby: puts "Hello, World!"
来源：http://dali.hnqzz.top/Article/details/gtmbmdxzfy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtwyskhilp.html

[A02] 变量声明与赋值
来源：http://dali.ppjwa.cn/Article/details/gtqelzxqms.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtxmnxdnoh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtrrdskspx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtvvpsknku.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhengqikj.top/Article/details/gtjofrczws.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtvqqmkqci.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gtfvxksivn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gttdbkvypf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gthnwgqvji.html

[A03] 常量定义
来源：http://dali.yueranfly.top/Article/details/gtgpsditsf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fengsongda.top/Article/details/gtnqipseoh.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtrmfgdsvx.html

JS:   const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtnloyltkn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeahswjh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtrehqjxcd.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gttsquknik.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gtisedecbw.html

C#:   const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtsnmpskbl.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gtptufcmjf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gtikjnuuxm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoftcoskc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtjhgsqfmf.html

TS:   typeof x; x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtxwlceeib.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cdnleiting.top/Article/details/gtabaxuvwb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gtmdgqcshk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yonumen.top/Article/details/gtxhimqyvi.html

C#:   x.GetType().Name; x is int
来源：http://dali.quarkkingdee.top/Article/details/gticpmlxwc.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gtsuttqudx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.quarkkingdee.top/Article/details/gtksuireik.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtitkfpcqx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtchrnqiav.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtuxjhtauj.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gttcznrumx.html

Go:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtgdcfkqjb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtuvtkodzt.html

C#:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtqxdhjvis.html


<!-- 参考信息 -->