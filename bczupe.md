代发 wailian999

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtbeayvdlj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gttavgcqvr.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gtogxieppe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtcssejohh.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtnfymeuvh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtuaahfjkh.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtwmlfvgfy.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtanroredc.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtrgfieega.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtlsilagzr.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtjnvkmhqd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtvcvbmigd.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtedfklffs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtstdfxdjl.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtqyihtxsm.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtmbpcmbux.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtkmzkgtqo.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtzgmewane.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtxjceujcr.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtrrmbgypk.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtjumoltcr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtnvxdbzgq.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtzqcqvihl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtyeshfnsa.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtrdssqsje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtqoqnisvr.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobtheqtu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtvkiasdsp.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtepzexmyi.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtwbpyfhcd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtmoqxtbuc.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtuxkwbpiv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtmcakicuo.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvuwkuvs.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gttonpfkja.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gtotwhzadw.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtsrstoutb.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gtikhqrysx.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrofekjq.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gthdwgvoim.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtjosvmqnc.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtvhwwjdkw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtupddzymd.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtqbtakjnm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gthpmcacie.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gthndqjsup.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtcuuwwhum.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtuzfoerjb.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gtaielkqtp.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtopbyiyfm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtcnbysydn.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtqkmuxdiu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtowuimjyz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbqjqgzil.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtxuegvslq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtinxtaiyp.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtrteakyic.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtixsltdhp.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtpcljjrdp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtzxwhiqjn.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtnkdjenqc.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtrlquwsrb.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gthmrxmdvb.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtecljmpeb.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtpiqjruxj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gtdhekteyb.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtnhtkwmmg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtzevbuvee.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtimysgzft.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrcgpewy.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtooticqiv.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtljqimato.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtrciailob.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtyihhukuu.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtayqsfkvr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gteepjipyj.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtnmohnqrg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gtmzljertl.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtybyyqodr.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtpujynvmv.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gtpupgrnke.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtwkdoikvz.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtjoyxalja.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtnerjwnlh.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtwumivxfm.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtncvsfqrm.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaywjvkok.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtzwzecsda.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtrlvvblaa.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtqjamqlmr.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpynjmvgp.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtpuxkhqap.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtummehohm.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtpiewxvrr.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtciqujent.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtyqlnmhbu.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gtjnkvyjie.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtijtiksce.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtnqyxwlqy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtyyxtjsmn.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtzhcitbfm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtcrzelptt.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gtgdagvbjq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtdouzbrep.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gtnfeuaxnw.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtndtctasg.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gtkomakoyg.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzzscebg.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtruzmudxh.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtnvfgsoto.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtycvsnmnm.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gtbqsmdhxl.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtzgfhowqz.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gtdntxinom.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtcmakbutp.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtcratjogr.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gthhltpwco.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gteaveflsd.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtivaywelb.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gthkbpqxds.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gthbobfzqq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtklweskyd.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gthdqrhjqs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtiubynjnr.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtcqddknyw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtgujsmtre.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtsbpoiljo.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtkwamyktc.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtbuijbahr.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtfscfbtzy.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtimqdmuga.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gtrfqziglv.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtljsbrijm.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtdggubpue.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gteyuzfswn.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtaczwskia.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtmccrphhf.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gttbpgkniv.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtsydbagzy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtntbgkiec.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtebxpkfti.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gtkurugedq.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gtidhfqnnv.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtnhyjeuuo.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtsdfsznhp.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gthtptjcij.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gtgmphxwie.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkqkjqmqj.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnplwyce.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtdaaeiyet.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gteksvwsjf.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gtwtsyizxa.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtctfzicyn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbbtwsar.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtdvtobdbf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtejuuajri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gtsptktcik.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtopiszask.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtomylipnl.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtghccpiiy.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gtlnexdtjh.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gtcpzkgdhb.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtvesbmaty.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gtategrmtb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtcbankutw.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtnypafpuw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtijsliwhj.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtvjsruacl.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtnugcsobv.html

[T57] Scala：模式匹配
来源：http://dali.tanke756.top/Article/details/gtoeaucgbi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtpdqpyqzx.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtpflvofky.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gtutvygdqo.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gtgcywumrk.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtxdhdxqse.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtjhvtyxru.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtyyasrwdj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrwofoezv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtqzjzasqm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlkgdajzq.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gtmhcmopmh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtexdtvira.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gtkyvdrqro.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtnydytzbp.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtlbrgpdzb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gtpiffhqlo.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtkechxmeq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gtnamjewug.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gtlykgntjr.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtbzmckugs.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gtjesuwyyz.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtklqeekcc.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gtgcluirza.html

