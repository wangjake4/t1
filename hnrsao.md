代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gtnkergwet.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdtgnfnf.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gtickqhzdr.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gtlglqizal.html

[U45] PHP：类型声明与返回类型
来源：http://dali.havefunace.top/Article/details/gtumkqwqvw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtngynlmcq.html

[U46] PHP：可空类型
来源：http://dali.hfpthk.cn/Article/details/gtqqfzjtlx.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gtuaponxsa.html

[U47] PHP：联合类型
来源：http://dali.yj20258.top/Article/details/gtfkkusleh.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gtqbjzhhni.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gtcvxjhpad.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.9152youxi.cn/Article/details/gtmigepbhg.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtritrkadd.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gtrfwitruy.html

[U50] PHP：构造器属性提升
来源：http://dali.kuanghao11.cn/Article/details/gtkskhqglt.html

public function __construct(private int $id) {}
来源：http://dali.chenlongwang.top/Article/details/gtocnaqdyh.html

[U51] PHP：数组解构
来源：http://dali.iojbl.cn/Article/details/gtfwqfxmvz.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gtryvbopin.html

[U52] PHP：箭头函数
来源：http://dali.yj20258.top/Article/details/gtkpzfzfnq.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtvjqelbio.html

[U53] PHP：空合并运算符
来源：http://dali.nanxinkj.top/Article/details/gtaqysrydl.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgufenzy.top/Article/details/gtjbmihlye.html

[U54] PHP：空安全调用
来源：http://dali.aibaodan.cn/Article/details/gtudnvqtnd.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtobkfnzvj.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtrabdwwvo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtrmpkajdb.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtkmrpwemo.html

f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtueemypsf.html

[U57] PHP：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtgsfvoshp.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gtysctmotq.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gtoynzxnpk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gtythfsaiq.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gtoxfpfpvo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtfxxenqhc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhoulong.xyz/Article/details/gtjuktncqk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gteonrjdvl.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gtcghdiyil.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtezahsctt.html

[U62] PHP：日期对象
来源：http://dali.daria6918.cn/Article/details/gthdmvkynb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtlyjabhao.html

[U63] PHP：文件读写
来源：http://dali.cucudq.cn/Article/details/gtknpvytgh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gtbjjyilse.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gtnzkfyumg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtafjytbak.html

[U65] PHP：会话
来源：http://dali.yanxiufei.cn/Article/details/gtfiajzirj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtkzrdslkj.html

[U66] PHP：设置 Cookie
来源：http://dali.daria6918.cn/Article/details/gtohsseoni.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gtrvhusyuc.html

[U67] PHP：处理文件上传
来源：http://dali.xinyue.icu/Article/details/gtouqhrwfi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dianchejie.cn/Article/details/gtlfenjxvh.html

[U68] PHP：PDO 连接
来源：http://dali.c1oappe.top/Article/details/gtrhiqbokd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkxjfscr.html

[U69] PHP：PDO 预处理
来源：http://dali.jiagoushi.top/Article/details/gtdwmqokdc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gtjbwkrtxk.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gtawmtdsyq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cashguo.top/Article/details/gthhmzzajl.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gtyvjfikvv.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtuocpzycp.html

[U72] PHP：写错误日志
来源：http://dali.hongshengwenyu.top/Article/details/gtmxuubxsy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylywtbmy.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gtxsmcjqjp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijvlmyhp.html

[U74] PHP：读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtjlepqddk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtqqjiivpn.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gtxhpexxwp.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtycbuewvw.html

[U76] PHP：简单路由
来源：http://dali.svipenyu.cn/Article/details/gtmfszvsid.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gtzbztgwno.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gttzrpskgo.html

composer require twig/twig
来源：http://dali.chenjidiqi.icu/Article/details/gthbnbsbfn.html

[U78] PHP：单元测试
来源：http://dali.pycfn.com/Article/details/gtspnosxic.html

composer require --dev phpunit/phpunit
来源：http://dali.zdqjudy.top/Article/details/gtktdghoic.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gtguxskyiv.html

composer require --dev phpstan/phpstan
来源：http://dali.ppjwa.cn/Article/details/gtnwvzaoys.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtgyxkcsfd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cucudq.cn/Article/details/gtxxxhtgik.html

[U81] JS：初始化项目
来源：http://dali.wangshuangyany.cn/Article/details/gtmaqustah.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtwvifrngz.html

[U82] JS：package.json 脚本
来源：http://dali.daxiang520.top/Article/details/gtuzzbdxcs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gtkoituvhj.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gttvohqhcj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gtlyzhuneu.html

[U84] JS：CommonJS 写法
来源：http://dali.gogol.net.cn/Article/details/gtmnqhghba.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gtwcrufupe.html

