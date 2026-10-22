代发 wailian999

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmzcrzbr.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtaghqkzpr.html

[U32] Py：代码格式化
来源：http://dali.yvedp.cn/Article/details/gtxbbnpatf.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwkvayus.html

[U33] Py：打包发布
来源：http://dali.vqdsnc.cn/Article/details/gtqjwcfyil.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtekayrenk.html

[U34] Py：判断编码
来源：http://dali.haohaochexian.top/Article/details/gtgrhwffhg.html

chardet.detect(raw)
来源：http://dali.jqgfzy.top/Article/details/gtypvcpbnc.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gtnwmudnvi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtcrrquerw.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gttixfszcx.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenzaomai.com/Article/details/gtmafcerdo.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gtkaxhmjzf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gtfhoedgtq.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gtjaobdkan.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtulkqnjmd.html

[U39] Py：判断是否在交互环境
来源：http://dali.316326.xyz/Article/details/gtmbcuxvmm.html

sys.stdout.isatty()
来源：http://dali.bjfxy.top/Article/details/gtkgtuawjm.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gtiriaqknp.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtpiyxmtks.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gtqyfdgioi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gtatbaqmls.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtggeddhrn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtvypflavp.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtynigfwqa.html

namespace App\Http;
来源：http://dali.jyoumei.cn/Article/details/gtnfbetmkw.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gtevsphixc.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gtbjqymrqf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtpfygcaym.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtivmsakab.html

[U46] PHP：可空类型
来源：http://dali.iojbl.cn/Article/details/gtyycsifoo.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gtressrxje.html

[U47] PHP：联合类型
来源：http://dali.daria6918.cn/Article/details/gtujkfvano.html

int|string $id
来源：http://dali.yuxming.cn/Article/details/gtealfutmn.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gtsupzybkh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cheryme.top/Article/details/gtymxodnxv.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gttvytppaj.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gtgqxuisav.html

[U50] PHP：构造器属性提升
来源：http://dali.yuanzhike.top/Article/details/gttrbbzesh.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtppsxzyxp.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtgfwknlxn.html

[$a, $b] = $arr;
来源：http://dali.mhx1999.top/Article/details/gteshaabva.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtdqednbof.html

$double = fn($x) => $x * 2;
来源：http://dali.ybcxt.top/Article/details/gthhdzwyrw.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtnwtbkcve.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gtkwjsscbo.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtxbubxbow.html

$obj?->method()
来源：http://dali.zhiwuduotai.top/Article/details/gtlrwdbhgb.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gtagiaxlja.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtdvaqhlxb.html

[U56] PHP：命名参数
来源：http://dali.ppjwa.cn/Article/details/gtjgvjfydu.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gthypnubsu.html

[U57] PHP：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtmbwtbeyy.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gtsoyxtpei.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gtmzyvcwfu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dianchejie.cn/Article/details/gtnkwrygdi.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtllnlegvj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtzsqfjrvs.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gtzxnwcqqd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gtivwvmtgf.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gthzkzdccz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtppelxvrr.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gtvpsdxgpk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtsmpixxls.html

[U63] PHP：文件读写
来源：http://dali.yongpay.top/Article/details/gtvdktacua.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtheieismr.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gthzagpkbo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtoyeuwqda.html

[U65] PHP：会话
来源：http://dali.zhengqikj.top/Article/details/gtrxhhbfkm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtyfzplnab.html

[U66] PHP：设置 Cookie
来源：http://dali.316326.xyz/Article/details/gtlohunqdn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yvedp.cn/Article/details/gtnrgvrmer.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzpnltln.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jianghu66.top/Article/details/gtfkenjtcs.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtcvltnrzu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shzxlz.cn/Article/details/gtgqlvozrg.html

[U69] PHP：PDO 预处理
来源：http://dali.hnxiangtu.top/Article/details/gtvaxzpbpp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jiagoushi.top/Article/details/gtjavachnq.html

[U70] PHP：PDO 事务
来源：http://dali.ydzc1.top/Article/details/gtvldikcoq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xylfe.cn/Article/details/gtbhclzinr.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtiphkwkvp.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtznjekust.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gtzcnfwzox.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtialkythr.html

[U73] PHP：读取 ini 配置
来源：http://dali.guannengcc.top/Article/details/gtudzytvfg.html

parse_ini_file("config.ini", true)
来源：http://dali.ivvv.top/Article/details/gtfyrmebdr.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtcwzpfenx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhgxpmzi.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwgqeqzv.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gtywvmlilk.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gtauyzeeou.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jyoumei.cn/Article/details/gtzuysslzl.html

