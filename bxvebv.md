代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gttueuaffv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtkolnucbg.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gtwoqahndz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gtnoerspoy.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtlcnzjmfw.html

int|string $id
来源：http://dali.ybcxt.top/Article/details/gthnfnycbr.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gtjplemtwr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gtyohokzah.html

[U49] PHP：只读属性
来源：http://dali.xylfe.cn/Article/details/gtmcetooxe.html

public readonly string $name
来源：http://dali.zhoulong.xyz/Article/details/gtgcdpeody.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gtquxlhamy.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gtmrttyckw.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnsnjwxr.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtnvjipdji.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtzzygmjmx.html

$double = fn($x) => $x * 2;
来源：http://dali.cheryme.top/Article/details/gtvrjvahbo.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhxlqgbt.html

$v = $a ?? $b ?? "default";
来源：http://dali.sufxvd.cn/Article/details/gtagnjmkrp.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrzvvfrf.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gtezwoyifj.html

[U55] PHP：match 表达式
来源：http://dali.tanke756.top/Article/details/gttwvlrmkd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gtwvweduel.html

[U56] PHP：命名参数
来源：http://dali.zycfv.cn/Article/details/gtvbnfnwof.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtwffbwqbh.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtkzgxzqaj.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gttifdalyd.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtqasppiat.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gtgzejjrvm.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtgvnvizxs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtaldqxmdd.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtnuzlvcuz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cdnleiting.top/Article/details/gtoqmzwjtf.html

[U61] PHP：正则
来源：http://dali.hywenlv.cn/Article/details/gtxzndnjsl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtgojhtyxd.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gtsmmfshum.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hywenlv.cn/Article/details/gtkccgwilu.html

[U63] PHP：文件读写
来源：http://dali.hfpthk.cn/Article/details/gtbkysejow.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.andypj.xyz/Article/details/gtnlqufvgq.html

[U64] PHP：目录遍历
来源：http://dali.yj20258.top/Article/details/gtlndlfaip.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgufenzy.top/Article/details/gtpgbolkvf.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtlckchdrl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtbzmtqwoi.html

[U66] PHP：设置 Cookie
来源：http://dali.hysaishi.cn/Article/details/gtmkgrxpou.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtimcjbrew.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtdmwrbohm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtethpyjxd.html

[U68] PHP：PDO 连接
来源：http://dali.redwolf501.top/Article/details/gtpgyozgsg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtquxpprkr.html

[U69] PHP：PDO 预处理
来源：http://dali.fzhhl.top/Article/details/gtbapehxff.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hywenlv.cn/Article/details/gtrcymbbtm.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gtgcexoycc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhongyouzk.top/Article/details/gtvutljtnr.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtvpheomjx.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangdashe.top/Article/details/gtefgdmpri.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gtqhzmvrre.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyvjvgkq.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayohgplq.html

parse_ini_file("config.ini", true)
来源：http://dali.ivvv.top/Article/details/gthkzjlqjt.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtyypbyhfj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj202588.top/Article/details/gtnvbdbgup.html

[U75] PHP：依赖注入
来源：http://dali.zhengqikj.top/Article/details/gtzwtyyfno.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtqegigvpx.html

[U76] PHP：简单路由
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeawgsdn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gthrgvxbdr.html

[U77] PHP：模板渲染
来源：http://dali.aibaodan.cn/Article/details/gtphrebeyi.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gtnvfvvuek.html

[U78] PHP：单元测试
来源：http://dali.sxryk.cn/Article/details/gtxaiqrynd.html

composer require --dev phpunit/phpunit
来源：http://dali.hnqzz.top/Article/details/gtdrcgquzg.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gtudlnhsyy.html

composer require --dev phpstan/phpstan
来源：http://dali.hnxiangtu.top/Article/details/gtrqipluut.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gtfpzodyqf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gthashddby.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gtiyqikqne.html

npm init -y;  npm i express
来源：http://dali.sweek.top/Article/details/gtucwyqaeg.html

[U82] JS：package.json 脚本
来源：http://dali.shzxlz.cn/Article/details/gttxxvmhap.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gtysohnbig.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gthwetzgtt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtdlefsjdz.html

[U84] JS：CommonJS 写法
来源：http://dali.daria6918.cn/Article/details/gtqczwyifh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gtomovfuuz.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gtbkwsnvey.html

a?.b?.c
来源：http://dali.ivvv.top/Article/details/gtmevfixqs.html

