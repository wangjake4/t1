代发 wailian999

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gt2xxmckxqy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2rvmolork.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gt2weerqsvh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2ubcivleq.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gt2fkmrtlsd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gt2lnpvecmx.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2pckbxdgg.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2unfmxzbm.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gt2yzdxczye.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2rffehwxi.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gt2nipzcvmd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2abcqojgg.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gt2ccgoiarw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gt2tjvgbxxm.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2ijohmizv.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gt2vuttkygu.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gt2erqkzzqs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gt2zritrehe.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2uvbpufth.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vffagsmq.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gt2otcnbcwb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gt2loqssgat.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2grgbtzvc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2qzxxujzc.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2dtmajqeh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gt2qtzffwab.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2cpixgqnp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gt2bmcbnldg.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2uigkfidu.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2epzmyqfg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqonvufs.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2hugbetwl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2cwhfuzgx.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2ddwqkrkk.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gt2nmqxhupp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gt2cduzmhss.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gt2tbrxqgop.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwfalazo.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gt2kzvxetro.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gt2lzzwdzey.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gt2rcquxuzk.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2jiwejqkq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2smzhzpcu.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gt2iokibmlr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gt2twuormfs.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuwsvjdo.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2dvkdeuxp.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2xduauijj.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gt2guxflfva.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2yaivvanm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2cjkfqero.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gt2msxmosub.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2cmzuxwgn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vmjcnmca.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2dpoivrwk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmftxovz.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2tvlwxguc.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2lkesjieo.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2ujopvpey.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2oxdjvtwh.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ariegryw.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2fvsdzand.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2tsnjadlp.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gt2cfegoepc.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gt2dicqhang.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gt2rxetdtyx.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2xrddnbgj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2zlsdhhid.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2kwstksuq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2gxlbuezm.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2fpcnaqxc.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2dlzmcfls.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwwcxxtk.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gt2olnvkoye.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gt2tufpofzj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2ehpzzulb.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxhhgaap.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2uyzgueqs.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gt2vwvjjyms.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2gkoiwlyg.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2reqozkhw.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2ykavtnka.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gt2pnvhreeg.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyfbrime.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gt2sapspzda.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gt2pofkxvbw.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2xphzayfo.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2tapufvus.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gt2sbnwbiyo.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkdslfbl.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2zaodstuf.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2clfyfpak.html

[T19] Swift：可选绑定
来源：http://dali.shzxlz.cn/Article/details/gt2kkryoivv.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2jysqistn.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gt2zedajbef.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gt2jdfigimk.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gt2qglfgkxa.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxufikop.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gt2dpvuldak.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gt2khtfpkzt.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2lzfumjjc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gt2xcwefdyu.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gt2spvwyxdb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2gjncqxhb.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvdpnfve.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gt2kwsingzb.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2gazkzwju.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2vcvpsqsw.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2mkqbvpmn.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gt2oxvoczlv.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2ihvhyeeu.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gt2mtqlwase.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gt2sxjxjgas.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gt2qurbjpqf.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2ouoclrod.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbpbyihw.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2iwzygkve.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2hdqqcabl.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gt2navfbsct.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gt2qpkrmlzq.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gt2uyejomyh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gt2bvhrhgsu.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gt2jrxdfimj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gt2bkqfcccj.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2acrdssdd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2nlbpdkaq.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gt2uhtbbpiq.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gt2zbbxhdqy.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2fzlgczjk.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gt2zyqbtkqw.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gt2ueznkinx.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gt2vkigwxei.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2aaysytjy.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gt2shpyalzt.html

[T40] Lua：元表
来源：http://dali.zhixingplan.top/Article/details/gt2qjlfsqts.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gt2iqnrnzam.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2bbshujix.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2xdvfctsi.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gt2ljwgtvcn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2ycusymvv.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2rfaxzbsa.html

"值: $a"
来源：http://dali.xuanzx.com/Article/details/gt2ghbsctau.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gt2wfdbqnmm.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gt2zwztdqxh.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2ggnfbfma.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gt2oqqlwmsl.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gt2fqsntkae.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvqkfrue.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gt2shsajgyo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gt2cpykemsq.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gt2lmiewzjq.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gt2puooqosq.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2retcdhho.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiquttln.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2wllrtpkm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gt2wfmccgmc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2kqsujfyv.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2pdvnyonc.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2exmocast.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gt2pnbagkoe.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gt2lkakfvot.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrpuphvp.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gt2ygxbsmox.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gavropqs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ronkaoug.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2jctdlzht.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gt2cxixeypx.html

[T56] Scala：样例类
来源：http://dali.redwolf501.top/Article/details/gt2nubojodt.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2keufpsgm.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2grtzepds.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gt2ntompurl.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkokwdwb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gt2elhcpasf.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gt2hyvebqme.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tayephbl.html

