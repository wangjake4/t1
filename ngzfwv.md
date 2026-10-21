代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gtgszzydzy.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtmspjjjle.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtsuwdsdiu.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangtech.top/Article/details/gthxgwswmx.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gtyfzbgiaw.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtwaexywtx.html

[U10] Py：按值排序字典
来源：http://dali.xziqi.cn/Article/details/gtjstolkjp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrqqueyl.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtycyglkfn.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gtvqauktsz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xziqi.cn/Article/details/gtomctwqxw.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtnzuxleld.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gttjxzydfp.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gtqifxvnbz.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtcjlauopp.html

defaultdict(list)
来源：http://dali.ppjwa.cn/Article/details/gtseunific.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gtrzvsgvgt.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthclqtrfk.html

[U16] Py：命令行参数解析
来源：http://dali.dashuyun.cn/Article/details/gthdyomrlw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgueogqfb.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtxlvjjywn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtpwqlmkkz.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gtlgepuslz.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gtdcmirthj.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gtddvthaol.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtztwakmmd.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gtqsgfoozl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtdcomyfow.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gthowmxkkz.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gtgkxogdwp.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtikaesask.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gtxynddnpl.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gtckaszfmd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gtqbfpzotz.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gtpbucixby.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtiqjlvyue.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gtdraiehcs.html

csv.DictReader(f)
来源：http://dali.316326.xyz/Article/details/gtmlknqvkk.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gtjcuealqa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gtciezxvlr.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtvjwqlfkz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gtcdkobrsk.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gthrjdgfks.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gtrxdbenfj.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtekagduwm.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtcowlfilo.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtwzdkiryo.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhaykspb.html

[U31] Py：单测
来源：http://dali.shangyingyoupin.top/Article/details/gtyppadsjz.html

python -m pytest -q
来源：http://dali.yongpay.top/Article/details/gtvrtgemuf.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gtrjozrgkb.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gtskjoeiev.html

[U33] Py：打包发布
来源：http://dali.hammf.cn/Article/details/gtsjqxacbt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkzkwywt.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtykzockbr.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gtfnbnppuv.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gtvprzdiwp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gtymikdgci.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gtmnznzbir.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtldopitsk.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvdbojtp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gtmczjgohk.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gtkeedvxza.html

Path(__file__).resolve().parent
来源：http://dali.9152youxi.cn/Article/details/gtpbhxawmv.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtcaqsnifb.html

sys.stdout.isatty()
来源：http://dali.bjfxy.top/Article/details/gttvmormov.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtkcehkuyz.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtciafczfb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gtwiufhycy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gtpiepksry.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.kuanghao11.cn/Article/details/gtjbarzupn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sysykeji.top/Article/details/gtdnrkqwqw.html

[U43] PHP：声明命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtzozygmov.html

namespace App\Http;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqczgtbu.html

[U44] PHP：开启严格类型
来源：http://dali.316326.xyz/Article/details/gtxtlitdat.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtomphdnay.html

[U45] PHP：类型声明与返回类型
来源：http://dali.0kj1m.cn/Article/details/gtohpeabsp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtotouvyof.html

[U46] PHP：可空类型
来源：http://dali.svipenyu.cn/Article/details/gtesrvwgxt.html

?string $name = null
来源：http://dali.andypj.xyz/Article/details/gtbozhfaea.html

[U47] PHP：联合类型
来源：http://dali.aibaodan.cn/Article/details/gtlloqkjor.html

int|string $id
来源：http://dali.ybcxt.top/Article/details/gtdnfgaclp.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtvympakpv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gtlqjqyftz.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtkevanlbb.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtkbtbuajr.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gtrpynnfev.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtashiqqwj.html

[U51] PHP：数组解构
来源：http://dali.xuanzx.com/Article/details/gtekuiloww.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gtrhemsoha.html

[U52] PHP：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtkayegphe.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtdzjlcjnp.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtvfiiovgc.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gtitofzyzc.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gtzwsmuhyq.html

$obj?->method()
来源：http://dali.0kj1m.cn/Article/details/gtheaholqf.html

[U55] PHP：match 表达式
来源：http://dali.chenzaomai.com/Article/details/gtyossbxzo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sysykeji.top/Article/details/gtdevrwmsk.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gtcedkrumj.html

f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtwkbdazah.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtbaxpfgqy.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gtanlklswj.html

[U58] PHP：数组三件套
来源：http://dali.yueranfly.top/Article/details/gtleoiwjyx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtjamivyam.html

