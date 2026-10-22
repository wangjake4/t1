代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2ekohtsod.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gt2dlneqkvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gt2seuvdjbs.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gt2gyqswetm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2gjbeuvqb.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gt2yndlvetq.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2yclmfuvf.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gt2wpqacnov.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gt2cgcfanyz.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipigfhzz.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2wjhksgnp.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gt2iukvcldy.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2harqdftw.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gt2mnajidta.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2rcylfdyu.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gt2nlkvkxvn.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2thjwpbac.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2ftihxsqt.html

#endif
来源：http://dali.sysykeji.top/Article/details/gt2xotgptbo.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2avtlvlsv.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2wyrwcnzt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2vpwdaafu.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gt2abphfgdo.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gt2ggibdcrj.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gt2bkcymfnb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gt2uwjnsorb.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gt2ykekfrhn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gt2fzqvytow.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwvprjdp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2zpdppqef.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gt2gfemcrfb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2gfyrqvyh.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gt2amygwltj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gt2xibvvpsr.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gt2aidqxpdj.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdrunvhr.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gt2rxjsjojy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkchjowq.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gt2cssktpph.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2xifmgizm.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bljotrdv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjhcrmtc.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gt2iooeqmsu.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gt2aqcvwkgu.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2sjcnryym.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gt2qejgugnw.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvdfdjag.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgpouejp.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2gpxpbykt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gt2jrmvkgnp.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtcpciib.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2xrbyumyh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eivkydui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2trzmekkk.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2myypwtgb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gt2gppnhpxv.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2uubutthy.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ctopxsrm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gt2vvioyzgk.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gt2capqngrw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2bzpejuer.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2qaxttnou.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gt2upnhtsci.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2nrohdtyd.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2iliijuuc.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gt2mgwegsju.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gubwlohv.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gt2aojwpgsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sybzwmha.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gt2rpdqtqil.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gt2uriyozsa.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2jculbqfo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2mntlsvri.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gt2qmjwtecw.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2bfcuyhvm.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2duyuxozs.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2sgzwveik.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2iykbjshm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2rluuybli.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2scnmwvsl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srfqnutf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2tbzjbtlf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2gpwzwzof.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpxvkgap.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2jnpqwsoc.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2nrtzqdkf.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gt2arlycfyq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gt2iyvxktgy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2ukjjmfiy.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2gbmswqda.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2qfgagqrx.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gt2jugtksib.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gt2lvjmhvhb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2laimtgum.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzmhwkzm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2qnkpsusj.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gt2lkstbflv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjraqwbm.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gt2hpakzqda.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2oqwgqhcz.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2ekzygpjk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2biwthwym.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gt2wvptfvjl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gt2lorammvf.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gt2jewaaqgn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyujabdl.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyyqlssa.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpsmufow.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2aouyrmrg.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gt2tgniighz.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gt2mcochnxy.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2yjfmizsc.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gt2onqexwba.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gt2ochtxaix.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2xqekwjqs.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2xxdcfnqw.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2syptggqb.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2iufaeduq.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2fnyjsiaf.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gt2xtmxissd.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugdwktjt.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2pjnkjiel.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gt2megjlxlq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gt2egdlexbx.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2rzbrjuek.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gt2ofvffbpp.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gt2eqpihhdm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gt2ztzeomlu.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gt2qsbyphti.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gt2miiriitf.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gt2gydphkfb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2stnxytwi.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gt2dxfrdhtr.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewqlwmat.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gt2gwjmlapr.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gt2fofmegbq.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2wvfwcola.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gt2ncqayfsa.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2vpksavjm.html

enum Color { case red, green }
来源：http://dali.hammf.cn/Article/details/gt2byiqryrr.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gt2ccfnyyln.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxgkqfjq.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gt2wuktarxf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnzsefs.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2fkwcwoai.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwiliidw.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uatzrbyz.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2jjbnenpu.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gt2avaxtnjc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gt2jirsqeit.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gt2nsqprmcx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2anuhpths.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gt2uaypuyhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2jsarfqhi.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gt2zlwincou.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2vaqvsybn.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gt2vkozwcwa.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gt2ixtwggvy.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgpftmhe.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gt2lwimtojh.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2yamxiutk.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gt2zttzerdo.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gt2injezzby.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gt2ohftdyfk.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2rbvcqbps.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gt2grghkwto.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gt2bkxtuord.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtlsybv.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxwlvyym.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gt2ahmfthkn.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gt2vkwfwojo.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wsbibfmv.html

