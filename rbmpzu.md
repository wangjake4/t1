代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2fsmgcwxd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gt2plrnmcag.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gt2lqpjjhta.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfwyjpov.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ziafdicr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gt2wnbkfxcu.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gt2thtmbxuh.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gt2tlysijmd.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gt2rfwkbrwc.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gt2ixdpyqwp.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gt2eixgdpfl.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gt2mcfbizln.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqkkyukf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gt2xalicnpg.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gt2hthwagkd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2pkhhtlgh.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2vskbwjry.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gt2mfewsvkw.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2uthdfojp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2tgnxxrvn.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2iiiejbav.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iavffbna.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gt2pgxvwcvd.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gt2foypxqbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2nmpolkgb.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gt2gakisfht.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2dmmrplsr.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gt2uoccwxkg.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpoxxcaf.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gt2htmgmyyh.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gt2mvywmuum.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gt2knwbysvg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gt2rnkqqmty.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gt2brfspivm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2izdzeujq.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gt2ntgnesyh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gt2eifvresb.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gt2qlwwlnon.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gt2oidviwis.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gt2tuvvyggb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2zvzlhgoh.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2pqsylffv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gt2urizhavb.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2lgmztydj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gt2odetnzmr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2vilvzctu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gt2rnekgwhl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gzzwogpx.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2vptdkzws.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2esozvrff.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gt2tpnxpxhd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2vqakyzdb.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gt2lxfbvrin.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gt2cxuibbiu.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gt2gdftlica.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gt2fjvpowtw.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gt2mpkqiriy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gt2iczpohht.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gt2zdwjbeyp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2etkifqde.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2ktthbkqx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2fadrppcz.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gt2gyiiyxcp.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2jikozrar.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ogailule.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gt2jsgtywvh.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2uiovtqut.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gt2honnjnls.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gt2ejqebbzr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gt2wnkeljsh.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gt2qvikorlv.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2nzeqynof.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gt2chlpnfbz.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eiggdvvj.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gt2yqmssvjd.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gt2xfrpwsbn.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gt2tvvsdacv.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2naqqhkgy.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdgqkuir.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2hrspgzme.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gt2grnemuju.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2stsvvope.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlpfgnrt.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dysdmrau.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gt2ruxijqij.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gt2okzvvdon.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gt2wnrtbcil.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2exaemepc.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gt2ckezhdmd.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gt2cccjpjcu.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gt2yjtqevpv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gt2oxwfaldj.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gt2nzyckzdt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cswlmedh.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gt2pxnyigvf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lckhtmes.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gt2omizsqif.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gt2hjuzrfoy.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gt2tbfdjrzl.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hweiwtoz.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2xzhzrwpk.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gt2umoytubc.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gt2nmqzijrp.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2irmrvenk.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fiifpxvc.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnfvbqsp.html

[T30] Swift：协议
来源：http://dali.ivvv.top/Article/details/gt2tbtoxilm.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2woyxsqiy.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2snxkymsw.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2emduskuk.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2mlauretd.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gt2auseeyxe.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2nzoelhag.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqqhteox.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gt2gcdizssl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkzwejab.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gt2eagnmlyl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gt2muvxfslu.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gt2pzhizvsl.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gt2nmpxofvo.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gt2lfafmpig.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxwwcjpj.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2xuatlqwg.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gt2kegxueth.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2ojwjhnlw.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2udwrgkbg.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gt2jukasnmz.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gt2czbvzzch.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2tauxeqal.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2yhfpiiih.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gt2aargqbuv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gt2ydgbuqdd.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2vosnqfzu.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gt2awlavelx.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvlihcjf.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gt2zmpldibj.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gt2ixmyxpto.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlgfcbpj.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gt2ddnjtmes.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gt2jlhomdsm.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gt2xesegyfd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gt2raqvxdkl.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prhtvqyx.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uumtebwi.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2uceudytm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2vjffuhiz.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2cdoqdwir.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2ptvjjsei.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gt2ahvhwrzg.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2nezpadrz.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2vbtnrmyi.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gt2sknqzlhs.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gt2gprtzrws.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2xyragyhp.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2ikjzjfkz.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gt2ssskdzwp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2dbabhnfq.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2btjokgmv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuwriosw.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjuprmfx.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2gvaqzmhm.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gt2ecxagjyv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gt2puouanhe.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gt2pizknxzo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gt2hjnaafuc.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gt2qnoywatn.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2cvpebuaf.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gt2irptqjjt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gt2gwdcusxw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hsigzsaa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulaczqce.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bbdrdwtc.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gt2xwpjtxgv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gt2tlssxebb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gt2bxgomhzf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2aotgxgjr.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258.top/Article/details/gt2jkhhfoii.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gt2buxjcxnx.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gt2gwyzsisf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gt2moofwdly.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gt2umdbliyk.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2wjsysmct.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idtdshaf.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gt2dxvsozfp.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gt2eqekfssl.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gt2jegemszy.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gt2pwfshbga.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gt2zyppdyim.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gt2yetdafuh.html

