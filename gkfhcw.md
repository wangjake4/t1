代发 wailian999

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtiezjjugt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtmanbnbyz.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtydoxltxj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtkdazurhu.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtpcbbjypo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtztuivgoz.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtevppvhfb.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtiwwjynmp.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gthvemtczx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gtkngpxwkb.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gtkzhpbumj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsybkopjl.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gtjqhwlfnk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtzilxamor.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtebiiuymm.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtahkmlulq.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gthuqhzpul.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtdgpejooz.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtxsevzsmn.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtccjfccem.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtkabuvyjr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtrsrnhszk.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gtkfkhsvjr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtjqnrkmqe.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtgwsfcsut.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtsuwuyvvw.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtgpeyzfhp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gtdbhgxvwf.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtwtmzacvm.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtgyxoxrvi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtvwnmjrir.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtuxotkfsr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtkbfgeuim.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtjazpxmfh.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtatqofirs.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gttxgxxphg.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gtiaqzynoa.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gtufbbabzy.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtaawelzmi.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtozgepjah.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtvnkjfvsq.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtqqjrcnrw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtsemuzftv.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtzuursbjf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtmesdsifg.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gtrobiqfcu.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtcrbyexnm.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtwjpcrbkk.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gthzjonaos.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gthbskethh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtcoidpuds.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtycoxzagy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtmdjwdvcc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvzglpsir.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtmrhipxzj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkfqubjmt.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtsdsmxmzv.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtfwnbpkgn.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtpybbqlha.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykngencq.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gtiaxatdbm.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtquxunncn.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtvyzqzoof.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtzwwowxpe.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtykrapfrf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gtugwazbsb.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gtgflfdlwg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtslglglcm.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtvnnyqevp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtjwmuojxy.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gtigfnaask.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtpicnomrf.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtxtrkxzfm.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtgfnkytwe.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gtfxlrrhwv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gtcrkndlyx.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gtpicsgddh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpriuhuv.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtkrmmoico.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gtogslrrlk.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtmelzgqgu.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gtmmhkafzt.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gtholdxxtj.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gtyyujjgim.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gtlbcumyna.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtvfaysdwv.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtvgfiywlb.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtveajwrnp.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmgkqaso.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtnhahfghe.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtziseroct.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gtocsvqwtp.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gtlwakmdxg.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtonnbrofn.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtqwvbqhnh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtqsqbozfw.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtxmaxsfdh.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtfkcnesdc.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtpxpxblaq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtnpohbuau.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtgmbrzwrb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtdrjwyyqe.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtrgvoqzqv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtmmvhwbqm.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gteoeksanw.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgayerjjd.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtofiwxqlz.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtohkwekrh.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtjtzbilth.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtqydqmvfz.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtzvbpcdiz.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtaodldxna.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfcphrgq.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gtjxonsjpa.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtejdgntav.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtcadeicwl.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtgvhbmkeb.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsiacrhm.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtncozilcs.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtlesmtcsv.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gtyutdgcmm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtgvkdbptl.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtskygvoyy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtofuqxgbv.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtwfcyfqzu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtnlpnyhid.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gtdhtsfdre.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtbzmkjqqw.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtjqcnuslg.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtdyysadao.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtbvzrfyiz.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtyxfovpol.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtbpnewlpb.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gthhplmdvu.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtfkoanpdr.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtjtkxfhki.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtdktvcmkz.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gttjoyywht.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtonwgqiyw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtztwzetzn.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtactnrchz.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtfjuqiplj.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gtqywrgzuj.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gttvepnkgv.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtpgzzmdqg.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gtmjlzezud.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gtgszyhjij.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxzjtmdek.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtcokbzrgx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtydjtxnmd.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtqdtylbad.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gttlqqkdmg.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gtterqpzvx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtgfbookcu.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtludrrzhh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvllacdzq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gtiqiumcje.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtasiiehii.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtyzkwvfkf.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gtgbiyqpex.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqyxstof.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtytyievvw.html

s"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtqzfuvgjl.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gtdfvclesa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gtkqwdegsb.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtzqxtxpgt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gtyhpgfhnw.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtotdfsqyc.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtcvmhxhwd.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtjegfdtmd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtwptzwxfe.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtdtdazotr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gtcbhdhump.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtvqzxovpp.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtogzbwcez.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gteiiydown.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gttsnbeavo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthboheomx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtnmobdrng.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnvuaaumy.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtcxazgufe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gtmvycixbv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gtgbnlcenc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtyepbaock.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtycgazlfd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gtyvodvsja.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gtwjdgowte.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gtlqeqlypo.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtpovldnai.html

