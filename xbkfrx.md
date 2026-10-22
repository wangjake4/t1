代发 wailian999

[U49] PHP：只读属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcmqydjl.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gtttsqyucj.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gtncqgryie.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtomoeumbd.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtbppvrnme.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gtnexrpoha.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtdlpzwbiy.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gtoxkmerng.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtujfwkggy.html

$v = $a ?? $b ?? "default";
来源：http://dali.ppjwa.cn/Article/details/gtbippkgvc.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtqyrtswxk.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gtmzuxhyxm.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gtkzxapwoz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtwnejhfff.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoviobgh.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtbhijnnjc.html

[U57] PHP：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtpmdjgour.html

"值: {$a}"
来源：http://dali.jinqigfzy.top/Article/details/gtfailjydp.html

[U58] PHP：数组三件套
来源：http://dali.dashuyun.cn/Article/details/gtyqlndpxk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gzhubu.top/Article/details/gtkgyqlzri.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gtrlrqzxma.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtywghytyo.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gtoeafgjum.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gtvnielfbu.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gtnpocbsev.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtfxooipse.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gtqarqypkr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cucudq.cn/Article/details/gtwnruokjo.html

[U63] PHP：文件读写
来源：http://dali.yongpay.top/Article/details/gtsvkupeca.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenlongwang.top/Article/details/gtbhmaeaos.html

[U64] PHP：目录遍历
来源：http://dali.sysykeji.top/Article/details/gtuuwjicyc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zycfv.cn/Article/details/gtlmvgtaoy.html

[U65] PHP：会话
来源：http://dali.zhongyouzk.top/Article/details/gtdfisujvo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtfcglcoga.html

[U66] PHP：设置 Cookie
来源：http://dali.cdnleiting.top/Article/details/gtcfkntcbu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.316326.xyz/Article/details/gtadnsrili.html

[U67] PHP：处理文件上传
来源：http://dali.zhixingplan.top/Article/details/gtgykazobq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtniuvsokf.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtjrepybqr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj202588.top/Article/details/gtaddmsjww.html

[U69] PHP：PDO 预处理
来源：http://dali.chenjidiqi.icu/Article/details/gtawtskayc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jyoumei.cn/Article/details/gtnzdjymoe.html

[U70] PHP：PDO 事务
来源：http://dali.iojbl.cn/Article/details/gtdmrvbagx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtkoisyzpx.html

[U71] PHP：抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtbxdezkwx.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gtdmnyugfo.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gtdhymsqwl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtxumwpftb.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gtvjyojknn.html

parse_ini_file("config.ini", true)
来源：http://dali.meibo888.top/Article/details/gtzplddyia.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtwbvypaqw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cashguo.top/Article/details/gtsoizfdcf.html

[U75] PHP：依赖注入
来源：http://dali.snrcjt.cn/Article/details/gtioqkahgf.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtkariexye.html

[U76] PHP：简单路由
来源：http://dali.9152youxi.cn/Article/details/gtlhqqtxth.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258.top/Article/details/gtxnmvzlcv.html

[U77] PHP：模板渲染
来源：http://dali.yangfankeji.com/Article/details/gtduhaqmfr.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtjxheimiz.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtyrjjozkf.html

composer require --dev phpunit/phpunit
来源：http://dali.yvedp.cn/Article/details/gtieedmapo.html

[U79] PHP：静态分析
来源：http://dali.hfpthk.cn/Article/details/gtciyobwjs.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gtefjstqjt.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gtcbbiydaw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtlumdyxpx.html

[U81] JS：初始化项目
来源：http://dali.haohaochexian.top/Article/details/gtrbjgczhf.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtgjsjeakg.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gtdivdurvs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtalvzsztc.html

[U83] JS：ES Module 导入导出
来源：http://dali.jiagoushi.top/Article/details/gthgpjfzqf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtfrmyyvqv.html

[U84] JS：CommonJS 写法
来源：http://dali.cucudq.cn/Article/details/gthrzmyfwn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangshuangyany.cn/Article/details/gtfemqyajt.html

[U85] JS：可选链
来源：http://dali.jyoumei.cn/Article/details/gtwndlkmsi.html

a?.b?.c
来源：http://dali.cheryme.top/Article/details/gtfgrowuxa.html

[U86] JS：空值合并
来源：http://dali.sweek.top/Article/details/gtuagudgwg.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gtlijwiddt.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gtmqaoiwwb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gttzjgxsqi.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gtsjfyzbgu.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gtkaxoxfyx.html

