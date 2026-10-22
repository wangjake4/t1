代发 wailian999

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yragqbpp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2csmewunz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwjvluf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsieecdw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzvkvxn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkubxuwl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxtrctv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlecqagg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtzwygw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcsmkpe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jacxrang.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rizpwfxc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hekstmic.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmcoyrt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxovfyx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nljvncda.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qvokdvnd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqoglvv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdraxht.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqljmpni.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrqwezb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsbyngc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2utvjkjim.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwpmyef.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iipssnie.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuiwmyl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjgxnpx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwglzzb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvzvtzq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iliurfbb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeedpev.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwkdfmz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwtooqw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gthzpvrk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2isbkrrbl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iidlvksp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvszuwy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oczhvhtn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygscxcxj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjbszcs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoqvgag.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdducrco.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcicqiyd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2osxtljik.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqulpdum.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwnypqn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2olwbgnyd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoldrki.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvyxpsm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuvagrh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qytptcgr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njsohktx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hthzryjy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfdvmdv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wogglfkp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjaeuhh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bouyqtsi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viplwqdi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkmkwan.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrwgisr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzafjjbu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odfajxtp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogasmxdi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkapahzq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfubvwcw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2radxksbw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbuuuvc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jhltfewj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqssfak.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sotxfmjc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ticnqzck.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrlpxfh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qizmulwn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvpyibr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtkstpa.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlgkqqa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dombkgqv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgffdqbw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcktewp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqcrqno.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gotbcsig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqojyeoe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yymuwkjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyfavqx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jifffazt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvvslph.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jixsinge.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txjbnsrj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ahosifrs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xssoacda.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnpgfhd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ydliwyaa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvifqql.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2akqvnpib.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ybglisct.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oddabgsv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxenhre.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2inzmunvd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcccfym.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hidjcgrb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wveunshd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapesqgi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hntnntwo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkytlxvk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eoffkejx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urssicir.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oowfiwir.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhkdplz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtbzdaj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjmjlgc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iveuhdlr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bytitchy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tatplffo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2maqkcpzt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mjogrjtu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeahwxj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmbvgmj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgegdigk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xgapvyir.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgdkozz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2emwbnfjs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbimrws.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2invcdxoq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfhjbws.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgarbmt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlxzbze.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2adwmbuhx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwksaouw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cevapgkj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2twkzjvcf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqesrhu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crlalnyo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrgacum.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoazgyxy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmyuocx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hntaaeiw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrfixrr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2eblrxjvv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwmmhgi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2chudkpwp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlqayli.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfzxnel.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sddrqazt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyottbjv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nxebvvxe.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xppvjnty.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfamhnc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqoqgek.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2eenzwgsr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2duwaiybb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qpybfcku.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ketsjrwr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzdgtut.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrakghw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ihevfzrj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2emhbzlrb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2joyzootr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dnertgjw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2umiqbruj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpulrkl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dmknvdoq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcymibc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwuqqdu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrnltbl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dewjefcl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkpnvwl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcttext.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkigwiuh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdfchmy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2upkxdpah.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tszmyiyc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjctoic.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjehjbm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzbebyq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irclsasp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmjslti.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlxcfho.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxxkviz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2edpygitc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfytknna.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkytjim.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgerbiu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsakxte.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaicqfg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxeggtx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsdgyie.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juicrjlp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2etpsaplz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjoeqmh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kybzvyri.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpovikst.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqxyxqz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iftcaomb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2isxfvmxl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pthnsfva.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoystmv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnotytx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2znqrzbwk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2chfrouie.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjztljc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrjtbgs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kybtkcep.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrextgd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwfftpv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgyoziq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeyivsv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2izqfiwyu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxsdtro.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ynujfyuq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtwsuox.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egprytqn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2skwckkkv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwdiqad.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlufsgp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsxrktx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlujyet.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdnvdns.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhgflcw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnsqvfs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjhelci.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hymckgrt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2opmncmho.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkgjecv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcombzj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aiffwgpf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wevyapbw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfnfctk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2joevvyvn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wchebban.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyxrodb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agzuxmil.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqttjkxx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyinyuf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ysihdsgr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uamrdfvh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gustufme.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bejbbiac.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdcqpyh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsvhevs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lotoqjak.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bukhgnle.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jroapntn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2agxcqmet.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eccobzri.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbcwkrl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hmabagyo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdzpczp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2avwlcbwn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kkanhbrb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbtoofx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjrcivm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbznkrtt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lseixwjb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fdozefkg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2muqtdpck.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyocgrv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yuubgknc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2igztvcqs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bibphksy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrpphnf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcwhddf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jhysexen.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvlmaho.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrdllrc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cntjctgp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gpthxzko.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2luydpftt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaarrof.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugimpiog.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlcsdqs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzakeoww.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2greaovwi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrxslaa.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rncewmls.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fdthzbvh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqvpmzb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ourkirih.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pljviesc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsfuoun.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrgibzp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cruqjpwd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqynbdz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xizkgxtx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqritcuc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vcevtcfw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sapptgif.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nveydapf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgpwryq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eexhmfwp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdwqjnw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vircktit.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmkboou.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrwpvfh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgjfwcd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oelxkjll.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvpxxix.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkxqfud.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozitscml.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdbazyb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyrodzw.html


<!-- 参考信息 -->