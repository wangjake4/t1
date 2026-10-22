代发 wailian999

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gt2ewdobzsx.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gt2emeijjlm.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gt2eejyddyf.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gt2iraqpldf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gt2dadkiyyt.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gt2pomxvfvx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.andypj.xyz/Article/details/gt2vkjaaxdt.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gt2nlbntdxh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gt2dsikkjvk.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gt2nundmtae.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2ircmpfrr.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2fbnnddsr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gprplhgq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2jzptubzf.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2skmlmuvz.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2wvelgarl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2dkrstioy.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gt2wolxihgu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkiuipbf.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2cxvilijw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2eoidwfta.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2bpysuazw.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vadfvcyw.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gt2rhhpygrt.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gt2eeegrgwz.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2ovipaegc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gt2frvuqhhs.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2mungqkff.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gt2acvuyhlo.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gt2ylqtlocs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2nazmehqn.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gt2jkmtgaqp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2spqvymku.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2dgeccrpj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gt2epvsgdxx.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2zttaqmyt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2zvspizvo.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gt2otbjliee.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2plrryfrr.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gt2ivlcolxk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gt2hfevzdsz.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gt2jftupdwo.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gt2ihmguqzb.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gt2rssdfjwq.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gt2pnvdqfhe.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2fcbvuidt.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddcmahhv.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gt2dcpmoszx.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gt2zlwfzkbh.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gt2wxciwsvx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eduhgodp.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gt2gbxeulla.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2nacydure.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2fnzpyect.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2mpzbmbfs.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2uptgazqh.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gt2ewjesxsc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gt2grpxkahw.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gt2sfqhunwk.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2dtrtkywo.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2fmtncitr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2olddahcq.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gt2wgftywrd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gt2exvepxel.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gt2xomwlbdn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2loxkfkfj.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gt2zujmagmw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2jfizxoet.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gt2cmjqnmwc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gt2xwfdcwvk.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2nluxludn.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gt2gvmxyvqf.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrcvfovr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gt2lxnzdxbv.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2xspfqkwn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gt2tuuzyapc.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2mohgzimy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gt2osgijdjc.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gt2bcpyrztb.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqqqeqiz.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gt2tnkefbcu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2nddgypnv.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2rnkvlcmh.html

