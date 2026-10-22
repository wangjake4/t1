代发 wailian999

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gt2lczwejex.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2sqoutzln.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2lpoliapu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.havefunace.top/Article/details/gt2sjbbjoee.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2huetwbhu.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gt2cmdfdlbd.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eeiwwvxr.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjpqivrz.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2konqgtnk.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2uwxqgngf.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2kcfsgipu.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2ocupwmcj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2sjscxeoo.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2nqbmpmct.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gt2mufwpsur.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gt2gqgusfdt.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2zuszjtez.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gt2ebgstezw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2azdzuzqp.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gt2cxzadlki.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gt2cfdeyuvu.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gt2yqepmyzn.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2nsypvzpr.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gt2cbzanivv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gt2suveqzbi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2jhdxlkya.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2nfrzdktf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zivggcrh.html

[U01] Py：创建虚拟环境
来源：http://dali.gaohongyu789.top/Article/details/gt2illnndfg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gt2xlzpzkye.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sxryk.cn/Article/details/gt2gcebqgbm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gt2cfxvhtdd.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gt2djfooxjd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xziydtst.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gt2zrkkgovo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2swaqwiic.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gt2lmogflik.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2emjrthkz.html

[U06] Py：合并两个字典
来源：http://dali.quarkkingdee.top/Article/details/gt2onjdxpbe.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gt2peeednbg.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfuzlgwb.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gt2vmpifsok.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gt2lwggkfms.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gt2wnfkbbwb.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gt2asyudsao.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gt2wxqbmeuz.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gt2stvubqxy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2weizputh.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uilhchqw.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ietxscon.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gt2cqufhboi.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gt2mefsvuht.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gt2knfgpevl.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gt2nbzyelgo.html

[U14] Py：分组收集到列表
来源：http://dali.yangfankeji.com/Article/details/gt2jcgvtocg.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gt2rdsarcfy.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gt2bohucpza.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trixxfpa.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gt2erehmxqr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gt2tbuudlpf.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obxrrfox.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gt2jyffhdwn.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gt2tojtmsdr.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2sbwiymrf.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gt2sbppgwtw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gt2jeojggdv.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gt2cadapprc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gt2axsckopt.html

[U21] Py：自定义上下文管理器
来源：http://dali.yonumen.top/Article/details/gt2egnfwgiw.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gt2sauftctn.html

[U22] Py：矩阵转置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikghcxpt.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gt2rfiphgxg.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gt2hbbbbihy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gt2thbpujvp.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gt2pbrvjxuk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2yhdfgaln.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gt2xuzkihon.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oprcuooo.html

[U26] Py：并发下载
来源：http://dali.nwbrower.top/Article/details/gt2hxyxknjp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gt2bgxmgsxc.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gt2guddsrck.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gt2kegqmycj.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gt2xhnmyiyw.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gt2xueogals.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gt2mgehdybm.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gt2tvbwsioc.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gt2jwpkluqa.html

@dataclass(slots=True)
来源：http://dali.dashuyun.cn/Article/details/gt2umuvnong.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gt2tbisijnj.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gt2tihpjaoa.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gt2yvqfhmzf.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gt2dxynncoo.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdnppctb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gt2arpnoopg.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gt2uepvugiq.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gt2drthwcdh.html

[U35] Py：发送邮件
来源：http://dali.birdmap.top/Article/details/gt2oxajexnl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edhiqnwt.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gt2ynijgeac.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gt2asdkcgtt.html

[U37] Py：读写 Excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhmcfcgh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2xsdhymgk.html

[U38] Py：获取脚本所在目录
来源：http://dali.ybcxt.top/Article/details/gt2zexnkciy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdirxkz.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrvluupp.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gt2ufgnkiql.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gt2uinqulgl.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2uwbjhjbs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gt2pmkxygby.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gt2katxhwld.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gt2vpmkfqbf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ataunbnt.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gt2dswyhafu.html

namespace App\Http;
来源：http://dali.cdnleiting.top/Article/details/gt2lyxcgtnf.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gt2epgyxeax.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gt2jgabgbrd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gt2hvbqwcjk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mvdeyshz.html

[U46] PHP：可空类型
来源：http://dali.0kj1m.cn/Article/details/gt2qyhcgnpm.html

