代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gtzhrsmmlw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnxjrwcgc.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtaidsevnx.html

$s =~ s/old/new/g;
来源：http://dali.yonumen.top/Article/details/gtbabdlgzg.html

[T49] Perl：函数
来源：http://dali.316326.xyz/Article/details/gtnocwmpsg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtmrlkejgv.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtemzwgusx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsnxgsww.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtmfdrwnyf.html

[T51] Scala：Hello World
来源：http://dali.daria6918.cn/Article/details/gtgaevfgyo.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtuwldoqql.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gttivkxapt.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gtpvdkpvwm.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtxgtvlgtq.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtokigvpgu.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gtygidxuyh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtqoynfpcj.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndmomhcb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqsefcfqm.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gteqjyqkdj.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gtztkgamrb.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtxznhvmzh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttktqwlfv.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gtkqfzwojq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtxgqmxjhj.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gtfwazyzic.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtoiipaxsj.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gtwqpwoxqv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gtflkdlwyv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrhbazgnz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtbfycbnot.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoreozieu.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gtsdcqxobw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gttokkqmcf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtdjpmyknr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtykmnwwwo.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtcyowzpzf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gtmssapjfz.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gthashasbv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtmfdfvowb.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtsibfarnx.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gttlvambug.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtqqhucdpd.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtmvqgvody.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gtwfbbwbtj.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gtqjufpekp.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gtjifluqhp.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtrpxspjar.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtkwmpdtxp.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gtbodrncci.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtgthsjrfr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gtqmzqjhdp.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gtyzssrxro.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtsmcovnfe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtsvjyfxfy.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gtwayymnbf.html

[U13] Py：固定长度队列
来源：http://dali.sufxvd.cn/Article/details/gtdjbikydw.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gtyhqcupxn.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gtqfnnokzj.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtwdjlozmo.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gtsrjynqlo.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtglamftfw.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtfynprrbe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gthjyvmxpf.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtvpkpqlyb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtrwmioati.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtdyemioxm.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gtywmbvyzo.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gtofdpttxf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gtavfbnlgg.html

[U20] Py：缓存函数结果
来源：http://dali.wangdashe.top/Article/details/gthyjxdsoi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gtwofxxrpe.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gtglrduubq.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gtnjqhovdw.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gtmnseshgo.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gtmrcegfdn.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmanblaw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gtevbrcbgb.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gtaxlqvqxd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtmcnejmbl.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gternrdnsk.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtjskvkrma.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gtaxqegocy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.9152youxi.cn/Article/details/gtshkxavyq.html

[U27] Py：异步 HTTP
来源：http://dali.xziqi.cn/Article/details/gtpikpkknn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gtngbfbiis.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gtjayidpxk.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gtgatgqbzg.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcucncws.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtirxjwrtj.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtwtwkuexx.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gtqgwytllh.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtbwvinydq.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gtzaguvvbu.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gttkfwznpf.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gteakipdpt.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtbhpzhmpd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gtkkvgtysw.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtejceqofu.html

chardet.detect(raw)
来源：http://dali.wangshuangyany.cn/Article/details/gtziqkowkb.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtmhchereg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pycfn.com/Article/details/gtcuuciizs.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtuoccjluq.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gtgengadas.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gtnnaovwkz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gtpwotigzf.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gtjvxvejet.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gtduzkuzft.html

[U39] Py：判断是否在交互环境
来源：http://dali.shangyingyoupin.top/Article/details/gtoajowuqi.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gtydkadtxo.html

[U40] Py：打印到标准错误
来源：http://dali.hywenlv.cn/Article/details/gtyimoawfz.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtebjdqboo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwzvnjph.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gtezvypwhg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gtsuwkuioz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gtgfleupnd.html

[U43] PHP：声明命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxszshvb.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtaidogbqi.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gtxleujomh.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gtixgmlbyu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pycfn.com/Article/details/gtnynqhqem.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtfkovwhgb.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gtxhlopatf.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtmtkicttu.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gtekeucvcn.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtyewamqey.html

[U48] PHP：纯枚举
来源：http://dali.ehwqpu.com/Article/details/gtgqprdxhm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnxiangtu.top/Article/details/gtzxcwfqwr.html

