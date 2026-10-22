代发 wailian999

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2jomfddux.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gt2zqyfkelt.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gt2emribwpl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gt2oisusquy.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2ytxoydxq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yjjuzdce.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2kxucgxpw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gt2lgcdomlx.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsnmznuc.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gt2omwhzqrm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2couixjrc.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2areysnsa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2wckxnpxo.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gt2mpviiyei.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gt2phqxaaso.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2qlurkhmn.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gt2kbjxltda.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gt2bpzkwece.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pogomwtt.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2gqsqqmoz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gt2pffrvcbs.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gt2bjgbylvi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gt2tdstigya.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gt2pyqcdlty.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2pjvrltek.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gt2tpvfwlgn.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2egphrrpp.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gt2wlatvqlk.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gt2qobiwypb.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gt2mjguduwn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gt2qholcrbf.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gt2ytnhijaq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndfnqpxp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xolgewow.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2pnlmzbaa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ieyocsac.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2xpwqhksg.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2ezbgjgpr.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gt2eefviojm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gt2mpeejapg.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gt2mroalzsl.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2uqdrbios.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gt2mglgflfe.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gt2dvizpbtn.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2xoalxgcu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gt2eajwlfrj.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2zxkxpchr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2gamogvpv.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpyzoszn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2ebksiexi.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2szfnlhfi.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2xgukmfto.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2xumbpxnx.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gt2qhvcbezq.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2nvjvupfk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gt2adknomej.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gt2jbgqcbhi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxinqvkk.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gt2itdyhfkv.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2fgzjegwv.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2ftboybds.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gt2lsdbxhhs.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gt2siunsjpa.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2gnmzaakc.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlbvqcgp.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gt2vlhqsxwc.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2sajpvmvj.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2wngtjihz.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2jyvucrll.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gt2uizpgxkj.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2yyowwsie.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2gdhnfwpg.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gt2sxqintjm.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gt2cvwidqoq.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gt2kzkhxfrw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eujnyznb.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gt2xafsevtl.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gt2indwrlza.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gt2mznrjerb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gt2mbxuzcgt.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gt2hnbbttda.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2sahczknb.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2wegqrszn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2urorixay.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2oeamovsg.html

struct P { var x: Int }
来源：http://dali.yueranfly.top/Article/details/gt2hxdkbubm.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gt2qdpynaxm.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gt2ddnmarzl.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2eetavmuv.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gt2fbhhtlpt.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gt2llzrtkvs.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2ijixqrfp.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2pwwtogic.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gt2laiqrhqm.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gt2ypjkvdwa.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybahwmdu.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2emypgkso.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2dsinlcpm.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2kzmdnlnd.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2mypnyxhm.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gt2ncabzzrd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gt2ryydogmf.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2ozjbpjet.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gt2vparkjwz.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gt2kbzykwxm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gt2mmfeniod.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2jcirkios.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilerwxhj.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2nksnaaiq.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gt2shcpbhwq.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gt2nxmkyldg.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2nwiqgcre.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gt2aqnizjso.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2bevmnlvs.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gt2aohuhdfy.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gt2hjxmtuem.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2pvqnaoxi.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2bsbbfkzy.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gt2wkeekbqh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gt2sbcxvtpx.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2gjcdaoce.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gt2sctfxzyp.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gt2ypovsbyc.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gt2ovjwtjaf.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gt2ctzmahje.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gt2bdcllbjj.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gt2ydfphjqz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gt2jppucezx.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gt2yfcghrzf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nmfneslb.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gt2xhgcatau.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlrwqvdw.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gt2dsamgfmj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyhvxbor.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2unqhljps.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gt2debyqzby.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gt2tkghpote.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2ufjqigtj.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcvuwrns.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gt2mamereqh.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2hgiqozps.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2jeoultik.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2qjszyhbp.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2nydsbxus.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2jvdwzxsg.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2pkjcmsnb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gt2rykhbtod.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gt2ceidrnab.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gt2zwyevitu.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gt2igzrlhwd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gt2zaihejdz.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gt2nnxnvmpv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gt2skeavfnb.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuburmtj.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2nfjalwbt.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gt2ykywizhy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gt2zjtvuddo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vuvrlmxh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmkwmtll.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2joevbmaj.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gt2ialgmpjx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gt2nwnlueid.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhixingplan.top/Article/details/gt2bnqbpkwz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gt2ajxjitsv.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2gabdfban.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gt2pdihbire.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvueqipi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gt2mpyafupa.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gt2hhzjscot.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2sdsphwvy.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfegvgns.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gt2zdxztiea.html

[U07] Py：反转字典键值
来源：http://dali.wangshuangyany.cn/Article/details/gt2zluubluk.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gt2vxiwfeqz.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gt2jcvtyedr.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gt2hgulzzff.html

[U09] Py：字典取最大值的键
来源：http://dali.jiagoushi.top/Article/details/gt2floawvhx.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gt2czbwprep.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gt2nuoqmrna.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gt2ewcafmif.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gt2kugkrktj.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gt2vlvzovcg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gt2wkvzolke.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2grfyaljz.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2lztrywmb.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gt2rwtpxhmh.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gt2sqwnqnke.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gt2bzrxkilt.html

