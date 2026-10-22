代发 wailian999

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gt2aarhkdds.html

int|string $id
来源：http://dali.vqdsnc.cn/Article/details/gt2nztaofar.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gt2vllwcivt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gt2fxruevyb.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gt2mwlzhydd.html

public readonly string $name
来源：http://dali.jyoumei.cn/Article/details/gt2srumnsnj.html

[U50] PHP：构造器属性提升
来源：http://dali.dashuyun.cn/Article/details/gt2duyrmqdr.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qbjevckd.html

[U51] PHP：数组解构
来源：http://dali.haohaochexian.top/Article/details/gt2fxprtmaw.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gt2drlpnekn.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2udiytfqb.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gt2loruetuk.html

[U53] PHP：空合并运算符
来源：http://dali.9152youxi.cn/Article/details/gt2kbgmwaoz.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gt2myybujmz.html

[U54] PHP：空安全调用
来源：http://dali.jqgufenzy.top/Article/details/gt2harucfhm.html

$obj?->method()
来源：http://dali.zhixingplan.top/Article/details/gt2xqyouoyc.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gt2rgubtjsm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gt2wnhxapvj.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gt2lkprcgyn.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2qfxstxhy.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2oqvqngri.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gt2cwvbbpte.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2csyhziir.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cheryme.top/Article/details/gt2jqpwkkcu.html

[U59] PHP：自定义排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsudnier.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gt2rhlnvxmg.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gt2plguzkdr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aijiofij.html

[U61] PHP：正则
来源：http://dali.tianlin.xyz/Article/details/gt2uxwnkkmk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2gnzkehvy.html

[U62] PHP：日期对象
来源：http://dali.shuidangran.top/Article/details/gt2amprxbzo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gt2zfwmvttj.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gt2hsdxyjyy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guannengcc.top/Article/details/gt2gwvqjqia.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elgztejh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ydzc1.top/Article/details/gt2tfepfoqh.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gt2ylswbqsr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2grpcknam.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gt2edugufsy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ydzc1.top/Article/details/gt2ksqvrwez.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gt2mmiujrqq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuxming.cn/Article/details/gt2jdnugbhj.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gt2zjcbkmgd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gt2hscwlsab.html

[U69] PHP：PDO 预处理
来源：http://dali.gzhubu.top/Article/details/gt2hkwqnpmg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gt2dqoeidvk.html

[U70] PHP：PDO 事务
来源：http://dali.daria6918.cn/Article/details/gt2qowuzjbr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zycfv.cn/Article/details/gt2xooocbkc.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2bxzdhlpf.html

throw new RuntimeException("失败", 500);
来源：http://dali.iojbl.cn/Article/details/gt2aqezzjhg.html

[U72] PHP：写错误日志
来源：http://dali.yangfankeji.com/Article/details/gt2xvebfqjk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gt2ilhnncmp.html

[U73] PHP：读取 ini 配置
来源：http://dali.hfpthk.cn/Article/details/gt2trrwkols.html

parse_ini_file("config.ini", true)
来源：http://dali.daxiang520.top/Article/details/gt2zlpbklau.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2wpvrjqwl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gt2qamurblz.html

[U75] PHP：依赖注入
来源：http://dali.bjfxy.top/Article/details/gt2ldibuudb.html

composer require psr/container
来源：http://dali.zhongyouzk.top/Article/details/gt2eoiegcay.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gt2mzinnstz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gt2tliqqucs.html

[U77] PHP：模板渲染
来源：http://dali.ybcxt.top/Article/details/gt2hbqpgdpt.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gt2mfpwaius.html

[U78] PHP：单元测试
来源：http://dali.sweek.top/Article/details/gt2bjkzwtjh.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shqzopwd.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qaekzhxq.html

composer require --dev phpstan/phpstan
来源：http://dali.yueranfly.top/Article/details/gt2uxokjezy.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gt2oyhaquud.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xziqi.cn/Article/details/gt2skchkzih.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2dtqxtrwx.html

npm init -y;  npm i express
来源：http://dali.yanxiufei.cn/Article/details/gt2jegunwdz.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gt2eqzwsslp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gzhubu.top/Article/details/gt2mccfsrmh.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gt2elbmwfxs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2xnvoqlqk.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gt2amkfdsej.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.kuanghao11.cn/Article/details/gt2bifnjhgl.html

[U85] JS：可选链
来源：http://dali.ydzc1.top/Article/details/gt2udimpnlj.html

a?.b?.c
来源：http://dali.cqqwz.cn/Article/details/gt2skiqwdoy.html

[U86] JS：空值合并
来源：http://dali.zycfv.cn/Article/details/gt2zxsblopm.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gt2mkaogann.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gt2iaytaeot.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zdqjudy.top/Article/details/gt2sykjtwfo.html

