代发 wailian999

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gtntkmyfoq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtvjrmduej.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtathacctu.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtttcnpylg.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gthlxpupzk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtdkomyogm.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gtibbassup.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtuxtlfpsx.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gttqxhzakh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtksuckyiv.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtvliljhia.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtpwkkmtwa.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtkzjyavra.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtwvbiqcan.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtneftpaey.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtpwengahq.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtfjcslbcp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtxhkxtlor.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtskdtfajf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtaqsmazqc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtxxwdqmlv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtubnbhhrm.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtrvawqjsn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtrwkjorjn.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtzkxblyrf.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtxtgctmbs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtbgfqmlhl.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gtftwitmbi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtloudxceo.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtepiznalr.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtbkzqdvvk.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtrzhmrqvx.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gtowprlfrf.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpwlvehs.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtqzutdlwa.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtimvfljwb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtgnbsbusx.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtijifttgk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtnbddakcm.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtilpvicsn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtzcctovdq.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtalzhvxlo.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gtubykshna.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtwnggtsgh.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtrrztteqo.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtnnyhvsck.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gtlrdnggcx.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtmpfrkiwx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtfrvztith.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnrwoqykh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtcqxiwpgj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxzznimp.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtphgwhpvj.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtfpapzcfo.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdmozypxs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtxbmzvnfd.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtsmevtppw.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtavfruzho.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gtmdxjrieg.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gtjxiqixym.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtbeiscshw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtrrmzqegb.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtufvlviaj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtpuxuvhvv.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtxypybdfr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gthslquvrd.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtvytybnbf.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtjcrilyek.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtdkmzbjxg.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtybyqpmdc.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtnrvxitpj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetmbynjz.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtqyegesvk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gtarsbcfoc.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtknjyoaap.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtstiaacfq.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gtrgfjmsel.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtfjncsnbm.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gtongakfla.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtdyqfrgbc.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtzysxqwtz.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtsbopqifx.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtwevtnivf.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtqpghpoeb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtfjwbsxol.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtlmlexpfb.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gttyibwdce.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gtdzwyclsd.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtkyszrzjz.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbsejckc.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzsflyyr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gthdcoioaq.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnuqthcb.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtgrjcaxdq.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gtcwgnjoiu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtjkgmylqu.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gthpdzgoqk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtqhvvgqdc.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gttyxsrlna.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtcfipinnm.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtagpjaicv.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gtiasytasf.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtlyjtdvwt.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gthzuulajx.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gtdauplcys.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpujkfzzk.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtdgtespxd.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoocmynmt.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtkxflumcf.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gtvatrmsoc.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtibzrxdyr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsdlrebs.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtvganjtqq.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtukrgmbce.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtrqwlcpir.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtmwoyqukt.html

[T33] Lua：表（数组）
来源：http://dali.cdnleiting.top/Article/details/gtnpjuehyt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtlclizbqt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gtskximmcp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gtgroqsqyz.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gtikgabkvk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtmlvvkizo.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtjtyhdaej.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtmlqsrtbp.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtzyvjctla.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtivcvgbsd.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gtvgmkkrnl.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gturyjiqgm.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gthrnhxzsm.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gtgbqndgdq.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gttytdnctj.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gthzisyyly.html

[T41] Perl：Hello World
来源：http://dali.aizwys.cn/Article/details/gtaurcnagw.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gtzvlluzvh.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtsqvinuns.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtwplyaptn.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtebaxmtjs.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdbcwckv.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gtzocrnlcu.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gtllojwudj.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtuwhdclev.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbqgpfjwa.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtvgasxilv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gtephosfeo.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gtdxxorndt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtyoopzmzj.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gttkiqzslc.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gtypvtfuis.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwcxdewrz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtmyfjemaw.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gttdcalnfp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtfxfxzine.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcjhawpex.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtfchxponu.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtjaldthqs.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrcducvk.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtkyujevam.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtgujhigqj.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtfaqyzlbx.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gtskqccijq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtfjrlkibv.html

[T55] Scala：集合过滤
来源：http://dali.yvedp.cn/Article/details/gttzdtpoto.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtrrjbxrhu.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtuqgcoyrj.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gttgrscijo.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtwmbnznon.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtthoumcxh.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtnywkqibv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtvkvunnhe.html

[T59] Scala：循环
来源：http://dali.yj20258.top/Article/details/gtrlpllypj.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtrgwrgwjc.html

