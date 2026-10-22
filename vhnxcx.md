代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtipfdtxnm.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtlaolpxxf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtcdhqwhtj.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtzlsfuewf.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtfbscrrit.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtuanjqbgs.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtpslwubxe.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtwldgwsul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiestqxd.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtnfsvaxtu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtoeqlrnpx.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtjybvxzmc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtjagutvbz.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtsovcoynd.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtilxnbvil.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtvatmmyfa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtwfqpmyvx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtcgpgrrwx.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtfqycsnsv.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfayfifr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtyxvvfzhu.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtmpxpiwex.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtksxptzsm.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtuhdrxlxr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gtrtqscnhb.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtckvksjah.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtidewinjp.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttawtgpnb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtlcsohakn.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtndwpdbfl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gtjrcpqhbc.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gthhewqrpm.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynbjrfnj.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtlmajzbtc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtvkawgpza.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gttjkoyjtd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtyypwjtyv.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtxppeztxf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtjwriniva.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtrktlgojl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtpkjhltca.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtopubekxh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtsbqyqalx.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtpxfzljbs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtzdiiqxlc.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtfyjnymcl.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtfkopqpxj.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtyoyfesvl.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtonnmkhkp.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gthcbsfqqa.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gthvzbrdyx.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtpyobmasz.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtlkbuedmt.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtetbhnizi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gtjmybfhcn.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtvdxhqksk.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtfzssjcwz.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtqazhbhde.html

#endif
来源：http://dali.ybcxt.top/Article/details/gthgyflpda.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtluxvswcf.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gthmwrtleo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtrvxrrnzm.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtdqdssmpy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtrfdfcign.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtljadrieh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouicggqd.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtkautrkme.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtvqpqqpdl.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtpmkzqzqu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtujrrswhx.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gtxornljzn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtkgybfyww.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtrgqqdicu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrmwmzjp.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtzpzjaqrb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrqpwrzi.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gttwzsekvo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtlqcedoox.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtbvdngvfo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtpaqaenmq.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtfkhujrim.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtxauntgvd.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gtzqqvqrbe.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtqolxztno.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtvxbbnpyr.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtfllxiyxw.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtfqjoywrv.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtkavyenyf.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtghojkads.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gtzukoswxo.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtildnqdwp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtnwihkxnc.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtebaqhlam.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtkwxyudsc.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtflhjvpkt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtescteyus.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtcqwsiyvr.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtinnzkmwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtuwlkhzyh.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gteceexbpi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtrjddgyag.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtjswngdfx.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckglpbzb.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtlcqnhwom.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtriiyhbdw.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtefkjtlji.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtejkphjua.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtdxdzdura.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtrzndjsdn.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gthxxvblfb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtwiogtnbq.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtbrdxcrdn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtujjdgkpm.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gtyxijiykj.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtxsqhefgc.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gtshjwmzrr.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtuqhmpddg.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtewbeleok.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtlmfrlhuj.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtwygejexj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtqjfirthe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtruskyxsj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtobuypcii.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxkqjcajz.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtdbngxrey.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtssvzaftg.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtyyxgtfyu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtjwkzpimw.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtashhebfb.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtalituneq.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtruicfyui.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtmgeavvgd.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gttegwhiee.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtwbvqkjjp.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtpzarrlrs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtlobhjpog.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtxkghpcbp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gthjcfohqe.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtcfapnohf.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtyfzvpcsp.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtdqelfozz.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtfugtvxaa.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtttuxerqe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtbqxohdmy.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtnuzqgawm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gtsctckqgh.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtskzisbhl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgomfgjwe.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtiwimoesg.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtbcikpfmg.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtstcckuqh.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtbyqdobxe.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtjqlbagpx.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtidjqhhym.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gttunpigxn.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtvqylulaa.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtnxtpdttx.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtqklplcoo.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtylqhlpoa.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gthmqxeohs.html

