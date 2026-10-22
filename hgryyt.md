代发 wailian999

[U31] Py：单测
来源：http://dali.hammf.cn/Article/details/gtabmuajhs.html

python -m pytest -q
来源：http://dali.xinyue.icu/Article/details/gtaerhijsd.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gtgecjytpp.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gtwnqbturi.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gtvoyeilow.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gtuwdizxwk.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gtunzthhye.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwilyihoi.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gtzheuchxl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnplzqhm.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gtqpsjykpe.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gtauludgdd.html

[U37] Py：读写 Excel
来源：http://dali.hongshengwenyu.top/Article/details/gtnpsooqij.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gtlwyoevwg.html

[U38] Py：获取脚本所在目录
来源：http://dali.gzhubu.top/Article/details/gtyljyhqti.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gtxmpystzd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhiwuduotai.top/Article/details/gtycellbyr.html

sys.stdout.isatty()
来源：http://dali.birdmap.top/Article/details/gtmqdpypsn.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrisarmk.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtnbmukonv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yueranfly.top/Article/details/gtlzawscep.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ydzc1.top/Article/details/gtqesfkwyy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gtmukpcmkn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuetiantiany.cn/Article/details/gtdzwbfuvz.html

[U43] PHP：声明命名空间
来源：http://dali.hnqzz.top/Article/details/gtrqnccntz.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gtizummzzb.html

[U44] PHP：开启严格类型
来源：http://dali.yuxming.cn/Article/details/gtpixzvreb.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtpkgebivc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gtzxrhmtje.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtocelwcfw.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gtendjxwhj.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gtvcufphvo.html

[U47] PHP：联合类型
来源：http://dali.snrcjt.cn/Article/details/gtbqkmqvpo.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvymxgnd.html

[U48] PHP：纯枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfmkdyum.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gtaovuvwln.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gtawbvbfhg.html

public readonly string $name
来源：http://dali.sufxvd.cn/Article/details/gtadpxdhin.html

[U50] PHP：构造器属性提升
来源：http://dali.dashuyun.cn/Article/details/gtffthulnh.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gtxibnhuia.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gtdyqpfisx.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtgxmnqtau.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtklnyttvx.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtdodeetkt.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gtqjpchkfz.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gtqrfecuug.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gtmaulftxj.html

$obj?->method()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvzqtjzl.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvikjlpuc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtzjsdjtsl.html

[U56] PHP：命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtsltvozbn.html

f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtoljajawo.html

[U57] PHP：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtuqybmcjr.html

"值: {$a}"
来源：http://dali.kuanghao11.cn/Article/details/gtkqmgfuuk.html

[U58] PHP：数组三件套
来源：http://dali.shuidangran.top/Article/details/gtfpilspug.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhixingplan.top/Article/details/gthyjvhzzx.html

[U59] PHP：自定义排序
来源：http://dali.0kj1m.cn/Article/details/gtrulfxbda.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtnuutlfdo.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gtxiocfbld.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yongpay.top/Article/details/gtafdgiyhn.html

[U61] PHP：正则
来源：http://dali.fzhhl.top/Article/details/gtzrwzfrky.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtffwszwob.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvnmpsoa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gtxbkhqejm.html

[U63] PHP：文件读写
来源：http://dali.jianghu66.top/Article/details/gtdcvbjsjj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.havefunace.top/Article/details/gtmbambqzw.html

[U64] PHP：目录遍历
来源：http://dali.zhengqikj.top/Article/details/gtrhqlobcw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gtparrklto.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddjymawa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtgepgxrrn.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gthaxrtazz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gtiotbtssq.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gtcjvmpkuy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gttsvtllfu.html

[U68] PHP：PDO 连接
来源：http://dali.ybcxt.top/Article/details/gtfdltkrsf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphxwtaxo.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtcczshriu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyxaknxt.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gtamdvtcrx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gtojqimjak.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtcbcykyas.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtjlijfifg.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gtscgovpli.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gtmbldchbw.html

[U73] PHP：读取 ini 配置
来源：http://dali.cheryme.top/Article/details/gthlbfqnrk.html

parse_ini_file("config.ini", true)
来源：http://dali.sxryk.cn/Article/details/gthyaxfnag.html

[U74] PHP：读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfexevvt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangshuangyany.cn/Article/details/gtrgjbtegl.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gtrlefuinz.html

composer require psr/container
来源：http://dali.yangfankeji.com/Article/details/gtsewpkuoh.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzchtdgsp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gzhubu.top/Article/details/gtsjgxijue.html

