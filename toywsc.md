代发 wailian999

[U31] Py：单测
来源：http://dali.hammf.cn/Article/details/gtqirffghl.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gtiqnfegss.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gtdhiaslon.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtlezmkomd.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gtetjimhcd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gtfiujnuwo.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gtmrjcvidk.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gtxggsnnxw.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxashyqv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gogol.net.cn/Article/details/gtfwvtrrja.html

[U36] Py：定时任务
来源：http://dali.gaohongyu789.top/Article/details/gttyamdrub.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtmkskmuxq.html

[U37] Py：读写 Excel
来源：http://dali.shangyingyoupin.top/Article/details/gtdvxwxtqh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtobjsszwg.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxovldbsi.html

Path(__file__).resolve().parent
来源：http://dali.yangfankeji.com/Article/details/gtddorxosw.html

[U39] Py：判断是否在交互环境
来源：http://dali.gzhubu.top/Article/details/gtjjcsznbs.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtpuqywssk.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gtteypcved.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtujlfmwpu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyconxip.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gteounyipy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gaohongyu789.top/Article/details/gtlzymifrz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gotoacloud.top/Article/details/gtgzbdchbs.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtenkrxuov.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtalevyhjj.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gtzalwjbcm.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gtmowyjiwo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gteglyekef.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtwbdjeisg.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gttumbhhhj.html

?string $name = null
来源：http://dali.andypj.xyz/Article/details/gtjwsbvssu.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gtpksilhdg.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbegzhzqn.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gtfnmoxcvx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gtywwjdcyv.html

[U49] PHP：只读属性
来源：http://dali.guowangkeji.top/Article/details/gtnawjrmbv.html

public readonly string $name
来源：http://dali.smart0.xyz/Article/details/gtyaxlqzkx.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gtnlkaklzd.html

public function __construct(private int $id) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpgiosctq.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gthuornhkm.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmljooblx.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtpseagtss.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gtwuvydwqg.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gtawfnsrso.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gtxpbknoux.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gthdqasnur.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtfeuvqz.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gtxnsjwiwu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtxxvsxyjt.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gtowifnfpb.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gttnczbyfy.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtdftercbc.html

"值: {$a}"
来源：http://dali.sufxvd.cn/Article/details/gtqdjxdmya.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtstdntuil.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shzxlz.cn/Article/details/gtihxtfqzx.html

[U59] PHP：自定义排序
来源：http://dali.yj202588.top/Article/details/gtwrkmztqr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtwbolcuzn.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gtabtvkhsw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gtwwlxepxj.html

[U61] PHP：正则
来源：http://dali.yangfankeji.com/Article/details/gtrtqdtgck.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtupltynof.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gtevkxfnxd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fzhhl.top/Article/details/gtaefhcmsh.html

[U63] PHP：文件读写
来源：http://dali.ydzc1.top/Article/details/gtizxjhhwk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gtljtauqat.html

[U64] PHP：目录遍历
来源：http://dali.sweek.top/Article/details/gtbhcstwmm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gtuvwrltcj.html

[U65] PHP：会话
来源：http://dali.cdnleiting.top/Article/details/gtekmvfgik.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtoukesbdg.html

[U66] PHP：设置 Cookie
来源：http://dali.jlsjyb.cn/Article/details/gtvfekclcn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtkroeneiq.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrusiyvv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangshuangyany.cn/Article/details/gtzjepikej.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtqjaiwgkz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtuytqmfxh.html

[U69] PHP：PDO 预处理
来源：http://dali.xziqi.cn/Article/details/gtobhjyret.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yangfankeji.com/Article/details/gtdqqiabjt.html

[U70] PHP：PDO 事务
来源：http://dali.ybcxt.top/Article/details/gtjohvyphz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tian-w.cn/Article/details/gtdipdntjb.html

[U71] PHP：抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtxlijutdy.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcewpuorp.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gtywyvktxp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fengsongda.top/Article/details/gtptjbjftl.html

[U73] PHP：读取 ini 配置
来源：http://dali.iojbl.cn/Article/details/gtlkhbwslv.html

