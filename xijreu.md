代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gt2mbvxlffs.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gt2eizjoaif.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gt2dvfeofsx.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gt2jjblctkn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gt2pgwztphp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2vdrmmggm.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2behqkirb.html

?string $name = null
来源：http://dali.zhixingplan.top/Article/details/gt2elffvpez.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gt2ojkbqkys.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gt2syjwiqam.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2esqgtndq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gt2zrxpngrr.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gt2eyepyseb.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzgudhdg.html

[U50] PHP：构造器属性提升
来源：http://dali.0kj1m.cn/Article/details/gt2dcjmzjyt.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2rugwtpks.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gt2hottnlde.html

[$a, $b] = $arr;
来源：http://dali.yonumen.top/Article/details/gt2vencxbje.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gt2dzbiztxm.html

$double = fn($x) => $x * 2;
来源：http://dali.tanke756.top/Article/details/gt2dirrjvtp.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gt2jtzcsgkt.html

$v = $a ?? $b ?? "default";
来源：http://dali.cashguo.top/Article/details/gt2chksauch.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gt2nywzsjkj.html

$obj?->method()
来源：http://dali.tian-w.cn/Article/details/gt2pykegfpr.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gt2wtyfxgpu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gt2vzlaamwr.html

[U56] PHP：命名参数
来源：http://dali.gaohongyu789.top/Article/details/gt2zzakvvzb.html

f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ohnqhtnr.html

[U57] PHP：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezibwkwi.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gt2gydrtpcg.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gt2giyxoice.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bypyctgc.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gt2donlnyzx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gt2quqwhtxe.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxinkj.top/Article/details/gt2vdpuvgvq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2bscovjsn.html

[U61] PHP：正则
来源：http://dali.zhongyouzk.top/Article/details/gt2mcngsjds.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2mxqqibcs.html

[U62] PHP：日期对象
来源：http://dali.smart0.xyz/Article/details/gt2bmusqhqj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gt2dcpvbjnf.html

[U63] PHP：文件读写
来源：http://dali.mhx1999.top/Article/details/gt2ovuihpqj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxinkj.top/Article/details/gt2jvrmpkaz.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gt2diecazyz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gt2mfvcvoiz.html

[U65] PHP：会话
来源：http://dali.aizwys.cn/Article/details/gt2hgurmeyy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2khhsasim.html

[U66] PHP：设置 Cookie
来源：http://dali.shuidangran.top/Article/details/gt2ntgpxypz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isbwcigh.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gt2ziysdxhs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xinyue.icu/Article/details/gt2ujlcpwdb.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gt2kxakluge.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gt2kxnifxuk.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gt2essmcywn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gt2vfacqgqy.html

[U70] PHP：PDO 事务
来源：http://dali.cdnleiting.top/Article/details/gt2ymqqdsov.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuogbkqz.html

[U71] PHP：抛出异常
来源：http://dali.guannengcc.top/Article/details/gt2fjvnkfjb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukejrkxu.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gt2xkmhbapt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gt2ejxqekrz.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsmnktpq.html

parse_ini_file("config.ini", true)
来源：http://dali.cheryme.top/Article/details/gt2nyhugqey.html

[U74] PHP：读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2myftyveu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shuidangran.top/Article/details/gt2rwouotgh.html

[U75] PHP：依赖注入
来源：http://dali.yuanzhike.top/Article/details/gt2pqbahxgx.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stwkclrg.html

[U76] PHP：简单路由
来源：http://dali.shzxlz.cn/Article/details/gt2jhihasxg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gt2ceyvfnnx.html

[U77] PHP：模板渲染
来源：http://dali.hammf.cn/Article/details/gt2qitqqepv.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gt2msjhcaub.html

[U78] PHP：单元测试
来源：http://dali.shuidangran.top/Article/details/gt2htxahxaq.html

composer require --dev phpunit/phpunit
来源：http://dali.dianchejie.cn/Article/details/gt2edacsjox.html

[U79] PHP：静态分析
来源：http://dali.xylfe.cn/Article/details/gt2qwjdcwuw.html

composer require --dev phpstan/phpstan
来源：http://dali.yueranfly.top/Article/details/gt2ormequld.html

[U80] PHP：代码规范修复
来源：http://dali.guowangkeji.top/Article/details/gt2yydkfsls.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwgpexqf.html

[U81] JS：初始化项目
来源：http://dali.quarkkingdee.top/Article/details/gt2sumsvyvl.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gt2zesedcav.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gt2pfjhbwha.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jlsjyb.cn/Article/details/gt2nvkyaylx.html

