代发 wailian999

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2wjazuywa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2rvymbvbw.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gt2gskirsia.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2zfdwbqza.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2vhwupzbv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gt2akwiwfrz.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2qlmxwlqx.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2gqstsuou.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gt2iomuqznu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2qbhaokja.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2vzpxvqmd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2nxfzbwvz.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2dyaoqwhm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gt2egfrrvxc.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gt2tthfqnfi.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gt2yujyjhck.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtdtmkrt.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2sqhwhrcn.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2koolizlq.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2tswvaldj.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gt2xvetejpa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gt2vwrvwhme.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2mqzgrvme.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gt2wyanmwfi.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2fzfyxowx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2pleirxun.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zyaanvly.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2djbiibky.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2womblufp.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gt2qctgypep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuucxkm.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gt2udtvugla.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2jampmgcp.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2nscttpmx.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2wfaomloe.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgtpfvak.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gt2xxmavsta.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gt2ygymrwua.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gt2svnzholo.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2mxgsnape.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lryymboh.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2pcklljbj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwvmegwv.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gt2einrfblw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2svzxvqyv.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2drzdqhsb.html

constexpr int N = 10;
来源：http://dali.xylfe.cn/Article/details/gt2ufcvdyed.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2eivzgybt.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gt2miaxozqo.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gt2zksbhixi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gt2nksahpis.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2ozkftjlk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2cyhssupc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zejzcoad.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gt2ujmxsnir.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2nhryktqa.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2qskubphl.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2iqyliutc.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gt2tzgvmrtw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gt2nprvzxsr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gt2zkjppbto.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2jtvhbljx.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gt2bavbqhvt.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2lxfgakqn.html

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gt2aaaarjsc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gt2akesdtdc.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txoiklad.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2jjvlmeni.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2oyejhpeu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2ftcjejpq.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2ohbcbgrk.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2pyhhpuiy.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gt2kpehokbm.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gt2dljucprg.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2nxonymcs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gt2ozpgfaax.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpnzveod.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gt2ebhzolbe.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2hresyotk.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2csxzkypq.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gt2wgyzsush.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gt2potoafpa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbwsglw.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gt2libdnvzz.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2eutircud.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gt2fmgteiua.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2oxenlymb.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2zrwcqdru.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gt2whsdqpjn.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izacifqs.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2oqlxkauj.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gt2ypmhswwu.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gt2oruisdpz.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2egzqwqoa.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2irpxdkoy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gt2duvhuctz.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmwybgxq.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gt2txitxxyo.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gt2fejqiqex.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gt2hpofyokn.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gt2edgdyjxt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2dghqfdua.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gt2juwpdycx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmjubibw.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gt2riqugwbr.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2perykdwh.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2ihbkgxhi.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gt2hbcyhnhh.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2xpqpeclj.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gt2aglimnhg.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2xnkxvrjj.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gt2zhdibndl.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gt2jqwufpdw.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gt2lrpgskvu.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gt2ehdhwbkj.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gt2tzxxkurz.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2alvvnhyv.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2yqkwwuks.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2gxtksdsy.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2ioycunvo.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gt2nosdgpxc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gt2efpixxqj.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gt2pxrtbmit.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gt2fmjsthaj.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gt2fpvsayca.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnqzz.top/Article/details/gt2anumgjop.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gt2nzhnxbjr.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gt2kgazqedw.html

[T37] Lua：字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2addwhact.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gt2csvikerr.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdlrtjmd.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gt2qdgaaicj.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2nsabokkh.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gt2nvtseyqr.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gt2unuvfddn.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gt2yrgebnrd.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2kcutepqd.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gt2hwevdqmb.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gt2fyjqdbph.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gt2breegrza.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2okqzftuw.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gt2fllzywcc.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gt2caidafcm.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ofktjkbc.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gt2jwfaekwe.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gt2nxujisgm.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gt2exwjnnln.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2hgmkaioi.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gt2clyycvqd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvopdhut.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gt2oriawyba.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gt2molbisvc.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2xkzenqdy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2wkfstral.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2wnjcvimd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gt2ckfnpopj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2kykdtrnc.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2uocmcdcd.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2euuqatxt.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gt2kmjicavv.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2barlgnvd.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2cvtsnwrm.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfmsafdd.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2dioeyhdk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2qkridbxk.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzkaruiz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gt2hkmqvcgq.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gt2kjwjtbpg.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2mkrjujbw.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gt2frkfdqou.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odvnbdbx.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2dpwxdqnt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gt2sagywcod.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gt2uvkifmqi.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gt2xlwekuyk.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2hrdbtmhd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gt2kvpyewpa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlrrfsxw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2ensqrjin.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2njsjzlhc.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gt2msvihmtu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gt2plsbmuuf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nryqbtze.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2auxunoxp.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gt2uewgqotg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gt2jilfscmt.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gt2txwvmdkt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gt2yurndqlg.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gt2vcqtsdlk.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2omznwyvb.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gt2cwumsyns.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gt2kkbkoumy.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gt2chvvdfvv.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gt2yqjjtkih.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gt2lpmlauia.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gt2gizwyjil.html