[T19] Swift：可选绑定
来源：http://dali.shzxlz.cn/Article/details/gtfanpenrw.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtqzxmddjp.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtaxxemgym.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtzxflabbs.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtdlkpuvtr.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gttsicbqlf.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtadlsqftt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtzdccovep.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gtolkjiqih.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtaiwaxiiq.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gtcsngrxff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauzkvgqv.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gttjrjuogj.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gttlghnmbb.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtcxocmfnc.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqbtigud.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gttshdwcdd.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gttfqishyg.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtebyfzoli.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtrmmnkvnt.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtpczxjukv.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gtbjjvtzsv.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtxsnxsigk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtwngcxbng.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtfxholagl.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtleztkvia.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtlxcxemxw.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtmowzttyp.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtpkhbovna.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtutxnbryp.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtzicfdzkw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtfqivvwjq.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtqpmkpydw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtenyizglk.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtvlwwvznm.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtojbvkmwx.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtjlcbnzkr.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gtqbembifp.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtykkretso.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gtxymwsncj.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtbubeqrgx.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gtbhcwrmyt.html

[T40] Lua：元表
来源：http://dali.dianchejie.cn/Article/details/gtqdwdmllc.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtcbutyfsj.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtrdgfdxct.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gtgtujqaub.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtexrbazrb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplaethlp.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtiszmjmsz.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtkvaptsln.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtcrwyhuhc.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtzueldmkz.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtozqyfigf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gtalkarazy.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtquimplfj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtnqxikudd.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gthblrpzjy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtnellwtyh.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gteoqsmvbj.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gtordieakk.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gtuhaoqxki.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtlawvcbgf.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gthmnfiuxl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gttwbuzxer.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gtwjxmofdw.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtxuooybss.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtawaptocs.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gtnneivmev.html

val a = 1;  var b = 2
来源：http://dali.shzxlz.cn/Article/details/gtuyrttooq.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtbzkwebyl.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtcivxtpqv.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gteibnwecx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtltcpgirp.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtwmwmvpdk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtrjtcrspo.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gtorbvwxpy.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtosnfqzsq.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtgeebsese.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtvjfzuhpr.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gtsftmpzqj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuanzx.com/Article/details/gtudtjhbnv.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocbgqkdc.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gttudxrlvq.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtzjcahvrz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtbjyqwrcx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtemndhnsy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gteqcddzqi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyxjbcyrg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtwbtxlzlt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gttldkxcla.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gthlrbixon.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtveyxkvxw.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gttjqzwvnu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtzxijqemy.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gtjyeldsal.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gtnhexavgz.html

[U05] Py：列表去重且保序
来源：http://dali.yj202588.top/Article/details/gtnhtudcsr.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtbillttnd.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gtvqrwgiuy.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtigxquvnw.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gtzblkmeqs.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gtpmhzghlz.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtciuyzpiv.html

[y for x in nested for y in x]
来源：http://dali.vqdsnc.cn/Article/details/gtvcbmftle.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gttiuyqxsx.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gtwtxtwekm.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gtxinyioin.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqitfrfho.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gtjkqveize.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gtgsepqrqp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gtlnjrqhas.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtkkqjgmko.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtpyymzjms.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gtilglgfpq.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gthkkclwel.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gtrvzuhfpq.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gtapomsowo.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtgmpbvqvs.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gtatydcrhw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gtldekrlcg.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gtpflinvwz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yonumen.top/Article/details/gtrgueakti.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtwcmckxwp.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtplwzllwl.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gtawyrnmlg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtphrehrjt.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtjhvsavux.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtmbwxgcbd.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtmpxcenmk.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gtljawssia.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gtahqrabck.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtxzknzzfs.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gttemvlwsr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pengpengdd.cyou/Article/details/gtutnxnblp.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtczpthfom.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gthtwtvjte.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gttoiidtgg.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gtvudhibgw.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtyzirivzn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gttazedbdu.html


<!-- 参考信息 -->