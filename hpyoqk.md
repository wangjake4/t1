代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gtkabmyojq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gtculyyzbk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gtmdlwfuqk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gtojmxsfax.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtbsznzsjo.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gtviewhhsj.html

[U44] PHP：开启严格类型
来源：http://dali.shangyingyoupin.top/Article/details/gtitksokkf.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtdmfqoqlk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtdvfiliaf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gthuekaiqu.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gtbpaswrrc.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gtcendywas.html

[U47] PHP：联合类型
来源：http://dali.yj202588.top/Article/details/gtyepbtokb.html

int|string $id
来源：http://dali.cucudq.cn/Article/details/gtfvaqkhlp.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gtvmqmtkxz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gtumtalgpt.html

[U49] PHP：只读属性
来源：http://dali.aibaodan.cn/Article/details/gtsirpulhs.html

public readonly string $name
来源：http://dali.gzhubu.top/Article/details/gtxamhymts.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gtndtkdpyg.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtltpbipwb.html

[U51] PHP：数组解构
来源：http://dali.xylfe.cn/Article/details/gtrupywwdr.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gtyjlxqqnb.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteujallte.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gttkeuaiyg.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gtqyozzrxq.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gtkqocidfm.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gtawbskcct.html

$obj?->method()
来源：http://dali.jqgfzy.top/Article/details/gtvswcduun.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gtyemibshg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gtainhuyyh.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gtmczhxgtb.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtpnsbvamt.html

[U57] PHP：字符串插值
来源：http://dali.guannengcc.top/Article/details/gteqxdtyqa.html

"值: {$a}"
来源：http://dali.jinqigufen.top/Article/details/gtczyhfmlg.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gthxvrxzcj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.smart0.xyz/Article/details/gtwnqbewvw.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gtywrvuwyf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtwwcoibft.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtjpwkdmdq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gtpkofkmku.html

[U61] PHP：正则
来源：http://dali.tianlin.xyz/Article/details/gtcrpiebgs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtlhmawgje.html

[U62] PHP：日期对象
来源：http://dali.svipenyu.cn/Article/details/gtyqmtmjmp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gttplzmgtt.html

[U63] PHP：文件读写
来源：http://dali.cashguo.top/Article/details/gtapsmflzj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gtgtbwospd.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gtoboqapek.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtqwkjnaoy.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtxahssluz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtskxcpifo.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gtcsvkowgl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gtbjwzaznw.html

[U67] PHP：处理文件上传
来源：http://dali.zhongyouzk.top/Article/details/gtfhropigy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigufen.top/Article/details/gtuhdcfatx.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gtvpptnnet.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aizwys.cn/Article/details/gtpyadnsbz.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gtkqocfoey.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gtbaebsyja.html

[U70] PHP：PDO 事务
来源：http://dali.hysaishi.cn/Article/details/gtnktgfvjf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.andypj.xyz/Article/details/gtcvopkhxa.html

[U71] PHP：抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtxvdgpyzd.html