?string $name = null
来源：http://dali.cqqwz.cn/Article/details/gt2witnthod.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fapalfie.html

int|string $id
来源：http://dali.snrcjt.cn/Article/details/gt2urkwxkkc.html

[U48] PHP：纯枚举
来源：http://dali.aibaodan.cn/Article/details/gt2jeqoiucs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpqghpkz.html

[U49] PHP：只读属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2homdfxqa.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gt2ksiwbsmn.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezzhdxca.html

public function __construct(private int $id) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2mkezlwod.html

[U51] PHP：数组解构
来源：http://dali.guowangkeji.top/Article/details/gt2occaaeta.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gt2vdzwqsmm.html

[U52] PHP：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2qemsrpxr.html

$double = fn($x) => $x * 2;
来源：http://dali.dianchejie.cn/Article/details/gt2nasxvlng.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gt2xadlgloo.html

$v = $a ?? $b ?? "default";
来源：http://dali.xinyue.icu/Article/details/gt2dcnkrghc.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gt2fsfipltk.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gt2wiujotxl.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gt2cuilfcjt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsqmdtyq.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gt2kzciwfic.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gt2lmwcuouj.html

[U57] PHP：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2ebvnvcut.html

"值: {$a}"
来源：http://dali.yanxiufei.cn/Article/details/gt2xgtrmfbt.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gt2igqyiwna.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gt2nwtfmxzo.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gt2llzoinsw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2dwvgjqas.html

[U60] PHP：JSON 编解码
来源：http://dali.birdmap.top/Article/details/gt2qbgisitq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gt2nyyzutwv.html

[U61] PHP：正则
来源：http://dali.iojbl.cn/Article/details/gt2onmjaymq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2nnqfpsrl.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gt2qhaahayr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gt2potegzlk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjncidq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gt2yxflognz.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gt2gofytuva.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenzaomai.com/Article/details/gt2klawniwn.html

[U65] PHP：会话
来源：http://dali.hysaishi.cn/Article/details/gt2gokfxhpp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2jvrelhqp.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gt2tkfkurwd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gt2gwjiaaog.html

[U67] PHP：处理文件上传
来源：http://dali.guowangkeji.top/Article/details/gt2kiwbafgu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gt2yopfpwgp.html

[U68] PHP：PDO 连接
来源：http://dali.pycfn.com/Article/details/gt2jffhjuuk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgpqaleq.html

[U69] PHP：PDO 预处理
来源：http://dali.aizwys.cn/Article/details/gt2zilavlaa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gt2tpfxsqmt.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2gblpwmtv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgsmkje.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2cptxggbn.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gt2muxcyteh.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gt2ggiflyot.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gt2mdtsntjv.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gt2hicultuk.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gt2deigraff.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2xklwotfv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gt2fcejnoos.html

[U75] PHP：依赖注入
来源：http://dali.sysykeji.top/Article/details/gt2aumxkwcr.html

composer require psr/container
来源：http://dali.jqgufenzy.top/Article/details/gt2hgryyhaj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyayqzm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uertiega.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biskcpao.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gt2pshakola.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojphzucp.html

composer require --dev phpunit/phpunit
来源：http://dali.chenzaomai.com/Article/details/gt2trizddaq.html

[U79] PHP：静态分析
来源：http://dali.tanke756.top/Article/details/gt2iqocpidk.html

composer require --dev phpstan/phpstan
来源：http://dali.havefunace.top/Article/details/gt2tfprrvvf.html

[U80] PHP：代码规范修复
来源：http://dali.shuidangran.top/Article/details/gt2oplwjatx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgwmrvfn.html

[U81] JS：初始化项目
来源：http://dali.zycfv.cn/Article/details/gt2guoszdsc.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gt2kajwetof.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gt2bzkasnqp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2stdtiyte.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuanzx.com/Article/details/gt2pprjvkwf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2qiaqgyzm.html

[U84] JS：CommonJS 写法
来源：http://dali.redwolf501.top/Article/details/gt2ogmqvnof.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gt2ulxkdgeo.html

[U85] JS：可选链
来源：http://dali.jlsjyb.cn/Article/details/gt2vxfvxrws.html

