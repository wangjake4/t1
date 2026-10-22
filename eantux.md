代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zeulwnzy.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gt2uknhartv.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2dhvtyyzk.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2cbxkjmvq.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gt2bndbkdbn.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gt2fiufdlby.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gt2uoqvyjot.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gt2iypviwjt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2aydjodsi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2worrrosy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2mfveptme.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tczykbqk.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gt2okcebfwg.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2grwvijid.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2ngdskjlj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2owhkkrue.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gt2uivnhgah.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtsurkw.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2yblolken.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gt2hlbedpqc.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2ghaghmyt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gt2ftztxrnk.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzurppzq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2mdbavahb.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gt2mhdwcyyw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2mzvdekrj.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gt2wswrfxwq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbluqqmh.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gt2yoqmqfuu.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gt2gnboyezx.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gt2pnyilpud.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gt2xkxnuved.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gt2rdcthqmm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gt2rhikovjb.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhtmtofj.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2nrvfqcbq.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gt2kqkbidnl.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gt2noqowvxh.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2mdctmnwk.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2yzqoumfg.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gt2ppxdpbbl.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2cfdiumor.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2wilvlbzn.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2mxdvzhcz.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gt2lelctozn.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gt2gztrbkbz.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2rjeinpgf.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gt2rfsjknvd.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gt2otpsuhxk.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gt2chsoaaqh.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gt2ooeeyxwf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gt2ylnbbdmp.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvbqzslr.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gt2sxdabgzb.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gt2cdtvdkwt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2dacotrgk.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2rorhksdf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2spvlbdpb.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wljyzsjt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2zphvgfep.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gt2iwwnbajq.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gt2sipupclt.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gt2exvqbhle.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gt2drbcdfkg.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gt2oplwacnm.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gt2kdkqmqta.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2hmsgcbvk.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gt2ioulghay.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbjibvve.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gt2mjsxdsct.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gt2sihznrbk.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkvwmask.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2yxwetyvz.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2nctggluu.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2fyhbzypy.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gt2khmqiluo.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gt2vzwltzjn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gt2ahpurmpe.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gt2agijzuen.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gt2upsimanp.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gt2vqvjupaa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2jlfnnkla.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gt2grzqnsqa.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2zkbkbghg.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2kozlziko.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gt2lamzzynq.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gt2yyyvcbho.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gt2ozaajmpf.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2ramhgwas.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gt2boeiqcjf.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwbfkznp.html

setmetatable({}, { __index = base })
来源：http://dali.chenzaomai.com/Article/details/gt2fhpfhvoz.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2hpyloxfp.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gt2lezraing.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gt2lzzlkvsc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2eoisjpmc.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2czdwudtd.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gt2ewgrwvvi.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gt2lsnqknih.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gt2wttyeiex.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2ppswyxbo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tpbafpsf.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gt2fkmbyjrl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ebmnfwnt.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gt2qxcfqtrw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gt2kbkhymvd.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gt2zaezerpq.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gt2wasxbjjr.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gt2izngpfwx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2saonekaz.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppufybvt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gt2zszrsitz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwfyibni.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2mhvdxhoq.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2ieyusrkn.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2teadsmtk.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gt2ymvxyqmg.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xteideye.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gt2zhiizjbd.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gt2ncdykecb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2lspzgwjh.html

[T55] Scala：集合过滤
来源：http://dali.ivvv.top/Article/details/gt2ydrvkrzb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gt2quvvcgul.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gt2iqhowrmv.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2yrmdsrld.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2qxvibkng.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gt2bqvuglgq.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gt2gbavbelh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gt2wjweiani.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gt2jnmafzyt.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2yanlmuqk.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gt2radeednx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gt2waatcmmf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2dquanmvr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2blqpmhvz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2qdeiaysv.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2rveucyab.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gt2dsoqeccm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gt2oholtoyw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gt2rlvwepop.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gt2riljqvhd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gt2yiebbfrt.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gt2ycjrcets.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gt2itcmtrpb.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gt2juzwavuz.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2pcatxzov.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gt2scztujez.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gt2lsoqcdxr.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gt2pqkdqokv.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gt2ekzfvckr.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2gbsudztz.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gt2yctxsrzw.html

[U09] Py：字典取最大值的键
来源：http://dali.yonumen.top/Article/details/gt2kbpnnsiv.html

max(d, key=d.get)
来源：http://dali.shuidangran.top/Article/details/gt2afjzrzso.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gt2tddyfnbc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gt2rsqwuukn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbbzbvd.html

(x * 2 for x in arr)
来源：http://dali.shuidangran.top/Article/details/gt2jbzrtcfa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gt2epimxqgm.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gt2uuuraqfa.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gt2ekuzelwd.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2zhznqfyc.html

[U14] Py：分组收集到列表
来源：http://dali.jqgfzy.top/Article/details/gt2kpggsxvq.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhmywbpg.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gt2xiivixsc.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqjgpqek.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybsepzfz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gaohongyu789.top/Article/details/gt2yjqaqxiv.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbwyiuxv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tanke756.top/Article/details/gt2nrhrbrqz.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfmrsyud.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2ruvjtxwl.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gt2mymwgdbz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shuidangran.top/Article/details/gt2jkekeaze.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gt2hnehmuim.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqpgtjxs.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gt2vzittsbq.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gt2dydjcraj.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gt2yotyiucd.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gt2zjrllhxa.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gt2vovtffdb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hysaishi.cn/Article/details/gt2gmvmrkvp.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gt2qrhakvia.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2yiomxema.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gt2gzxhnqvr.html

