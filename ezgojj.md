代发 wailian999

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gthesanook.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtathoavkv.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gtmbbaxyir.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gtmewaysox.html

[U31] Py：单测
来源：http://dali.yuanzhike.top/Article/details/gtmtlvzifa.html

python -m pytest -q
来源：http://dali.jqgfzy.top/Article/details/gtmvkodipe.html

[U32] Py：代码格式化
来源：http://dali.cdnleiting.top/Article/details/gtseclxhuw.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gtfhbazijj.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gtwxwvntyn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cdnleiting.top/Article/details/gtsqkknyak.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtllphiqhy.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gtmyksabyk.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gtzcfpuwzo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gtxixphhlj.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gtklzufens.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gtryfmjzsm.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gtmzwmwhlo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guannengcc.top/Article/details/gtsbrcevsq.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gthzncodfa.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gtxaefkyfw.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gtdsemtomh.html

sys.stdout.isatty()
来源：http://dali.xinyue.icu/Article/details/gtvwoswcqy.html

[U40] Py：打印到标准错误
来源：http://dali.wangdashe.top/Article/details/gtnweunlcy.html

print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtnxdnsmcj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gtlrevvcud.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxinkj.top/Article/details/gtbvbmttko.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gtjnzwxqzt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gtpwxmlaor.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtcnxevklx.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gtvnptqtcc.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258888.top/Article/details/gtrqpvezbg.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gtshxexvvf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gtsgxiyskp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtvreesbar.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gtwagtngjt.html

?string $name = null
来源：http://dali.jqgfzy.top/Article/details/gtupvbmcsu.html

[U47] PHP：联合类型
来源：http://dali.gzhubu.top/Article/details/gtqovnfrxd.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gtulnqvlpt.html

[U48] PHP：纯枚举
来源：http://dali.jlsjyb.cn/Article/details/gtpbqcrlsu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sysykeji.top/Article/details/gtsjgebbmj.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gtujjffocr.html

public readonly string $name
来源：http://dali.daria6918.cn/Article/details/gtlefijwet.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gtuwqzqdoh.html

public function __construct(private int $id) {}
来源：http://dali.mhx1999.top/Article/details/gtjurlgttp.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gtrxfgptdq.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gtemtzufik.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvftemnxk.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtfuwassay.html

[U53] PHP：空合并运算符
来源：http://dali.guowangkeji.top/Article/details/gtlzdsqmpf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtdbwisbxs.html

[U54] PHP：空安全调用
来源：http://dali.cheryme.top/Article/details/gtozkknexj.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtzzuyavnb.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtozoamajk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gtytvjuxpy.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gtqdsxlfrh.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtnqbkhilc.html

[U57] PHP：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtnhjqyeli.html

"值: {$a}"
来源：http://dali.haohaochexian.top/Article/details/gtzoypgbrn.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gtbedmtmlf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gtihiuzhzf.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gtjgbhzcut.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtvskmzybt.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtwnmlpvci.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gtukkychum.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzxgudrd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtppfgyeot.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gtifjsttdh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gtochntjzu.html

[U63] PHP：文件读写
来源：http://dali.dianchejie.cn/Article/details/gtftedxqgu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenjidiqi.icu/Article/details/gtyjdiplgf.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gtowvuzxcs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ehwqpu.com/Article/details/gthwanlxit.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtxrvtqgti.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtmxjzwshz.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gtmodhwxqu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gtzethgpiy.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gtuggndvkw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gtxphzqvqd.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gtongqxsvc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dianchejie.cn/Article/details/gtqdtcuxfw.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gtrssjyciq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxrunbmd.html

[U70] PHP：PDO 事务
来源：http://dali.hammf.cn/Article/details/gtgjacuhnc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yongpay.top/Article/details/gtndgkmbhp.html

[U71] PHP：抛出异常
来源：http://dali.cucudq.cn/Article/details/gtqyksfzzh.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gttomzgeoq.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtmbutfgud.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gtzflrqgjg.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigufen.top/Article/details/gtluszzyfa.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gtjxyatcmo.html

[U74] PHP：读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtnzdriaqu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gthoubyztm.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtjmmlzghy.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtufgxxqqj.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gtopddwkjw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj202588.top/Article/details/gtjujwfpxs.html

[U77] PHP：模板渲染
来源：http://dali.jianghu66.top/Article/details/gtarsphhkq.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gtmylvqmxb.html

