代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtqphdvlct.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtmwwlbhym.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtkzylpwrm.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxeldykgb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtxbxxiako.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtfunewlnu.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtkqrcqdah.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwxavowk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtbczfposk.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtablfymdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtrgbftzbq.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtrksxvecg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gtfsjelswk.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtadbonura.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtxzhtnohc.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtbdsanksb.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtdbqfyuky.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtuybmmmlv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtgvywdwuw.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtrtpwbzia.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtywparbcw.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtrhyilieg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtpolpvkvg.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtlvsnqkgz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtwqijmmcl.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtvsjwfyui.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtoryqxmyt.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtbmervpdh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtweyfmcce.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gtqeezaene.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtopmcdjko.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvitmkzzr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtxewhinbu.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsluopry.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtbyqzfyka.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gthmhdxgxk.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtrbeqolng.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtmmsjsm.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtfhexyepb.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gtgyfvquqk.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtmatyrofl.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtszbydqdk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnymecjgp.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtbrguless.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gttdjswyiu.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtpqkawplu.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtipqjvfnb.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtjacknqcq.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gtchdhngaa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gtbipnalvg.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gtwvxskcku.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gthgvjfjwp.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtjhfdibki.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtujbqokyd.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtysltrrir.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtatucvocq.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtyygstxfo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtdemzfmhj.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gthojkjwwk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtkjnafbvl.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gttlkydmnt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtmcnaefcy.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtoeziexoz.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtkqjjwvjn.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gteuerqcnz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtkwzewnyh.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtuuqrukpi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtaunqapmc.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygxuejpa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtfaagoqry.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtwpnertvi.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtrwslzcjx.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtzyafnkwh.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtfrvqtxiy.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtsxqolxzg.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtpgstevjo.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtvnectkhl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtjxatjfns.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gtceyzzpee.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtxqpozrje.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtlybhwsnn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtwsutdayn.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtodutrykw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtnqxaghef.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtlrhrdjfm.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwsincev.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtbydkahwu.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtzwuwdbbj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtkjqhkiyx.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtjkqcmggi.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gthinpuijy.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtcrxoxnwu.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtbxpxgjbj.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gtphyfmygl.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiftyrum.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gtixfiybyp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gtreewmnhb.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtmuozsvrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtrmsbxbjb.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtzybnbxok.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtzimlsgqb.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtvohkhogq.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtrmnykjky.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gtbnyksrjd.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdykcrqtk.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtamljujwo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtthgkokja.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gttxievrlj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtsvocblym.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjheujzne.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtmqcpejde.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrvtjhrxt.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gttkqgbdle.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtbkynzjbl.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtgrnuiirc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtgufmxidb.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtjeocvijc.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gthvylnykd.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtyhqwehoz.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtaghfqzix.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuexsdgbg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gtrmyrbxmu.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtwvvhfrwp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gtapgsvzhr.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtcdvbrvvp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtfmjijxif.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtreifcdyc.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtxucbkqvs.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtopdrdvmc.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gtbiyxquvk.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtkqtglbpa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gtluhmpusb.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtzihpznrj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gturchhtde.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtjnbvkkzf.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtqmbnxqxm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmawdsicc.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtqfvhktij.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gtokdgmbvx.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtqbcuybpn.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtvshtwpet.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtaqigxjtw.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gtkqiwqbfb.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtyqzmfbvn.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gtaxztkgvz.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtsxccjfou.html

