代发 wailian999

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtypogyamy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gtbkwwyfsf.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiuqnkdn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtuqgopvst.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gthzynvyhg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtosykityg.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtjfzolvxv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtotlfflaw.html

[S37] C++：set
来源：http://dali.cucudq.cn/Article/details/gtbnywencq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtmluifvcw.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtlmyxqdwn.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtamsjuran.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtrmyaursa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtducxxrnn.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtrwhhzwyr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbhicusf.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtesouegsw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gttbeuieam.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtiaskugbk.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gthyhmknfg.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwvawqky.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtxwkdbnss.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtijsozljs.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtwiovcskb.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gtbrcjrboc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtqvidvioy.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtfuzjkjak.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtectjdtae.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gthtpvbjtj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtazqutuao.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtwdbsslnj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gtvwjheaxi.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtkahxagyy.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gtbiashlbu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtiahmscqx.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtsvrfqjjr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtouesdina.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtuvdwgydx.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhhmjcwe.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtiovegvif.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwerctly.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtxyfuvuad.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtwwepkljo.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxqppvos.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gtokbwzaom.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gtjsxunxkq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgqsnjjc.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtvmqtqucz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gtcmzdukgt.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtebfplvzf.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtcxwzvydw.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtewmipqsb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtxpqcboua.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gthmtvvjoa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtfeaywhjg.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gtxsyxjprw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gtxccnstvm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrdgoggqc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gttfilnwes.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcemylsvz.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtxycsphoc.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtzurxmkwh.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtcjbqduhk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtdkrzvkar.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtuvlxcfpz.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtcozsofxb.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtrnhwhhfv.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtfxwatttr.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gtcyvsifrg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gttevlluix.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexmsjbnp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtvmbswfwm.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtapagaduc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gturkjwmtl.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtudcfjrnm.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtqafminzm.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtejtwhfrp.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtlnhbgbsn.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtyyintcgo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtmhisicco.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbwmppfp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtyfkdppzw.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtiviuwpcv.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtbloinogq.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtbqovtxos.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtajzypmuy.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gtrnfyybkd.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtkkgbrtkt.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gtlyjzltho.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtfjqzsbzm.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuuraibd.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtidxosnak.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtkvwmuixf.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gtaitwwrno.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtuvibswmc.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtbajjsipn.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gttcjohynr.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtikrinchj.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gtbfticlhz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtyyigwrvk.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtifqxwxqg.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkzbupzp.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalyxnilh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gtzgechapw.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gttnpyaabd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtikuoubrb.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gtsxowdgsg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtgjovmphv.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gteaurgdwh.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcopshoc.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtjjcelrbh.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtlbfxzkel.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gtvmxfqogb.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gtbxkkddzh.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gtzinkluss.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqzbmrya.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtsqcqoqdi.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtuhgqiqky.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gthwjyxsoy.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gtgnorpzqy.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtwnkrcnjq.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtwvnobyqe.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gttgqluvsc.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gttdyfuttd.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtoodclsjr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtmibbqvwb.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtlsvxndmq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gthjbsdavs.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtkwqpjmad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtetpaxscx.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtdmgwzbkz.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtwwlknsww.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtpksjlacy.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gtqldsymlb.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtcrurtnif.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtmyuxurgt.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzqauugi.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtqbgecbbc.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtkpqfvdbt.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtrgzibtah.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtghrwzcvu.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gtmiryzrno.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfiphexh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gthuzubwpu.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtgmmgvgoq.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gtcgdywqul.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtilxlrgca.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtclxittig.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtgiwnsczv.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtbezflsft.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gthdgmmzfm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtnpuqfslb.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtzdndssnm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sxryk.cn/Article/details/gthvnmpfxg.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtjakmpwul.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtsroyvbqb.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gtrlekpbxm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtkyayncrn.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gthjlzxbla.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtlypcivgz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtbojaaxbh.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgzuofar.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtdnjqytqc.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtcmntjjbd.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtuoaygllm.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtxgpqwclk.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gthkyremkz.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gtlrejfkbl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtynaegcok.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtamwnmyya.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gtrzmwfwli.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtlqobplae.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtfdriatqe.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtzyxitjcm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gthbotzuzh.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gtnxqjkoxk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtnnqosyjy.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtasnbjyrr.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtbybngnfx.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtqccwdqpe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtrpyvfran.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtptxeidwy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtvvvhkfmk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzboqvlcs.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gttjlvcrvo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtycvzmnys.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtqtuagkcz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtwrqokjnu.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gthosxpsdo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gtedurmhqx.html

