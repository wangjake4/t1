代发 wailian999

[U49] PHP：只读属性
来源：http://dali.chenzaomai.com/Article/details/gt2jahgqrmr.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gt2uwqysfqp.html

[U50] PHP：构造器属性提升
来源：http://dali.zdqjudy.top/Article/details/gt2aejalsuc.html

public function __construct(private int $id) {}
来源：http://dali.xuanzx.com/Article/details/gt2nennwtra.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gt2qatgxdut.html

[$a, $b] = $arr;
来源：http://dali.fzhhl.top/Article/details/gt2gnlwyicc.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gt2mioctapr.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gt2fhjoggci.html

[U53] PHP：空合并运算符
来源：http://dali.yangfankeji.com/Article/details/gt2qrqbmabr.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvrlpllu.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmsgdnlo.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gt2xpetnbzr.html

[U55] PHP：match 表达式
来源：http://dali.daria6918.cn/Article/details/gt2iefoatqn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gt2wavnwumt.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gt2iygovjtu.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2musykrvj.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2gexgpdxx.html

"值: {$a}"
来源：http://dali.dianchejie.cn/Article/details/gt2qbzjczks.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gt2uzmauxvl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rohllqhc.html

[U59] PHP：自定义排序
来源：http://dali.xylfe.cn/Article/details/gt2xkjzcayj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2ljfxqumb.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gt2cbbulvmo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gt2ajuxxjyv.html

[U61] PHP：正则
来源：http://dali.gotoacloud.top/Article/details/gt2ldbfkudt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2akplxoem.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfzdmikw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.redwolf501.top/Article/details/gt2quixzpql.html

[U63] PHP：文件读写
来源：http://dali.jlsjyb.cn/Article/details/gt2mhjxwumh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gt2qlmhbbcs.html

[U64] PHP：目录遍历
来源：http://dali.dianchejie.cn/Article/details/gt2ymspxaia.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gt2wfozaawj.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jizlqcsp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2zewccvhb.html

[U66] PHP：设置 Cookie
来源：http://dali.xinyue.icu/Article/details/gt2azoxmmel.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.redwolf501.top/Article/details/gt2vnznjbql.html

[U67] PHP：处理文件上传
来源：http://dali.guowangkeji.top/Article/details/gt2kfrznfgw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dacknrll.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gt2rdqxgrfw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmsbnloy.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gt2zwxbzfng.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gt2gbscgoii.html

[U70] PHP：PDO 事务
来源：http://dali.daxiang520.top/Article/details/gt2zgjprlyc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dianchejie.cn/Article/details/gt2ewbkwbuc.html

[U71] PHP：抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhrodwat.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gt2ycqggkoq.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gt2wigwooet.html

error_log("失败: " . $e->getMessage());
来源：http://dali.mhx1999.top/Article/details/gt2xilekgpr.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifwhmsbo.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pquwkwoy.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2ijnhzsmf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.havefunace.top/Article/details/gt2dllzmxpb.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gt2woizyoni.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gt2helfwsrr.html

[U76] PHP：简单路由
来源：http://dali.tianlin.xyz/Article/details/gt2tagmwknj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gt2yjibvxoh.html

[U77] PHP：模板渲染
来源：http://dali.yueranfly.top/Article/details/gt2eeriirtj.html

composer require twig/twig
来源：http://dali.hongshengwenyu.top/Article/details/gt2byrhaivv.html

[U78] PHP：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbxtgatx.html

composer require --dev phpunit/phpunit
来源：http://dali.chenjidiqi.icu/Article/details/gt2rczzbtjt.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gt2bpqinvig.html

composer require --dev phpstan/phpstan
来源：http://dali.cheryme.top/Article/details/gt2dbhyitpx.html

[U80] PHP：代码规范修复
来源：http://dali.daxiang520.top/Article/details/gt2ewpetley.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.mhx1999.top/Article/details/gt2dqgianfw.html

[U81] JS：初始化项目
来源：http://dali.ivvv.top/Article/details/gt2zwxrvfvx.html

npm init -y;  npm i express
来源：http://dali.meibo888.top/Article/details/gt2zalxftvv.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gt2zvssdjax.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tanke756.top/Article/details/gt2smxgsene.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gt2bvzyxptw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2sqeprylm.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gt2twyepstg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gt2srbzfdci.html

[U85] JS：可选链
来源：http://dali.shuidangran.top/Article/details/gt2rfjaqawl.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gt2oubzpaio.html

[U86] JS：空值合并
来源：http://dali.yvedp.cn/Article/details/gt2qlwbgqge.html

a ?? b
来源：http://dali.hnqzz.top/Article/details/gt2jfqguhdq.html

[U87] JS：解构默认值
来源：http://dali.hnqzz.top/Article/details/gt2zsvyhgxj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hammf.cn/Article/details/gt2wdrojfyb.html

