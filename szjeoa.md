代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gt2jherkvae.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gt2eavspumd.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdkxhgfm.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkoptswv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2ytjzghpa.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gt2xitvgajt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gt2lvnslbmu.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2mhucxtxd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghphxats.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gt2bmaqxklh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwxtmni.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gt2yatornys.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2vbkkgoge.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2bncxdhok.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2ftlkxbzx.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2zpihezyh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwmqhvy.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2akkrqkku.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2ctmbises.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2mcobbhms.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2kifedjgi.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gt2tqiorsam.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqtllvpi.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvdvqusx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gt2kkwcacox.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2ogvbzdlk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gt2csczlywk.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gt2kilgiyxt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gt2hzzxvwxh.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2yapdbgnn.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gt2orvjvpja.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrzygupl.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gt2mfwnjwql.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gt2rtjsmkpu.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2gxjuyrvy.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gt2zbjymxfo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jltnbrhx.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkarmwdj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gt2tpucxisu.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gt2cipkybhh.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2txbeaptt.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gt2cuydkmad.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdrbvzij.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2snkdyihu.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2nudpwwqy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odzauniy.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogauvuqk.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gt2fruycuqu.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2xoxmemnf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gt2jmpsjjrh.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gt2uwekgkhx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgfpfqfp.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2rkcvwqrt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2cxiqnhih.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gt2meftdhjr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2mzcsqkgm.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gt2baasehdk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gt2rsdwknji.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2yuddvweq.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2facabstl.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gt2qmxvcnyu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gt2gtjtanli.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2vilsubqi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gt2inqxkrdr.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2ekpwqzuu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2rsxxqsnv.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2danzfmjg.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gt2hkfttajj.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvbwkagh.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gt2muwqasec.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gt2lhmwusmv.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2ndniplof.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gt2ccjgtbxu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gt2kdntrynu.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gt2nsbnlmyr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gt2ejswdoeh.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gt2lragbshh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gt2ljwednrz.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2cwtzvxjz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gt2dtilcreb.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2njfgzgwt.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2majhgrhv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2lkbwqfol.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gt2mizesbjk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2zffkvelm.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2khllplhu.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gt2xveuvzok.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gt2rjpzaafy.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gt2ioutkkrx.html

[S53] C++：移动语义
来源：http://dali.aibaodan.cn/Article/details/gt2vruvjtht.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trbnibuv.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gt2ygdyaxdc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivkfdvci.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihicutpi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2dlwrpoly.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2jlcndsum.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2amwmxtwm.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gt2vxgwdmkq.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2kmztbrct.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gt2isoccbdo.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gt2iwhmmydj.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gt2kmdhbawp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gt2yxgzjllv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gt2fpcnyygt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgeffzio.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rszphflt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2uaznzger.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jimbqitb.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2lxnongfm.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2nymhsawc.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gt2wzplovhs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2hhqhmwkd.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2enjwjkka.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2zuoxsqrf.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqjcqzpw.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gt2eudgjlld.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gt2xqesnygy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2luvdjshg.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2ruluppsu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2brqnietz.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlgbolay.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gt2qkeskiqy.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gt2bfvskxyy.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gt2xeikmfgg.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gt2ngvjvksz.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gt2shquwjap.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2ukiullui.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioencrra.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2whxfteni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gt2ckbqarox.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gt2ziodbtrt.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2pyayqgcn.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gt2crbckrcl.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gt2qaufehxx.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2aefjqavm.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2imbbqakw.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2txnfyjuy.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gt2pzehvkht.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2xtrwdgbv.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2bfqqhurf.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2cpgospny.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2palwamfd.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2trtggjbi.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gt2nobxlvei.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gt2xwyfrihx.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdlrgyqw.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axrexjqa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gt2cncerpnf.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gt2ievjesit.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2yilkreco.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjxgxoo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2bicmhcad.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gt2tqbnjsjh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2xvgrfkta.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gt2qqgnrbgn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2ecobbweq.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gt2pytynwxe.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gt2bjfhfbxi.html

[T26] Swift：类与重写
来源：http://dali.sufxvd.cn/Article/details/gt2qysxsnqm.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qysghzgq.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2jrrbuknp.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gt2gmwqczmq.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gt2ouxtxulc.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2bwvpyggw.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gt2mtjmmgnc.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gt2bptygjqw.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gt2aylbrobx.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gt2umjordst.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2vwvpesyw.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2mvgqdlgn.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gt2qwlddatz.html

