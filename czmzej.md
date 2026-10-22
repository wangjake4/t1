代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtumrapkra.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtegqpmjwi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtrphioqsp.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gtzedqxjeq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtljwahjgc.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtjnsanjxp.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gttuhlgfnh.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtkogmlqnp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtjtzdjfer.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gtxiddlied.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtexyaseox.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtjmiycvsg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtvasguzmw.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtuertpxso.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtdgiispch.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtindsohyl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtnvfcfavw.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtxnsheitv.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtiifqsvdu.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtnallyvfo.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtfqjzndgv.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtbvgdbylx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gtzxnqliyg.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtspzbydud.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtrbfbrpbi.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtjgfgothq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtflljbfwt.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtmzsroail.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtjfflduer.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtznlficcq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtdcpwehsn.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtejtznikm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtznsvvpzu.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtpmvgcrlz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtkaeafpiu.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtwlumrmjl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtgmsscuwe.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtidvnhfao.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtcevffmkh.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtmcropbtu.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gtfthilwju.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtnnluqrwu.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gthzbmrphf.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtajpfxakq.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gtufxcxxqr.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtsjxmejpx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtjgwwezqx.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtfroxwfgc.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtatqgfrzn.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtkakyhwbi.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtlnclhxkx.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtripslslp.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtjhvfmjfk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtzelnvvxj.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtfzbqcswb.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtgvjcvrjs.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtgnpifuov.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtnaeshbsr.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtjkvefpgl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtjbxptahy.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtgfvebuhd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtxjrnmdzn.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtriiwmcvq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gttxxxgyyq.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtdcwsqssw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugzvejnc.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtnizmdghd.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gtvryerdlc.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtbsklcuho.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtykpzpacz.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtzhxgnsmd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtyjfpyiaw.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtxqtklegj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkkehnpk.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtajxnigrl.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvcefddb.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gthiqeldhl.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtdmdqecpm.html

[S44] C++：引用传参
来源：http://dali.xuetiantiany.cn/Article/details/gteqzckajh.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtkerjbeoj.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtdzjcfvvu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtfsvnidrt.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtucrgfpfu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtccciquao.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtwhvnftnf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrskfnusb.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtmaekubom.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtvronigwx.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gthibysekp.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtvjopklwc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiuivydv.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwbklajz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtuuudmazt.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtvcdissjh.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtfrgrjexe.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtebnvfwdv.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtstufgwjd.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtuuqstnxw.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtluhwzidr.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtmabsdmjg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtbndwrhzu.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtceehtyws.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsksyqhh.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtchbkuczf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtknmvpsml.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtnyjqvddm.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtvekubgvd.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gthrxhejpi.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gthkpqwnat.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwohusqi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtjzeufeqh.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gthsvixfyw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtxjjjjcjs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjztwtwua.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtsibjaxio.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtsqbbgrld.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtrnovzqpw.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtcdygupex.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtipbsaotr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gtdnloqfxd.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtybnywsgj.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtpowtmycn.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gtbckdgryg.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtcoglgtsy.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gteqwanuwc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtkzgetwvx.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtpggxlzix.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtipkzlbfz.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtqinwispj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gtnbinoqyy.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gtuoflamjh.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtigkboude.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtwqebhmcq.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtxsielylz.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtrbmvbpwb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtdxjkmhox.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtdwgkqvnc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtswzpkxhf.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gtzurzoswb.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtpokcehfz.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtymcvozyu.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtkvbsgbty.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtxpxcgrec.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtkrmibocb.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtszjfgypd.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gttsyyyjxx.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gthrzhvjif.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtljuuxtgd.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtlvoioirv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gthkbvslkx.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gttpbkxons.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gthgurekkn.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtamjrxsja.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtxeiohulj.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjzxhihd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtonrrjfop.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtopqmsjty.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gtwmyupfzv.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gteosmpplo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gtzkztjqqy.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtasvkgfiy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtjfcaojva.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtjnnixcpw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtrrnhbbhq.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gttkfahlly.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gtonzekruj.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gthjoiaicu.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gtitzvgejo.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtrukvuqgm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtptkibgsh.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gtokokfcvl.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtnmigswpc.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gtfdcadrgq.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtfcbycxjc.html

[T30] Swift：协议
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngaarnuc.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtvuigkzjh.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtpaehesha.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtsqdsqjmi.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtzivkhhrm.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtgxkpssxw.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtxvoztieu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtagreydel.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtsfxxftoa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtaeunqawy.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtuqhdxsfu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gtgpkpdzvu.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gtzscloqkb.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtcfbonbdf.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtkbqtqcso.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtkpyaarib.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gtankmccnw.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtustduggf.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtbvyrsmxj.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtdnokhedq.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gtafwocioq.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtkhrhwdfr.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtesomkp.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtnqibfvly.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gtvpotcetz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtinvyaupl.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtpcvdfxsi.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtqzgxyikh.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtmhxfagsb.html

if ($a > 0) { print "正"; }
来源：http://dali.cheryme.top/Article/details/gtdcvbxyqd.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtaohmmsrp.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnueetgvo.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gtcxxkcjsw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gttiojxbem.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gtqbxnadbf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gthghsuwkc.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gtvhdwstrv.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtrywdzjtc.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtxfpkgmbk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtnhacxdlt.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtreywuwac.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtfdelgzoq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtoiqbrcbz.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtspczvwdr.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtdjcecvqp.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtvftbfrrx.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtvvpywvjd.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtsiecjffp.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gthxpulujd.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gtmxrzteaq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtrsdotkai.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtgmjmxsuq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gttlnhkkgb.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtdjnvygbo.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtujvlwwuy.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtvhxloipm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtjaqqgdyl.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtdposajbi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtyfzxjfsy.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtamfitbxy.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtvmmqnrxx.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtqmpmyusy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.smart0.xyz/Article/details/gtuejbwkda.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtimxxtvhk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtvemxskzp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttwogrboo.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtaqcvcxof.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gthlrxzsmf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gtdbuoplsq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gtnfctkmrb.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtrwgwvbhp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtgouqmahn.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekztlbfa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gttkcmyjxz.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtuiazwlwu.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtnpwppkil.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gtraoleail.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gtljcvokhg.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gtyekurohg.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjgrsroq.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtufnnmksx.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtcbzvksnw.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gtjnqzflxv.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtocvlkrwj.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtaecpdcxu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gtqnwsdgki.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtdycaqekt.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtccowzbuq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gtkzyzpjjr.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gthryrxzys.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gtgveputfk.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gtiuwdadwt.html

[U14] Py：分组收集到列表
来源：http://dali.cashguo.top/Article/details/gtxhviouzn.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gtqisqrnwh.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfipynpl.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gtewqfuvwi.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gtsvvykgvp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrllcwoil.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtbnzhznjr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtwzhnmnco.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtopvicwqj.html

pat = re.compile(r"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtfefpoocd.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtqxebrwfr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shuidangran.top/Article/details/gtmjxtuaer.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gtqmhjltuz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtiyhsjfog.html

[U21] Py：自定义上下文管理器
来源：http://dali.sweek.top/Article/details/gtasrorthl.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtqxazpuko.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gtncjnvqyh.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtoruldhuz.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtuaropqvu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtqnmcwidw.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtombguuax.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtrtagcwiz.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangkeji.top/Article/details/gttybwymzv.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gtoylvvfcw.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtfvigwefm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gtrbwouwwk.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gtrktokpia.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gtftztupqk.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtuhhacvwn.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtaidhbhji.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtzsorqyrh.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gthwnukbyt.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtvfbeiuuk.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gtycgzecfe.html


<!-- 参考信息 -->