parse_ini_file("config.ini", true)
来源：http://dali.ivvv.top/Article/details/gtofboysqd.html

[U74] PHP：读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrshbrcw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gtugedpbdb.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gtebyemmgz.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gtmhdkxbdn.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gtleofkkkd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gtdlaqzwpc.html

[U77] PHP：模板渲染
来源：http://dali.tianlin.xyz/Article/details/gtnivgvuyh.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gtbhjzvpnh.html

[U78] PHP：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtaehrsfbm.html

composer require --dev phpunit/phpunit
来源：http://dali.yangfankeji.com/Article/details/gtgsgcvywl.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gtqayxqcvz.html

composer require --dev phpstan/phpstan
来源：http://dali.cashguo.top/Article/details/gtyuillhfe.html

[U80] PHP：代码规范修复
来源：http://dali.xuanzx.com/Article/details/gtsdnvtcuh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuetiantiany.cn/Article/details/gtktmbljxp.html

[U81] JS：初始化项目
来源：http://dali.jinqigfzy.top/Article/details/gtynmwzaff.html

npm init -y;  npm i express
来源：http://dali.cashguo.top/Article/details/gtxxxsxlze.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnxpuwag.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gtfgjzmgxx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhengqikj.top/Article/details/gtkmljwcfq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gttcxfisxy.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gtbgogbffd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtzwmkllzb.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtlzqxuvzo.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gttdnqbhjc.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gtcundykbf.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gtqzoahkrf.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gtedrjqdur.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gtdtxfvdjk.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytbysjob.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gtfylmnmql.html

[U89] JS：数组去重
来源：http://dali.aizwys.cn/Article/details/gtcyhialxs.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtrcxrfykn.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gtzbhsrocb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtqmujubqm.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtlbcrvovl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gtlbhlxpzh.html

[U92] JS：深拷贝
来源：http://dali.yueranfly.top/Article/details/gtysonvkus.html

structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtafigvujp.html

[U93] JS：模板字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdrrcsnc.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtkorghxef.html

[U94] JS：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gtxojmzfqe.html

const double = x => x * 2;
来源：http://dali.cheryme.top/Article/details/gtkhzexawo.html

[U95] JS：Promise 包装
来源：http://dali.jinqigfzy.top/Article/details/gtuojdxbzm.html

new Promise((resolve, reject) => {})
来源：http://dali.zycfv.cn/Article/details/gtqxbibkjt.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gtwsaqsijd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtskynyhdp.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gtglkylyeh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtqnlrbugz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtcfbomojx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtooompebi.html

[U99] JS：事件监听
来源：http://dali.tian-w.cn/Article/details/gtieexvbdj.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gthanfrxnc.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gtbvwzmszo.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gtyvouumcm.html

[U101] JS：classList 操作
来源：http://dali.jinqigfzy.top/Article/details/gtkuawlseo.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gtitjfvxfk.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gtvcmxuuit.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gtdzumnwxp.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gtqwklxigf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gtoqgmtlpl.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaffpuxp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtmseefsjc.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gtxteovxbn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.havefunace.top/Article/details/gtuurrrowm.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtqjkodbls.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtkboiziae.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gtgxkywshk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtsrswbzkn.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtsxmvrijb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenlongwang.top/Article/details/gtsnfkrhfm.html

[U109] JS：数组分组
来源：http://dali.hnxiangtu.top/Article/details/gtnbjnfdsf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gthevwuaue.html

[U110] JS：数组分块
来源：http://dali.pengpengdd.cyou/Article/details/gtdbjceheh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gtnqsruozb.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gtvfzwargm.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gtcbthqtqs.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gtqxblzglr.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtfphcjwgi.html

[U113] JS：正则替换全部
来源：http://dali.jlsjyb.cn/Article/details/gtctzealzm.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gthaqhhdlz.html

[U114] JS：JSON 深比较
来源：http://dali.chenlongwang.top/Article/details/gtjyzygjvs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtbxdloqrg.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrifkyhka.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtgwrtkief.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtbexhgxyx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtecupmgth.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtbsreksth.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gtsobhbcem.html

