代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mvnqgzyd.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2zbdgheav.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzdnvbzi.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gt2yybiudoq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gt2exdbjsvo.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2ducxowft.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2vxknlkln.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gt2ibhlhlxf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gt2lvdmhrck.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gt2vemkbwnl.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gt2nhaisluz.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2qpzaxnvt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2znnycdjv.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gt2yfzrlsdb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucmruoqf.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2espzfmof.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2pxmlduku.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2bumzismp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltpkvwyo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2erphdwiq.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2ethbjibw.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2vwskiixd.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gt2fgkhkpol.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gt2keditafx.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2owhrjtke.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2gyucjasb.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gt2jzazwmgf.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gt2tlnqxjxj.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gt2ardnlyge.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2svgcvngj.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gt2syzjumwh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2elvkpmuo.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2ivyximqu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2uvrggmob.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2hpoolnhh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkxzaac.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gt2wjtzyigh.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2qdzsyqeh.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gt2mkuwynkk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gt2kafpappz.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gt2vfmylvfs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gt2bqkeahwq.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gt2sigwzkzs.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fakfndij.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2gujjezto.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2fqepihui.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gt2jmxcpqwy.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2epjnzyjn.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gt2xeknuvzj.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gt2illaqqmo.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gt2wxwrtigw.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gt2rxqxrlrg.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gt2jlsimhoc.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2gmjwpgnz.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2vtrspxmn.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gt2upyekgma.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2xfapckfp.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gt2hungzbzt.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gt2dhdcgnhr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gt2haiiguxp.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gt2zfntjtnk.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gt2xvxtbxop.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gt2itowbffx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2kwttpfhp.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gt2xxuczzen.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqrnejmj.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2mjiegqyl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2vfolkbcz.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gt2bormurix.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gt2uyrnodvq.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2zdcbmxpd.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yusldfya.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gt2wojihmwa.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gt2ursntvge.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2slkbfucw.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvdlgseg.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2ejyveneo.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gt2eskwsthn.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gt2alqxqbqa.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gt2rxlkwrzy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfglsot.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2fumdiajr.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gt2blgiqsjg.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gt2yawezlor.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gt2erwcdgjs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gt2iisijzjn.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gt2jfhfzivb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gt2attnfrzv.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gt2ofzpbuuv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbphxtra.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vuidytkj.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gt2jzeafxwv.html

[T37] Lua：字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gt2qymorscm.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gt2cehqipby.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gt2rxhiydjh.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2ivqntjtr.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2abiffbdx.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gt2iffwctfj.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gt2oedvzzhx.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gt2muthqlwf.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2frbvqxga.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gt2pheyclmh.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2sokcqjyg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gt2inrptkby.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2egyphepx.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gt2ommqpvpi.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2vfwuaxbh.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2dsaftwfv.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2pevjpxxi.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gt2nrvlkkgv.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gt2kdybjnzk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gt2qkjliuxg.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gt2zqveasro.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgsvthpy.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2tqkfjlih.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gt2jdmefjfh.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gt2tgralaaa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2vrddzvpr.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2hxqjiaht.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gt2zfldzjsb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2mcfpbtxx.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2eamkrxpu.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2yhvdoflr.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2qkrrqaco.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2tssmdmxy.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2lvxpnjvx.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2llksmkww.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gt2vmuzpnvr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2vjlkjiuf.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2qmymjvlv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gt2btqzzynv.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gt2peiigkfv.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2lusinwkb.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2fmtckmxn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gt2usmhvgpq.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2vfhgoyli.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gt2zjneuclr.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gt2ifaggeay.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgtnyaog.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gt2gsnzdzrm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovrepxox.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcydeqrd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gt2dfpmmstb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2cbukgylq.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gt2uuevqydz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtrgwpau.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgfpxfas.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2rawtywgi.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2kpvfiuhw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkleeleq.html

[U04] Py：变量调试打印
来源：http://dali.guowangkeji.top/Article/details/gt2vgyfcysr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gt2kpipszqm.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gt2wruqnxcq.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2cezwvdqv.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gt2jxesrupf.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gt2vsrpfmyk.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2joymiecp.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gt2pnywxmak.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gt2iwlzqusa.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gt2cjxhvtno.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gt2leetycwh.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gt2miaqpwzp.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gt2eqfjllyl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gt2tigmufks.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gt2msqqlrse.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gt2xjpjlwyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gt2ebjypkir.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsmhgzje.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gt2ubreutgm.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gt2zoznxcav.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvlufpjd.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gt2iafltfmx.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gt2rggbpdhf.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gt2qbaphnnw.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gt2eeajgomd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gt2rishlrew.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gt2agpmlbsy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gt2llaoqxge.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gt2bizbztan.html