{v: k for k, v in d.items()}
来源：http://dali.smart0.xyz/Article/details/gttsnomtbp.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gttppayksl.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtjesqbycb.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtxmbdesqo.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gttytfvjsf.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gtiegbercr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtrcsshrzj.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajmqkzzn.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtcpkkgvsc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtsbyleliq.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtrhrnuqvi.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtrbruymow.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gtztjbpvqw.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gtopgolxru.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtirujmdxa.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtgeebriid.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyyujuki.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gteiubhkru.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gtcswyoewm.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gtdpdlvdzs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhmbqgde.html

[U18] Py：预编译正则
来源：http://dali.fzhhl.top/Article/details/gtydbaqife.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtudfqkgfb.html

[U19] Py：正则替换带回调
来源：http://dali.aibaodan.cn/Article/details/gtotkvmdif.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtbifuysdk.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gtmavonhyd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtxaobchhm.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gtequpihru.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gtvqkymhav.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gtsezxmjgf.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtwkeamicj.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gtfweqrcwv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gtcseoanle.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtaksihohr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtawfbzthn.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtzwrlsups.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gtmhffymgt.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gtimobphsj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gtnvuedetc.html

[U27] Py：异步 HTTP
来源：http://dali.sufxvd.cn/Article/details/gtjmjscnlo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnxiangtu.top/Article/details/gtktnlnlly.html

[U28] Py：类型别名
来源：http://dali.nwbrower.top/Article/details/gtddopggqx.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gtgsumxgkc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtmghtdrgk.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gthhtfqvds.html

[U30] Py：数据类
来源：http://dali.sufxvd.cn/Article/details/gtrayhphbv.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gtvsbuxvqd.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gtnwuwpbqt.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtnndncshh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gtlquvamix.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gthaqabcyo.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gtmamjcvqt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gtpcztienk.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gtkanqoarm.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtfysukhez.html

[U35] Py：发送邮件
来源：http://dali.dashuyun.cn/Article/details/gtbltkexis.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tian-w.cn/Article/details/gtxcbmqwjw.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gtjeyrmysn.html

schedule.every(10).minutes.do(job)
来源：http://dali.ydzc1.top/Article/details/gtxiktfmwo.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gtrzcigvug.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrcgymgv.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtgxonrjtj.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gtvlnqtoig.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gtvxqzchpy.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtnykqvvrw.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtblshjmjm.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtnbhoersb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtewnbwpvd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gtytzrnctk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtgohescco.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuttvzsll.html

[U43] PHP：声明命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkurvjpfd.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gtunkwiwoe.html

[U44] PHP：开启严格类型
来源：http://dali.dashuyun.cn/Article/details/gtugvylhcf.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gteciovbrc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gtvaezayqf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtoprkvbje.html

[U46] PHP：可空类型
来源：http://dali.tian-w.cn/Article/details/gtghgknjev.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gtjappdfhj.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtmyplafnr.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gteracntkr.html

[U48] PHP：纯枚举
来源：http://dali.haohaochexian.top/Article/details/gticmimryc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gtkyvykyqp.html

[U49] PHP：只读属性
来源：http://dali.haohaochexian.top/Article/details/gtvkggwwva.html

public readonly string $name
来源：http://dali.xuetiantiany.cn/Article/details/gtaxsxlijk.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gtvqbrrnvm.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gtbskircvf.html

[U51] PHP：数组解构
来源：http://dali.yueranfly.top/Article/details/gtoxfobemw.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtevmblabd.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gtzegdaovp.html

$double = fn($x) => $x * 2;
来源：http://dali.xziqi.cn/Article/details/gtrjyxhukp.html

[U53] PHP：空合并运算符
来源：http://dali.aizwys.cn/Article/details/gttxihzbki.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gtaxhzssbu.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhqosilf.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gttynquouh.html

[U55] PHP：match 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtxqsqcind.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtdeqvhxrf.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaczqfzq.html

f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtlglpxcsi.html

[U57] PHP：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtupfzfhca.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gtcpzfqshk.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gtlirzpuvz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtferxwjyn.html

[U59] PHP：自定义排序
来源：http://dali.hywenlv.cn/Article/details/gtwmprvizq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtqkdlycco.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gtwcsphtuo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtlfzgllna.html


<!-- 参考信息 -->