[U88] JS：对象展开合并
来源：http://dali.c1oappe.top/Article/details/gt2kxgscowz.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gt2otkjrhzi.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gt2uxdrckbb.html

[...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfkhzetk.html

[U90] JS：数字数组排序
来源：http://dali.chenlongwang.top/Article/details/gt2dokxtrdw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gt2hzoonuwh.html

[U91] JS：对象键值遍历
来源：http://dali.c1oappe.top/Article/details/gt2ccafevuf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gt2elzhfipe.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gt2zjsdsyez.html

structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2luwfbmso.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gt2gkydmmvd.html

`共 ${n} 条`
来源：http://dali.yangfankeji.com/Article/details/gt2yzkkkntt.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gt2rttfgzuf.html

const double = x => x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gt2xesvnqvw.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gt2nigwrzsp.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gt2asasbuiv.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gt2lgcvxrwt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2hmhbgqyl.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gt2lbcltite.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2gtnyuhuc.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyhqilqq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gt2pwoxxhav.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gt2lgxkyyyy.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gt2zhvkxfjs.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gt2cfwpkqaw.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gt2dlxuimjy.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gt2fskpowfr.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gt2yxyszcps.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gt2udiqrdfn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gt2glrhaejp.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gt2ykefbxbi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gt2zztsxkeg.html

[U104] JS：防抖
来源：http://dali.yj20258.top/Article/details/gt2kczpjwzl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2fcearkap.html

[U105] JS：节流
来源：http://dali.aibaodan.cn/Article/details/gt2eigfzmep.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gt2dotcevis.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2scqtpexi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2bprmkkpd.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2qymaprkp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2qmincioz.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gt2rovwdtql.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbgrycsa.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcvzurtj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2wynvumqc.html

[U110] JS：数组分块
来源：http://dali.ppjwa.cn/Article/details/gt2hteyyuvg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gt2geqpaxrc.html

[U111] JS：对象转 Map
来源：http://dali.hammf.cn/Article/details/gt2ncvtnihi.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gt2pklqwjpo.html

[U112] JS：字符串补位
来源：http://dali.havefunace.top/Article/details/gt2aqdiignj.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2mslwkmxw.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gt2tqtwifca.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2nqxoswvo.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjerrpiy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gt2nzzagjzv.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gt2vewsvnyl.html

crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2axzrnzmu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gt2kubtvnvj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sxryk.cn/Article/details/gt2akohwdqv.html

[U117] JS：单元测试
来源：http://dali.cucudq.cn/Article/details/gt2bzvsjnrp.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gt2tfqumtud.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gt2vyaocizp.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gt2lltmjwyp.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gt2syjivggt.html

npx vite build
来源：http://dali.gaohongyu789.top/Article/details/gt2jrsstyoa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlhnpqms.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxaoqin.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tlknmvfw.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gt2qjvrxnqp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ajoqrnar.html

按语言统计（条）：
来源：http://dali.yuxming.cn/Article/details/gt2brbtmeyl.html

Python ......... 252
来源：http://dali.ehwqpu.com/Article/details/gt2nucedpcf.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gt2moxeeuuj.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gt2tzjhsqvb.html

TypeScript ..... 212
来源：http://dali.9152youxi.cn/Article/details/gt2xujfswou.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gt2czoihgpt.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2ljnnpeiw.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxsyibff.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gt2rkqmbloi.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gt2bbhlddth.html

C++ ............ 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thoaxpaq.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gt2txxttdcs.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gt2ewclnreg.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gt2srezmcjk.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2fgjcmzee.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gt2knryvyir.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2nzmxqmdf.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gt2hzycqrid.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2focrhwho.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gt2pxfnfedz.html

按章节统计：
来源：http://dali.yueranfly.top/Article/details/gt2fbswnvsc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gt2iimcwbih.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2fjknkrht.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gt2cjizvgkt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gt2znooxnlj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.9152youxi.cn/Article/details/gt2zswzpvpg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2uohursdo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2wfaumksu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gt2rftxqyzt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2wlqedour.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gt2ejiaeesn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2nsxwvpzj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2uslzfbcr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqvlysni.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gt2nnuorfcu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daria6918.cn/Article/details/gt2ggvmpndb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyrebedg.html

Q SQL 专题                              90
来源：http://dali.jqgfzy.top/Article/details/gt2ebqwqcho.html

R Bash 专题                             80
来源：http://dali.hnxiangtu.top/Article/details/gt2szprzmqx.html

S C / C++ 专题                          60
来源：http://dali.haohaochexian.top/Article/details/gt2htcbskgu.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gt2exlwlgri.html

U 高频实用片段                         120
来源：http://dali.yangfankeji.com/Article/details/gt2jciglphv.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2lqkdtfbz.html

合计                                  2106 条
来源：http://dali.c1oappe.top/Article/details/gt2jxbeigyr.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2gprcofoo.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwnnlckx.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2ncxwplhb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hammf.cn/Article/details/gt2gkpfoink.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gt2gvrbiltt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxuanxn.top/Article/details/gt2mdwqmopt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.vqdsnc.cn/Article/details/gt2nbeiqtsb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.iojbl.cn/Article/details/gt2ximfqhsw.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gt2lmcaqhqu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lwxqbovg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aizwys.cn/Article/details/gt2porqmcar.html

Common Programming Examples Cheat Book
来源：http://dali.fengsongda.top/Article/details/gt2frwrtgrg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnyfeyyt.html

【收录内容】
来源：http://dali.yangfankeji.com/Article/details/gt2vxzkfqro.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gt2yxizfzxj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhzrdpnq.html

SQL · Bash · C · C++
来源：http://dali.nanxuanxn.top/Article/details/gt2hiypnpwm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenlongwang.top/Article/details/gt2njuanjzf.html

【使用说明】
来源：http://dali.hysaishi.cn/Article/details/gt2wyvzpduh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinqigufen.top/Article/details/gt2ttvcolsl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gt2btegrwsb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gt2hzdvsihg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.316326.xyz/Article/details/gt2tcmifksu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gt2kzwdbhdz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gt2gaytuzia.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yangfankeji.com/Article/details/gt2llkbkbeg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2gpsqzzev.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdwsnrlg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpeeyieo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gaohongyu789.top/Article/details/gt2ejiyjtnn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gt2anbailha.html

【文件统计】
来源：http://dali.aizwys.cn/Article/details/gt2fshcwbvr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gt2qqnnaagp.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itsadswc.html

目  录
来源：http://dali.feifeiyinyue.top/Article/details/gt2oldrfopc.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2djyuzyyg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gt2nbrtdgdy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gt2sayqqdhx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2ssbctnyt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gt2boyrabkg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnroiylt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gt2tufprkta.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2uccpadcj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2azptxrdw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpvosobi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gt2xqnkufif.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2oqhojuvh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2uryvllve.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2sliwqzxc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ipfailaa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2btfzoegg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2awjfmfmr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gt2khhnrokp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xinyue.icu/Article/details/gt2jgmjakft.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gt2yipivnvc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2gusxsxqr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gt2hrttpvzf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xrzlczbl.html

A. 基础语法与类型
来源：http://dali.9152youxi.cn/Article/details/gt2smhucplx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydnllzxb.html

[A01] Hello World
来源：http://dali.c1oappe.top/Article/details/gt2lkvxvqcw.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgvyjcpo.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gt2oxpdeubu.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2lqngkbfi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gt2ietdupfl.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gt2musyupoh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gt2kyzejfeb.html

Ruby: puts "Hello, World!"
来源：http://dali.haohaochexian.top/Article/details/gt2mmlekgbj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gt2gmkkicze.html

[A02] 变量声明与赋值
来源：http://dali.kuanghao11.cn/Article/details/gt2esogzyhr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gt2wdyozghx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2thonqihc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yvedp.cn/Article/details/gt2zvkbocaz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ybcxt.top/Article/details/gt2wpiwkblb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2tdnhjvqf.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gt2yfqbtrlf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ppjwa.cn/Article/details/gt2bytotrkd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2gcnhzqpy.html

[A03] 常量定义
来源：http://dali.aibaodan.cn/Article/details/gt2zoffvvyj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gt2tfqjnbnx.html

PHP:  const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2odqnoyev.html

JS:   const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2puxzsgul.html

TS:   const PI: number = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2whlermhz.html

Java: static final double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrvxfjie.html

Go:   const PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gt2oqehuvpn.html

Ruby: PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gt2qfdeaybg.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2caaqhnkh.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gt2oiqrheye.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vttvxcnx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkwveatx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gt2djhoresv.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gt2tucvlwtc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gt2ysntwxsz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.kuanghao11.cn/Article/details/gt2ulsdntbw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gt2wrauvdon.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gt2odumuafj.html

[A05] 整数除法与取模
来源：http://dali.nanxuanxn.top/Article/details/gt2erupzhxh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ehwqpu.com/Article/details/gt2rqbyopar.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2jlyqwpti.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2zyflgtgo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2iecqgddq.html

Java: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2pgpookwv.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2rjcwhqcz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chxepfxc.html

C#:   7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2hikpymwk.html


<!-- 参考信息 -->