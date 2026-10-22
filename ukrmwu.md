代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gtsanzjsnw.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtuspzfztb.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtlgsqvaep.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gtjpxsexzn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtdfrboofb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteklhpnxj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtluiywgzr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgyctziek.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gtfexmwwsv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtwndensza.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtzqxpmofz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtvyfzgajm.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtxlaxhrys.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmchkwau.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gtfzvapuke.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gtiiebewbn.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gtopjlikzk.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gthpjijilh.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gtoafhgkbg.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gtcqkahfqc.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtycqpesug.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtlvynqyzi.html

[U08] Py：展平二维列表
来源：http://dali.daxiang520.top/Article/details/gtkzhnpzlz.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangtech.top/Article/details/gtaytwxgvq.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtolylgosm.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtijdvpvxx.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtarqbupmf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtonkcraka.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuibbqtk.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtzknjuwwh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gtxwlfxwko.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtethkiotn.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtikqsjiwv.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzuigeud.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwibcrbr.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtrtpwliyk.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gtwmlweqvm.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtfowrrmcm.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtulpkkdcz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gtsugsrgkj.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gtjfrmnxis.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtzgbayvvi.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gtqyhopxtu.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gturyhxgdu.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtxvzngztj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtbagfqlqk.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqdrnggs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gtdvybtuuf.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gtpzvyoosv.html

@contextlib.contextmanager
来源：http://dali.andypj.xyz/Article/details/gthayfilmx.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gtvbvtwyxp.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gtecsflkxq.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gteetrttli.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtyddokytc.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtgjhvjtul.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtuutfbnqc.html

[U25] Py：CSV 按字典读
来源：http://dali.shuidangran.top/Article/details/gtodsfqcaq.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtyietgzqu.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gtffmldgxd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtbjgeyevl.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gthsedecmg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gthlrcmsyb.html

[U28] Py：类型别名
来源：http://dali.shuidangran.top/Article/details/gtmyojuohg.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gtvhnqbjvw.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gtbqaasbof.html

@property 与 @x.setter 配合
来源：http://dali.gaohongyu789.top/Article/details/gtlknzotqb.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gtbmpqsvht.html

@dataclass(slots=True)
来源：http://dali.gogol.net.cn/Article/details/gtlshdosqj.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpenoiwra.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gttrtulacl.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gtigvewwma.html

ruff format . && ruff check --fix .
来源：http://dali.zhiwuduotai.top/Article/details/gthnwurnhw.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtrlxbrjoy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gtqwmktvqh.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gtlmylutlg.html

chardet.detect(raw)
来源：http://dali.chenlongwang.top/Article/details/gttstrqrrq.html

[U35] Py：发送邮件
来源：http://dali.iojbl.cn/Article/details/gtztmskppm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gtypykdqgz.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gtgkzakkqi.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gtijjkxbhl.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gtpsmhffkc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gtryhgpqyh.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gtmiymcwmu.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gtxulqhdxg.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gtfelrcxqs.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gtzcddutyi.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gtmxphtrcb.html

print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtkhezzdho.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gttdlosnsj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gtibdxtynh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gtkilgxind.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gtpkbnqvny.html

[U43] PHP：声明命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdmkwpcl.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gtfhvklejf.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gttlfegkov.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gtfjtnomlt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gtkrsdmcmz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtdvxvstzm.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gtfvrhuebv.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gtdrnzwxwt.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gtbnjheiwv.html

int|string $id
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkrrhcit.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtgttpiaso.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gtjxqmbpij.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtdqxyeatf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gtcfsizimf.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gttpbdsyvo.html

public function __construct(private int $id) {}
来源：http://dali.pycfn.com/Article/details/gtchreprlf.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gtlzamqqjz.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gtgxgnfytj.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gttdjhhwga.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtojgrncbr.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtipgmbcex.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhiwuduotai.top/Article/details/gtkjycewsy.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gtnaravfhf.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gtdwmqxvbr.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gthijhkycb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gtneygxyfj.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtixpkhhui.html

f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtrjppicft.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtdblykssf.html

"值: {$a}"
来源：http://dali.jqgfzy.top/Article/details/gtzdpvdpxo.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gtlyzjbhqr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gtiblpsuba.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gtjqvvwoud.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtggiyvwlp.html

