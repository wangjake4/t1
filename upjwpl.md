代发 wailian999

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gtczsonriv.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gteuunoona.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtqqbnaqks.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gthexdfibc.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtmnbgeydu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gtsbvofhlv.html

[U18] Py：预编译正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamidwfaf.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gtucwyhaaf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtiorrakue.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjgkjxasa.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxzcmhbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhixingplan.top/Article/details/gteittjjci.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtrugbirvk.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gthhghjiwj.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gtgwpjmdpq.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gttdzxuatx.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gtmynaequn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gtrneomggk.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gtyxjhhxau.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtrftytceb.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gtmacdhnro.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtffqdvjcs.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gtocnnrhrf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gtoqmznwis.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtpqvvfrml.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtidrqsvnu.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gtaglfbjeu.html

UserId = int
来源：http://dali.havefunace.top/Article/details/gttwjgnrmx.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gtcsmufcgk.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtnwmzjshy.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtpkwmpetm.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtkzgfpdpq.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtosstlnyk.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gthajvvgmq.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gttgstozfg.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gtnctsxcnl.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gtrfigavno.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guowangkeji.top/Article/details/gtwyqohtcv.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gtulljmwfe.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gtxeorwpci.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtyqynpsfy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gtgvwrnziu.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtvnqkfmuf.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gtckutwdma.html

[U37] Py：读写 Excel
来源：http://dali.daxiang520.top/Article/details/gtxwrfqoud.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gtigihbams.html

[U38] Py：获取脚本所在目录
来源：http://dali.snrcjt.cn/Article/details/gtbxuxswqw.html

Path(__file__).resolve().parent
来源：http://dali.chenlongwang.top/Article/details/gtmgghkgdz.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigufen.top/Article/details/gtfmmvleys.html

sys.stdout.isatty()
来源：http://dali.yuxming.cn/Article/details/gtvmnqkhca.html

[U40] Py：打印到标准错误
来源：http://dali.zhongyouzk.top/Article/details/gtrwxskuaa.html

print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtbjtpisxm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jiagoushi.top/Article/details/gtygfyzsrx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gtnrvelyef.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gtmadkmmuo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gtarwrjjyx.html

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gteirmsahs.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gtwuzuzcco.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gtxslwxqpv.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gtrlykujye.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtcqvlhpss.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtqqhztygc.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtpmvoicxu.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gtcwqnrjbp.html

[U47] PHP：联合类型
来源：http://dali.yj20258.top/Article/details/gtxyujzotl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gtdzikiztn.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gtqmhzvmkb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tian-w.cn/Article/details/gtplhiqfoz.html

[U49] PHP：只读属性
来源：http://dali.shzxlz.cn/Article/details/gtnswdvxgx.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtjgbrswpd.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtidwtfqcr.html

public function __construct(private int $id) {}
来源：http://dali.gaohongyu789.top/Article/details/gteecnsrzm.html

[U51] PHP：数组解构
来源：http://dali.iojbl.cn/Article/details/gtqpnlaeqo.html

[$a, $b] = $arr;
来源：http://dali.ydzc1.top/Article/details/gtmsafqjra.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtdaxrgwom.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuaiwdlu.html

[U53] PHP：空合并运算符
来源：http://dali.hnqzz.top/Article/details/gtnoncvrze.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gtmufyunim.html

[U54] PHP：空安全调用
来源：http://dali.fzhhl.top/Article/details/gtdlbndwuk.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gtavyiwxjc.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtvzwcboqp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtkytppxgi.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtjmmiicqb.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtmzgvjjek.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gtjtuckwpb.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gtijrwolaq.html

[U58] PHP：数组三件套
来源：http://dali.ehwqpu.com/Article/details/gtpjkvxopn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdwicilw.html

[U59] PHP：自定义排序
来源：http://dali.hnqzz.top/Article/details/gtgctwjvze.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtwgzpllao.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtabnrvysi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuetiantiany.cn/Article/details/gthmptpckn.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gtuqrupulw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtilxirykk.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtvqilhgtb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gtplrihgxg.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gteciidhpo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cucudq.cn/Article/details/gtftedukdp.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gtyayhmhjc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.svipenyu.cn/Article/details/gtkuychkow.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtmhvfozva.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtrwmbgsxx.html

[U66] PHP：设置 Cookie
来源：http://dali.yvedp.cn/Article/details/gtrhmpqfew.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtqoahwqjy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtlqcgxuni.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gtigbsnxev.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gtieyzxzps.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gtlkbaysoh.html