[U49] PHP：只读属性
来源：http://dali.yuanzhike.top/Article/details/gtlgvdrfhq.html

public readonly string $name
来源：http://dali.9152youxi.cn/Article/details/gtbehmmoiv.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtqivbjeee.html

public function __construct(private int $id) {}
来源：http://dali.ppjwa.cn/Article/details/gtnvogguvm.html

[U51] PHP：数组解构
来源：http://dali.yuanzhike.top/Article/details/gtcfakttzu.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gtpmllyzqi.html

[U52] PHP：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtwmtpzmxh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gttnqokwoz.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gtcdrnibkr.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gtrmsblekd.html

[U54] PHP：空安全调用
来源：http://dali.birdmap.top/Article/details/gtsizacxlv.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gtijwuwrxc.html

[U55] PHP：match 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtyrmeojqx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtvmpcvokb.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtqrhjpmkw.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtogdduscb.html

[U57] PHP：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtpgjtgfty.html

"值: {$a}"
来源：http://dali.sufxvd.cn/Article/details/gtvjgoiotn.html

[U58] PHP：数组三件套
来源：http://dali.gzhubu.top/Article/details/gtmqxbvfip.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtrrhtmzhh.html

[U59] PHP：自定义排序
来源：http://dali.daria6918.cn/Article/details/gtlhxkqkju.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtixxxykpl.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gtpdqroucy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cashguo.top/Article/details/gtodamflpi.html

[U61] PHP：正则
来源：http://dali.zycfv.cn/Article/details/gtqbmyefcl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtgnqmhztf.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtswhphsas.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gaohongyu789.top/Article/details/gttxgqgste.html

[U63] PHP：文件读写
来源：http://dali.ivvv.top/Article/details/gtmspblsvz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yonumen.top/Article/details/gtkckstdbc.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gtdcvjzsbw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtxjpevtlq.html

[U65] PHP：会话
来源：http://dali.chenlongwang.top/Article/details/gtwgnsgbbe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtzqlqntyt.html

[U66] PHP：设置 Cookie
来源：http://dali.yangfankeji.com/Article/details/gtmupkrfit.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gtxkeyhgvu.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gtmerhpvfd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gtoyaefuja.html

[U68] PHP：PDO 连接
来源：http://dali.ybcxt.top/Article/details/gtxzqyqebv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gtxnqvcjse.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gtghrotgpz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtvbiflaph.html

[U70] PHP：PDO 事务
来源：http://dali.hfpthk.cn/Article/details/gtvnwzlxfv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nwbrower.top/Article/details/gtfqeqzsvj.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtbjybhdvd.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gtxotwetqa.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gtdiuixtws.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gtgeebuhou.html

[U73] PHP：读取 ini 配置
来源：http://dali.jqgufenzy.top/Article/details/gtqtkynmyg.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gtoevhpjfg.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtnfpxsbtm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigufen.top/Article/details/gtpooogmsr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gtgovxcuaa.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gtgkidcnrf.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtfnkdrglr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtqnortxgx.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gtvptrltbw.html

composer require twig/twig
来源：http://dali.cdnleiting.top/Article/details/gtmjhtqgpk.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtgukpmbsv.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gtwdodgbll.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gtbjqumjtd.html

composer require --dev phpstan/phpstan
来源：http://dali.havefunace.top/Article/details/gtfpszsvyl.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gtevmwfryg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gtfsenjbwf.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gtuqriylup.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gtygjlbooc.html

[U82] JS：package.json 脚本
来源：http://dali.haohaochexian.top/Article/details/gtyaumdkci.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.snrcjt.cn/Article/details/gtjkiruayb.html

[U83] JS：ES Module 导入导出
来源：http://dali.daria6918.cn/Article/details/gtuuflspsl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtrfezinky.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gtnvceklbn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhixingplan.top/Article/details/gtgiddzaff.html

[U85] JS：可选链
来源：http://dali.gzhubu.top/Article/details/gtnskpvtqg.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gtcdrokbbj.html

[U86] JS：空值合并
来源：http://dali.jinqigufen.top/Article/details/gtiedxlask.html