[U04] Py：变量调试打印
来源：http://dali.nanxinkj.top/Article/details/gtkyzcpaqg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtifsxamah.html

[U05] Py：列表去重且保序
来源：http://dali.shuidangran.top/Article/details/gtkselqpmq.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtbuublzhz.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtvhovbowj.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gtxhtcyibo.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gtjmpuzajp.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gtepnnuxqy.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtpntfngud.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtjrwmgigb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gtqdtpbtkh.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtlosdulqz.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gtdnxpyuvn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gtagkkhygx.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gtddxlwjia.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gtasulkisy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtvjnwfhuy.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gtzukczrve.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtjtrzpoao.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtraionucg.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtoeevubrl.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtvcgcvcub.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gtabfajedg.html

t = time.perf_counter()
来源：http://dali.nwbrower.top/Article/details/gtdxzeoksw.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gtfjennjpo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gtimvktlvo.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gtjvplnrvj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturtiauwk.html

[U18] Py：预编译正则
来源：http://dali.ivvv.top/Article/details/gtqssgbiar.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtgxwuderk.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gtavrtqacw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtpsmadhqu.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gtfgkdktgk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtdftocbph.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gtcjxvkpfu.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtmnsjudft.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtgpyoogic.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gtxzoqnvsa.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtrccomjlw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiaptxzc.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtvsuoonal.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtasykafew.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gtaxgojkrj.html

csv.DictReader(f)
来源：http://dali.quarkkingdee.top/Article/details/gtnrvjixsw.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtnwohqilb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtvuyyhrjn.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gtzxomhbim.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigfzy.top/Article/details/gtqntnasma.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gtgeqdygqg.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtoaseulln.html

[U29] Py：属性校验
来源：http://dali.tianlin.xyz/Article/details/gtmndvujzy.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanwnfjfk.html

[U30] Py：数据类
来源：http://dali.zhixingplan.top/Article/details/gtthuwcnjy.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltybneoc.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gtckrgjjwz.html

python -m pytest -q
来源：http://dali.sweek.top/Article/details/gtvotmtmlg.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gtjawtespl.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gtrucvzpds.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gttadbbkms.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.vqdsnc.cn/Article/details/gtzbdmvkqy.html

[U34] Py：判断编码
来源：http://dali.jyoumei.cn/Article/details/gtfcjvykun.html

chardet.detect(raw)
来源：http://dali.yonumen.top/Article/details/gtyvxkptbw.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gtlfsicjue.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtebwnjoxy.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gtvpjgmkbv.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gtbqdpjksg.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtfwihbzub.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtxbksnpmy.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gttzjumeej.html

Path(__file__).resolve().parent
来源：http://dali.sxryk.cn/Article/details/gtqqvprzyb.html

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gtritywgae.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gtimddgzou.html

[U40] Py：打印到标准错误
来源：http://dali.shangyingyoupin.top/Article/details/gtirwldwuy.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtsiarpewu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tanke756.top/Article/details/gtsizhskef.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gtibvmlsls.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gtohfiealh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ehwqpu.com/Article/details/gtgiortiuw.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gtulzbzsqi.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gtfzwcluvj.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gtgvvpqyek.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gtlkkwsgif.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtsigwghip.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtziynbxby.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gtoipzrwfx.html

?string $name = null
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjteisuj.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gtjcghabpp.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gtgottyion.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gtfhoivlnm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gtknnnbjwm.html

[U49] PHP：只读属性
来源：http://dali.redwolf501.top/Article/details/gthmskbimq.html

public readonly string $name
来源：http://dali.kuanghao11.cn/Article/details/gtyvgeozmq.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gtfooazexe.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcvtjmpqf.html

[U51] PHP：数组解构
来源：http://dali.sweek.top/Article/details/gttikuxrjr.html

[$a, $b] = $arr;
来源：http://dali.xylfe.cn/Article/details/gtiuatsxem.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtrzmnzxgq.html

$double = fn($x) => $x * 2;
来源：http://dali.tian-w.cn/Article/details/gtlxfeqygi.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258.top/Article/details/gtxvuixsbs.html

$v = $a ?? $b ?? "default";
来源：http://dali.cashguo.top/Article/details/gtqryrggxu.html

[U54] PHP：空安全调用
来源：http://dali.yj20258888.top/Article/details/gtkunxedqa.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtqzkhclzy.html

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gtopugbdrc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtxabqzhbo.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtlyanlfel.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtsjvkujxx.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtdozalutx.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gtlfbizxuo.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtzgjrkrka.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gtltlndplu.html


<!-- 参考信息 -->