[U09] Py：字典取最大值的键
来源：http://dali.guowangkeji.top/Article/details/gt2sykjzcte.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gt2qjnfniab.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gt2pzhjwybm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gt2xsisahrx.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gt2zaxlipuv.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gt2yxpupjrd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gt2flrhihue.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gt2qnbwhggl.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gt2uksgcwax.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gt2rwzlzjsu.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gt2kzupilvj.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gt2smxrdbwu.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gt2ljcxvdnp.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfqvjgie.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gt2imvwhtnv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gogol.net.cn/Article/details/gt2qljkosiu.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzckkkev.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gt2rpdgoqtx.html

[U18] Py：预编译正则
来源：http://dali.yj20258.top/Article/details/gt2lmdumuea.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2kfrbzmlr.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gt2utynpled.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gt2wrqgebsf.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gt2ugagcvqt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gt2krzxrhrw.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gt2lroyvskz.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gt2ypzwkqgb.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gt2pigjtgpc.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gt2dzbyjsrg.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gt2cqnlawcq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mysdqawm.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gt2ovblgyhw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2wuuhzkic.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfwweojn.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gt2sqoqylbx.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gt2qpugltcg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnhcfalr.html

[U27] Py：异步 HTTP
来源：http://dali.nanxinkj.top/Article/details/gt2phvfosxw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tubqqmlw.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gt2akqhxnwu.html

UserId = int
来源：http://dali.havefunace.top/Article/details/gt2mblvmclu.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gt2qtdupiov.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gt2rcyynsva.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gt2epynbsug.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gt2bpgvdiuw.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gt2etszqmsy.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gt2runqwtwd.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gt2adyrmjej.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gt2onwcmhpk.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gt2duozauze.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gt2vvlcwfpi.html

[U34] Py：判断编码
来源：http://dali.chenzaomai.com/Article/details/gt2mipvympi.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gt2awyrryus.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlejegz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gt2hhhctiqa.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gt2dbrigvzl.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gt2jbybuqpg.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gt2hyxktwff.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peidvipj.html

[U38] Py：获取脚本所在目录
来源：http://dali.vqdsnc.cn/Article/details/gt2hzonpeyb.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqzkrpkw.html

[U39] Py：判断是否在交互环境
来源：http://dali.cqqwz.cn/Article/details/gt2jcojndkm.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gt2wpjlxmcb.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gt2vxrqybjm.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2qqwrnscx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gt2lxtwqkzf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuanzhike.top/Article/details/gt2bztjyrgr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sxryk.cn/Article/details/gt2bigtoweu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gt2magfdsgv.html

[U43] PHP：声明命名空间
来源：http://dali.bjfxy.top/Article/details/gt2xkjoojow.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gt2qwncikhm.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gt2qoqnwuxk.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2zkirnyvn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gt2rllguiqs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2vnfvvtje.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pixraqsu.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhgjgpcn.html

[U47] PHP：联合类型
来源：http://dali.gzhubu.top/Article/details/gt2uhlwavfp.html

int|string $id
来源：http://dali.jianghu66.top/Article/details/gt2iunwkdtp.html

[U48] PHP：纯枚举
来源：http://dali.aizwys.cn/Article/details/gt2kgnsxnev.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gt2grspuqoh.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gt2ntfglfjy.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gt2igxgsztp.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgfzy.top/Article/details/gt2jdothrtd.html

public function __construct(private int $id) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhtlvaol.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yajozktd.html

[$a, $b] = $arr;
来源：http://dali.ivvv.top/Article/details/gt2csuzfbqi.html

[U52] PHP：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdndlusz.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gt2pszyiert.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gt2umiwkpcx.html

$v = $a ?? $b ?? "default";
来源：http://dali.havefunace.top/Article/details/gt2jjgqwfhz.html

[U54] PHP：空安全调用
来源：http://dali.tian-w.cn/Article/details/gt2damimgug.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gt2sqmmexwe.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gt2lsnnobwx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2yzxlpaxo.html

[U56] PHP：命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyblkwbp.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2wwvjxxeb.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2sabdfzqk.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2onogyxhk.html

[U58] PHP：数组三件套
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xclkojjm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fengsongda.top/Article/details/gt2dlxhzukw.html

[U59] PHP：自定义排序
来源：http://dali.meibo888.top/Article/details/gt2vnjpixow.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2ppedompp.html

[U60] PHP：JSON 编解码
来源：http://dali.hywenlv.cn/Article/details/gt2lxwgljzw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gt2pciqrlwk.html


<!-- 参考信息 -->