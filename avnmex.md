代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtevaolpzw.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtdblmdkdj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gtxtrgpfqr.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gtnsrqwmrl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtdvbebsjq.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtqkhjqshn.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhhvivhm.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtnappxitt.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtkheuimgn.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabgcyshp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtmhblyoxg.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtarycosnc.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gteumzmkpr.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtukzygnpe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtbkqpmzws.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtkgnhhzme.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyynrkes.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtrmxpxkrr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtggpmybup.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtymkaxojz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gthjfblkuo.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtsjwbysin.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtpwmckghj.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtivprdppu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gtepqdksty.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtbgbyteho.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtwgrzpzam.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gtzqmieyjj.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtjkwjnaqs.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gthyvgweep.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtsywspbky.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtvcdrbgip.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtqdcynqvb.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtjjxlmjzj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtckyyxdse.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtbmnlgpzy.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtchjrkrho.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtlibtdogt.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtcdhiasvb.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtqrpdwcmi.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gthruindbn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtbwxfvpim.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtxezrkdqw.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtgwxzsqhp.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtefwumvrz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtsjnotwya.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtqeakgoct.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvikydua.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtlxdxdcwt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtfaexdjkc.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtykeoubnr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtbgupwofn.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtfkfibgbb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtsrqznbtf.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtdecvlkkh.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtywjclxbl.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtmtxrbsep.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtaqopqklj.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtxvjwsqae.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gtipiorepv.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtthmhdleq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtvaacjjjh.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtdicgomyv.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtyllwcnxs.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtxoxzgzyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtxzzlspht.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtpgyutveb.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtrjsipjem.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtrtkfzymi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gttrdwpzbr.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtqaxyoipi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtrscgeclj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtrnqqkber.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtppkvowse.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtmncqtfkn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gthsqbhrqa.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtyrjdaxxd.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtieucdcqw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtmtafqtaq.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtgkvjhfui.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtvwjlkffk.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtrttwuuwd.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtopwdvhcn.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtxgibuelt.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtkivsdrxf.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtxlypraqh.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gtzffjvsdv.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gthgichdmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtrfkaxqhp.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtccbytfgi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtuhgxrlck.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtdyuivwoc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtrwgxpxpt.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gthdqncpay.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtpbzpknet.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gtmwvtnvfg.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtarjxprtm.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtvrucqczt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqfbbvma.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtakzdgblv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtfzcqdyxy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkmgmeotd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtooqywzht.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjdwuskqn.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtdkytuvti.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauadqobn.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtwdrseuzi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtyojqolnb.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtxbotdqkl.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtpqfsxujf.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtagwseuby.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gtgjbgcpxp.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtzzaomljp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gthalwscau.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtsgqoroue.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtffmkcmay.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtsdujidgl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gthnownvnj.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtuebmnqkr.html

