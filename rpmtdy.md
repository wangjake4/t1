代发 wailian999

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gtovaewerh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtrxslcyvm.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtjiotuwcw.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtwhxanqus.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtstunhsvq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtlixsmrhp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtwqzufpfz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtejhgohos.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlxbhnni.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtqpgfsfxq.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtltpqqtlw.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhitaenm.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtyvglppba.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjnzrbuf.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxiqjzjg.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtixkltgos.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtgozsugvf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtikfpqeiu.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gtkszdeipi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtbjzmcyrk.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtoukrzywi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtsvqrugvx.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtelohnfpc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqbtfcrg.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtlvogdkcg.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtrfdwfehq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gttomrfmhw.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtcgtmhwtf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtbaocdhjz.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtsmsgfozb.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gtphytkvwc.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gttsfyekyt.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtjvtpwieh.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtvbccijvr.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gtnjsbiobg.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtuoeydyrh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtqsivggsn.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtmhvgiayz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtzyawpzzx.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtsqrhxpgw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtmdaaqjhp.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtipjnjwrt.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtpnwiqjac.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtuzmihsyb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtmgsnqsqt.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtozpcgjic.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtjyogjhok.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtkaxsmnod.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtbrhvcfuy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnhwdjols.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtyzipbces.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthonuojwg.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtglbynwhp.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gteipcfktj.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gturfcvuvg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtrfdvrwau.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtnqwauwvj.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gttbacrnmo.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gtimztqwqu.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtyxjgxoit.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtpcbuabhd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtoxolthta.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtqzivmtnb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtkoswhlag.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtnfchpixz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gthdpnqlrp.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtnbscjalc.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtaukblrxv.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtsnmitvvq.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtlqaeiqzl.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbkemsik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtxlxztgpa.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtunogcyer.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsukunvpi.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gtgafdtpjt.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtttlbkqze.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtpasvxcny.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gtzmwveugk.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtexzkipvq.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtaiftxvke.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtcvmlsehe.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtacgomedq.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtqoiswogp.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtdlbobguf.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtzamisyqn.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gtfbxtrlxi.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtjvvddoqi.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gthvagttyq.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeslrliq.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtwpprqeyg.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gttlfmhvwm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtgcqolrzy.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gtbxmgxiqw.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gtokhwmanl.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtxpuwllbc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gttplcvgwl.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqhkdwbbv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtihghwbvt.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtgveqnpof.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtvvisiodj.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtythhshus.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtiwsjjoud.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgevomgkq.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtobarvuhf.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtmsfqqenv.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtidfxmymi.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gtbipnyigj.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenhxoago.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtuypkczwk.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtomjvbwyg.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtnkrdrwkw.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtrzghvtwr.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtbvqgigiz.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtrteasrzk.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gthfqskhhe.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtaecdeoby.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gtcfnzebtp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gtwjqjkhpz.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpzjtkmm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gthhrmaqzk.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gtfuldrcfw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtelzurlsb.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtrszjhypo.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gthrdhkckh.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtcpvkgnra.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtvsvutqpv.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gticgnuvff.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtxjlgbhyd.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtzgermald.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtuquonunk.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtonskzovx.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gtiypaqtkq.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtavnocvqp.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtxhrzofdt.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtxryrgrci.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtqcblmsot.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtcnfkgtor.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gtgpiccvyr.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gtkyoseuqj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtaennwube.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gtcstaufah.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtgbfpqghu.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gthgjincio.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtcvjnxvfi.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gtcbnifapd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gtemrelfhd.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtycjeekll.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gtozeaguhd.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtwjccgvqk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgajyufq.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtilzkpzlu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtiwcguhuu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtxnfnoygp.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtkbrimxji.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtpeztylbf.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gtqhadakom.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gthfwfifdi.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtroppcpmk.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtfiohnumv.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtpksmoeri.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtsdpvdehc.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gttoujrlfn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yongpay.top/Article/details/gtqwymowqe.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtiltaioyy.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgbrfgza.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtiwyduwvq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtgchmqrtb.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtjuujtdkj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ehwqpu.com/Article/details/gtnqzbkiur.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gtzpjtgqia.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtwhsohfto.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gtlufgigko.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtiigjnukq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsjhvhuyf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtlvvwezfe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtoxqxkrje.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gtwjxixpuy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gttiwacwhi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtfrpiwpvq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwryxhpiw.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtygwnhrgm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtmgazuwpt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gtbmrzbojd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gthzqowmpn.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtahmjnrnz.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtayvlmiuz.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtecdwdckm.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtpksqxcqw.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtgppiezgu.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtnquhngng.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtwqkbpxng.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtdsfudnhc.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtnnytraop.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtwteeoedv.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gtrhedfznv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gtakkuhllf.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtslknnmhm.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gtbyvldtkj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gtsvuoiffk.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gtigvgvenr.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gtfiaqggpx.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtrzvlmsop.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtrtogutjx.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gtowevaxsv.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtilcpnsku.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtvhokazuq.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtoidjsyuh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtbdjbvlcj.html