[U77] PHP：模板渲染
来源：http://dali.redwolf501.top/Article/details/gthdkghbds.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gtdzapfsxz.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gtwldlgxej.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gtlifbcwvq.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gtmhpiejdr.html

composer require --dev phpstan/phpstan
来源：http://dali.yanxiufei.cn/Article/details/gtvwnsojvy.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtpgunpjnw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbeqwlkw.html

[U81] JS：初始化项目
来源：http://dali.ivvv.top/Article/details/gtfmzenufb.html

npm init -y;  npm i express
来源：http://dali.c1oappe.top/Article/details/gtoqysphqa.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gtxyevfnvc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ehwqpu.com/Article/details/gtqsjefonx.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtqwfrecvi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtysvgfhik.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gtnyfsbmvp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gtulodakkg.html

[U85] JS：可选链
来源：http://dali.jinghuilouyu.cn/Article/details/gtosfbuimn.html

a?.b?.c
来源：http://dali.jlsjyb.cn/Article/details/gtntyvpqip.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gtpkneobrc.html

a ?? b
来源：http://dali.jinqigufen.top/Article/details/gtdtxumswx.html

[U87] JS：解构默认值
来源：http://dali.daxiang520.top/Article/details/gttvrkmjrq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gtszmotofp.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtyqtlteob.html

{ ...a, ...b }
来源：http://dali.mhx1999.top/Article/details/gtywnmcwzd.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gtafczmfbh.html