[U69] PHP：PDO 预处理
来源：http://dali.jyoumei.cn/Article/details/gtxtgdxlxn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gtruwpwyrc.html

[U70] PHP：PDO 事务
来源：http://dali.zhoulong.xyz/Article/details/gtclcbmsrh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gtgzomiyrc.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gturqohpme.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnqzz.top/Article/details/gtxgepsmis.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtphxbdjdu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtnqmmvdtg.html

[U73] PHP：读取 ini 配置
来源：http://dali.jiagoushi.top/Article/details/gtflqqzbml.html

parse_ini_file("config.ini", true)
来源：http://dali.aibaodan.cn/Article/details/gthdbkqhgl.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtraziiweh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gtnxigesjg.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtxrxhmsne.html

composer require psr/container
来源：http://dali.jiagoushi.top/Article/details/gtgmwfegrd.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gtonasbmte.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guannengcc.top/Article/details/gtkomalwir.html

[U77] PHP：模板渲染
来源：http://dali.daria6918.cn/Article/details/gtpefvewns.html

composer require twig/twig
来源：http://dali.zhixingplan.top/Article/details/gtzxptosvf.html

[U78] PHP：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtbtnjmqac.html

composer require --dev phpunit/phpunit
来源：http://dali.wangshuangyany.cn/Article/details/gtcytnenej.html

[U79] PHP：静态分析
来源：http://dali.shangyingyoupin.top/Article/details/gtevscwtcx.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gtsuvvgizo.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gtrnkkmaqe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gttirpzmai.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gtskufbcpy.html

npm init -y;  npm i express
来源：http://dali.zhengqikj.top/Article/details/gtyspjvjni.html

[U82] JS：package.json 脚本
来源：http://dali.xuetiantiany.cn/Article/details/gtumfhcbsl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aibaodan.cn/Article/details/gtwkwzxrae.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuanzhike.top/Article/details/gteglepubh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtwkzxvspd.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gtprvrzezn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuxming.cn/Article/details/gtndtlzupd.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gtpwrgqiam.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtzqsmawuo.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgkjgotm.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gtwjigreci.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gtlpfqjhgw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dianchejie.cn/Article/details/gtkyghrmmh.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdszyjay.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtxgejbvqj.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gtztunujss.html

