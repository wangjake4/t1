代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtmzbdchnv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gthnwjzflz.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtttivuqkm.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtzhqjptuy.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtxqdbckif.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtvjywygmd.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gtjccnuxdy.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtfpywqsvw.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmcyvqib.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtjicadhvb.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtjxwvqspo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtjcjjykft.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtzjsxupii.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsyjykjd.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtenkjklrs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gttwdyoyip.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtkgdtzysh.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdasytuyw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gthaieuyht.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtffviwasa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtwplhuyux.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtchcucdqz.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gtohmspsik.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtypzkavue.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtoyoeaodr.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtwadqdyqn.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtdjcksogs.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtmohefjza.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtijmxpneh.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtgsxglyqd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtcxbfkaaj.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtzffyxvtf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtuqbtpqhx.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtnobrvxor.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrrsaqky.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gtlkucsgie.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gthcjbujhh.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnyavueea.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtiwsosxmv.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gthztlfrei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtzhhuopeh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzmgfsqzq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gttxposgou.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttkjtbfiu.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtogjjvrim.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgypuulex.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtoulqzbbj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gtpiajedgq.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtbgewxuyt.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtoribrdgg.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtuwwzvrpu.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtrrybffkb.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtimoxwmos.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtyesmhfcq.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtfqzalknh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtxjcpksgd.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtfocapblj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtykvuxkfn.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtebabmozq.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbzyzyps.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtatdhujxb.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtymfnqscy.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gtggtbdqak.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtfkdykpwx.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtdlkjngkm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtsgrzjehz.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtvwxeczcx.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtcomurlfi.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtgpfxbivw.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtdcudqnni.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gttnpmjmtl.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gttbnylxkv.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaarfwuw.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gtstnhcany.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtcfhrwxyu.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtyjrbpaae.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtmxdaqvvq.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsmysveh.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtscajskhd.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gtbnjuadnm.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtzlvtqqdk.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtalmwrkiz.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtcvehciwj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtqbdcizjh.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtzanprcqy.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtfvdbuqdb.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gtgeibyeci.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtdehpsjkp.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtngtewtab.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtujwqpwph.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtkehrbtui.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtwgfiebmy.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtkfckougd.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtqmdumxew.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gtgleltlsi.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gthvsvbcam.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtyytxnpuq.html

do { try f() } catch { print(error) }
来源：http://dali.aibaodan.cn/Article/details/gtwqwdmxwg.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gtodplplvx.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gttiqtoxmn.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gtpgtougak.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtxkvummvl.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtbgkdtrbh.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gtrmhmuvsi.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrtzovec.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtwgbfvudw.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtepnwajdn.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtyadcroje.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtznyrlgyb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtequypvpr.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gttkeijtbn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtzwcoywlv.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtydkevjpn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gtnetgccty.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtfdityhsj.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gtrsixptfa.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtxxichxob.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtjaxslvqo.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtuylftawy.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtzskozcmv.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtwaenmqqe.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gtqwehvqhs.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gtvrvezigi.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtwvidscql.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gtcmmglfmu.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtbzwwufzu.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtmcjaxoqa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gtgofrfulu.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtjbzlonkt.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtroigqhwu.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gtqvxbittq.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtuumvsdew.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgxlmaqa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctbtayck.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gtcyvjyxol.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xylfe.cn/Article/details/gtaguuqjwk.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtjbltatzv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gthsrwjtjt.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtlprktkrh.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gtiyjwfgao.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtcwxkyidp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gthxkostfb.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtbvjhxxko.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtwazryhmk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gtsdcdyvwy.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtwvoksnpm.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtbbhtukzt.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gtsjbqyjzn.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtlamejgko.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtjojtyiif.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtpaexjbrt.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtwfyfujlm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtncprhgpl.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtdyptqwwt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gtpaftfmrj.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtfvhzyezw.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtkrgaoqra.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtsqnjsrvc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtdewihdet.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtghrqcvrx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtorutchfn.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gtgxmujqsz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtmohemedm.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtisyeypwl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gtwmercvld.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtflgqcjga.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtsyjmiyfl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdingnizn.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gtqqreosxg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtdnmmuwsm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gtphgjgdai.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gtjbwbjnyj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtgtmwbdbt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gtgadozadk.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gtkucpcksm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtjjzrnxri.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gthynesmdj.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtufcwvhyz.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gtdzlbjhqo.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gtqduegics.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtvreffkje.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxauqafwq.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gtkattdhrg.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtbsxliqby.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtanxxboyx.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gthwuziqqn.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtdmrebpcr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiebkuqry.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gtccipexbt.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gtgjfprsgg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtakifpqjt.html