[T45] Perl：数组遍历
来源：http://dali.aibaodan.cn/Article/details/gt2friyrxyd.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gt2sojbxfqv.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gt2yoktqmpr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gt2mfpebwbs.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gt2wbpinetq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gt2ropjqoeh.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2ryyijvcl.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gt2rtubngda.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2wnxxvjga.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kumiyhsh.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2vxsodvtd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zdqjudy.top/Article/details/gt2yfknyqcl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2abfqtkqu.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2pbzddrab.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2yvxxzfsg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2adknrtfx.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2mpnvrzhu.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2zxbbbujs.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2vxgotplo.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2hoslvyad.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2izxrtdyu.html

[T55] Scala：集合过滤
来源：http://dali.meibo888.top/Article/details/gt2skqwekfe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omhopkyc.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2hivwiixa.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2kyjngdhw.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2vpuurwyw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yvedp.cn/Article/details/gt2wbtsspha.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gt2fyblckhd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gt2npcxxqyr.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gt2jprrkohe.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2grfuxokf.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gt2lorzyget.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gt2iwmdayxs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2tzbtrywk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2hgxldxay.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2jmqwisst.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gt2bhygdmcx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gt2silbxwox.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogbrdteg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gt2arodiqzf.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gt2jctyqcid.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gt2vgvjezdo.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fcrwhykm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gt2ekitazsx.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gt2lsoyuvbe.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejzwyoyj.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gt2nsfyepjv.html

{**a, **b}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oweacurq.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gt2epusvdbc.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gt2sovgyiai.html

[U08] Py：展平二维列表
来源：http://dali.tianlin.xyz/Article/details/gt2fhezcezz.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gt2zjamlgbd.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gt2okilvtwt.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gt2tsvhjmwp.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gt2cjykdmxw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gt2qwjbsobw.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gt2wtbnthdi.html

(x * 2 for x in arr)
来源：http://dali.chenlongwang.top/Article/details/gt2gvwljwof.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gt2fikkvjzc.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gt2qnkoujph.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gt2yykawzaj.html

deque(maxlen=10)
来源：http://dali.gaohongyu789.top/Article/details/gt2snkecjis.html

[U14] Py：分组收集到列表
来源：http://dali.fengsongda.top/Article/details/gt2bdswkeid.html

defaultdict(list)
来源：http://dali.xuanzx.com/Article/details/gt2nnjtnuzu.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gt2jcjcouuh.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gt2jxzdlzls.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2ojbebxzs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gt2sbemkveq.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tplsnrof.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gt2gwvevvof.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gt2ddvqqpbw.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2snwrnhdf.html

[U19] Py：正则替换带回调
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqgwzlla.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gt2uambrfjy.html

[U20] Py：缓存函数结果
来源：http://dali.dianchejie.cn/Article/details/gt2ufbwilhd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guowangkeji.top/Article/details/gt2bigfcvbh.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gt2uzqyxojy.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2jglwwvay.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gt2jzoiwrry.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gt2neuarpgv.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2kshrfmfs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gt2hxpmvtfs.html

[U24] Py：路径操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdeqcdpa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktwdhksx.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gt2qeqvbfow.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gt2vzaxwsxt.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfaxskyd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2ulfjfzjv.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gt2coglnhch.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hfpthk.cn/Article/details/gt2wikultre.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gt2loyvwrev.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gt2umdikkxu.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gt2hhtfpkoy.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gt2lirkwpzj.html

[U30] Py：数据类
来源：http://dali.xylfe.cn/Article/details/gt2zjvprmtq.html

@dataclass(slots=True)
来源：http://dali.sxryk.cn/Article/details/gt2fsnkjfav.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gt2zbkbkdou.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gt2gipmyhfi.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gt2barhebar.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gt2ouxetxmt.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gt2akzzgsoy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeifxbfa.html

[U34] Py：判断编码
来源：http://dali.kuanghao11.cn/Article/details/gt2ryhsgkhu.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gt2ctysxxqw.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gt2fnrxghhz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gt2dzkvkozy.html

[U36] Py：定时任务
来源：http://dali.ivvv.top/Article/details/gt2mevjkznu.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gt2mceukuwz.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gt2jhnkvgqe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenjidiqi.icu/Article/details/gt2lztbkydw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gt2nyfepwiw.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gt2uojmjfll.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtymdnwn.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxgvhwzg.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gt2czcdfxpa.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2grnppvuq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gt2rpehgrgw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xziqi.cn/Article/details/gt2hqaskrsz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gt2buslmisp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gt2rzmhxgnt.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2osrfbzin.html

namespace App\Http;
来源：http://dali.gotoacloud.top/Article/details/gt2xipleoru.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gt2jjstfjwx.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gt2jcynqtat.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gt2zzctuuwc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2ueqsyyky.html

[U46] PHP：可空类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ftfqqzhc.html

?string $name = null
来源：http://dali.zhixingplan.top/Article/details/gt2xlkgthbe.html


<!-- 参考信息 -->