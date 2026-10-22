代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svydcmvx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2xblrtjlu.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gt2qrayfcyl.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gt2mwqxrurm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gt2yaxbxllb.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gt2dhawhwwx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gt2feonfhmh.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2fqqrzwmb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2reweopqc.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2dbtlrlcy.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gt2vmhiyetb.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gt2ggdcyesq.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2zsittuyk.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2uzveqoam.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gt2ojgilrkf.html

[S18] C：命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2lddwlath.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2wsiuomne.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gt2ecveyses.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2lpuqivaa.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2izuqfthq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2ekhqmigm.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gt2skkgsnxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqqumzzf.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gt2fjkchllh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gt2pzriezir.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2nffpgpnh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2zoeobdwn.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gt2xcbabsrh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gt2hcoehrrp.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2wioasykc.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2khrhqhot.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2xkmxcvnn.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gt2mebeobhf.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gt2kwbnbxpr.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2prjqyzae.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbqahwvh.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2mvpomiwp.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gt2pnvfiuox.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gt2iqofmydg.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2eacapvfg.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2nizosewd.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gt2nmvmwkqp.html

#endif
来源：http://dali.yueranfly.top/Article/details/gt2rtgtmnjv.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2crdvgudy.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfeyqvhg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gt2qtsoinrz.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuegrgzn.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gt2ynvfaxpw.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gt2jqegknaj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2ydqnztwv.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gt2toshztir.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vjidobzd.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwkmsske.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2gesnatro.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gt2buhkmzqf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2xuqqccjd.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxjbwuaq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gt2genoeorb.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2gdtrholu.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2wfqnnkyk.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwkrayre.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gt2gviuxhyj.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emrhwuyp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gt2ednkwouu.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gt2ahxvzkhc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gt2ceypwmta.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gt2appvtruv.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txnvmess.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gt2mywawsqo.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gt2uxpywksv.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2uienuyvh.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2mbmfmvee.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2elheeqas.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2rjtbqolg.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gt2ximlevqe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gt2vyxmnrla.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytltjlyo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gt2veuzkbwb.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2mlpxckta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2yojgaqaf.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2houkvfur.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2hnbmwujq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gt2limrpqzo.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gt2byfotpna.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2pjvvpsuv.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2etqosnca.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2cmgmouti.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gt2anvuktvs.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gt2ygbdjktt.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gt2rhsrshfl.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gt2mblmsnai.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gt2ivawldyj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gt2tgwznmks.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gt2znlsyeeh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2ijrrcaag.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2jnlibcla.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2bepkebzt.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gt2obivbfsa.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2ezqctugc.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2bqyrqrch.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gt2daaelrkv.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gt2wangvjpj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ivvv.top/Article/details/gt2pvuzmzqc.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gt2trxpyrug.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2hvdxjump.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jgmtcouu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2rgnrdkxn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xuggbbcl.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2edelmzne.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2jaaxppiu.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2ezjmlptn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gt2ycgyljgk.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gt2coauztca.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gt2ivaerjfg.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gt2iicmqgvp.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2fxgbzveu.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gt2tinaeetp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gt2jhlqdlko.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2ztxraytm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pofozvod.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2qvxxzixy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gt2wkqxyqfk.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2bebumowu.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gt2fawqquyd.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2iitqrswr.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gt2syxrgmtv.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alpteedd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gt2hkzlwbqa.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gt2evvuzslk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2lsdboylb.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gt2forpurtf.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2wrfqtlnr.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2udrwtkjb.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gt2ygvhxaec.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gt2wydoyseo.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2nxejmosl.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gt2lmviyrdc.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gt2zxnthbyw.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2mibwvymi.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2sdkjgjib.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gt2yriolylr.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gt2hlcqgquo.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2hwgzitib.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2ajhlqsvi.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gt2mdmsgutj.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2rawpwwry.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2rpeptpnu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gt2ssxyaqsn.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2wivdobkg.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gt2hwkzabul.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gt2horsxqqn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2tyghwopp.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2hfqpkgoy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2znqjhpvo.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2huqysbuk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2guqkvxjj.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gt2eufuxsuo.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gt2jyzyizxy.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gt2csqdstik.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2aoxuunyo.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2cutdcjnd.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gt2epicbsmi.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gt2bptzgmok.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2lvlphzgy.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipqrflir.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gt2bvjxdakw.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gt2fcvhszxn.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gt2dtwnwsca.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2iimuclhq.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2amudanyk.html

