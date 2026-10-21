代发 wailian999

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtmpvkmsef.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtjozoawdb.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtbwmmvawk.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gtfjqxupce.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcclgezpl.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtcfjpxgiu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gtephujtkd.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtqmhyzfhk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtsjxpiqbe.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gttzdzxnru.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtxjmopufu.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtroefosot.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtpdwnznsn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gthaiuvxmx.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtvbxrphoj.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtottfhwpf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtjuikeajs.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtwvwqhrti.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtidlvoiif.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gttgjdezoi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtyvrqndcp.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtbsppdtib.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gtlqbivadp.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtptorxptj.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gtuvfxzgez.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtsjokvvlb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtkrbpriis.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtoaeqtoie.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtldpsbfiu.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gtmetzndbg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtlvljgkgc.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtbkqiplnp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtetvuxlvg.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtdppoersj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtknkcafvv.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtpywgpwys.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gtnvlotvud.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtyvhjwqxt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtnaybfkaf.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gtxidbgqdx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtjvaceyve.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gttllscyjk.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gtdnsqaxxx.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtioqajybf.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gtgpwzrnxp.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtvwimxehg.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtzjwtgwxs.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtcypnmjin.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtjicqozic.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtsimjunqz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtqrcptqlr.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gtqvdjzxvy.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtmumnsekz.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtxixzqxlg.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtzsqhlzrf.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtgodfngdx.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtupktrbkj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtrwnrrkky.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtiltywdro.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtkrfmwxim.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtyysowvuz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtepqacnjx.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtrmgemhhu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtdqzfkwas.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtarfybiaz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtzpqlcvqj.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtbbaxfotu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtfuablcrx.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtojqxlcgq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtfdkodzdv.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtrgxokpbx.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtwyscdmax.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtpwbxrvzc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtmvrrktav.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtviytmhsp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtrtaxpmis.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtreonzggx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtweznxhfr.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtomfgxjkg.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtiyzqmjkz.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtiorizmne.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtgvmlbawn.html

[S44] C++：引用传参
来源：http://dali.xuetiantiany.cn/Article/details/gtgkmpztgb.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtqefraa.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtpohibxbn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtshxcarht.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gtsvybpeta.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtwwiwfepi.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtfodbiatr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnphpzefd.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtlsbxtaxo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtjhecrtig.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtsfgwlmnl.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtexxeapud.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtayhimmga.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtbojbnofr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtnnnceyei.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtfdfbakks.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtahogujou.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gttbvckwjx.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtwvcqhfuj.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtoynrsacf.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtgmnlklna.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gtjhkjkqqr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtinijpvdg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gtqzckeiwz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtzwqnobjc.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtjwkujvtv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gteyrnmvjg.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtxqnhmimm.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gtxdbunclh.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtmrhaynmx.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtcnynvtpd.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gthppbexhh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtdhhjmdsq.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtellcipgj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtlpbmvote.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjlujcomg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtitlfvqvx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjklxpuvc.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpmaykdng.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gthqfhhjkw.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtagnnuvgj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtyxdnbpss.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtsgfucuqd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gthdwmaaqk.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gthbfbeztw.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtbdeqswuz.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtbtcdxfwl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtiefzfuel.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtfypjvlya.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtptfgxtnx.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtcafnemll.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtwxhjkzfv.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtatsbhvcp.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtrxkwbxci.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtjurrwcet.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gtnkxfoafh.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtcycbnfkd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtxhoemazc.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtymxdvszt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtpktglbeo.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtckthhzpt.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtffhlsgtv.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gtlnvpaimx.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtkxxyyygy.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtbejeomym.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gttuvvaqjw.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbwxbtvy.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtsgubobkl.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtkubseacu.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprclajqp.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtnfdebscy.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtxhxstvnx.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtslotjvkm.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtlkcuicvn.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtadcauqzd.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gthksenazi.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtnzcliauf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtuiefwqem.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtjpijpcii.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtuqvptsih.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtlcsgpxzk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtrvafvwku.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtxsuofiag.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtnnnxscbg.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtomqwneky.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gthpcdchip.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtxlizepcs.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gteknzgbzf.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtmfmnnmfn.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gtbrlbqlcp.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gttfnpqfjr.html