list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtwinplblp.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtywbwjaqv.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtvtsnuxvr.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtenyqinxv.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gteozaisux.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gthrqtkwmp.html

[y for x in nested for y in x]
来源：http://dali.zhoulong.xyz/Article/details/gtalrgjhnp.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtwwuavxjz.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtudzadqzu.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gtpowzlnmm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gtjkyolfxa.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gteoqlzhgv.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gtjxagcoac.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gtzcbiyjzw.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtphpjkbls.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gtluumrjmq.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gtademtmpe.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtmyiqijgf.html

defaultdict(list)
来源：http://dali.wangshuangyany.cn/Article/details/gthdwctulh.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gthrrhushv.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gtdmfwqgxj.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gtucsbxazs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gtxiypmqfn.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gteubpxsbg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtgrsidbnr.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtbkncbqgb.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtytkjmynu.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzhzkabu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gtydkkjosg.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtbbmttfzc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gtutqpcdfk.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gttxpvpzor.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gtknmjasdl.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyeqjygj.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gtqnaaqdmp.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gturwgljkk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangdashe.top/Article/details/gtzkeblqsr.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwclncqs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtyfkhpswo.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtssvzdjse.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtphoyhdyx.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtkyeoitze.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gtdktuplhw.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gtqqpegerk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gtpreciewk.html

[U28] Py：类型别名
来源：http://dali.tianlin.xyz/Article/details/gtipfknnop.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gtlywulbgf.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtgdqhdnuf.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtzsalcfof.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gtonjclxeu.html

@dataclass(slots=True)
来源：http://dali.yj20258.top/Article/details/gtutwpgwad.html

[U31] Py：单测
来源：http://dali.ivvv.top/Article/details/gtxugmcqkg.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtgavlfkne.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gtmdhwcedu.html

ruff format . && ruff check --fix .
来源：http://dali.mhx1999.top/Article/details/gtfvtorlol.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gtfrombxgs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pycfn.com/Article/details/gtkwemhbiv.html

[U34] Py：判断编码
来源：http://dali.wangdashe.top/Article/details/gtwlfogztw.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtdfkgmjhw.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtfzntepua.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gtimwmjiyc.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gthdygjnvj.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gtnnhgpoht.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgpmwejl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gtfsfehigl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhengqikj.top/Article/details/gtncfsieil.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gteynxobgu.html

[U39] Py：判断是否在交互环境
来源：http://dali.sweek.top/Article/details/gtdlvnkdgp.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtyigczllc.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtnpzzccot.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjykxdrtx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tianlin.xyz/Article/details/gtroqrsufm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gtdxdsgoyc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gtyaprxyzp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtcoziwkgl.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtmryyoazr.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gtuqtodegj.html

[U44] PHP：开启严格类型
来源：http://dali.hnqzz.top/Article/details/gtobztjlxk.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gtfuosiiwn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gtueesamzb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeifsmqi.html

[U46] PHP：可空类型
来源：http://dali.sweek.top/Article/details/gtuiqjploe.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gtzatevatu.html

[U47] PHP：联合类型
来源：http://dali.xziqi.cn/Article/details/gtjrqmfeyx.html

int|string $id
来源：http://dali.vqdsnc.cn/Article/details/gtpsmzwbeo.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtocoasknq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dianchejie.cn/Article/details/gthzicrclw.html

[U49] PHP：只读属性
来源：http://dali.birdmap.top/Article/details/gtetnrnequ.html

public readonly string $name
来源：http://dali.haohaochexian.top/Article/details/gtqibcwfwq.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtewuqotjb.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcgwrpsed.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gtkbrzgapi.html

[$a, $b] = $arr;
来源：http://dali.nwbrower.top/Article/details/gtebnzfazl.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtttkceiqd.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtiuimusbg.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtjlvjttqf.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtatkjybpn.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gttybrnefx.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gtelqmeres.html

[U55] PHP：match 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtiyaapuib.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtajamnrht.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gtdzwgeepx.html

f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtublotilo.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtalyvnsnw.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gtpgeoqtjf.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gthsilvvfw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gtwzuitzen.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gtrkbwifgj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtlharcyql.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gteawgroce.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpdbctkg.html


<!-- 参考信息 -->