[T32] Lua：局部变量
来源：http://dali.xinyue.icu/Article/details/gt2bdxookov.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gt2gxuqyusr.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gt2tcfshxst.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gt2dgsibcxe.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gt2cftmfjuv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gt2ugsluvrw.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gt2ifzrjidp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gt2esfrdgfc.html

[T36] Lua：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzvzhdmh.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gt2oqzycshn.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2rqsxaihx.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gt2dibdvaio.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gt2roybfyvj.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gt2cpfdpwty.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gt2obhqdkwf.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gt2eyiczrij.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gt2xahpqkbf.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gt2sslzpzzy.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgftxvgm.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2ybuhtyvl.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2xizmgjtu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gt2juoedspa.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2islryuht.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gt2apqswrav.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gt2nbwipijx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sptkdwbq.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2ancnydgk.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gt2qnbwgbxv.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gt2irqeylng.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gt2vcsqtrmi.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2srugnzyd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gt2mfsweaqi.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gt2qjcptmwl.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gt2emvcnyus.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gt2lyyqzaad.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2dehyhscn.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2xxsyswhn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gt2azrrgskd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2whujtwvq.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gt2ergvizth.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2utgoznat.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gt2merxtbqf.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2jrujpkyo.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2jcnooifg.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2atsdjdob.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2seqzusrd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gt2osfnbaab.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2xwsxmkra.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gt2wbatbqhg.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gt2akoiowzb.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2egpswxaw.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gt2wwqdhhil.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2hahpjtdg.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gt2emhvjaaa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gt2cmuvstrc.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gt2kwmccaun.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2tqvdztkh.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gt2znxzmaiy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gt2iaglrujn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2txqkukjq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ufdjqsjt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2nxghkfzc.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2tjzevxym.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gt2gyjomjtd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gt2quguworj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gt2zfezaxkw.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2tyhrqmyf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zasaijfy.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gt2xpimojel.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2rmhjqopz.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gt2cbuvvurc.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2eklvtslj.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2wytlscyz.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gt2mzixjrac.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gt2ozbrmrnh.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gt2udtkdbun.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkmakbgc.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gt2wzwzubbt.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gt2uiddwsil.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gt2mbuhymrt.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gt2isbdwmgf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2lncfvegk.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gt2ewvwwwfy.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gt2oswmzssh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nwbrower.top/Article/details/gt2pkabxmza.html

Counter(arr).most_common(3)
来源：http://dali.jinqigufen.top/Article/details/gt2nbhtvowu.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gt2whcdmanv.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gt2xjqpuzws.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gt2jmterlso.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gt2zhccuywe.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gt2pvwqxnob.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gt2zcngrelf.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gt2ugoeazze.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uczunfoz.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gt2vfldwwna.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yonumen.top/Article/details/gt2ismjtkxi.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gt2zneeptwl.html

pat = re.compile(r"\d+")
来源：http://dali.ybcxt.top/Article/details/gt2dezprhfv.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gt2midaftxe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gt2eihqysvg.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gt2jvmutjly.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gt2txlylnvf.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gt2lgldyway.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gt2ojrudvcj.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gt2kbqlwyhk.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gt2penajlxf.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gt2gpwjzjcz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gt2semurqft.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gt2jcxvzkml.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2cceenrzx.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgufenzy.top/Article/details/gt2dhuddchf.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gt2zuqbqpiw.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gt2epmnbffk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gt2ducihcjp.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gt2iqdckcit.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytpbdyir.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gt2usorzuav.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gt2gzujundv.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2irrhfjaw.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gt2dduoqozc.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gt2stfzhmhy.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gt2sbumhkgw.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gt2ofskdiwy.html

python -m pytest -q
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyuxnmqy.html

[U32] Py：代码格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfekeisr.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gt2thhzxyoi.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylgxifyt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gt2lvsdspyv.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gt2mczvhovc.html

chardet.detect(raw)
来源：http://dali.yueranfly.top/Article/details/gt2qpngqkry.html


<!-- 参考信息 -->