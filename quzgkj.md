代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtpnlqlblt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtxdzsqvil.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtycwqvktw.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrlzbcao.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtpypyxquc.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtbizuokou.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtnjmwakkp.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtjrmbmhuz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtmjcpcdod.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtczbhiseq.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtvnfqiekd.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpvyxiuo.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtksclgfqi.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtpgtdymft.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtncqrbrgg.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtgdjvsxvw.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtruadlfkq.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtjvqcoamt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtgdhqxvjv.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtkxdmwnel.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gteoocakjp.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtwleqrxmo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfesfnzah.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtlaoxqmqb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtjyrckuov.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gtrmmslhrn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcprqpmk.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtvalgstpr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gtwfpgpsqx.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtigwjqhtb.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtzmekzgja.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtavtewure.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtcehuefnj.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtyuqmfuxo.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtfzzniwah.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gtmycjsqxk.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtkgjruqww.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtguyhkjad.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtfclmdjxf.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtebqwcmeu.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtbudsfayl.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gthnvyvjjk.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gttelsotvo.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtiibmtljf.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gtwcelsaht.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtctkivntp.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtyidsuwpy.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtuuoeyhak.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtpabeicgr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtppmwfwma.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtanowdvay.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtixfcodvl.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtvildbean.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtxtujfmcv.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtmwuenakh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtobuhdivd.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtaqzxykio.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtudnklwls.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtpvfmrdxd.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtvheopsbf.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtvafwkhya.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtscschlwl.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtclmxsbqs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtwrywohew.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtxxmwxjfy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtrvmyfxhi.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtgibedqju.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtvaboyjcu.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtmzgdinfu.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtmzycgoeo.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtwlviaobn.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gthjrfnhqj.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtxyhqvmuh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtlapqreik.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gthpwtjlyx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlyyzhbeg.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtvskamjrp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtvqksgegs.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtwsrglmjk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtmqvuxwmq.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtczswxqtp.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtisazkdae.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtvirquucw.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtbzhlrgdl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gttxksszbn.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtrkisnvtf.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtujlmkekh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gtssjoswtn.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtquamsbbu.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtrjqascju.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtahwtnzcz.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtlicapmlt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtqfrejvzp.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtumgjodqy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtmocujvid.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtsktnfgua.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtotovdpzs.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtjxxnvwaz.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtfpllkoug.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtjxolmtsb.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtgtyywsjt.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtksjrjttx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtkfugsaub.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtafelmvfq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtdphysimm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcydsrryv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtyrjnoqco.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthzvmlusi.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gttrnejdwy.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtrplaxseo.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtxxggmhnd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gtgublmqvp.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtpxscxwnp.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gthvbljvmn.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtnllibggf.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtvrtshfhh.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtswazaimr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gtcwkjniih.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtmgemwufv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gticifyqmf.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtktlojkem.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtikmyqlad.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gtlidsfkai.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtlxpoujnc.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtmiosylxm.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtstlwzwrm.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtwzrcrgzq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtajbzwxrk.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gtaescxgvd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtrvopjcgl.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtuzjeuzjp.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtcqqvrzwl.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gterpitxsp.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtjqzczloa.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtmonkqkcw.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtnzgxgmel.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfdxrmrw.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtgrnyoctx.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gttcgpqwsz.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtidfzoulb.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtghpklwzs.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtvhocmses.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtkeswqfmg.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtejzruseb.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtyhvnpwya.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtqqzfijvn.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtfzxfdauq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtmtfzqcok.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gtcnfgarpv.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtjoavjqtv.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtnmksyfku.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtdhhhqarq.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtzsxvzzll.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtbqzdczhv.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtisdycrha.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtajozlpge.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtgfozjdsx.html

struct P { var x: Int }
来源：http://dali.hammf.cn/Article/details/gtcmoiilkh.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbvdxowt.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gtffgjobtz.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtzqxzqomi.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjrxwrdm.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtgmcxweme.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gthbnshaxb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtsqcjhlpo.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtryakwquy.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtarqnuigf.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtrczgajgg.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtxqcelrog.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdszaqhvp.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtvmcpuosj.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtnfvnwtki.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gtguwkxdij.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtxcmdvkbs.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gtnsvgeltx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gtefubonxi.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtbgzratdr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtfelcnyfo.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gtspergyqw.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gthusywoow.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtskliyzbb.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gthhqivlop.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaogqmcd.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtuxyyovtg.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtgzmsgjud.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtnmtcqgbd.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtsbgzwach.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gthpctyjal.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtbtzjowpu.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gtpziurcuz.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gtimxqmwws.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gtpzusrmwu.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqytjatm.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gtewwjaple.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtocchblav.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gttvajlpru.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtbbnclmwk.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gtyrdjgsxa.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtjbsdremc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gththugych.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtjidsewzw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtsydcllwz.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gtcvhyphjs.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gthyjelsqi.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtdoecmexg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtwltlryfu.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtjehiawdt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtbuipiaif.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gtjqbdbqvy.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtlshzkqel.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtagjumnwd.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtroihrmil.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gtnspfrovi.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gtfvhqfsaz.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtgjpjmyri.html

[T54] Scala：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtftggvdix.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnickkqne.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtsgbuafmy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gtjyamobtn.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gtjvpfjjzq.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtwtharamo.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtlelujjmc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtuaxwobmv.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtnyxraohn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gtiiuogpbl.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtofkwiuqq.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtozheftic.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gtogqkysix.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjupiaxb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkospwyxt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gthcjjehuz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqfpjuomc.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gtorvxzdik.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtoueyqeby.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtarewqmzv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtctnushgj.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtlxvslive.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtlzadurxu.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gtcivdrhxz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtdjdkwhlq.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gtbdaqbrfh.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtjslzifwx.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtjygklvwn.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtqvfmxddo.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gttxthsxbn.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtapmnodcf.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtnefywfja.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gtxdmjjlag.html

[U09] Py：字典取最大值的键
来源：http://dali.gzhubu.top/Article/details/gthaxeqexd.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtcpmmhuvn.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtnycypeul.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gtgqirpdlq.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gthxislryl.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gtxmfcopjr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtthfudput.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtfxofzabk.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gtiawztzxa.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gtgjhlzmih.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gtceviciyw.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gtqreoqrkw.html

[U15] Py：高精度计时
来源：http://dali.iojbl.cn/Article/details/gtpyaxfruf.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiljsxrn.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gtnvnwnodl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gttnvqlrwe.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gtqshnznov.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gtzzguocmg.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gtpynqdwoe.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtkciunjxe.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gteajkzauy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtzthmpiwg.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gtyjbymxeg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtfoguhnic.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gttyzncgdp.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtxrsejcpz.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtmtgsuaps.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gtwhhkgtot.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtasjykuoc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsqlntki.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gtvnbyuszb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtayjnhinw.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gtopxcaclz.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtwyfhudjw.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gtaouawfxk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gtyiurdgck.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258.top/Article/details/gtakbwowuc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtzydhkatz.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtdurxtwck.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gtbwicavzt.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtyllwftvg.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gttxucszqt.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtftagqbvd.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtzeaskdpi.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtwghrjtyy.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtuuejphxj.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtsodrbmtt.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtyaqsrljq.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gtjvppptpo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yvedp.cn/Article/details/gtguflmrny.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gtcvnldtqq.html

chardet.detect(raw)
来源：http://dali.wangdashe.top/Article/details/gtuldizmiq.html


<!-- 参考信息 -->