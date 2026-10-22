代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2qkoybowm.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gt2rhtetbwh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2lrtozvcj.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2myndqbtx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gt2dfkrfbuu.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gt2lsnbrkls.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2hmmbzfcr.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2myzxgrlg.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gt2qratsgxi.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gt2qoevkzqk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gt2tnbgtusu.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2ggsqlhvn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2itkqxdzi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gjtlvdga.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2rhtigxny.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2snqdlidi.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gt2sheikmlv.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2avwfykwf.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2wldkdcfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gt2gdfxtsbb.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2grlzmkul.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2skflmixl.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gt2zbvbfpsx.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2mvhebinh.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2qdtydjza.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gt2cwclwqyk.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2yqbcjbkn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2gexassrn.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyqmqqrp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2cseucipa.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gt2hegephzx.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2olgffuyu.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2hesshrvl.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gt2lytarmrs.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2yokkbjfc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gt2ijzeqbrr.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gt2xqmwuctw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gt2kbtixigs.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gt2jdwzkgqm.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2thafqono.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gt2zgavhoen.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gt2kdcaujvj.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2efjexkzr.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2trbkmhej.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gt2rrcdamrd.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gt2smrsqnwx.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2dzmbginx.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hptnkwng.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gt2hvewjyuf.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzuevakt.html

[T18] Swift：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2ckoyhtbz.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gt2lmljrbef.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2fyrmonxm.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gt2yavfebij.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gt2pwvllfam.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gt2abdxvxhi.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gt2iprowrhp.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gt2hhjfbdid.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqeasrib.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2ryxqxrry.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gt2zoupxywx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gt2qwmhgoau.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gt2knmnqrpo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2ssdyidtn.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gt2pkavdjta.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gt2synbtzzp.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2yigstksz.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2qjrcteuu.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncvouzhm.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2etyaxqrh.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gt2qxowvwbt.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2aqobdacz.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gt2rekuwqxa.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2uddmpapo.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gt2rugnoxau.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gt2tvkgrntw.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2flzzscxh.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2whhoomkn.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kklyrhvt.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otuzinnk.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiqelwas.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gt2jlpidbtb.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gt2owztxhud.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gt2yqmldgeo.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onjolyza.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2eqgvvnbk.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2pacfjzdi.html

function add(a, b) return a + b end
来源：http://dali.vqdsnc.cn/Article/details/gt2elnbujrx.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2lhxpfuxi.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gt2nwimdhad.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gt2bpayfefg.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gt2yxgdeeqp.html

[T39] Lua：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2lsqcnmur.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gt2fecxdybh.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2dzrjytzn.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gt2ajouosxs.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2ttgyogxn.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2ktioaszs.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuulyaew.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gt2zijlpext.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2jygnjcrm.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gt2jizyxinm.html

[T44] Perl：条件
来源：http://dali.daxiang520.top/Article/details/gt2fkvlyqlt.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agswbofy.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gt2jyotkyel.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2cvjnpbtd.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gt2myzjemtz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gt2jfwdcwiw.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gt2cjzyfhbn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2pllbpikl.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2kcvnjsqq.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gt2tcavdaih.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gt2wbometmq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2mbfbobap.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2owmpkurf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gt2huakpxyb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gt2hjfvboxa.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2msgpxyjw.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2lwtqovqm.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gt2lreuqzzn.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkozwrpf.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2zxwggdzt.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2mxyatjti.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2nhadazcd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gt2etrqirhr.html

[T55] Scala：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gt2ffqqbkjd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gt2getlhouw.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gt2njfmvzdu.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gt2rehcbfew.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2dfzqyyhx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gt2uujvqadb.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbhjufjx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gt2shlldtlt.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2fwwagbtq.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2xpmuesjl.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gt2qkjfsfpw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gt2kozorszs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2tqgvbvyf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gt2yvcbecli.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2waapgeyy.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhlhwpnx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcnksgai.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsiqjned.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gt2gdufsmsu.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gt2xkbxozgv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gt2chqwkzyh.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gt2mpfwnjub.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gt2bzgadamp.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gt2uboskvgi.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2csjdpwng.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gt2vioocgqq.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gt2irydrxwk.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gt2zejzlhib.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gt2chwatczq.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gt2dfuijgha.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2dwdrmxig.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gt2puhxzdjz.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gt2xaagbwjz.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gt2mfnvpzew.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gt2vppvbmdj.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gt2kjobivff.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gt2oteqfdwb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gt2dmdclexi.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gt2yominqts.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gt2itjvypab.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gt2rbqbarbk.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gt2powyvkfl.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gt2alqeywoo.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhbewsmw.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gt2fatcymvo.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gt2kywtgdaw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gt2jpeixdtj.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmepwnhx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gt2uibabgwz.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gt2hlkrwmou.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2prcizbvt.html

[U19] Py：正则替换带回调
来源：http://dali.jyoumei.cn/Article/details/gt2qzxmpnnj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wggfsumg.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avmqxtok.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gt2gsvlkybf.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gt2nzsqejmk.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gt2boaazhyi.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gt2agwfskhm.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gt2enykqxcz.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2oktjlczb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gt2huuntqzk.html

[U24] Py：路径操作
来源：http://dali.ydzc1.top/Article/details/gt2yslpuyks.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2meavgbut.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gt2ylfdjqea.html

