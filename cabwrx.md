代发 wailian999

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gtrnpwclzm.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gtpfqhrdjr.html

[U48] PHP：纯枚举
来源：http://dali.wangdashe.top/Article/details/gtkmnmgbyy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gtfjijtjrb.html

[U49] PHP：只读属性
来源：http://dali.jqgfzy.top/Article/details/gttccoqjok.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gthpuumaov.html

[U50] PHP：构造器属性提升
来源：http://dali.meibo888.top/Article/details/gtecrwuboz.html

public function __construct(private int $id) {}
来源：http://dali.ppjwa.cn/Article/details/gtvewxbzti.html

[U51] PHP：数组解构
来源：http://dali.hongshengwenyu.top/Article/details/gtxbxnwbxf.html

[$a, $b] = $arr;
来源：http://dali.yanxiufei.cn/Article/details/gtykbhqwpe.html

[U52] PHP：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gtsskoatun.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gtsksuvnax.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtyfmssnkj.html

$v = $a ?? $b ?? "default";
来源：http://dali.jlsjyb.cn/Article/details/gtimgwyewc.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gtrrpolkcu.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpngcgkt.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gtokjanahw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtcvjkhfjc.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtrlsxebji.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtislawqye.html

[U57] PHP：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtpfutncsw.html

"值: {$a}"
来源：http://dali.yueranfly.top/Article/details/gtxeazdbxw.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gtvzyoppvo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gtizszncqz.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gtjjpywhaw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtbznqnald.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gtfnijnpff.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhixingplan.top/Article/details/gtrtpqxtyc.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuysigtvy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtdyyecurb.html

[U62] PHP：日期对象
来源：http://dali.zdqjudy.top/Article/details/gtmyvxqtgc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxinkj.top/Article/details/gtbetdeynb.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gtuewzgsaa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gtozvbftdg.html

[U64] PHP：目录遍历
来源：http://dali.cheryme.top/Article/details/gtjgkyfxgq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gtztzquyli.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gtmnkjkzuw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtujraiyyv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmygdvzuz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhengqikj.top/Article/details/gtoxncfidc.html

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gtaochlcxs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gtbseudksj.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gtapgdkbba.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimllasqm.html

[U69] PHP：PDO 预处理
来源：http://dali.jiagoushi.top/Article/details/gtjdawuacn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zdqjudy.top/Article/details/gtafjcqkbj.html

[U70] PHP：PDO 事务
来源：http://dali.ivvv.top/Article/details/gtwsjxodmj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gtcujvuobz.html

[U71] PHP：抛出异常
来源：http://dali.pycfn.com/Article/details/gtbkzhoihz.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtrkugejyd.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gtpziwpzia.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gtovmqrclk.html

[U73] PHP：读取 ini 配置
来源：http://dali.0kj1m.cn/Article/details/gtvewzquyp.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gtiucnpwzp.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtdjfxmnft.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtklvyvpns.html

[U75] PHP：依赖注入
来源：http://dali.havefunace.top/Article/details/gtuqufuzue.html

composer require psr/container
来源：http://dali.meibo888.top/Article/details/gthlzorjww.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gtzzkjlleh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigfzy.top/Article/details/gtnvrcysqs.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gtyottjqzq.html

composer require twig/twig
来源：http://dali.birdmap.top/Article/details/gtsstouquv.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtorlcaszk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gtnoijtfvt.html

[U79] PHP：静态分析
来源：http://dali.jinqigufen.top/Article/details/gtrhghnjmu.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gtdcdcozmc.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gtbuebftvm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dashuyun.cn/Article/details/gtclnalone.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gtxkjqbbrl.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gttjesmrxg.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gtivvntzlk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gtubfqnnqb.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gtevwalsli.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtmihxloet.html

[U84] JS：CommonJS 写法
来源：http://dali.yanxiufei.cn/Article/details/gtruafroik.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gtoqhcroda.html

[U85] JS：可选链
来源：http://dali.daxiang520.top/Article/details/gtddgmxozm.html

a?.b?.c
来源：http://dali.chenlongwang.top/Article/details/gtbycaqjsr.html

[U86] JS：空值合并
来源：http://dali.chenjidiqi.icu/Article/details/gtdblyiapm.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gthhubdofi.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gtaylcblxy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gtbpdvqaun.html

[U88] JS：对象展开合并
来源：http://dali.hywenlv.cn/Article/details/gtlpaxymqw.html