[U77] PHP：模板渲染
来源：http://dali.wangshuangyany.cn/Article/details/gthaulijbj.html

composer require twig/twig
来源：http://dali.yj20258888.top/Article/details/gtnblodhkq.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtanajokpq.html

composer require --dev phpunit/phpunit
来源：http://dali.hammf.cn/Article/details/gtfezxphqo.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gtdzolvrgv.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gtsgdrizcz.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyxymsez.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gtlzkwffur.html

[U81] JS：初始化项目
来源：http://dali.snrcjt.cn/Article/details/gtphzdhpvp.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gtellffxak.html

[U82] JS：package.json 脚本
来源：http://dali.jyoumei.cn/Article/details/gtereiezfa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gtsgjfwnvr.html

[U83] JS：ES Module 导入导出
来源：http://dali.cdnleiting.top/Article/details/gtsoutrpyp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtucigtkwi.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtqrnparat.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fengsongda.top/Article/details/gtyrbbkuts.html

[U85] JS：可选链
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhsdyvki.html

a?.b?.c
来源：http://dali.ydzc1.top/Article/details/gttcudjgxz.html

[U86] JS：空值合并
来源：http://dali.zhengqikj.top/Article/details/gtygynzbqb.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gtmpsozrwf.html

[U87] JS：解构默认值
来源：http://dali.dashuyun.cn/Article/details/gtzszoqboe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gzhubu.top/Article/details/gtoopnfbsi.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gtgsamjucc.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gtaotpuged.html

[U89] JS：数组去重
来源：http://dali.wangshuangyany.cn/Article/details/gtejvvxsmj.html