csv.DictReader(f)
来源：http://dali.c1oappe.top/Article/details/gt2fhmaquwk.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gt2ussjxrfy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gt2yfbzoyjj.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gt2szwzsjfs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gt2rmmprkxd.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gt2eucbnqvx.html

UserId = int
来源：http://dali.zdqjudy.top/Article/details/gt2ypwwvcns.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gt2ymdvxgwe.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gt2eplkutxg.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gt2vztquqgs.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2pxnotuls.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gt2zcvbdrxc.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adzehxej.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gt2ekexzlph.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gt2kryjnrah.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gt2cusxaaxl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gt2hyavepcl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqwlzyg.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gt2zwvinhvn.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gt2poraguxb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnqzz.top/Article/details/gt2fqgumfbg.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gt2ooacwnyj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dalxrble.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptsgifxn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gt2dyojfqpm.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gt2otjzgves.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gt2odvbermz.html

[U39] Py：判断是否在交互环境
来源：http://dali.sysykeji.top/Article/details/gt2jxbmevwk.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gt2ipuzqnbc.html

[U40] Py：打印到标准错误
来源：http://dali.ppjwa.cn/Article/details/gt2cojmctlx.html

print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gt2zrdslkrb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gt2rcyzffkr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gt2byfjicgl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tooyvxzm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gt2vusugmzh.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gt2kcqdrruk.html

namespace App\Http;
来源：http://dali.birdmap.top/Article/details/gt2yctvoqie.html

[U44] PHP：开启严格类型
来源：http://dali.316326.xyz/Article/details/gt2pkwhevjb.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gt2pbhogdum.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gt2oyubivgb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2smquyuus.html

[U46] PHP：可空类型
来源：http://dali.cucudq.cn/Article/details/gt2nctcfeqx.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gt2pzgzwmgz.html

[U47] PHP：联合类型
来源：http://dali.hywenlv.cn/Article/details/gt2imlcsqjj.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gt2fgrmhnok.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwipfok.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dianchejie.cn/Article/details/gt2uvvhdbmd.html

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gt2mmrnhwlo.html

public readonly string $name
来源：http://dali.gaohongyu789.top/Article/details/gt2gptuxrbp.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gt2anxhouuo.html

public function __construct(private int $id) {}
来源：http://dali.redwolf501.top/Article/details/gt2oajqsdev.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gt2qhyjtqqh.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptldoqdt.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gt2cblnjemz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gt2glhugiwy.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gt2iopnybcf.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gt2twcjrpuf.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gt2myoghtik.html

$obj?->method()
来源：http://dali.yonumen.top/Article/details/gt2iwxexgpy.html

[U55] PHP：match 表达式
来源：http://dali.yonumen.top/Article/details/gt2pzkqvugd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gt2ucjmeops.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2gmyvdfej.html

f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gt2ggxjbgvl.html

[U57] PHP：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2nspkwwhl.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gt2jlpejfll.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okezevde.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ueypbixq.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gt2dgzmqowq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2snvxxiuq.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gt2pvthqbzj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2mbogfxlr.html

[U61] PHP：正则
来源：http://dali.chenjidiqi.icu/Article/details/gt2vntehggi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2egmzvlki.html

[U62] PHP：日期对象
来源：http://dali.yj20258888.top/Article/details/gt2xlvtsbph.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gt2rhtkkhyu.html

[U63] PHP：文件读写
来源：http://dali.tianlin.xyz/Article/details/gt2phkobkrl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cheryme.top/Article/details/gt2guxfioqb.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2tmmpmxvn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnxiangtu.top/Article/details/gt2utgeyocm.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gt2rzowpnae.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2opcwrkev.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gt2ffnowybn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gt2jivoorvm.html

[U67] PHP：处理文件上传
来源：http://dali.yonumen.top/Article/details/gt2ncnlpkfb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gt2szvlbbmw.html

[U68] PHP：PDO 连接
来源：http://dali.yongpay.top/Article/details/gt2untnwlfg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gt2eitrmwwi.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxuanxn.top/Article/details/gt2byhcinoz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gt2iegeldmt.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gt2awoltyzi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gt2sxholoxi.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2qcblhasc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqrcuqob.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gt2gmwhmpvd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gt2ijizwdyj.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gt2nqdcxuuy.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gt2cppxhisb.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2tihtzxhw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hammf.cn/Article/details/gt2lhckekav.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vboibosn.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gt2ihnwrhst.html

[U76] PHP：简单路由
来源：http://dali.cheryme.top/Article/details/gt2yupzxcld.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hfpthk.cn/Article/details/gt2qyusubog.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gt2jopuvqfj.html

composer require twig/twig
来源：http://dali.bjfxy.top/Article/details/gt2ngwthpvs.html

[U78] PHP：单元测试
来源：http://dali.tanke756.top/Article/details/gt2vzmfrieu.html

composer require --dev phpunit/phpunit
来源：http://dali.sxryk.cn/Article/details/gt2efxnbepw.html

[U79] PHP：静态分析
来源：http://dali.ydzc1.top/Article/details/gt2qwxnnequ.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gt2dkkohxtn.html

[U80] PHP：代码规范修复
来源：http://dali.yuxming.cn/Article/details/gt2wdfbwsyx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjvytvsa.html

[U81] JS：初始化项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2anxucfkw.html

npm init -y;  npm i express
来源：http://dali.cheryme.top/Article/details/gt2epnhujbw.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gt2vmuzkwtd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hfpthk.cn/Article/details/gt2dinbrgce.html


<!-- 参考信息 -->