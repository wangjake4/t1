代发 wailian999

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gtiykksrnu.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtsmqrtdrt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhixingplan.top/Article/details/gthpclyawf.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gtghhiyabz.html

[U51] PHP：数组解构
来源：http://dali.hnxiangtu.top/Article/details/gtuvvjqumi.html

[$a, $b] = $arr;
来源：http://dali.wangdashe.top/Article/details/gtuehfpgzq.html

[U52] PHP：箭头函数
来源：http://dali.yj20258.top/Article/details/gtdjnfabqh.html

$double = fn($x) => $x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtepeddlnn.html

[U53] PHP：空合并运算符
来源：http://dali.quarkkingdee.top/Article/details/gtzzqniyia.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gtwueatuhr.html

[U54] PHP：空安全调用
来源：http://dali.dashuyun.cn/Article/details/gtlmtooubg.html

$obj?->method()
来源：http://dali.cashguo.top/Article/details/gtzsvrnknj.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtswqdkvix.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtsotxiu.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtpynojtzl.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtfujhmort.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtktiktbya.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtoyrzqeky.html

[U58] PHP：数组三件套
来源：http://dali.ehwqpu.com/Article/details/gtezpgrrfs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gtckenoqhz.html

[U59] PHP：自定义排序
来源：http://dali.yanxiufei.cn/Article/details/gtblfmzovh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtjxzpkbqf.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gtjisigntr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cashguo.top/Article/details/gtoputbexa.html

[U61] PHP：正则
来源：http://dali.zycfv.cn/Article/details/gtypxhpqeg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gttgtcdzbp.html

[U62] PHP：日期对象
来源：http://dali.0kj1m.cn/Article/details/gtzbdourja.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafdjzrja.html

[U63] PHP：文件读写
来源：http://dali.wangshuangyany.cn/Article/details/gtebygujzm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ybcxt.top/Article/details/gtqiyamona.html

[U64] PHP：目录遍历
来源：http://dali.guannengcc.top/Article/details/gtiqyrmisv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gtgyqkdkeq.html

[U65] PHP：会话
来源：http://dali.gotoacloud.top/Article/details/gtmwyinorr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtgewwviar.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtdlpftwgt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gtiqkidegc.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtquxjvrks.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gtymgwssmt.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtlslentmz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yongpay.top/Article/details/gtijpqpcmw.html

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gtfsrnquzs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstcaccbo.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gtinoffoau.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tian-w.cn/Article/details/gtrlmmzfym.html

[U71] PHP：抛出异常
来源：http://dali.sysykeji.top/Article/details/gtwpsmkglh.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtstdciagy.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtgraicpgo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gtptzcnwpn.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gtmcvfvkti.html

parse_ini_file("config.ini", true)
来源：http://dali.fzhhl.top/Article/details/gtcnvtjook.html

[U74] PHP：读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtoeezezkj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtgwuxowzk.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gtumamccpd.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gtfejuwtkg.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gtsevfeioi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gaohongyu789.top/Article/details/gtmfvfavoe.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtztiadfzz.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gtozvjofqi.html

[U78] PHP：单元测试
来源：http://dali.sysykeji.top/Article/details/gtzgajcgro.html

composer require --dev phpunit/phpunit
来源：http://dali.hfpthk.cn/Article/details/gtnqsciext.html

[U79] PHP：静态分析
来源：http://dali.kuanghao11.cn/Article/details/gtcewlkfei.html

composer require --dev phpstan/phpstan
来源：http://dali.yonumen.top/Article/details/gtlxlczqkn.html

[U80] PHP：代码规范修复
来源：http://dali.yanxiufei.cn/Article/details/gthweiuabm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtdwrmntzm.html

[U81] JS：初始化项目
来源：http://dali.yj20258888.top/Article/details/gtpyagzqkl.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtphmjcxee.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gtrapcuwpm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sufxvd.cn/Article/details/gtwrbygvxq.html

[U83] JS：ES Module 导入导出
来源：http://dali.kuanghao11.cn/Article/details/gthqseozob.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtelqxoiyz.html

[U84] JS：CommonJS 写法
来源：http://dali.smart0.xyz/Article/details/gtmbuwymst.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tanke756.top/Article/details/gtfgsbbcay.html