throw new RuntimeException("失败", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtgugpizxz.html

[U72] PHP：写错误日志
来源：http://dali.yanxiufei.cn/Article/details/gtaoafpolr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gtozqgrybr.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gtpgebsibe.html

parse_ini_file("config.ini", true)
来源：http://dali.vqdsnc.cn/Article/details/gtwlmusvbl.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtogaedsbk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gtepowawmv.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gtlhlrxsgy.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gtmxdpfvwq.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gtoacgovwn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yvedp.cn/Article/details/gtyimbcnnk.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gtvkiqdamb.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdxratml.html

[U78] PHP：单元测试
来源：http://dali.meibo888.top/Article/details/gtfgzpvnmu.html

composer require --dev phpunit/phpunit
来源：http://dali.jiagoushi.top/Article/details/gtlneogdkw.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gtwaihdpox.html

composer require --dev phpstan/phpstan
来源：http://dali.tianlin.xyz/Article/details/gtcxfnkdro.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gtwbykhhxs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtbvkknkqg.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gtyyiklpdb.html

npm init -y;  npm i express
来源：http://dali.hnxiangtu.top/Article/details/gtbkezrsmv.html

[U82] JS：package.json 脚本
来源：http://dali.cucudq.cn/Article/details/gtcixjdlfq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuxming.cn/Article/details/gtrbfeirni.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhixingplan.top/Article/details/gtypmjstwa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtsrhluwnx.html

[U84] JS：CommonJS 写法
来源：http://dali.cheryme.top/Article/details/gtebkufeju.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyvmjllc.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gtbtuqebhq.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gthxzylyee.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gtcbicfztb.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gtxmchckog.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtwezgasbm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gttafuksxn.html

[U88] JS：对象展开合并
来源：http://dali.pycfn.com/Article/details/gtobggnaot.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gtpknqylew.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gtegshyols.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtvxhlsfug.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gtgndjaxbs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtwuefmiic.html

[U91] JS：对象键值遍历
来源：http://dali.jlsjyb.cn/Article/details/gtrapvlyfh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtkalytkrv.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gtxezxocgu.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtqincfccd.html

[U93] JS：模板字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtlwbiszca.html

`共 ${n} 条`
来源：http://dali.hywenlv.cn/Article/details/gtffruvhsj.html

[U94] JS：箭头函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaxdsmtq.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtoxvgworn.html

[U95] JS：Promise 包装
来源：http://dali.smart0.xyz/Article/details/gtlvvmyenh.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gtqewldopx.html

[U96] JS：async/await 与异常
来源：http://dali.hammf.cn/Article/details/gtllhfhjpt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gthlrtohci.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gtojugqtra.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtsqaioyfq.html

[U98] JS：fetch 带 JSON
来源：http://dali.guannengcc.top/Article/details/gtujgvgbrt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhiwuduotai.top/Article/details/gtymkujzvo.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gtpgvaiudt.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtuprabvoj.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtkshlowrv.html

document.querySelector(".item")
来源：http://dali.tian-w.cn/Article/details/gtxvruczkg.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtkrjwdrob.html

el.classList.toggle("active")
来源：http://dali.316326.xyz/Article/details/gthrjclknn.html

[U102] JS：本地存储
来源：http://dali.dianchejie.cn/Article/details/gtqhqojtnh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gtqrgcikua.html

[U103] JS：定时器
来源：http://dali.hongshengwenyu.top/Article/details/gtwljymclz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtywdpemly.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtletajuvs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtxvwtpmrd.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtfovcuyas.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gtprbhsxch.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtlhtifquy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gtvmiwdkef.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gtsvuakmvv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtngtcrkdc.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gtgpradkcp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gtjydizssu.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gtqvujfzku.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gtawqzqnyx.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gtkisbcxlw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gtmqgntlwq.html

[U111] JS：对象转 Map
来源：http://dali.jqgfzy.top/Article/details/gtwyypnpvr.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtiqbnrwaz.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gtzbwfomdf.html

"7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtbdsbmyyx.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtcliawkng.html

s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtccxschhl.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gtmjxhvkwi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtjipsrhkr.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtxhvfiafc.html

crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhitdrhq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gtsjgmkdjg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gtqqlmabem.html

[U117] JS：单元测试
来源：http://dali.c1oappe.top/Article/details/gtnbashlzj.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gtptqaarbm.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gtznqazgbz.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gtauzwdcvo.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gtnqqohicr.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtggbmxqbt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtvoxotjxv.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gtokkjroyz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcymrtpmm.html

统计汇总
来源：http://dali.fengsongda.top/Article/details/gtptifllsf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtivvujari.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtdvrxuplp.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gtyghkjcfd.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtuxtugdgc.html

JavaScript ..... 252
来源：http://dali.dianchejie.cn/Article/details/gtqcquxgyx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gtisoakxpa.html

Java ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtcthqaoqw.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzgjfqbe.html

Ruby ........... 212
来源：http://dali.iojbl.cn/Article/details/gtrapekrfy.html

C# ............. 212
来源：http://dali.yangfankeji.com/Article/details/gthuaacgay.html

C .............. 30
来源：http://dali.hywenlv.cn/Article/details/gtpkcyyyjk.html

C++ ............ 30
来源：http://dali.nwbrower.top/Article/details/gtobzbqmnr.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gtivigsnqk.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjpzghtb.html

Kotlin ......... 15
来源：http://dali.yuxming.cn/Article/details/gtehgjeivf.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtrtjduafn.html

Lua ............ 10
来源：http://dali.guannengcc.top/Article/details/gtgcrqjtzg.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gtycfwvwln.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gtdepkpclq.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtgqmpjiiz.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstppwdub.html

按章节统计：
来源：http://dali.fzhhl.top/Article/details/gtselutvkd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gttzuafclv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtgokrnzms.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtgmvnohom.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gttnmrlpzu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigufen.top/Article/details/gtehcikxko.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtfwiybhwo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gthzblqisr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gtpbpzokhd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtykjmmnnv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtohftlava.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtevjntgme.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtkjhgcjtv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gthjkgvutc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtttguyixh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gtfceavvcs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtorgwyhzq.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtubqbzzfn.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gtntjevlbo.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtqsfplnns.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gtupjjlisc.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gtedioxqnz.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtnddjayog.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gtttiejozf.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtkxjpyivh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gtxjosvkpq.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwxzcrsb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gtuqekffcs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gtvcrpxsrh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gtzymvsynh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gthhxubzrd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gtcnupffgc.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gttymmjxpg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthjoeldlh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtuivrwcow.html

Common Programming Examples Cheat Book
来源：http://dali.zhengqikj.top/Article/details/gtnbnjpzsu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchnihaln.html

【收录内容】
来源：http://dali.dashuyun.cn/Article/details/gtncmmbche.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyksffwm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgfzy.top/Article/details/gtxsruxjer.html

SQL · Bash · C · C++
来源：http://dali.smart0.xyz/Article/details/gtlpdcutnp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jqgfzy.top/Article/details/gtedjscjyc.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gtkoebftow.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxinkj.top/Article/details/gtkgswjpwu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gtgemlszcg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.havefunace.top/Article/details/gtzaiddxok.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gtfhzdkjpr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shzxlz.cn/Article/details/gtbkfvoccx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.birdmap.top/Article/details/gtkjozbudh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gtolrdurjo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gtngsjsgeb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.havefunace.top/Article/details/gtbsvkcgpp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtzqdvbxmm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.andypj.xyz/Article/details/gthodldsmf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gtkjduwios.html

【文件统计】
来源：http://dali.chenlongwang.top/Article/details/gtetnjbbjp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.iojbl.cn/Article/details/gtsxjagmja.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtehssawfg.html

目  录
来源：http://dali.0kj1m.cn/Article/details/gtglmldwxo.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtatuhaxon.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gtrvtdnqtv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtfujnvcxd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtswpcctiw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gttwzlcigp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.guowangkeji.top/Article/details/gtgivblxuo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtdzzthsaa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtqxtktsmp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtqivifqij.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtsrrgohtb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gttgkvneoj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtkxptezul.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtkvkbapmp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gttpefhojp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtpuxmrzww.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gtdxllhyim.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtxmjflviw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.meibo888.top/Article/details/gtqnxchlle.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtdblbusjl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtsextbcgi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gthkmoqaix.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gttgfrjnop.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtknopxmkc.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gtnqprnaap.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbilozfty.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtigvyasfe.html

Py:   print("Hello, World!")
来源：http://dali.daxiang520.top/Article/details/gtfbflthvg.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigufen.top/Article/details/gtsrjlwzgk.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtkyyfalas.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.andypj.xyz/Article/details/gtmfbxzqsm.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtonhwuqjd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtscjvwxfm.html

Ruby: puts "Hello, World!"
来源：http://dali.pengpengdd.cyou/Article/details/gthowujdhi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtnyirpqdy.html

[A02] 变量声明与赋值
来源：http://dali.snrcjt.cn/Article/details/gtwideaeev.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258888.top/Article/details/gtsalzvbdh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtltxrelkn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.daria6918.cn/Article/details/gtbtqfiqhl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtfnmbmsia.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtyjtlltbj.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgfzy.top/Article/details/gtenamiwoj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gtnubxgnml.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtfrwgmgxr.html

[A03] 常量定义
来源：http://dali.nanxinkj.top/Article/details/gtnnoxldxv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtqqhmokwi.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebgqbjca.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtnfloqyjx.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtxowlyofv.html

Java: static final double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtakbcptmf.html

Go:   const PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gtmvqlhblj.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtrwmvvqcd.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtgjjmdocq.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxplujhx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cashguo.top/Article/details/gtkptdvhlz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.haohaochexian.top/Article/details/gtiqwfrhwu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gtxxrbghoe.html

TS:   typeof x; x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gtdrzskegu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.havefunace.top/Article/details/gtyspkvxnl.html


<!-- 参考信息 -->