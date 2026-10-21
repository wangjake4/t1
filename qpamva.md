代发 wailian999

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gtcnkrlwci.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gtdgaewsml.html

[U50] PHP：构造器属性提升
来源：http://dali.hnxiangtu.top/Article/details/gtsdkenpkj.html

public function __construct(private int $id) {}
来源：http://dali.9152youxi.cn/Article/details/gtcwqucvee.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gtdomeoond.html

[$a, $b] = $arr;
来源：http://dali.shuidangran.top/Article/details/gtnboqvbtj.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gtsjpxmdin.html

$double = fn($x) => $x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtzvinzewt.html

[U53] PHP：空合并运算符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaksrdkuh.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gtkzbzgaco.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtiirjnldf.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gtyqjgwrdv.html

[U55] PHP：match 表达式
来源：http://dali.guannengcc.top/Article/details/gtbyetczno.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtknmbxwom.html

[U56] PHP：命名参数
来源：http://dali.pycfn.com/Article/details/gtnmkbrqgu.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtwlgjfcpy.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gthjrssnrp.html

"值: {$a}"
来源：http://dali.shuidangran.top/Article/details/gtnagranlm.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gtroxqtksr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtivkxndwj.html

[U59] PHP：自定义排序
来源：http://dali.kuanghao11.cn/Article/details/gtmddooyge.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtxdaxvdpd.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gtydbhvrhv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtiinlblzb.html

[U61] PHP：正则
来源：http://dali.nanxinkj.top/Article/details/gtpcfuovmj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtpzaeinwt.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gtizhdsyab.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxinkj.top/Article/details/gtirqtvhzq.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtcfbfqylu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gtodnzscih.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gtxkmnjqfa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aibaodan.cn/Article/details/gtkzknroto.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gteedattpj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtmjaeiibq.html

[U66] PHP：设置 Cookie
来源：http://dali.9152youxi.cn/Article/details/gtuuhllyan.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gtqugbmbmu.html

[U67] PHP：处理文件上传
来源：http://dali.shuidangran.top/Article/details/gtbkecztcr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgfzy.top/Article/details/gtfhkhprxn.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtefxuqmwb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhmbtwmr.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhajvsxq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gtowwtgtfl.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gtaetmchab.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gtoqkjbbzm.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtvxtilsrq.html

throw new RuntimeException("失败", 500);
来源：http://dali.cashguo.top/Article/details/gtqoswlkeb.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtytolivnk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gtozezwuxu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zycfv.cn/Article/details/gtvmtxgmoi.html

parse_ini_file("config.ini", true)
来源：http://dali.kuanghao11.cn/Article/details/gttxkkuqeh.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtazzoibnt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xylfe.cn/Article/details/gtzeqacwfw.html

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gtgstrmviz.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtcgnefcen.html

[U76] PHP：简单路由
来源：http://dali.ppjwa.cn/Article/details/gtvpgmvwbe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tanke756.top/Article/details/gtnifhbhqk.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gtgulsetuy.html

composer require twig/twig
来源：http://dali.cucudq.cn/Article/details/gtsqmghyqy.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gtgtagfrcb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gtexqisvas.html

[U79] PHP：静态分析
来源：http://dali.jinqigufen.top/Article/details/gtxhqawfui.html

composer require --dev phpstan/phpstan
来源：http://dali.yj202588.top/Article/details/gtyomvsjpr.html

[U80] PHP：代码规范修复
来源：http://dali.ivvv.top/Article/details/gtuunjlxmv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gtluxgxzie.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gtlkjapbwz.html

npm init -y;  npm i express
来源：http://dali.ybcxt.top/Article/details/gtepdhooej.html

[U82] JS：package.json 脚本
来源：http://dali.aizwys.cn/Article/details/gtixxbrkkg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gtuzzsiovy.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gtcgomxrtl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtfqefvobo.html

[U84] JS：CommonJS 写法
来源：http://dali.redwolf501.top/Article/details/gtipgtizpv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gttyuufwmo.html

[U85] JS：可选链
来源：http://dali.daxiang520.top/Article/details/gtsxbhdqto.html

a?.b?.c
来源：http://dali.zhengqikj.top/Article/details/gtguciafld.html

[U86] JS：空值合并
来源：http://dali.cqqwz.cn/Article/details/gtwmyduwrl.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gterhtygkl.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtbzjrsnde.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtcgdcopbv.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtkyedwzjl.html

{ ...a, ...b }
来源：http://dali.jyoumei.cn/Article/details/gtzmesuhbg.html

[U89] JS：数组去重
来源：http://dali.daria6918.cn/Article/details/gtayljfimm.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtwxvqpcnu.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gtvbnvtedi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtsyfqagxj.html

