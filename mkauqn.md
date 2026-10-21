代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtlrvwuhyt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtfdxfvlzg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlchyghsy.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtlnzfzfmt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtltpcrmsj.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtolnyfnxo.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtopuzscxg.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtpccuwlrr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gthdnmeywk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtdzscnqni.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtuvyzdfin.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtopupkczp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gthauxuatw.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtlwqdqcbe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtbljkjdpf.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtnsvperrh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtfycqkaem.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthflsmoaz.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gttpubdlgd.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtxdspezou.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtbucmvxvn.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtprgnqayo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvosanyy.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtpmrqqbdz.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtoldcdiye.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtzpxfzlly.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtuddenfgh.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gtoslfutrd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtmxyppufd.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtaohzjtst.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtexgpdjly.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtyzclfacp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyfituar.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gtfyhvszkb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtuvgldzdk.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtlczhgwyh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtvcfwstaa.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gthrcdaizh.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtkflobtst.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtqsbfvfxp.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtqrmsdtxc.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtunkgksik.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtadfimepb.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtoewjqjxs.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtrgzoodtp.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtnhakqyac.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkxkcbat.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtvbxhrcmh.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzngqqpa.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gtdsmusgsk.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gtjjygtaal.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtumpmajjy.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gtyljblrtc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gtysybirds.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtlwaotczt.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtlybymsjl.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtuvjwxnjl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtcxglwzxi.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtbuwsjvwe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtftmtkcye.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gtnqezdacq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtxviqcwpo.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtsnbzdlws.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtrgmwjiyr.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gtzpdksmrz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtnuhuzpil.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtxkoqinui.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gteywbzvkf.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtuotglvbx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtsupcjzei.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gttuuojacp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtukbqfnwb.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyxkzwtj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtbjytstus.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjvkimwkf.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtfetjumxy.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gtovtkaqod.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtuhpzgatl.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtugneuwcs.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjxzubuug.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtjtxwarrn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyvauvwl.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtgzyyrcdg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gtzsnvpkvy.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtkidtkukx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtrrktrbwh.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtyunrrkbo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtgrvdolkv.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtojenhgsv.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtvujczqsn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdlizjvc.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtwvlbzmxn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtmndbaegw.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gthhmaqtut.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtkonyqsbq.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gtnaimpwva.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtzzqpehxk.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gtfpupswxs.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtkfibaclq.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbgxpzkl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtelxqndsx.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtxbpfaaik.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtzkxhdjnv.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtcbpkvwud.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtssdsfoaa.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtqfdwgfjv.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtqqvapyig.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtksqdzeyr.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtjpgernnb.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtgetjzskg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtaadotdwz.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gtiyhxcifk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtygjpvcoi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfwjsjacy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtnwsifzjr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjrheddax.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtgzsxkxyq.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtexgetlmo.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gthhoffpmn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtcnbgwrwt.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtexitxrxj.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtynresxmo.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtgeoexrkh.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtnaafnfmm.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtkwjfcbgi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtnsbkznli.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtgapgxlcz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtgdzextml.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtwmitathn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtlyytxszp.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gtfzrzikzm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtixnijhbn.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtugjspmkr.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtkbugmfvv.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtigpdkoqx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gtzmzkmlar.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gttaxdwbol.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtzgebfyhi.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtnlbcqmwz.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtzlbolpna.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtvteootmt.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtxdjkcyxa.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtmjaibjbq.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtuzgthsmd.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqinpmynz.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtjjobegjk.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtszatvrzi.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtfbarmukm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtlngkdrwa.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gteldpnzim.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtjedywhez.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gtwzwumcsf.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjggnmnc.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gtosiilkka.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gtpixcpsrz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtficuxity.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gtnhvawjfv.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcfecnah.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gtbiivfouv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudcvaxhi.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gtdjpnadot.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtenonoeso.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtjskeyqaa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtefmxhkzj.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtzecvuyqt.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtwvpnwxes.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtgmcovceq.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtmseunlsu.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtfarafcoc.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtxhippbiu.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtogfceuuy.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtyxbkqoio.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtmwrebnpv.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtsfiozmht.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtmhkkfqyb.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gthhnokqtz.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtrzfyjxpz.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtwimoamlc.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtedlwqoop.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtlksadrmu.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtiikqicmq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtfkswskdf.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtilzjnvzv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtyewkpips.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gtjikwmwue.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtyhcdglmr.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtotoinpkb.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtmiltfths.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtvqbzyowh.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtsglynikd.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtbzwxnocu.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtefgkuuvw.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtkkkvjwdq.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtroiwaowm.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gthbaopdxm.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gtbqnalssi.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvuwfirp.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtrrydgsiu.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtitwvrsfx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtqmpyibzv.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtdadjctun.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtnwpxkreq.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtmghzzpgp.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtzqwoafhz.html

[T45] Perl：数组遍历
来源：http://dali.redwolf501.top/Article/details/gtkrroscbk.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvvmliqw.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gtzwjgywqj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrtufoiiy.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtlbslnblb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtiayccqbq.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtimyxrnrz.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gthwcyyavy.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtanvzhoco.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtupywrxud.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtepxsawtz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtkbjywmwn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtsehigmvp.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtyytzskdf.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtclrbdmdh.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtlzkrjppp.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtvpxgnzhs.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gtonuwmnza.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtkjirtuxn.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtxnlsumic.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtufgrhnsr.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtlecmkinl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtdhvbynfw.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtzjzwltva.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtghzepist.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtwvtnajmn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtzbwnosks.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtmradevzr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gtlvyjdoad.html

[T59] Scala：循环
来源：http://dali.yj202588.top/Article/details/gtmkbuthik.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtmlmrlbqk.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuikprvls.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtarqluvaf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnjbchuzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gtjhohzqrl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqavhpqds.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gtuyqikacd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gtxpibeimt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtzleddntt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gtvgveifzu.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtifgctvxi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gtgrlzsquk.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtejrprgjr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gttciwmfbz.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtdhyrufbb.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtkkdvpffj.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gtycrybcpo.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtenvbjxjs.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtpfbndkys.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtnnnksvca.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gtqthsekwi.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gtmtbostag.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtgysieolv.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gtqcpcgizk.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gtkcmixkcn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtajbfftvx.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gthynielkv.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gtrmjscwfi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtdsenwpmk.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtfgtaurck.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gtzhjyifou.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtgaacmovl.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gttsjaasqx.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gtcwridulj.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtffolblbz.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtxbxyvjbi.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gtrglageez.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gtivhilvtz.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtamihnscy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzrsvdrt.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gtfdpmvusm.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtycqakxjm.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gtjleqwzhm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhongyouzk.top/Article/details/gtbqkguqfb.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtoherglof.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gthwdlsuei.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtiurqbdch.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gtnqusuxer.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gttqcbsvns.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gtpwtedphy.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gtbejldfzc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtaemyewgr.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtirdzcezc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtwapakrhe.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvesgcxrr.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gthbmpksab.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gtocdwjghu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj202588.top/Article/details/gtcrqjmwep.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gtaizvabpm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gtwheuctrj.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gtsiwwqvvb.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtgoqswkcu.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gtgwvkzzht.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gtohigwjnb.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gteozfldme.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gtasmpwoxv.html


<!-- 参考信息 -->