[U89] JS：数组去重
来源：http://dali.xinyue.icu/Article/details/gtlsprezmu.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtkiadbfps.html

[U90] JS：数字数组排序
来源：http://dali.yuanzhike.top/Article/details/gtwurowewj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtrqbvzqqy.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gtjgyynhpn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hammf.cn/Article/details/gtowwloptm.html

[U92] JS：深拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjlqatsg.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtqyrmclgb.html

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gtzmcsrslf.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtzwiwasmc.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtjnqifmqu.html

const double = x => x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupzkiydv.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gtvatehrsi.html

new Promise((resolve, reject) => {})
来源：http://dali.sxryk.cn/Article/details/gtbhltdwpd.html

[U96] JS：async/await 与异常
来源：http://dali.guannengcc.top/Article/details/gtptvdfqpu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtcbzazqre.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gtleyvlczx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gthdxncbqd.html

[U98] JS：fetch 带 JSON
来源：http://dali.ppjwa.cn/Article/details/gtphffmzgj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.mhx1999.top/Article/details/gtryvyzmrp.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gttagxtwfs.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfszafxgx.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmxqtpvh.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtjxfjgksj.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gtohhnmihx.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gtfyozbbgj.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gtfyjcfnqt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dianchejie.cn/Article/details/gtfvrzutgw.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gthhxpxykx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gtuhusrgxs.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gtoizwairk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtipwgkcie.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gtbkjxvhbu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtwhinypct.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtxetxxzip.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gtrvxliado.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniuvouhk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtogwtqxly.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gtobfjbrky.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gturudpyoj.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gthtyufsmi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gthqdyspuq.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gtydmycksv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gogol.net.cn/Article/details/gtslnvypcy.html

[U111] JS：对象转 Map
来源：http://dali.dashuyun.cn/Article/details/gtbmpypqvf.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gtduryoazv.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gttmmfgwqb.html

"7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtbsyvimua.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtsqytjbtg.html

s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtcsknncgq.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtxrjiuodt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtizvtwzmc.html

[U115] JS：生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtciwjrusf.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtwskribjg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdeulodz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gtfengddlz.html

[U117] JS：单元测试
来源：http://dali.sweek.top/Article/details/gtqjtcycio.html

npm i -D vitest;  npx vitest
来源：http://dali.jiagoushi.top/Article/details/gtoridzrcb.html

[U118] JS：开发服务器
来源：http://dali.yueranfly.top/Article/details/gtnvbtkqbq.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gtxxtrngug.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtanzpraua.html

npx vite build
来源：http://dali.shangyingyoupin.top/Article/details/gthmfqfrsk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yanxiufei.cn/Article/details/gtknzeprwv.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtaknqmrtd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvrqgrrkj.html

统计汇总
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipqjjozn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgrhybelp.html

按语言统计（条）：
来源：http://dali.jiagoushi.top/Article/details/gtmecwkucw.html

Python ......... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnotjtph.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gtazifxyzf.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtpvfozszy.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtsxbfypnv.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtilhouqxu.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gtgqudsdsk.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtdrxxywkn.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtxytqvydp.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gtkcujeaup.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtpodifomz.html

SQL ............ 90
来源：http://dali.yj20258.top/Article/details/gtirwelakt.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gtwieqjgji.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gtaopjyzvj.html

Swift .......... 15
来源：http://dali.bjfxy.top/Article/details/gtbroocqgo.html

Lua ............ 10
来源：http://dali.redwolf501.top/Article/details/gtpuovtgay.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gtrmhfcqds.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtpcuwpjtv.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtzooxhqdg.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtdzvtixin.html

按章节统计：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdyyjgtt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcayihcl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtjyanhgpo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtierwyzzs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gtgnrhxrvl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjgpyqqe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtygyesfxt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtubjhhfiz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtmiygthxi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtlybwyycv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtucovjgvd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtxrnvzark.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtqzogjdnm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtehaygawy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtwlwpjdxf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hfpthk.cn/Article/details/gtsepbvfij.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmilxbxzv.html

Q SQL 专题                              90
来源：http://dali.hongshengwenyu.top/Article/details/gtkhdcaxhc.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gtmabkblrx.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gtecrytpti.html

T 其他语言补充                          60
来源：http://dali.gotoacloud.top/Article/details/gtblnpwajj.html

U 高频实用片段                         120
来源：http://dali.gzhubu.top/Article/details/gtgsydzmrt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtqkppchjg.html