[T18] Swift：字符串插值
来源：http://dali.yj20258.top/Article/details/gtbzmbbojj.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gttmoanpgd.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gtcxjuqwlw.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtcmlimoyc.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtkzpqfjwy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gtnvzuvbpg.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtehmbqrww.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtpunwjeag.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtsmtfaswq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gtxupsrdmo.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtbzgywvpa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtpigaflrv.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gtzlzjsoqy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtxagfuoks.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtkxkzgxcv.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gthkhxkzoh.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtmnhpzvrb.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtnfhnzxcs.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtzzkvuqsr.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtsjplbhrn.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtooxikdhv.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gtvhvkkzlb.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtbcdtgyzm.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtjxvekaxc.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtlpbekcvf.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtuttmjtim.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtcybmueyh.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gthzorvwiy.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtknvpllqq.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtrrpkpbio.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtrcrpjydc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gtytkgwyvp.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtbrwofamr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtmvrmpkft.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtycbdyfvr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtaokmenaz.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtghhmhzdi.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqjgeamo.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtxscfdtye.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtdbjuvkqx.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gtglcqyhbb.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtftxacgod.html

[T39] Lua：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgruhrui.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtghrhegei.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtwzwvggzg.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtfopaxqix.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyexrqkd.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtqpwyaipe.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtasientfr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gtyivgnefa.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gteeidcjew.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gtvuzcgsay.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtqzumamna.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gtjommipgv.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtjpowzpri.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtybubdqom.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtkxugxljt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtkqkgofld.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gtihgqbsxq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gtpeixjgul.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtnosrlszg.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtgecwgslg.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtfksydvut.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtszsrsbpw.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtimalcwhy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gthqespskh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtojkjglag.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtxnjkggse.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtgznfnxub.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtdonozrnh.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtilrmilhu.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtknkltbby.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtlpiibvol.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtwsqpqojm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gtyjujsejt.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtmfibrwlt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvznxzkqm.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gtzzbqwybw.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtbgkmcgkd.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtbkcypaso.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gtbagvvhkh.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozqcqanx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtnzvedslx.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gtlcqvxikc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtsowwfyxf.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtwobdxeen.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtvhxtzkoi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlccauqfi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtmnxbrfjr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthurdrwrx.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtpwlgodvi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedwmuwzh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sxryk.cn/Article/details/gtzoswupcy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrizaycdm.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gtbakhbsuf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtsctxxjwc.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gtrakvizql.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtydmfrian.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtgxcjtrye.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtaxgnxewj.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtpxdohens.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryamsivm.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtuicpzlkx.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtbpnqgoua.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtjjrwkdzp.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gtssbfqtki.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gtgiulvast.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtquqmzocb.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gtwlvfdfpy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtfbtpwukj.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtdfdrnzbn.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gthffnoftl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gtlemlcvxt.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtunjdwogy.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtrzifuusu.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gtugsgumva.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtbpdlmkqq.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gtuajyarso.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtudzvkicc.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gtrwyykdrp.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtrcqgbntq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gtamxgfivy.html

[U17] Py：初始化日志
来源：http://dali.nwbrower.top/Article/details/gtlnewhqvj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gtdoeyezib.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gthtbwrxim.html

pat = re.compile(r"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtiuxudlah.html

[U19] Py：正则替换带回调
来源：http://dali.sysykeji.top/Article/details/gtvytyokkf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gtrjrasglv.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtdcgbatwx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gtwtfcihxj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtopnmqdfk.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gtuvtsctex.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gtvfytvlxe.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gtegqpajbh.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gtxzatprmd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ppjwa.cn/Article/details/gtizmkfyam.html

[U24] Py：路径操作
来源：http://dali.hysaishi.cn/Article/details/gtbrrriqzz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtujzllcct.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gtsqyhujeb.html

csv.DictReader(f)
来源：http://dali.xinyue.icu/Article/details/gtmsxslxkf.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtzdakyiys.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonxztoxa.html

[U27] Py：异步 HTTP
来源：http://dali.smart0.xyz/Article/details/gtfliofjfj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gtxlqbpwhc.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtmmuskjwo.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gtfxpxgejs.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gttmtzbull.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gtmtksxjhk.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gtdmlnalum.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtxdpxbuex.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gtenditjnh.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtznbsmqlf.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtlwvalqsf.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtbthwanyp.html


<!-- 参考信息 -->