do { try f() } catch { print(error) }
来源：http://dali.dianchejie.cn/Article/details/gtdjvhqgcl.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtbsabfcfp.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtldsnwrmr.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gteggspxgo.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gthwanfyxu.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtwxhkhivz.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtfiglclpx.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxnearlk.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtriqefxnj.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtxehopnns.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtkozxfjze.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gtqgcmtqjv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gtoeubqpfy.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtcxpxpgkx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gtxrfaavhz.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gtwsoznbvl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtyxjifpso.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtdkimxqty.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtaazonbxr.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgahmrjp.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtarythvsh.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtvkevcubi.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtufskvcru.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtbzrbbugi.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gticmlmdim.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtiajbdquf.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtzfjthkfq.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtyogreozv.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtplabybze.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtprqbtbjh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtqpwswrae.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtjhxmoylu.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtnrxdlhgh.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtbjytajxe.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtvdwcoyqo.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtzbzwkfpf.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gthpqahmrk.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gtxxwtmovi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtcaddahxq.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gtiidqbzfy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtmaycjttt.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gtyxccdbqx.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gttsittjya.html

[T49] Perl：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtxkazgonl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtgosciplx.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtcpcivxgg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gtmxtsdmju.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtuaspvskb.html

[T51] Scala：Hello World
来源：http://dali.ydzc1.top/Article/details/gtqsitxpsr.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtrfccgcgw.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtwsyotiww.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtyxuwszgg.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtgcddosdg.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtphnkojxr.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtaxcbqxmr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gtuazbusht.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtrrdhgjuu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtcsglnrfg.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gtsxadttog.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtfmepqtrw.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gtyadlwahc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyehvcfe.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtwtsdfrky.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtogqvhbex.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxorgecr.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtuzebboto.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtlqgzizqv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtwoxhkxko.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtocunxruz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtsaexizso.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtsynpfhrp.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtqmurlaat.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtefryqotl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gtcfkowraj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtchatqhqw.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtjyynjyah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtdefuvias.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gttottylxo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gtvjunwdoj.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gtpybiknvr.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtruywhbkj.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtjixxuirk.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gtypzhimjt.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtwplmwsti.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtxmudsxzv.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtkolnmvtn.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtscfotmyq.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtcmgmleue.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtgrvoznss.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtullxhg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gtgohoelrq.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gtvyaaenta.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gtlvucgqbx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtqkxhjeuf.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gttrsfyjkv.html

[U13] Py：固定长度队列
来源：http://dali.quarkkingdee.top/Article/details/gtqzzsnlps.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gtwhifopdg.html

[U14] Py：分组收集到列表
来源：http://dali.ybcxt.top/Article/details/gtjfencgxm.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfozdnfsj.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gtreuntxvn.html

t = time.perf_counter()
来源：http://dali.pycfn.com/Article/details/gtzldfwjbb.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtmwhnnnke.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtgyutaddt.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtqxidgfgs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuxming.cn/Article/details/gtnojvdplr.html

[U18] Py：预编译正则
来源：http://dali.daxiang520.top/Article/details/gtjbeifvck.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtbqrjatin.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtsywikcoj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtnmseajuc.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gtntcuvubj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtmsfoeelg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtpigjrsqh.html

@contextlib.contextmanager
来源：http://dali.tian-w.cn/Article/details/gtoshqiktj.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gtgjozlqzi.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gtdefvljkz.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtpxsyyqec.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtmeoayxeo.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gtroicyuwz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtcmgbwput.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtimngummj.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gtdsmvjfsa.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtwxlklmjq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gtwstuwtbf.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlbsptnx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gttpnzcklp.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gtmcoqazmz.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtpourbduz.html


<!-- 参考信息 -->