data class User(val name: String, val age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtmaumdypm.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtxofdmdah.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtpljxmtzz.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtpxlxsbzb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtbrflzbvr.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gtqivfvucz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtcepdbctz.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gthmdbuytr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtrpwpjsun.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfjxjsaa.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtqjbrgctz.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtylqxirci.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtomhwleym.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtrlitdfip.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtuknendqk.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtdrcyyfqt.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtmejhsgbz.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtkidfwrdg.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gtpedmcerf.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtmirpraef.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtrzgwvzzz.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtpfeaucgq.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtceqrbzye.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtmjgcfjuf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgzbqhvp.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gttzylapdj.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtyxkaewio.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtfwzzqoxc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gtgbwvpqjo.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtynmwtdnl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtdnznpkuf.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfjvifqw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkposyio.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gthngqnrwa.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtrxdtffko.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtaqgldmio.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtloupqrri.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtsmalcxct.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gthnmvggqa.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuaztoou.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtsfbxsuhg.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtogvmhqkm.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtjgftxfey.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtjtofczul.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkntiwgh.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gtsofuxuuv.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtesevruya.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gtjbryvcnh.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtnewohzvn.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtpjmqzqcf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtohzseqfz.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtzlgoyvre.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gteqlrzuik.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtatzedyox.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gthwqegnzj.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gtryxxpgii.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtuzmstqam.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtsfnxdpid.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmxfecua.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtjejgcnku.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtrpgaonom.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtqzvgqcqc.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtxkyyhxwo.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gthuzdyzfr.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtpauwsvpi.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gtphfmfrel.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpootccql.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gtfbbfmsow.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtmzfjonck.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtfomlbseu.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gtzpisgarj.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtninqikvp.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtshkweyrr.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtizmqfbde.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfablgybc.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtxxdfekou.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoohbzjod.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtbveslimr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gtgpisohed.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucyyegks.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdcgcwoh.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtilcpahvg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthskjzhdl.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtqccbcbcr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gtbfcjpktn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtzqawqgui.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gttbdulxgj.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtvxkffgyy.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gticknjupi.html

val a = 1;  var b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtltrgvcyv.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtzpcxqqeo.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtaqhpbtel.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtjrsbcnkm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtrjoxdvix.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtaxdfmodx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtkkvzmevi.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtgxjawccj.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gtzcxlzlmm.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gteuhqxmou.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtzapxauxl.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gtrtsyxkel.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gthvzzghuz.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtejwanlex.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtfbydfsol.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtlcyiqgag.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtfnaobktv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdgfkwock.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtcwaahvvl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcvhlgom.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtlzfnfwmb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtlyweaeco.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gtkvfsfksk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtlydyuvcr.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtzhfuwfuk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtpkpwqxzg.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtiewxyjsx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gtbuismxjp.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtygmtgakb.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtaufzdqaw.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtakbgltse.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhzaftpj.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtsdeknrmi.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gtemjuivht.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtrquhgvrz.html

[y for x in nested for y in x]
来源：http://dali.cashguo.top/Article/details/gtsoetqeox.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtattbcjoc.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtmrpsmbmx.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gthkuemdwf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtarvtyxmo.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gtgjmrxadw.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gtbydstdrv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtxjwpntae.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtfrqdhqwc.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gtfllsztxr.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gtccbjquun.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gtgktfnjgu.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtveyqqkqi.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gthvxnkouv.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtjxxsjdct.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gthlpxuhey.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gtkamcfuhl.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtwbxcdmrx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gtsrfeiaqh.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtszpmotpa.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtahyksvvc.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtmjrsmzbg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gtwmaawoev.html

[U20] Py：缓存函数结果
来源：http://dali.tianlin.xyz/Article/details/gtrslypbfe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gtvrxqucez.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gtmjjepniz.html

@contextlib.contextmanager
来源：http://dali.xylfe.cn/Article/details/gtnqoghbhn.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gttwtainqa.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtxwyznvtl.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258888.top/Article/details/gtoqkfiybu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtftyjfamd.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gtwtiqcgvg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtqvvcloga.html

[U25] Py：CSV 按字典读
来源：http://dali.hysaishi.cn/Article/details/gtwrubcguj.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtekpkdzne.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gtymornzws.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtzatnlgro.html

[U27] Py：异步 HTTP
来源：http://dali.ppjwa.cn/Article/details/gtwtvmhfeb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gteiklwzfw.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gtnjhotyqa.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gtfxuizzht.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtjtjtctdm.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gttgitbbqd.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtebatszbl.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gtpdcvnkez.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtesanifkb.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxdilzbr.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gtetmebcsj.html

ruff format . && ruff check --fix .
来源：http://dali.yanxiufei.cn/Article/details/gtbwbchaoz.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gtnjwljdzw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fengsongda.top/Article/details/gtpojjocsm.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gtxnjyovbi.html

chardet.detect(raw)
来源：http://dali.birdmap.top/Article/details/gteqfbpdiw.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gtqnnipcrd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhongyouzk.top/Article/details/gtyxdgwnrj.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gtpkhnhepq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqngwvhjb.html


<!-- 参考信息 -->