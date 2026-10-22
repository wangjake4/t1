代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2frdzuefw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hduathrq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsqjlro.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsrknxk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxndaiay.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzougej.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqbafih.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnntlgll.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2arwoninb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xiikimtr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkaoxvb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oawkycvd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rwstyhza.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oejugziw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gacwvmav.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqvhatu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xilzuqge.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgskyxbi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2suarodgm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qyryqlim.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2czqehzqg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2odvvtkpt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2amnryjue.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvnnxfk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkcdlnr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfsesrz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iuravmsa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbwkwhm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxredwy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffwglw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lozikcnl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfayino.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kufrmgyg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxlsbeq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dvezjffg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfslzpav.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpaluxb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paiycpba.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zehlxbrd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpghmooa.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cedwejho.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcntzja.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyavylr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtymcou.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eucwvsfm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxikpdk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeeztwu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqlnctb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiyvmtv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfrgsfx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaprsre.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqjonvi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrnnkop.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvfiqci.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2alvpcswx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfipqbu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rslbccwc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlzhdvs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zefwuvvn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdmioac.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqjtlxv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awjdptem.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtrglnz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jcydvbpe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnlkuzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzlgyke.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrdxypf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dydgsxha.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nfakfgtk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2orocviuw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxggnai.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhirlezt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eumjqrkr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxfqfuh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsyvbai.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2duhoarbz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2venwsfdu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzkjvnw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bewqoene.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2abxxtoxr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaknalp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwbhwpg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nftrrttv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwhzoat.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hysbnlez.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmumnvj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2whsqbahb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fabsglkk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2obmuubqb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfiszqo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vboppukw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2djiwycmc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2euevzhyx.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozojslkm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsmllnf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdprrhp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2evhgrjpm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjeadme.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqlnjaj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxxghxh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hbevedhp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphiohlm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2perbpbvj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkczood.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2teqcfmqb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfauwoua.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxsyxae.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jumzzcqn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ismgfuxe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqecvij.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrobism.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmtowep.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wawrtbgs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwhedai.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2intmrsnr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtotwrvk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcwenjf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmgtmyi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhfuxry.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2miquarcb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uzapgmen.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrxpdqw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfzouvx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuvjrze.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2roivesls.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xunbghoi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2izmswahe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkqifbf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pledlvjw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmvlvev.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dbplsitn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdbrsmn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2onmmlobu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhlvkub.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2trxgxkbj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibkqrii.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrwkjxw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedzuudy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoqwqkh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiavqedd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyxrbcg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fswtdtuv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sglbgtrf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iskhqxkk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmcijoz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeyfhgc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2otttvcmp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdfsoqb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2duunsouh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rwolwpek.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxwxcjg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2auydpjkj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcolycm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmziagiq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pknsflkv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhwoois.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgxxxio.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqyjfwm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2psutklia.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsmmqjr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ludvalah.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvhnjat.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uvavbkaf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyjaqxu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qkifuoma.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2imlcnxfc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlgncwc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urkdqkpi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtlhugu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyctqck.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fotkcvgf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnofmbi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvwvmnx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgwcpun.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvwdhur.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntplfgie.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiqcuhk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbhxumh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uancwtqr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2smkmkpzj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsllwrtx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfffgtr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbabfam.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2phkhubtg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvajqmb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwoowpx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hijqzdyy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2edvbdipc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xirhwitl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnelbmsw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2chaekcxr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvicbrzh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxznqyj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bequngqi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pgblyned.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nldtnvjm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkniekt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiesmas.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuuvkws.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrxmiom.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aybkguqu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlznmhkr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyzwrjo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdeqiyp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvqscos.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaxords.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkepcgq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnykrnxr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pheourit.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyevqtav.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2swtksyrt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2garvtase.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zewzqxlj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlmcgsb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsypuhe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rawlrbyu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfwdzwa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlmycho.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2omhaudkg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsarfbss.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yomhlwln.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmngsdr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkwhwgz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qhizacia.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yoodlfbt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uryelfaz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlrlrpv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ehscrplz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuwvxug.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbnrxew.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hjobmany.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbhammz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoysgjg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2utasxmum.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vshtacqb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2snwmvmyy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwaiwvm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nydzymyd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtxmqdx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwewymxj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybawunfq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnptnbqi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlwtenx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgjgfnz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eiitztny.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2flfbpash.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpfegfp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzkppvr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtplfiy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2noqgwqkb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2txjimoqe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvojzlt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2klshcaxe.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2neofzatu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znjxhgza.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sverhhjh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxqbjgu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ltandobv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2alyfoqhm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2negucrxr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxpmrkv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvckjbie.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeyqsuk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2csffaqoy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqleyrs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjlxqyr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uatxwkhi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnsjbqh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twukydsn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2thnimcsy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nwehtrxk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qowjnuek.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvukbzz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2enuxdooo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwazwjf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izltpeqe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuhtlpe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2etaxcmwo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgnjpfh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxylcsm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nsahvyca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzfdkbj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeytmjm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jigcieiz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kyknoyir.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkafddpw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnbiurj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgoeyze.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eelsaade.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hweavsuw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwwmkhp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjhksin.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzxtrao.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcywkch.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhsdkqe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iicdjews.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2khwiqplg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2erfegnza.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsahmylh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idgaucio.html


<!-- 参考信息 -->