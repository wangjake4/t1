代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xvedngjw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xojtmkea.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdmuufd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyzmdvs.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzppfat.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ammehvon.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pygyhdhe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqrhvjj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jawdebpt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2scpgmrat.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afeiwpyg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbpdums.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxwxewt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgbiwji.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mffmuxnu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsfkeji.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fsruheol.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwblahdh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2szidfwuk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gldbjzpt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkyycnu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnnfyxl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbiwpdm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyywdfjr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjbdhar.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prcozsmz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvxjtda.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2umioynzj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhhtdxj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svlsoffl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2duajtnxu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmftmvh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xuizqety.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2couyxtng.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfysfmag.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtjcwui.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdmuaff.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ugezzgac.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthzkjrp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qpesrclf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sugtiqoj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uurrkyzn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymizfwnk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bqasjwea.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2twvudlvk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlsaegg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2syxiaiai.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaagglc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmqsdxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oorcsmsb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnzbobj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syvfqqfs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdfoivu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvaykin.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qiksibpy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fykvmmkt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsrpsbg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bipxkswf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyffmgu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kaouvpjb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvniwlvb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqgtkhw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iacfdmho.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rllbnxsa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lshwnpbv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgrmjgd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbduhuf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2apwvaysi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyilffs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kewxtxii.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqosoab.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlwyxzr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2epgvrphi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqnfdsb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lomujxtk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2takhrsrx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvqisor.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyfgmqu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdhiszw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxkthgj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbczgoq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dplythci.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvhdues.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2phmafrra.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnomwkn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2puvytrra.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyzclro.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2omzqoxhg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2floaruaq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jycocqvo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gwauqxbv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrimicxm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vzukwexp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhkuyoo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zenyyqzy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2smfqfkvv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgyuhzl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmnuycx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2doqzcgbh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhdoyvk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qagzzdqk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwhkfjg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2poqpkltp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsxklfu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sewnwpes.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdfdiqh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxlqwoz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2trvpskna.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoawxkg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwvjzhn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2spxpgntp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2emgsqzle.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xeejdjtx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2toovpphp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cghygfux.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwqtcrm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2osygyzip.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcobyhw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sclloplh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2odtdmbzs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lztnniou.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbepltw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mypgxdth.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndetneuy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ezosiftt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxnchsq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2owcmmsqk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iizewjqd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qahxsrjs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2phoakmpe.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kzckarxg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiivbpd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlnfluy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyqtmjd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cljgnhtu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oijhvqku.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2obgfkdre.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2evgtayrt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frlmxebj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtwjvpy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfwlyyr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqhoppe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjdshrh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yryteqmx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsgwgik.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpauarh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vftrraub.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vquoczra.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gydwuavk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pubcisko.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xoueatrl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvbufjg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvshspk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2suzndzmx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xadeckvq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2osdydtup.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gueyydfo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkhgpxu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcbsxxk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruscjluq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkpoglu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2owrneqkb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fihijuhr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwvffjq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czjwrpnm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxblqxxp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2czvzcrlk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyatavrk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaeplpc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qniixhaz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2clfnsphe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaiuwoh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwxcxnv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2caxnynha.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdislhe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2crtfbzzg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2flhsgdyk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bihqhnvu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdlblnh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2expmxksd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2prskbfjc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hziyoesw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bcohkydv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsecvbou.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aubjzvaz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdqlhij.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqemjbo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuuubxv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ssttgcrs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjokywp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxygezw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mozfiwtu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uchgbygc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gucjudzx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzyfrot.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ruideliu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmtzabb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2raykuwue.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vclgwvtb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuvawko.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwihsgb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaiznyc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mksfqqrl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrclfktq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2izwanphn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2klyobnph.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvhmhzi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyycklw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sawvdzjo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqyoodx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmummnl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjnjkfs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhbfcco.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuhxill.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxfpatc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxdlzjl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcjaaru.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjekvic.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaqxbcs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvuzadp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqthglw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdwrqlk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcpdmki.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ccawhepq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2srpzoxng.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlavdirs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2itopwjgq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eheklwkm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2azbscjht.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2siziftzm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fxukdsbp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvaezkv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2djghxkho.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuyhqiw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpxsguh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsohdisr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzdbnlf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwqatfv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpihzca.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhmjvjx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xlusnqep.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rostvavs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxuegee.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbyivnw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmcjhxd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgeztkr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzhiavc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgmjykg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtyxlyw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrsehbt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyjwdug.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfviqfl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwdbqbv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsanchae.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qbymwkgo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrgqndn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hghypbrc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwmijsv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qxurfjrp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcngxtk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pulpalnk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnpqnax.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2swywtgzb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wphtqngt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpvdtyi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lobpyjwt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzmxblx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dupcqtqg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhdgvkw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgxkkep.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rjucgjer.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rmppqddl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2igvigosu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfprkjfu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoqpzjb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2odmhotvu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqunbzx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpvojsg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpigjku.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrhazjl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxokigh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcwxawa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfielif.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efcyjmqj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfppowu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcxbfnt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyyyiga.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzjyamh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdfivhm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxzspil.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsfylim.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2foekndkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmkdthe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aroerule.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqstjib.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpdgsfu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdwwrho.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2enwmetbj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsvavty.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjerknl.html


<!-- 参考信息 -->