Counter(arr).most_common(3)
来源：http://dali.shuidangran.top/Article/details/gtizqiyyrn.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gtmaowvgbo.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtjzdzjrpq.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtqzigqhru.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtkuqhltbr.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gtsmgiugdi.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gtykrqgjsp.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gtmnimljtr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hysaishi.cn/Article/details/gtcdoeuycq.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gteqeczudn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gtfllyimwo.html

[U18] Py：预编译正则
来源：http://dali.fengsongda.top/Article/details/gtzcilxmdj.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtsnyfibpo.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtpefcecut.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtuimblmdl.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtzgtwbtao.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gtjzulsugc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gtugowizol.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gttnrxpyzu.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gtalhdbqlg.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtcyqixbuq.html

[U23] Py：分块读取大文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmkotoke.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtzwkatgle.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtsalojdeb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtustfgydn.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gtbjyhkwzj.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gttyblyxtx.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtpghiyjox.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gtbdutycys.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtmbzrbdty.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauimnvuf.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gtabjtcyxd.html

UserId = int
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrrrtkfv.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtmaiayiwg.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtimqkyjao.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gticbpgvcz.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctbvymjo.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtacqzmelh.html

python -m pytest -q
来源：http://dali.birdmap.top/Article/details/gtliiaqplx.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gtnoapppom.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gtfhbcfkxk.html

[U33] Py：打包发布
来源：http://dali.guannengcc.top/Article/details/gtfnvcscvx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258888.top/Article/details/gtlhrsaehf.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaydqocrc.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtmklojxlz.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtwzkgszst.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegomzmtu.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gttkbeugmi.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gtrpndjfqf.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gtnwlgckft.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gtynvjyoka.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtckgleymh.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtdlaborvf.html

[U39] Py：判断是否在交互环境
来源：http://dali.nwbrower.top/Article/details/gtorcwpnyp.html

sys.stdout.isatty()
来源：http://dali.zdqjudy.top/Article/details/gtvsanwmwv.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtobfqejmo.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtapojxarg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtvyslpvuu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hysaishi.cn/Article/details/gtbipvjozc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtfpcbmssx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenzaomai.com/Article/details/gtioorfwmu.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gtemshvlgd.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtwmykeigu.html

[U44] PHP：开启严格类型
来源：http://dali.shangyingyoupin.top/Article/details/gtfwtxyyzp.html

declare(strict_types=1);
来源：http://dali.bjfxy.top/Article/details/gtvrcpawme.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuanzx.com/Article/details/gtzdawahal.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtilqgsjyq.html

[U46] PHP：可空类型
来源：http://dali.wangdashe.top/Article/details/gtsyyopjfu.html

?string $name = null
来源：http://dali.cheryme.top/Article/details/gtdvodgcwg.html

[U47] PHP：联合类型
来源：http://dali.bjfxy.top/Article/details/gtnhmzpibs.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gtwdbemdbs.html

[U48] PHP：纯枚举
来源：http://dali.cdnleiting.top/Article/details/gtvcndouib.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gtkaisxdti.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gtvzgqwjfn.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtjunypfjp.html

[U50] PHP：构造器属性提升
来源：http://dali.yj202588.top/Article/details/gtqdyabjkz.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gtepplodoa.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gtdarbzell.html

[$a, $b] = $arr;
来源：http://dali.ehwqpu.com/Article/details/gtvsnqlkan.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtwegloxfw.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gtgjwsdkvn.html

[U53] PHP：空合并运算符
来源：http://dali.xuanzx.com/Article/details/gtgktsirkf.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtqcysdrgw.html

[U54] PHP：空安全调用
来源：http://dali.jyoumei.cn/Article/details/gtdiodiade.html

$obj?->method()
来源：http://dali.andypj.xyz/Article/details/gtrulwvtfv.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjtojycs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gthdohymun.html

[U56] PHP：命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtaufeqief.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtxlytpbzc.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtpchwmfaj.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gtgibdezlp.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gtjavweeja.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gtzhxjwuke.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gtykiottyo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtiscpgvbc.html

[U60] PHP：JSON 编解码
来源：http://dali.svipenyu.cn/Article/details/gtlpbkdomm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gtahrvnppk.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gtbxcbpffk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtqoubdzzs.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjkxgtvl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dianchejie.cn/Article/details/gtynsyoheo.html

[U63] PHP：文件读写
来源：http://dali.bjfxy.top/Article/details/gtdkfcqpmu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.0kj1m.cn/Article/details/gtxwqzdikv.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gtmqolpvzo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenzaomai.com/Article/details/gtxzhsthut.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gtisjwjyte.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtwtwwbfjt.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gtviwqieag.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gtjeudkpfx.html


<!-- 参考信息 -->