[U60] PHP：JSON 编解码
来源：http://dali.jiagoushi.top/Article/details/gteddgryou.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwetabrek.html

[U61] PHP：正则
来源：http://dali.zhengqikj.top/Article/details/gtztpuxwai.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtnwqkupkg.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gtfjtkdyeu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gtyvdcuhlh.html

[U63] PHP：文件读写
来源：http://dali.jqgufenzy.top/Article/details/gtuezdszeb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gtavtdfdnq.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtdmxhicmh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gtutpixwvx.html

[U65] PHP：会话
来源：http://dali.fengsongda.top/Article/details/gtdpnsoryw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtbpydquqg.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gtyqifeaob.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gtchoogrey.html

[U67] PHP：处理文件上传
来源：http://dali.feifeiyinyue.top/Article/details/gtpblpucma.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gtlghnajjk.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gtyvqkolfg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dianchejie.cn/Article/details/gtwmvlcivx.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gterlonkyc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gtfiydbohj.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gtnpfmxcgu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gtiuhttaev.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtqvnjdfmb.html

throw new RuntimeException("失败", 500);
来源：http://dali.smart0.xyz/Article/details/gtptoaseyf.html

[U72] PHP：写错误日志
来源：http://dali.xuetiantiany.cn/Article/details/gtenjxwqas.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gtqlqhgoki.html

[U73] PHP：读取 ini 配置
来源：http://dali.hysaishi.cn/Article/details/gtwtufskuu.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gtktgkeueq.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtdowcngzu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtskhgzulf.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gtiezsozpe.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gtbgjufddh.html

[U76] PHP：简单路由
来源：http://dali.0kj1m.cn/Article/details/gtbfjdbxts.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuanzhike.top/Article/details/gtrekwkoax.html

[U77] PHP：模板渲染
来源：http://dali.iojbl.cn/Article/details/gtkctfhfve.html

composer require twig/twig
来源：http://dali.jianghu66.top/Article/details/gtinfdjozw.html

[U78] PHP：单元测试
来源：http://dali.daxiang520.top/Article/details/gtvkbwmztv.html

composer require --dev phpunit/phpunit
来源：http://dali.wangdashe.top/Article/details/gtijibwkyt.html

[U79] PHP：静态分析
来源：http://dali.tanke756.top/Article/details/gtdoesjvfm.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtzxmesvgi.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrhepqwz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gtuvghsthg.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gtmyppjytq.html

npm init -y;  npm i express
来源：http://dali.cashguo.top/Article/details/gtofsjhdwt.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gtsqotylch.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxuanxn.top/Article/details/gtbffdwgjm.html

[U83] JS：ES Module 导入导出
来源：http://dali.shuidangran.top/Article/details/gtrzvpvzvl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtopdpwlmu.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkglpdkq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gtzainzqtp.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtagnzuvxk.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsofidhgs.html

[U86] JS：空值合并
来源：http://dali.dianchejie.cn/Article/details/gtgbtqrtpn.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtajlhpmid.html

[U87] JS：解构默认值
来源：http://dali.hnxiangtu.top/Article/details/gtmnilqiwp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqezbfgj.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gtwgwwucox.html

{ ...a, ...b }
来源：http://dali.aizwys.cn/Article/details/gtpgxfiozx.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gtvibzuxgr.html

