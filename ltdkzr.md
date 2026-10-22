代发 wailian999

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedddmwmv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.kuanghao11.cn/Article/details/gtxopodnju.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gtsnxjphib.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gtcgposldt.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gtpkkjqitn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xylfe.cn/Article/details/gtsfelyscu.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtpyvltalc.html

schedule.every(10).minutes.do(job)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhxzuutg.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gtnewmctxu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cucudq.cn/Article/details/gtemvkgapn.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gtndczjwme.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gthlskdigz.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258888.top/Article/details/gtridzocur.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gtzkpgemen.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdedxdmb.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtpmtudbts.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtkcrasurp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtzvpunits.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daria6918.cn/Article/details/gtedhptmvt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hywenlv.cn/Article/details/gtvrtwccwm.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtropczcxh.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gtssmclzxw.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gtcskaacuz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gtyykrtfhu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258.top/Article/details/gtklmfhqll.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtlbldemkq.html

[U46] PHP：可空类型
来源：http://dali.shzxlz.cn/Article/details/gtpppwwlib.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtozlqqgnp.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gtuhdgmczd.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gtcpevfszx.html

[U48] PHP：纯枚举
来源：http://dali.zhoulong.xyz/Article/details/gtjdikgabi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gteepmfmvy.html

[U49] PHP：只读属性
来源：http://dali.ehwqpu.com/Article/details/gterncgpfj.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtktvnkmnp.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtuqivjbzr.html

public function __construct(private int $id) {}
来源：http://dali.shuidangran.top/Article/details/gtdegderim.html

[U51] PHP：数组解构
来源：http://dali.nanxinkj.top/Article/details/gtgzijotfa.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzfetioh.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtlxfqjxvx.html

$double = fn($x) => $x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtluolqftr.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gtqcgrlswx.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gtwtlykdgc.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtflqblaya.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gtfhjgviui.html

[U55] PHP：match 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtwnzkxhqk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtczszdnqp.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtnzxbuyjq.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtowgazzsp.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtazhqjdoy.html

"值: {$a}"
来源：http://dali.yj20258.top/Article/details/gtexzaxugm.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gtmgsbgkkr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cheryme.top/Article/details/gtjexubzhg.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gtdsvdrxav.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtfyyadjbw.html

[U60] PHP：JSON 编解码
来源：http://dali.dianchejie.cn/Article/details/gtsrtmsepr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gtcexptglh.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtxdeupygh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtcfyljiyj.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gtwvdhatyz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gtjtehuizb.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gtedlrtndk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtcamqjkvy.html

[U64] PHP：目录遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtzravdzjo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenlongwang.top/Article/details/gtrhmhodwx.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gtmiyiwuof.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gtcfrowsxs.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gtdbmuduwb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gtmfqnomui.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gtcteklvkj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sufxvd.cn/Article/details/gtscjpzdpd.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtxaeoshis.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zycfv.cn/Article/details/gtqdekkjod.html

[U69] PHP：PDO 预处理
来源：http://dali.xinyue.icu/Article/details/gtcqcvmwai.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhiwuduotai.top/Article/details/gtmbhvljpy.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gtjkmgaypr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanwegpsr.html

[U71] PHP：抛出异常
来源：http://dali.yj202588.top/Article/details/gtefbdxisq.html

throw new RuntimeException("失败", 500);
来源：http://dali.jianghu66.top/Article/details/gtfbyfzxhq.html

[U72] PHP：写错误日志
来源：http://dali.chenjidiqi.icu/Article/details/gtjjpeawtk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gtbixkuwst.html

[U73] PHP：读取 ini 配置
来源：http://dali.fzhhl.top/Article/details/gtwnwbvwwc.html

parse_ini_file("config.ini", true)
来源：http://dali.cheryme.top/Article/details/gtdxsasflh.html

[U74] PHP：读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtgfvkzkke.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtlldunlpd.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gtjrwmabjm.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gtbxlxnkzx.html

[U76] PHP：简单路由
来源：http://dali.hnqzz.top/Article/details/gtarzolmsb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtyuvpjivx.html

[U77] PHP：模板渲染
来源：http://dali.hfpthk.cn/Article/details/gtpcjsghim.html

composer require twig/twig
来源：http://dali.xziqi.cn/Article/details/gtwedrdahz.html

[U78] PHP：单元测试
来源：http://dali.fengsongda.top/Article/details/gtmujcqpuh.html

composer require --dev phpunit/phpunit
来源：http://dali.jyoumei.cn/Article/details/gtjiphcubb.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamypoldr.html

