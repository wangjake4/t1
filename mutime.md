代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.shzxlz.cn/Article/details/gt2jbgelcat.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gt2okzktubp.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gt2jmjytehr.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gt2wgrghyjh.html

[U29] Py：属性校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bywfkyvk.html

@property 与 @x.setter 配合
来源：http://dali.tianlin.xyz/Article/details/gt2lkvygfmm.html

[U30] Py：数据类
来源：http://dali.pycfn.com/Article/details/gt2uminmzel.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gt2zzhwxlcp.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gt2ksnghnnw.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gt2tsufarcq.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2ubfpzvvi.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gt2znkggsym.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gt2wwbdcseu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihayahhe.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdckqgjv.html

chardet.detect(raw)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozmiyxdw.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxjwhzuf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqhbkuzi.html

[U36] Py：定时任务
来源：http://dali.yonumen.top/Article/details/gt2ezpiaxvl.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gt2pviymiun.html

[U37] Py：读写 Excel
来源：http://dali.tanke756.top/Article/details/gt2citqxcnb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gt2muyutnut.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gt2nfdcpmfu.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gt2uunymxbq.html

[U39] Py：判断是否在交互环境
来源：http://dali.ybcxt.top/Article/details/gt2kwfaxtur.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gt2dbewgkpw.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gt2moscaphi.html

print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2dirxjehv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvnztfoc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gt2fbznwulg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmadisou.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxinkj.top/Article/details/gt2buqmpkhw.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gt2ulqynzxx.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gt2tvmtancv.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258.top/Article/details/gt2xtsvcjsf.html

declare(strict_types=1);
来源：http://dali.tianlin.xyz/Article/details/gt2zioqoioh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ebjdgxro.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2zoalngpn.html

[U46] PHP：可空类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwnxbswq.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gt2obddlyyj.html

[U47] PHP：联合类型
来源：http://dali.cdnleiting.top/Article/details/gt2dnwrypya.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gt2rpnktlwb.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gt2pbqyvegd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvkgxxmf.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdgjmtmv.html

public readonly string $name
来源：http://dali.0kj1m.cn/Article/details/gt2ofwooaqu.html

[U50] PHP：构造器属性提升
来源：http://dali.kuanghao11.cn/Article/details/gt2dzcybxzi.html

public function __construct(private int $id) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ddvkrfzp.html

[U51] PHP：数组解构
来源：http://dali.0kj1m.cn/Article/details/gt2irbuveie.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gt2fnizxbfq.html

[U52] PHP：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gt2qkdlpbyt.html

$double = fn($x) => $x * 2;
来源：http://dali.cucudq.cn/Article/details/gt2tilyglco.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vuqeuwov.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gt2rqsslqch.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gt2ylpmsrbk.html

$obj?->method()
来源：http://dali.pycfn.com/Article/details/gt2ctyxnlxl.html

[U55] PHP：match 表达式
来源：http://dali.xuanzx.com/Article/details/gt2zdfffzrh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gt2iljwcbzb.html

[U56] PHP：命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmfwnmvi.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2dczllapn.html

[U57] PHP：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhvfhaew.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gt2uivhbwom.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gt2mbqfbyuq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gt2icvtubnw.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2owjmatwa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2waxfzazt.html

[U60] PHP：JSON 编解码
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmlzcnyv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.havefunace.top/Article/details/gt2hjzrjwpw.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gt2nvmaoxlk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xohgixbw.html

[U62] PHP：日期对象
来源：http://dali.zdqjudy.top/Article/details/gt2wwviqusa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gt2abpdqblz.html

[U63] PHP：文件读写
来源：http://dali.ivvv.top/Article/details/gt2voyjdout.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gt2uxokvhka.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gt2pgnhzptb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gt2nagwrzpr.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gt2spajnakw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2fvpzhqcx.html

[U66] PHP：设置 Cookie
来源：http://dali.zdqjudy.top/Article/details/gt2mokyjtej.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shzxlz.cn/Article/details/gt2pjwzedvv.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfsfquxb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2byeptenq.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gt2ribfdqpg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gt2fdgwjyyw.html

[U69] PHP：PDO 预处理
来源：http://dali.smart0.xyz/Article/details/gt2fcwzkwrl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ybcxt.top/Article/details/gt2gaslfkhh.html

[U70] PHP：PDO 事务
来源：http://dali.yueranfly.top/Article/details/gt2rhkxfrrp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gt2gkhomeoo.html

