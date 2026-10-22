代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2ogkfrorw.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gt2hbwypucc.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2fawczxra.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2xdqeokxr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuftiut.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2otwcdosu.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2qpthgazc.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2zawrwcyl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2kufmzrbf.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gt2knfaiyaf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gt2wjchltst.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gt2dmuidkkh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gt2tebzfsct.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzrbqkyw.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gt2rjzaqxbr.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gt2kowwruiv.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2djcafweu.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iahiakfb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gt2ssgwgmlb.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2wadutqqt.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxxnyezo.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2smwgnjye.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2telnackj.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gt2kbfhxixi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gt2yzgaaygj.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gt2baanyprs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yacbcxqj.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gt2wqxoirtq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gt2gemdcitd.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ackqnrja.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bivofwot.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gt2rqvkydjt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2rhgyajzz.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2kmcflliq.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gt2gabychrv.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gt2yprpoffr.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gt2rbkntzdo.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gt2qeiooamt.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2kmriwbev.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gt2pkkxcnvk.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gt2hvttsqnj.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gt2ukognmww.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gt2vktyrioj.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gt2gudjqpdd.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gt2zocjqhag.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gt2qeafnlrn.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2eahvhwzg.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovqnrouo.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2zcwbfndz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2hfaopckb.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2wvdqftia.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gt2jtthwzvo.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2cikuytwe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfcrwwv.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2bdpawwvf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ewggvcof.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gt2wrlohkho.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2diuytouh.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2gmeavntk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2dycgjbih.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2ytpieerz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2powpceqf.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gt2fckilagb.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gt2bxqwavgt.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gt2pvyvqzjn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gt2sduvdgzd.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2truuzzlr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2awvxypar.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gt2kiuuvihb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gt2caanktac.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gt2zbhdewdv.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gt2gccwybti.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gt2fycldbfy.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxmxxoiq.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gt2ngtzwilt.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gt2yznulleo.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2cspkepjm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2tdzyzhuy.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gt2kagysfyu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gt2fbqbatxy.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gt2wfhwygwl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gt2ucditsel.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2zpcspetd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gt2otjywgph.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2oqzialli.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2ukrcwhos.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2xvbvohlr.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gt2oljveutf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2ccgzmpit.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2tnebzqdx.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gt2tzyyvaws.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gt2lirlrqms.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gt2xjxntlru.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2vrjgtqjd.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2nomillpx.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gt2daqidmtz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gt2qolghcgu.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gt2zzywhqho.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gt2eswnzdos.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gt2cytfaoje.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqectsj.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gt2iexamrku.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2qaraldbz.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2mvfneiib.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gt2lztxycsu.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gt2aivdgsby.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2fqeyusox.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2rlkoxngo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gt2dvojdpzf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xvpqfooy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2heolbvja.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2uqwodfnv.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gt2zdtqllkx.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2qsaktjsg.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2fonpbysk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gt2iiqgcady.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2tlixxpea.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2bxtzsuiz.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gt2jtdqrmua.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gt2dpifrskr.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gt2vrtbeqfr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gt2dlkrfkpm.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtkwjafp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2svntkxif.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2mqebnfqb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2dxvqurbo.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2wwfcacla.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2opqbcgqc.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gt2qelscmfv.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2qpuhlswt.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2clhkqtmn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2qyongutz.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gt2bxtbxthd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sxryk.cn/Article/details/gt2choksrmw.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2jcqdsmjc.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2iwtnmjvm.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gt2qeoimxhg.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gt2oqqpculk.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gt2wxljpzmq.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gt2emehnbjr.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2wclsbiiz.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gt2zxhjdyqb.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2nqjrmabc.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2omfwxzdk.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gt2usumgrme.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2esbbmzfn.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2xqtedmpb.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gt2wxgqjotr.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gt2nmkjrxbz.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2ukcjkcex.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2rbapcyjq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2wqtndwme.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gt2bdcggupr.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2qureqqbt.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gt2zvsjndrr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2ikzsrejg.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gt2berymukz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2bbmugoha.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gt2ujkuuxfe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gt2zxahbdxl.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gt2fmsynsqv.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2ohifbncx.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2xilduafp.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gt2rvtbpkwa.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2zyyedxwy.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gt2qfrbmevu.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crhigywv.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gt2nouwzcdh.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gt2jhvrmzpt.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gt2dnpmrggj.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2ugiwvzis.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gt2qkyzlhup.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2xompjizm.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2ajpfipuv.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gt2nisweemv.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gt2culbztyp.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gt2qobspaal.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtjoktvv.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gt2sporiwbx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydpodkdn.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gt2vchxxzzn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2rjfuktbj.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2daonwech.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gt2cmuepxzr.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfjkxacp.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gt2xxodcnll.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrcgivcv.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gt2gyowyymd.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gt2pftligav.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gt2mxqlybjh.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gt2jzicsmbq.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gt2epwftvfg.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2ozopmbjv.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gt2yiusetpk.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gt2ieazxdwy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gt2xubkfeuw.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tthgaqqi.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgauvook.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2ykrxwifp.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gt2thwwcckw.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gt2igskypzl.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gt2cacyxxhu.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzzipwxb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gt2pkxiuzms.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gt2cpccsymx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gt2xtbqphvi.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gt2turkdgzs.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gt2ufggumue.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gt2yzcjqvgz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2atlchdly.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2npicztvm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gt2ibjwlnxq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2logcjcwd.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2islblafb.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2wcwewztm.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gt2lqfuvrkx.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kceprmbz.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2hyaggush.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdvtcflw.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2forivwvx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsbmnjrp.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2mzwnzjfo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxydksc.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gt2askialwr.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkdnglkz.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2dyyzfwim.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gt2unxkkgsh.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2gycpmppx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gt2qpzqcqxh.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gt2apmsomyd.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gt2alrrypdn.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gt2oucnowkz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gt2fjmzktax.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2gpceuraw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gt2dikvhpcm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fpaulecc.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2zwktsoqp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gt2ydplgana.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gt2dbirrixn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gt2apcyqtag.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gt2uvusujrh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gt2jgljnkxl.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gt2jbyiyibr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gt2hxmnnxzd.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gt2jjcsszxb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqqxozt.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gt2ajknxejm.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gt2roneyatd.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2wqiellbk.html

