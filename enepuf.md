代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtnfnlrweb.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtnegxldbb.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gtushlhzxp.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtepxdbrwa.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtywvbbocs.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtruamiack.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gttevnltcs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtpiokwppi.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaukqkael.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtjvbjtkrd.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtnngexjen.html

$s =~ s/old/new/g;
来源：http://dali.pycfn.com/Article/details/gtfqyjotnu.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtruigilww.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgebhlsr.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtlynwcjsy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gttnxvxuwm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtjjphcqap.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtvwjigkkp.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtzjttwgbk.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gtlzqbpzwa.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtjcqxzlfn.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtaqpwutfi.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtlqrldpsd.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtrhrvhith.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gtsthmzzbr.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtmtvtmawj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gtcdemwrjg.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gtgddgphkc.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtpinxfxil.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gtwnhxiugp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtpfvdaqwx.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtklzpktkf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtwjlajpgc.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtunxefvtr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtunyyrrgx.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtfcwqmbfm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gtyvklrevn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtylptdonz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtmxqketur.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqkhobaep.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gtfgfdzbgg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhengqikj.top/Article/details/gtiptgejbs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gtxtjyflzk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gtqhpfhmlf.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gtphrdclcn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gthnckehvp.html

[U04] Py：变量调试打印
来源：http://dali.chenlongwang.top/Article/details/gtnegppsoa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtqkvkghca.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtfnirrfsl.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtavienskc.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gttnfnqjlt.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gtzmokpcjm.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtugqmmohq.html

{v: k for k, v in d.items()}
来源：http://dali.sweek.top/Article/details/gtucxvwyvu.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtjrsyojli.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzljaqcpa.html

[U09] Py：字典取最大值的键
来源：http://dali.cdnleiting.top/Article/details/gtyioezumf.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gtuekkpkzu.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtvqrthiiq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gtekzabirc.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtmbaapy.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtmpccvfol.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gtgnxajyqs.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gtsiytdezg.html

[U13] Py：固定长度队列
来源：http://dali.aibaodan.cn/Article/details/gtkxrcoika.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtvgemqtfl.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaufykyls.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtfpqdndlo.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtnqibujtt.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gtomdqryez.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtpcfoskvn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gthkdrhlvy.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gtrspfdvtk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtlbiuwbxd.html

[U18] Py：预编译正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbizmhreo.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcxoduvc.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtdoplusby.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gtgngzgsty.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gteyrrnoop.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtbeoblipm.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtpprlrxmt.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gtbokxcwzb.html

[U22] Py：矩阵转置
来源：http://dali.chenzaomai.com/Article/details/gteagumsnk.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gtjirouefh.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gtegwlaxgy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guannengcc.top/Article/details/gtatmrpvuj.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gtbiogwzhs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtilsilpmf.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gtphmwasbc.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtdpcwhlre.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gtomxypato.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gtagpttyjr.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gtfqvgczad.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtrchzcrgq.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtvckiwwry.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtdufevqsx.html

[U29] Py：属性校验
来源：http://dali.pengpengdd.cyou/Article/details/gtrqozmfjs.html

@property 与 @x.setter 配合
来源：http://dali.sysykeji.top/Article/details/gtvrsmryxf.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gtxskgqlhc.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtycynjxrb.html

[U31] Py：单测
来源：http://dali.smart0.xyz/Article/details/gtznfwgcai.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gthyitzwhz.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gthdnpfdrk.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gtwyrjqpda.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gtobuatfzx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gtjneucpzh.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gtzyonkhiu.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnobvylqz.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gtvvfysqqi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gtrfmmznwz.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtodbwzumq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtmlngwpyb.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gtiqyvjxbk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gttydwfzqj.html

[U38] Py：获取脚本所在目录
来源：http://dali.shuidangran.top/Article/details/gtsholfxok.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gtkxmenzbp.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxnhpyxd.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gtagehuzlq.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtyibrtaue.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtexvoyuco.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtifkbtwsa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xylfe.cn/Article/details/gtsbfewndg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gtrfhhatjx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtkpujtlkq.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtzgqdzwum.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gtfelrjctf.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gttnwlsziw.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtukukvmjd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gtexaupbjg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtkwgbnuoy.html

[U46] PHP：可空类型
来源：http://dali.xinyue.icu/Article/details/gtbehtbzvx.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gtkrlxowtj.html

