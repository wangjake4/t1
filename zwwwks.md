代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2vmagvpcw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glyibfrd.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnpcwpnp.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2mpjmvjxc.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gt2kfobpnvk.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2iyhggakn.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gt2bfvzmqxm.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2mecngxuq.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soenfszt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gt2cxnqmumm.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2edppolwn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2soyaycjx.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2aooqzpmw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rrgliktx.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2itxivimh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gt2ptuvbikq.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2ivyqhvwx.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2acujnoms.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2bqkpvmus.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gt2swqplnjj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2yxwrbcol.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2sfqekygw.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gt2wxmfychf.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2vshmvbrk.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2pqumtxmi.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gt2djozciyb.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gt2jwdsjfzr.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2ieormqkr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gt2lvqovqgf.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gt2gpseelma.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2kuxnwerj.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2ojygplrw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apobxvlr.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gt2mgsloonc.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2aimyetlk.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gt2xcwpqxlf.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gt2fnanmnfy.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgfqoihe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gt2llvzxsmz.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gt2qcfyfxfw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2ujtrrras.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ksqmxvns.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwemcsr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2swxlkwpi.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2mccxluff.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2hlbozdut.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2ivtyrmny.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gt2rcvgeutc.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2tusuccia.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnypxclg.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2uwchafci.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2bsgqmxfq.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gt2fnsdljtb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gt2kvfsdwjp.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2laivmxxj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gt2imiaqxiz.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2ktnsyfvu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gt2cdiqasnt.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2fffuehdy.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gt2xmtnzfzp.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2qqgyykyl.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gt2mixmzbuy.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gt2cqvifyoz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gt2ppmvqazi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mstgnolc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gt2nctdhpqr.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gt2bfosygln.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2bosbbzjv.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gt2zrwcoorj.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zffrravl.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gt2xtqezvlk.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2ougfehzy.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gt2nzincxjb.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2wrlbbhbl.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2oajlofxw.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2efxexzkv.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2tuxuflvq.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2avzfsdoa.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2jdyxxssa.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gt2axvicrqs.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gt2lovuvwcj.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gt2yhnfmzlj.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2logkbvjo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gt2vfzwiklg.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gt2gchogklo.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gt2wkhqdwje.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gt2sgvgchqz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gt2pvqtcbib.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gt2lrfaazpi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2wgjfstaf.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gt2dlrvwdpt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ssfgwrwj.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2rmnpzbxv.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gt2xafocrfd.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gt2nevamhrf.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gt2fmvqkede.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gt2gkhhpxyp.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gt2vxsattoh.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gt2oyqdshcu.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gt2wjjxcgjm.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gt2xzkdhxgw.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gt2mzteoxgl.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gt2qnvrlayk.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gt2mofwbxef.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2tkhjqjdr.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhtjpsrc.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gt2imvzxcir.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gt2qnwpkniz.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2mxipwnsh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gt2jwzypsyu.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gt2hetuxoyp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2jlydongw.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gt2licxnpbw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2tlnmecxt.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gt2ziltypzj.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epdftldx.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gt2ntnpyxen.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gt2swevlrkk.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxxvovtx.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gt2uwckqwpz.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2hsfeppva.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gt2vjnxtrur.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gt2amilkmit.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gt2sbwpaiqz.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2lnsnsgpz.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gt2ilfkbwle.html

[T42] Perl：变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2wkfuguds.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2uhmdtbwi.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2bbentqlm.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gt2pgmqhobq.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2cilvcyte.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpapwclm.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gt2vubeclan.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gt2fakqdocr.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gt2tmxtvgmj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2sbwatvid.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzminbks.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gt2dcbutkms.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gt2zvsstfcl.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2ryqdchwg.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gt2jtiegwps.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2tijkanyt.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2yikbqjqn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbonmofh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2uwluxpgg.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2pxdxvqjr.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2mnpsqpkh.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gt2gafxeyew.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gt2psjbcepz.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2xjnpleru.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2fhxknnnc.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2qxhvqnym.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bzuypqvj.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fznkqlcy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyknxyqa.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gt2qpwlopcq.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2zhfgwmyz.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jptzwsah.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gt2gsrwfrks.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gt2pcyazexy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2iuhkxvjs.html

[T59] Scala：循环
来源：http://dali.ydzc1.top/Article/details/gt2lecigupc.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2kkjczbum.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gt2okbhvzwn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxokowpp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ngblmbzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gt2zohzxfbn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mptcywbh.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gt2psqjyoyv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gt2zxjnzujz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gt2xfkpozrx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gt2ohipbinc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdsennsq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gt2hcfbrgdi.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gt2wskzpsws.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gt2vsrgkawh.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gt2sekqctny.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjmeximm.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gt2sbutrsof.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2cnvabtjo.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gt2vuzfnbmc.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gt2fskuujhf.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcbpizwk.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gt2cxmkcmjx.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gt2njqzkaex.html

max(d, key=d.get)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrczfjkw.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gt2saewtcgp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.quarkkingdee.top/Article/details/gt2lezzbfcx.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2fwkmdmrx.html

