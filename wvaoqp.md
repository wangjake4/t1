代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcivzni.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2whemvzbf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ramfcgfx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrqlzkl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eevvzlxc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvfpznp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzhqccm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2seuodsnr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2egsdjrgn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmeicbq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgogkev.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2khewflcg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2puhxryxu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcszxuz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uizunigp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyluazu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnjgqiq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2omwzjawh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcfnugq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxztjwq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2whlqeesk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pgubjxoz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nncvscal.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnrjbbq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdhufqm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpxjtwg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrhstdt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbxltcs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ialbpqpb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijklnmgv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvvswsn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsxxsym.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmejnoa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkrodwk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2etlpplys.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ighpjmgw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2irwaxsps.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbntnksl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2joumvyvu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaraesi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2omxawhsl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnsbzui.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrwaehn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzppbli.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzjgajc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vifsqxqr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2odajojvv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvciraq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwuwokc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwkaans.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvqvrka.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2toeabeln.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eazvdvoa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwaorab.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqlddjz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ostqjxqu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnawlyxe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeqkmsf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdxshtk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaeymfu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcdzhfh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvkdmtj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2drbznppe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdsdyoh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evratrpq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdzawfw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrsraxq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrvaxlc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycybpysv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmlxbhu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jofgkwil.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2onwkkbar.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtnknra.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hnymfbbt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oktwdakr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhgsjkt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cormuhkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyvupel.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcqzevf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqewlnvn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ckecxsvy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvwisld.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjhveyd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xiulrbkv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbygvsx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrqjprq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2oayqslty.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwgetul.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqzifst.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oewxiwdt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpijual.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzhdrzg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkvjzgj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2knasoamz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsvqmdx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjkpcqi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iildmgiv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2evpnwsuf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ynigdrak.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvofrir.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sisgdnkv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkobkqk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlbxgbc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2udzhabkd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lipvvkjv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2smwpfhyg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqyulli.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sukzmsua.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpilnpr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpehqsn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ihahhyqw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwteuyv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xxopozyx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfjcsdg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bampuoff.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwcppgw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvapekm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iamfsztu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfmfsdp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoqtbfy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nplsakqc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzxepuy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wpykixpa.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mndlitgn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjgsmwk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gvomvwrr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdwirox.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2psrbvcrh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cypjbskt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouenwfuc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pyphngus.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlwvjbl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hbivmvet.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgevako.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2husyvymi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pycbjxzm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2emcorlui.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhljbtz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2udslerxq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoegowl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zuomvqps.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdhjviu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjrdbtn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mvevwjna.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyvxtxz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxggvao.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxczjmwk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2erbmytub.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2evntgeiz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kotvnony.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsjbwoq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2siqweecu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qheaxhsi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcaqxnp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bslzfxac.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtzdsts.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqtqybs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2asuaglao.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2naofdwop.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeruvva.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwnfudm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2evfjkfpo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dqurlbvz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvroffje.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2igurlcbb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswfbxyw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfwahtj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2txdhhbuw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uezserjz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omyinsjw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhzvkof.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiceoli.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnjcjfk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pskxifjz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ssetcrot.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdlvput.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bsusxkwr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2addbwciv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsccbcp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmfegpc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsswwyd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzxxoqu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfbdylc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnjvcjn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2spkimcfz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyskgta.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxxpqrr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkglrul.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bngdkamy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxlxixc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2deuqazcc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgyfsmf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zchvisnl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwotiqaf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfpkool.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkurmdl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fyufyonb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2koztgbbx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkghldn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2goekutpn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2quvstece.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxjipru.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwwcouq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jihvxrgq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqqkryg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkomrfxj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpeztah.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnzghox.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyaawmj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcryhsx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnblooo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2thiuuzpf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2joitgosb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgduzfl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfemhid.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmfbcgn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2twbcjbre.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfialkt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rruewzid.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2foifutbt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoyzodz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aelgdklv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnllnkp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2adhsxutz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qahhnpay.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrhukox.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvilst.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbjzwbk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmdrbcu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgnxwtw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kelvvjus.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzcpeoc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnarlen.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2doksclrn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfbaphe.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2japxwhaf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdpqbgt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2malqlhfu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2msklipvq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjioaka.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cabniblh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqhmdiw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tglsxfck.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbowzado.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbmfvju.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2odrrhrhd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqcidog.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiojddx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvazbsa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2colchjxu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbgylpb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2smmiqgjd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2teidbnwt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2froeahhe.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2smqsnmic.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdshrug.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lljeomgk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vibfmtgl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvnvejr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaawqqfu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsxqtam.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gfakilqx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgswqhs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nofgrswg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgmayqk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2igkfcdyy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzenfknb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jisnzvji.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjcyqmz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkyutya.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcwtjju.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnlbjyt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oobrfzts.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbudffi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjbphpc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2stydvczb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbglyxv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iblyyiwm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtsdyn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wefmausm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxpdslv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjtbpxx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjjtlha.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2smejgeak.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2udyrqszj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhfdcho.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fypkczma.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwpcnys.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zheflmws.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltysnqic.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xunphrkv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2urpvmpin.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2coymuhao.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjuennc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2viazvfec.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xcttcszi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiweocr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2stajwvua.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tisonnct.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gursppag.html


<!-- 参考信息 -->