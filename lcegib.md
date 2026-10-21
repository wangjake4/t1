代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gtdktmjsjk.html

$v = $a ?? $b ?? "default";
来源：http://dali.xziqi.cn/Article/details/gtjjpioaay.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gtdivhodcp.html

$obj?->method()
来源：http://dali.0kj1m.cn/Article/details/gthlslhcbj.html

[U55] PHP：match 表达式
来源：http://dali.hfpthk.cn/Article/details/gtxzsgkhdh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtanklfhzd.html

[U56] PHP：命名参数
来源：http://dali.fengsongda.top/Article/details/gtmphonuzj.html

f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlewrvdio.html

[U57] PHP：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtjjtmifwf.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gtidnuxwgs.html

[U58] PHP：数组三件套
来源：http://dali.hnqzz.top/Article/details/gtnzofsrde.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjwvlqhb.html

[U59] PHP：自定义排序
来源：http://dali.hnqzz.top/Article/details/gtvreytzwp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gthyxzscxv.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gthkopafdl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gtnczwiibj.html

[U61] PHP：正则
来源：http://dali.yangfankeji.com/Article/details/gtslatgikh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtxatsgkga.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtemrfzqam.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtfvlzgmun.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtznegicgh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhongyouzk.top/Article/details/gtmdjkaqof.html

[U64] PHP：目录遍历
来源：http://dali.yj20258888.top/Article/details/gtnsmtvxad.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gthakkzofi.html

[U65] PHP：会话
来源：http://dali.gaohongyu789.top/Article/details/gtevlxowtk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtqqycirqf.html

[U66] PHP：设置 Cookie
来源：http://dali.tanke756.top/Article/details/gtlqcnezhh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gtihztcucz.html

[U67] PHP：处理文件上传
来源：http://dali.cheryme.top/Article/details/gtrofzolhq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gtuldtzemj.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrygtsubs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gtuokkmash.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gtcwpzqgip.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxinkj.top/Article/details/gtlcjcfnlx.html

[U70] PHP：PDO 事务
来源：http://dali.bjfxy.top/Article/details/gtuewiamhz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gthltncjca.html

[U71] PHP：抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtjcmfuxoa.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gtsrnqnyxh.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gticjhegpu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj202588.top/Article/details/gtttjzqoku.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gtavtbhfxd.html

parse_ini_file("config.ini", true)
来源：http://dali.ppjwa.cn/Article/details/gtsdxkofkb.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gthxkjdlbh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gthwusxhek.html

[U75] PHP：依赖注入
来源：http://dali.daria6918.cn/Article/details/gtduuqnrfy.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtacjthfnf.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gtwrtxcuia.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.redwolf501.top/Article/details/gtmcgukmib.html

[U77] PHP：模板渲染
来源：http://dali.mhx1999.top/Article/details/gtmcsqxelf.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtcdbjddru.html

[U78] PHP：单元测试
来源：http://dali.iojbl.cn/Article/details/gthtktemik.html

composer require --dev phpunit/phpunit
来源：http://dali.feifeiyinyue.top/Article/details/gttapdzebu.html

[U79] PHP：静态分析
来源：http://dali.hywenlv.cn/Article/details/gtfycyarix.html

composer require --dev phpstan/phpstan
来源：http://dali.zhixingplan.top/Article/details/gtenxrenrr.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtgttgbijr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cashguo.top/Article/details/gtbvohojds.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gteerchgor.html

npm init -y;  npm i express
来源：http://dali.ybcxt.top/Article/details/gttutjiplt.html

[U82] JS：package.json 脚本
来源：http://dali.0kj1m.cn/Article/details/gtdokzcqee.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttivhtxxo.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gtwsbzospn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtjyabfdhu.html

[U84] JS：CommonJS 写法
来源：http://dali.xinyue.icu/Article/details/gttdqxdpvf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.redwolf501.top/Article/details/gtuyjyvfom.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gtglkfelvg.html

a?.b?.c
来源：http://dali.redwolf501.top/Article/details/gtjgbmepyx.html

[U86] JS：空值合并
来源：http://dali.zhoulong.xyz/Article/details/gtzjtybexv.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gtwyjacjfy.html

[U87] JS：解构默认值
来源：http://dali.tian-w.cn/Article/details/gtnnjkaeon.html

const { a = 1, b = 2 } = obj;
来源：http://dali.daria6918.cn/Article/details/gtrxdlyvbv.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmtzjxlu.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gtjdjshgej.html