[U85] JS：可选链
来源：http://dali.iojbl.cn/Article/details/gtmqoieudg.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gtfuamtvjq.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gtlmmemywi.html

a ?? b
来源：http://dali.jinqigufen.top/Article/details/gtdgwbdjen.html

[U87] JS：解构默认值
来源：http://dali.fengsongda.top/Article/details/gtcfgbmvce.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hammf.cn/Article/details/gttazaxlvu.html

[U88] JS：对象展开合并
来源：http://dali.cucudq.cn/Article/details/gtnoxnmvsv.html

{ ...a, ...b }
来源：http://dali.cucudq.cn/Article/details/gtrlfsivor.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gtyizmsfun.html

[...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtqwccikxa.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gtkuwqffed.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtnrgyqvpc.html

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gthmwwmhkl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gtoohevazw.html

[U92] JS：深拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnbhpdxh.html

structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtqjdmtkju.html

[U93] JS：模板字符串
来源：http://dali.yanxiufei.cn/Article/details/gtogrxkqup.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gtvsxjhkqz.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gthofbepmm.html

const double = x => x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtzjdrtvha.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gtrwajgqpv.html

new Promise((resolve, reject) => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtzuarrfvn.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gtupobvnwy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtywvylssl.html

[U97] JS：并发请求
来源：http://dali.yuanzhike.top/Article/details/gtltjwpohi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtjtdunbrx.html

[U98] JS：fetch 带 JSON
来源：http://dali.hammf.cn/Article/details/gtgdrnueix.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnalvnvgh.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gtmqswqjkf.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gtivcsvugl.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtonyvkxez.html

document.querySelector(".item")
来源：http://dali.bjfxy.top/Article/details/gtgolatesa.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtrcczpesk.html

el.classList.toggle("active")
来源：http://dali.hnqzz.top/Article/details/gtqhmhuqap.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gtncwwsaqr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cashguo.top/Article/details/gtlagkedza.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtpmwtvnae.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gtndtheimd.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gtijjkhiuy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtvfdbchoi.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gtpnmuonod.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmqgamze.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtcgpvddzl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gtuqygjynr.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtunxnwlqs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtfvjrehyf.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtmgtqeblw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuxming.cn/Article/details/gtggnovxpo.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gtkvbaaked.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtdykxuafz.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplaahgib.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gtidcjqgvf.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gtgmdsmwpv.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtmtnsswad.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gtlzmddqba.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtpougnamj.html

[U113] JS：正则替换全部
来源：http://dali.yonumen.top/Article/details/gteqzbkksq.html

s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtezadltvk.html

[U114] JS：JSON 深比较
来源：http://dali.gogol.net.cn/Article/details/gtezwldkuu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtcglsgurx.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtaywufbtq.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gteangqcbx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdocassus.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtninkgbqe.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gtlobadljp.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gttrzgddhn.html

[U118] JS：开发服务器
来源：http://dali.chenlongwang.top/Article/details/gtbtizfxuv.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gtihbvyamz.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtszzhaagu.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gtlndqagpf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gturjkzkeq.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gtdfhyxqjw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gteqahukiv.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gtkhbolmcm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpaxocoja.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhzxkxsi.html

Python ......... 252
来源：http://dali.yj20258.top/Article/details/gtqtcnvzuk.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gtzfciizxm.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gtaumlusud.html

TypeScript ..... 212
来源：http://dali.nwbrower.top/Article/details/gtaqcxfaei.html

Java ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gtcudgcxct.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gtqxtclkhe.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtrdbhifsx.html

C# ............. 212
来源：http://dali.nwbrower.top/Article/details/gtsxhypzdh.html

C .............. 30
来源：http://dali.zhongyouzk.top/Article/details/gthfbtbked.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gtghnflith.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtpzmqojoz.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gtnxjlpjaz.html

Kotlin ......... 15
来源：http://dali.yangfankeji.com/Article/details/gttjefeaxw.html

Swift .......... 15
来源：http://dali.316326.xyz/Article/details/gtwppbsqre.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gtoknuenpb.html

Perl ........... 10
来源：http://dali.sysykeji.top/Article/details/gthjgpoubd.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gtoywesilp.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtmgntvzqc.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gterdqnbal.html

按章节统计：
来源：http://dali.cashguo.top/Article/details/gtidzptuas.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtzzwpbcdo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtpswtyabm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtlmvtfnwe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtdovullhd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gtfvxbekfz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gteofctmek.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtrqfltoay.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxkxkukm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtfjbftfnl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtihfzebfx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtlkjkyrml.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtbadifylm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqqazphj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtqqanxaof.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gtrepxsjae.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtwmididzd.html

Q SQL 专题                              90
来源：http://dali.aizwys.cn/Article/details/gtxnczzamo.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gtqizyagje.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gtkdbqidlp.html

T 其他语言补充                          60
来源：http://dali.daxiang520.top/Article/details/gtxhrmbkhv.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gtokguobil.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtgoryloim.html

合计                                  2106 条
来源：http://dali.jianghu66.top/Article/details/gtnlofjdgc.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gttvyphrfz.html

使用提醒
来源：http://dali.nwbrower.top/Article/details/gtalfcruvo.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtoydaldtd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gtxlavncty.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yonumen.top/Article/details/gtejyytvdu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hywenlv.cn/Article/details/gtzxqvumju.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xylfe.cn/Article/details/gtsdtgicup.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ppjwa.cn/Article/details/gtisuuljff.html

—— 文件结束 ——
来源：http://dali.0kj1m.cn/Article/details/gtjebcxvtt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtegjrlwky.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.svipenyu.cn/Article/details/gtxbeeqbsy.html

Common Programming Examples Cheat Book
来源：http://dali.cqqwz.cn/Article/details/gtfehdlick.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrgkzeuhv.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtjysiwdmp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gtbdysgdev.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfbifxxc.html

SQL · Bash · C · C++
来源：http://dali.cheryme.top/Article/details/gtwmddsrea.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenjidiqi.icu/Article/details/gtqdjqtapi.html

【使用说明】
来源：http://dali.meibo888.top/Article/details/gtuifzuypk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gtxzuxfill.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtdurwnxda.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.smart0.xyz/Article/details/gtqwcuuwht.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtqfbhqwvn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zdqjudy.top/Article/details/gtpfimvygn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gtcohvjstv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtwjfdxmbb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zdqjudy.top/Article/details/gtvlchgodc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gogol.net.cn/Article/details/gtevoykhrd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gtnzkcxwnx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtilqpinve.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jianghu66.top/Article/details/gtmtdhaijw.html

【文件统计】
来源：http://dali.gotoacloud.top/Article/details/gtxrnkupbb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtnvkghdbo.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtwxerpocc.html

目  录
来源：http://dali.zhoulong.xyz/Article/details/gtckmlsrrx.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gthiotgyqi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtoirruzpm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqocwaamf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtcegcmnxu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gtdvtmulaq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gtcfnqeenu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlwxifvj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtlqldhwxj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gtejyrbegk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtalizjjkw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtqibwsjtu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtchsepogw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmrcrtel.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtgsdhbpos.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtkrmwpxze.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jlsjyb.cn/Article/details/gtrseyknzo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtltmfvhnv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yonumen.top/Article/details/gtfgbnmhjt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtxnrffghb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnxiangtu.top/Article/details/gtdwcudvuu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtkszeezkm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtefvqzadn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtygfcqgdp.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gtbhaaycqz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyryxyceh.html

[A01] Hello World
来源：http://dali.yj20258888.top/Article/details/gtrqpgfqrd.html

Py:   print("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtpgbjlvym.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gtzsrhlkpf.html

JS:   console.log("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtmhpcacas.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gtbqtiwlmc.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtbvnfhkuh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtvkenfwzv.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258.top/Article/details/gtrwefaieq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtqwffknec.html

[A02] 变量声明与赋值
来源：http://dali.zdqjudy.top/Article/details/gtwihuvhny.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gtoeoibiuu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gtddauvjhb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nwbrower.top/Article/details/gtezxsjtam.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gtlxpkkeon.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aibaodan.cn/Article/details/gthkgeztog.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gtdwnwmoci.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gtbtnnqffo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtvsltanwf.html

[A03] 常量定义
来源：http://dali.aibaodan.cn/Article/details/gtoqlsovlt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dashuyun.cn/Article/details/gtjcmmbfnw.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwzakifr.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtuwxoiyxl.html

TS:   const PI: number = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtrhshenwx.html

Java: static final double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtvdztpcvh.html

Go:   const PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvycplumc.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtidcmunxm.html

C#:   const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtzrzscnkc.html

[A04] 判断变量类型
来源：http://dali.daxiang520.top/Article/details/gtujeosznr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gtctrjsimd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shuidangran.top/Article/details/gtrvhwowxn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ivvv.top/Article/details/gtewkvhlhh.html

TS:   typeof x; x instanceof Date
来源：http://dali.meibo888.top/Article/details/gthemkdnrp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gtjnhmmmgq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigfzy.top/Article/details/gttsxpwxmt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gtqjkemqbl.html

C#:   x.GetType().Name; x is int
来源：http://dali.ivvv.top/Article/details/gtueyqaxdd.html

[A05] 整数除法与取模
来源：http://dali.yvedp.cn/Article/details/gtgfzjklae.html


<!-- 参考信息 -->