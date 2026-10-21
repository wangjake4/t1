代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtlxyxwihd.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtjutjlznk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gthzkmojrd.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtcjetrzcd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtajwlplsn.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtawnqjjvt.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtsirxndmg.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtovwmcskp.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfwjhrcu.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtjjvhhvvg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtujwyhzme.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtjppqrajq.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtixoegsgs.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtgwgsxmox.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gthurgyinl.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gthbqmilal.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtonvyagel.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtushcqxpf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtjbkxwvsd.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdssrlkv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtjibdydut.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gtlhbwwcxc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtfzpqbemq.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtewwauifm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtidiikxjt.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtunkpxexy.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtizwrtxxw.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtyrqtzxzj.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtiiozejxo.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtssuygicy.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtmnvetmmy.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtxgalbnbw.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtpjhidzza.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtkqnnrbns.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gtkvlpkwfx.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtldijenqe.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtgiqahwjp.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtebhwniux.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtgvgmcgnw.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtcnuqfsrk.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtqkjpyula.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtmgkiicxq.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtbxofpycy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtcvlbwzap.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtwhseepqn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtxxirgtri.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtvsdsfgfs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtrboiueyp.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtesngbust.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtunascica.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtemyofiqw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtdjgpqheu.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtmzbzklsj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtyhwgivuf.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtkxiouzps.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gttnlnhzmr.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtnbhwmthc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gttzcwsjoi.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtcgukbkoq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gtxqcofdoc.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtwsztbpxi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtvbmiiask.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtnssoyeny.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtuzizhknq.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtncrbqdgl.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtgothhcwu.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtbgehwmhw.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gtgrixgcol.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtxkrrgfvz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtqwnsfteb.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtrchbpqhg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gtevvccdgs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtucqqhstc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaovqmfza.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtkspzedyp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtshbuoxdw.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtbdnupnhs.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtrdleprfl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtzrabfoke.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtymvmnnps.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtobczwztg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtowvyfjyn.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtwwbjktdz.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtjcdrkppz.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtazoylpwg.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtjghqfzho.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gthqwwlpyp.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtpeanqkcm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiijezymt.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtpxohtcty.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtrkapopcb.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gtyewugack.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtjbednert.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtxftdzucw.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gturppbuyj.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtsiphufrm.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gttvrxyvbf.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtrpixmsqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtxrxozfjn.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtmkywdkzg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtruvibyxa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyjtlcakv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtitpwgxdp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkvevatdu.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtipkkizdk.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtcjqkxwmz.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesqakasl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtrnfwdnot.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtrjkvxjrv.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtypqnistv.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gttbhsbwnl.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtwpoyajoh.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtrdnkwxco.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtzuxeswlv.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gteosrhdrc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtsfcmxfwh.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtlnemebfh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtmaapefgy.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtpkneiqoo.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gtroyqbtev.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtyfrrefuj.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gtcikaelzq.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtkqluypwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtakmynwgj.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gtnbrxguoa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gtfpfcdzrc.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtzalwtpir.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkzboeaxk.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtsgngriwi.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtpksoqfqs.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtfubsaijs.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtpyebphmc.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtovthkzjg.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gtfshiwtps.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtvecueqao.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtlqvjvzes.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtipdmgidx.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtrespyirp.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtntqgysrm.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gttrvhsinz.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtowfzwbky.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtmrufrgqp.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtzfmjjduu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtavxyzheb.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtirnnfesr.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtmvgxsgsm.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtjogwhkai.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtkgoinyoh.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtfeqppdio.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtsivvvlpp.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtkyzcbzwt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtqoyubfvw.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gtbjrfacxk.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtdtjtogjg.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtstybyrrc.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtnntrzeoa.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrrezguc.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gtcdavgofp.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtfhtewyjx.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gtztvyaqme.html

