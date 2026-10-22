代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdipfang.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2ejgbddhk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gt2ojgzcimo.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2kmswundz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocsiyuff.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2kloxgwii.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfajpavi.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gt2lbnpxvwb.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gt2ygpxtjlf.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gt2zrqcvyzl.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2rjjdngqi.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gt2kamznbgt.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2jsvweuje.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2pchoctug.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2cukwuhbo.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2wwxnwbjg.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gt2yconfmcy.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gt2duexxpgv.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2jfoqiquc.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djgkojmy.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2pyencxte.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bcdxyvui.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogyuvmdf.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gt2zxjqrcgp.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gt2lcggwmiv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2gdpwqlrt.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gt2xqlhhqht.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxvzbxut.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gt2pupbrveo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyjbawva.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gt2qpakoocb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2gdonjhbh.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2wlapqbrg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gt2spcnbqth.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gt2reutdvby.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2lzcjztec.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gt2cxahkdne.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gt2uqzijuwd.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2zhfcghud.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2stuucurd.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gt2vjyogjgs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2ucrtydpc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjdehgl.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gt2sezzvkyw.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gt2zujhzwvn.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gt2mvlqjuin.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2ryjxjdnp.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wxigkjvc.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gt2rrvdhzpu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gt2sblhlnjc.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gt2uedddxbs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gt2tvnqific.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gt2iqipxzyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gt2aoklzxzm.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2heferryk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gt2vfgbvstc.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gt2asosprxw.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gt2kusztjyz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2xtfquvrr.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2jacytzkr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2hfmtncwj.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2jxjzmxty.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2wehjwotr.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2sejlwblb.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gt2obyjwbwu.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gt2fxckdthq.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gt2aymgxatr.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2rvsmwpng.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gt2fgsvmyar.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gt2gehnfhhn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2abkwbyec.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2jalzlgrd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gt2onanvbqc.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gt2ksolaazj.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2pdvchfiv.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2mfvdmkhe.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2addmkkxc.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gt2fjuxgrei.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gt2eaxqtuja.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2xyayrfcf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2imjhzxaw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2dvhfokta.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdlinhqq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nfjsxxid.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2yktodgfw.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2iicebzjn.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gt2hnbhntop.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpoyesmc.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gt2drtupjij.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gt2vrtbgjbf.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gt2twnzyysp.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gt2oawpvvql.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2rgudclpu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gt2mwttqnjb.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltdvcsth.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2yviwkqkn.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2tlkijtjs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2bfvgdzam.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gt2fvapabrf.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2byfzshsr.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gt2psrizaxt.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bseoajhv.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghqomofs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gt2pujgfgrs.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gt2gqhoqaxk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gt2gwamvcyc.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpryfjbr.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2uvjloeju.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gt2kcwybbja.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjfitckw.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2bkahkcqb.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2imapomcn.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gt2bvkkkvwz.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gt2pnxjdukc.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2rjmrslwp.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqzumtuu.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gt2qzikmjnz.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gt2fjpjobcm.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2qkkqdsua.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2pxofjikt.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gt2rwnqspbb.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gt2wlrhwdev.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2aecsuger.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gt2npbyvhnd.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gt2njayacfe.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gt2rrpactqh.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gt2tqbzdybi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gt2ttthhfop.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqgilkes.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gt2vbnmndha.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmfeiqne.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2nvkeffxr.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gt2chldyuhl.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gt2rohwqpiv.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gt2oxmevbud.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2hzpjaldk.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gt2hudbdiux.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2ugdajjmw.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gt2rojdujom.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gt2sqmicrbh.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2rlpyejxi.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gt2rchrqyzg.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gt2nxkmazrp.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxkngtnp.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2ixzcymzc.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2ysznbimv.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2tzlzyjhv.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gt2ekdbpurh.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gt2xmquutes.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2tmhkizng.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqgvoxum.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gt2gzpppkud.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gt2pfjrxbwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2zqydmuzu.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzawxnat.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gt2igpxztnw.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gt2ekqyqowg.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gt2axbusozk.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gt2ajmezaax.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gt2tsiadmxx.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2odcftlic.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbxlyoxs.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gt2mxohavoq.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gt2xlmyigcd.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmgykiou.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gt2cfnesrdn.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2hbhibppy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2qlfwsshp.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2htaitblg.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gt2sagvpqpb.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxjmxtuq.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gt2ryjjhtmy.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gt2mxwqfgjh.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gt2ibdyyhib.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bldrxizd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gt2kipvybva.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghbfsxym.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gt2cozdbawo.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2aegapjjt.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gt2aaauteqo.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gt2isfqxlgb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yxwuycfd.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2qbqmivdy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gt2cwsdvdgq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gt2xvxidtse.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2xdqwqkgf.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzwseloi.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2gauynmse.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2mwiebfpd.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2navnpbzl.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2uspecuhm.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2vcsisdem.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2myhvoali.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2eezqmrkf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gt2jreffxmt.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdryfjle.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gt2acwqaywq.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2hdpixtjy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gt2bokiqrwu.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2ssnuaptd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gt2rplqvbpq.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gt2bjbugeev.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlwpczdg.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2blhcytkq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gt2jsxztuob.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2xquzmuvd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2djqyiays.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2htgbrmxu.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gt2uikraswi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gt2mjctthyx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gt2jjfwmoaf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2kaoehqnx.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gt2ttevsvww.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gt2ysyvssys.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gt2wpcrhnbf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gt2mzaxcqqj.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnpjzvgd.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2pgvbdtth.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gt2hdtuepqe.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gt2xhhcnthp.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gt2gtpkkpxk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsckwdr.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvygusxb.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gt2tqnrtwmv.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnlxjweh.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gt2kktyuccj.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gt2npmttkiu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2tfldanes.html

