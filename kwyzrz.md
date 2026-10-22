代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gt2jrxdzecz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2cfpsltua.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gt2yxntmuqw.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gt2azrjfmks.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gt2tplgnysa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2nlxiswlx.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcwqndsg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gt2gxmhkizx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifmoayys.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2tnrhncak.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2uylxxgoq.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gt2dqzaigvp.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gt2osydstod.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2mhdzhyqb.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2tnjyqnap.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2nvajlkhq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zukprwfh.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2ivdrqykl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbflipvs.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gt2vtbolhpq.html

case class User(name: String, age: Int)
来源：http://dali.cheryme.top/Article/details/gt2emelvpzg.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2feqxmjjd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gt2vcnoeqwr.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gt2ateygnxq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gt2alknrkom.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gt2ngyizjws.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2hopnbezw.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gt2dztkgdtp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gt2vzuzxjvg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubwgifqx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2liybgxbd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wclqbzax.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gt2bqblgdzu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awdpczdk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gt2miuexheg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2iyqtvwla.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gt2niwcvgnc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mximywbv.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gt2chuqclak.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gt2vscyyugp.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyoiysiq.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2sjuqnmje.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gt2neksoolp.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gt2zglvsykv.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gt2uddzijwt.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gt2xghdrkmm.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gt2fefjjeaw.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gt2ludrmnaj.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gt2jckqixbt.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gt2thhvuatx.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gt2bteybdml.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gt2cuxqoflt.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gt2lrgymprv.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gt2osjrktkp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbudlrlw.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kybdrsvj.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gt2xpdzvycw.html

deque(maxlen=10)
来源：http://dali.xuanzx.com/Article/details/gt2fyilnogz.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gt2vcilldug.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gt2crqmvwnb.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghaijayo.html

t = time.perf_counter()
来源：http://dali.meibo888.top/Article/details/gt2rwdlguyz.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gt2efirosrl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsutmckd.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhlnzokv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gt2nymlmjjx.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gt2vnengtut.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gt2mreyvitq.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gt2bbkjmwel.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gt2twcqpkog.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gt2dgfxrqhm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gt2xgcbdwos.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gt2nyetwlhm.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gt2wpnfmbaf.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gt2aqgnsitg.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gt2jvtkenha.html

[U23] Py：分块读取大文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqjqrfun.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.smart0.xyz/Article/details/gt2ulpkcefj.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gt2trlpceop.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2vfukptih.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lstyzzvu.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gt2bjqslcvm.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gt2wagaipbu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gt2dcexuoam.html

[U27] Py：异步 HTTP
来源：http://dali.hywenlv.cn/Article/details/gt2rrzenycl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gt2vbyvwfte.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gt2mebrorey.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gt2xadbmzxw.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gt2ggsfmwij.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gt2iggohsyj.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdwppocn.html

@dataclass(slots=True)
来源：http://dali.daria6918.cn/Article/details/gt2ldcpyqeh.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsnvkdjb.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gt2uhoezjrm.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gt2tguggddz.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gt2usyyjqyt.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gt2emndqeiu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ivvv.top/Article/details/gt2yykpabws.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gt2ymeggikd.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gt2dmxtgrmx.html

[U35] Py：发送邮件
来源：http://dali.cheryme.top/Article/details/gt2fapacdmc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fychotvj.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2jifbfjmo.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gt2kmkkejge.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gt2heoipctp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.birdmap.top/Article/details/gt2vcywddip.html

[U38] Py：获取脚本所在目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfxqmmgp.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gt2wzoomkzr.html

[U39] Py：判断是否在交互环境
来源：http://dali.hywenlv.cn/Article/details/gt2unuqddhb.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxggrvtj.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gt2ykzvqksn.html

print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2cdduechw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gt2pkeaugwz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gt2jkmmuoke.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gt2gltwqxwg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gt2elzaqiui.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejfuqmcb.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gt2xwjsfxqe.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emkrecdp.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gt2wljwrgbh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gt2ehjjdknk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2aaoqonwd.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gt2nnpkuozp.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gt2tmbgjemb.html

[U47] PHP：联合类型
来源：http://dali.yj202588.top/Article/details/gt2znwakcuf.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gt2ovtvqvav.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gt2zlvgzimx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.iojbl.cn/Article/details/gt2fmonyjxm.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gt2xcmbtdzk.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gt2casnfygg.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gt2ajqkyzok.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gt2dmwvkxwe.html

