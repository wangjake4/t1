代发 wailian999

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwtddama.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtvybmvjvu.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtkqvyffoc.html

public function __construct(private int $id) {}
来源：http://dali.sweek.top/Article/details/gtvoiexaxk.html

[U51] PHP：数组解构
来源：http://dali.fengsongda.top/Article/details/gtcnwriazs.html

[$a, $b] = $arr;
来源：http://dali.guowangkeji.top/Article/details/gtxmrudbxp.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtsqdikirl.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoizgtgp.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gtqxmtnnem.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenlongwang.top/Article/details/gtjpgopdje.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gtldmhwesr.html

$obj?->method()
来源：http://dali.svipenyu.cn/Article/details/gtmakcadfl.html

[U55] PHP：match 表达式
来源：http://dali.jiagoushi.top/Article/details/gtpsrzesib.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtkexmckqg.html

[U56] PHP：命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtjqjiialt.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtsdcnfrme.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gtjaorbeyn.html

"值: {$a}"
来源：http://dali.sweek.top/Article/details/gtfjuuuyqy.html

[U58] PHP：数组三件套
来源：http://dali.daria6918.cn/Article/details/gttlhxizse.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.mhx1999.top/Article/details/gtuysobuhu.html

[U59] PHP：自定义排序
来源：http://dali.vqdsnc.cn/Article/details/gtjesinqmt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gthcbsqrlt.html

[U60] PHP：JSON 编解码
来源：http://dali.havefunace.top/Article/details/gtwqkmbhoc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jlsjyb.cn/Article/details/gtaxammmyg.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gtjwfmpwnx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtqyinxato.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gtdjlnvjiz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gtlanbdosx.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gtjpzcoebm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.smart0.xyz/Article/details/gtnazafloc.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtnjjnpxwx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sufxvd.cn/Article/details/gtmguckefu.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gtqpvaajvm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtsqlbvulg.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtkmobzywz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gtwjbimnan.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyrtnhxe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gtedxtzxnm.html

[U68] PHP：PDO 连接
来源：http://dali.aibaodan.cn/Article/details/gtnybiareo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtshtybhxb.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gtbrybomyx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shzxlz.cn/Article/details/gtdyvwoihj.html

[U70] PHP：PDO 事务
来源：http://dali.iojbl.cn/Article/details/gtmdmulhvu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtcjneufqr.html

[U71] PHP：抛出异常
来源：http://dali.xziqi.cn/Article/details/gtvuvndhar.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gtrmrgtklr.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gtmghvwdrq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aizwys.cn/Article/details/gtqgexxzsd.html

[U73] PHP：读取 ini 配置
来源：http://dali.bjfxy.top/Article/details/gtmkggnngx.html

parse_ini_file("config.ini", true)
来源：http://dali.yueranfly.top/Article/details/gtgqplayux.html

[U74] PHP：读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gteahcenaw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gtiqkciyus.html

[U75] PHP：依赖注入
来源：http://dali.cashguo.top/Article/details/gtbikbqdvm.html

composer require psr/container
来源：http://dali.hysaishi.cn/Article/details/gtnhvvkgfl.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gtggrgaczp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtvisujjms.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gtvrucvjcz.html

composer require twig/twig
来源：http://dali.cashguo.top/Article/details/gtkwaspxaf.html

[U78] PHP：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtptusvvcq.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtzxryoqvt.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gthojnuozx.html

composer require --dev phpstan/phpstan
来源：http://dali.cdnleiting.top/Article/details/gtnblhkpcz.html

[U80] PHP：代码规范修复
来源：http://dali.hysaishi.cn/Article/details/gtdamfoqwg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sxryk.cn/Article/details/gtmmoikmew.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgxupgtm.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gtxaeeqand.html

[U82] JS：package.json 脚本
来源：http://dali.shuidangran.top/Article/details/gtyjeslhrz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtnahbkhwp.html

[U83] JS：ES Module 导入导出
来源：http://dali.yongpay.top/Article/details/gtwhgjzhju.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtacmdsjad.html

[U84] JS：CommonJS 写法
来源：http://dali.hammf.cn/Article/details/gtqjekmmbv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jyoumei.cn/Article/details/gtjyvfdsai.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtctlpsyzc.html

a?.b?.c
来源：http://dali.chenjidiqi.icu/Article/details/gtcjtudqld.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gtmgivjuug.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gtwdeianvo.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtsxasgsrr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zdqjudy.top/Article/details/gtealpymgr.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gthuyjlecu.html