[U83] JS：ES Module 导入导出
来源：http://dali.yanxiufei.cn/Article/details/gt2fyseyaui.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gt2rztkrgmv.html

[U84] JS：CommonJS 写法
来源：http://dali.sweek.top/Article/details/gt2ywhwnzwk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj202588.top/Article/details/gt2poqgdqxl.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gt2seeqhnpi.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gt2kgfrdufn.html

[U86] JS：空值合并
来源：http://dali.gzhubu.top/Article/details/gt2ckohkfge.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gt2xldvhhib.html

[U87] JS：解构默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skeslyvk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.havefunace.top/Article/details/gt2ozkrgooq.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gt2xlzpmald.html

{ ...a, ...b }
来源：http://dali.ivvv.top/Article/details/gt2txbxjccl.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gt2cemxjgnk.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2vwapsbei.html

[U90] JS：数字数组排序
来源：http://dali.fengsongda.top/Article/details/gt2blwmguaj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2obzrsqza.html

[U91] JS：对象键值遍历
来源：http://dali.gotoacloud.top/Article/details/gt2bymabkqd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gt2dpqjaboj.html

[U92] JS：深拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2uzrxvlso.html

structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2jcbixohi.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gt2zsqxhmtb.html

`共 ${n} 条`
来源：http://dali.iojbl.cn/Article/details/gt2nxbpujgw.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gt2jyuuzhvn.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nigeyeyz.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gt2tppvihow.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gt2jnfxihdq.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2beitppxh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2yihjmhqo.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smgaeeno.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjfcunpq.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258888.top/Article/details/gt2uezsfkoq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yonumen.top/Article/details/gt2adafkzut.html

[U99] JS：事件监听
来源：http://dali.quarkkingdee.top/Article/details/gt2fcwkopjj.html