[U11] Py：生成器表达式
来源：http://dali.jqgfzy.top/Article/details/gt2gemkcmoz.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gt2tevihcvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gt2ypoclbde.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gt2apcmcgsn.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gt2hqkcdocn.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gt2lbbkpsry.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2nfllapme.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gt2vraexxst.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gt2edwpjrrz.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzocegvu.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gt2rougdayp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gt2bwxwxkxt.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gt2qqzmcstr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gt2juglyyfr.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gt2uexovnsf.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2crjjnjet.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gt2vrvlmeju.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gt2ctnxmxdg.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gt2beaqbxzm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2icierbjl.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gt2rtfdfwdx.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gt2qxhyqfjd.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gt2zbujprbi.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gt2morthnbt.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gt2icywsbxc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gt2kqdstzgu.html

[U24] Py：路径操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcvplhjb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2exqdbmky.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gt2zigbrotw.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gt2dxtpcumw.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gt2engzuyxb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysnoieyp.html

[U27] Py：异步 HTTP
来源：http://dali.0kj1m.cn/Article/details/gt2nlzwcttb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gt2ljkayifm.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gt2wgtvbfsy.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gt2ximemcpq.html

[U29] Py：属性校验
来源：http://dali.chenzaomai.com/Article/details/gt2gcjfmege.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gt2tycejwox.html

[U30] Py：数据类
来源：http://dali.hywenlv.cn/Article/details/gt2mwjbgbpq.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2coawwehj.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnlwqhcm.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gt2zrzbdfpr.html

[U32] Py：代码格式化
来源：http://dali.tian-w.cn/Article/details/gt2nggitvim.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gt2pozmrsuw.html

[U33] Py：打包发布
来源：http://dali.yanxiufei.cn/Article/details/gt2hwyubgyd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcgxnhgs.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gt2bnwschjd.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gt2fwhemhqt.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gt2awtidypg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gt2efvkafml.html

[U36] Py：定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2aohuchrv.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gt2wmdebmvh.html

[U37] Py：读写 Excel
来源：http://dali.daria6918.cn/Article/details/gt2pbfgwldb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gt2ugtkxmns.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gt2ptrokyka.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gt2dwrunkxv.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gt2ybyfnpvq.html

sys.stdout.isatty()
来源：http://dali.mhx1999.top/Article/details/gt2ujilcbzq.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2isgtgbkn.html

print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmwcsnri.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xinyue.icu/Article/details/gt2wmttxlto.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xejnjnmm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gt2meexpoxi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ybcxt.top/Article/details/gt2zdmqvsou.html

[U43] PHP：声明命名空间
来源：http://dali.andypj.xyz/Article/details/gt2zwppbqac.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gt2sislwzdy.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gt2nbgiqakt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnauxipc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gt2ktfngbuc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ctdqkizv.html

[U46] PHP：可空类型
来源：http://dali.fzhhl.top/Article/details/gt2judzzzip.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gt2nytsliyt.html


<!-- 参考信息 -->