[U51] PHP：数组解构
来源：http://dali.gogol.net.cn/Article/details/gt2mxxtarjj.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gt2gakypwjl.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gt2snojkxdn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oncrwvyj.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gt2xdglphks.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gt2lgnshmql.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gt2jiovnolt.html

$obj?->method()
来源：http://dali.jianghu66.top/Article/details/gt2pmavovoz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bilqghjw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtupiqpj.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gt2lxaadbqq.html

f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wazmebdt.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2draglgod.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gt2fnddexsp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsobqtp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gt2lpoyozyb.html

[U59] PHP：自定义排序
来源：http://dali.sxryk.cn/Article/details/gt2nibrjslr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gt2bxpeczcf.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258888.top/Article/details/gt2sxxtvqse.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fzhhl.top/Article/details/gt2luioriwu.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gt2vumacgwp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvjnrpyi.html

[U62] PHP：日期对象
来源：http://dali.chenlongwang.top/Article/details/gt2wpszznjk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yangfankeji.com/Article/details/gt2fmdsglpu.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gt2ygwcvbdj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gt2vchzqwkq.html

[U64] PHP：目录遍历
来源：http://dali.jqgfzy.top/Article/details/gt2azwbepsw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gt2wivhqbwz.html

[U65] PHP：会话
来源：http://dali.redwolf501.top/Article/details/gt2uygbwxja.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2shdqyuls.html

[U66] PHP：设置 Cookie
来源：http://dali.sweek.top/Article/details/gt2lojhgoau.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cheryme.top/Article/details/gt2hpukkqoy.html

[U67] PHP：处理文件上传
来源：http://dali.sysykeji.top/Article/details/gt2cbueeptj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gt2tqadfudf.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gt2yzrzjckg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnqzz.top/Article/details/gt2pjmyygim.html

[U69] PHP：PDO 预处理
来源：http://dali.iojbl.cn/Article/details/gt2zpuqxawp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gt2tjggxpww.html

[U70] PHP：PDO 事务
来源：http://dali.daria6918.cn/Article/details/gt2rirhooyx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aibaodan.cn/Article/details/gt2xzyrzvzq.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2ywahkdej.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2fodnvhrr.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gt2hoshqfuc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gt2egpvikll.html

[U73] PHP：读取 ini 配置
来源：http://dali.c1oappe.top/Article/details/gt2kycoikvt.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gt2wyrwlzus.html

[U74] PHP：读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2hqsstnuh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gt2vjjcjddc.html

[U75] PHP：依赖注入
来源：http://dali.jinqigufen.top/Article/details/gt2mkoucsek.html

composer require psr/container
来源：http://dali.yangfankeji.com/Article/details/gt2fwdzkvvr.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gt2aesqkdpx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gt2kjarxind.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gt2qpeejodx.html

composer require twig/twig
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygjhyhpl.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gt2rygriqrh.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gt2gnvbldje.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gt2puftbxof.html

composer require --dev phpstan/phpstan
来源：http://dali.shzxlz.cn/Article/details/gt2gsuxqwrm.html

[U80] PHP：代码规范修复
来源：http://dali.pengpengdd.cyou/Article/details/gt2cngzyfoe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hfpthk.cn/Article/details/gt2npkxhkmi.html

[U81] JS：初始化项目
来源：http://dali.zdqjudy.top/Article/details/gt2zpocsvvh.html

npm init -y;  npm i express
来源：http://dali.snrcjt.cn/Article/details/gt2krfnmfxb.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gt2bhcxmaqr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aeklluzi.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxuanxn.top/Article/details/gt2rymyywky.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gt2xppjxjrr.html

[U84] JS：CommonJS 写法
来源：http://dali.haohaochexian.top/Article/details/gt2wjmzotjx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnqzz.top/Article/details/gt2wvxqoqmk.html

[U85] JS：可选链
来源：http://dali.haohaochexian.top/Article/details/gt2mfsmzcyw.html

a?.b?.c
来源：http://dali.daxiang520.top/Article/details/gt2gwrxlyjm.html

[U86] JS：空值合并
来源：http://dali.redwolf501.top/Article/details/gt2rwjgwqii.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfzezmsp.html

[U87] JS：解构默认值
来源：http://dali.fengsongda.top/Article/details/gt2oxhccvnx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gt2dgggmnqn.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gt2hmzncpjy.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gt2wnnrdyyi.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gt2cfuzzkux.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2paleexir.html

