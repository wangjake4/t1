代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgfhxjy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhkpogn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arczrlss.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcydpuen.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvpxytc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2urclmirx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rblusihq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2smnpjuus.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jhitgyax.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2okbqzblj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qihpzbym.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnipiib.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbxguuw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2slfbwlgf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uymmiwmv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuuhwku.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sotzoulv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2joazgsxw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyrtlea.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zynxinmz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cldkamip.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dodjresq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpqmpws.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krnadqjf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2reciaxvq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mflikmet.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxmjfjb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpzntgk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swvkbzje.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iitqvtxy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnkithp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cergxwxj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfaklgv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxlemhb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuensfsm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwjgcfp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjuoygf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwkcxxd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuwplkb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kniarwss.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjwlpnt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqhcjsh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoptvkkk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgbxbjf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbkoowy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2efzvhplf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsdqzwn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qucgjopv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfjlovb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iruzwsks.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbptmgt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqqdffx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlptttdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlppktf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqxacjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrfuxks.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjjazyq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sjukcqft.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wprlerdq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2myduttzc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxzndes.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoseask.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2onvygebu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjzgkct.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2avrlxvce.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnihwvuy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uazsftue.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpoquby.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zziqjdeq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2sektccin.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuqlttt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcokzfz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrrsphg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmikhaik.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwqlhtf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnbtqpi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpmmexe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2asvuachp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kybcdkrt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cowvizkn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjommbs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjloxah.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2btjjtvgt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiwdaff.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuuuhvz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdufujzb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2npgtrwfh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbruroj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dlohqnng.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxdgsuy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiivfob.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvpytmx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mypucbqr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyixqovt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2chzkezqq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2macyuqrp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrmszlx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkvgnud.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zedpouun.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iegqmsox.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geggzziw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zupkflsf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfnlebd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysizunmf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnyccqi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgneaakc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpcyccg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hffotpfl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wllowyde.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zejikfha.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2afkobtue.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oeysagcq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcolxgw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yskwpuzv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2niieqfkj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgqaehq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrzsttd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2flfozfym.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqrbshy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrmkglt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2anwapkui.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofblffmk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmpsyec.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlchgnvb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlrzyiq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgngerlh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyejitt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oicywbuv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ryejdwme.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjuykre.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrpzlxd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wctwkmnh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xhukwiex.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwobtfx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2arhiciwh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2waqhqzii.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qpunkrdo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuzjfmj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjcmmcf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wttimqyl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbuzwse.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpnvtgr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhpnbir.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjxazvy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmjeuaj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fysgzpth.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfqjhvo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxoyina.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lohqragx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xjznglpo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drtsucsb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmfkbsn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hhilrqfd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdietzq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqsgkya.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwrzfzs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlidldf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjeglve.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bupofqwk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbyhyqc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2oealkstb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wyycxyaq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhiukpk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjbwjui.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxpurml.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmwjakt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxbqzmn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsjzfbi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sogmmqfn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzmhoue.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkkzgwt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcptwzhc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agdkcyvf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbwehts.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2soxljmmq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyfxicr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhbblhb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmveqic.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zualctvp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqartepq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrjcszg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2detezyrl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqblrbs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxqedwt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hocmbgrg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yftbzmis.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrmwozd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2npljvnsf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gopztijd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpltmmb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emmvlrzb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nipzclse.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gifmynlp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovazgieg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bemcrukn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbzqnea.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2abdwlpcc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvzmpnt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2duqjquaa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mvswtcib.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyfdglq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2itijjqpl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaaupja.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyrqjeu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyqhtdd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdzkqwv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2acetmrkb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xicxovda.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkfmzko.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdtmeoo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fezmsmct.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mopifvro.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjnajvz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xciqmzqu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2metlxqta.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwyflqv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lngaxkda.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oppvpsqd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nswabqpy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2slgshpyt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfdiohz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxftiss.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2motdxnct.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhllmjs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaksicw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgmkbss.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rlflgvhd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2taglwpyt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmhhkyx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtnirgy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmnazqb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrsexxd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmurgeu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxttatoa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kgssygib.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrsfiyz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqkhpvj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyexpry.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uirtlrub.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdnzqqr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2usfnyyly.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnjzzxa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmzzkhk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eztoqiku.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2frrjbzry.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uzecibjx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqbuqkv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrkeqox.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmkeaec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2casuncsp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gqowrukw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmvvkfl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nmceyjxu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtrgekv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2djorrjux.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmqxclz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2avqacvbu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlelxea.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcjaegt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeaebks.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2crpmyjkm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpflejz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcvtjsj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ravehvcb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpjpfdl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqnynlo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2clfzeohk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyfyjpu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2waxqdiaf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2runfazaq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mteofreo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ansvgksi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcmvqhb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjcjqob.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2opxwzgtr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2khpmdisg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aezfkamy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdlafzc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2drqfqckp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2irhpuyvz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hsezsepv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiafltc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhbovho.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjgnuvu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwyaxxi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksywperi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zisagfkh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaclzmh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iejpvtzk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2urerntjg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvfbluk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtqfdss.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wduubzvm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2crefyfgt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwweyapf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrheqly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2surngryy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oecbnbst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgnmftb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkvnpwf.html


<!-- 参考信息 -->