[U71] PHP：抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2iaqbhhpk.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gt2lxpppujb.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gt2yimotygf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangdashe.top/Article/details/gt2wdedniwd.html

[U73] PHP：读取 ini 配置
来源：http://dali.yongpay.top/Article/details/gt2tcmdgclt.html

parse_ini_file("config.ini", true)
来源：http://dali.kuanghao11.cn/Article/details/gt2jmeqfoni.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2wqpxmkqm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.birdmap.top/Article/details/gt2ckecbwel.html

[U75] PHP：依赖注入
来源：http://dali.fzhhl.top/Article/details/gt2wzfzduud.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gt2qtkfatuy.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gt2gqkkvwcb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gt2sufubiqa.html

[U77] PHP：模板渲染
来源：http://dali.jyoumei.cn/Article/details/gt2rbxufstv.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbqezpvo.html

[U78] PHP：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvdqkwyh.html

composer require --dev phpunit/phpunit
来源：http://dali.fengsongda.top/Article/details/gt2rapyvvvp.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gt2czbelxxi.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gt2chrvqgoi.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gt2vljdcdpo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhengqikj.top/Article/details/gt2jrylqknx.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gt2cwyxqcwd.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcxvhjyg.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gt2ovrkjdnt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gt2sencafez.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gt2mmlljkmc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2lwtzwnub.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gt2rtbkpafr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gt2rpqrwqnt.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gt2jmdldqwf.html

a?.b?.c
来源：http://dali.xylfe.cn/Article/details/gt2tbnfylet.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gt2uenoomjz.html

a ?? b
来源：http://dali.dashuyun.cn/Article/details/gt2elruxcab.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gt2kjbzfwyq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gt2cdtiscir.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gt2pmbyxhyx.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gt2fqevnxos.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvapzhos.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2mbhuflcf.html

[U90] JS：数字数组排序
来源：http://dali.chenzaomai.com/Article/details/gt2klbgrqug.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kblfafgf.html

[U91] JS：对象键值遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2huyolfcf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gt2ucacclxw.html

[U92] JS：深拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2kmmzrmas.html

structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2taaveesk.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyftzaxt.html

`共 ${n} 条`
来源：http://dali.tian-w.cn/Article/details/gt2ffynggjc.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhtoojyh.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2evcfhjff.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gt2mhfcbunw.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gt2xfhddbnk.html

[U96] JS：async/await 与异常
来源：http://dali.gaohongyu789.top/Article/details/gt2mbnkwgrg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2azxglvyl.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gt2gcvsuyeg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2xbwhqblz.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2idjikfeh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jyoumei.cn/Article/details/gt2aiwkxapw.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gt2idummgrz.html

el.addEventListener("click", e => {})
来源：http://dali.hfpthk.cn/Article/details/gt2xeysrpek.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gt2sdjqoubj.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gt2yhwvbqxf.html

[U101] JS：classList 操作
来源：http://dali.tianlin.xyz/Article/details/gt2bmnhznok.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcqtcnlq.html

[U102] JS：本地存储
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpthdxku.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gt2zejqihab.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gt2jeatyfgu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gt2bjvgytbn.html

[U104] JS：防抖
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxmmyipu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2pzmehnok.html

[U105] JS：节流
来源：http://dali.cqqwz.cn/Article/details/gt2jmmjkjya.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2silzbsgw.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gt2ynzdtjxa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gt2icswqcpq.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2kswdeogy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2bjlouaek.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gt2orrgvdqz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cdnleiting.top/Article/details/gt2hfxlrijs.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gt2lllxxdaq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2mfosrdhm.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gt2adoutith.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.havefunace.top/Article/details/gt2iokjbfqy.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2pzlbxxtu.html

new Map(Object.entries(obj))
来源：http://dali.havefunace.top/Article/details/gt2itpkxzdt.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gt2gyjifhwy.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2qtrapyhb.html

[U113] JS：正则替换全部
来源：http://dali.sysykeji.top/Article/details/gt2bvcgnpva.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2odewlgni.html

[U114] JS：JSON 深比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbgykvfo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2itenqhgd.html

[U115] JS：生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2diaybqlc.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2epswkyrw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gt2xmcypmcv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjqfhfva.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gt2htfckybl.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gt2tzbittnb.html

[U118] JS：开发服务器
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfqgjcha.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gt2upegqicu.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gt2xxagiruc.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gt2tlzzciwr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuanzhike.top/Article/details/gt2zhtdvzut.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gt2uycltsbl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2szvyhsoh.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gt2pzfvsdfe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybcmskiv.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxodblmh.html