composer require --dev phpstan/phpstan
来源：http://dali.yueranfly.top/Article/details/gtezxqiace.html

[U80] PHP：代码规范修复
来源：http://dali.nanxuanxn.top/Article/details/gtpogpqryy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gtpcxbgaks.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gtymoermjb.html

npm init -y;  npm i express
来源：http://dali.chenjidiqi.icu/Article/details/gtuwsldhph.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gtqlnkkwjy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gtvhiyixzq.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gtaokxvukc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtemgxuepy.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gttlnjpofb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gtribcwwhh.html

[U85] JS：可选链
来源：http://dali.chenjidiqi.icu/Article/details/gthkvytjxn.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gtdqrpwwrd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gtswuoahlj.html

a ?? b
来源：http://dali.gaohongyu789.top/Article/details/gtttmsquuh.html

[U87] JS：解构默认值
来源：http://dali.hywenlv.cn/Article/details/gtiizoohau.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gtnrwmxdyt.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gtlyrfveux.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gthfzoikal.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gtsytldkri.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtezgszwsi.html

[U90] JS：数字数组排序
来源：http://dali.birdmap.top/Article/details/gtbdtsfdez.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtmduymvcx.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvtniqzv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtkkuuzpwn.html

[U92] JS：深拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrqujiys.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtlramkvuv.html

[U93] JS：模板字符串
来源：http://dali.chenlongwang.top/Article/details/gtbpasjtvn.html

`共 ${n} 条`
来源：http://dali.9152youxi.cn/Article/details/gtlzrvbqtc.html

[U94] JS：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gthhxitwoo.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtyvfgllur.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gtsmkoklhj.html

new Promise((resolve, reject) => {})
来源：http://dali.fzhhl.top/Article/details/gttpmdaioq.html

[U96] JS：async/await 与异常
来源：http://dali.aizwys.cn/Article/details/gtaulskuki.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtddbeagpn.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtlzsceegk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtnrbgcoct.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gtiiwqkidp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.0kj1m.cn/Article/details/gtvqyfunkk.html

[U99] JS：事件监听
来源：http://dali.svipenyu.cn/Article/details/gtcmyyewvm.html

el.addEventListener("click", e => {})
来源：http://dali.ydzc1.top/Article/details/gtfkaayhxl.html

[U100] JS：DOM 查询
来源：http://dali.jinqigufen.top/Article/details/gtcntexftl.html

document.querySelector(".item")
来源：http://dali.zhiwuduotai.top/Article/details/gtfywrfuoc.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gtahbtumqv.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gtrqzmqfvb.html

[U102] JS：本地存储
来源：http://dali.quarkkingdee.top/Article/details/gtqcfnoyun.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gteacpgmct.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gtahxtlouh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gtrcpfmrtb.html

[U104] JS：防抖
来源：http://dali.cashguo.top/Article/details/gtwctypahh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtnlblmbae.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gthgjpehle.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cheryme.top/Article/details/gtlukipdwi.html

[U106] JS：日期格式化
来源：http://dali.guannengcc.top/Article/details/gtamkjiacp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtdyjnaakd.html

[U107] JS：数字千分位
来源：http://dali.shuidangran.top/Article/details/gtdvgcbwys.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtodvjnrnn.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrqvxhzd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtmtrwiibt.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtvlrgtjvb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtsoichuyg.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gttbgdmebc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gtnpkpzvpn.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gtdjnllsmf.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gtcbseaglg.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gteopmxhqs.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtqmfrruvw.html

[U113] JS：正则替换全部
来源：http://dali.pycfn.com/Article/details/gtsptemhaw.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtfxhqfshb.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gtszorfjgf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtkdctftrt.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtutcqtqqj.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gthxhlkfxt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gtfxvzvrze.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gtclaljtya.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtamvvpqmx.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gtqscxmtvi.html

[U118] JS：开发服务器
来源：http://dali.havefunace.top/Article/details/gtbzdqdsmt.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gtyawcnxce.html

[U119] JS：生产构建
来源：http://dali.nanxuanxn.top/Article/details/gtgsaxeqvn.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtnrcodfyr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtrhchcpcl.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtodzbzrpj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpzprwgrn.html

统计汇总
来源：http://dali.yvedp.cn/Article/details/gtpujrersc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsocmeuyn.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gtuyzrqcls.html

Python ......... 252
来源：http://dali.gzhubu.top/Article/details/gtbvtrbxch.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gtssdqunft.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtqklvdxby.html