[T29] Swift：guard 提前返回
来源：http://dali.fengsongda.top/Article/details/gtsikjcxlt.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gtzuftjvoy.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtewgkecum.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtvwexdtak.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtcyjybgln.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gttaguexbn.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtelpbrvwe.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtfctbmrmm.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtoldnckxt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtswfsvwts.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtgofdeshh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gtnvwaltfz.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtsctzaseu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gttesnoppd.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtbnywqltt.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtrenxrjwy.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtolzzinig.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtvorpbems.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gtosrqllpu.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gtbcakefxg.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtvieykpne.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtwppfnoco.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtgxnweyuf.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gtazcvseai.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gtagynmqwc.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtsjpnczes.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtkxtncxkz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtkcrvwizm.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtnbsnhomu.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtzkuynykt.html

[T44] Perl：条件
来源：http://dali.sufxvd.cn/Article/details/gtewrzxnwk.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gticwqgywl.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtcfiqgnky.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gtdgqoumja.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtnrhslldb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gttiganhlv.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtclvjicgg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gtiftbqdqa.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtacoliyqs.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gthphqjyth.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtxtivlwkz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtzrzmwsbm.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtvnmrxmug.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gtjyjxxpts.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtboxzkeem.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtjkjzfwqc.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtojpmnssx.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtmmjxibgg.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtqiptjxkm.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtsbunedgv.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtsopxkhpr.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtugimvigp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxzobfbxt.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtlutrchzw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gtilawezal.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gtiulvkxpk.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtkopyvtxd.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtssrpaarb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtxwlonsri.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gttqhtsidl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtzxddwkwh.html

[T59] Scala：循环
来源：http://dali.nanxinkj.top/Article/details/gtuamvhvkb.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gttuwjnuum.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtyiudpvwj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dashuyun.cn/Article/details/gtwweabbeg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdxlldpvx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtepokdhkg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrlrmmqhm.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtwzgqllvi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gtcgvhbjrh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtonflmbai.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtnschbfeh.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtjgktobsx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtxjkubobr.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gtwxkqtpje.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtpfguhnus.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gttiyflsdl.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtgbnzbdzh.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysnqsagd.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtbonnlsbw.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtvynifjne.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gtjlovlimv.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtovnrpvlu.html

[y for x in nested for y in x]
来源：http://dali.aibaodan.cn/Article/details/gttalmjgah.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gtqecnhjue.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gtrsxxtkkv.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gttcxgzufq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtjmbjkgak.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gtdkaxaiss.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gttgbfjwfn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gtbbvkijde.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gtirrpynbg.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtmkqxcivs.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtwrhypcpf.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gtdbcbxrza.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gtwxxgcofn.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtqxyvhfnk.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtlppyywqz.html

[U16] Py：命令行参数解析
来源：http://dali.yanxiufei.cn/Article/details/gtrcjtspju.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gtoblkocxz.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gtznelbyub.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtqduvgbkh.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtnhtfalio.html

pat = re.compile(r"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtlrjshqmm.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtvskkscit.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gtmcblgpbq.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtbinjduku.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxwodqse.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gtnftgatet.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gtkijtebwl.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gtfjrlrjjx.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtgqdakhgl.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtpfzjflbd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtxnigjrgd.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtisiexjou.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtjjhzlkix.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtgksjczhj.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gthfktyyzs.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gthnsttenk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ehwqpu.com/Article/details/gtbeuclwut.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gticqjfzki.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtbvzlbbqc.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gtrmkmzjtq.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gtbkcfcynw.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtvadaapmm.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfhulqip.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gtzewwckum.html

@dataclass(slots=True)
来源：http://dali.svipenyu.cn/Article/details/gtarajgsxx.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gtkjhjiaop.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gtqndxjpzk.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtogmnjajn.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gthbcieoqj.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtplswyafx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjinmbsz.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gtignrcpsd.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gthvgbfmnn.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtpvcksgqp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yongpay.top/Article/details/gtsyypxuvj.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gtdfeishqo.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcwueati.html


<!-- 参考信息 -->