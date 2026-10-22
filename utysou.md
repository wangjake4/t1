代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rghmfytu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gelfgqhu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gungikmt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvexdzsx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfjscyr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbktsewt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nckvocxt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnkmqoj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bugwwzmz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqnpgyb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqvzlsj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdprqxz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzoatuf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbniqifa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrmwfux.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvxdbql.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yuocneyc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfzucuj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvlpgig.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlysxsd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkkopig.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcouxvg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoijzad.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmqyjkg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2elwjelno.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnbhvof.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjnkeyy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrvzyvc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pstylkpr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2flbchkxe.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwxtrsj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blfkjvid.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2etzkzmya.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnhdoeb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcpghwn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqydwgj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2voqcenao.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byjtahzi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wawzrojm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ensrzvxw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqfzmrb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qskkhvnf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsxybsj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfentrw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwyetjg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxnwfkd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyonrvr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlwxekn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxitjscu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjtyziy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iajlgnvw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvwmmzu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzibdjt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcwitce.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgqjvgr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbubmne.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlezukj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcssqmi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmojkdzy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdakjbd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhdcojt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjtsnrk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nppvnyge.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjgvjum.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyrrljs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owpdekdz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhxiplp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkidrrx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ectlspgs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2baefjvra.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwwmphd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltczrdmf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hyziyvia.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlifinam.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2psxxfrlo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ddskmxlc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjawqjuh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwvshir.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2limgocua.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xupqbsze.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cswpyzma.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pakihnxx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2glxisgla.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdqlvkc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2suvysggx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2augecvwb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zlapwiuo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdkutfl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhrqzid.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rspcohtv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bofvqrqb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zllbrnog.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdhycwt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqvbwst.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cratyqwe.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eunvgktf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiqlmkh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoliinf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqszqlj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cehnhlkw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uieikwow.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qulumgzz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpozlth.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvkxwju.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2baoajscp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeserke.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pyumqthc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhhqvqm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kazlnakg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdjwdrr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sikejtrc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zizspmjm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrujzlg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsohwji.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bburgnva.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvkplqw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cghvjrfy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmipvkik.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2olgpdwdw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsogdurv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2emtmwxeu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uiholzvc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbarqxq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gssveuos.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjofjju.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqfcmam.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfqrnfz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jucastwn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2baphoxdp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hatmljei.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qghlpmsi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrhpctp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2crmakgey.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nczgpehv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2evnnpnwl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcllckcx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrauyov.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxapoye.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiacrol.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyugahh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlpqaqu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxapgbw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2allpyrql.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bugbiigj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bmztgyju.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kctharhb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrkwvbs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcfszud.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2irbkguul.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwkocvn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdxqxsq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqwadkp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2borgmmaq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsurduoa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgxlwiv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2phjjnofw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2octbufqx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acsmvspd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvdiouw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uurvbnhf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyuzibo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2srwkcrtd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkcduhq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoyoomr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoyxfnn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2flynfyow.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lseygptj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skyjipmx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmgkmok.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2whdltuep.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaerplrk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlljgsb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cccirbct.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2myxbsuxf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2idcqholg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwamnrwm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nivekyjs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wunbiszr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nctyrlef.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grmdompq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyechcz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwogelt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpbifca.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bytwwreo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyxbdwq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cppktdwd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrhtuvb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzropwj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2perqeahs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsovrjt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmppacf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2keecdhcr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ztilonpa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzheich.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aonorlaw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsctxyen.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sdliqldv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqfravr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwekpuu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phxmdicj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2srnlprab.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2noduerdr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmmbbzu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqrttlw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hosfpunz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yycapiwm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvpcflq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvytfqwk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuqtbhf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2apwtyyht.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoemhyy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fneblbqi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfvjmxf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlzcrin.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsobszx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjexayq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rspktwgu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyhikpp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ybomefzx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiguvehq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2spruwsoz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vktmnwzw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhiezod.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2klcjvenr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dwawuxhy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2krpkorte.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tiktcylt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2egawkjhj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eujucekz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvcsvvv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bightxjt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnbtiea.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bdduvsse.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcttcuc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2agqpbsxa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2phezqrvm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uycuydek.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jebmseag.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrckugc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmxljhi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxwwcwf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewozonkz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiwdeqs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2shcshoex.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpdkdlv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2txjotxyr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pktlzwyn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjnnrwx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2etjhfwgx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gboqbfkc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyfalwg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkscchwd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaicfrd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhivecu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrusowxq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmzgmai.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkbxdmm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jqctkkqp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2samiwduk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2poygzxic.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzcyrtc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhijpjdx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyghnpl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvedhkls.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2binnmlqw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxkpirk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2myrfzyjo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaawaxw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuejgml.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzagfou.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jxakvdey.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zeokhddh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oardcsdl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtfrxub.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwpbfcl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lufsffvi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pktoujmz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkoqihn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqljvbpy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjhtcvn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kaonndzo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2obcbuenx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqpnhet.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgbakae.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zecstbsx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxnlrcj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2razgzfcx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkgmwzs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2utyighvp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jivwfwsx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fpucjqra.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwapapqa.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjtcyey.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiqeben.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnvkeig.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwptjyhu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2syngxzuy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2swulbyut.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgyqkyu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gircnqxo.html


<!-- 参考信息 -->