[U85] JS：可选链
来源：http://dali.ivvv.top/Article/details/gtxlsecyxu.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gtczftqjwx.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtrcsmemrq.html

a ?? b
来源：http://dali.meibo888.top/Article/details/gtprrieged.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gthsrsynrw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhixingplan.top/Article/details/gtjoqmpkyx.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtortbkqwq.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwltabuc.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gtyuqbqdgy.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtbjvxdzyv.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gtdarirzzx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtgymiyxzh.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtxektibvl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ivvv.top/Article/details/gtwmalmyuq.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gtebzseoii.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gteyalbbcm.html

[U93] JS：模板字符串
来源：http://dali.zhongyouzk.top/Article/details/gtzzvnoirv.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gtagmlnhgl.html

[U94] JS：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtnkkpqgrn.html

const double = x => x * 2;
来源：http://dali.xziqi.cn/Article/details/gtzepokkfr.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gtmjoltgil.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gtohosaedf.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258.top/Article/details/gtftarzpou.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtedveirwf.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gtbdhrvakp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtvwwornnr.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtbdvhbdnj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gttmcsqbrr.html

[U99] JS：事件监听
来源：http://dali.ydzc1.top/Article/details/gtodhvttfl.html

el.addEventListener("click", e => {})
来源：http://dali.yangfankeji.com/Article/details/gtyswivgdl.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtwahaiino.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtftehyvfu.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtjzrmjfzi.html

el.classList.toggle("active")
来源：http://dali.hongshengwenyu.top/Article/details/gtnlwqsofp.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gtqzatkcvr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrjiegmf.html

[U103] JS：定时器
来源：http://dali.tian-w.cn/Article/details/gtgftkvimi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gtfguopdza.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gtuegetbvv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtjneoftdn.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gtuwlooljo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gtsuhopzyv.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gtantpjfga.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gtxaiuknrg.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gtqxzfhyln.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gtttwvqjas.html

[U108] JS：随机整数
来源：http://dali.sweek.top/Article/details/gtljtryfar.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtnarhdvlg.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gtrjqqswqz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtzpgmrwyh.html

[U110] JS：数组分块
来源：http://dali.pengpengdd.cyou/Article/details/gtlfdldcop.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gthbtzexes.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtoaqjprlw.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrscngur.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gtbhusmnln.html

"7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtixuvvumt.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqdkopbw.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtmnuwclwu.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gtufucehlh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtevlguegt.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtekrknwed.html

crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtrvfbbbmf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gtgnqprckn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gtnqkjthzk.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtplkoxvfr.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtjgblnuml.html

[U118] JS：开发服务器
来源：http://dali.feifeiyinyue.top/Article/details/gtpnzjcmcj.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gtlrphliiz.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gtdueqacms.html

npx vite build
来源：http://dali.bjfxy.top/Article/details/gtudkbtjbq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gtbiadblrs.html

import.meta.env.VITE_API_URL
来源：http://dali.pengpengdd.cyou/Article/details/gtpvmxkija.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgrzhzada.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gtbbegedpg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtilceybup.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemoylidc.html

Python ......... 252
来源：http://dali.zhixingplan.top/Article/details/gtdjpbenew.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gtrqxsbujv.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gtopwbxrhl.html

TypeScript ..... 212
来源：http://dali.zhoulong.xyz/Article/details/gtvtohqhvz.html

Java ........... 212
来源：http://dali.zycfv.cn/Article/details/gtzurfoipi.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtdorifpwp.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtkgtviifd.html

C# ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtjbhihvbk.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gttswxtpze.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gtjucluxcp.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gtdsfocsnv.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gtfrifghqj.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjylpaskk.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtygqmihoa.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gtcqewuhet.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtqatwpsnr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gtcttobfjn.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtabwfdfgj.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtfyvhshuu.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gtjhdllqqi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gthpqqdomm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtqqhhbkkr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtgkmbhumr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gtesgkauge.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenzaomai.com/Article/details/gtrejhebfk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gtthdqavyg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtidphwxsx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gttyhknjdu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtrcmdwuim.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtbumsfnqk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkupgnavh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gteetolssx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gthgfgjuua.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtplmdhlyw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gtgixtpyjw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtynycaaac.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gtihoiuiyz.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtdxmdeddt.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gtukskmwtz.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gtkrjtxohi.html