[U90] JS：数字数组排序
来源：http://dali.aibaodan.cn/Article/details/gt2cdtnxqrz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2ybtijyjd.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigufen.top/Article/details/gt2cnnlovrq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daria6918.cn/Article/details/gt2vmfvsqco.html

[U92] JS：深拷贝
来源：http://dali.birdmap.top/Article/details/gt2pfmckxvn.html

structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmklglem.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gt2mzzhdjjq.html

`共 ${n} 条`
来源：http://dali.xziqi.cn/Article/details/gt2boirgbqy.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifdxiuci.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gt2xncadsiz.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gt2noaqmkux.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2iilwpklk.html

[U96] JS：async/await 与异常
来源：http://dali.ybcxt.top/Article/details/gt2bcwjnphu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2blhbiulk.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gt2tgjivitp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2zbccmyth.html

[U98] JS：fetch 带 JSON
来源：http://dali.fengsongda.top/Article/details/gt2jibxbovu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fzhhl.top/Article/details/gt2mzyjzghz.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gt2dylvpife.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258888.top/Article/details/gt2epdtpshu.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gt2zupdutfd.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gt2bjjjlnjq.html

[U101] JS：classList 操作
来源：http://dali.jinqigfzy.top/Article/details/gt2odwnrwqb.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gt2nsolqckb.html

[U102] JS：本地存储
来源：http://dali.zdqjudy.top/Article/details/gt2gjehoeao.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gt2ujtfgjiw.html

[U103] JS：定时器
来源：http://dali.pycfn.com/Article/details/gt2hdazbfdh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.kuanghao11.cn/Article/details/gt2ibwhmawh.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gt2wzhjokdq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2amevtizj.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gt2rwenxhat.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcfaleon.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2fcprjvdd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gt2wikenckj.html

[U107] JS：数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2ocrjzfdq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2djfrluiu.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gt2jhssyeql.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhcwatrk.html

[U109] JS：数组分组
来源：http://dali.zhixingplan.top/Article/details/gt2iyvibevf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xufgntrh.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zflgofxl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.birdmap.top/Article/details/gt2ufxkjnrp.html

[U111] JS：对象转 Map
来源：http://dali.jqgfzy.top/Article/details/gt2lpawjuna.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2gknmrzpi.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gt2dznlkbmp.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2wadrvsix.html

[U113] JS：正则替换全部
来源：http://dali.aibaodan.cn/Article/details/gt2dzdunmar.html

s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2oplcqqsr.html

[U114] JS：JSON 深比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntxqljrk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ousytxbe.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2urizwbkm.html

crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjubyavm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gt2omuintrc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gt2tumtcqqq.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nylawswc.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gt2kuevruxg.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gt2bjkdhbcd.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gt2ihjwsvmp.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gt2lfbrxrdi.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gt2xycdpglg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gt2qehjigyy.html

import.meta.env.VITE_API_URL
来源：http://dali.hywenlv.cn/Article/details/gt2arvdttvl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yxhzkiej.html

统计汇总
来源：http://dali.jinqigfzy.top/Article/details/gt2qcoklbua.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kxizrgyo.html

按语言统计（条）：
来源：http://dali.redwolf501.top/Article/details/gt2xxgnramg.html

Python ......... 252
来源：http://dali.fengsongda.top/Article/details/gt2adawrntz.html

PHP ............ 252
来源：http://dali.mhx1999.top/Article/details/gt2ugdnmvbh.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gt2afuspejt.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gt2zzezpfjk.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2zzirtaru.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcafynjc.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2mvffttqj.html

C# ............. 212
来源：http://dali.bjfxy.top/Article/details/gt2coedzrck.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gt2ewwukwtr.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gt2laefpnry.html

SQL ............ 90
来源：http://dali.havefunace.top/Article/details/gt2ufemttwf.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gt2pojvkkdy.html

Kotlin ......... 15
来源：http://dali.xuanzx.com/Article/details/gt2tjhxqkfo.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gt2kkqpowkb.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gt2sqzanuww.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gt2cpntjjbx.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gt2qwegjsaw.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2qqvgrzdy.html

合计 ........... 2106 条
来源：http://dali.havefunace.top/Article/details/gt2lmjwnpfv.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gt2djbpfttb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gt2hrqxmaqz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2dtzwamsz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gt2jwublehu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwokxems.html


<!-- 参考信息 -->