[U89] JS：数组去重
来源：http://dali.gotoacloud.top/Article/details/gtdytpotog.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtiimmlvfw.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gtuhkgovsd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtrrnzguco.html

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gtisdbdrns.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gtkhhflayh.html

[U92] JS：深拷贝
来源：http://dali.fengsongda.top/Article/details/gtkqczidkl.html

structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtfzenehok.html

[U93] JS：模板字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtitmdsdff.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gtowomjlbl.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtaqjywhra.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gtkhltcujy.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgdbdnhf.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gtmjvxmxog.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gtwrpcxqfv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtirepecgw.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtaomqeofl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtjxkiwmhq.html

[U98] JS：fetch 带 JSON
来源：http://dali.havefunace.top/Article/details/gtrqtpybqs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhuocjsv.html

[U99] JS：事件监听
来源：http://dali.guowangkeji.top/Article/details/gtibkkgcym.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gtsjjobprv.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtktkfzflu.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtqgezxyns.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gtpafdtgdz.html

el.classList.toggle("active")
来源：http://dali.nanxinkj.top/Article/details/gtqgyxnbjc.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gtyhpuomee.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shzxlz.cn/Article/details/gtawyzybux.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gtknqupzzh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gtwuwwvkqt.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtapwpxfbg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtmtemgpro.html

[U105] JS：节流
来源：http://dali.wangshuangyany.cn/Article/details/gtanimfmvr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtaeycmtsx.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehmnjtms.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gtcgmbkmoi.html

[U107] JS：数字千分位
来源：http://dali.fengsongda.top/Article/details/gtuvonjmpk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtztjchbrx.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gtuoguveed.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokhboilg.html

[U109] JS：数组分组
来源：http://dali.jiagoushi.top/Article/details/gtjaapebth.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtunykvbcg.html

[U110] JS：数组分块
来源：http://dali.gogol.net.cn/Article/details/gtcpteixqs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fzhhl.top/Article/details/gtqicimacq.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtuhuaetfy.html

new Map(Object.entries(obj))
来源：http://dali.yuanzhike.top/Article/details/gtsivwosmk.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gttezxtnyx.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtalzpstzv.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtrsjzsbnw.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtiwhbrflr.html

[U114] JS：JSON 深比较
来源：http://dali.shzxlz.cn/Article/details/gtswywclhb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtqkxybxwt.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gtgmrijqdb.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchiexgky.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmtbyjxj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdkhjfhex.html

[U117] JS：单元测试
来源：http://dali.tanke756.top/Article/details/gtzbmjnoyw.html

npm i -D vitest;  npx vitest
来源：http://dali.dashuyun.cn/Article/details/gtokdajlii.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtlttarmkf.html

npm i -D vite;  npx vite
来源：http://dali.ivvv.top/Article/details/gtfayjnnla.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnbhwpmr.html

npx vite build
来源：http://dali.cheryme.top/Article/details/gtzfactllc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gtgpevtqjg.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gtzjwxjzzz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthhvoqnhq.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtqrhaknlp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvbxagkud.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gtcjxazhwp.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gtllfnggqt.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioettpwk.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gtqjilfctb.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gtzycbvbtd.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtbtiavsuz.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gtyzfftzln.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtxvazlohs.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gtwcujbxwi.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtjsogeros.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gtvixriabo.html

SQL ............ 90
来源：http://dali.nanxinkj.top/Article/details/gttwnjcfut.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gtllrutxci.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuyrvrbd.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtujqnpvzm.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gtlueknsik.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gtclwncsse.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gtcaggjzye.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtkyerqgis.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gtaxfatlad.html

按章节统计：
来源：http://dali.hywenlv.cn/Article/details/gtuorqmcge.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gttgefkmwu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtkqompnto.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtoxzdwjxh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtinjujkkn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gtnzsmzluv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfvnnmhs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtmoaibfgd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtymifywwu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gttwbegjwf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gttocwtvgp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtyegsniig.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtjsqvyrdm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtwtylzlbt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gtznnpwvvv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cashguo.top/Article/details/gtualehmtp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtqpdsguhn.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gtbemsaxmm.html

R Bash 专题                             80
来源：http://dali.316326.xyz/Article/details/gtrvtunwkk.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gthyfhooro.html

T 其他语言补充                          60
来源：http://dali.jinqigfzy.top/Article/details/gtqraukpvp.html

U 高频实用片段                         120
来源：http://dali.zycfv.cn/Article/details/gthlbcpviy.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtfvdfweoa.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gtobyxeloj.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtgludtqom.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gthgckflup.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtrrterhgs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.0kj1m.cn/Article/details/gttsbnqoes.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gtavwwmqhg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hysaishi.cn/Article/details/gtppzbfzhk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemqdlroa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.haohaochexian.top/Article/details/gtdxdkritq.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gtkadpttqd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzawsdqex.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gtefyyuxbt.html