[U88] JS：对象展开合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2jaqrncym.html

{ ...a, ...b }
来源：http://dali.yanxiufei.cn/Article/details/gt2xzixmpnm.html

[U89] JS：数组去重
来源：http://dali.birdmap.top/Article/details/gt2hrscibqw.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfqwfiyd.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gt2bsklenbw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2wzbtvfei.html

[U91] JS：对象键值遍历
来源：http://dali.c1oappe.top/Article/details/gt2ibeubfeu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gt2iyjvyvuq.html

[U92] JS：深拷贝
来源：http://dali.c1oappe.top/Article/details/gt2dxphygee.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2osgurwcd.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gt2xawanihc.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmywruny.html

[U94] JS：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gt2oybbyiff.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gt2mivtzunc.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gt2ldxjfkur.html

new Promise((resolve, reject) => {})
来源：http://dali.xinyue.icu/Article/details/gt2skajznsx.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gt2tobmnnfc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2uhjnsgna.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvptncrh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2loprmlhg.html

[U98] JS：fetch 带 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2hpunmtmy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gt2jpvbqbdp.html

[U99] JS：事件监听
来源：http://dali.hywenlv.cn/Article/details/gt2lvwjdikg.html

el.addEventListener("click", e => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjrjedri.html

[U100] JS：DOM 查询
来源：http://dali.daxiang520.top/Article/details/gt2lmrbucee.html

document.querySelector(".item")
来源：http://dali.hammf.cn/Article/details/gt2qlirojms.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gt2akaxcmey.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gt2duugltfq.html

[U102] JS：本地存储
来源：http://dali.snrcjt.cn/Article/details/gt2yfjpttdd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gt2klysjnuh.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gt2lhfvzhqk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gt2ktswvajs.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gt2yszyychl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2hspqyaku.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrqcuvwl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpmsofjp.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2jqzzveqk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gt2lgveruqx.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2aqroovdi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdscfmep.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gt2rscvwnhj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hysaishi.cn/Article/details/gt2lmupktpy.html

[U109] JS：数组分组
来源：http://dali.xinyue.icu/Article/details/gt2ujhwjppd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2jbtezstl.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2movlmuld.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsquxry.html

[U111] JS：对象转 Map
来源：http://dali.meibo888.top/Article/details/gt2cctflhtv.html

new Map(Object.entries(obj))
来源：http://dali.sufxvd.cn/Article/details/gt2wmhsqvny.html

[U112] JS：字符串补位
来源：http://dali.vqdsnc.cn/Article/details/gt2nvipoevc.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2tgcmnmbi.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gt2zlvifkkk.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2wiyunknm.html

[U114] JS：JSON 深比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anlfzdbn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyiskpgr.html

[U115] JS：生成 UUID
来源：http://dali.ybcxt.top/Article/details/gt2riyyhret.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2sbetacbo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gt2mxqlaklo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2zkcvikpc.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2yymvkhgo.html

npm i -D vitest;  npx vitest
来源：http://dali.sysykeji.top/Article/details/gt2fyefcfef.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gt2srwlbgak.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gt2iffntomu.html

[U119] JS：生产构建
来源：http://dali.nanxuanxn.top/Article/details/gt2koowvzsy.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gt2qtdmsueb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iihxprhl.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gt2fkeymvvs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tqrzvvvk.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gt2plkqzwtr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldblquho.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gt2bvfwtskp.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gt2facizxax.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2grmzxham.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gt2blooaxbi.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gt2letjfaor.html

Java ........... 212
来源：http://dali.sufxvd.cn/Article/details/gt2yvzbzhlt.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gt2eaypkosi.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gt2ipbplcok.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gt2omjozyik.html

C .............. 30
来源：http://dali.andypj.xyz/Article/details/gt2nuqqytaj.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gt2epesblgk.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gt2prpycuzo.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gt2zdpkecgd.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gt2qfvbbhag.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gt2kpflqddj.html

Lua ............ 10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctbiareu.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2ssccsmav.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gt2looiefle.html

------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntzjwwuk.html

合计 ........... 2106 条
来源：http://dali.chenzaomai.com/Article/details/gt2pyvuqeft.html

按章节统计：
来源：http://dali.shzxlz.cn/Article/details/gt2ajglslfi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gt2acnndzov.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2kvlyfzba.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2gjrvroli.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gt2mxcalvsu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hfpthk.cn/Article/details/gt2seyudbtv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gt2qvmadbcf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gt2ppbqubxh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gt2uvaxqnir.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2pahdtxfp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2nrungdor.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2gvndafmx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2ljqewkod.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2feooinaj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gt2hfrsuykl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gt2aczvluhz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2pvxtnqvm.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gt2ivchrhtd.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gt2ppodocqp.html

S C / C++ 专题                          60
来源：http://dali.tianlin.xyz/Article/details/gt2sbrwvmcn.html

T 其他语言补充                          60
来源：http://dali.ybcxt.top/Article/details/gt2jjbionum.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejuhmhqb.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2pxjefcyk.html

合计                                  2106 条
来源：http://dali.shzxlz.cn/Article/details/gt2vrcekofp.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2azzqgilp.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gt2ayjsdrni.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2stptfnwj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gt2aybfcvjm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gt2nlpsdwwd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gt2rtqdykgv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gt2hnijmyta.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gt2ylzpaueo.html

—— 文件结束 ——
来源：http://dali.quarkkingdee.top/Article/details/gt2liqtntki.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fmccflxs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.quarkkingdee.top/Article/details/gt2ytsvrpbr.html

Common Programming Examples Cheat Book
来源：http://dali.mhx1999.top/Article/details/gt2yhnffmqm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2uwdsbpht.html

【收录内容】
来源：http://dali.sufxvd.cn/Article/details/gt2lovacdhc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gt2dcswsora.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cucudq.cn/Article/details/gt2bhrentzj.html

SQL · Bash · C · C++
来源：http://dali.meibo888.top/Article/details/gt2jwkluzwc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuanzx.com/Article/details/gt2fzxoxmqh.html

【使用说明】
来源：http://dali.yonumen.top/Article/details/gt2zmkgoexm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sufxvd.cn/Article/details/gt2jukgsdem.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gt2vqgowaqq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.kuanghao11.cn/Article/details/gt2mtmjdezp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzpcjavr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.9152youxi.cn/Article/details/gt2ekixqutm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qskatjlw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sufxvd.cn/Article/details/gt2voxiofcn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ybcxt.top/Article/details/gt2dlwpzucz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj202588.top/Article/details/gt2mgjqugvi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yangfankeji.com/Article/details/gt2yfuvsobi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gt2inmljoij.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shuidangran.top/Article/details/gt2gwgwzcao.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gt2pvvczcwv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gt2yrcfaufy.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2pzxrnmvz.html

目  录
来源：http://dali.c1oappe.top/Article/details/gt2gteddhng.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2ybxoyqbm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gt2lyfjeyuy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gt2eddbfuae.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2vnfkjhdu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxaaxynk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gt2wsgvetsg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2abtnzpjc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2nuuftqic.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gt2otvtrgoh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2lwsofguz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gt2scvelwyk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvfkgkvg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2ygqcptnr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2qmwbhhgt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gt2uutxhoix.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhengqikj.top/Article/details/gt2vtkeighb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gt2lxutymyv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gt2pyixikno.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2gwhdtyur.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gt2eiflfotr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2uhzyyiqm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gt2joctvkcs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iacqfckn.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gt2jpvywaut.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhejtfmm.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gt2saexmxap.html

Py:   print("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmdyxrfa.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gt2mxhateyc.html

JS:   console.log("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2fbvlqvht.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gt2tapwgsos.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2yxpxzmzu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gt2jdgflhhd.html

Ruby: puts "Hello, World!"
来源：http://dali.snrcjt.cn/Article/details/gt2yhfxrgym.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2kuymiqdn.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgyvuqbc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jyoumei.cn/Article/details/gt2czutccpr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2sdjattog.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj202588.top/Article/details/gt2gmlkgrfr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.smart0.xyz/Article/details/gt2ucswfkhx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gt2njhwzlfd.html

Go:   name := "Alex"; age := 20
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjbsposu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gt2ssdamzjr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyqbzqp.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gt2okcxnenz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxinkj.top/Article/details/gt2ibtvyksh.html

PHP:  const PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2dgqtoywj.html

JS:   const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2xyywoftq.html

TS:   const PI: number = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2kckemhms.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2gdxqpndn.html

Go:   const PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gt2ucawdxwo.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2hapcnoze.html

C#:   const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2dwtzpfhf.html

[A04] 判断变量类型
来源：http://dali.gotoacloud.top/Article/details/gt2phzlezzd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aocehbiv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tianlin.xyz/Article/details/gt2fvypyxes.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gt2oypbtozz.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2klyffrhm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xziqi.cn/Article/details/gt2tcsshhfg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gt2fpqettvl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuanzhike.top/Article/details/gt2prapeqzo.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvekkana.html

[A05] 整数除法与取模
来源：http://dali.fengsongda.top/Article/details/gt2vowuhoda.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jianghu66.top/Article/details/gt2etnvqicv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihobnnub.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gt2gvibwxfx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcnzgjti.html

Java: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2axgrsbpd.html

Go:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2jpvpqhsd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysjjxuqf.html

C#:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2qhiksxhu.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2omtuxhqf.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gt2hkmeytdq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhjgdefe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkxlicoe.html


<!-- 参考信息 -->