[U86] JS：空值合并
来源：http://dali.yangfankeji.com/Article/details/gtgpjcqead.html

a ?? b
来源：http://dali.meibo888.top/Article/details/gtnnqhgpcx.html

[U87] JS：解构默认值
来源：http://dali.jyoumei.cn/Article/details/gtowqqfdkv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gtfeybrdqe.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gtpncnhvor.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtfucnrcon.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gtpcqbgjyy.html

[...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtiislcxjt.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtzpemfxly.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtemjgzpqk.html

[U91] JS：对象键值遍历
来源：http://dali.gaohongyu789.top/Article/details/gtjmjdruae.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gtdkeopyab.html

[U92] JS：深拷贝
来源：http://dali.hywenlv.cn/Article/details/gtdgrcbtol.html

structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtiyxvhdde.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtsttaeike.html

`共 ${n} 条`
来源：http://dali.chenzaomai.com/Article/details/gtrushdotb.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzvwkzkr.html

const double = x => x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtvpleqwwn.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gtlofapxwt.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliqucqer.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gtpmnhviec.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gthqbczpjx.html

[U97] JS：并发请求
来源：http://dali.ehwqpu.com/Article/details/gtsrdibwcr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtgczyqkjr.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtmirehgwi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtstaqsmcj.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gtnlifigjb.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gttywiujpe.html

[U100] JS：DOM 查询
来源：http://dali.hfpthk.cn/Article/details/gtxvytnbkw.html

document.querySelector(".item")
来源：http://dali.hammf.cn/Article/details/gtnzwdhtga.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtwldkcdfy.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gtcjbicydo.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtjwymqdee.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuanzhike.top/Article/details/gtyjbxxazb.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gtqezsjqjh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gtqyojrlut.html

[U104] JS：防抖
来源：http://dali.tian-w.cn/Article/details/gtesvvahon.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtrramotmo.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtvavcwxua.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkjrqwpb.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtgghwrfss.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtfghdhlee.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtiwiejwth.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtkyzpyocn.html

[U108] JS：随机整数
来源：http://dali.bjfxy.top/Article/details/gtnxboojth.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiumzjyue.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtotljxxlj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlebphwse.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gterobkptb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gtcrzlnpqs.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuitvbct.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gtrnpqvapm.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gtfsqvtuhp.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtymjfrjvp.html

[U113] JS：正则替换全部
来源：http://dali.havefunace.top/Article/details/gtbmurrqxl.html

s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtpegzlmyj.html

[U114] JS：JSON 深比较
来源：http://dali.smart0.xyz/Article/details/gtpogkhhce.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtwsdgjler.html

[U115] JS：生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtcvllnotx.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtlubijyci.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.meibo888.top/Article/details/gtjdbxmpse.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gtwocbdhnz.html

[U117] JS：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gtytxvjxnh.html

npm i -D vitest;  npx vitest
来源：http://dali.zdqjudy.top/Article/details/gtokyrpmsb.html

[U118] JS：开发服务器
来源：http://dali.nwbrower.top/Article/details/gtvlnwuptt.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gtrljurjpe.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gtgoaqycvq.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtpgavpjvl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtfnjvhpzf.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gtemriypuq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlmvjdoej.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gtkpbmmqhs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthlenmbfx.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtcyiukdpz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gtjfnkdmij.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gtigwkviqx.html

JavaScript ..... 252
来源：http://dali.bjfxy.top/Article/details/gtrzntbris.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gtaiwljvvj.html

Java ........... 212
来源：http://dali.xinyue.icu/Article/details/gtpcabxmqu.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtwtxkhssa.html

Ruby ........... 212
来源：http://dali.bjfxy.top/Article/details/gttohddjhx.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtealwzlyp.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gtikqrsgkg.html

C++ ............ 30
来源：http://dali.zhixingplan.top/Article/details/gtxxjfqmsh.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtviujcmqh.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gtmfimsaxy.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gtzjtwzmsw.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gtotqljjhr.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gteahvuudy.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gtmmkltzey.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbmxnbbp.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtklubatnp.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gtyupgjsac.html

按章节统计：
来源：http://dali.xziqi.cn/Article/details/gtqazytkhs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtpewfsxpi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtknmabout.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtcqzqncde.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gthcgzvnin.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dashuyun.cn/Article/details/gtysthvduc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gthpngajui.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtzirqxacn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gteedaxpkj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gttxepfptl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtbjvkcazr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtppiqfbzw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtwrnrysgw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtutrywyyi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtywydexpf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gtelwstlwv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtwgiyqrel.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtsjsjbati.html

R Bash 专题                             80
来源：http://dali.zhongyouzk.top/Article/details/gtoexrvrjb.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gtomwqaffn.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlnelaip.html

U 高频实用片段                         120
来源：http://dali.hnxiangtu.top/Article/details/gtanzhmdwr.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtknpsbydx.html

合计                                  2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtvyiotitt.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtlovfysop.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtvlnytaup.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtankivwjh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ehwqpu.com/Article/details/gtczjdrncz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nwbrower.top/Article/details/gtpmmwbcch.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.9152youxi.cn/Article/details/gteasqdmdp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gtamppngmw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.haohaochexian.top/Article/details/gtotgqiiff.html

—— 文件结束 ——
来源：http://dali.yongpay.top/Article/details/gtwheturjo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwndkdrln.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258.top/Article/details/gtlyoiupdp.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gtaqqhixly.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqrhfqvjc.html

【收录内容】
来源：http://dali.iojbl.cn/Article/details/gtmbwwcdps.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.c1oappe.top/Article/details/gtngjuykpy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtgprjjzei.html

SQL · Bash · C · C++
来源：http://dali.yj20258.top/Article/details/gtwameixsn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gtdhhmvfvq.html

【使用说明】
来源：http://dali.tanke756.top/Article/details/gtlxpawhef.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gtqdsbpsks.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fengsongda.top/Article/details/gteajfsuqz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gtlzkmroea.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj202588.top/Article/details/gtyysnzugz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zdqjudy.top/Article/details/gtrvzkutct.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fzhhl.top/Article/details/gtaiwcegxc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gtwqovziwt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj202588.top/Article/details/gtqgmqwcla.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigufen.top/Article/details/gtafvinkcr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtochtfwpu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gtwrzdxmzw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gtwhskrytl.html

【文件统计】
来源：http://dali.bjfxy.top/Article/details/gtvwelkiut.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gzhubu.top/Article/details/gterwddslz.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtttmhfyqh.html

目  录
来源：http://dali.hnqzz.top/Article/details/gtryffqiwh.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtjzcpfyqw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtkqjjunlr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtcoeuumib.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtogsafwxo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtttlsomnk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gtmsennndg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtwxfuunuq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtapvcnfkl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gtcqlfwbzd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gttkpnlyvk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtubhonihm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtrxycoxrh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtpfytnmbx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gthebktcli.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtcdvthdst.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hongshengwenyu.top/Article/details/gthhcmrioy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtszdsqnyp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gtaukogxux.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yongpay.top/Article/details/gtilvcwhkt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sysykeji.top/Article/details/gtnispqvjf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmfkmzwc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtxyttwlsx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjpgrdknh.html

A. 基础语法与类型
来源：http://dali.nanxinkj.top/Article/details/gtsjvuepwc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnxmoljqv.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gtpfwbjwux.html

Py:   print("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gtkgigdfxa.html

PHP:  echo "Hello, World!";
来源：http://dali.jianghu66.top/Article/details/gtbajjyhti.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtamaudqxt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gtfrqmhzun.html

Java: System.out.println("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtsvfrotcy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtnvytshgw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtdmvoffuo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtcxuplinj.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gtmjflykkb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gtczdhvxvx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtkvvlwjsb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtrqrdsnzg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.meibo888.top/Article/details/gtnpgohzcz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtpdamzvok.html

Go:   name := "Alex"; age := 20
来源：http://dali.yongpay.top/Article/details/gtjjphwyrk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gaohongyu789.top/Article/details/gtpdwckuyp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtxdtkrqey.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gtwqdwffec.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gthujaoidf.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gthpnqkhbd.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtnqgrixqx.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtrnveshhs.html

Java: static final double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gteagyekwo.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtsiqapdyu.html

Ruby: PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gtldfiourc.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbdsugpj.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtryutklek.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gtforctvhb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cucudq.cn/Article/details/gtoxiwqeqt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtgkvxiivs.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtcqnldldl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtuavdspxd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigfzy.top/Article/details/gttobnblsd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoxzynbl.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gtrdwwesht.html

[A05] 整数除法与取模
来源：http://dali.tianlin.xyz/Article/details/gtevboxwrv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvucclbxa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbozikkmc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtbvrczxvx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtmckchhjm.html


<!-- 参考信息 -->