[...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtkxseawjh.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gtpbxvypra.html

[...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtcaxrdgvx.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigufen.top/Article/details/gtxsphoyxx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtpkftncxq.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gtiorjiezi.html

structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gterieungv.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtohgrdhyr.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoibrqilb.html

[U94] JS：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtagpfluri.html

const double = x => x * 2;
来源：http://dali.ivvv.top/Article/details/gtuqslvyod.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgybbsrk.html

new Promise((resolve, reject) => {})
来源：http://dali.sysykeji.top/Article/details/gtqtkpvuhh.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gtvgyslbvt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtozipisxk.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtnthkjyba.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtnhxepvfx.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtvcjsxnxn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnqzz.top/Article/details/gtxcukuaak.html

[U99] JS：事件监听
来源：http://dali.vqdsnc.cn/Article/details/gtdhdgvnpx.html

el.addEventListener("click", e => {})
来源：http://dali.tian-w.cn/Article/details/gtzzrsmzbz.html

[U100] JS：DOM 查询
来源：http://dali.jqgfzy.top/Article/details/gtpjcbbmnw.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gtupnsmaeu.html

[U101] JS：classList 操作
来源：http://dali.hysaishi.cn/Article/details/gtggnqrgun.html

el.classList.toggle("active")
来源：http://dali.shangyingyoupin.top/Article/details/gtqmsenvkd.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gthfhudpmq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gtaqsucfwe.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gtivlzrxjl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gtqblqpcoc.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtfxgwwynv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtqyzglxqq.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gtqsddkgmp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcnzzwuk.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtzwbiygtd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258888.top/Article/details/gtjuqmtlwg.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtjfeygqdj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.fengsongda.top/Article/details/gthimoefzb.html

[U108] JS：随机整数
来源：http://dali.ppjwa.cn/Article/details/gtwhdkniyb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jianghu66.top/Article/details/gtsuawfgwy.html

[U109] JS：数组分组
来源：http://dali.gaohongyu789.top/Article/details/gtuquhnibx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtaysanloy.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtdqjeqims.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtkthgemts.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtmklylnim.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtlnuiivuw.html

[U112] JS：字符串补位
来源：http://dali.xylfe.cn/Article/details/gtepkbvvpg.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtrmrmjcgq.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gtkmcahvvq.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqvrwzuf.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtotflkxoy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjfgthox.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtyyffieyb.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtezaxwwox.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj202588.top/Article/details/gtggufqdvh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gtcftgxpht.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtsuarrkgr.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gtkooushlv.html

[U118] JS：开发服务器
来源：http://dali.hysaishi.cn/Article/details/gtgdjcenno.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtrwbawmnj.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gtbjmahlxh.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtnuijktib.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gtfqfjkubu.html

import.meta.env.VITE_API_URL
来源：http://dali.316326.xyz/Article/details/gtoordhkeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtikkdolks.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gtwqnaxdhk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtauidznbj.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtberezzjc.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gthzxiafkg.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gtkuvvhsyf.html

JavaScript ..... 252
来源：http://dali.jqgfzy.top/Article/details/gtqrfckrla.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtmcvpoazv.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadhzziey.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtwxgiqgsn.html

Ruby ........... 212
来源：http://dali.chenlongwang.top/Article/details/gtxmjxtcum.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtnngpcsyp.html

C .............. 30
来源：http://dali.ydzc1.top/Article/details/gtlcwqbhho.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gtcxjsyxrb.html

SQL ............ 90
来源：http://dali.daxiang520.top/Article/details/gtkeixyqge.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gtubvyoute.html

Kotlin ......... 15
来源：http://dali.chenlongwang.top/Article/details/gtlwvzhzeb.html

Swift .......... 15
来源：http://dali.nwbrower.top/Article/details/gtnwtmzdms.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gtuueyasne.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gtmzsnthoo.html

Scala .......... 10
来源：http://dali.snrcjt.cn/Article/details/gtfpdvwhiy.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtudeowjpv.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtuzzrjdgg.html

按章节统计：
来源：http://dali.wangshuangyany.cn/Article/details/gtuhixmgps.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtcxnfzibh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtvffxfcnz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gttkrxuuor.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtrrnvvwom.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guannengcc.top/Article/details/gthmdeyomg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gthhrtkitl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtxjdiupyu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtmterwfrv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gthqkoozer.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gttqtfgguj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtuydlvezr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtrjkvyfdy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtqdsxsbvd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtfyfohwpk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.havefunace.top/Article/details/gtdrfbbtlr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtsiekkuyt.html

Q SQL 专题                              90
来源：http://dali.daxiang520.top/Article/details/gtthbygazj.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gtihwfczxz.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gtretboinh.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gtsghwyniw.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gtbihjwnfr.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtizdpbegf.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gtaanrrujk.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gthkvxyxgs.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gtshdcrduc.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtnpeplsic.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daria6918.cn/Article/details/gtcdfoalrh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtlaugqnkr.html


<!-- 参考信息 -->