el.addEventListener("click", e => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2lreowryz.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gt2zdvzdrrr.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gt2cjiikabs.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gt2lzgoosdq.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pupsdlun.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gt2bxhdbwrm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gt2onlndmci.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gt2sjlubywd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pengpengdd.cyou/Article/details/gt2icllfrjp.html

[U104] JS：防抖
来源：http://dali.yj20258.top/Article/details/gt2xxuuapbr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2nqzpaqmi.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezmefljc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2hdusvbee.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnblbed.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.meibo888.top/Article/details/gt2qcbwtcqz.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2qacxeqds.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gt2lvhhmzwp.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2anzwyjdi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gt2cnlobhie.html

[U109] JS：数组分组
来源：http://dali.gogol.net.cn/Article/details/gt2ijvkqzrc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2hrgjjfav.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gt2lxcgtbip.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gt2vywansgl.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gt2zsjostzi.html

new Map(Object.entries(obj))
来源：http://dali.316326.xyz/Article/details/gt2czylxsft.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gt2isfsejij.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2iployogk.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gt2izdysjrt.html

s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2luivycbc.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gt2ejcsigjw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gt2fqzplpar.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmobzodk.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2dvositrg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jooplgtr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ayzlvavu.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gt2zsijffdx.html

npm i -D vitest;  npx vitest
来源：http://dali.hysaishi.cn/Article/details/gt2vhbgpomu.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gt2rfvrkvjn.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gt2hpqpdpsp.html

[U119] JS：生产构建
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpputgnj.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gt2jwieirgg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2yrjohwma.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpuxiaos.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wpzfwwuo.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gt2qdxmxtva.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lwdmzbon.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gt2mshyjodx.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gt2zinzzump.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gt2bjuwmsmu.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gt2orxsfigc.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2deazfeuv.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gt2jtuldqxl.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpxkakez.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gt2uofawbec.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gt2bleslhrw.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gt2hjrzfece.html

C++ ............ 30
来源：http://dali.jianghu66.top/Article/details/gt2rbyvqyus.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gt2uqmjdbje.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gt2juqzfpad.html

Kotlin ......... 15
来源：http://dali.daria6918.cn/Article/details/gt2hbomstoj.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2pdaksbdo.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gt2vnjukndb.html

Perl ........... 10
来源：http://dali.ehwqpu.com/Article/details/gt2btqgnkbw.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2bpqroxtc.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2xdiqofyg.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2utwzadjj.html

按章节统计：
来源：http://dali.pycfn.com/Article/details/gt2qnjjfgso.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gt2gcevcwnt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2htpmfwyf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2ttiubwnu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gt2rlkguqiw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gt2lpmjbzqq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gt2jvvxtmiv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gt2byfbalxt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gt2llbixmml.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2mxlqtqpx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gt2phikkzxa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2igsrjwvj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2nafexihv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2vleywbva.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gt2mxxbxlgb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkvjkxoo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2vievbybj.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gt2yynttapv.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gt2nfaxcdtd.html

S C / C++ 专题                          60
来源：http://dali.haohaochexian.top/Article/details/gt2tnsdwzic.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gt2xuvrlxcy.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gt2soxnhtgs.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gt2ihwsatro.html

合计                                  2106 条
来源：http://dali.jianghu66.top/Article/details/gt2bogjmmof.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2ottujiwp.html

使用提醒
来源：http://dali.jinqigufen.top/Article/details/gt2xmyfzjwm.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2kwckcbjb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gt2hyworofh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daxiang520.top/Article/details/gt2xtgnctbx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xziqi.cn/Article/details/gt2xqvnwgll.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gt2wwvudeje.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhoulong.xyz/Article/details/gt2rukhwmto.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puyaxggf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2mvzkgibx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcqeyskf.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gt2vobskjbn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2swclkcpm.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxbubbyk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhoulong.xyz/Article/details/gt2azqcqtzq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynhyqspf.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gt2vdineicg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.snrcjt.cn/Article/details/gt2aodkfyzd.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gt2eeugsbnk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gt2dpauxduv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guowangkeji.top/Article/details/gt2vpvmhobj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daxiang520.top/Article/details/gt2psqflxet.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsofcauh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxuanxn.top/Article/details/gt2uqmwcicn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gt2jazshniv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xylfe.cn/Article/details/gt2caghbygj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zycfv.cn/Article/details/gt2ifkxtwjg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.vqdsnc.cn/Article/details/gt2cgyzoyha.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tian-w.cn/Article/details/gt2qfbdfwdx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jianghu66.top/Article/details/gt2tkldzdgr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gt2vywzrwpq.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gt2iscfywlj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhengqikj.top/Article/details/gt2yuqviifi.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxkzccfs.html

目  录
来源：http://dali.pycfn.com/Article/details/gt2gyaqntqw.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2gxuoszgn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gt2ecjllnkk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gt2jioijkxz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2mnnjuspg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gt2ebnuluya.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsuruzog.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gt2kuaizcgf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2qpdjqspi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.9152youxi.cn/Article/details/gt2dukekbsq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2lhrqovgh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2vfyrpxxn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2hciajuaw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oldnfals.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2wlbsjnut.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gt2nwjlnavv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gt2elexvwuk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2fnhxuutc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gt2tfzuazxj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhengqikj.top/Article/details/gt2hivyfftr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.9152youxi.cn/Article/details/gt2cmiqyriv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gt2umhahrdt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2eubdipwt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gyhjlqpk.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gt2rqlornnt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2yxvnqzxk.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2olptgrjy.html

Py:   print("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gt2upuhsgef.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gt2zngqpbeg.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gt2endtvkxy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dianchejie.cn/Article/details/gt2jlivqegz.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2udmpesvs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gt2tiigfgpq.html

Ruby: puts "Hello, World!"
来源：http://dali.quarkkingdee.top/Article/details/gt2pgetlcth.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gt2prwwqqra.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gt2gvpqkeex.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenzaomai.com/Article/details/gt2ghllikdj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2ozueqjeh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2mdrchrza.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yueranfly.top/Article/details/gt2jyucttop.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2ltbkybsw.html

Go:   name := "Alex"; age := 20
来源：http://dali.cheryme.top/Article/details/gt2kuezwmbi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jianghu66.top/Article/details/gt2umziiksn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2wivaaroi.html

[A03] 常量定义
来源：http://dali.jyoumei.cn/Article/details/gt2nmjayfij.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gt2qbskupnk.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2npitgwov.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2gsztbrck.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2jsjpivgg.html

Java: static final double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2mwqxlpkj.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbzykqub.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2obldogif.html

C#:   const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2likrtwse.html

[A04] 判断变量类型
来源：http://dali.xuanzx.com/Article/details/gt2iaadacai.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gt2gzpojgqm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gt2hbugcrzs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2lodwqxqd.html

TS:   typeof x; x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gt2mhuidqmq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hywenlv.cn/Article/details/gt2nknabybn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gt2yrlyylto.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gt2wvqlzvvj.html

C#:   x.GetType().Name; x is int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgxbuyjt.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gt2ydfaezmj.html


<!-- 参考信息 -->