pat = re.compile(r"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2qwtdevxk.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gt2zkznabyf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gzhubu.top/Article/details/gt2ekwjcnrw.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gt2wvdupdbi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gt2svwicxeq.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gt2lcovmwqu.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gt2otjmfvuu.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gt2lgovorav.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gt2acyumbae.html

[U23] Py：分块读取大文件
来源：http://dali.jqgfzy.top/Article/details/gt2guecjmwp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gt2bcebmdub.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gt2ejpdvbbh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2hhexcjmp.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gt2sixrmbcd.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gt2wqgvtcou.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gt2cgorkaai.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gt2agcnyylj.html

[U27] Py：异步 HTTP
来源：http://dali.zhengqikj.top/Article/details/gt2wudnwkct.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2mevrzmeq.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gt2ghyzgzmm.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gt2eveeshvq.html

[U29] Py：属性校验
来源：http://dali.jianghu66.top/Article/details/gt2xruydbgw.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gt2ibtwcadh.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2ytekdlvd.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gt2ampfnegp.html

[U31] Py：单测
来源：http://dali.birdmap.top/Article/details/gt2ayirjlhq.html

python -m pytest -q
来源：http://dali.xuanzx.com/Article/details/gt2bsnghnbf.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdufvnjb.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gt2zmldspvs.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gt2wammwnfv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gt2nxgseyhm.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2nohrtxmb.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gt2zaggxjwg.html

[U35] Py：发送邮件
来源：http://dali.jqgufenzy.top/Article/details/gt2uikyejcx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnxiangtu.top/Article/details/gt2rocdelfp.html

[U36] Py：定时任务
来源：http://dali.svipenyu.cn/Article/details/gt2shmgrcgl.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuxming.cn/Article/details/gt2ulnbtvhv.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gt2shcoqqda.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efnttvhz.html

[U38] Py：获取脚本所在目录
来源：http://dali.guannengcc.top/Article/details/gt2mhfbpypv.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdzeuicc.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigfzy.top/Article/details/gt2nonyoltt.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gt2mkytsugd.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gt2yeolkdwu.html

print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gt2juqptmrt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjysxtyn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gt2mrbgyter.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gt2xdybgqva.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gt2lgxlzayv.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2uenxsuqn.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjvqasod.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gt2cisnhdyi.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gt2licxbczy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sysykeji.top/Article/details/gt2jnmgfgbf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2mrrcrpnj.html

[U46] PHP：可空类型
来源：http://dali.0kj1m.cn/Article/details/gt2mezxlxik.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gt2ufsyersr.html

[U47] PHP：联合类型
来源：http://dali.shzxlz.cn/Article/details/gt2igjjmogt.html

int|string $id
来源：http://dali.aizwys.cn/Article/details/gt2ppmvmtxu.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gt2eloodsrd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gt2bhfsedmm.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gt2uriobtrz.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gt2mvzsytmc.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gt2feiijzvx.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gt2kpktialu.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gt2qdtusccd.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gt2nfjhwjya.html

[U52] PHP：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbrhogdg.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gt2hkjwjkob.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgfpnguo.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gt2qvzujyoy.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gt2fzvfuyfi.html

$obj?->method()
来源：http://dali.fzhhl.top/Article/details/gt2axiihhji.html

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gt2gpctfvhs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gt2qlafakcp.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gt2bdrnvzqb.html

f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gt2wzxrpkuk.html

[U57] PHP：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2bwnpywvr.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gt2qxnelaie.html

[U58] PHP：数组三件套
来源：http://dali.nanxuanxn.top/Article/details/gt2fojasysh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oojodboz.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gt2rmulqxml.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2kzbfltgt.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gt2zsafdxfx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chnckpyu.html

[U61] PHP：正则
来源：http://dali.sweek.top/Article/details/gt2udlymeiy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2widjbypd.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gt2jafgfdlw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tian-w.cn/Article/details/gt2onjkorsv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwvvplg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gt2mjwzwmuw.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mivybhpt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqxjbdbu.html

[U65] PHP：会话
来源：http://dali.redwolf501.top/Article/details/gt2hgqrcuam.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2tiuccfgj.html

[U66] PHP：设置 Cookie
来源：http://dali.yueranfly.top/Article/details/gt2rokjnptx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gt2ozylmxlj.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gt2quawxcwu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgufenzy.top/Article/details/gt2cxfzpnnh.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gt2szpbcwkj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gt2lhqshrgm.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gt2uevtwgnb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gt2cthfkdoq.html

[U70] PHP：PDO 事务
来源：http://dali.fengsongda.top/Article/details/gt2nuotvixk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daria6918.cn/Article/details/gt2otgyxetl.html

[U71] PHP：抛出异常
来源：http://dali.havefunace.top/Article/details/gt2ppahujnm.html

throw new RuntimeException("失败", 500);
来源：http://dali.xylfe.cn/Article/details/gt2iucrguru.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2smlwsmtp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.vqdsnc.cn/Article/details/gt2brvixoln.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gt2zioqxlur.html

parse_ini_file("config.ini", true)
来源：http://dali.haohaochexian.top/Article/details/gt2fzrdgqlc.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atuxfscc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.meibo888.top/Article/details/gt2joqtkzgz.html

[U75] PHP：依赖注入
来源：http://dali.havefunace.top/Article/details/gt2muailwju.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gt2tdmianjw.html

[U76] PHP：简单路由
来源：http://dali.hnqzz.top/Article/details/gt2auomonjh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gt2vksnwajv.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gt2qycvqjbh.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gt2ymxlblwc.html

[U78] PHP：单元测试
来源：http://dali.daxiang520.top/Article/details/gt2zvvlcghw.html

composer require --dev phpunit/phpunit
来源：http://dali.sufxvd.cn/Article/details/gt2eeuswopw.html


<!-- 参考信息 -->