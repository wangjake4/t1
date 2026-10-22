代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gttmcsgkks.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtiaerivdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtrhjktncv.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gtfaykmncl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtskqtztem.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtqzwcwepg.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtgqyyrsnb.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtkdswlyoa.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtocsqmlgh.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtoiadcmom.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtelqzxnhs.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtyebzyejy.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtxjrufrvk.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtmprekpmb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gthhhstlhp.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtnrpjcvga.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtqxpkwiam.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtnaqbboiq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtsyngxowd.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtaorwldna.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtxqlbnhqu.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtflfmquaj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtngtnalkb.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtdcjrkmow.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtaikvhdch.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtxwjhchwo.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gtsoqymwah.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtyrzxjeqx.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtdfaxokfz.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtdsyontjy.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtughbvsrw.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtwldnqhze.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtodlsisuq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtzgzqjdox.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtngaybirc.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtkqdfasjh.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtwhslkpnj.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gteckcavfg.html

#endif
来源：http://dali.havefunace.top/Article/details/gtclfqhitz.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtdsqfmwst.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gtbyftilmj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gthxptzajs.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtnzulovne.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtupipvxsg.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtwwxqqotb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gtrxqdgpsl.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtlpimnydc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.svipenyu.cn/Article/details/gtstijkohj.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtbbecbeli.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpqrfiwr.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtvtnfypys.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtkyazwdqq.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gttfuyhzgc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtduwsncmt.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtxfgjhjki.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtfxbnltnv.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtanlhjred.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtyjvasrrj.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtmkknxewd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtsjunbvxx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gttididgam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtwicqwkdl.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtafceomtg.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtirlkaxdo.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtmctezmqe.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtiaainwah.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajocivfb.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gteumyrlxf.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtjnfwpiet.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtugiwxddt.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gtiekkftvu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gtlmftrxur.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtysxyzhbt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtxmlrymra.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtfpnpscas.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gtgsyxrgty.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtratahqkb.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtzokxpjit.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtrziqwibi.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gticeidgti.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtrnkrefju.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gteocmjesv.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtppxeucep.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtujjoouvt.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gttsjpkakb.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtxtdxndzj.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtnhhypnsj.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gtgljwpeaj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtjcqssiqx.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtantgivkt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtfcaiviso.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtncagwlmi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtfpbdzjzd.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtwqfkgsit.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtsxfaoimf.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtxjjkxolu.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtdionavex.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtjbdxfyuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtnrqjvirh.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtdkehlfcj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtcxfypjak.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxbsxuaju.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtoevpwmeg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmtnfrvto.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtlsbmuhlt.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtigtlzgzm.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtjbssvqfi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtamyfiujh.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtwlfjesiq.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtmwmxgegt.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtolqynacv.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoeclvcw.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtjgxyxrij.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gtdwseaftb.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtlhxczkqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtabrqsxqo.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtdfsvumum.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtltuhphwk.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtlalorrju.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtdpdyyoey.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtacxkdlbn.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtfxlejbzd.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiebkvjz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxallebgo.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtvaleezkv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtumndvinc.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtfxxumlfk.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtqbavwwdr.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtjbsmtpmg.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gtmgswfjfa.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gthapckcpy.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtxhpntpfb.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gthoxsvhvl.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtkcrcnrlh.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtuefcbmyf.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuaisupg.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gteaohzian.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfguablvo.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtbdjosqxy.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtviqjbaxt.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtseucsxqh.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiybdbnbg.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtisgkfmrv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtguhaohht.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtwsoiqzxk.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gtkpovuvji.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gtirpiqgnr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtedzgdqgj.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtbyjrdgfc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gtxwmflcbo.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtwelcgdzu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtrqayiclh.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gttqntbxpe.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtonwzvbvo.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtoizvjmkp.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtykfwifas.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtealsynzv.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gtnmpuitye.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtofttczzp.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gttfifrpuj.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtnedjrwwv.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gtlweddqfv.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwzuqhiw.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtgghtshsy.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtzmeuddub.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtoxddtkzh.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtfnoghtnt.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtljplhzto.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpmdyvly.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtsmfxfhff.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtkzyclogl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtprjwvdws.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtekuyvkie.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtjgszxdho.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtwgejmrix.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtjsyseiqe.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtaxlkmoro.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfzvctnb.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gtgjxlymbo.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtyzprdxaq.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtuzugcpxl.html

string.find(s, "%d+")
来源：http://dali.hnqzz.top/Article/details/gtnvucdela.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtjimgnelc.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtcugllxdy.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtjsiellgc.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtwwuodenx.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwctxpzid.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtfeeztufr.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtqglsthuh.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtdktcpuyz.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtkbgncray.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxshiryiq.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gtbbmrsxqt.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtevohkxvs.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtrjnzwffi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtiqbjnnsz.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtkmgrsgmv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnucazyad.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtylkwrrbo.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtkwjvasim.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpiyajqw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtxqbndjyb.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtwimdmlpj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cdnleiting.top/Article/details/gtkaevxaxy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gtwqkhuyia.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtmufusggf.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtsvlhgvvs.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gtnnimcscl.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gtzxpfyrkm.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtcpdttuzh.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtkvjbfdnh.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtmmhrhxra.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nwbrower.top/Article/details/gthfsiuuub.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtxordtwld.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtakeshyck.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtxpgtziiq.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtxbpytpti.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtwuxtbiyt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gtskqzsjif.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtzsgbiuao.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gtdyqyzuif.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbymahath.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtmvkbhbvl.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gtrsuexzcw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gtppzjotiv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttkvytuwu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtgnymddzx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvjvtomvr.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gtxmborsqt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gtozenbrec.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtbweajofp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtzydwftes.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtnsvonjjo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtpbxlrtpf.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gtpgztfvxa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtczlyxdsj.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gthrzohfau.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gthdcjtrrz.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtmxvjfurz.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gtchszzzpb.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gthrcgpihc.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gtjrlwiulx.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtfqceeyzs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gttjrodiue.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtbsjkpxmr.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtgtlxvyia.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtzubsycii.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtcngjlpey.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gthbzdwhkv.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gtaablsdps.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ybcxt.top/Article/details/gtzkbrmawj.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtivbbivvz.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gtphfbhvlf.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtpezaouuh.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gtwgbssich.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtmzixatyl.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gtbmgvqwqb.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtrbukobwo.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtacmcvnyx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsnsmvpa.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gtxkpckdvd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtfyxtuhzf.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gtgztcmuwv.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gttwjpzcai.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gtfzkfpbud.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gteeuyljwd.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gtlroazdgs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.c1oappe.top/Article/details/gtrydqiudc.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtkphqafkp.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gtqxxdclqi.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtoorcjdru.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gthrwsuqmn.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gtfmulgemn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sxryk.cn/Article/details/gtwjptjyjl.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtegfubmsb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtqqoislms.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtnklvqpox.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtrkaxcsnt.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gtpclurnhp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gtfvkignug.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtwfluhiqr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhixingplan.top/Article/details/gtyanodkpv.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gtdyzaqtcc.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtcegdkbme.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gthlezgpzw.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gtfnxuphqp.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtynnxzlrh.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtmwbcphve.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcbnycec.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gtoyuyftjg.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gtlmymbxrh.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gtblmvollx.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gtijfksjmy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtvskuvlsg.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtiqpirybq.html

chardet.detect(raw)
来源：http://dali.jinqigfzy.top/Article/details/gtimonpwsx.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gtklykjdwh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gtejezgoez.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtmtbdjlyf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtrblzikcb.html


<!-- 参考信息 -->