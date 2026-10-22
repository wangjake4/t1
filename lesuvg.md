代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyfenvti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gt2ihukazga.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2orgxybib.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gt2vcempyne.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2atgqsfbf.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gt2lafgfldi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2zkbozpnx.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2ercfkndg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2pxamezvc.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gt2imkgwoyb.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdczrobm.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2enleoncm.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2odqasvxy.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2dfgowagz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2kvguleqx.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2dcbkjmkr.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2izccmwgp.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2bmxahfge.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqvgfqzl.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvfohtpd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2bixxiplf.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gt2qkjwpzlg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2cvjuvfjd.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gt2tterwjat.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gt2qtdspdwl.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gt2rzqhlnou.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gt2cbvtfubr.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngozpmqp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2tdoflnrr.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyddovuy.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gt2pngfwgdb.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndzsxjjm.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2exebndmr.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gt2kopkuazl.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2ahlgwnax.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2znkxlsyz.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oaxsbmxg.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2pdzfwdjs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiuphdmp.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gt2bqqkwqts.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gt2phzxnlut.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gt2ilfbgekg.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gt2uzwgapml.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2gghrktwq.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gt2lootfvtz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gt2trqzjrvr.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gt2axqrglsm.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gt2qfpeegck.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gt2xxbvnxgh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqzcjvyu.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gt2wadmmanl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gt2giwilnmo.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gt2osztuasb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsnawlov.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2reiedeho.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2xjrqusvu.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2qaghaqeg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2dezzchzn.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tghlkdcq.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2gecvcolr.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gt2apdvambw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2fyjmsfcv.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncfznfft.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gt2fgkfbyho.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2xyugsoyu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2hddweygm.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2oxglelhz.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gt2czbjbwtb.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuptbvpu.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gt2nbcpgquu.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyuxfzar.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gt2gdhjgtgw.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uexgxtws.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtuhyzl.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gt2rzcahsjn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gt2pvmydmnt.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gt2kdytnbcw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gt2sederrut.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcbuyiar.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gt2jgjsyray.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2yjrbugdc.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2bkbjmwvr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gt2vrnpemwv.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gt2srprhnyl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2xrfdoltb.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gt2crpmjslo.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gt2tcjnrgpr.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2osgrzwcc.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gt2vfqekjbk.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gt2ovroxokt.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nitqtxfq.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gt2aafyimhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2qzcwrwdl.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gt2bvddllqz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2whqwoyun.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gt2sveuhxaw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgkjmbpx.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gt2zguvftxc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktynkpsq.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gt2vwjdqpkm.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2xutmshjb.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gt2nrezhztg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gt2nlhwpjmk.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2ysepzzbe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2yqtacfqx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2tysccgwu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2bncmbtrt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2qczjctvm.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2odbuwktx.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2wdnqednk.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2sxpkyxcz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gt2gehflbwt.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2cnxryuph.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gt2kxpngdos.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gt2wdqqhwtn.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gt2gizpqull.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gt2xsejqtch.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmpvhoix.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkzmfefn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2qtsmsbxz.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2lrkoweuz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gt2xnxheojg.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gt2mniljnix.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2dgwpduip.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gt2pzpgcjus.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gt2kmrpxpje.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gt2ptsknlyp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvwjtwoy.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gt2hcgmkjyb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2ekpmhqdm.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gt2ymvozmtt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqzwlbej.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gt2poqnrxey.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gt2rdxhosyq.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2cgpfardy.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2muwfqqpw.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkkdjsuw.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gt2vhkubdje.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2smsbscow.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2rvhnevej.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gt2odzokqmu.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhdkdyfv.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2qxcpbiqb.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gt2hmsjuxgq.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2gdfakmgh.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gt2auqtcyiu.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2cduiswix.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gt2lyztciiw.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2fkpbnyyo.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gt2thsgugcz.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gt2epiqlwre.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gt2ivkwjjro.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2rtdjkuxi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gt2eexxzdrl.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gt2gxnkwdue.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2mvxwqxkz.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gt2iiwrkuni.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gt2zmsnxzdi.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gt2orrhuprm.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gt2eynbcvml.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdalsrdn.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2tlbqbenu.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2rvjlqbnu.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykzlkpoa.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2usagozeb.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gt2vhikmrnv.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyvpoewg.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gt2vlvkbdpy.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2tejqxmul.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2azjtarba.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2jxfrmzag.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2rmkmxwve.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gt2onyiuike.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvrtchp.html