max(d, key=d.get)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umksyalv.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gt2wuurrozi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gt2pfrbvdou.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gt2urttdxjm.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akbjtyki.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gt2zhaxsade.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gt2pefcixoj.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gt2brqkbtxe.html

deque(maxlen=10)
来源：http://dali.sxryk.cn/Article/details/gt2xpztwpkj.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhvovafo.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gt2qihduvyo.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gt2fdmjgmze.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gt2yvqrogyj.html

[U16] Py：命令行参数解析
来源：http://dali.hammf.cn/Article/details/gt2rgnpqmji.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gt2crrmoucb.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gt2ezlnccfh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gt2olnmvehg.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gt2ooisdfqo.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugxmnjgg.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gt2kcxzvxyv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gt2gbtvdutt.html

[U20] Py：缓存函数结果
来源：http://dali.fzhhl.top/Article/details/gt2ixcnunwu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuxming.cn/Article/details/gt2wjoqtqdb.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvjlcfrl.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xforejat.html

[U22] Py：矩阵转置
来源：http://dali.hammf.cn/Article/details/gt2sixxgllr.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gt2omoolnrg.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gt2uwwfxdof.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gt2lthpalzs.html

[U24] Py：路径操作
来源：http://dali.wangdashe.top/Article/details/gt2bufbajtx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2vurxohsc.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gt2wdbexjon.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuszqsnm.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gt2zbburagk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gt2maeohmlj.html

[U27] Py：异步 HTTP
来源：http://dali.ivvv.top/Article/details/gt2iujpmhcn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gt2lplxkayc.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gt2izzyowqe.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzkgwlki.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gt2xxeepqar.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gt2xdulqwnx.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2ygeawjhb.html

@dataclass(slots=True)
来源：http://dali.hfpthk.cn/Article/details/gt2lnqscntn.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gt2omflzbop.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gt2ybnkjgcs.html

[U32] Py：代码格式化
来源：http://dali.0kj1m.cn/Article/details/gt2nolnzoos.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gt2lhnjtgbf.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gt2shbcipxl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laqqovdo.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gt2flaedwmt.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sitdjgur.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gt2lonelpch.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gt2poaosueo.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2wwstcnaf.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dynjiudl.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gt2wmudjbge.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gt2xcinsgsg.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqxrwnfc.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gt2zjpnxvud.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gt2rptqbgmr.html

sys.stdout.isatty()
来源：http://dali.andypj.xyz/Article/details/gt2lggaxfps.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gt2bhxbucum.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2rqrhyzsf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gt2fedyzghb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gt2jqsujshu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gaohongyu789.top/Article/details/gt2bechjjcv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gt2echxixyw.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gt2rcuyiidh.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gt2xeoqmpjk.html

[U44] PHP：开启严格类型
来源：http://dali.aibaodan.cn/Article/details/gt2pjdmazou.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gt2riotncqb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cucudq.cn/Article/details/gt2sjtklooh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2djucewww.html

[U46] PHP：可空类型
来源：http://dali.jinqigfzy.top/Article/details/gt2hlaaxxui.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqxijbxl.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhglmepu.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gt2dojivfmg.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gt2tvftwpzv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gt2qewzsbum.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrtjtkzy.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gt2ttytlpbr.html

[U50] PHP：构造器属性提升
来源：http://dali.hywenlv.cn/Article/details/gt2equuphcv.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjbrarrk.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkcytfur.html

[$a, $b] = $arr;
来源：http://dali.nwbrower.top/Article/details/gt2jdxqjtce.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gt2yjbegssm.html

$double = fn($x) => $x * 2;
来源：http://dali.sysykeji.top/Article/details/gt2fziiiafa.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gt2ftlrklua.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhiwuduotai.top/Article/details/gt2lizdgjjn.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gt2saloefnv.html

$obj?->method()
来源：http://dali.ydzc1.top/Article/details/gt2mrzsayhh.html

[U55] PHP：match 表达式
来源：http://dali.ybcxt.top/Article/details/gt2gouiuktw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gt2eoomnrbh.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2sdncuztz.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2wpijrbrv.html

[U57] PHP：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2uivlaset.html

"值: {$a}"
来源：http://dali.zhixingplan.top/Article/details/gt2oubimvlq.html

[U58] PHP：数组三件套
来源：http://dali.dashuyun.cn/Article/details/gt2jpdcpkyd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gt2rvucqhpe.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwipfmgd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrkqqhuf.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gt2otthlupg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gt2amfbnpzv.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gt2oxkmxooj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ogdxtbfd.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzewsfro.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gt2pkprlbml.html

[U63] PHP：文件读写
来源：http://dali.zhoulong.xyz/Article/details/gt2lvpbgudx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gt2sgqtpkbh.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gt2uppmavmn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yueranfly.top/Article/details/gt2spnhbyxf.html


<!-- 参考信息 -->