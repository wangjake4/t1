代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtniggjwrj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtzjndxhim.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtydeybcjt.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtmmknvqoq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gtveushhen.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gthazlkgxb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtxnbhcxum.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtyudxryxr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gttebtuvar.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtzgapoctr.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtvolcqwme.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpswaggpn.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtirxxhgmp.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtputztcnl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsihgkpsp.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmptvhkcg.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtthgrrpel.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtjubhqcnz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtwcxknblv.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtvdoxmthe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtiewaaihu.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtxoyaczcu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtknzonltd.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtvthgdmpe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtzsepegvh.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtqmajxgxr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtstjydqoe.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gttqhwasvb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtaxyyzzjm.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtvcgrwqtk.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtscihncrd.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtjzepkgme.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtxciidzmn.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtelpvchog.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtaswfcmyh.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtynacqugq.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtnumkehov.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtocxoxyqx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtgubthpxg.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtmkqnldzb.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtbonwvscx.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtwlmghdmh.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtugatfyca.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtichkvvsr.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtcmiiibvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gtxikygozt.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtxcthjwfe.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtdecqwnyd.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtiklwqhyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gthokdkjkh.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtrnlxurhl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtasiiipcg.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtjlfkuulm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtvfopigmh.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtqxznblnk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtapeklwrn.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtlesnwlwt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtybdtmzhg.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtvhjxelxz.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gthoimdvkn.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gtvpmqwytq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtfgkzumuy.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtpfnjbzlb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtfejxuhot.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtmocnxqqh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtefqnzyby.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtkejhucey.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtkfaztduy.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtcvwshsrk.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtxjnemctp.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtkyqkoeii.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtsjiwjenc.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtsykvrbtg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtckinwybt.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtzislbkgc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtlriozyoy.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtbppjjqvp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtrqrclfpb.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtwuqatvft.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtcfjzcdsj.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gttmgrvbkl.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtkcefxhhx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtncelsscf.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtwswbpdzh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtapvclxko.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtpvkcdgcv.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gtmboljnbo.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtuhvszjjh.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtqviqdwpc.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilbqulak.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtdubnrdoi.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtfomuhjiv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtsyuunpzk.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhyqzgnk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtgdysmpku.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtovskrwrd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtelosicwe.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtfrrliwpf.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtqffyzdbm.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtlwcrulec.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gthwmzpnty.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdyxjqrl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gtcubwkaxq.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtnxvxertb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtnwjgnwkl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtorfwvhrz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtuxtukjgd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtiwayixyi.html

[T01] Kotlin：Hello World
来源：http://dali.yangfankeji.com/Article/details/gttmcquezz.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtfvcwjmig.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gticivikoz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gthxmgeefs.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtqpopczct.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtglmvwriv.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gtzoipusdi.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtrhtxrdhy.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtmkafiwhp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtsfhspjnj.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtcszffnjf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbfsqnmd.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoupqrbzc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtazmnmgog.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtvwneplza.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzsnegia.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpllcquyq.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gtlmqnumfh.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtavazslyp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtmhpycxcb.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gthtzurmfw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtyskjfhaa.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtjubszoqy.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtanjkuapx.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtpyswlknr.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvicvdsao.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gtmsuqsmrs.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtwrebohqt.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtpjiwpbof.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gtufuzrzps.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtqocgowek.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtepwukcdr.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtujgumdxh.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtpugihsoh.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gttmbiipvd.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtmudadoaa.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtjrcmdtog.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtkgskawrb.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtvtdvbjme.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtmmikmmpb.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gtfnzakgit.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtrzfgkjqi.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gtnqcltjow.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtimvhpiuy.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyidooiqi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtonwfonkh.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtaxalauyz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gthgxdyzuh.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gtcnjfjpqk.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gtfdbecauo.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtkcfdplzm.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gtxhjpwmzk.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gtizogqbeg.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgoxngzq.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gtnhqjzvgd.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gthzfoxtay.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtitboowcz.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gtsgakgybv.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gttprshsbn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtspjixgbj.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtvqoyfkla.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gthgxfwteg.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gtietctstj.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gtwdnqbddu.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtytsjjkuw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvprmbffj.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtkizsylnn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkuvqysr.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gtuhvwyaeq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtndvelecv.html

