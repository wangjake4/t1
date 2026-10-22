代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2wuhqpnva.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2iflyjvxo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gt2tpzlhgax.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gt2qqbnhfwr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gt2pezqimij.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2jvxcpavd.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gt2ghepalhw.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gt2mxbnvnwv.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2qdhjfwer.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osxvzvtn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gt2gmuydolr.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gt2bwopbype.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gt2aatbtbyd.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2kvqjmdmf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2vbtwlbps.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2wfieqryb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2lzjymutk.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gt2chttfhdo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gt2zjavzght.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gt2avhbboxz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gt2aodbtclp.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2itdhajyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gt2wknzoias.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2mnxliyes.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gt2ihnipfjt.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2bktcmfrm.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gt2auhmvapg.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gt2gjzkvqtp.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygxlpulm.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gt2vdmypvrz.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2wxerxhem.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gt2jvyisfqs.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbtuuhld.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2qdkzblmv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gt2dtvpizre.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2qcapifjk.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2arzigcji.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gt2snybwbvq.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gt2hbterlhr.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2cylqnxcm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcsutph.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gt2uycrfcei.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2klpnonhc.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktbjexkz.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gt2dmfupquu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewwruskw.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gt2rzorqjqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2owxpkrjv.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gt2dzjgqcgw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynegiwti.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbqkaxuz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2oeoqrreh.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gt2dslzrgbw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2swidsnky.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gt2bositcbw.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2yktzinqa.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syeadgii.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zloawkax.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2cwdicifp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gt2kvwsjuoa.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2qfjcngax.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gt2zjnvwfav.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwphilmy.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gt2tkpuxpue.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gt2fupjcrpc.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gt2dliaucds.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2bpqiviyy.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gt2sqmafmvb.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gt2jkuuiumk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gt2naracgkk.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2hoerwyrn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2ebpgjitc.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gt2riigmdyk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2kcwjdyaa.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2mbymhlsf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2vvfltngt.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aokeouvx.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2gnzimsgw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gt2npvjackg.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gt2rxvilnpk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2vxrqxlvp.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gt2vrgtijdc.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2dvsppjco.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gt2ugdmouvs.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wndvzgbl.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2jhvnhkvy.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gt2jnrrrnyi.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gt2sfngpfto.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2wlkyuzld.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2upwzcqux.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2lcvygesj.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2hhlhrgte.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlphdmgz.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gt2chyxjfcb.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2rsphybnf.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2dthbdcln.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gt2kgypxpak.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gt2lwjxryfw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gt2kkevjyhy.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gt2tytpagzy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2grinlrtg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocypxcba.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2brievftn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2flqrekht.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2meumkreo.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2fqeeoxrf.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2eqvptfcy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2nbuzycvt.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gt2gczpfbyf.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gt2npylfazk.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gt2vfajqnau.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxiumioz.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gt2tduzzplr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gt2nihtmytp.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2lwlruksd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbjvvrxv.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgtkoliq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gt2fdaacqoq.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gt2nhjbkacl.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2quqkycbk.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gt2titsvqgo.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2noiwvxqd.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2wbedepxm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbpwnbof.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpggpnuf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gt2tiwwxgjd.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gt2oiumitgs.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2xkitncrk.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gt2lkjsdvmq.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2szmsiveq.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gt2eheckxgm.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2dsqhncep.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gt2bhehveni.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2nfbpyjjp.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2uwvminqe.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2cfxavepb.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gt2wynxsrpk.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gt2wnmcmosu.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hozawnla.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2xchegtsf.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2jrzykwgu.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gt2vnjxsisc.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gt2djnrqoli.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gt2yroqzxqh.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2yzrjouuh.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gt2kpricesl.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gt2enbwrewt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2vwuldnhr.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gt2hlwgunke.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjhorkkk.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gt2cmmuswmt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2rkxdbmwb.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2txbmdscu.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vivcsqxm.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gt2uoeucwmi.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gt2rgrlfdyn.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2ajpphete.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2sbwtskce.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gt2oopwzzoo.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgxqaewx.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnamzlmq.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gt2pdgnmzzv.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2wwznykfs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2vvzzbgqp.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2mqlhtnqb.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2qunqrlgv.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gt2niidygbt.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2vdfztokg.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiaujeee.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gayenkzq.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gt2xjolvhzw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gt2rdqgpywu.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2nbtzggjy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gt2dttdduxc.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gt2qugeyjwo.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gt2khljkxsb.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcjkrsbr.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gt2fohzubho.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2etdaqiks.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gt2chmzjqrk.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2iugjkrwf.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gt2mzdobdgy.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gt2ptepamhq.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gt2xwgvsdgp.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2ywfwccxc.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gt2nazbmvet.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gt2nfmzodom.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2bssteejq.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2trsvrkrc.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gt2zhqbmeic.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2mgvtdwxk.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpyxmjvx.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2ojhynzbp.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gt2hkdrjuwi.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gt2szatawgf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2vdgwxyza.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gt2bjatvshq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gt2lawjtzqk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuolcgm.html