a?.b?.c
来源：http://dali.xuanzx.com/Article/details/gt2dvxwbhhf.html

[U86] JS：空值合并
来源：http://dali.nwbrower.top/Article/details/gt2ucggnycl.html

a ?? b
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhjhopgb.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gt2ogkrvbuk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozbghbes.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gt2zrqsbsxb.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gt2gnxjcvxd.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gt2febxxetg.html

[...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2vofnooab.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuncgvc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2tnoblpip.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfvrrstf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gt2uqxwnmxf.html

[U92] JS：深拷贝
来源：http://dali.yj20258.top/Article/details/gt2hopxozcf.html

structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkcvvhvo.html

[U93] JS：模板字符串
来源：http://dali.ydzc1.top/Article/details/gt2paqrsnci.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqzneemy.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gt2rabssmht.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gt2jbpezwgf.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gt2nfteawmh.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gt2ikxegiss.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytvhfbnd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2ykvhuqbd.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gt2dcqzvoya.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2raitxkwc.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2mjvhrgjy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gt2aoazjsqo.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gt2mdnvahml.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gt2xbyzugss.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gt2ktnukrdv.html

document.querySelector(".item")
来源：http://dali.zycfv.cn/Article/details/gt2dmuvpmfo.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gt2oiqmvafh.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wemrjfha.html

[U102] JS：本地存储
来源：http://dali.yangfankeji.com/Article/details/gt2krrhaxuy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gt2ikhmcnnq.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gt2owdpqczb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gt2chkodvkc.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gt2ucrspzvi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2kazyzlgp.html

[U105] JS：节流
来源：http://dali.xuanzx.com/Article/details/gt2unllbjje.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2sieyussc.html

[U106] JS：日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2zzaknooz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gt2mfnqokad.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gt2wisijjby.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gt2zcpitirv.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gt2kedrpmwm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gt2fqrydgpv.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gt2jjmhonbw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2gfzizybr.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gt2njddjdks.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovhucbnn.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gt2vtgekrua.html

new Map(Object.entries(obj))
来源：http://dali.sufxvd.cn/Article/details/gt2wvfgjrfl.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gt2lngvcnjb.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2aivcpjaz.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gt2znskzwlo.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2csudtcgg.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gt2xgtulfad.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2uyqlpony.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2jcvpmqwm.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2csfqnzmj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gt2yashhpdg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rwfqkaln.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gt2qokfzzsh.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gt2cjxiignq.html

[U118] JS：开发服务器
来源：http://dali.hywenlv.cn/Article/details/gt2frnqdpkq.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2wisrjceb.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gt2xqoilhfe.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gt2umypmngs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2vwrwyinf.html

import.meta.env.VITE_API_URL
来源：http://dali.fengsongda.top/Article/details/gt2hrlcpkwy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pvgeypiu.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfwiarzp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2snmepilj.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gt2fqbammek.html

Python ......... 252
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhgblvpu.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gt2lfehxakg.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gt2xomcptzq.html

TypeScript ..... 212
来源：http://dali.aibaodan.cn/Article/details/gt2jeuqbtbt.html

Java ........... 212
来源：http://dali.sweek.top/Article/details/gt2pdpokwdk.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2uwzhrnso.html

Ruby ........... 212
来源：http://dali.snrcjt.cn/Article/details/gt2ihpwlxdk.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gt2crkznpaz.html

C .............. 30
来源：http://dali.tianlin.xyz/Article/details/gt2nhzzidok.html

C++ ............ 30
来源：http://dali.ppjwa.cn/Article/details/gt2noaroeiv.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gt2dgzscuth.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gt2luniqgxq.html

Kotlin ......... 15
来源：http://dali.xuanzx.com/Article/details/gt2ofysyogn.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gt2mgqkwkoc.html

Lua ............ 10
来源：http://dali.zdqjudy.top/Article/details/gt2fnofudom.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gt2frsetnet.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gt2dpdhzsbn.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2aizunagb.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gt2kirpejsx.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gt2aupxxqik.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gt2fdkcwhwr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2vshfqlma.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2qaolhsvz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gt2mrqsqdli.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ydzc1.top/Article/details/gt2dxrxldjt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gt2lmascstp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2bisefttd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gt2nzdmuxup.html


<!-- 参考信息 -->