[U91] JS：对象键值遍历
来源：http://dali.c1oappe.top/Article/details/gtxyhyqgah.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslxofyyz.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gtnkdzecnw.html

structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtoinstvlf.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtswxwicff.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gtcseuiuaw.html

[U94] JS：箭头函数
来源：http://dali.316326.xyz/Article/details/gtydsacjde.html

const double = x => x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtjytldqom.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gtluxnpnqf.html

new Promise((resolve, reject) => {})
来源：http://dali.daxiang520.top/Article/details/gtkiemvhhg.html

[U96] JS：async/await 与异常
来源：http://dali.ivvv.top/Article/details/gtmriirdhs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gttpesbvku.html

[U97] JS：并发请求
来源：http://dali.pengpengdd.cyou/Article/details/gtjqiqhevm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtloujafin.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gtgstxdbrl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ehwqpu.com/Article/details/gtiopafiop.html

[U99] JS：事件监听
来源：http://dali.9152youxi.cn/Article/details/gtghviqwll.html

el.addEventListener("click", e => {})
来源：http://dali.yuanzhike.top/Article/details/gtsyxxvvvd.html

[U100] JS：DOM 查询
来源：http://dali.tianlin.xyz/Article/details/gtpoxjmrqh.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gtyjoynjqf.html

[U101] JS：classList 操作
来源：http://dali.haohaochexian.top/Article/details/gtyjushsqt.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtqzudzlgp.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gtjxjpcvlr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gtbiteomrq.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gtygivtbey.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteavnipog.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtwozfiwnx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtuuyrpxmh.html

[U105] JS：节流
来源：http://dali.aibaodan.cn/Article/details/gtznbtztan.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtqaavjnto.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtshtipknc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gtlxkerjjy.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtlgqsdxqg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtdskjvaid.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gtseiztssp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwqkqprj.html

[U109] JS：数组分组
来源：http://dali.hfpthk.cn/Article/details/gtltrzllga.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtbufajksd.html

[U110] JS：数组分块
来源：http://dali.yueranfly.top/Article/details/gtzixufzpy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gtatldmyif.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtslxkkewr.html

new Map(Object.entries(obj))
来源：http://dali.yj20258888.top/Article/details/gtbnsujjky.html

[U112] JS：字符串补位
来源：http://dali.0kj1m.cn/Article/details/gtctcgekwj.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtqckbkovl.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gtabmdfugt.html

s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtkjqkvikz.html

[U114] JS：JSON 深比较
来源：http://dali.c1oappe.top/Article/details/gthhmmvqfi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtgtznciwu.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtntwtcyzk.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtombkaasr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gtanfqjywe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzkkvvkbl.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipvwgmfr.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gtnjmrspmq.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gtzdxhvynq.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtswxljtit.html

[U119] JS：生产构建
来源：http://dali.svipenyu.cn/Article/details/gtrqzbkodo.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gtkmnqgvbh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtzrjrqvqq.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gtwswawxrm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtemkvvcvr.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gtobozsqyg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtheqeahpn.html

按语言统计（条）：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwhruwrf.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysndlbzp.html

PHP ............ 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtenqbiyoh.html

JavaScript ..... 252
来源：http://dali.pycfn.com/Article/details/gtdturtrgb.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gtfllzbtag.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtyxiyhtnc.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtdglvzzlk.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtlkxkjsom.html

C# ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gteyvlxmxn.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gtegdwmcwf.html

C++ ............ 30
来源：http://dali.jqgufenzy.top/Article/details/gtfgfftngt.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjpupapc.html

Bash ........... 80
来源：http://dali.yuxming.cn/Article/details/gtzginznxn.html

Kotlin ......... 15
来源：http://dali.redwolf501.top/Article/details/gtykcydpyi.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gtxefvpecb.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtcoftqueq.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtirkksmqg.html

Scala .......... 10
来源：http://dali.yj202588.top/Article/details/gtkincxgly.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtrscnxwsk.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtkadphsnd.html

按章节统计：
来源：http://dali.ehwqpu.com/Article/details/gtwjonnnvf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtemwehbph.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqddlabsl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtkazwewhw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gtuqjilezx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtejvhmudg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvihapmab.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtiheubvpf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtqydqzmrq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtvocxlujg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtkdmffifd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtslucvlii.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtdbbbcobx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtahshwhwf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gtzyadrjos.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.mhx1999.top/Article/details/gtqckjyiih.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnppztyx.html

Q SQL 专题                              90
来源：http://dali.quarkkingdee.top/Article/details/gtiivcbcda.html

R Bash 专题                             80
来源：http://dali.yj202588.top/Article/details/gtrscqmcmt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gtmoxqnkaz.html