a ?? b
来源：http://dali.snrcjt.cn/Article/details/gtzvnmtmon.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtlnwfnquw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttjkpkot.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gtpfiebdxe.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gtqytmwtmd.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gthxgqjkqn.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtggfkpzeq.html

[U90] JS：数字数组排序
来源：http://dali.hywenlv.cn/Article/details/gtskkoizjk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtlexehzov.html

[U91] JS：对象键值遍历
来源：http://dali.xziqi.cn/Article/details/gtgzaexvcu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ppjwa.cn/Article/details/gtibhphucw.html

[U92] JS：深拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhucmevk.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtsgronuyt.html

[U93] JS：模板字符串
来源：http://dali.jinqigfzy.top/Article/details/gtyyxqxusc.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gtfenyphfa.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtuvehgqfq.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtqzjemhxk.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlyrwmdu.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtxuaxnjtu.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gtuebyhwmc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtbuhmueut.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtnnbxtudw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtyfoerlic.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gtpeybgerd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gtyqlpjtaj.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gtlrgkqvnn.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gtxhvhwugh.html

[U100] JS：DOM 查询
来源：http://dali.yonumen.top/Article/details/gtbijtqkvi.html

document.querySelector(".item")
来源：http://dali.shzxlz.cn/Article/details/gtkjeapzpf.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gtmodmyxvi.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gtyyulnqzj.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gtweunpifi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtzownrqyu.html

[U103] JS：定时器
来源：http://dali.yuanzhike.top/Article/details/gtzsyfdjeh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gtktbeydco.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gthfedydnb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtagmmmkpa.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtpvnsfhob.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtbfqkpswb.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtvgmwkfow.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhiwuduotai.top/Article/details/gtmqsktkfx.html

[U107] JS：数字千分位
来源：http://dali.mhx1999.top/Article/details/gtmdgjiwyc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtjylkqyyo.html

[U108] JS：随机整数
来源：http://dali.hnqzz.top/Article/details/gtcgxepcqk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtinwnbxbg.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtwqxqpmqv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gttjdfgann.html

[U110] JS：数组分块
来源：http://dali.ybcxt.top/Article/details/gtfzpubxjv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gthseghcmo.html

[U111] JS：对象转 Map
来源：http://dali.quarkkingdee.top/Article/details/gtfukbcvbv.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gttjoqvjcl.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gtnuljhbmm.html

"7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtbpggowyt.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtxiwrmkzk.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnkesnyi.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstqtjrxt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtepybsoso.html

[U115] JS：生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrpuxdla.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtyxptgdfk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sufxvd.cn/Article/details/gtycggyhoq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gtkumpquta.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gtudwegbvy.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtnshznzpk.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gtybmvzktz.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gtwldvovja.html

[U119] JS：生产构建
来源：http://dali.316326.xyz/Article/details/gtsfasdiga.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtbbaynpja.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtpfhhjugi.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtotyuhsru.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtezmnkuiy.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gtjllynsbg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnnfdcced.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtxtvozcuz.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngecnquq.html

PHP ............ 252
来源：http://dali.gogol.net.cn/Article/details/gtvjwyrfmo.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtmzwndpuo.html

TypeScript ..... 212
来源：http://dali.fzhhl.top/Article/details/gtulgcdnxq.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtbvcqjvks.html

Go ............. 212
来源：http://dali.cdnleiting.top/Article/details/gthmfhbtzp.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtwiveffof.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gttnaagzyj.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gtcsjzrwyr.html

C++ ............ 30
来源：http://dali.zdqjudy.top/Article/details/gtarqnjuqt.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gtquaujntu.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gtxlqqielt.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gtfjwtvpvk.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtjxkzwfye.html

Lua ............ 10
来源：http://dali.jinqigfzy.top/Article/details/gtbdlmtuve.html

Perl ........... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtggjgeouu.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gtjgizjqhd.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gthhplynza.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gtlkcluigq.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gtisdyxgvc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtfudxkomm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtpzitbhma.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtlzxaglqa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtnouoehvy.html


<!-- 参考信息 -->