[U47] PHP：联合类型
来源：http://dali.tianlin.xyz/Article/details/gtqbnazxkr.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gtfsvvrfvk.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gtweoktjar.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gtjutdsxip.html

[U49] PHP：只读属性
来源：http://dali.jlsjyb.cn/Article/details/gtacwqkmfx.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gtlbgzocut.html

[U50] PHP：构造器属性提升
来源：http://dali.gaohongyu789.top/Article/details/gtxupadyvt.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gtzqethezv.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtlsotyasx.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gtngxfjqac.html

[U52] PHP：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtwccrgjdm.html

$double = fn($x) => $x * 2;
来源：http://dali.guowangkeji.top/Article/details/gttjvpatvl.html

[U53] PHP：空合并运算符
来源：http://dali.wangshuangyany.cn/Article/details/gtqyeoqwbl.html

$v = $a ?? $b ?? "default";
来源：http://dali.shzxlz.cn/Article/details/gtmgifpahc.html

[U54] PHP：空安全调用
来源：http://dali.fengsongda.top/Article/details/gtynysfanu.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gtptpfwhbl.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbiqizek.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtaiqefsqn.html

[U56] PHP：命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtxoqnyjqr.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtjrsoeqge.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtoqetrdvy.html

"值: {$a}"
来源：http://dali.nanxinkj.top/Article/details/gtvlwwfzed.html

[U58] PHP：数组三件套
来源：http://dali.jyoumei.cn/Article/details/gtawaisrhp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtovxgwilx.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gtoysxfoyt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtgtycknql.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258888.top/Article/details/gtyqdennxq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gttgcraxod.html

[U61] PHP：正则
来源：http://dali.tanke756.top/Article/details/gtsklceuvv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtfcavcmqd.html

[U62] PHP：日期对象
来源：http://dali.hysaishi.cn/Article/details/gtbjeanixl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gtjtuwcalh.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gtwcxhgnms.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtvkleaszn.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gtstjpfzpo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gaohongyu789.top/Article/details/gtjdpgwcsx.html

[U65] PHP：会话
来源：http://dali.xuanzx.com/Article/details/gtcjtzsbiu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtejorgtys.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gtnpkndonc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gtggutpkxo.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gtkxkabrdo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhoulong.xyz/Article/details/gtkzgsljbu.html

[U68] PHP：PDO 连接
来源：http://dali.havefunace.top/Article/details/gtuwyjwoqj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pengpengdd.cyou/Article/details/gtcuqtoaxv.html

[U69] PHP：PDO 预处理
来源：http://dali.yuanzhike.top/Article/details/gtklpjvwfx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.vqdsnc.cn/Article/details/gtcindstxh.html

[U70] PHP：PDO 事务
来源：http://dali.meibo888.top/Article/details/gtfrrzzpks.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gotoacloud.top/Article/details/gtcisgibhw.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gtjtjycibl.html

throw new RuntimeException("失败", 500);
来源：http://dali.cashguo.top/Article/details/gtlkbacsus.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtpancjzpo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gtlhstjdix.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtxjpfwzol.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gtuizionvc.html

[U74] PHP：读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtdbfqxfya.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zycfv.cn/Article/details/gtjsktgnww.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gthwsgvxyq.html

composer require psr/container
来源：http://dali.yonumen.top/Article/details/gtlvimhhea.html

[U76] PHP：简单路由
来源：http://dali.dashuyun.cn/Article/details/gtscpjayof.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gtupxuxmem.html

[U77] PHP：模板渲染
来源：http://dali.pengpengdd.cyou/Article/details/gtoxouykmh.html

composer require twig/twig
来源：http://dali.cheryme.top/Article/details/gtdlrltmmz.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gtwllvzegq.html

composer require --dev phpunit/phpunit
来源：http://dali.jyoumei.cn/Article/details/gtzzrjfqsx.html

[U79] PHP：静态分析
来源：http://dali.jianghu66.top/Article/details/gtdmvrptjm.html

composer require --dev phpstan/phpstan
来源：http://dali.daria6918.cn/Article/details/gtgwcvewoy.html

[U80] PHP：代码规范修复
来源：http://dali.tian-w.cn/Article/details/gtmegmdsoi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guowangkeji.top/Article/details/gtyijtuvzd.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gtzkvsqkcj.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gtudrwysbm.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtsxoodimp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloobojgf.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gtbbdqydbw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gtjxunsrde.html