U 高频实用片段                         120
来源：http://dali.gaohongyu789.top/Article/details/gtfhrhsjtd.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtnkcfaaac.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gtotfnugtr.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtqrqqemri.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gtafygsycy.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtucepxmsc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtcovkvqqb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gtjwrjznal.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.0kj1m.cn/Article/details/gtrarzmczd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gtzpdrdmqo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gtzvzygidw.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxegwrpz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxrnhwaoo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gtdsjdvvbg.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gtjxspzpne.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcwjzcexj.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gtyyyrbdrs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxoxexjb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gtrgvfpliq.html

SQL · Bash · C · C++
来源：http://dali.zdqjudy.top/Article/details/gtkmovuuzo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shuidangran.top/Article/details/gtnkxjchnh.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gtjvpyqfsp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ydzc1.top/Article/details/gtauhoeshw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.feifeiyinyue.top/Article/details/gtdfmhinbh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gtgrrpsuky.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jianghu66.top/Article/details/gtbkdojhpy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gtkytyqoya.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.birdmap.top/Article/details/gtntmjohzy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yvedp.cn/Article/details/gtluzdguuq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gtfrgbmqvc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.feifeiyinyue.top/Article/details/gtxymyapgq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zdqjudy.top/Article/details/gtsnuchzrv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnfeyacu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dianchejie.cn/Article/details/gtxjpaevwa.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtxvqkfrhg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.meibo888.top/Article/details/gtuoeovinz.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtuphhhavu.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtcydglpzr.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtemxpreog.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gthiqfqhpv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtfomshskj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtlpvqydqt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gtoukljrer.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.vqdsnc.cn/Article/details/gtwrgtpabu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj20258.top/Article/details/gthinvchom.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtzgxwdofu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtmimiradc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtsirhjsrw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gtljhhxflq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtpnakwhws.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtnhrjpvcj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtydmaalxk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtpxstnwsu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj202588.top/Article/details/gthlhiftil.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gttxonxvqi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtoptgxzzl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtdyhpmkej.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pycfn.com/Article/details/gtvyahahrt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtldxipsna.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtzhoizooy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxqadeytq.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gtwvglkvmu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnengrbfn.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gtyuagqgee.html

Py:   print("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gtzmzbcdnj.html

PHP:  echo "Hello, World!";
来源：http://dali.gaohongyu789.top/Article/details/gtpgehveit.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtnzvyakpt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.meibo888.top/Article/details/gtehnqdrxv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gtzmejodbf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtrvmawixo.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gtnrudmqwq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtqcejpwta.html

[A02] 变量声明与赋值
来源：http://dali.gotoacloud.top/Article/details/gtcpqvpvem.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gtlpynysgw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtutiiorxs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtpeardlrk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnqzz.top/Article/details/gtwhhomwsn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtydvnzdhd.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gtebgefwzb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yangfankeji.com/Article/details/gtfrhrpiyv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gtfawsfkkb.html

[A03] 常量定义
来源：http://dali.andypj.xyz/Article/details/gtjyrgepkm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gtbaykrqum.html

PHP:  const PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtzijhosbp.html

JS:   const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtzxatbeiw.html

TS:   const PI: number = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtqesjjscq.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtpduzcwdd.html

Go:   const PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gttxqicfxl.html

Ruby: PI = 3.14159
来源：http://dali.xuanzx.com/Article/details/gtmfyormxw.html

C#:   const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtfppkamwr.html

[A04] 判断变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtbqqqjkio.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangdashe.top/Article/details/gtvprtdcbg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhixingplan.top/Article/details/gtnudhmjuq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtzfffnkzz.html

TS:   typeof x; x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaubnhkjx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangdashe.top/Article/details/gtjbjaoqax.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.mhx1999.top/Article/details/gtsdqhxjjs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gtiktsyzea.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinghuilouyu.cn/Article/details/gtvejbdtsd.html

[A05] 整数除法与取模
来源：http://dali.kuanghao11.cn/Article/details/gtqhekedsv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shuidangran.top/Article/details/gtboxmecsp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtvwwdndwx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtqqerrpxl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtxpfbzkbi.html

Java: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtwcrholey.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxaxhcis.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtakfnzozc.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gttczdyugo.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gtzdghfntl.html

Py:   int("42"); float("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtjnrjsvop.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmfdppff.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gtublldtch.html


<!-- 参考信息 -->