合计                                  2106 条
来源：http://dali.zdqjudy.top/Article/details/gthxeaqioh.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtormpuojo.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gtmnzqadyx.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtvgjimiim.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.snrcjt.cn/Article/details/gtsrhhzrbb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gtetydszli.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenjidiqi.icu/Article/details/gtknbgpaol.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gtvnauzlrj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.c1oappe.top/Article/details/gtmzukacog.html

—— 文件结束 ——
来源：http://dali.iojbl.cn/Article/details/gtedmyhmbc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtynyjselg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.redwolf501.top/Article/details/gthblsluiq.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gtqmfmepuu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnxlcvihh.html

【收录内容】
来源：http://dali.pycfn.com/Article/details/gtinzpmiil.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yanxiufei.cn/Article/details/gtbhgcvssz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gtvwrarozu.html

SQL · Bash · C · C++
来源：http://dali.nanxinkj.top/Article/details/gtgttfbfqb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tianlin.xyz/Article/details/gtzkwmrrwo.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtdzokfnin.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xylfe.cn/Article/details/gtekmudqyx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yangfankeji.com/Article/details/gtpwfztjrz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.iojbl.cn/Article/details/gtqqxwxoyd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvergbjrd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnlrmbfx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.316326.xyz/Article/details/gtburlonet.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hywenlv.cn/Article/details/gtojblxrmq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zdqjudy.top/Article/details/gtsyfigxwq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yongpay.top/Article/details/gtzfeouiqq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nwbrower.top/Article/details/gttigxdvgm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nwbrower.top/Article/details/gtjvkzivaz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtjmlyfwtf.html

【文件统计】
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssmworer.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtnkgddytw.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtegzosgca.html

目  录
来源：http://dali.yj202588.top/Article/details/gtrjqfzhzx.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gttfpseolf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtfuljzasb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoymccmv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtqwmndjwr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkyccnbf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtrilqlvum.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gtesbrhrtn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtbrpjqjcs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtzzowuaxh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtlmsdstcn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtwxzoeksl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtvibfhtbh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtarwpndet.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtzilffxhh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtszdrnkbi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ybcxt.top/Article/details/gtmcdsajay.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtikxgbaho.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgufenzy.top/Article/details/gtayomprrn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtlmbmfqdk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtlrcazlig.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtmzvlnkhi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtfqyjexjc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjgedumkt.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gtdzqzjzhg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtiulxzffw.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gtjszszfcf.html

Py:   print("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gtgmoatnaa.html

PHP:  echo "Hello, World!";
来源：http://dali.yj202588.top/Article/details/gtxjysnxqt.html

JS:   console.log("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtwlpjjqhq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hfpthk.cn/Article/details/gtxodjuchr.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpyxoebv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gteswapvwb.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gtypkqwixc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtqydiwglh.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gtrqxxdhjm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtsqmmjwwa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nanxinkj.top/Article/details/gttmvyouln.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jianghu66.top/Article/details/gtmouoqmma.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.316326.xyz/Article/details/gtgwbpxjca.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtobgqyxpr.html

Go:   name := "Alex"; age := 20
来源：http://dali.yangfankeji.com/Article/details/gtprlolaef.html

Ruby: name = "Alex"; age = 20
来源：http://dali.meibo888.top/Article/details/gttiwyevih.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtyonvyzwk.html

[A03] 常量定义
来源：http://dali.hysaishi.cn/Article/details/gtlhsztqaw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yanxiufei.cn/Article/details/gtmjijhbvn.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtaxkgfusw.html

JS:   const PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtrjblgqfw.html

TS:   const PI: number = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtfvicfkqq.html

Java: static final double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtbddisokj.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtckugmktn.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtwbtfpukb.html

C#:   const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gterddtlay.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gtujcwnwcx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhixingplan.top/Article/details/gtabpsmwcv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenzaomai.com/Article/details/gtwhqvajhl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtjhfzsyir.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtifkcuihk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtqsdsygiw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuanzx.com/Article/details/gtzmxlgnhv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gtounjxvti.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gthtdrezoy.html

[A05] 整数除法与取模
来源：http://dali.xuetiantiany.cn/Article/details/gtnvdjveol.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jyoumei.cn/Article/details/gtwgcowktt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtvydvyboy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtgpyjdipb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtlktzlwjy.html

Java: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtepagspst.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtbbzwhmed.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtiqaihenr.html

C#:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtodtzknvl.html

[A06] 字符串转数字
来源：http://dali.316326.xyz/Article/details/gtdfxflkrl.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gticdoaoea.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aizwys.cn/Article/details/gtnmwkmtpj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtrlhhatxq.html


<!-- 参考信息 -->