void inc(int &x) { ++x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zagrombx.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gt2cmvdufnv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gt2jmenrpwk.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duykjski.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2zmxhqmuu.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gt2rdxlbnzl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bezebpmu.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2uyxvzjvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2khqvjcem.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gt2pcoknmjg.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gt2jdqjeocc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2hqywxcgc.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gt2ematyyxj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxvnzmlb.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2zqrztmtu.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2ijcjvjvo.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2dwmzithv.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2ibkzenwc.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gt2tljrvvud.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gt2wguoxwcx.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gt2mgkrzqzl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gt2optlerwu.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gt2tbxcjmtn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhvevyxh.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gt2kwjbuyxu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gt2kexdlyzp.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gt2mvhrxaig.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txmsnsag.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gt2nkamtkin.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2teefynkj.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gt2ydkscndo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gt2wwzgasju.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gt2secodtwr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2mdoygkps.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hkwmjlcg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gt2zcxlcwhg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tqcefroc.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2cvarckoo.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2weacvpua.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2umcbubpw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gt2kruloyqk.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gt2zjeeuiza.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gt2yqnuwazx.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2orftlpfi.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2irvjoxhe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2qbqgrshq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jewpdrlq.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2xuvnoakh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2skyxrntn.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2bouebern.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gt2pzxghbwl.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2eoicnkyy.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gt2edtldyqd.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2ngoafzim.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gt2vehfdyxp.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gt2oyrbxphp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gt2ggukqfto.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gt2mafpwzga.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2elqjdwpv.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gt2qiljfpzh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2hqfgbcgf.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gt2fdwyfpcs.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gt2jxrvdwfa.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gt2wracskkv.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2obtgxhvj.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlddpluf.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kymgrmok.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2zgncsnfo.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2lfqpniex.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gt2okbwvcop.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnmzqlf.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2pqtjpdfi.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gt2mhxavtcr.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gt2rjvefesc.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gt2zqwynsvv.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gt2alvxjsnv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gt2snuytwwd.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpftbawf.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gt2bzxjfxfr.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gt2mbswvnav.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2ndzyqrcb.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2qpzocmfm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2krgqmudj.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gt2imselvux.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2esltqooe.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gt2skkgxcrr.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gt2qbtaeejg.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjkssmzw.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gt2cuylztkw.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gt2vtyhbonz.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2ozdhgorf.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sczzdbii.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gt2drhqaapu.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2xktezjzf.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqmdpuaq.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gt2mozegmny.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gt2cdjgiayk.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2xmxmmvot.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2uyqtjtmm.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdrgbxdr.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gt2wvygknkw.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gt2mhoozhfz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2gruyxrkz.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gt2hbuahjkc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gt2cwdrcjnt.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gt2rvfjdest.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grsfclds.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqqprdgt.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gt2nbjbtrru.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2htzsxofc.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gt2kjzeeosj.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gt2gmopzqir.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gt2nzskmsod.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gt2amaqizts.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gt2risshard.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gt2zsxilpch.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gt2rddfjamc.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxogzhsz.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gt2acyqrbdc.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gt2oxyztmro.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yziappyc.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2mddxdbgy.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gt2uahkmwil.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gt2txudzanb.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gt2mjfxsckr.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gt2vvfgxoeg.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gt2ubmclkzp.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gt2asfbqqro.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gt2dlyvjwmp.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gt2zzjnkyoi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2cdjalvks.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gt2kdflcvee.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gt2seppqrqe.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gt2yailcgbp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2fjtgnlvd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmrawzc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gt2sconhmis.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gt2khhvabgl.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2xpqhccmc.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2qfpjptxv.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gt2kwyjriyw.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2nqvybiuz.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2cpsskoud.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2rpvxqzig.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2zeuitvxj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2owfwldor.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2ydhzffer.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gt2nobhvcug.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gt2kfzsoeus.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2fnukixrz.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2xuaeqcnx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpqsihhx.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gt2wbpmzdzi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gt2zmpkwbdh.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gt2quandbxm.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2slkwjyad.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gt2xhpfrzts.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gt2udhjpavp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnitttmf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2uolfjkjg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2upkyszke.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gt2bigxwraw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gzhubu.top/Article/details/gt2mghkympt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gt2pylsigjw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2qrtsukgr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gt2bjpyzktv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kskdzdlp.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gt2gwasaxgm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gt2ueztpoei.html

[U05] Py：列表去重且保序
来源：http://dali.shuidangran.top/Article/details/gt2zxpcwryr.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2eanzoajx.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pseqoopn.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gt2jjlwwfuw.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gt2bqnpkksx.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gt2tloahlhl.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gt2dfdkpyji.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gt2dcdbzojd.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gt2dhvxbfek.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpockbvd.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gt2efeyjkzc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gt2jfyhpcny.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gt2pldohzoh.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gt2mlfblfrl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhengqikj.top/Article/details/gt2zjetrirj.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gt2jpfobbaq.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gt2ehjpykbn.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gt2yirtrdwy.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gt2vdjrtras.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gt2rasjdepi.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gt2wzqyxgue.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gt2srzasxkf.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gt2pjguftmy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gt2ficmdtch.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gt2ubscaeoh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gt2vseckdlo.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gt2tjyyxdba.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gt2nlkobjyc.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gt2qjnsoydr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gt2acpuagdb.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gt2yoydegla.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgowczoi.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gt2eerelzar.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gt2jmokkbmi.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gt2zgcairdk.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gt2nljoydtq.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gt2hhmzuznd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gt2sxjcbhhr.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfrexhbe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmoikeoc.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gt2vysxogdj.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gt2kxwulklk.html

[U26] Py：并发下载
来源：http://dali.chenzaomai.com/Article/details/gt2vgcddndx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oivqoltc.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gt2okoyeftb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj202588.top/Article/details/gt2juccvqsw.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gt2lytnwmul.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gt2ndvbmomi.html


<!-- 参考信息 -->