csv.DictReader(f)
来源：http://dali.iojbl.cn/Article/details/gt2ccjwuout.html

[U26] Py：并发下载
来源：http://dali.redwolf501.top/Article/details/gt2ubffwzyr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gt2mzzihneu.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gt2dngshxrn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gt2pdwcudje.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gt2yubmxvuw.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gt2rivmoshg.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gt2uthqcumq.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gt2yoflsskm.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gt2jguhauug.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxjfajm.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gt2wfxmteam.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gt2cxyvhten.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eigofzbx.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gt2oatyzceg.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gt2gmxdjzso.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gt2euuwnota.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2priaxvyi.html

chardet.detect(raw)
来源：http://dali.vqdsnc.cn/Article/details/gt2kicbpdxh.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gt2abhclkeb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gt2mqyrnutl.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2rukfybnc.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gt2islbnmgb.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gt2rsvoqhoy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gt2pmxvbpqz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2mprlznxr.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpipyigr.html

[U39] Py：判断是否在交互环境
来源：http://dali.dianchejie.cn/Article/details/gt2flnahglo.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gt2emefzqjb.html

[U40] Py：打印到标准错误
来源：http://dali.cucudq.cn/Article/details/gt2svttvfbu.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2veiuwsfs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daria6918.cn/Article/details/gt2ftulzajc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gt2nogwltef.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gt2kxuzphny.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gt2lvbmiern.html

[U43] PHP：声明命名空间
来源：http://dali.yonumen.top/Article/details/gt2bklrfajj.html

namespace App\Http;
来源：http://dali.xinyue.icu/Article/details/gt2txxbrgcb.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gt2isbxehpr.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gt2qctieebn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.0kj1m.cn/Article/details/gt2skiqfmxj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2iqprmsoi.html

[U46] PHP：可空类型
来源：http://dali.svipenyu.cn/Article/details/gt2uiutdpuu.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gt2bppsyhsu.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gt2erpwdunc.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gt2rjekzhri.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gt2ewxulsus.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gt2nftmruvt.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gt2zohdqwne.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbmduxle.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gt2onuggwrc.html

public function __construct(private int $id) {}
来源：http://dali.iojbl.cn/Article/details/gt2iesdoext.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzdknuye.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gt2bcslvjpk.html

[U52] PHP：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gt2jjsqwcoz.html

$double = fn($x) => $x * 2;
来源：http://dali.aizwys.cn/Article/details/gt2qmlkwgkz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdtdmht.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gt2jpaoqpte.html

[U54] PHP：空安全调用
来源：http://dali.chenzaomai.com/Article/details/gt2mpcsqwzr.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gt2pgthghwt.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gt2nlavmvnk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2zfsuqlyi.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gt2nrlzvwcl.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2paqdzkqb.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2jwupjbjy.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gt2hpkxscno.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gt2lzfxvkun.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvhyiigi.html

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gt2izxmwffu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2ueubbqun.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gt2osgfzrze.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xziqi.cn/Article/details/gt2fsxbhzgx.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gt2wlwqewmq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2vzfjvivf.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gt2uwbelahy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gt2bfuwrbzr.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gt2igoynrke.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gt2bcczyemh.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upxdfpji.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gt2vkpzywru.html

[U65] PHP：会话
来源：http://dali.jinqigufen.top/Article/details/gt2nlnlcigo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2tgpnpwbe.html

[U66] PHP：设置 Cookie
来源：http://dali.mhx1999.top/Article/details/gt2imfrvigu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gt2lujvnasb.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigufen.top/Article/details/gt2vaeigavp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.svipenyu.cn/Article/details/gt2gbnmciuw.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258.top/Article/details/gt2nospjjva.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.svipenyu.cn/Article/details/gt2fhhfxzhu.html

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gt2juqspysm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gt2jatvqtbr.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gt2wiifkkkx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gt2smetkgve.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2rovftbru.html

throw new RuntimeException("失败", 500);
来源：http://dali.jlsjyb.cn/Article/details/gt2tiwvtous.html

[U72] PHP：写错误日志
来源：http://dali.yongpay.top/Article/details/gt2sjxqwvac.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nanxuanxn.top/Article/details/gt2klwtiehe.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gt2sddbfdsn.html

parse_ini_file("config.ini", true)
来源：http://dali.shuidangran.top/Article/details/gt2plufdmik.html

[U74] PHP：读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvpidyda.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gotoacloud.top/Article/details/gt2vmujgved.html

[U75] PHP：依赖注入
来源：http://dali.yongpay.top/Article/details/gt2fblcauob.html

composer require psr/container
来源：http://dali.yvedp.cn/Article/details/gt2yosojkds.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gt2nszklxph.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gt2opkxdiqp.html

[U77] PHP：模板渲染
来源：http://dali.fzhhl.top/Article/details/gt2hngbbnsl.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gt2coheozme.html

[U78] PHP：单元测试
来源：http://dali.gotoacloud.top/Article/details/gt2frdbhkad.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gt2zxomkzbm.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gt2syoptatf.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gt2demtzcyx.html

[U80] PHP：代码规范修复
来源：http://dali.hysaishi.cn/Article/details/gt2udjcyttm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ehwqpu.com/Article/details/gt2jpxkzouq.html


<!-- 参考信息 -->