Python ......... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwpcewnz.html

PHP ............ 252
来源：http://dali.yuxming.cn/Article/details/gt2ijauiqcp.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gt2jyrojadc.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gt2ckjrioxj.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2amwaqguw.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gt2qddblato.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gt2hapgqiyz.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gt2vwnpatlk.html

C .............. 30
来源：http://dali.shzxlz.cn/Article/details/gt2grdbkkdg.html

C++ ............ 30
来源：http://dali.fzhhl.top/Article/details/gt2qzbokzff.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gt2xbbqgmde.html

Bash ........... 80
来源：http://dali.fengsongda.top/Article/details/gt2hrujqfop.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2hlgkxgyu.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2ojnlrhfn.html

Lua ............ 10
来源：http://dali.haohaochexian.top/Article/details/gt2qseyiomr.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xalkvxad.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gt2wkcsatbr.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2jdsnigif.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2iuvkihpx.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gt2crvgibmv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2mjalcjzs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2xlagqxug.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhhpfubr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gt2qnwamicu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ppjwa.cn/Article/details/gt2vuljgjyt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgjhveg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gt2nhrgcpdx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbiagml.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2rbzbnczc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2xbgwagiu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oterujdy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2zzapodac.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofcdxufn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gt2fpfmweki.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gt2thhpvkxo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gt2mxjtbwww.html

Q SQL 专题                              90
来源：http://dali.jqgfzy.top/Article/details/gt2ttfggtag.html

R Bash 专题                             80
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqeweelj.html

S C / C++ 专题                          60
来源：http://dali.redwolf501.top/Article/details/gt2tsbrsfuk.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjqhzegr.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxrdokoj.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2addbulil.html

合计                                  2106 条
来源：http://dali.zycfv.cn/Article/details/gt2acordcqk.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2lxiujwcf.html

使用提醒
来源：http://dali.quarkkingdee.top/Article/details/gt2qtvfslxy.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrelvhig.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gt2jerxwlzx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gt2vkbhpxdl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cqqwz.cn/Article/details/gt2slobmtob.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gt2voivxbjc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhiwuduotai.top/Article/details/gt2parvjgum.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gt2liexigdi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hfsajcze.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gt2uhaviqek.html

Common Programming Examples Cheat Book
来源：http://dali.iojbl.cn/Article/details/gt2mkbzhpvd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2fujzzyyv.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gt2iqngmhhv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.snrcjt.cn/Article/details/gt2oxbdlscp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gt2kilittpw.html

SQL · Bash · C · C++
来源：http://dali.sufxvd.cn/Article/details/gt2lofdultx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daria6918.cn/Article/details/gt2qcrtypeu.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gt2dsoxqklx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xziqi.cn/Article/details/gt2eqozptrx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxuanxn.top/Article/details/gt2xyjudlxu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sweek.top/Article/details/gt2dcvqbuuj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gt2ktkbwkeh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gt2dqutkvjb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.bjfxy.top/Article/details/gt2gjedsyre.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gt2xlvbysgu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gt2nhnrlthw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gt2npraodkd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.kuanghao11.cn/Article/details/gt2lqttvgnt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gt2iklxuwyf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhqmpeje.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gt2rwnhtipt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nwbrower.top/Article/details/gt2zypvcetj.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2cdgwkghz.html

目  录
来源：http://dali.dashuyun.cn/Article/details/gt2lgzdqvli.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2wdwnabyk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gt2sgpkioqu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2jyyezmfg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gt2fwwpvhof.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gt2qhhluhcu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gt2mekkkskj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gt2dhdudhjz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gt2bmxpjaec.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxyzahqm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gt2uswufgbg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2zdmqigew.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gt2lyskyhra.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2wdzbxwrf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2jmmvdapz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2skcvyhrz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258.top/Article/details/gt2aqfyrfkp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnmilrwm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ydzc1.top/Article/details/gt2giogohcg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hywenlv.cn/Article/details/gt2brqotsdc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gt2qzzyaugq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gt2zqbrcmny.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gt2erarnmul.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2yeobydxv.html

A. 基础语法与类型
来源：http://dali.nwbrower.top/Article/details/gt2rysvwnjk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2opnedguo.html

[A01] Hello World
来源：http://dali.nwbrower.top/Article/details/gt2duyeizio.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grlmherp.html

PHP:  echo "Hello, World!";
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxumaklm.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2nkokdjhs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gt2poaesqqr.html


<!-- 参考信息 -->