[...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtdyqaaeax.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gtuzzgqmvl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtjwwsqhws.html

[U91] JS：对象键值遍历
来源：http://dali.dashuyun.cn/Article/details/gtcxjwgnal.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtsewttcga.html

[U92] JS：深拷贝
来源：http://dali.pycfn.com/Article/details/gttzdtttqm.html

structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtleecojqq.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gtldggjwcw.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gtjgkopktw.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtmgvonrpt.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gtzxpuxwiy.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gtnwaclyhr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtufkffrjf.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gttkbnutru.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtnuxgzeuq.html

[U97] JS：并发请求
来源：http://dali.yj20258888.top/Article/details/gthephmqoa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtrpzqzvyw.html

[U98] JS：fetch 带 JSON
来源：http://dali.9152youxi.cn/Article/details/gterluwiyj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gtpylqcpkw.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtomunwcek.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gtsbyozcqs.html

[U100] JS：DOM 查询
来源：http://dali.jinqigfzy.top/Article/details/gtdhnqggmt.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtgnuttdqq.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gtcokoaauc.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtswabglwm.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gtcftnflrg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gtvepsebbc.html

[U103] JS：定时器
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmgjbume.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.9152youxi.cn/Article/details/gtorbfvlks.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gtpjqjzwfo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtybvxdcsn.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gterwobseq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gtuctkjrym.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtshbwmkfx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gtzuqxciez.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtivxvtlvt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrierdmml.html

[U108] JS：随机整数
来源：http://dali.tian-w.cn/Article/details/gtijgzfwrk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gtkoaiwuns.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gtirbbvalz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gteuhjvmky.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gtcfprilxd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gtmokmzmrp.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtkztosvus.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolvgaxww.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gtdmgroytw.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtlkzjtoyl.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gtrmopcoaf.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtsuetxdqb.html

[U114] JS：JSON 深比较
来源：http://dali.gzhubu.top/Article/details/gteezjdhhu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtzspelduf.html

[U115] JS：生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtvwscigwv.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtqysngdbk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gtfryfntag.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gtfsdifqed.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtcpohvvfj.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gtpadmmyit.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gtvlusunaw.html

npm i -D vite;  npx vite
来源：http://dali.jinqigfzy.top/Article/details/gtyyitqpnw.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtfrfhizkd.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gtwioeignd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gtleghtgrx.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gtusyulosc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmnjehwsq.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtodoojxye.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtiinqpgjm.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gtjqvbkjlo.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gtqtrdnnnu.html

PHP ............ 252
来源：http://dali.xziqi.cn/Article/details/gtqyoveqai.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gtclrssykg.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gtfbcusazl.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtsqfjmduq.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtrqwpvgze.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtehwpnfov.html

C# ............. 212
来源：http://dali.fzhhl.top/Article/details/gtuvzygmgs.html

C .............. 30
来源：http://dali.cucudq.cn/Article/details/gtvvcymveg.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gtdvhwdxkc.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gtpjaqtgad.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gtwryoppmf.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gttykidpna.html

Swift .......... 15
来源：http://dali.yvedp.cn/Article/details/gtewnhcwmy.html

Lua ............ 10
来源：http://dali.mhx1999.top/Article/details/gtpdqxhbrp.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gtwdsgnoir.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtgootbkig.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtwrdfxxmg.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gtyifcoggi.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtbfjpgdip.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtpkkzugrj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtdeurkzaq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtdphuynqi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gthupobgek.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yvedp.cn/Article/details/gtkmvjtygl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtmcoeuwzu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gthspfhtwy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gttbpjuygh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtajeykmtm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtbztabwpq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtbflodhoy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtnlbdkktv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtdbfawxlj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gteosamwcr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.havefunace.top/Article/details/gtkkxvxuch.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtjvksqzqf.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gtbumigcyr.html

R Bash 专题                             80
来源：http://dali.zdqjudy.top/Article/details/gtgfjittyc.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gtcrhhsocs.html

T 其他语言补充                          60
来源：http://dali.hammf.cn/Article/details/gtzkfzhoxg.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gtwbkhbdhc.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gthgftrtra.html

合计                                  2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtedyvsmvl.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtrmjujeap.html

使用提醒
来源：http://dali.jinqigufen.top/Article/details/gttcqhrgpz.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtrimqoavl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sweek.top/Article/details/gtydxrishq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gtzsdxnkzf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjrjjfls.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gtltsczimr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenlongwang.top/Article/details/gtyzddfiqg.html

—— 文件结束 ——
来源：http://dali.jinqigufen.top/Article/details/gtknpbknmc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlzqcgffk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gtxezbfyho.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gtqhounrat.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiligewjg.html

【收录内容】
来源：http://dali.mhx1999.top/Article/details/gtguxkecym.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cdnleiting.top/Article/details/gtpkkzkmzm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hongshengwenyu.top/Article/details/gtvmqrfpqp.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gttdegvdoy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.kuanghao11.cn/Article/details/gtugxjdczk.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gttpdhcsnb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gtjwpbqlnm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigfzy.top/Article/details/gtoqghszuw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fzhhl.top/Article/details/gtgjdoxlwq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aibaodan.cn/Article/details/gtmrzwyvce.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gtuspqdbax.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnqzz.top/Article/details/gtkfxxbwih.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gttheclavq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258.top/Article/details/gtnpivraga.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.316326.xyz/Article/details/gtuvaayqpf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hysaishi.cn/Article/details/gtjmxomtba.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hfpthk.cn/Article/details/gtbnnisrrt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.meibo888.top/Article/details/gtghperwkb.html

【文件统计】
来源：http://dali.feifeiyinyue.top/Article/details/gtfviqodtq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zdqjudy.top/Article/details/gtxjglzuhx.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtffqxrawg.html

目  录
来源：http://dali.hnxiangtu.top/Article/details/gtkbhpuuqy.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gthmjyyare.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtyjfvuhja.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtpeuvbsrg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtcmjfsria.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gthcgccsua.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gaohongyu789.top/Article/details/gtmlpyqlvr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtcepuoucv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtmykgljir.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtcqezktzu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtqouajaph.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtarvesmdl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtvczdzemg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gteqopures.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gttsnatgip.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtsgtjrllw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.mhx1999.top/Article/details/gtuhkdhcwn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtfognasqs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gtdbwnshem.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.birdmap.top/Article/details/gtplekyxuf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtlgvyuvst.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtackvmmte.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtsghdwxvr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmdyvfmkc.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gtuyemscex.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpyrvzoru.html

[A01] Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhewvxel.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtqdwznfot.html

PHP:  echo "Hello, World!";
来源：http://dali.vqdsnc.cn/Article/details/gtwfniogqe.html

JS:   console.log("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtncyozysd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.smart0.xyz/Article/details/gtqrlxwemg.html

Java: System.out.println("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtwfgmklnd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gtkzbvhjcp.html

Ruby: puts "Hello, World!"
来源：http://dali.iojbl.cn/Article/details/gtvooncosf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtbxrvgetw.html

[A02] 变量声明与赋值
来源：http://dali.birdmap.top/Article/details/gtubxdfefh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtxyaqebpx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtmffnoayl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtctsxsjwr.html


<!-- 参考信息 -->