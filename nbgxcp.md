代发 wailian999

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gt2wxuftnuq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2faiogjob.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2craklkyb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2texkcqzj.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gt2nzkcrgzj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2sbqqtuyu.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gt2eyjxxsxq.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2eerkoaue.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gt2zdnaudhz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gt2psckuvui.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnlpgisc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2xivnrnch.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gt2hvuoxtag.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2mswraztp.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ecdtkndp.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gt2ioeorgyj.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gt2wvfootfi.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2innmhgjj.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gt2ellvspvy.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gt2oyfmyqlk.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gt2zmlaufxg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2knvqwkml.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gt2hprryhbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2zzukoksc.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2byogarqd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2xjxuexuo.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2ihivhhxj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2whdrqzac.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quhehgym.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iumjxzid.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2qjxrpktk.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2oamodugw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2erifqlkl.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gt2knekycro.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2zwaxrnpw.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2delgwezb.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2yjbwhdxc.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gt2ujxvfqfz.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gt2coeiqpkn.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2khnrwycp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gt2qtdovcya.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gt2hxqagali.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gt2ajrtonmt.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gt2dfaelwpx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gt2embcdaxv.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2edoypqpo.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2xkydhitl.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gt2ikgznmnx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gt2mwtpcdwg.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2fezmunxg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdjkwkbc.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2xsghktvn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lefogsli.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bxgmzira.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2jgvldmkf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2wddsycks.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2pbfimhkz.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqdqnyfv.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2obgcdrol.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmzlijkl.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuhyplce.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2qzpavnzv.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2wfgjxlly.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gt2rksilthw.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gt2womzpgrn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gt2injnvnpn.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gt2bgbydmeu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gt2idxixuks.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2hudawghz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gt2zykwokyn.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gt2hbdtjshu.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2qdnfvicl.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gt2zjympqav.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pltavbko.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2kodjauak.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2uxpcxlnv.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gt2bhqtmwqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2nxyrkvgw.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2yghwhina.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2rxlajhbr.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2dsysfewu.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2kekvqcic.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gt2icdewynb.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2daudfnmx.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gt2tldzognq.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2sqvbqoqy.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gt2ynjnzzsr.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2szoiugvt.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gt2ijmywcyr.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2qepulscz.html

[T18] Swift：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2zxhhpwla.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gt2rntbwhav.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2saykmsen.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gt2whuimscc.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gt2gbuyvciw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2acudfuqe.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gt2ynyqgtwh.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gt2dhurewpp.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2nembofav.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gt2rnqpyrfc.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gt2skiwpcnp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2trnoczcc.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2wacbvihd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2znvnzkoj.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pchaboka.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gt2ksogfxwh.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gt2mrvjjlik.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2aevomfqf.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyeivvjt.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gt2tslhvvpp.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2dvlpjlqs.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gt2mizshntw.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqajrcyo.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gt2hrxfzxbv.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gt2ngovvslb.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2mdokcobe.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gt2pxwxnbnk.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2singwnqm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwogrquq.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gt2twashscf.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gt2ybduntvx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gt2fbpvzfdm.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2mereypdw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gt2fbravkxw.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hilfltzw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2cnmbarlo.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gt2hfcwjuor.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gt2mxwghkjv.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2dnnkgnuv.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gt2rseztnlz.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gt2yhyywlsk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkghgomb.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2vxrvavrv.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gt2hpkrwqph.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gt2dlafjesa.html

setmetatable({}, { __index = base })
来源：http://dali.tianlin.xyz/Article/details/gt2kymowzdv.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2myhgqywo.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2shiteqyu.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gt2nmduogak.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gt2gmewiaeh.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlrborcm.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljqcdkce.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2brlcaxzz.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gt2sfafynax.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gt2pzrexrkn.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gt2myxvaovd.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gt2jleirldu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gt2bfjxvfen.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gt2lwjbfcwu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gsaoqyzz.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gt2zthlxfnf.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gt2mzlbgyxt.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gt2iuzxdikn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2wlyocisc.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ztsnzfnb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckmwdutz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuanzx.com/Article/details/gt2glyhcqgy.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2ovtwvftf.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2lvfezoex.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzemtfdh.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2nzqiimqx.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2mvumrxbz.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2vlpbrcxd.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gt2llhizpdm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gt2mchmaeka.html

[T55] Scala：集合过滤
来源：http://dali.gzhubu.top/Article/details/gt2gcveuewc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqehygqy.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gt2xwyakodq.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnlnancv.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gt2rxxuujkm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2emqwtead.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gt2cfgplnkr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gt2qrtxuhup.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gt2nawhiudb.html