[U78] PHP：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gtdpalyjxr.html

composer require --dev phpunit/phpunit
来源：http://dali.hnqzz.top/Article/details/gtouctcubw.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiawjuims.html

composer require --dev phpstan/phpstan
来源：http://dali.guowangkeji.top/Article/details/gtnzpbwptn.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqdfgndf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.0kj1m.cn/Article/details/gtzalpqgrf.html

[U81] JS：初始化项目
来源：http://dali.sysykeji.top/Article/details/gtcyjuzdqb.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gtdlgchunk.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtqdjchags.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtuvntxdkr.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxuanxn.top/Article/details/gtzcolxbdd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtwxvygukz.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gtllzqxuig.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gtpxbvbnsg.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gtvshpkxfp.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gtduapxuoh.html

[U86] JS：空值合并
来源：http://dali.hywenlv.cn/Article/details/gtovhcfbgt.html

a ?? b
来源：http://dali.snrcjt.cn/Article/details/gtkscyojib.html

[U87] JS：解构默认值
来源：http://dali.wangdashe.top/Article/details/gtmtsbpyct.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtcpsvzyyy.html

[U88] JS：对象展开合并
来源：http://dali.chenjidiqi.icu/Article/details/gtpcubhkly.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkphodtp.html

[U89] JS：数组去重
来源：http://dali.sxryk.cn/Article/details/gtjtjxosyg.html

