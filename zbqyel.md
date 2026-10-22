代发 wailian999

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gt2rszddyjp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2nicliyzj.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gt2wbghiphq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2xhdtqqbx.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2hkxgyqas.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gt2qzlbezca.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gt2fmissmkj.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2gphnpuoc.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gt2tqpeawzm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gt2eqhvsmvz.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gt2wkypmnub.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gt2wuzdlsss.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2acvgtmoh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gt2ymjgnjut.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gt2hsfuslzl.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gt2fqfuyvso.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysbcsyak.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avcrtvfk.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2dpyzatjz.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2luycopaj.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gt2evedcxid.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gt2ptqphlxz.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2kagcvniw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gt2hbjgrbvb.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2ghlptkoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gt2shqzhhzf.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2kwhwrvmu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2jqrtqkxz.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2dyjvqjas.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxjsoqpz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gt2exjfrgkl.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2mitvbiez.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2ooputsuh.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2cthtwcnl.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwpfzmul.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gt2nmcuiuqc.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2revdedhc.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gt2aenfmncy.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2loakeerw.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2azdopjlp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gt2zsdfymnl.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gt2gutjjjyq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2xtfqfabi.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gt2ijniyhxp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2doxrkzgl.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gt2ssyothzn.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2qmlkzezk.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxembezv.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2djmvqkfn.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2clflkjpi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gt2sebowaai.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thtjafru.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2ozxiiyrk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2jaajjiys.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gt2pjmzaiyt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rbvqeqry.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grysfusy.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2mkbzngks.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2gdrnzyiu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gt2kmjgyzkc.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2clcekvqi.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2qbrlwmdl.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gt2ugrrwxhd.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gt2wesuwuxl.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gt2szzjoskp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2thospgri.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2cqvrqkps.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2lbzgkbwe.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gt2ashkiive.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gt2fuzuufnf.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gt2qgplpfaq.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2mbsdkrgu.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gt2xhcwrauf.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gt2gdodaeso.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2zcvlimjs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gt2ioetrxne.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gt2hbeyadfc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gt2oeeycxwf.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbvemwtm.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2etewoayp.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gt2noqldwyx.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2drnllacf.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gt2vgqcgwfx.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2vzbvowkb.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2apglzwvl.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gt2twlrdcmd.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2usbczgsr.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xoxmbkit.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gt2buhnbezn.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byycmhhd.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2fkdgaija.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gt2vqpssxep.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gt2xtaxmkvg.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gt2rvpcuqyq.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gt2twzmdncb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gt2yeeluxfo.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2aeggxyxd.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gt2chutmyel.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gt2kpiqbnsc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gt2fsxjdydt.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gt2apjemtdw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gt2pptfkxma.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gt2ctrabiwd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2jjizybuw.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2nccgbdrk.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gt2jmuqqhbj.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gt2znmsrotd.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gt2riailujr.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkhcehcq.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gt2mfskulei.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2fznxadgv.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2xapdatir.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gt2bqkdncsi.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gt2vjdyvxmv.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2orrynikg.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gt2smyggesk.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2ciqprntj.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lswkrgpz.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2wqotmfkw.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gt2gvnjlxeq.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2nqrnhybx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gt2evkwvtfx.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gt2wsqmvflg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gt2uavcjwgu.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gt2xbewmfoc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncdqhury.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gt2insecvhc.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gt2sfnieyae.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2qijvrqjd.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gt2ecazjzgm.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gt2iwoftzfi.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2vvxvnhgn.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gt2ntiryzkz.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2phcgvgfa.html

[T40] Lua：元表
来源：http://dali.nwbrower.top/Article/details/gt2pvyjlrgm.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzqenueu.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gt2arnssuux.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2haczetct.html

[T42] Perl：变量类型
来源：http://dali.jyoumei.cn/Article/details/gt2olsnulmy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2umecwpjh.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2jkiijpjm.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csijglqy.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gt2hjklbond.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chjbxfnq.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gt2facdvjtu.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gt2wbvrwdsl.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gt2tykeiqtf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gt2nhnyadxg.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcucimeq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gt2cpbqtraf.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2rdximxdr.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gt2mysurslq.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2rjkpqgch.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2lwuzqehr.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2lenponmy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvpzetrv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gt2mrpyoklo.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2nihecknf.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2agxzphdz.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gt2hjhtvpgu.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2hrnhfbdv.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2kioqpjwy.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gt2yztotiwx.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gt2mwygnmxr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyboyift.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2clwngorg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gt2xzgxtnyy.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gt2pinditwz.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gt2tsdffprv.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gt2zfdbmvav.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gt2xisxzrib.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gt2gnqzdzxm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gt2rtpvmqjs.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gt2ggbligim.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2sibwvcta.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gt2awvwffic.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gt2lkzpqino.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xflfjizs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gt2rpoglljz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2gaoczcej.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gt2lphofdxr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gt2cxqaqqul.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2vbwjupty.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gt2ibexlsxs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gt2rxuncyxb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gt2kybrutyv.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gt2tcykyeee.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2egytmgfr.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gt2actwnfmn.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gt2aveucrgb.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gt2thrxhdgm.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gt2kjuheaae.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gt2modhficj.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbbzqrur.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2vdrellcr.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gt2fcuoixqf.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gt2ecxpsevv.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gt2eucjyhez.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gt2zqwkhazs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gt2qsefyvac.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gt2crtwjwho.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gt2lwcxmsrv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gt2hzjeydgz.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yctbgqko.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gt2qxkdewrk.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikwkrgvv.html