[T60] Scala：折叠
来源：http://dali.cucudq.cn/Article/details/gtpqukrbaw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gtmuputilo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkmdesaur.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gthlzoibav.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlwwokaqp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gtujpyqgoi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrusdtfi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqmelbts.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtluajhort.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtucybutuj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtwueycqgx.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtuqvbhnrv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtjxqlmswy.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtkrnejskj.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtlqavfxcq.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gteppqvops.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtucjoxlrp.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtthopvhpq.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfovxrmx.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gtyjvgrood.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtcrutckjz.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gtrzehhjip.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gtmaxeysox.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gtcxiakyoy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtiauyxygz.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtozsflzrq.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtpnqgcsax.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtpanbujel.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtdbkthxoi.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtrtjyckxx.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gtrwrtlhuw.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtokmuilvp.html

defaultdict(list)
来源：http://dali.fengsongda.top/Article/details/gtjvxnjtbr.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtbebhlfzv.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gtxlqopfwq.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gtlleuqxph.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtawzkbcgc.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtojitghin.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtovmbusqs.html

[U18] Py：预编译正则
来源：http://dali.shangyingyoupin.top/Article/details/gtgnprtibb.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtbfjxxyft.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnagptsp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruorsujx.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gthqviocth.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gtskczkxjo.html

[U21] Py：自定义上下文管理器
来源：http://dali.xinyue.icu/Article/details/gthzulnasc.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtzmgiyjbn.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gtvbugrkvn.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gtkipueikz.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtciuqfoph.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtzjfxybcq.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gtetrxzmle.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtydvxukom.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtnyifbrdy.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtoxqumfdp.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gtnsnwirgx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gtmdxmmele.html

[U27] Py：异步 HTTP
来源：http://dali.gogol.net.cn/Article/details/gtruziponl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj202588.top/Article/details/gtsavsryxv.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gtyolmeagf.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gtuiydnuzl.html

[U29] Py：属性校验
来源：http://dali.gotoacloud.top/Article/details/gtmiajrjlk.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtzqdeyibj.html

[U30] Py：数据类
来源：http://dali.chenzaomai.com/Article/details/gtwqdqspve.html

@dataclass(slots=True)
来源：http://dali.daria6918.cn/Article/details/gtcwentvoc.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gtpeeshusg.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gtalvskrtt.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gtfdilapac.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtepnyprvw.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gtciuutljq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gtzjtiyhan.html

[U34] Py：判断编码
来源：http://dali.redwolf501.top/Article/details/gtertodcfy.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gtoorsylrf.html

[U35] Py：发送邮件
来源：http://dali.c1oappe.top/Article/details/gtpmxwwwqx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkymvxlp.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyifbpfi.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gtclxraqji.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gtawxdskfp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuzdvxdc.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gtuclqlvmg.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gthlqhjrav.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gtytpvemko.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtvhtjnuco.html

[U40] Py：打印到标准错误
来源：http://dali.chenzaomai.com/Article/details/gtvcvoeukw.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtyrswircu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtpapdxxhq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtckjsgccz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gtebhydvxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtnsgvpfgz.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gthzqlfslp.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgewxcuq.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gtjxcysgex.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtfjtvzfml.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gtuzjxmnbs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtcnepnrze.html

[U46] PHP：可空类型
来源：http://dali.bjfxy.top/Article/details/gtdcripsgn.html

?string $name = null
来源：http://dali.hammf.cn/Article/details/gtyntequxg.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gtkrtjlsgz.html

int|string $id
来源：http://dali.fzhhl.top/Article/details/gtupbvgkdr.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gtbatlvyro.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gtlrybhtmp.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gtbtjkvygf.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gtuzbeqtec.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gtkxyluvot.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gtnjxjfiws.html

[U51] PHP：数组解构
来源：http://dali.jianghu66.top/Article/details/gtumhoqqdu.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqijrlawu.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtsszwnwnf.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtsbvdvraw.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gtrfrhepuc.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gtmnpijpwi.html

[U54] PHP：空安全调用
来源：http://dali.kuanghao11.cn/Article/details/gtnbzekplr.html

$obj?->method()
来源：http://dali.yj20258.top/Article/details/gtpwxbtliy.html

[U55] PHP：match 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtvpdhcpgu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtjlrpnkwx.html

[U56] PHP：命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetzmvhuv.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtohnwikws.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtxosjmedr.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmzlintqo.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gtovkrdsar.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gttaqqrrcd.html

[U59] PHP：自定义排序
来源：http://dali.hywenlv.cn/Article/details/gthjwlvxwy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtelbtklxy.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtyvqdccqy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gtwzsdovhq.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gtrwwniroy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtfeeqijsd.html

[U62] PHP：日期对象
来源：http://dali.fengsongda.top/Article/details/gttzbvvngy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tanke756.top/Article/details/gtijjtrkmz.html


<!-- 参考信息 -->