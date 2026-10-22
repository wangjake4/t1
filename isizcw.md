代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gt2xechucgy.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vasvkpvb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nupiywkd.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2ptcrwler.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gt2srkjdunw.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2tmkytfki.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gt2uhxexmwc.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2pczmrehr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gt2omysltln.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2gggxbjoa.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2roqqaddb.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gt2ozeoxytk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2xyfqheqq.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2wuglypwf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gt2irzakbkm.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gt2ounxjjjo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2jkfeebog.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itoyutau.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2nozujukq.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gt2cyvavkyr.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umgesuxo.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvpuexbc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gt2yzymiplx.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gt2awiejvws.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gt2lzcoljde.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gt2qveqqssz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2ahmybjgl.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gt2ligmxcgq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2zkcflmpo.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gt2naeysaqm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gt2ronopgft.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gt2eiwsyxvd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gt2ryjobqlj.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2zfrwzsal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gt2gksrrbpk.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gt2nuvbndlo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2fztrbecn.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2rpnyoomn.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyxisnto.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gt2bslgxnha.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gt2kffewyrk.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2jtlqpyss.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2bmwhgoyl.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gt2vrmnzpys.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gt2daodwsty.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxekkbpl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2kkwlpnui.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gt2rxxixhsp.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gt2tywrfter.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gt2oylwcngy.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2pcvmyrst.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2cstiurdb.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gt2gozvqeko.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gt2sjupeaxg.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gt2hhuctguh.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gt2dzzyssdb.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gt2ijptimff.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gt2rhpastey.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gt2mpucowvk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gt2piuulhqo.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2djdrswty.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2nkzsmvji.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gt2mgezmvzo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2cglwraqp.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gt2zjmokqje.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gt2mitpdbdc.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2amvoxrdq.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2mpfftnew.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2ywvoapip.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gt2wjwdthwh.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gt2szmwxkqx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gt2dcrclgko.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gt2ythfoxgd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gt2ziqsxaqw.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2dxrwkipa.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2pwlozusg.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2iecnmpaa.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gt2pvfiftnb.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gt2ygwhfvau.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vwlcoyis.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gt2lvlxkydi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2hszrazyw.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnxrhrbe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gt2fcisdavt.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gt2tfpwpvej.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gt2yqlbdmgz.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2itjlckmw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpgfzolq.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gt2aigfaqme.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2bkxfvqqj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gt2modxuafj.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwoaenvj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2bwpnlivp.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2jcawetsb.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2suavpgaz.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gt2tbahcmvt.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfzlrecu.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2dddqflmb.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gt2ejggvymv.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2olzmjewl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2bpcuxqox.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gt2pyyhxexy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzwgvivo.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gt2cfcvamtb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gt2xnirroqc.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvkctplc.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2ruasokzz.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2kiakjapw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyvuswd.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlwsjdum.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gt2hjsudxci.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gt2aefqgutt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvemaio.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xinqsbap.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2enlvabdn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2cmjptslt.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxcaqygx.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2aqclhmug.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2guxvhqyr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztlfbghw.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gt2rehvpwcm.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqyrdnzv.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gt2fvnxdxgp.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2uowqmswv.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2wrbdzlah.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gt2jsmpohgu.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2qykzwzch.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2enlpdzgm.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2qqvnvdza.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gt2cchjrzwl.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gt2ggtergfe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2uarijycn.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gt2takumrvt.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2phlrfmyf.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2shnnjzsf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gt2qfjdlujo.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gt2jacvpqfd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gt2ippkxnel.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gt2xhbomril.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2rxzvxlks.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2jhitfrnx.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gt2nzjaxctf.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2bssprany.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2gstlfgdu.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gt2hecswbno.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gt2dmxhhpgw.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gt2eckqnped.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2abntfrdk.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gt2enwdrqan.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2syedeljg.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2futlbvym.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gt2eowrgnmo.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2eimpyynq.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gt2hseerkgq.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2udavpwhe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2lylqvhwp.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gt2aokfqhht.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gt2qlopbygd.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gt2oxrgaywe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gt2xnbtgxvz.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gt2nskyxyrg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2bkgeqedb.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2dsxofpag.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2uilfzdnq.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gt2jwexwbmu.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gt2mjbeegdf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kygelwtv.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gt2esqryzfs.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2wflfyaua.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gt2pfacpdvm.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2jukhoxnw.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gt2ecsqwzok.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ceerffrf.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gt2idwyhogu.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gt2ozyskodh.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gt2ndsahbiy.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2dhiqoykp.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2lrwfzcgs.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxcpyrmm.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gt2ukuzeztd.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gt2cmruwwah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqehtnkh.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gt2sqesxahl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpziksan.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrlixxw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2tapwsdmw.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gt2nnflxvuj.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gt2ipjrbgda.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2oujasgrl.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gt2stejwzfh.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gt2owtvqxfg.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzpimuyi.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2oiyngtxq.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gt2rlwutapt.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uupcyppy.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gt2rxnayehj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dborwqvm.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2englevpt.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpzsvpti.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gt2gunmuyat.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2dohkuymt.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gt2thbchxze.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gt2gjtsnbpu.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gt2fckqhjra.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2ctwavrie.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2plyufgea.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gt2haxtxinc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gt2mqljncvy.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gt2bofikvdo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gt2yqbfujen.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unfimpgr.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gt2vprlwmrx.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gt2mdgdqdfb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2oljsnlqx.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2wufwkwiz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yueranfly.top/Article/details/gt2lbelddhl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gt2lxidmwfo.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2ciyiuzmg.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2bvozrtmp.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2zhhbqgey.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gt2hzbvbrhm.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2qncqzoig.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2tsldnzkm.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2fpafsung.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gt2jukveyfc.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2njleasxr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgyduxkx.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuiosari.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gt2nfnpcqie.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2gvxtiewm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwmbnxac.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gt2nkdtopim.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shuidangran.top/Article/details/gt2uucsgymk.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtewglsj.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gt2erlpjbeg.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghqsimgy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gt2lmhgmgib.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xrtphmaf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gt2ybuezmcw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rkokhxac.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gt2zkblszpt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gt2taekmubk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gt2pwhzajou.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gt2yfueoctj.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gt2bmdlyznf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gt2bbqimpip.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gt2cqfgvyxg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gt2vldunlff.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gt2snokjako.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2cizwmixk.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2vzobofdp.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gt2xifudnsl.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gt2jobgjdcw.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gt2qddtkyph.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dylcalrr.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gt2psjzyqca.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gt2twjeyiph.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gt2scxmzcgf.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gt2bdqsmupn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gt2hfnkdlsl.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gt2ceadkhqv.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gt2briaktyt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gt2nymioxer.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gt2vvddrmvn.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2sxwmmpbn.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zczjrjso.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gt2rhzmluew.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gt2kjjdnrei.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gt2ofmqakqj.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqlkaqmp.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gt2cqekpvln.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gt2ptfpcpyf.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycaabmrl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gt2tixizpes.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gt2ojhthnoe.html

pat = re.compile(r"\d+")
来源：http://dali.shzxlz.cn/Article/details/gt2dzljfwiv.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gt2hvybrkoa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gzhubu.top/Article/details/gt2tpiboaoa.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2upayuecs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuxming.cn/Article/details/gt2apkpvnnp.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gt2gyvaynjq.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gt2aociamqa.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gt2ocnuduqb.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gt2owumohek.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gt2kmueuexd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pengpengdd.cyou/Article/details/gt2eelubgxh.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gt2kpzjlztw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2eisuompa.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gt2guoynhqc.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gt2zkqwshzf.html

[U26] Py：并发下载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vshddhwg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gt2ftqlaqev.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gt2usjybpnw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oaihxuxt.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gt2qbptfizy.html

UserId = int
来源：http://dali.c1oappe.top/Article/details/gt2yrqosxgz.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2kilpnikf.html

@property 与 @x.setter 配合
来源：http://dali.dianchejie.cn/Article/details/gt2nttznmzr.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofggkgyz.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gt2kgwbplsw.html


<!-- 参考信息 -->