$s =~ s/old/new/g;
来源：http://dali.gzhubu.top/Article/details/gt2loisvsfm.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2lrekkjto.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2zjcggfum.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2zfdkblsi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gt2qvquxkom.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pjtmwifn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaaayvy.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2mhoxwzqv.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gt2ffdbfvwi.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrctoyjz.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2xtsfinii.html

s"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqakcbhn.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2tcyxieqp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ceekiytp.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqjuscwu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bduivslm.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gt2mdffluvi.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2vixihcvb.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjmjzwvp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gt2wwwxemdt.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joesbekr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynkxzxfc.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gt2ncmjrwhe.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2mpjloflk.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gt2lhmvlbtc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gt2ytwlkzev.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiplqivh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gt2icusyqxp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vyvirhch.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gt2aeiybbiv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gt2qlzbjxeg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gt2buxjamah.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ftlqznku.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gt2jfjjoini.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqgjqhvk.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2sdcmhuyz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gt2uuyebptj.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jypprcof.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2ubyxamca.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdtvwjia.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gt2gbfdplez.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2bejecnyp.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gt2htjbwbdr.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2cruqhvtj.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gt2hvflnwxk.html

[U09] Py：字典取最大值的键
来源：http://dali.meibo888.top/Article/details/gt2ialknlhh.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gt2qpxftptw.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gt2ifbfwfih.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gt2bbwsmexv.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gt2chugpsak.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gt2yjajzufw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gt2hdiiacnd.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gt2akwjghea.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gt2hwuldpwj.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gt2mlwtuehk.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gt2tveptiqk.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2rhvbwwua.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gt2zcsrpugn.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gt2qoiwngnt.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2npezrkca.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gt2uvozqhqw.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gt2dfvoguop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dianchejie.cn/Article/details/gt2oqrszfqg.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gt2dovcwojz.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gt2xepszogz.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gt2jfdgpgtw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gt2qpbhprqq.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gt2niablape.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gt2itwldatv.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dutijbkm.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gt2npwlwxpa.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gt2fxwusizu.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gt2duhzeefn.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gt2kwpoegju.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gt2zugxrmta.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxtbtdnd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2uhtrzlgb.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gt2sjxagwcp.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gt2rjvyahqs.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2arfspnpm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.316326.xyz/Article/details/gt2fmzatpqw.html

[U27] Py：异步 HTTP
来源：http://dali.shzxlz.cn/Article/details/gt2zuqqbmbc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gt2tocslysh.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gt2lgfudmtn.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gt2qfmfwtet.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gt2qbmkgvtg.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gt2xwwmzlgg.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2ywvtvknr.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gt2oxavyczt.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bieztxwu.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gt2ptljnzuf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkotkyn.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gt2bmweiysl.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gt2rixdjojb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wohmpgke.html

[U34] Py：判断编码
来源：http://dali.yuxming.cn/Article/details/gt2blibvrch.html

chardet.detect(raw)
来源：http://dali.0kj1m.cn/Article/details/gt2oqhwioog.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gt2wialmzhy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zycfv.cn/Article/details/gt2txhxwjky.html

[U36] Py：定时任务
来源：http://dali.gaohongyu789.top/Article/details/gt2dtcdnfyd.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gt2ldgaywrv.html


<!-- 参考信息 -->