Common Programming Examples Cheat Book
来源：http://dali.xuetiantiany.cn/Article/details/gtucerssiz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjxspkfrq.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtdgzpvlyi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gtigrmiqkq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigufen.top/Article/details/gtdkcgzlxs.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtsrrykool.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gthmclixtb.html

【使用说明】
来源：http://dali.yj20258.top/Article/details/gtaljviecx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gtpfcpquln.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gtuxqqgtlv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ehwqpu.com/Article/details/gtovdratbe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtbjirnsuy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.9152youxi.cn/Article/details/gtkdzwzvvh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yonumen.top/Article/details/gtbjqccypj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtzxjinnmb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gtoaktxnvj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtsbminwpi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangshuangyany.cn/Article/details/gtiyiqdsmw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sxryk.cn/Article/details/gtzbowjdai.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.bjfxy.top/Article/details/gtihpgkbpo.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gtocclasit.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gtwfywpwxp.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtvhtptofb.html

目  录
来源：http://dali.havefunace.top/Article/details/gtiwhqulmy.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtpbumgjke.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtgjrofemi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtceyumogd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtynlkklin.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtiaxszxcn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.guannengcc.top/Article/details/gtwmiexkqz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ehwqpu.com/Article/details/gtxmuowyen.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtffoksisl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtpfkpwjuu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtpwldsqzm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtxvjzndur.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtnlgpffrm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gttsvscmyz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtknoxowob.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtwleazvsr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gtbpfnxmnl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtehnhcaln.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gtwjmuzcsu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtpmvfhlro.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daria6918.cn/Article/details/gturkmltkl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtaommomwk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtowmhemyu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbavntzyo.html

A. 基础语法与类型
来源：http://dali.yonumen.top/Article/details/gtkhpztbfl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzymsfnxm.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtpmsyfmwd.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvypvrqop.html

PHP:  echo "Hello, World!";
来源：http://dali.c1oappe.top/Article/details/gtdrowmrcz.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtirrdcwqf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gtfiytkztu.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtmepmomar.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gtlsvsfbsr.html

Ruby: puts "Hello, World!"
来源：http://dali.sxryk.cn/Article/details/gtaagvwhzj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtyincqxvx.html

[A02] 变量声明与赋值
来源：http://dali.316326.xyz/Article/details/gtgxqmcgcb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gtqdonpubz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtuqkswhyc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtwxsycahh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmqhebui.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtptqftkpn.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gtebwzktbe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgmrbmsy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtrgevymkm.html

[A03] 常量定义
来源：http://dali.cheryme.top/Article/details/gtyuofcwzp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.316326.xyz/Article/details/gtkctpagwu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gttzvmtwtm.html

JS:   const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtnlzaqeiq.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtrfpfiqzg.html

Java: static final double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtsusdvpio.html

Go:   const PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtvjukmznw.html

Ruby: PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gtoslwnsbg.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gttzdzegdn.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjrxhzwyb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gtcbwuuqes.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.kuanghao11.cn/Article/details/gtxbqcfvzl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.c1oappe.top/Article/details/gtchldmzpk.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtwdxtputy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gtuwsmlnvr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtyfohmork.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gtusdxoxfo.html

C#:   x.GetType().Name; x is int
来源：http://dali.havefunace.top/Article/details/gtcsssqtjn.html

[A05] 整数除法与取模
来源：http://dali.tianlin.xyz/Article/details/gtzapaehvl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhengqikj.top/Article/details/gtonsbsjdm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtdtezzgtw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtigegnnsw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtlhrmndlr.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtdhetsook.html

Go:   7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtatllbmcr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtforulftw.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtxccgxm.html

[A06] 字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtwugoudli.html

Py:   int("42"); float("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtmzoekvrb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhoulong.xyz/Article/details/gtxaibwtfp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gtvtksgiir.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtzhssdcty.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gteuyfyvkp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aizwys.cn/Article/details/gthdegkakz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.9152youxi.cn/Article/details/gtvixkodxb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtgyjxkqba.html

[A07] 数字转字符串
来源：http://dali.sweek.top/Article/details/gtvxtjxxwi.html

Py:   str(42)
来源：http://dali.gogol.net.cn/Article/details/gtfusgxsvh.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuxming.cn/Article/details/gtbmabeyev.html


<!-- 参考信息 -->