[U14] Py：分组收集到列表
来源：http://dali.mhx1999.top/Article/details/gt2pkvtdehy.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdvjivwi.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfjfnpnp.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgwparug.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gt2eewnyzkj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gt2wkiptmfa.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gt2ujkwpqqx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gt2tqjjypcp.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gt2udkxqdsw.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2chqaxxrg.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gt2xricgpgp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pycfn.com/Article/details/gt2hymoivbx.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gt2grasbelt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gt2ormrtbtd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gt2rtyslzur.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gt2zdnfpxul.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gt2ljkklpte.html

list(zip(*m))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjifrkxm.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2asienzfn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2meobilyt.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gt2mrldbbwa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gt2ntejesvw.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gt2ixtbhcmf.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsjgdmyg.html

[U26] Py：并发下载
来源：http://dali.hywenlv.cn/Article/details/gt2tultlqxs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gaohongyu789.top/Article/details/gt2kcquehva.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gt2pfdhvxaj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gt2ytrddclr.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gt2spnbfoig.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gt2ibtvdvzi.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gt2wvjhfgyu.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gt2qrtpfifh.html

[U30] Py：数据类
来源：http://dali.hywenlv.cn/Article/details/gt2enyjqjxk.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gt2tkaqfscw.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gt2skqxwgre.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhumeinz.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gt2ivmtchqg.html

ruff format . && ruff check --fix .
来源：http://dali.ppjwa.cn/Article/details/gt2rhnsavlh.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gt2aurkwsyi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgqwibai.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gt2lvwiqyfl.html

chardet.detect(raw)
来源：http://dali.mhx1999.top/Article/details/gt2mknxqwbn.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gt2bgwcmgfc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsmfjxvd.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gt2rqhlvpmv.html

schedule.every(10).minutes.do(job)
来源：http://dali.feifeiyinyue.top/Article/details/gt2navftcnr.html

[U37] Py：读写 Excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhipdmwt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnqzz.top/Article/details/gt2udwdqdlg.html

[U38] Py：获取脚本所在目录
来源：http://dali.gzhubu.top/Article/details/gt2hbriuulq.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gt2frjrerqx.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waezkaay.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gt2jkqcisjo.html

[U40] Py：打印到标准错误
来源：http://dali.dashuyun.cn/Article/details/gt2axbgdkua.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gt2lhawibgh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtohakaz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gt2cmhcihep.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gt2ocfldjex.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gt2zrxshnzi.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2ltllrwrr.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gt2uxuldynu.html

[U44] PHP：开启严格类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2zldnpdit.html

declare(strict_types=1);
来源：http://dali.smart0.xyz/Article/details/gt2kpguicei.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvpmmzgv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2gzklpnzk.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gt2hndancai.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gt2turqsjfs.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gt2sdxbshyt.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gt2ymysyczg.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gt2ljrwxtjf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvgvodcq.html

[U49] PHP：只读属性
来源：http://dali.kuanghao11.cn/Article/details/gt2cblzmvgu.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gt2sktfhzwo.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlctdjcu.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gt2fdjpujds.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gt2irirzmtd.html

[$a, $b] = $arr;
来源：http://dali.zhoulong.xyz/Article/details/gt2nvuocoeb.html

[U52] PHP：箭头函数
来源：http://dali.316326.xyz/Article/details/gt2msfrlrho.html

$double = fn($x) => $x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iolcqbia.html

[U53] PHP：空合并运算符
来源：http://dali.xuanzx.com/Article/details/gt2ykblzsiy.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gt2fvoenopn.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quiidavy.html

$obj?->method()
来源：http://dali.zhixingplan.top/Article/details/gt2nwijlxrb.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2sufogrwf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2kenbhhvx.html

[U56] PHP：命名参数
来源：http://dali.yonumen.top/Article/details/gt2ixjwcipi.html

f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gt2ytvhhbmn.html

[U57] PHP：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2coqrcqvg.html

"值: {$a}"
来源：http://dali.hywenlv.cn/Article/details/gt2stmbhcol.html

[U58] PHP：数组三件套
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuhjslbn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzsjoqwx.html

[U59] PHP：自定义排序
来源：http://dali.xinyue.icu/Article/details/gt2kguwcrpx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2tkzqqzlx.html

[U60] PHP：JSON 编解码
来源：http://dali.wangdashe.top/Article/details/gt2lfdrczuj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gt2zhisdksv.html


<!-- 参考信息 -->