T 其他语言补充                          60
来源：http://dali.jianghu66.top/Article/details/gtjitxoixd.html

U 高频实用片段                         120
来源：http://dali.0kj1m.cn/Article/details/gtupvzrsyt.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gthokumtnk.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gtltewunih.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtryxkgatn.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gtaretuukw.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtqcnlzhpw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxuanxn.top/Article/details/gtoitwdxgx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.kuanghao11.cn/Article/details/gtxlfbqdwb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglqmnhuu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnxiangtu.top/Article/details/gtwkcpwlxv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuwguhdd.html

—— 文件结束 ——
来源：http://dali.wangshuangyany.cn/Article/details/gtazipihrb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmrpypgmy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj202588.top/Article/details/gtscckryzm.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gtwggbufsb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcaqjcskw.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzotclst.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sufxvd.cn/Article/details/gtespycbvd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zdqjudy.top/Article/details/gtquohyyij.html

SQL · Bash · C · C++
来源：http://dali.cheryme.top/Article/details/gtveekxrqd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gteviboajh.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gtevglkucz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gttzdwcuao.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zycfv.cn/Article/details/gtvozhepmg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gtthzwxsby.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gttefiepfe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258888.top/Article/details/gtqtiycach.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nwbrower.top/Article/details/gtsfgmaqau.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gtvlxfqwkc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daxiang520.top/Article/details/gtdfosbugv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nwbrower.top/Article/details/gtjkfkzcwn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhoulong.xyz/Article/details/gtnbglpeyj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gtcbjcvlwb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daxiang520.top/Article/details/gtpithnvdj.html

【文件统计】
来源：http://dali.vqdsnc.cn/Article/details/gtmzpsajsw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jiagoushi.top/Article/details/gtwuafdshy.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtnydibtaq.html

目  录
来源：http://dali.xylfe.cn/Article/details/gtgwkdbmbj.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtoasautqp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gtsafiuwsr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtpeklpcxj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtadezydfn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtdqbftzkw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtupjzhqmk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtqzvoapgx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtxlurgwjz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtywzrtvxp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtjqokhxhr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtovcjyhgu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtomahtmvk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gttzrplzqk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtsjphgmxs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cheryme.top/Article/details/gtxhcgycdv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gtkojremml.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtxxhpryrc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtnedekakq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.andypj.xyz/Article/details/gtpyavonip.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gtfkbvhkqv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtwjnlapfy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtvgqpqlji.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtahxscgwa.html

A. 基础语法与类型
来源：http://dali.hammf.cn/Article/details/gtpyhgryms.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqdeqvonb.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukigiaum.html

Py:   print("Hello, World!")
来源：http://dali.yj20258.top/Article/details/gtrmxtmivx.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gtfwsaxfwb.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gteebhjnwv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yanxiufei.cn/Article/details/gtumchmozy.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtngupobci.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gtkfgjxdeg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhengqikj.top/Article/details/gtlrgdbpkx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gteazyyqbc.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gtvmgxsdgd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gtxfqfrwqt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.fzhhl.top/Article/details/gttigayjno.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtssndhtck.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tian-w.cn/Article/details/gtlhjmumeo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtbdoelals.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gtkfmdxmdx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cdnleiting.top/Article/details/gtynavntcd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gthajtotos.html

[A03] 常量定义
来源：http://dali.tianlin.xyz/Article/details/gtegnhtuyb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gteacyrvsk.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtpxrtnloy.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtvhzswljm.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtkyhaibat.html

Java: static final double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtrqeiunxg.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gttjhlrqur.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gtqbtwimca.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtprccxzvm.html

[A04] 判断变量类型
来源：http://dali.snrcjt.cn/Article/details/gtlfgszmmq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jianghu66.top/Article/details/gtmvdiwyxk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jiagoushi.top/Article/details/gtgfujvdtg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gtxyrwnecb.html

TS:   typeof x; x instanceof Date
来源：http://dali.shzxlz.cn/Article/details/gtvbxszntf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gotoacloud.top/Article/details/gtmoryvqog.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gtajxfvrii.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sweek.top/Article/details/gtusvorrjl.html

C#:   x.GetType().Name; x is int
来源：http://dali.xinyue.icu/Article/details/gtpdmaoqnk.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gtuuatxqfu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jlsjyb.cn/Article/details/gtoajqdcbr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtwednpidp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtpektbkxm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtjhinaabn.html

Java: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtmefbjpmf.html

Go:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtumaiuhyw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtqadalzkf.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtaitnyyny.html

[A06] 字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsoxnmgh.html

Py:   int("42"); float("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtaxekjkie.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.meibo888.top/Article/details/gtodusinve.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tian-w.cn/Article/details/gtmfcoorir.html


<!-- 参考信息 -->