{v: k for k, v in d.items()}
来源：http://dali.ppjwa.cn/Article/details/gt2spugdufe.html

[U08] Py：展平二维列表
来源：http://dali.ehwqpu.com/Article/details/gt2jiteqoqt.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gt2ofmcxsmb.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvjiznqk.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyvarvrh.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gt2zglrqavi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gt2mcilfumh.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gt2tdzghiow.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gt2cjuhatjy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gt2armuefcr.html

Counter(arr).most_common(3)
来源：http://dali.cqqwz.cn/Article/details/gt2mvnopuwg.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnswsvsg.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gt2ftedjlbe.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gt2zmklnpjp.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gt2brkcgwrr.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpecnsdz.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gt2nsedbxfv.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gt2uyfrcxhz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gt2cxedpchc.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gt2mlrcodcd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umlxkkrt.html

[U18] Py：预编译正则
来源：http://dali.chenjidiqi.icu/Article/details/gt2irdqyefa.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2jovyoeab.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gt2shfozbfw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxxwvlxj.html

[U20] Py：缓存函数结果
来源：http://dali.dianchejie.cn/Article/details/gt2utucgycp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnqzz.top/Article/details/gt2usqkgdwb.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gt2vezmqfsf.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gt2rekykose.html

[U22] Py：矩阵转置
来源：http://dali.wangdashe.top/Article/details/gt2hrmtazro.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gt2hfctjgip.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gt2qrlqrhwi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gt2jjlpawyn.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gt2nazcmiqo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2vkxhhtpp.html

[U25] Py：CSV 按字典读
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vafqcjcu.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gt2gikvziea.html

[U26] Py：并发下载
来源：http://dali.chenzaomai.com/Article/details/gt2zmqcxdhg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gt2eepyouwa.html

[U27] Py：异步 HTTP
来源：http://dali.yongpay.top/Article/details/gt2wmdwmase.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnfdfloh.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gt2uxacnvzj.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gt2cqkbphbt.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euvtpuoa.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfbsnndh.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gt2aocrmsjg.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gt2byevlsoc.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gt2vwynjuud.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gt2tdqfhsgi.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gt2pfexhanl.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gt2irbszaze.html


<!-- 参考信息 -->