(x * 2 for x in arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2vahcymeb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gt2bkmoixme.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gt2kiyughhk.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gt2yhcezatr.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gt2zitopgaa.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gt2qbmjayxm.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2sxcgvxop.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gt2negfgaky.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gt2xrfdtspx.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gt2fqxhkbed.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqqqdine.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gt2deadygkh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gt2cngfgnfz.html

[U18] Py：预编译正则
来源：http://dali.xuanzx.com/Article/details/gt2iupaiuac.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2vcsoivjg.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gt2roknecoh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gt2naumdguv.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdorjtzs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gt2doievhvm.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gt2ktewxumo.html

@contextlib.contextmanager
来源：http://dali.xuanzx.com/Article/details/gt2duqtlecp.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gt2vjbkzsgj.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gt2xocgqsde.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gt2thxgdkmz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gt2evcphkrp.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gt2ggjaaogp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2mnarrdnp.html

[U25] Py：CSV 按字典读
来源：http://dali.gotoacloud.top/Article/details/gt2wqhnkjzp.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gt2gwemdedf.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvkelirb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gt2akikxcew.html

[U27] Py：异步 HTTP
来源：http://dali.sysykeji.top/Article/details/gt2ypylqwgp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxuanxn.top/Article/details/gt2rqemtjpx.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gt2gtzbxzfb.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gt2eymlkift.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gt2ubvgphmw.html

@property 与 @x.setter 配合
来源：http://dali.daxiang520.top/Article/details/gt2xllsnxvr.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiuhnfak.html

@dataclass(slots=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2jxuehstr.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gt2djejgljv.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gt2kakeakds.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gt2kyuvuzxd.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gt2zfaqszso.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gt2lbkukccc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gt2rnmcaljo.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gt2gzwbkgyf.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojrrqfqi.html

[U35] Py：发送邮件
来源：http://dali.sufxvd.cn/Article/details/gt2ivnnznmx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gt2wiazalbe.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gt2fmusobnz.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gt2vojonrgd.html

[U37] Py：读写 Excel
来源：http://dali.daxiang520.top/Article/details/gt2vvrsjyva.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gt2piccecje.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenlongwang.top/Article/details/gt2jjbsonxb.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gt2jrgnqxzz.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gt2bavrmyzx.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gt2rpqagkuk.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gt2nkailnfa.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gt2fljeldsv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxruzghh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gt2pkbbaaiv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gt2onrfhmhx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fraytxgq.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gt2dkrhfgso.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gt2cltkzpho.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gt2okzflsyo.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gt2jrhpcxga.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkanpfkt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2lkkspdsm.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gt2ajoqlqkx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wlppxtpd.html

[U47] PHP：联合类型
来源：http://dali.aibaodan.cn/Article/details/gt2niroveul.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gt2tewtfiav.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gt2jhatccpd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gt2zdxczrvf.html

[U49] PHP：只读属性
来源：http://dali.jyoumei.cn/Article/details/gt2kibixfua.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gt2uhhdvjsu.html

[U50] PHP：构造器属性提升
来源：http://dali.yuxming.cn/Article/details/gt2khcdghmh.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsukaftz.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gt2chtxwume.html

[$a, $b] = $arr;
来源：http://dali.dianchejie.cn/Article/details/gt2bcjnmtxf.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2gfcqunie.html

$double = fn($x) => $x * 2;
来源：http://dali.chenzaomai.com/Article/details/gt2sqfiwifi.html

[U53] PHP：空合并运算符
来源：http://dali.gzhubu.top/Article/details/gt2yveejscs.html

$v = $a ?? $b ?? "default";
来源：http://dali.ydzc1.top/Article/details/gt2tppbdghh.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gt2rbhylgfk.html

$obj?->method()
来源：http://dali.xziqi.cn/Article/details/gt2fguejuvu.html

[U55] PHP：match 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2venipwzp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gt2qjqizcxb.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gt2fmrzdxea.html

f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gt2xlrlxtvp.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2yiowrtsr.html

"值: {$a}"
来源：http://dali.jlsjyb.cn/Article/details/gt2icnojpcu.html

[U58] PHP：数组三件套
来源：http://dali.xziqi.cn/Article/details/gt2kikfdtyq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gt2ibfzkoka.html

[U59] PHP：自定义排序
来源：http://dali.hammf.cn/Article/details/gt2lhlhmmxi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gt2rvijyqmx.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gt2wukxqofp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2ymtexmpr.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gt2mvdnotno.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gt2tqurgugc.html

[U62] PHP：日期对象
来源：http://dali.andypj.xyz/Article/details/gt2vnsnvzei.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yangfankeji.com/Article/details/gt2kfcbpbde.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gt2fzrhlwuu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gt2dwqgkadd.html

[U64] PHP：目录遍历
来源：http://dali.jianghu66.top/Article/details/gt2wbinuwop.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gt2vloznbyw.html

[U65] PHP：会话
来源：http://dali.jinqigufen.top/Article/details/gt2nocwwzfl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2qzxjldtn.html

[U66] PHP：设置 Cookie
来源：http://dali.tianlin.xyz/Article/details/gt2pddyfgfu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.iojbl.cn/Article/details/gt2hxviwaqy.html


<!-- 参考信息 -->