[T34] Lua：遍历表
来源：http://dali.daxiang520.top/Article/details/gt2ykftfupu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gt2qpkfmfjb.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gt2xzslfhom.html

local d = { a = 1 };  d.b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2pgawcczn.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2clkpotgi.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gt2sawkrkcx.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2ppxvzvsu.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gt2djdeyvgv.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gt2iyrcpfud.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gclfnvhy.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2vugabohb.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gt2qrdpbbcl.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzrpolxd.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gt2wgbadzfm.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2vditovjo.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yclzncdg.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gt2zboylzzq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gt2msuxibhz.html

[T43] Perl：字符串插值
来源：http://dali.yj20258.top/Article/details/gt2bnaykiun.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gt2umdethkh.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2oelxnmzk.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2lqwvhssq.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2kdnfmepd.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gt2lmwpfqks.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gt2dxfumsio.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2dzfxjpbd.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gt2xjuhseku.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyvgezur.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gt2vsqhquaa.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gt2wwjtiaxz.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjxnmgfr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxvtgrpe.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2hfqqqspo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gt2cpqojoxg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mtfjtlud.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2yrblfihr.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpzbwcbi.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gt2gelttzse.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2oinlutjn.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2rtexbuhz.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktdzjmbj.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kapnscou.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2baycqisk.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2bbqzygjo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cucudq.cn/Article/details/gt2wefgsmdj.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gt2kvquweus.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2qiveazwx.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2kmbiwmmt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gt2nrruxnet.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gt2ntiyssjy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gt2vtxzurnd.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gt2melqdhef.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2aaadcars.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gt2lnsupfye.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gt2omtjhvmx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gepmagbl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2cbxzfmgo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2prlggisq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xycoefjw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gt2ywyoctvy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gt2hoarykkb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gt2dcvlsuub.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gt2jbrtyqwc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gt2swydgvuj.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gt2hsmkymfo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgrwhnnc.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gt2qlluyzlm.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2vyjqxwoy.html

[U06] Py：合并两个字典
来源：http://dali.jinqigufen.top/Article/details/gt2ckxkdebh.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2wqeeqead.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffgvccrh.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gt2mlvsvxbt.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gt2mhkpgczi.html

[y for x in nested for y in x]
来源：http://dali.ehwqpu.com/Article/details/gt2djbkjeln.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gt2otwlppuk.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gt2qqjcqklm.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gt2lhvupbat.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gt2drvivasa.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2hzuxxmix.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnjsxmif.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fengsongda.top/Article/details/gt2qepnmhrz.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gt2rvskrctz.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gt2rckwqpte.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gt2bamwbbeq.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gt2gkgcawva.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gt2fnjyzste.html

[U15] Py：高精度计时
来源：http://dali.hammf.cn/Article/details/gt2plrjspla.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gt2nvesyiue.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gt2guobkzsl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gt2mhqtusdo.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gt2dywgyqmw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gt2fgkifzsa.html

[U18] Py：预编译正则
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgqyxgfy.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymucqfuh.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gt2tobbjtrg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gzhubu.top/Article/details/gt2txqdprfs.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gt2tiynfygq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gt2vyhuqynl.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gt2jvzqrmib.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gt2exfiuhkn.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gt2hbapjtcq.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gt2wrixehxg.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmbzbcog.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gt2svrmsxth.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gt2ehbgwpqg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2dllwnyyo.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gt2cmbesopu.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gt2yxhhiqsn.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gt2qakcpcym.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhiwuduotai.top/Article/details/gt2whvffjvq.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gt2himlhnxh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gt2ltophgkg.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gt2arshsjhm.html

UserId = int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyjuifnf.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gt2vvewrcxi.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gt2cdhnppwl.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gt2fowbeinw.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gt2thhxbbaq.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gt2gpvwugtj.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gt2zzcomdor.html

[U32] Py：代码格式化
来源：http://dali.fzhhl.top/Article/details/gt2ryuhnajo.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gt2roqalryu.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gt2eciieusu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gt2tmytnnwa.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gt2iweazvob.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gt2lghwmndl.html


<!-- 参考信息 -->