[U17] Py：初始化日志
来源：http://dali.vqdsnc.cn/Article/details/gtgnejumys.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gtyxbksvlt.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtoxcvbjwr.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtmxvqssrp.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtefkwuvqq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwrggfeg.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gtywivopgp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxzexxvi.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gtvyzkprln.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtcjasvaki.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gtheadfvsu.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gtafygvkll.html

[U23] Py：分块读取大文件
来源：http://dali.jqgfzy.top/Article/details/gtuovwgatf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdsykgpt.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtoxltjoey.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtpzrundfv.html

[U25] Py：CSV 按字典读
来源：http://dali.yuxming.cn/Article/details/gthwrcgumb.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcedxsyqn.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gthylmiquh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtgwwnulpa.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtculygjht.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtyanchtuk.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gtxwgqnark.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtnwpxbyfp.html

[U29] Py：属性校验
来源：http://dali.shzxlz.cn/Article/details/gtrxnlyogz.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gtpgckboij.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gtpwywxvwe.html

@dataclass(slots=True)
来源：http://dali.gzhubu.top/Article/details/gtqmdchpnh.html

[U31] Py：单测
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgzsjwty.html

python -m pytest -q
来源：http://dali.sweek.top/Article/details/gtascwawqh.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gtbkdcnkbo.html

ruff format . && ruff check --fix .
来源：http://dali.yangfankeji.com/Article/details/gtdlvuqrrg.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gtuigknozq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqclxwegj.html

[U34] Py：判断编码
来源：http://dali.zycfv.cn/Article/details/gtsgqmtdxb.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohzarlwd.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gtkapbdfei.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtikwhdeez.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gtvbkoshzp.html

schedule.every(10).minutes.do(job)
来源：http://dali.vqdsnc.cn/Article/details/gthjbzqctc.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmlkbems.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daxiang520.top/Article/details/gtikqrzood.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuetiantiany.cn/Article/details/gtwxdgsgyo.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gtzmoabefq.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gtdrlawuwy.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gtohebcgml.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtddcxxpgk.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtlukfvozn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gtcpzjoagy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhengqikj.top/Article/details/gtgeeenjux.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gtkafnhkpv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shangyingyoupin.top/Article/details/gtjcekwjvd.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtlimbpyzd.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gtswdkdsov.html

[U44] PHP：开启严格类型
来源：http://dali.aibaodan.cn/Article/details/gtjkbdhghy.html

declare(strict_types=1);
来源：http://dali.jinqigfzy.top/Article/details/gthmpcbxgp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gtowbpowwl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtxabnogft.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtgbsrgsrq.html

?string $name = null
来源：http://dali.sxryk.cn/Article/details/gtukfjgpmt.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gtlhgrhcmd.html

int|string $id
来源：http://dali.cucudq.cn/Article/details/gtrwyauqix.html

[U48] PHP：纯枚举
来源：http://dali.guowangkeji.top/Article/details/gtyewjocnm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlurarog.html

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gtxxlkibfo.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gtglodlqqj.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigfzy.top/Article/details/gtvkizpcsq.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtlebqbehl.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gthygdilid.html

[$a, $b] = $arr;
来源：http://dali.andypj.xyz/Article/details/gtpkxwwanq.html

[U52] PHP：箭头函数
来源：http://dali.tanke756.top/Article/details/gtlpbnrtkr.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtsgxeilxf.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gttbctdjtu.html

$v = $a ?? $b ?? "default";
来源：http://dali.gogol.net.cn/Article/details/gtklitdtij.html

[U54] PHP：空安全调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxqleazi.html

$obj?->method()
来源：http://dali.zhongyouzk.top/Article/details/gtglgkmyev.html

[U55] PHP：match 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtbnzyfzms.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtfgioaarb.html

[U56] PHP：命名参数
来源：http://dali.smart0.xyz/Article/details/gtklszqcef.html

f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gticxkhsaj.html

[U57] PHP：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtupxwkdcn.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gtpyjjvtqu.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gtfnnebcmp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guowangkeji.top/Article/details/gtyhdliyum.html

[U59] PHP：自定义排序
来源：http://dali.iojbl.cn/Article/details/gtggslwpik.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtmzwpgrpj.html

[U60] PHP：JSON 编解码
来源：http://dali.cashguo.top/Article/details/gtollbktzs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gtpjuypbgu.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gtlyzqohac.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtlqxwvvil.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwqtllnz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtzmvyuuid.html


<!-- 参考信息 -->