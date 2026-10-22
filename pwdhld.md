代发 wailian999

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtnwwomoub.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtnpxspubt.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxhuegxz.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtmqyjaazm.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gtpfbwwmpv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtjiajtbui.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtrnnvaplp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gtsfposhpg.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtxxjzdeej.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtqzdgciob.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gthiiowfrs.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtemnibwlg.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gttfpopjzp.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtjvqxdaej.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtktefzedl.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtitidxtqk.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtehfuczfj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtocrwbryb.html

[S46] C++：函数模板
来源：http://dali.sxryk.cn/Article/details/gtzvuojfsx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtllrttqhl.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtkxpryfhv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtvrpvjhfb.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtkqglcngk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtfoghexke.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtntwvaxip.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiuveigo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtgqmkuxkb.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtujfeicam.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtchbgqjnl.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtbxrcroti.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtotuhezlx.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtqehctjas.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtuarggjcc.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtyehvnupt.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtqodhmbll.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtvlqkpumc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwctfnnw.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtwcrcuojp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtjpsdpzqq.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtryqyrefb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtejdkbbkb.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtvpdaasdw.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhxejddx.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtgaykfwpa.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtoyjxybst.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtiwuwznxq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtzgsbzbkf.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhtzfyvg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gthhbmlouz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwmaisdsv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtztkuqqui.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuekrplls.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtfksfktup.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtyhwxkfwk.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtkntpejtg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtadmwaurj.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtltuvxnan.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtqfaoetql.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtdhglpvsw.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gtcyvbrosm.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtwrllhouc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtkatyglys.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtfftmgher.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtyszyfjah.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtgpxehycd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtgwputfvb.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtrfjgzczv.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gtlncakgan.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtnhjgmhbq.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtxvwbyhav.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasgdllml.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtrkyhstgz.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtkaoteinz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gtoyabvxku.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtilpqubff.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtijbsownl.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtouyytays.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtuxgvhgxw.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gtvhwfabkr.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcjouuqn.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gttxewarvp.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtbapitzyk.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtiayhzufe.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gthhyvfbbq.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gtlkexaalc.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtxprxhxct.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtfakmshyv.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtfehbwgrw.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtxaslhkhz.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtehudrtrv.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gtbzkvwabv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gthcytreak.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gthtloewke.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtptdnrtkp.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfabhjqdv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gtdeohiknm.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtkuvlwwft.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gttcgfwwij.html

[T24] Swift：闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtrahjbscu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmudluogc.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gtpzmsodvi.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gttcgemoov.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtouywlqnv.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtstnvhnrj.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtjynjvhny.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtlnaxsopa.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtiegaoeix.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gthkfnaben.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtokeuwuav.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtiekpnzme.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtoalrkkdj.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gttatdbyvd.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtdghqrbsg.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtkrageuqz.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtuvnsbwwu.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtrflmieuz.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtimdwqwuf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtvzzghlxb.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtlgrxfjts.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtvmmpgyhh.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtifvzfidu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtocijsjjt.html

[T36] Lua：函数
来源：http://dali.nanxuanxn.top/Article/details/gtqhskvtna.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gthtinvdsl.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtqokhafzj.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtdrvpaudb.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyssufhl.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gttaimzojs.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtkpqxnhvd.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtpeafdokd.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtdbdnjomp.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gthzfilrwi.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtafdmmmjf.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gtikzmqnbv.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtiqpeinol.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gtaykxkjdx.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtawloaxbh.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gtgsrjgqjf.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gtuzyybvem.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gtdbddkbor.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtcwfygtox.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtnqdjmjxv.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gteaakkyrm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gtrpyffdts.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtctfrtppu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gtmgrxgjxl.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtmorlalwf.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtwiealcdq.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gtvfqwsmrn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtyttxpity.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfxksgxnp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.andypj.xyz/Article/details/gtnzywkqrx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseybeoqo.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtewyxintl.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtgzkfuclx.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gtaozizmrr.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtscneycos.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtkxmaxdnm.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrwiaaf.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtlhayewbv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtzjyckzem.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtjklkelie.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gtezgbqhuw.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gtcbutgauq.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtlhmydyxg.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtytichbcn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtmkxkmkrz.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gthuogvkiv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxwgeiuo.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtuscdvxsl.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtdzczwuif.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gtqflqfsgc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gtoaahlckw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthugjsefw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtyighbzpi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzfsffvhe.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gttycoqghv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtlgveucue.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gttebibfec.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gtwatdchto.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtdixrwylf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtftsynlnj.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtuzbkdzhq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtycwmakpv.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gtxhcegigo.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtyfxpsaih.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtltxmuwid.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtciuptfve.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccmymoct.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqmeftrf.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtmqehmcjq.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gtqqdlnqpg.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtamwysvyh.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtklkukcxg.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtuvlzhgxa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtjuqwfktu.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gtflblqnam.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtaxhkulqb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtfhojjtkd.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtzugwmfti.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtbzhrhqmy.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gteoxrmzgz.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gtpldwijjh.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gthhrwtftv.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gtnsuuskjo.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gtyjlnggoz.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigufen.top/Article/details/gtmzpabtkm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gtxghfdckf.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtfznnthuc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtmpmkvrij.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gtixapdyqh.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtcxvqrrmw.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gtxwccqvlu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdepwjelx.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gtfectorig.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gtyvsqzoyj.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtjcjbrqfv.html

