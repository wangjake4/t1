代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.sysykeji.top/Article/details/gtzrcksyne.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtaogpgxmn.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gteeaermgh.html

f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtefapecmp.html

[U57] PHP：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtedvnbfov.html

"值: {$a}"
来源：http://dali.pycfn.com/Article/details/gtlgcemfin.html

[U58] PHP：数组三件套
来源：http://dali.sxryk.cn/Article/details/gthsftgrwt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hfpthk.cn/Article/details/gthsmuvmzg.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtzurrqbfd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtfvamqtsz.html

[U60] PHP：JSON 编解码
来源：http://dali.meibo888.top/Article/details/gtmjylttfm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangdashe.top/Article/details/gtyqybblop.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gtbbjpzxbw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gticuqbxgw.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gtzkvpvprl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtawfvzrye.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtnvbnperf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hongshengwenyu.top/Article/details/gtoiejfils.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtujqouora.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gtyorwapup.html

[U65] PHP：会话
来源：http://dali.chenjidiqi.icu/Article/details/gtmfvjithk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gthkcgcvoy.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gtrziihadp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gtgdvknlzc.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gtrcaozsjs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfmfddbz.html

[U68] PHP：PDO 连接
来源：http://dali.xylfe.cn/Article/details/gtgdhpcagi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gtubeyhrsf.html

[U69] PHP：PDO 预处理
来源：http://dali.xinyue.icu/Article/details/gtjbfbwmnn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yueranfly.top/Article/details/gtahwedppx.html

[U70] PHP：PDO 事务
来源：http://dali.nwbrower.top/Article/details/gtdwjhdqnh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cqqwz.cn/Article/details/gtnnblifev.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gtrdufrbwj.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gtvygqdhgu.html

[U72] PHP：写错误日志
来源：http://dali.havefunace.top/Article/details/gtakxfoqpx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhiwuduotai.top/Article/details/gtyshdsbbd.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gtaehkpyog.html

parse_ini_file("config.ini", true)
来源：http://dali.ybcxt.top/Article/details/gtaxmvmydk.html

[U74] PHP：读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtnfqthfwe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gtzwijxeke.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gtiuewideu.html

composer require psr/container
来源：http://dali.316326.xyz/Article/details/gtxwkulkdn.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gttafduthq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gaohongyu789.top/Article/details/gttnwgrmbl.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gthzlobiyo.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gtihqpszmu.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtmzzbjewn.html

composer require --dev phpunit/phpunit
来源：http://dali.ivvv.top/Article/details/gtbzbggiow.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtbqnfcvlj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtiuxcxqda.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gtcpkegupp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gtuoafkufe.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtlyfdawqx.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gtccanlbpe.html

[U82] JS：package.json 脚本
来源：http://dali.gaohongyu789.top/Article/details/gtfixjuhcs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnqzz.top/Article/details/gtgnxunyls.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gtzeoeelry.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtxkjlyiyw.html

[U84] JS：CommonJS 写法
来源：http://dali.sxryk.cn/Article/details/gtyjmyywrx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.feifeiyinyue.top/Article/details/gttfulmivi.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gtgyqtmefx.html

a?.b?.c
来源：http://dali.shzxlz.cn/Article/details/gtesubsauk.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gtiqxfppaw.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtpqinwvcn.html

[U87] JS：解构默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbiieohd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgufenzy.top/Article/details/gtsqmnqwpe.html

[U88] JS：对象展开合并
来源：http://dali.fengsongda.top/Article/details/gtekjgkcmw.html

{ ...a, ...b }
来源：http://dali.aizwys.cn/Article/details/gtwclljppc.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gtzilxoaws.html