[U84] JS：CommonJS 写法
来源：http://dali.feifeiyinyue.top/Article/details/gtvzrpsmem.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258888.top/Article/details/gtnlvhnazn.html

[U85] JS：可选链
来源：http://dali.0kj1m.cn/Article/details/gtjqsnwepn.html

a?.b?.c
来源：http://dali.chenjidiqi.icu/Article/details/gtjfbrxqwq.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtcbvemkbg.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtqnkpcivc.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gthmzzeomy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gtfmttyjwr.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gtdjnzatpy.html

{ ...a, ...b }
来源：http://dali.wangshuangyany.cn/Article/details/gtmxemkvcw.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvozdbymb.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtxyhlfdmn.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gtzpegexgn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtlrytqxhy.html

[U91] JS：对象键值遍历
来源：http://dali.svipenyu.cn/Article/details/gtmcqymbcc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtbhwvfbpx.html

[U92] JS：深拷贝
来源：http://dali.0kj1m.cn/Article/details/gtvfyqvzje.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlocdjrtl.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtwbjuocst.html

`共 ${n} 条`
来源：http://dali.svipenyu.cn/Article/details/gtelecyvci.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtlyehikpb.html

const double = x => x * 2;
来源：http://dali.redwolf501.top/Article/details/gtycbcoyue.html

[U95] JS：Promise 包装
来源：http://dali.jinqigfzy.top/Article/details/gtnkxdqgmv.html

new Promise((resolve, reject) => {})
来源：http://dali.meibo888.top/Article/details/gttpovezco.html

[U96] JS：async/await 与异常
来源：http://dali.shangyingyoupin.top/Article/details/gttmctoqcg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtasrtopok.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gtbbuzhppf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtyvthnmfd.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gtgqjprpos.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258888.top/Article/details/gtewesuqzu.html

[U99] JS：事件监听
来源：http://dali.ehwqpu.com/Article/details/gtusmwcnmz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gtljfetucx.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gtgcydknvu.html

document.querySelector(".item")
来源：http://dali.gotoacloud.top/Article/details/gtlpswdntb.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gtdecypiwr.html

el.classList.toggle("active")
来源：http://dali.yangfankeji.com/Article/details/gtvkpxcdfv.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gtnqdqtdkr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gtfjlvhuwq.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtyqtftokv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtdrexekfr.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gtapjgkwfh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfqpifrx.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gtfazpezdd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.mhx1999.top/Article/details/gtsylqqoav.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gtidmzasgh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gtnmrhguws.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gturdboxzr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtyttmhjgn.html

[U108] JS：随机整数
来源：http://dali.c1oappe.top/Article/details/gtzpvqgtfj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.birdmap.top/Article/details/gtlxmmialv.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtrukpndsm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtheewqtus.html

[U110] JS：数组分块
来源：http://dali.haohaochexian.top/Article/details/gtkogxdrag.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gtovxtonjq.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtrabtrniw.html

new Map(Object.entries(obj))
来源：http://dali.hysaishi.cn/Article/details/gtbmmzcxvh.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gtqnncevic.html

"7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtcowniods.html

[U113] JS：正则替换全部
来源：http://dali.jqgfzy.top/Article/details/gthkhuzkus.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtxpyoiidn.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gtezzsogjk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtbuyqcrqe.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewbodtnv.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtzfmgsikr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gtyerbydlk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdaoyabnc.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtpsbwdwqq.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtmdlbdjuq.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gteeqkqhha.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtifgypcpj.html

[U119] JS：生产构建
来源：http://dali.gzhubu.top/Article/details/gtjdnjptib.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtdfbecwaw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvesygze.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gtbqofttnw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfglyjibf.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtgqjpghnn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjinywjnp.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtsmwwpujq.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtdxnvxiti.html

PHP ............ 252
来源：http://dali.yangfankeji.com/Article/details/gtnsetmtis.html

JavaScript ..... 252
来源：http://dali.0kj1m.cn/Article/details/gtmuzqsbra.html

TypeScript ..... 212
来源：http://dali.xuetiantiany.cn/Article/details/gthmtqnvqx.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtkkrogvpg.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtssoczaca.html

Ruby ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpcltiip.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtdajugqov.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gtmgpllxzw.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtffedwbfs.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gtxjfsqala.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzybdyhxk.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gtjaeonmeh.html

Swift .......... 15
来源：http://dali.fzhhl.top/Article/details/gtpzisiqil.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gtcjeqlgxv.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gtbrufudaw.html


<!-- 参考信息 -->