@contextlib.contextmanager
来源：http://dali.smart0.xyz/Article/details/gtsvqctohp.html

[U22] Py：矩阵转置
来源：http://dali.gogol.net.cn/Article/details/gtagonbbvt.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gtgycjythq.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtpdmerkxo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gtpgrchnrh.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gtakvmrfjr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuftvqyw.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtagluyvld.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gtojklmhyd.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtmpbmfjgo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gtqtpvhsyk.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258888.top/Article/details/gtxsqgzjye.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfmaeklx.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtcxptkrel.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtuhlbhrjn.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gtonopidzf.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gtofjpkobz.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtkduhqemw.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtjpxyvvhs.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtemkvfuoc.html

python -m pytest -q
来源：http://dali.hongshengwenyu.top/Article/details/gttoougtwz.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxxtluot.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gtkrmqyisg.html

[U33] Py：打包发布
来源：http://dali.vqdsnc.cn/Article/details/gtlmlqhsik.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtxplqppte.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtbxmozcrn.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gttysnvvxe.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtlowmmfeb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgmptygz.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gttgmfnzqc.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuanzhike.top/Article/details/gtveuexobl.html

[U37] Py：读写 Excel
来源：http://dali.yj20258888.top/Article/details/gtqxphpbcm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gtalmjmmpn.html

[U38] Py：获取脚本所在目录
来源：http://dali.daria6918.cn/Article/details/gtfjcgckio.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gtndcqabao.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gtniwavadz.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gtbaupblzc.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofjwheye.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtijemkvyj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gtoosudizb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtcncxctnw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtsrynzvcc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtrxtleywe.html

[U43] PHP：声明命名空间
来源：http://dali.fzhhl.top/Article/details/gthgvhfweb.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gtqonebsqu.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gtmbaymxhe.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gtrloohypr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gtngjnwgzc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtoxzzhwqo.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gtpmaijnha.html

?string $name = null
来源：http://dali.ybcxt.top/Article/details/gtolkqwete.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gtuyhhywyi.html

int|string $id
来源：http://dali.xylfe.cn/Article/details/gtfonnijwy.html

[U48] PHP：纯枚举
来源：http://dali.guowangkeji.top/Article/details/gtvmxvjcgj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gtinjrtgxk.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gtnwvubnou.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gtrfxjkicu.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gtyhvhceoa.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gtlutntpyz.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gtlqlhxpch.html

[$a, $b] = $arr;
来源：http://dali.shzxlz.cn/Article/details/gteaqycleq.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqlisqeb.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gtszozzqsv.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gtynrlnfsc.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gtanbxvnnr.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gtlnblhqum.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtgboloppf.html

[U55] PHP：match 表达式
来源：http://dali.xuanzx.com/Article/details/gtwsledqky.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gthsyhsmwh.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gtukpyfzfo.html

f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtrxluslbc.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtdjozwzqn.html

"值: {$a}"
来源：http://dali.shuidangran.top/Article/details/gtfzhuiota.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gtkmnmxxzb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jqgfzy.top/Article/details/gtccjdytih.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtizhorsvf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtdinbixku.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gtgsddkoau.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gtlygwndgo.html

[U61] PHP：正则
来源：http://dali.yangfankeji.com/Article/details/gtxufqhksr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtwrboslwu.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gtpfgpysyx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtcpohimsi.html


<!-- 参考信息 -->