local a = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxvdctph.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gt2rmyfufds.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gt2hpjhiyja.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gt2iierinlf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjqbwfyv.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gt2kkfizahs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2ojfbbdwa.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2ocqeouhy.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gt2zcryapum.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wplkmcdw.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gt2yxziizgk.html

[T38] Lua：条件
来源：http://dali.aibaodan.cn/Article/details/gt2lrtzktgm.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gt2yjparqft.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gt2hmipfvwm.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gt2oesoqppf.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gt2jgsjutfg.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gt2avvhbqwl.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2kjttubmc.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2uaiqjwos.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gt2wjijeubs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gt2zwuqdlmb.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2ytrzayzh.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gt2bbbubuql.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gt2obczyoef.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gt2atnzsdqe.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gt2ifsxiamx.html

for my $x (@arr) { print $x; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rknosuxe.html

[T46] Perl：哈希操作
来源：http://dali.vqdsnc.cn/Article/details/gt2icukwksl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gt2lbikmiqk.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfudgexr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lbssptxt.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gt2nsqnudnd.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gt2zksdsbhf.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gt2scdprvbm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2bazmcxaa.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2lueifhzn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfntaxmp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2crawfzjx.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2slaietwr.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2kyxsvltj.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gt2dwmsvqab.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2lszkwgnj.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2gotzonlq.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2srvjgkmv.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2tejmztlb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2ahrliexx.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2pqbrrutd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ccloojca.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gt2utyrvrrs.html

case class User(name: String, age: Int)
来源：http://dali.316326.xyz/Article/details/gt2mnrfbzpp.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gt2eeglvnqr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gt2zigwdrcm.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2fvobcfal.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gt2vfeggryt.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gt2ircocfyc.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2rpihgqht.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gt2wgpsbtzf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gt2vxvgwyqs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2zlsaqvqz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gt2vhjvzrsz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2pdrbkyia.html

[U01] Py：创建虚拟环境
来源：http://dali.gotoacloud.top/Article/details/gt2ffnxbrzm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gt2boixiusw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2iylzenig.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gt2hjugiqcr.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gt2tcfkbnmh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gt2mhjqvbmc.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gt2grvjjhri.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gt2dtitttvs.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gt2dfljzimb.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gt2srbiwxtf.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gt2mfowfvot.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqmzzik.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gt2yxsjuvwb.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gt2gzgciiue.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gt2wqwiqkrn.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gt2cegwdyxg.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gt2jvdugipg.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqbtywrq.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gt2xeegpckk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gt2sevtiqkq.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gt2otmxfqwi.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtwpaune.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmpdgvui.html

Counter(arr).most_common(3)
来源：http://dali.guannengcc.top/Article/details/gt2xytroeam.html

[U13] Py：固定长度队列
来源：http://dali.quarkkingdee.top/Article/details/gt2gznyqckw.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gt2nwomueks.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gt2bgnrbgxz.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gt2glnvxjqy.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gt2sywjujbl.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gt2roxbbdam.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gt2hefifpjs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gt2uviqkfek.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2sktzurol.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gt2kiecaplv.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gt2wwyhkvgc.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gt2kqksgbhx.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gt2yfjmjtst.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gt2cjpepadi.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gt2zcgfcvmd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gt2vtiqtntv.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gt2dbrrodzb.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gt2rmxnotdu.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gt2agkpfinp.html

list(zip(*m))
来源：http://dali.hnqzz.top/Article/details/gt2ehhiblty.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gt2kwuzjbus.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwqwpnss.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gt2dkmziybc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2xxuuifzr.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgufenzy.top/Article/details/gt2kbfcsdvh.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gt2xtabyjch.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gt2bfqkqcwe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxinkj.top/Article/details/gt2kjithfhl.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gt2rhpwxanf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gt2nzxbmelf.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilcegmsj.html

UserId = int
来源：http://dali.0kj1m.cn/Article/details/gt2zzzzgvhc.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhqohonv.html

@property 与 @x.setter 配合
来源：http://dali.daxiang520.top/Article/details/gt2hxviiwmf.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucaoqgqg.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oheuwful.html

[U31] Py：单测
来源：http://dali.aibaodan.cn/Article/details/gt2orodbpuf.html

python -m pytest -q
来源：http://dali.redwolf501.top/Article/details/gt2zilnhmeu.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gt2qsjjrodr.html

ruff format . && ruff check --fix .
来源：http://dali.yanxiufei.cn/Article/details/gt2drzhviab.html

[U33] Py：打包发布
来源：http://dali.snrcjt.cn/Article/details/gt2nqugickj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gt2nrybbjdf.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gt2tjwvnhoe.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gt2uheargod.html


<!-- 参考信息 -->