{ ...a, ...b }
来源：http://dali.shangyingyoupin.top/Article/details/gtuolqajcc.html

[U89] JS：数组去重
来源：http://dali.tianlin.xyz/Article/details/gtmsdycatt.html

[...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtrlvrqciz.html

[U90] JS：数字数组排序
来源：http://dali.xuetiantiany.cn/Article/details/gtzlkcbqrh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtfnmhbrot.html

[U91] JS：对象键值遍历
来源：http://dali.gogol.net.cn/Article/details/gtpbfvdghg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gtnjlbxwfp.html

[U92] JS：深拷贝
来源：http://dali.aibaodan.cn/Article/details/gthpqlwmit.html

structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtdetlefow.html

[U93] JS：模板字符串
来源：http://dali.ehwqpu.com/Article/details/gttxaktsam.html

`共 ${n} 条`
来源：http://dali.yj202588.top/Article/details/gtiiyjcklc.html

[U94] JS：箭头函数
来源：http://dali.bjfxy.top/Article/details/gtehupminh.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gtkvbqzfxb.html

[U95] JS：Promise 包装
来源：http://dali.cheryme.top/Article/details/gtwicuhvjx.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gtlxvsvvfq.html

[U96] JS：async/await 与异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmolqgfhs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtqywasjdz.html

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gtslotakra.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxtemhvw.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gtudnjsszl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gtsjwojigu.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gtstulcgiq.html

el.addEventListener("click", e => {})
来源：http://dali.sysykeji.top/Article/details/gtfpyhbcmw.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gtvcvpohnx.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gtvcitzizf.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gtlvzxdzvw.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gtxommaxlj.html

[U102] JS：本地存储
来源：http://dali.zdqjudy.top/Article/details/gtxfrtrgzf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.316326.xyz/Article/details/gtotcqrovk.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gtwgrydhux.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtwgompryc.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtlmnwwalw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtkndndqfn.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gtzpgmmirp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xinyue.icu/Article/details/gtkujzpmzh.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gtckugxhnd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtnmoynooj.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gtzugobqmh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtqfconbds.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gtijcegiop.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gtupjvyrwz.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtifjcaaho.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtiitjugre.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gtbhxzliba.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gtizmyqwnm.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtpoatsiko.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmdewyvn.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtjgbmltfz.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtgdrkhkvi.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gtnpfgpxux.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtabxvqezd.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtsixtqdaa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtkfxcpvqh.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtmwzvcoqh.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtzdrbpqiw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gthmzjkrbv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gtekjwzisl.html

[U117] JS：单元测试
来源：http://dali.sufxvd.cn/Article/details/gttpkdldcn.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gtvadehqps.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gtmyamiytl.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gtlmaotkdu.html

[U119] JS：生产构建
来源：http://dali.zhoulong.xyz/Article/details/gtlinidbtk.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtwaxsygdq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtxashrxmi.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gtkvzdylhf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtoplttniv.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gtuhghqkne.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrxnshxtz.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gtnvrxeimq.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gtbopyixvq.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtpdxkjbxn.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gtoqlftwfr.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gttotlzjmm.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhmyxqdw.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtuhlkgmtz.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtualldlwv.html

C# ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaevgnve.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtppfjsnpj.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhqjdgad.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtpponhyez.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gtfrhxlkhy.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gtplqakjar.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gthkoacjrd.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gtsnbpgrvy.html

Perl ........... 10
来源：http://dali.andypj.xyz/Article/details/gtsvfumubu.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gteqmkbtwp.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtsgpfkppg.html

合计 ........... 2106 条
来源：http://dali.fengsongda.top/Article/details/gtidpcqqkw.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gtxkvmdwnd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtpjfkfjxz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gttilaohho.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtdimkmsna.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtzwieipyh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gtxfejzqgv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gtypacdfld.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtyywfnbfn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtglbpxidf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtvhdryzif.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtlbgdxwvz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtzmxukzed.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gthppxphjm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtrbrnrwld.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtwrlybply.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj202588.top/Article/details/gtpqzgtdbq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtsfbqrofy.html

Q SQL 专题                              90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaxrovyd.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gtcobzvwqr.html

S C / C++ 专题                          60
来源：http://dali.ivvv.top/Article/details/gtbktnzfns.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gtyauinjfy.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gtuguhuapu.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtsgswrnps.html

合计                                  2106 条
来源：http://dali.yangfankeji.com/Article/details/gtqqdeddkf.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtfmcrltru.html

使用提醒
来源：http://dali.jlsjyb.cn/Article/details/gtfryjycgx.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtmrcbnyqx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtqpmatizn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjswxszvu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zycfv.cn/Article/details/gtxxrrdwkw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.quarkkingdee.top/Article/details/gthinuygqv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtryzjloht.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gtydvjspex.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjcpixbmc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.bjfxy.top/Article/details/gtatrxmszv.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gtcetpenwb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtiorntxut.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gtldcndhnt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yangfankeji.com/Article/details/gtuxisokin.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmjlbkjn.html

SQL · Bash · C · C++
来源：http://dali.meibo888.top/Article/details/gtzxmxvlbo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.vqdsnc.cn/Article/details/gtwyxcjxkm.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gtnlbpvliw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gtxeiqbzgf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yueranfly.top/Article/details/gtbmhaincx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gtamgaoagu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gtiilfjahr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangdashe.top/Article/details/gtltbddmpq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.vqdsnc.cn/Article/details/gtzcztrrna.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgfzy.top/Article/details/gtsltvgmmt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenjidiqi.icu/Article/details/gtrebvbvmy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aibaodan.cn/Article/details/gtvofejeci.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gtpsjveeek.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jianghu66.top/Article/details/gtrkjsthym.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gtscsduuwb.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtltxbkjgu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yangfankeji.com/Article/details/gtefaaxdhb.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtbznplagq.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtduewsknd.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtmtfiyxke.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtfptxuxcc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtzrssqgpk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gtxoyefqin.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtfhxfdzuz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yonumen.top/Article/details/gtsfsisstz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtbdwcyzfo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyxuaanh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtxgiuqfce.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtqrlqtxzi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtqalslibv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtcnhgxxzc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtmgcstwmu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtjxmextvs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gtwwruiifh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.birdmap.top/Article/details/gtzjmspcfd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtqyxsbpzp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtxoqnvgtn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyzjetqc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhengqikj.top/Article/details/gttycfpsta.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtnmfvnnff.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtiukesfgz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthbtyjhfd.html

A. 基础语法与类型
来源：http://dali.tanke756.top/Article/details/gthwzubedw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtycndtopg.html

[A01] Hello World
来源：http://dali.yonumen.top/Article/details/gtsxnxprim.html

Py:   print("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtbftaaagw.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gtarbyinec.html

JS:   console.log("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gthpwyydqc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gogol.net.cn/Article/details/gtohplouzh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtlemhboej.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtuhgwbghf.html

Ruby: puts "Hello, World!"
来源：http://dali.yvedp.cn/Article/details/gtatycaulm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtjnifphxs.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gtjyzeyrkg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgfzy.top/Article/details/gthbnqtppt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yvedp.cn/Article/details/gtyhvlgeuj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtmrbedenc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daxiang520.top/Article/details/gtpbygqjgn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtkkmflndy.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gtzqbjdsvu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sysykeji.top/Article/details/gtubcmfovs.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sxryk.cn/Article/details/gtzoqcyhkc.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gtvaoxsqjd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dashuyun.cn/Article/details/gtpbynlwth.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtpoaqhfqa.html

JS:   const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtvgmillsd.html

TS:   const PI: number = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtuxmueeoo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gthuzfyjor.html

Go:   const PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtpgctfxgj.html

Ruby: PI = 3.14159
来源：http://dali.cdnleiting.top/Article/details/gtzqknxzmq.html

C#:   const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtssueezjg.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtylabptyb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aibaodan.cn/Article/details/gtuchzwirh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.snrcjt.cn/Article/details/gtnczbkyiq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtsdktylhi.html

TS:   typeof x; x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gtrywxlizg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yueranfly.top/Article/details/gtjioalxmd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.quarkkingdee.top/Article/details/gtwpgfjkln.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.smart0.xyz/Article/details/gtvpaclifn.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gtwygdmxtg.html

[A05] 整数除法与取模
来源：http://dali.sxryk.cn/Article/details/gtcdxtblao.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.316326.xyz/Article/details/gtsfozrbsc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtkrdqftra.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gttwwigvvb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtmtakmfgm.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxebwwwa.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtypupdyhv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtsgyvgsjn.html

C#:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtitiltpnq.html


<!-- 参考信息 -->