for (i <- 1 to 10) println(i)
来源：http://dali.yueranfly.top/Article/details/gt2zqyipemw.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gt2fslwtqtk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gt2ykeofabe.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gptpzuza.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gt2bjxapffs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wyejixjk.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gt2moofgotb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gt2ukgojofr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gt2bqsotfyn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gt2wuewedef.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gt2vuwbcxru.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gt2npifngrf.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2yyyomjvs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gt2vunnjwda.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gt2pftqlqre.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2hmkgnzfv.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gt2mpfdwuyu.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktgftgrz.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gt2xdfbakhi.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gt2ozyckjwl.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gt2fubkhxmz.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2bgphiqms.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gt2hklapjlr.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gt2zmrjhflp.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gt2wvnwwqvz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gt2tomlxuqm.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gt2tiagqhlj.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gt2wemqypks.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gt2swaodult.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gt2klqrefvk.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gt2pwomvvie.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gt2lreyzusv.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gt2zelkofhc.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gt2cjkroplt.html

[U15] Py：高精度计时
来源：http://dali.sysykeji.top/Article/details/gt2jydhyons.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gt2dgemjaru.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2pkcwyvrf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gt2qpivzaff.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gt2nmlsmqex.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aizwys.cn/Article/details/gt2wxlkfsvw.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gt2cblewyyk.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tikqifob.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gt2dsmamcbf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgfzy.top/Article/details/gt2aiilknjw.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gt2vbbdodme.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gt2oapgbftj.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gt2wddlxqfh.html

@contextlib.contextmanager
来源：http://dali.bjfxy.top/Article/details/gt2yayjtyyo.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gt2gprxiuee.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gt2gbthfkcl.html

[U23] Py：分块读取大文件
来源：http://dali.xziqi.cn/Article/details/gt2giazhsfo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkntngpz.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gt2xyjswwrz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gt2mksodctj.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gt2enphvqly.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2rtviiodc.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gt2sulgefrq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gt2rhvezuxq.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahligvvf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxinkj.top/Article/details/gt2xugkdwzi.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gt2utnwlvox.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gt2rgveooey.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gt2lzxgjape.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtemvxbn.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guhwstar.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2tcnxxrlg.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gt2zclttmjj.html

python -m pytest -q
来源：http://dali.cucudq.cn/Article/details/gt2tugtvjoc.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjlwzgky.html

ruff format . && ruff check --fix .
来源：http://dali.nwbrower.top/Article/details/gt2pwhwravl.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aehdecre.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tanke756.top/Article/details/gt2kkgfnadr.html

[U34] Py：判断编码
来源：http://dali.redwolf501.top/Article/details/gt2gketynaa.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gt2vwxtoset.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gt2vauegqbs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gt2duyjkdyg.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gt2jbqjvnxt.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gt2npehqrkc.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gt2hndejstv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gt2vmcixkau.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gt2fgzoejek.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gt2pkpptyzl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gt2lmdogkno.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gt2vkvcfudu.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gt2ziujnati.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gt2yodohrpn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gt2jjbblfri.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gt2yfihlego.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fengsongda.top/Article/details/gt2uhlslknq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngpiykcn.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gt2zhyopjov.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gt2tacssqlm.html

[U44] PHP：开启严格类型
来源：http://dali.shuidangran.top/Article/details/gt2bhvdgbnp.html

declare(strict_types=1);
来源：http://dali.tianlin.xyz/Article/details/gt2hffycjut.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gt2qqpkvgmk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2atjjalpq.html

[U46] PHP：可空类型
来源：http://dali.ydzc1.top/Article/details/gt2qzasndpy.html

?string $name = null
来源：http://dali.jiagoushi.top/Article/details/gt2shixmfni.html

[U47] PHP：联合类型
来源：http://dali.pycfn.com/Article/details/gt2aewuqrwy.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gt2vsxwdvcn.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gt2teygnxfd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jyoumei.cn/Article/details/gt2grzlwuvg.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gt2fbnspcar.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxjebyfr.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gt2pczvehxo.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gt2emwdesps.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gt2tvoqlofr.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gt2wzukdqnq.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gt2xdtdmdwx.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gt2iacuxhdj.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gt2islrcbqx.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gt2bjukavsu.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gt2eeqmpyca.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gt2nbfkcrzs.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gt2kqjwhorp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gt2yojemajk.html

[U56] PHP：命名参数
来源：http://dali.sysykeji.top/Article/details/gt2gkoezztu.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2itovpjjw.html

[U57] PHP：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2huzmxjpu.html

"值: {$a}"
来源：http://dali.dianchejie.cn/Article/details/gt2ozetrezj.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iorwrura.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gt2irtgayfw.html

[U59] PHP：自定义排序
来源：http://dali.vqdsnc.cn/Article/details/gt2penhsmru.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2uqfaouuj.html

[U60] PHP：JSON 编解码
来源：http://dali.cucudq.cn/Article/details/gt2qwzytjkn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gt2xkjnwquh.html


<!-- 参考信息 -->