[U59] PHP：自定义排序
来源：http://dali.meibo888.top/Article/details/gtecvnwiux.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtfrocrkwc.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtzumonaec.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gtyismexei.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gtubxvnraz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroauevtc.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gtgxqriwuk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtqktownln.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gtdadlqghw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gtjosvuyly.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gtkslyeiqx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hywenlv.cn/Article/details/gtihpuwxrd.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gtqyycxikc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtklnulmap.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gtfbtsrpgh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtqxifsuzj.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gthdpoluml.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gtcojdiaxo.html

[U68] PHP：PDO 连接
来源：http://dali.sysykeji.top/Article/details/gtmkdkelqm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gthsdzbzxq.html

[U69] PHP：PDO 预处理
来源：http://dali.tianlin.xyz/Article/details/gtaatgqahk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sweek.top/Article/details/gticvyblsn.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtgsjmjirc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtsloduhqa.html

[U71] PHP：抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtbksjqovs.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gtuvivztvd.html

[U72] PHP：写错误日志
来源：http://dali.hnxiangtu.top/Article/details/gtzbbdhcze.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gtqghkftff.html

[U73] PHP：读取 ini 配置
来源：http://dali.ybcxt.top/Article/details/gthsypgwwy.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gtahyyekok.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtdoyfjdwc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuanzhike.top/Article/details/gtzvyptbuf.html

[U75] PHP：依赖注入
来源：http://dali.cashguo.top/Article/details/gtvcppnwxv.html

composer require psr/container
来源：http://dali.jinqigfzy.top/Article/details/gtglquteow.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gthpbtlazt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gtfsmimvbq.html

[U77] PHP：模板渲染
来源：http://dali.yanxiufei.cn/Article/details/gtkvlztrvw.html

composer require twig/twig
来源：http://dali.xylfe.cn/Article/details/gtjwhvscim.html

[U78] PHP：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gteofqkyfp.html

composer require --dev phpunit/phpunit
来源：http://dali.feifeiyinyue.top/Article/details/gtrdgmglai.html

[U79] PHP：静态分析
来源：http://dali.pengpengdd.cyou/Article/details/gtrnjlxeld.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gtgimkltxu.html

[U80] PHP：代码规范修复
来源：http://dali.bjfxy.top/Article/details/gtdbywullp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shzxlz.cn/Article/details/gthkbluvnt.html

[U81] JS：初始化项目
来源：http://dali.yongpay.top/Article/details/gtkqppzmwc.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gtllnjynxk.html

[U82] JS：package.json 脚本
来源：http://dali.cheryme.top/Article/details/gttlpsfefk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yanxiufei.cn/Article/details/gtjagqhnec.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuxming.cn/Article/details/gtqrglgcys.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtdqybunhe.html

[U84] JS：CommonJS 写法
来源：http://dali.yangfankeji.com/Article/details/gtfqtchcmo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gtdhetkzgo.html

[U85] JS：可选链
来源：http://dali.hammf.cn/Article/details/gtovhrxzwc.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtratptbff.html

[U86] JS：空值合并
来源：http://dali.yj20258.top/Article/details/gtkevetcnw.html

a ?? b
来源：http://dali.chenlongwang.top/Article/details/gtcvkhshbn.html

[U87] JS：解构默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtqiwgvmue.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gtmvwrrntk.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gtdrvdvvmp.html

{ ...a, ...b }
来源：http://dali.c1oappe.top/Article/details/gtrriitjrx.html

[U89] JS：数组去重
来源：http://dali.yanxiufei.cn/Article/details/gthrqoyvbd.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtelmvapkb.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gtsqcwzmfc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumoefuuh.html

[U91] JS：对象键值遍历
来源：http://dali.yj202588.top/Article/details/gtwbtzrdia.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gtowaylhmi.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtwpmzfmqm.html

structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtjknzgike.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gtolwhivxg.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gtvmejdeqd.html

[U94] JS：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsmgtjipe.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtiajavarg.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gtmjydrmnn.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gttbnkfrgg.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gteorttjix.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtgxaluknu.html

[U97] JS：并发请求
来源：http://dali.shzxlz.cn/Article/details/gtrlzixqyu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtypowjtzl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhwxyfoy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gtnamxxuhw.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtowkxakjp.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtghewftdy.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gtfgtpvxfp.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gtmtrimrge.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gtmbcqccgg.html

el.classList.toggle("active")
来源：http://dali.cucudq.cn/Article/details/gtzgzdamco.html