[...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtsflitkfw.html

[U90] JS：数字数组排序
来源：http://dali.gogol.net.cn/Article/details/gtbfdirjna.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtptveewir.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtlyfderny.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangdashe.top/Article/details/gtusclltlb.html

[U92] JS：深拷贝
来源：http://dali.yvedp.cn/Article/details/gtknagdcdt.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gttloubvpo.html

[U93] JS：模板字符串
来源：http://dali.yj202588.top/Article/details/gtzsbkgthx.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gtbyvrmzin.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtsjyhisoq.html

const double = x => x * 2;
来源：http://dali.redwolf501.top/Article/details/gtcguweoad.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangtech.top/Article/details/gtatizutqx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhkrcesa.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gtizeedgge.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtssjfvsvu.html

[U97] JS：并发请求
来源：http://dali.tanke756.top/Article/details/gtnaikicxn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtudnzzakc.html

[U98] JS：fetch 带 JSON
来源：http://dali.shuidangran.top/Article/details/gthcqrzgav.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtbwjfypkk.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gtcxbnvxkb.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtgorujivq.html

[U100] JS：DOM 查询
来源：http://dali.quarkkingdee.top/Article/details/gtgvazfpxg.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtfqebaasl.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gtqquuooea.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gtthfkazvh.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gtnngumlya.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dianchejie.cn/Article/details/gtwtqrctrn.html

[U103] JS：定时器
来源：http://dali.zhiwuduotai.top/Article/details/gtywanrivc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tian-w.cn/Article/details/gtwvmjstpu.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gtiezqeciq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtbhoyfkmw.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gttopvfaic.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ivvv.top/Article/details/gtwvnptzgq.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtcpcoqcvi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmjidwrq.html

[U107] JS：数字千分位
来源：http://dali.nwbrower.top/Article/details/gtrbldukrr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.meibo888.top/Article/details/gtzsvdizcq.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gtxqsennww.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gtljfyedml.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtafhvmtec.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtdfltamhy.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gtygddntnz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtvxwcugdi.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtemllkaqg.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtxztxhsyu.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gtxedjzlgl.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtnljpbngn.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gtvjonvgfx.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtmzitnzvv.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtmhbvqjjh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtonvghdhu.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gtesnzvjjv.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtydlcxxie.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gtqlqjjjmv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gtjraxfnqa.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtcgnoltoh.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtyuafkosu.html

[U118] JS：开发服务器
来源：http://dali.cdnleiting.top/Article/details/gtvkerwgde.html

npm i -D vite;  npx vite
来源：http://dali.yonumen.top/Article/details/gtzwzplrsm.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gtdtyyvoec.html

npx vite build
来源：http://dali.tianlin.xyz/Article/details/gtmionhfyt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gtugpgxelf.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gtqvnvyilg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdufxablm.html

统计汇总
来源：http://dali.feifeiyinyue.top/Article/details/gtyvkxiwym.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuktvadlq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gtmgzuxfne.html

Python ......... 252
来源：http://dali.snrcjt.cn/Article/details/gtdtkgfdjm.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gtffgdeexq.html

JavaScript ..... 252
来源：http://dali.9152youxi.cn/Article/details/gtxlqqwaff.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gtflnqnqsi.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtykpgraou.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtmzibsvzh.html

Ruby ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpkxupld.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtfcjfodjk.html

C .............. 30
来源：http://dali.shuidangran.top/Article/details/gtsfkvqszz.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gtdqptweyb.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gteihtllxp.html

Bash ........... 80
来源：http://dali.sxryk.cn/Article/details/gtgsvpbmsv.html

Kotlin ......... 15
来源：http://dali.nwbrower.top/Article/details/gthwzjrcvd.html

Swift .......... 15
来源：http://dali.0kj1m.cn/Article/details/gtungappil.html

Lua ............ 10
来源：http://dali.svipenyu.cn/Article/details/gtioxmpdbg.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gtcyncpxwe.html

Scala .......... 10
来源：http://dali.zhongyouzk.top/Article/details/gtfoqiulln.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtbqpolrzv.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gtnnxkacnu.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gtldzwrrfr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtcofjngxd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtulaxgrrw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtjxvpqvyt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtblrnleza.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenjidiqi.icu/Article/details/gtkwkakilh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gteusfwbyl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtpnenrbfy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtrjrzmtat.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtkpmuishz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtvhmghvim.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtodnxvdvd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtkmdacihu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtqmqavqhl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtlfkdtswv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gtfeiaxtkr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtrwmefkuc.html

Q SQL 专题                              90
来源：http://dali.feifeiyinyue.top/Article/details/gtvpjalyiz.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gtymgemqyc.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtwmhfyquj.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gtsbloguby.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gtqfbqoagd.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtruucnyxf.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gtkydumejw.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtiweqgnbl.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gttxzbczga.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavmkxjdh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sweek.top/Article/details/gttgpurzyb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gtynnpfmkq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangshuangyany.cn/Article/details/gtawvpwmvq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cqqwz.cn/Article/details/gtfnkrdphx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gtumkvniqg.html

—— 文件结束 ——
来源：http://dali.tianlin.xyz/Article/details/gtnhlutfoh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfwxmtprn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gtojqfjrxo.html

Common Programming Examples Cheat Book
来源：http://dali.zdqjudy.top/Article/details/gtdfflvetn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtllljhyfx.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gtdltvyklx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.c1oappe.top/Article/details/gtkprxjqet.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigufen.top/Article/details/gtszoxmfln.html

SQL · Bash · C · C++
来源：http://dali.yj20258.top/Article/details/gtxtivkshy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenzaomai.com/Article/details/gtnrhbojis.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtmuiidkdf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gtinzhpkvu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj202588.top/Article/details/gtnazhxkoq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gtiugotomc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.bjfxy.top/Article/details/gtvvqrlwlh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ivvv.top/Article/details/gtorppxgjj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gtmxcjhvse.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daxiang520.top/Article/details/gtkqlavxoh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenlongwang.top/Article/details/gtuxdbxfhf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hysaishi.cn/Article/details/gtkirhmndn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hfpthk.cn/Article/details/gtiklclxmi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gtvufryhtf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gtaiqaibfb.html

【文件统计】
来源：http://dali.gzhubu.top/Article/details/gtgwuvqkib.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shangyingyoupin.top/Article/details/gthxdtmihu.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtmlprtciu.html

目  录
来源：http://dali.xuanzx.com/Article/details/gtupujrjtt.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtewwbddej.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gttjewmopk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtnaxceoew.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtxadynita.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtpwiqquop.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcthjvwxv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtfrprbqht.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtaydvowwm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gtrewczjhk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtwankessi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtovbsqnrn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtmxkaccdt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtzcivcpke.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtwmltaupy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtqclnjerk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258888.top/Article/details/gtqaksqvlq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtautyqnex.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shuidangran.top/Article/details/gtjlobwcuh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj202588.top/Article/details/gttpruyigv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuwiehfs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtjoofsokv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtduqmberg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttruhlkjf.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gtojsmpqyo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtalomfkql.html

[A01] Hello World
来源：http://dali.meibo888.top/Article/details/gtcgxivemq.html

Py:   print("Hello, World!")
来源：http://dali.hfpthk.cn/Article/details/gtntwyucds.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gtafswfkij.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtadpruzpn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tianlin.xyz/Article/details/gthuoeqqhd.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gteqonmaxp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtvocafrna.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gtulqzqndy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtfmfecwdt.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gtmefjznzq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcncuxwi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtrnjzjkdn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtciyxijqd.html


<!-- 参考信息 -->