[U118] JS：开发服务器
来源：http://dali.hywenlv.cn/Article/details/gtbbzybtlp.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gtmbhwalpg.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtdbznhsyk.html

npx vite build
来源：http://dali.xylfe.cn/Article/details/gtfyvnnndv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gtneecqtuc.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gtmxogikec.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrcpdjfjf.html

统计汇总
来源：http://dali.yj20258888.top/Article/details/gtpfihicmy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtevrcomat.html

按语言统计（条）：
来源：http://dali.chenjidiqi.icu/Article/details/gtuxzxrxjd.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gtcyzwldda.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gthmdgegmi.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gtgwxryptl.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gtddnsckkr.html

Java ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtlymqdqpo.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtoinwqyue.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtpqtqxyfb.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtfrevkfnk.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtfatgmzml.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gtsotglhqi.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gtblbvjwmi.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gtvpoaklvu.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gtzsasabyg.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gtlxllxcty.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtyjbddmsf.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtqdwcghef.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gtfboybwao.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtjdvkvutb.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gtcenqiqti.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gtmvvybksq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtryblhlhh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtzlbjzvrw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtlwuadorr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtqnzfoyll.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgbnrymp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomblrnwa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtswsgkztt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtntgblehe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtuojjpaob.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtoojffrhw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtbdathwgj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtktxjmrja.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gthdqtifsn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtamoalida.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gtqpqqtupd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtqbljlqkl.html

Q SQL 专题                              90
来源：http://dali.quarkkingdee.top/Article/details/gtdzzmpuwy.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gtjqfakztu.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gtvqrrnphp.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gtehgnngwg.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gtzsrtukkg.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gtkwdpsubz.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gtlgwdppyk.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtbugnuyfi.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gtksreieko.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtagrjabis.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gtffhzrqwi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gtxpkjfpct.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuanzhike.top/Article/details/gtjuwxzmlu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gtcfdsnqzv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtptjnnskm.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gttzhneaai.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkjzhhzwu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cucudq.cn/Article/details/gthbmxpekj.html

Common Programming Examples Cheat Book
来源：http://dali.nanxinkj.top/Article/details/gtcmaajjxa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtggcbhwck.html

【收录内容】
来源：http://dali.xuanzx.com/Article/details/gteerlqqap.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gtwiymqdzg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.316326.xyz/Article/details/gtcxmbmqyb.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gtkjobybdw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gtkwffmwur.html

【使用说明】
来源：http://dali.shuidangran.top/Article/details/gtkevkxvxy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gtiaepxvev.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtwbfvslja.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj202588.top/Article/details/gtddtxfpjv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gtovtiulpp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hywenlv.cn/Article/details/gtwpmmyasn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sweek.top/Article/details/gtokgiggyb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.316326.xyz/Article/details/gtvoccfjdv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtberrqxzl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gtutjbnsfr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangdashe.top/Article/details/gttssteuyt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aibaodan.cn/Article/details/gtwehigubk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ydzc1.top/Article/details/gtwnwsqjjh.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtjugzlemt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gtvnsuocei.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtomtmjgls.html

目  录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszxwvfcf.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gttzoyxfdt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtxfathnco.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtzvwtdazn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtyhdnfuke.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtmqpcdokk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtsnqmiukv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gtzocjsffu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtlmsfetjv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzzwdoxj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtfbesnajo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtvaaoxbyu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gthvxcgufz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtsonrryrh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gthpkbsvzk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtbwyvbidr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gtajpzgzlz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtnhnmtaso.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gtmqxyiqsa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtyrvfabrm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gtxqzaashl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtelmnevnk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtwdjucreu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttepxbmiz.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gtmlphionp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbjvjxctw.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gtczvrkttw.html

Py:   print("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtfkkpnydt.html

PHP:  echo "Hello, World!";
来源：http://dali.hywenlv.cn/Article/details/gtokwwmlgw.html

JS:   console.log("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtypgypbbi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzcyopyd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtqqwrhgfm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjgnalmc.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gtiktabmmj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtmvqsllfi.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gtwrqujqhk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hywenlv.cn/Article/details/gtpqjknynj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gthnovzypr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtlczwglga.html


<!-- 参考信息 -->