TypeScript ..... 212
来源：http://dali.gotoacloud.top/Article/details/gtpugcmbla.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gticfztjfw.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gtvgtqnshi.html

Ruby ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtfnmtvbmc.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gtxnzkvkyg.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gtskmwvace.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gtvrsmkmlj.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtqcpwoiik.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtzrmflmxy.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtryjrjico.html

Swift .......... 15
来源：http://dali.ppjwa.cn/Article/details/gtdpisdghg.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtcadgykgw.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtieoicdfx.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtbheyisqo.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtfhqrsfwp.html

合计 ........... 2106 条
来源：http://dali.ppjwa.cn/Article/details/gtkfreiitk.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gtfxvmbsew.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtfuaaluay.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtxebbfpui.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtgyfebhgf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtutecshvl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gtjsqepbna.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtgxssbanu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtpqspoxig.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtrrzhgzmu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtrkkwigft.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtyekqhrfz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtctgfaohp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtfntrgnso.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtluphlpfv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtvqxoupsw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gtboaegqvf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtccdwzdyx.html

Q SQL 专题                              90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyfqhwkq.html

R Bash 专题                             80
来源：http://dali.hywenlv.cn/Article/details/gtyvufwfuc.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gtxqnagpjc.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gtavgjhpfa.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gtdrdqzxui.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtfafqnbvw.html

合计                                  2106 条
来源：http://dali.xuanzx.com/Article/details/gtlbduxruo.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtvcbgwclp.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtittilfqt.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtxxmfiihc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jianghu66.top/Article/details/gtgtfmlyiu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ppjwa.cn/Article/details/gtstjpuxto.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gotoacloud.top/Article/details/gteaviysnw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangtech.top/Article/details/gtahsazcki.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yonumen.top/Article/details/gtvjddbnna.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gthcufervn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxhwpjzvi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxinkj.top/Article/details/gtfykqrglj.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gtxgqltldm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsbqlfemm.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gtsibpndst.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gtgxvsvpeb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdryfdto.html

SQL · Bash · C · C++
来源：http://dali.ehwqpu.com/Article/details/gtztmobzul.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenjidiqi.icu/Article/details/gthwebttzy.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gtgmaristr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gtnithisoi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tanke756.top/Article/details/gtjtezlmhr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtcgoyeaxx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ppjwa.cn/Article/details/gtqcopunhl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gtpycgrikf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xinyue.icu/Article/details/gtyycivhjc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gtdrjffqjs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yueranfly.top/Article/details/gtvmprkapb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ehwqpu.com/Article/details/gtfyuszwgj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtouxscnau.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxuanxn.top/Article/details/gtxagwrpdl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gtfyxmevbp.html

【文件统计】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgpyutlf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuetiantiany.cn/Article/details/gtwtczpqrh.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtmwkttjls.html

目  录
来源：http://dali.xylfe.cn/Article/details/gtartsaghd.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtyklmhknw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtzhcqxkfr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtmtgdmeva.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtrkphdogb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtuoqnqvsp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nwbrower.top/Article/details/gtxyayyrrz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gthwkambhe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtabgsbkfp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtxuuxxyqz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtzbljogiu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtueorovyy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gteavkxivq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtzlskiyrr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtnyvsvfex.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj20258.top/Article/details/gtbgddyllg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gtxyqnisaq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gteylwkhws.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gtfgzdxumf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yangfankeji.com/Article/details/gtklcnafao.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.quarkkingdee.top/Article/details/gtrjjqitxg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gthewyawnx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtaujjmoqn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtinhsexxs.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gtwdvajusk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbejwutjf.html

[A01] Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtkpjetmxs.html

Py:   print("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtfouyggac.html

PHP:  echo "Hello, World!";
来源：http://dali.sysykeji.top/Article/details/gtkjwigiuz.html

JS:   console.log("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtnvbkdamy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gttscvvukq.html

Java: System.out.println("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtygpryeoz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtpgmikixx.html

Ruby: puts "Hello, World!"
来源：http://dali.0kj1m.cn/Article/details/gtlnnsupff.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtlfftdrgf.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtezwqfcns.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gtgidcgttb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtpvkabisz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hammf.cn/Article/details/gtrzomydno.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtiwzxngyq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtrehlxdhp.html

Go:   name := "Alex"; age := 20
来源：http://dali.ybcxt.top/Article/details/gtgnksbkiy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pycfn.com/Article/details/gtuclhpawh.html


<!-- 参考信息 -->