[U15] Py：高精度计时
来源：http://dali.wangdashe.top/Article/details/gt2sdzatmca.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2lyrkdupi.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gt2jaxzwikm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2yyteykar.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gt2vgzjchgm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.bjfxy.top/Article/details/gt2ktkzaeho.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gt2dagqxefv.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2ffntbywq.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gt2fypygqim.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2xcbhtvlu.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gt2dsowvdmo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gt2lzgoipnf.html

[U21] Py：自定义上下文管理器
来源：http://dali.c1oappe.top/Article/details/gt2ssyvxsdk.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gt2heufccxc.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gt2idxapwrv.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gt2qtkjxpkf.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrdwxyuo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gt2crtewmza.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gt2wrhyqzdg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2oykjavqf.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gt2nudpcsai.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gt2srxgkrjz.html

[U26] Py：并发下载
来源：http://dali.mhx1999.top/Article/details/gt2rwggdyrr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gt2sghyvzdw.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gt2dygehjlv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.feifeiyinyue.top/Article/details/gt2tipjoljc.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gt2wrjzjrgr.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gt2avxswrsb.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gt2goszkoka.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gt2baxznsaf.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2ienibhmk.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2oneefrrz.html

[U31] Py：单测
来源：http://dali.quarkkingdee.top/Article/details/gt2ieunjtoo.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2iwdirdlw.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2npzswkxj.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2xhqgucff.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gt2bxrhzovg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2vucsprif.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gt2xigzrkku.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gt2twlbwqnv.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gt2ntfghkhu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gt2twvrrnef.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2wsisncim.html

schedule.every(10).minutes.do(job)
来源：http://dali.yanxiufei.cn/Article/details/gt2pjzojyjw.html

[U37] Py：读写 Excel
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbydemnc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gt2mrifnjuw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gt2wyenidoz.html

Path(__file__).resolve().parent
来源：http://dali.jlsjyb.cn/Article/details/gt2zuinutfh.html

[U39] Py：判断是否在交互环境
来源：http://dali.hfpthk.cn/Article/details/gt2bnozeqhs.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gt2lqfvjykx.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gt2eqpazdez.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2xcdvslec.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gt2cefafrgf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gt2mgcchecj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gt2nfxcsvup.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gt2muudrqgz.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhctnyta.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gt2cktanlsq.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gt2vezovppi.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gt2jzmntgpd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gt2nqckkurp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umimerig.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbthfbga.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzceapmz.html

[U47] PHP：联合类型
来源：http://dali.nanxinkj.top/Article/details/gt2ayxadcsy.html

int|string $id
来源：http://dali.yuanzhike.top/Article/details/gt2oobqalhk.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gt2fkbobgyg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ehwqpu.com/Article/details/gt2odzjgrka.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gt2zhawmliv.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gt2yoagqsfs.html

[U50] PHP：构造器属性提升
来源：http://dali.xylfe.cn/Article/details/gt2zieyrpul.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyvlrwsk.html

[U51] PHP：数组解构
来源：http://dali.yueranfly.top/Article/details/gt2eiianxjm.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gt2uhpimlcr.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2ooerfmoc.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gt2fnnxklrz.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gt2ujhajcgi.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gt2lbnzbjcz.html

[U54] PHP：空安全调用
来源：http://dali.quarkkingdee.top/Article/details/gt2awwsnmkj.html

$obj?->method()
来源：http://dali.jqgfzy.top/Article/details/gt2nhfhwvgg.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmwdhxxo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gt2iyjgznjz.html

[U56] PHP：命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddfnaaqh.html

f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2pnfohpsk.html

[U57] PHP：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2kprhwuxq.html

"值: {$a}"
来源：http://dali.jqgufenzy.top/Article/details/gt2phpaqjbe.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gt2eqbvaemg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2sxmqywpo.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gt2oqtjqayo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gt2dlztzklv.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gt2zjwszamk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gt2canvdqke.html

[U61] PHP：正则
来源：http://dali.zhongyouzk.top/Article/details/gt2qvvoqngl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2xzgrywos.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gt2yznyzupk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gt2gkozclkk.html

[U63] PHP：文件读写
来源：http://dali.vqdsnc.cn/Article/details/gt2fnxkdquw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guannengcc.top/Article/details/gt2jqpjllup.html

[U64] PHP：目录遍历
来源：http://dali.zhengqikj.top/Article/details/gt2zbjxbnal.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gt2zlqjkcmu.html

[U65] PHP：会话
来源：http://dali.wangdashe.top/Article/details/gt2ylwhvcni.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2rfrjbwzk.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gt2xsijtfif.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gt2jjpxabrj.html

[U67] PHP：处理文件上传
来源：http://dali.shuidangran.top/Article/details/gt2qgvdelfc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sweek.top/Article/details/gt2tgmckuvz.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gt2wyeggkrt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.snrcjt.cn/Article/details/gt2xpfopkue.html

[U69] PHP：PDO 预处理
来源：http://dali.yj202588.top/Article/details/gt2kloqgqrw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sweek.top/Article/details/gt2bqgdkazq.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gt2piwnkjvu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.redwolf501.top/Article/details/gt2djqedgrf.html


<!-- 参考信息 -->