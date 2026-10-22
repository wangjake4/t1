代发 wailian999

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtygelfpal.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtfllibbkg.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcqsjquv.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtjeiswswv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtuiopvdoh.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtluweagku.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtqeyvhvlj.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtngyxyjhw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtndwsxihb.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtarvosukk.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjfbuywn.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtqmnoeqpw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtsdhznfxj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gtndbvqaih.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtpvmdclag.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtmbrnvbze.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gthdxdnikh.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtfgcywdyc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtcdlnjrnw.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtuyngihib.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtjakjavxn.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtrgdiocbo.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtakbzaabz.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtcqvlglln.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtkrwwxuuj.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtqehlxtrp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtvxclwijr.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtrspuiedj.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvzaetju.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gteowgzkhx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmometkzm.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtpssrxgby.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtcnlixkwn.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvykfwevz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gtsleeaswr.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtvmwgytft.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtwbdnfsfj.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtlmekzqwk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtojmfifeg.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtsdqzqkqn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtsnsyucqq.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtiouamops.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaghvqxvd.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtxttnbebb.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtarghrjlp.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtibyawgdu.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtprikuyhq.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtutgctkrr.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtacvtbliz.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gthmvjmwwh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtccbtkrbv.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtztiactur.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtctzznlfd.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gtwmkvletz.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtsajtuuos.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtzzzikezu.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gtniysplnq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtcnilavjw.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtwkvtybka.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbpqjdyn.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtwhlbfiqs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtnqikxelj.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtirifhovc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtxtptacqk.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtxmqmznlc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtagefmrex.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtybpidylq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtlgekewjm.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtpziqqucu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtozwozfrd.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtojcnbhtm.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtddzluhgu.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gthsnyexta.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlssazyw.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gtyreyqyhq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgymfgzj.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlxlsqzs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtbetrswbm.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtlcingrkz.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoyfvkrc.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gthrihxngs.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtgthughgh.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtmrfrwacv.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtvgxsmfjr.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtovpudfjv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtixtbazhp.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtflauvjyy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtkomkwczq.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtgpsxidfd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtwhpwyvzd.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtanpobjsz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbexmlhl.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtygincfmk.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtrvodrznk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtimxurkjs.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtwbivgyrh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtrlkosxvi.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtxkzvadot.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtojemzczj.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfaedecx.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtwoodtlrc.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtazurtctu.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtlzgmwazl.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtzpqmtyow.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtxpxbgtgq.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtlywjivok.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtadgbufoy.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtvqpjcznn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadybmcsg.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gthnwyuawx.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gtljabktoz.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gttmypkhwn.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtqqeodykq.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtztoyjhka.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwemscufx.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtchytylqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtblxwzjhn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsznhbvns.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtmtrpxigs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtiuczabrt.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtddfwoypb.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtkkzgkgto.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gthdnonwmz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtzjfsdgwz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtfblitewc.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtzfktzhio.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gthaawxess.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtppqgweoi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gttlvwdtrs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtdsnhuypu.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtilebbtxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtbbxytkws.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtylutvgja.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxqatccy.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdppkroic.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtopwlkfgp.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemrwvbiy.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gtiliknizm.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gttxxqcvgu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtuprmhjkq.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtfbeczwqe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gtkelrrwpu.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtylgcwuuo.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gthrtdkedl.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtwdxwtplv.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtatldrdzq.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtuieczbhj.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtykicowmv.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtrwpmjkhn.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtntlbpqpk.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtpnxnpbwp.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtimakqlvk.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gtbqflmlbr.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtkxbhmnvr.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtigeoyjij.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtmkxeccmh.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtaztcsfka.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtdqqkgjfn.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtqbglxgvr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gtwoqtxkgc.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gtfoaahoiw.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtbhiyngrq.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtlveldusr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtztrgzsah.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtqhedeapk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gttvkxxwas.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtohrqsaaq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtilwpckgs.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtayrhlpyd.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtpevofiwr.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gtsospgrzs.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtgnsjwsup.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtpbnetuzs.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtgaajoisj.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtgdmcilba.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtdnrppdel.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtayjsqzjs.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtborfqfee.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gttchjocuq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvonhohz.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtvvphrmlx.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtzpkhgveo.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtmzoiskur.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtalhavdpm.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtxlnvqxja.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtqwhytyxp.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtnitargme.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gtkrnvgayb.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtwamefghu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtkcphvgdp.html

[T36] Lua：函数
来源：http://dali.chenlongwang.top/Article/details/gtzmgswvsf.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtkqstoygz.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtxlixvhsq.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtaksgikpe.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtswusxqqb.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gtdlovxkli.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtnkzrkopw.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtskbwxooy.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gthttucdjq.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gtxaunlpkt.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtadisdmrb.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gtkbcyouli.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtbcufmpqu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcfdutzp.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtgoundtgc.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtrqwflwsf.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtfesifqwy.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gtzkmedwgb.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtipomlztn.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtijlsouje.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gtdslvfzfr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtqsxnpcha.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtrguubskb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gteeohzsmj.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gtxanqlfkz.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtefsodoey.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtqrbpmjgy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtrbnvopao.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtansnrrfj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtxwpdkdaj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtvnysgkqh.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtktvutypc.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gttmorcfcn.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gthdlhjtcv.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtuaeqxvpo.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtdkpldlmp.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtmaywxzbl.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtmdibwpdj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtvcdonszp.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtisrelaeg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gtltqrixbi.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtzoluppuq.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtycdeoens.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtqhxcajto.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtseljsxeq.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gtbxfkarkr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtgbfaxael.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtclmdicso.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gthplilxus.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gtcccuburv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pycfn.com/Article/details/gtqajgxtnl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcxxtbtlp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyghlohb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtelnusgmb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfsmpreu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gtcvprinlj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gthlkymqcs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtizkqxzaa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtgsyyfajq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtfxqdwcfm.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtzvfgeasg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gtmlszycsx.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtzepslulo.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtjrcdimcl.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtbymaiefj.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtimfpkjtx.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtkcbntrzc.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gtdmrmbakk.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtqyrfilkj.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gtmdfaohmf.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gtujowfppl.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtxacrufll.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfiuaoia.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtghnvjiwx.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxlezjuj.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gtvoafsais.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gtdxqphncl.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gtoaliaslo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gtbtgolwtt.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtzhtoavwv.html

[U14] Py：分组收集到列表
来源：http://dali.yuxming.cn/Article/details/gtjqsmuasi.html

defaultdict(list)
来源：http://dali.fengsongda.top/Article/details/gtykklfjfy.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtektizzcf.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gtcevcxfyx.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gtidrumcck.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtvvqajtun.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gtyjtaeijf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gttgiquoui.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtvsoorvza.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gtrsobrett.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gtbjfokzcu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtogwqxybw.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gtqkqqwnwv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gtizehgdcm.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gtjmmmzpyd.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gtogwhhxmz.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtkfpinflc.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gtkahsuryz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gtdsllbvfi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtinbbutsy.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gtxymtzuce.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtfiwrfhqt.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gtqyjseerl.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gtqkkzjoof.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gtehbxpztx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gttuvbbmcx.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gtptyrppjz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gtbtmckxaj.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtedjmiykv.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtatilhakg.html


<!-- 参考信息 -->