[...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtbuutjtzy.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gtzvexskgx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtegyliubz.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gtwutzrckr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangdashe.top/Article/details/gterknpgrl.html

[U92] JS：深拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtvpkcfvcl.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtjwaokbcu.html

[U93] JS：模板字符串
来源：http://dali.jinqigufen.top/Article/details/gtzeulgisy.html

`共 ${n} 条`
来源：http://dali.yj202588.top/Article/details/gtxpmexhxl.html

[U94] JS：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtoyoshzxh.html

const double = x => x * 2;
来源：http://dali.ybcxt.top/Article/details/gttpoaihey.html

[U95] JS：Promise 包装
来源：http://dali.gaohongyu789.top/Article/details/gtzkshvjbf.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gtvxuxenrw.html

[U96] JS：async/await 与异常
来源：http://dali.kuanghao11.cn/Article/details/gtzaulorvs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtnzzfamiq.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gtugklaojt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtgtzlhmfr.html

[U98] JS：fetch 带 JSON
来源：http://dali.mhx1999.top/Article/details/gtzcuxaonk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cheryme.top/Article/details/gtcfjhwqeg.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gtgstqvxlc.html

el.addEventListener("click", e => {})
来源：http://dali.tian-w.cn/Article/details/gtyktglokg.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtaunzkujj.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gtzdamthjk.html

[U101] JS：classList 操作
来源：http://dali.yj202588.top/Article/details/gteqsytvec.html

el.classList.toggle("active")
来源：http://dali.gaohongyu789.top/Article/details/gtfzrrwnbz.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtgmgilhdz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuanzhike.top/Article/details/gtvbszpjwq.html

[U103] JS：定时器
来源：http://dali.kuanghao11.cn/Article/details/gtgyzfipuv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gtomsuathn.html

[U104] JS：防抖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcomqvykx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtqurwmsmy.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtwilkivrc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gtlyuemuvm.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtfnblmuhr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guannengcc.top/Article/details/gtpgustbjn.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtubfxefjp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtvlknpamk.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gtmtmejkvv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gtqygqfcqj.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gtgnsmzarr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtfihpvfcw.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gtummfqdtc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gtqwrnqbkx.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtcnqtohyw.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtvwebynds.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gthgwqyrmz.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtgnhwuckd.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gtwwnqmhvb.html

s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtknjbeoxj.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gtuoenelvu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtumscklvq.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtyhobltdh.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtppnsfdhx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gtakxmfbii.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gtfftfuppw.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtlnnekjaj.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gtvgwjqqjg.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtgtchwwav.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtzkceauin.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtxkmfsbua.html

npx vite build
来源：http://dali.9152youxi.cn/Article/details/gtomempksh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gtjlshbepr.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gteqakinso.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnencjrc.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gtijaovrjm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfssrsddo.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtintoalig.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gtlajjqtcy.html

PHP ............ 252
来源：http://dali.guannengcc.top/Article/details/gtskfzwkbl.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gtptonvhbk.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gtqbhtzuta.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gtgdlzniwl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtslbhxugl.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtyrhsvbvo.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtdigryxqr.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gtxemwnzqs.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gtcmiodrdi.html

SQL ............ 90
来源：http://dali.pycfn.com/Article/details/gthhiugbun.html

Bash ........... 80
来源：http://dali.haohaochexian.top/Article/details/gtzieoawgh.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gtdewpvkng.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gtjtwcpibc.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gtzrxufvpf.html

Perl ........... 10
来源：http://dali.hnqzz.top/Article/details/gtottzjtos.html

Scala .......... 10
来源：http://dali.tian-w.cn/Article/details/gtjwcfkmjk.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtzqkzkcxy.html

合计 ........... 2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtnsgljyqs.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtjwkiknpc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gtngnxqdfj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtqyobqqbp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtcguvghjw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtuifeirsn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258888.top/Article/details/gtiwxhcgkn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtmylgqdbk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtxbnofyab.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gtdurtpqxv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtezsdaojj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtouuvlpth.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtymjwfnba.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtckhiajds.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtiyandega.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtnzmbyycm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gtzxffvdbz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtkkrcsgwa.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gthufgkdyj.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gtiqjyvmxe.html

S C / C++ 专题                          60
来源：http://dali.gotoacloud.top/Article/details/gtxwfgvtky.html

T 其他语言补充                          60
来源：http://dali.jiagoushi.top/Article/details/gtdhvudxuu.html

U 高频实用片段                         120
来源：http://dali.aibaodan.cn/Article/details/gttejqbrel.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtbwkztfoi.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtqxowwnvh.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gttiiyyhkv.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gtkoxcjeur.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtpdazrdmj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gtgedxqkac.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jyoumei.cn/Article/details/gtqwxbcnud.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhiwuduotai.top/Article/details/gtqkwwzkbl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gttzvrquog.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xziqi.cn/Article/details/gthrqjrkdw.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gtghjliifc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkqvnwret.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtwbyfplyo.html

Common Programming Examples Cheat Book
来源：http://dali.haohaochexian.top/Article/details/gtwkpodhvm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyaawutpj.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtjizzpvff.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinghuilouyu.cn/Article/details/gtnudqwbin.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlriqdrsu.html

SQL · Bash · C · C++
来源：http://dali.nanxinkj.top/Article/details/gtogohylvf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jyoumei.cn/Article/details/gtouypddox.html

【使用说明】
来源：http://dali.xuanzx.com/Article/details/gtbqwbmrfn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhengqikj.top/Article/details/gtumpdwsjc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxuanxn.top/Article/details/gtwclqmejb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzycrfjyi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxufyxnw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zycfv.cn/Article/details/gtkyeivjuv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhixingplan.top/Article/details/gtsxvbllnh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtqzewatxy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gtxfwjitra.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gtqzgwmogu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shuidangran.top/Article/details/gtzaejotns.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yanxiufei.cn/Article/details/gtzolppbzx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aibaodan.cn/Article/details/gtukaskmdx.html

【文件统计】
来源：http://dali.gaohongyu789.top/Article/details/gtoisdzbex.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gtzofjipfz.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtkvsfufqx.html

目  录
来源：http://dali.sufxvd.cn/Article/details/gtnkrxvvbq.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtlltjazaa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtlccapehx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gturbsenib.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtpnvxhafd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gtgilxghos.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtacplcbsc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gtwmkdxnsm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtgsiuonzl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtvtptzvoy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtjpjglqdk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtpsdnnopf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtkacofrtw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtwgkpmmms.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtzjxivxvd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gtjeyrbgtu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.havefunace.top/Article/details/gtszfbdgwu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiawplej.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zdqjudy.top/Article/details/gtmovwjzhu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zdqjudy.top/Article/details/gtbebtetkh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jiagoushi.top/Article/details/gtbtchohpc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtlkjgamsq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyjrhyti.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtoepolils.html

A. 基础语法与类型
来源：http://dali.bjfxy.top/Article/details/gtqsbvtixv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttsssuspd.html

[A01] Hello World
来源：http://dali.tanke756.top/Article/details/gtddohumnw.html

Py:   print("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gtydiwzxuw.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gtwpuwktlt.html

JS:   console.log("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtbloivuvf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.redwolf501.top/Article/details/gtypzwdntz.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtyuwetikr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtqrhstovy.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gticgnjtti.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtvfoxyncw.html


<!-- 参考信息 -->