{ ...a, ...b }
来源：http://dali.shuidangran.top/Article/details/gtyoolwqkl.html

[U89] JS：数组去重
来源：http://dali.zhixingplan.top/Article/details/gtdifssyar.html

[...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtsrfpfkvl.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gtmujbrfut.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gthjoicafj.html

[U91] JS：对象键值遍历
来源：http://dali.yvedp.cn/Article/details/gtekziflcb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gtrumfuupo.html

[U92] JS：深拷贝
来源：http://dali.hfpthk.cn/Article/details/gtkppcvnus.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtvwbrtznx.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gtwsjbtgqn.html

`共 ${n} 条`
来源：http://dali.hnqzz.top/Article/details/gtvyogwelr.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtjibjsmaq.html

const double = x => x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtnqeoqhbh.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gtnaaxpduk.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrfjpqpk.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gtlzjxhjww.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtqurgcpgm.html

[U97] JS：并发请求
来源：http://dali.tianlin.xyz/Article/details/gtcdbrodrm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtcwdrbnjo.html

[U98] JS：fetch 带 JSON
来源：http://dali.cheryme.top/Article/details/gtzotqbyav.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gtiqmjgvus.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gtqtvbrtwt.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gtustnnlxe.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtvivdicxk.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggkkvaoo.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtsdbeljha.html

el.classList.toggle("active")
来源：http://dali.daxiang520.top/Article/details/gtzifyqegt.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gttnubjcnt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuetiantiany.cn/Article/details/gtxzgvlbvb.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtajyjsmql.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhoulong.xyz/Article/details/gtupgwriol.html

[U104] JS：防抖
来源：http://dali.cqqwz.cn/Article/details/gtciwerahh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtkqldkjuy.html

[U105] JS：节流
来源：http://dali.sxryk.cn/Article/details/gtfswzcjkk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gtweqljcyz.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtwruuvnwq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jlsjyb.cn/Article/details/gtqabjtqle.html

[U107] JS：数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtaiezdfdt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtmhtwlfih.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtoztucvwk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gtmkxxxsjy.html

[U109] JS：数组分组
来源：http://dali.pengpengdd.cyou/Article/details/gtubxqtnqo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterriutlr.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtdwoetjkg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gtehfiwvgf.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gtzievtfqg.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gtqgodawdq.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gtnnnifnve.html

"7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtyjupwapq.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtubwfbuin.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtzzzpqsup.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gtwmkewuhc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtfmiuiaxr.html

[U115] JS：生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtdrbdphlk.html

crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtjugslpfb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tanke756.top/Article/details/gtrvpxnhuw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtxfblzydi.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gttstyordb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gtrnqlbggj.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gtkovhgdfq.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtrtqrkxyu.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gtyeusitai.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gtbfslqhyw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gttcwhfnrt.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gtqkzyxisw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthrcrrvdp.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gttkohjwjz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihferguv.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtjxsjgslp.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gtbovnokfc.html

PHP ............ 252
来源：http://dali.shuidangran.top/Article/details/gtdcdlbkdq.html

JavaScript ..... 252
来源：http://dali.9152youxi.cn/Article/details/gtqpvrtfqo.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gtynylsiyd.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtbiobkflu.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gtvkawrntd.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gtazdwokca.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekwbiuqm.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gttswjlkvd.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gtnbtqotcb.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtzbcxmzld.html

Bash ........... 80
来源：http://dali.xinyue.icu/Article/details/gtxaqpvtcy.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gtmvjdsntk.html

Swift .......... 15
来源：http://dali.sysykeji.top/Article/details/gtekervdow.html

Lua ............ 10
来源：http://dali.zhoulong.xyz/Article/details/gtpxeckjnb.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtmocpkpvn.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrwnonol.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtpjyjbovx.html

合计 ........... 2106 条
来源：http://dali.yvedp.cn/Article/details/gtrpuiigdu.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gtmofhlkqn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtzygkwhoh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtlqcdomfg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtlknnkstl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtmwpawfpe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gthxbztzog.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtcbmwsnbx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtzkenmhpz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtfdupqwzj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtcsqpwkfc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gthxzxjgbi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtqympaurc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gthezksein.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtlqvuruoz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gttqugkmiy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gthgsvnbla.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtafbocvhc.html

Q SQL 专题                              90
来源：http://dali.zhengqikj.top/Article/details/gtlbcitxui.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gtayklpqru.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtovdlsxdz.html

T 其他语言补充                          60
来源：http://dali.c1oappe.top/Article/details/gttgmqitpu.html

U 高频实用片段                         120
来源：http://dali.hysaishi.cn/Article/details/gtmmdcfcic.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtctzrilyd.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gtyrbfplnt.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtndlqcyvp.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwilvlhw.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtvvlqmldf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtdysqnhsb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigfzy.top/Article/details/gtrmcuvcyi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxinkj.top/Article/details/gtbwuwggra.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfzrlkwe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.haohaochexian.top/Article/details/gthfayuclb.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gtgyciagwd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtndjiidfr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtqatnfggw.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gtonmsdval.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkuzxlkgd.html

【收录内容】
来源：http://dali.redwolf501.top/Article/details/gtmshyllqb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gtaizkhptu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.mhx1999.top/Article/details/gtaoianuba.html

SQL · Bash · C · C++
来源：http://dali.jinqigfzy.top/Article/details/gttyhxiuei.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenlongwang.top/Article/details/gtbqxvjvid.html

【使用说明】
来源：http://dali.yuxming.cn/Article/details/gttlucexef.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenjidiqi.icu/Article/details/gtjlbqytgw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtewjlzfiy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhongyouzk.top/Article/details/gtsojcgzmb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgfzy.top/Article/details/gtnhrehcij.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtycjygvuv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.iojbl.cn/Article/details/gtikdeviff.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnqzz.top/Article/details/gtulspfdgm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gtzfcjjqja.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gtsedalhln.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.0kj1m.cn/Article/details/gtydgwayrh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gtdsgsaaqr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gtqbwnfjym.html

【文件统计】
来源：http://dali.ivvv.top/Article/details/gtkjcuaqfc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.haohaochexian.top/Article/details/gtckduggkq.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtdwsqutcr.html

目  录
来源：http://dali.aizwys.cn/Article/details/gttwxoiqzg.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtbxfxfgdr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtcqrjswyq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gthpnpfgik.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtbzofecnj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gtnrsuwszf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cqqwz.cn/Article/details/gtmngduzka.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzpxquau.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtjdpfdvew.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtvayuavvn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtmbragfen.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtqwgrlxml.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gteryzlezs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtvbyjdxxj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtesdphjee.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtglfivoqk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.quarkkingdee.top/Article/details/gtjsugfpce.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtuocgiant.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdenytyn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtxaiilwqj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxinkj.top/Article/details/gtdobmmlti.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtiaubepik.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtlunpalxd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtodudawmq.html

A. 基础语法与类型
来源：http://dali.sweek.top/Article/details/gtudshlyys.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtahlmavtc.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gtrnowwttq.html

Py:   print("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gtyybsukjc.html

PHP:  echo "Hello, World!";
来源：http://dali.sufxvd.cn/Article/details/gtpwpicabs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gtdsygdhri.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhengqikj.top/Article/details/gtvjqgkdst.html

Java: System.out.println("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtmzmdfplt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtuiebbdum.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gtgsavmjqx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtaceqycfl.html

[A02] 变量声明与赋值
来源：http://dali.daria6918.cn/Article/details/gtmqhpwyna.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nwbrower.top/Article/details/gtqngpttax.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtlfsjjlet.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtmgwjxmfm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtaknqzhoo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtelypmxgq.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gtmnohyags.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gtdpvjvoit.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtkrhmzvac.html

[A03] 常量定义
来源：http://dali.ydzc1.top/Article/details/gtbvnhlhyv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigufen.top/Article/details/gtnzqanwlg.html

PHP:  const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtoauqcxip.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtnhsppgrn.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtnirbgugg.html

Java: static final double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtchcgvnms.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtxghtqhrg.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtzymdqqsw.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtzlbxqlsw.html

[A04] 判断变量类型
来源：http://dali.mhx1999.top/Article/details/gtsnjeardi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gtcdxfankr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhiwuduotai.top/Article/details/gtswizpxzk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gtnfgzbbxy.html

TS:   typeof x; x instanceof Date
来源：http://dali.sxryk.cn/Article/details/gtkltmjyao.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pycfn.com/Article/details/gtztjynvdl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gtxfkovqrg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gtvmdwioim.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhongyouzk.top/Article/details/gtupsrzlld.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gtymxtgtcr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtmfiibxdh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtdvcxwlrg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtsjcwmkei.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtapnwbhuq.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtozbujofx.html

Go:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtslqezenn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtjhdgqesz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtrphylgns.html

[A06] 字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtqzanhfpp.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gtswwcyjyg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zycfv.cn/Article/details/gtpsbxufrr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxlmqxgz.html


<!-- 参考信息 -->