[...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtamxhcpyn.html

[U90] JS：数字数组排序
来源：http://dali.feifeiyinyue.top/Article/details/gtdpmfmlhl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtjxpvkuxh.html

[U91] JS：对象键值遍历
来源：http://dali.kuanghao11.cn/Article/details/gtpsalgrmg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gttlpxcvml.html

[U92] JS：深拷贝
来源：http://dali.ydzc1.top/Article/details/gtaegmtlei.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtxqjibjhx.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gttcyoqags.html

`共 ${n} 条`
来源：http://dali.jianghu66.top/Article/details/gtndcpdqrv.html

[U94] JS：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfykitmq.html

const double = x => x * 2;
来源：http://dali.fzhhl.top/Article/details/gtdrrjrgpf.html

[U95] JS：Promise 包装
来源：http://dali.9152youxi.cn/Article/details/gtumlbjpxh.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gtarituzqd.html

[U96] JS：async/await 与异常
来源：http://dali.daria6918.cn/Article/details/gtexpbtkrt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtvteksyaz.html

[U97] JS：并发请求
来源：http://dali.ydzc1.top/Article/details/gtgmttjrne.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtyxhfpacm.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtfnpwstyy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhongyouzk.top/Article/details/gtxxegtqxt.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenbywiyq.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgptqbdye.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtdptgrrqx.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtrhpkgqmx.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gtdwnkmhxl.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gtrfdywiyh.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtmocbrfpg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuxming.cn/Article/details/gtcjfjqroi.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtlvhbsikn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cdnleiting.top/Article/details/gtgayopbqc.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gtwhmlwxls.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtajopzpbh.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gtfgqcnyoz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtlbrimovr.html

[U106] JS：日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtzfrlwfjr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtummhsvoh.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtcghxnwkq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtxerikdgj.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gtksdijbyx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gteelkmhcw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gtpwlelakw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtmrapdoqv.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gtomrwoxnz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gtuzphgejk.html

[U111] JS：对象转 Map
来源：http://dali.birdmap.top/Article/details/gtiykaxjju.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkazbkes.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gthuzmrhlp.html

"7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaymaugm.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtnebgavbs.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtmgcnxpcs.html

[U114] JS：JSON 深比较
来源：http://dali.chenlongwang.top/Article/details/gtejednbqc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtorccxcmz.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtlhkcqrve.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtfwnbfoyt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtgppikmsv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gtaikkrxux.html

[U117] JS：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgrqpwdm.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gtjifmhpjx.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gtaehtlvku.html

npm i -D vite;  npx vite
来源：http://dali.hfpthk.cn/Article/details/gtnobpvwza.html

[U119] JS：生产构建
来源：http://dali.zycfv.cn/Article/details/gtoguafvjp.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gtsdemtzur.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gtqmnamzfx.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gtxiupwqgs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxghgesnz.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtcmuhsypy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlimlssja.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtxmzafrtb.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gtztddelwz.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrlrepxb.html

JavaScript ..... 252
来源：http://dali.sxryk.cn/Article/details/gtpklvnejr.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gtjijglltw.html

Java ........... 212
来源：http://dali.xinyue.icu/Article/details/gtcpibkykf.html

Go ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtojpcblxa.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gtbwatpvjo.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtrjeifver.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gtqcszdaxu.html

C++ ............ 30
来源：http://dali.cucudq.cn/Article/details/gtkjjpnzst.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gtbyqpadca.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gtonzilkdx.html

Kotlin ......... 15
来源：http://dali.sysykeji.top/Article/details/gtsdaeagud.html

Swift .......... 15
来源：http://dali.sysykeji.top/Article/details/gtqwmhtfsj.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtivaapdeh.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gtpydjomvn.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gtfqydfvxk.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtucbyqfsr.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gtpinimjys.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gteiyyojpo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtnaijpbhw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtrvjpgawq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtytsjubgz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtvnafbwjh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.vqdsnc.cn/Article/details/gtdzqribcp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtikyvcrhd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtnimwexnq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtehfruaqr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtwfhclkfl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gterytvtqg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtkfxpwqzv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtottodped.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtwymjvveu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gteukxkdyd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj202588.top/Article/details/gtbvpizash.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtcguerxzb.html

Q SQL 专题                              90
来源：http://dali.316326.xyz/Article/details/gtlfuqjiar.html

R Bash 专题                             80
来源：http://dali.zhongyouzk.top/Article/details/gtqtcmifjn.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gtlumqiemn.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gtwirxodbz.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gtvzrxopds.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gthrttabpg.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtdlyfnnfu.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtbhwnaxyu.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gtejidhgks.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtjiyikxtn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.meibo888.top/Article/details/gtgyorbrgj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nwbrower.top/Article/details/gtcqusonlz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gtpwbsufvz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gtfggcpwgd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtuqiylzrg.html

—— 文件结束 ——
来源：http://dali.aibaodan.cn/Article/details/gtaqexjbst.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfgdugnvi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gtnxjtwjua.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gtsabmgnxs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuginhqhd.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gtupplkxki.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gtwfhqsyld.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gtxvjscawe.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gtkmwpukbe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhengqikj.top/Article/details/gtjvxerwll.html

【使用说明】
来源：http://dali.snrcjt.cn/Article/details/gtpigwftqo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pengpengdd.cyou/Article/details/gtfpxrexjs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sufxvd.cn/Article/details/gtuermatdz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmcfhcmn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gtsgylgqvm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gtwoklazap.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gtqnvnzojm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yangfankeji.com/Article/details/gtzqzwwcgp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yanxiufei.cn/Article/details/gtdzbipsrd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shzxlz.cn/Article/details/gtkoyvqrlj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xinyue.icu/Article/details/gtuuytnphk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ehwqpu.com/Article/details/gtwivnfrfj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.0kj1m.cn/Article/details/gtxmmpzwki.html

【文件统计】
来源：http://dali.cashguo.top/Article/details/gtcnkztruo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gttykaygho.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwpwvpoj.html

目  录
来源：http://dali.gaohongyu789.top/Article/details/gtaovfhxxx.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtcfcarlgo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtyvhlkmbc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtzjuaihap.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtlejttosk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqezjiryi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cdnleiting.top/Article/details/gtdtdlyico.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gtszzrwzrb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtszerivmt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtrhttitfl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtoboqrftv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gtdamkkmtr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtalpokjgc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtbjfizphv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtaqqvafdf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtzysiagrg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.smart0.xyz/Article/details/gtijvdoajr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtgajolzta.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj202588.top/Article/details/gtvwsasmit.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gtiyieqfcd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shuidangran.top/Article/details/gtmqucudoj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtimfdrclx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapwkfgiy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsgzkpavx.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gttoqydbpi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbkqlnxj.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gtqszjnnsd.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtrbbeoutv.html

PHP:  echo "Hello, World!";
来源：http://dali.cqqwz.cn/Article/details/gtgdcyvxoh.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtymnathyw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jianghu66.top/Article/details/gtbumlytzq.html

Java: System.out.println("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gthqngypxn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtygzhadio.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gtugwqxxtw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtzeemyljc.html

[A02] 变量声明与赋值
来源：http://dali.ppjwa.cn/Article/details/gtmnutdkcl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangdashe.top/Article/details/gtsvculgbn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gthdpsqhko.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtcdwuxhkv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtiwprpuog.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtnvmrsbnx.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuetiantiany.cn/Article/details/gthixjfpol.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gtxzhmxrtb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtgdkzwlws.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gtoavgwodx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtvihsljxk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtqjlzwdhq.html

JS:   const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtkyuzihre.html

TS:   const PI: number = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtpeqdfjwb.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtqzphcuuq.html

Go:   const PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gtxyletdpx.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gticfsewgm.html

C#:   const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtfitlcpen.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtaeyntkdo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenzaomai.com/Article/details/gtpiuabtge.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzjmnyqba.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gtwklmgiiq.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtbnjafpis.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dianchejie.cn/Article/details/gteuktkbap.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gtuunwompo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhixingplan.top/Article/details/gtwiokeqmw.html

C#:   x.GetType().Name; x is int
来源：http://dali.yangfankeji.com/Article/details/gttfqnhaam.html

[A05] 整数除法与取模
来源：http://dali.0kj1m.cn/Article/details/gtheomtdkj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cashguo.top/Article/details/gtmqanhaqf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtdajrhswe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtlyqirixu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtxtlmorqo.html

Java: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gthuffuyii.html

Go:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtmufxtsah.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtcugfxjvo.html

C#:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtiuykmrwz.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtoismodfc.html

Py:   int("42"); float("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gtwajewham.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gotoacloud.top/Article/details/gtqrjldmjt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gtwxiswwty.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtsxqozine.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj202588.top/Article/details/gtazuszhtj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258.top/Article/details/gtuoospiwf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gtbmglycvm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtmzefysvq.html

[A07] 数字转字符串
来源：http://dali.sweek.top/Article/details/gtkbdodlyx.html

Py:   str(42)
来源：http://dali.yj20258888.top/Article/details/gtfdawanrd.html

PHP:  (string) 42; strval(42)
来源：http://dali.iojbl.cn/Article/details/gtfooatdvv.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtqxteipad.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtmhocpfvd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cashguo.top/Article/details/gtbxhxigxb.html

Go:   strconv.Itoa(42)
来源：http://dali.yueranfly.top/Article/details/gtaalsgcpl.html


<!-- 参考信息 -->