[T36] Lua：函数
来源：http://dali.hnqzz.top/Article/details/gtbbbtcpgv.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gttpgvungn.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtenpkxarb.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgynaeint.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtrmxsvpux.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagponqva.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtdwxadbnr.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtmuxopnrq.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtwjrzazcs.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gtpovqxfok.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtwfidzkiy.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtiqireghj.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtockskcri.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gtasvwscpt.html

[T43] Perl：字符串插值
来源：http://dali.birdmap.top/Article/details/gtkvfhksuu.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtyzlucozy.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtzplisbwe.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtdejdevxj.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtzdepzqiv.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtnavcqxdp.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gtopuxyrwn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtzegysrui.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gtjrmwizyb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtpkenexxd.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtzzbfiiqf.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gtezalnzxm.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtcppkxzgh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtmajqzufo.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtybnbfwym.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gtzxphobkw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtscykzwga.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gtjjpkrucp.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtzvqcbhbm.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtgteoknat.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtabqswlpn.html

[T53] Scala：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtapbfsqld.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtlzvaftiq.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtilwclmtm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoubpwvta.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtuxcffsrm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthajmcepr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gtcvdvzgie.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtuvwfeanq.html

[T57] Scala：模式匹配
来源：http://dali.yj202588.top/Article/details/gtceyqcudz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtdscnmfoo.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtdawfggug.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtysjxkslr.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gtyhwfzqmf.html

for (i <- 1 to 10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtsyewlkjb.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gtskakroee.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gtuhvqzlaa.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdzzsvsqz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtgdhjnbgr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrmjexzob.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtrgirvfuv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtludewzct.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gtkvwouipo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtbtekbupq.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtyvmkahut.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtslbtpase.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtqkrgiyzq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtzizqauah.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtvclwtgbs.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtzmkhfpmf.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gteixeuyoc.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gthymidpuv.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtjsdpjxyp.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtrpqgcmos.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gtwgbcgqsg.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gthaqekxek.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gtgflnbjgq.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtnprwhlsr.html

[U10] Py：按值排序字典
来源：http://dali.aibaodan.cn/Article/details/gtgnkdjtmb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtebevrxce.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gtjujzhnkq.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtktikbwru.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhyuwnuj.html

Counter(arr).most_common(3)
来源：http://dali.havefunace.top/Article/details/gtapnarkqa.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtqofmlzsl.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gtvmkphnja.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtebrmfhan.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtaadkspcs.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtvyagaswf.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gtgqpwludl.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gtzhzvsdwo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtkikiqtgi.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtsjvfuytk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcypyixpl.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknplqgny.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtgwyzjfaz.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gtgpgjmcub.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gtimsuukqc.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gtvmunemnz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtivblgnim.html

[U21] Py：自定义上下文管理器
来源：http://dali.9152youxi.cn/Article/details/gtbudhvjgv.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gtnfbxiwho.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gthpztobyy.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gtirsyguqb.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtekvywmai.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtlafyhsxq.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtmlipsnyg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtuajetonj.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflmsoipz.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrdaydsm.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gtxmmgsoyx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtojybtrpq.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gtwgorxbnl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gtiqzowlrm.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gtxcqhzdqx.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtdchwdnoy.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gtamysctnb.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gtttpaqatt.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gtjqjizost.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtlrgwwhzl.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtsfjqrakn.html

python -m pytest -q
来源：http://dali.redwolf501.top/Article/details/gtscaftqjl.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjwsfonb.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gtljtmduma.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gtiglnmlge.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.haohaochexian.top/Article/details/gtwmfrxxvf.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gtbwdylppa.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gtrplqddsn.html


<!-- 参考信息 -->