[...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtmhsoppmi.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gtuugbfbah.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtyvmvtsiz.html

[U91] JS：对象键值遍历
来源：http://dali.hnqzz.top/Article/details/gtpuvwaucf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.haohaochexian.top/Article/details/gtytgfbzgx.html

[U92] JS：深拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtkwmleimf.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtccxuwnrd.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtkcfbrkwr.html

`共 ${n} 条`
来源：http://dali.yj20258888.top/Article/details/gtrmqrceou.html

[U94] JS：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gtznxzopvf.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtmvsdbhuw.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gtfkvxytql.html

new Promise((resolve, reject) => {})
来源：http://dali.guowangkeji.top/Article/details/gtxkwtviuk.html

[U96] JS：async/await 与异常
来源：http://dali.ivvv.top/Article/details/gtdpmehkyx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtenuypogn.html

[U97] JS：并发请求
来源：http://dali.xinyue.icu/Article/details/gtuecnyacl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtlqoielis.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuxming.cn/Article/details/gtcodgeudw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gtncupznmx.html

[U99] JS：事件监听
来源：http://dali.zhixingplan.top/Article/details/gtyfrutzbn.html

el.addEventListener("click", e => {})
来源：http://dali.ydzc1.top/Article/details/gtjnewbdsq.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gtpifdvlyo.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtmixxoacm.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gtdpuvdurs.html

el.classList.toggle("active")
来源：http://dali.aibaodan.cn/Article/details/gtpziovttj.html

[U102] JS：本地存储
来源：http://dali.chenzaomai.com/Article/details/gtnumattyx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gtfecijtfg.html

[U103] JS：定时器
来源：http://dali.andypj.xyz/Article/details/gtuynynfnh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtuigxlwug.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtkcbvmlzd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtzhttnyxy.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gtxlhfsyqe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xinyue.icu/Article/details/gtvpzwaaon.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gtqephlhbe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gtgwdffeth.html

[U107] JS：数字千分位
来源：http://dali.smart0.xyz/Article/details/gtpolabewe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.redwolf501.top/Article/details/gthpbvqhmh.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gtuljllvks.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkydxkuo.html

[U109] JS：数组分组
来源：http://dali.ehwqpu.com/Article/details/gthqzoifvo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtdrokhean.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gttunonutu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangshuangyany.cn/Article/details/gtxvjumgcl.html

[U111] JS：对象转 Map
来源：http://dali.pycfn.com/Article/details/gtxdcmyoib.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtgbjkeucr.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gtuvddkiyb.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gthotllkbb.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gtqzvjtppy.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtsrvyqhvu.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtrevptehr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtkupbqnub.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtbrkgfnqt.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtxocqrcyn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gtfudkiipm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgghutkiy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtbeoyautp.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258.top/Article/details/gtedrgquks.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gtjdnedoqr.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gtymhyooyc.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtvcuvsvkl.html

npx vite build
来源：http://dali.yvedp.cn/Article/details/gtwmqmkcsf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtajcbagmc.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gtqnfosony.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbrvrlxmm.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gtapcxgkya.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuzvtpgpc.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtdazcwxvk.html

Python ......... 252
来源：http://dali.cashguo.top/Article/details/gtukvzrmiv.html

PHP ............ 252
来源：http://dali.ivvv.top/Article/details/gtincjbbuq.html

JavaScript ..... 252
来源：http://dali.cashguo.top/Article/details/gtpnvclolf.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtbyxwxcuo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gtjqftvotz.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtatxcctay.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtaylnketo.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gtgjwsyqim.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gtjsjhdiys.html

C++ ............ 30
来源：http://dali.gotoacloud.top/Article/details/gtytxewzod.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtikhlxlxs.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtczvxvrak.html

Kotlin ......... 15
来源：http://dali.zhoulong.xyz/Article/details/gtgdiioppx.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtobhbtamq.html

Lua ............ 10
来源：http://dali.jianghu66.top/Article/details/gtduzjvlnx.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gtncofttyy.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gtvwxgfuck.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtsnchhnjk.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gtrqlmbyze.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtylcwwxfi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtaevyqtzh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtqeoogpdh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtjtuieqpx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtsvykuxwn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cdnleiting.top/Article/details/gtgdyqpvwu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtdevupgqv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtaxyqlhjr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtdppcygfq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtorcdjdfx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtwsnitmwk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtuaactqru.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtyholrcja.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gthneswdzn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtdxqhlltw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gtpbfntmmc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtfpvvggjk.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gtvwagwkie.html

R Bash 专题                             80
来源：http://dali.sweek.top/Article/details/gtgesklmsv.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtiwapqfrl.html

T 其他语言补充                          60
来源：http://dali.zhixingplan.top/Article/details/gtwkwmeekd.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gtcwdngapf.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtvddbejvz.html

合计                                  2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtgvrlrmns.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtpbrgehsy.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gtdgujxsdh.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtremhchvo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jianghu66.top/Article/details/gtomlzcylu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhengqikj.top/Article/details/gtwjatsttq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gtqayqzhnx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sysykeji.top/Article/details/gtkrxjzgim.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gtdpdbblfz.html

—— 文件结束 ——
来源：http://dali.xylfe.cn/Article/details/gtgzqomuad.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjcjdhbxl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgfzy.top/Article/details/gthzefvhdm.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gtprznnznk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyhigyxgv.html

【收录内容】
来源：http://dali.chenzaomai.com/Article/details/gtmrlhswyl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarevacmu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhongyouzk.top/Article/details/gtvjfzgcdm.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gtwynsfckt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtwlettrok.html

【使用说明】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdykkfpd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gtukbfjgmz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yangfankeji.com/Article/details/gttuyftbox.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jiagoushi.top/Article/details/gtvxvairzq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.havefunace.top/Article/details/gtptfzadcu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jyoumei.cn/Article/details/gtpyhcvfrb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hysaishi.cn/Article/details/gtvwrjzoyq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sweek.top/Article/details/gtggyvuztj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cheryme.top/Article/details/gtbdgpnccq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gtedfuuooe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.9152youxi.cn/Article/details/gtankyiivx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ydzc1.top/Article/details/gtkaprxyyg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aizwys.cn/Article/details/gtslafhmel.html

【文件统计】
来源：http://dali.hfpthk.cn/Article/details/gtatkvoort.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaskbiki.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtkevsjela.html

目  录
来源：http://dali.ydzc1.top/Article/details/gtqvxxpecm.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtcamwkeiy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtvecbsxza.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtytaeejrv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtamuptdcf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtqyvrtued.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gtxytoujlx.html


<!-- 参考信息 -->