[U102] JS：本地存储
来源：http://dali.ydzc1.top/Article/details/gtstxmhhwf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shzxlz.cn/Article/details/gtoahtmjtx.html

[U103] JS：定时器
来源：http://dali.hongshengwenyu.top/Article/details/gtlwfpaqdk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gtskompgbj.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gtpjvfhbra.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gthxebivfb.html

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gtsfaphzaz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtkfygyhis.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtywfnwjhm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cucudq.cn/Article/details/gtqddoyeon.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gttuhdtcsw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtcytydiwd.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gtjbqfqpac.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gteyxteiei.html

[U109] JS：数组分组
来源：http://dali.chenjidiqi.icu/Article/details/gtjnfmuypc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtickduucs.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gtwgrzfjyw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtiwattibg.html

[U111] JS：对象转 Map
来源：http://dali.meibo888.top/Article/details/gtewaejhsr.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gtkvvwedle.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gtbqfcrntj.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gthrnmcigt.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtvzeeejzc.html

s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtbxczvbbm.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gtuqrpiguk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gttlydfsaz.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gthmvyxhmz.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtyasmzxwa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jlsjyb.cn/Article/details/gtpjzwgvtt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmujwobww.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtszugykyu.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gtcgebgmbn.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gtsxjcuzls.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gtisfeetyi.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtwdcruujx.html

npx vite build
来源：http://dali.c1oappe.top/Article/details/gtghvmcggb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gthnnozaue.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gtfzomdwmi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtipnkhrup.html

统计汇总
来源：http://dali.hywenlv.cn/Article/details/gtdlxrwzvy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvpbdimhy.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gtmlffjfjb.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gtpfnsmyjy.html

PHP ............ 252
来源：http://dali.yj20258888.top/Article/details/gtzkgectqw.html

JavaScript ..... 252
来源：http://dali.yj20258888.top/Article/details/gtikmbqpox.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtitzjvpbr.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwpjuhjv.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtgsxmwuap.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtmzhdrtvc.html

C# ............. 212
来源：http://dali.aibaodan.cn/Article/details/gthajmvaco.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gtqvsabobl.html

C++ ............ 30
来源：http://dali.fengsongda.top/Article/details/gtutzynrck.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gtcbhthxgk.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtpjmbxdei.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gtgfexjxva.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtgcznozde.html

Lua ............ 10
来源：http://dali.zhiwuduotai.top/Article/details/gtumiwotbr.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gtkebnghwo.html

Scala .......... 10
来源：http://dali.andypj.xyz/Article/details/gtktomgtgk.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtuvymmvvd.html

合计 ........... 2106 条
来源：http://dali.cashguo.top/Article/details/gtmgfvrszs.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gtvwunhzjs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqnqarls.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtxaglxdba.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtnvowpxno.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gtchoxxymj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gtdgrobbob.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtrbnvzpmh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtcifcymns.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtpgympkue.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtwzkggcqj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gtogcgioux.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtbdlbjjfr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtmfektvgl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtofliaqew.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtwcnuymyk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gttmpoysch.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtnbmptrgl.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gtmoyqojej.html

R Bash 专题                             80
来源：http://dali.aibaodan.cn/Article/details/gtjwjqujkk.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gttgctttwb.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gteqdwksmv.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gtrprrjlmk.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtddjacyvt.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gtpiwsgnmu.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtdghlqmqh.html

使用提醒
来源：http://dali.tian-w.cn/Article/details/gtlhvzfvba.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykyxhkef.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtsfmhhjyn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aizwys.cn/Article/details/gtjtjosdqy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gtuxelhajk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gtmgwgcvdw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gtksmnriyl.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gtnjytluhr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtusgiyuwb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gtybozdrzf.html

Common Programming Examples Cheat Book
来源：http://dali.zhongyouzk.top/Article/details/gtdsincdtn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgnvbsiir.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gtfxzgwszj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxuanxn.top/Article/details/gtnrjwcrcp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gttzcnwalv.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gtnkysmnds.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daria6918.cn/Article/details/gtlzqmainl.html

【使用说明】
来源：http://dali.mhx1999.top/Article/details/gtuwesirfc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtregngpco.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gogol.net.cn/Article/details/gtwnidvttm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhoulong.xyz/Article/details/gtjoxlnfmh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jianghu66.top/Article/details/gtfuswkbdb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yangfankeji.com/Article/details/gtzbkailpk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xylfe.cn/Article/details/gtdrnhmtzm.html


<!-- 参考信息 -->