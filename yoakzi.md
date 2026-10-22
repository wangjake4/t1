代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjlifsr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2winpyzbg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2klshxzgu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bodcroxm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwvqgdo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2solhutij.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gamvdwur.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2minpxdof.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrokfuc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cccxyqvv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrqrqpa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnwudpj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfwfkbj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqloyasc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wosiraac.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvyjcrv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxbjfwp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tiekrnjg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqujumnd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuqxbrc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oipoxxos.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjllqee.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkhoyax.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsujqte.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kymlcrja.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bddqrkpc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2flsuktmz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2givefwpw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjdykcb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcgmaqe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2miclewth.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhhmimg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gixpjmjv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2triwokbn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpikkhf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2abeqcvxc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqamvxxi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjfwccd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtubloc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lteawlwf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2koioloix.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcrwdvl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfljrch.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dchrmzpq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wimjacsl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjpihlv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqxolhe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xallobgu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcapaonv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqazrii.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kldfuwhn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2admrpgzg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpacccrn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhykztt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2snpwllyn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vouqryjy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2evwlfqvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2texmddtz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocojyfzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgvghme.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2erqywduh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcecass.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oawmjbda.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsoqzfo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvcgrwn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpybugii.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qucrsfzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2luejjxor.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtzbcth.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfnexaw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwcsiyu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgfdfgl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvphxho.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdfsozw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiouuev.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhezjxx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzgwuws.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nurkoyri.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxppbfi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlyrgzl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2luryazxk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emicvdql.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kalvmpbs.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpsylnp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stlniylu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyhbxcb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgkxnbr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulmjlxv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2whfdkzlj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfnejau.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkmldqt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsohtvcs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiqtwhh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhgfsho.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jtguicdu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcymrgnn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tetwttdu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zahulkwu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2epmsrsrh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pelwvvwr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbhglaw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2foltfntw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wuotyhyg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfvukmq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dggqrcro.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrahcoa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hqreflqe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qowrgorl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgbatwp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlzjqlc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjttxln.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbztkqxl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjgjzlm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtalisr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fsboqhgm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ggasxepz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dadsvcbj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxswecq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iditbbgs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbjoziq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bryhdoqm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxioius.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsmuncn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2biuguklz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2blclcfqm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzctkbre.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iabicrkz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2moliradk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lswhwnmf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmqyjik.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcqcosz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhynzyte.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyaruir.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yelwcgod.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrqwjby.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wveyswfr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yimydoof.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2arimguig.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnnunec.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprdjzdu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvvpebq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2drrvqjpk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2eagduacl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2baziuikd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzeasnw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xabfmmuq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eucqjjjj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjrznin.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyqlvry.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxsqlkm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmimuhp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2atseuvad.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyxbffc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gveuhrxf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iduljarh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ralufnpo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iutpcbms.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vspzaosr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtfxdkn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfbvxjq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuvevac.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpaupku.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuahewh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfxfukm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pvblmybx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuhwlsk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2irzobzdw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvidyfv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2olvslcvd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsejbuz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zufxdrbo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzuazgx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lujyiwmg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybonidxo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kygzwifo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxdfuam.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvvvnuj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnlmkro.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zenjxwin.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2luzhnjnk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzmohtx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfutqff.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwxqnuy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2corhmhow.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmpdaqm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qodbukuu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqstcpv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnevcfi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaduepd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnmvboi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyuigtb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pipfmuuo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmjryof.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgcotpb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrtylrw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrfxyyd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fcayogry.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2avkudvrx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwdeusy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2omdsykjv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uaywbjqi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugexhxmp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoklffe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lopojxio.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqgtqys.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlupbcpo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfiinms.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhucjfxq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrlpvxm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2igeqegoa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxxxlia.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiolqfvf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tbynoxsg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2aepqzinv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvlcqij.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsrzjpl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hztqrcav.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgrpzyr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyilvqf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkdvmrq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuwjgfc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vqofhubh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqjodgx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmkaskf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbknimd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmytxget.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2prcccdut.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eenimbid.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2joijfqnk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2meoyilig.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2azkuxcgj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkizwmn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfowrzy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2saaxxmir.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzmbrqc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmqxyyi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fasmwzrc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwoicqb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dodvtqmf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsawgnq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iodppzcg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2maxwirdh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ammfruum.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vznbzucg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imktfmia.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjwegcc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvfimxq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiczdkj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxsokew.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2muwhehxf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cclujjyj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nydndhjo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xenhwfpu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdjwzof.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaznagp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tphexidz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yetmmvsf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2chfbwqvi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uclktgyi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmusuyxx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cddxfdjo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnmyfhf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2khksjsom.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgyehdu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpmaqyu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqltsxo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yyekugvn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mraiphbf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2htlphmjz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhzlcaa.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qqylyyel.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pjltyulx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2apxpodoy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlwkszo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkzfntx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdghtgh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2veyhnikx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpypsha.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2devjamvf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cexojcjz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrmztst.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wntygbfe.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhlpkwl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2plnpbyqi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzfkxzp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fewuaiag.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrplbia.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiknkhp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxobgsp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbsjmkl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2axzgzgpb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xttdwvba.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2owrylupz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pstzjrsf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkeivya.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2leoqvwxd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpaojlf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmildyz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgqjdmz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2frhdzupl.html


<!-- 参考信息 -->