[T60] Scala：折叠
来源：http://dali.snrcjt.cn/Article/details/gt2aoyejyjr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gt2zgjydlop.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhfysxkq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gt2mxxysqph.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ypkhgdft.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gt2gvfhnfoc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbdkxegy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gt2rbofsvcc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gt2pfsioael.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gt2wethlcnl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gt2onmgullu.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkbfhkrt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gt2xqjvrccl.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycxpnjbv.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbchmsvr.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gt2qlhbpadt.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gt2kdbrojgv.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gt2xrcjgsnb.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gt2gqwmwram.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gt2snaclsya.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocgxzczk.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gt2dospyqha.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgvmpwrv.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gt2oftvfglt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfdkdpme.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gt2rjvloseh.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2hswtrwqi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gt2ihfsnigr.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fefynpej.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gt2agrumvfc.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gt2oflmydet.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gt2pdkdptax.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2qrxsgdme.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gt2fkbfafts.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gt2vuoxwuxf.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2suktemgh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gt2utcuzlou.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gt2obsvbhax.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmpdodmh.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gt2lbsnwzju.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2idqgrapl.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gt2iddioyaw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gt2enpdkhfr.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gt2afpzngol.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gt2cqqhkeir.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gt2xcmcippi.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gt2mcdjkhdq.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gt2xsjhqrmq.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gt2anzbhdum.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gt2jzsnwjds.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gt2aohsxjxq.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gt2gkrnrigo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2fdfvrrlu.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpxlhvvz.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gt2hhvxdyvv.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gt2letbcykr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gt2yzethwdm.html

[U27] Py：异步 HTTP
来源：http://dali.shzxlz.cn/Article/details/gt2mrjqjoax.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gt2zuwwebrl.html

[U28] Py：类型别名
来源：http://dali.hfpthk.cn/Article/details/gt2vvupefbf.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvpyclnu.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gt2djxncbgq.html

@property 与 @x.setter 配合
来源：http://dali.havefunace.top/Article/details/gt2laxxtewq.html

[U30] Py：数据类
来源：http://dali.aibaodan.cn/Article/details/gt2zcvgmrrx.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gt2nyrkylrl.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gt2rdwoaoai.html

python -m pytest -q
来源：http://dali.xziqi.cn/Article/details/gt2xqadfwzc.html

[U32] Py：代码格式化
来源：http://dali.zhengqikj.top/Article/details/gt2wdkijcno.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gt2pmdfgmnn.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gt2mntzpnsk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjhzeqys.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gt2aaoocewx.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gt2arsdfqry.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciccjrer.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gt2tprjeiav.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2lmbbwftm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gt2zikftmig.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gt2vjealhqs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gt2eaefytvx.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gt2wtnvtccd.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrffmvbt.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gt2gyavkqkf.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gt2thvqvbkr.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gt2yiywpjxu.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2kdignbvd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gt2yxnccwsq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gt2cufhtayo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gt2qohuhpne.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.0kj1m.cn/Article/details/gt2donwbfdk.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gt2kflargzz.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gt2sgheitmc.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258888.top/Article/details/gt2tpgjqrwr.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gt2uqdjiait.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yongpay.top/Article/details/gt2vbhnmlmj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2kmvtbida.html

[U46] PHP：可空类型
来源：http://dali.tian-w.cn/Article/details/gt2grsrkfqb.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gt2fibjiwia.html

[U47] PHP：联合类型
来源：http://dali.shuidangran.top/Article/details/gt2lqxxpydv.html

int|string $id
来源：http://dali.shangyingyoupin.top/Article/details/gt2coyufmgf.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gt2stvjkqhx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gt2emhcphxh.html

[U49] PHP：只读属性
来源：http://dali.yuanzhike.top/Article/details/gt2wkslcypt.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gt2hbxocyiq.html

[U50] PHP：构造器属性提升
来源：http://dali.wangshuangyany.cn/Article/details/gt2rapouofb.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2zfcgvopk.html

[U51] PHP：数组解构
来源：http://dali.cucudq.cn/Article/details/gt2yvzyixoj.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gt2gdycgzor.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gt2offjplhx.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gt2lutimsxi.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gt2cetylnrb.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gt2gnjoyynn.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gt2xfnaqtwi.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gt2cdntmvsz.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gt2rvjnbnog.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ybcxt.top/Article/details/gt2srwyalci.html

[U56] PHP：命名参数
来源：http://dali.yj20258.top/Article/details/gt2fmborigm.html

f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlsrtjmo.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2qixhapcc.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2vwzyrxiu.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gt2qhjruxes.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gt2hkfrskuh.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gt2mzhujbnq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2dhaatugd.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gt2ablfgcvl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gt2yqdoxust.html


<!-- 参考信息 -->