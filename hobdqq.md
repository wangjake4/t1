代发 wailian999

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2hlfovbmh.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2tzfugztj.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gt2zyarslpd.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gt2jmatfvdl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gt2iqgwxoxx.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gt2bxrllyzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gt2fsxsgsaa.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gt2oeftmpbm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gt2jxofiiqu.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndczqfjv.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2upkijmhf.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2nnwcfemp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2lkhhdwjl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzuugkmn.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2qjsgdjnf.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2bimebave.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2inpmacsu.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gt2tysypttf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gt2nupirmuy.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2lxyxffaj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gt2ecqosiie.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2kxvecjbp.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gt2ymjsceqn.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gt2hiuhsqgg.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gt2ahjfdgym.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2sjdmwzum.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2ntqjzsgr.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2pigjoppt.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gt2yxthbnki.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gt2vynhzxoo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2dwmtjuzd.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2zfnduglu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2feuowmzc.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gt2vmmbnwdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gt2alamwyrl.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2caqgkqxz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gt2qdchanmb.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gt2zbcuspkj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gt2jzidkgid.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2bzusblqw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2tstwhqzf.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gt2tnxrxtjm.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdnlcdkk.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gt2avzjfdiw.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gt2fhsilhgs.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gt2kqxgjwlr.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2llicsubz.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gt2drjgcvgz.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gt2bomllbnw.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2gjxnkuim.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gt2lvhmonro.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gt2idjgoojb.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gt2julhyrpn.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gt2wmvewiwo.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gt2cfjxisyu.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqwbmnvv.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbprvuhv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gt2nsrgpeee.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpdifsij.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2yoprjuor.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2mzeytbbq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2djxcibdx.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2ohqpdrjn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gt2lxqehkxv.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2snmphrnj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2rlqcilkv.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2edjrrsfv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2igprzmtj.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2vzrbzojb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gt2qjqwyuix.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txqeilwj.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gt2pkmbatfq.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvbgvkfc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gt2intebvrt.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gt2adikjbck.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gt2sttiimli.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2ibsvkqrx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gt2ygnnedxq.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gt2sfcekykz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2eurcrrik.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gt2frekjbwl.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmfyzuhj.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2cjchjmys.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdhuzhp.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gt2bvbbbcex.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjgsvafz.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gt2uywitcrs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoojqngt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2hriltpad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gt2yarukiau.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2rofkpkcz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gt2wneocwfu.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gt2rxcnqvmq.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2oljpjzlt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2veeiuauf.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gt2bfusancv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2eeayyntn.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gt2rxfymnzz.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gt2ilwqcbam.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkusvtxx.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxryysuu.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gt2mrhtsutn.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulpqyjlr.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gt2hozwnfux.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gt2qyjafkdn.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gt2qxcflare.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2leviebac.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2jxlixhvq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gt2fbjlilka.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbulchpo.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2aobuedow.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gt2bbdztnfm.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gt2rejedrxl.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gt2mwldjldz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gt2vsizjfpw.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gt2qmsofgfk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2oqogrosb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2osjskxqo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnixqcjr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wcxuodwk.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2dbuosdtv.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2xnaneege.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2tuatijrb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gt2wclusnpc.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gt2ihuzqllq.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gt2qiouuteu.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdodtumt.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gt2yqunborn.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gt2ahmjtajx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gt2ivupjzhp.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2kzefemvp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gt2fqcgdjad.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdkxkvru.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2riyogyai.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gt2iqxztnjd.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2tuboxaeg.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gt2nkdmvbhj.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gt2vgzattbr.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2iylpgeot.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gt2lowqpolj.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gt2ktxwxxew.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gt2pqytldzw.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gt2jyrlricl.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2jivquxeg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzxmxobp.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gt2jakhrrpx.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctdxbdkj.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2ztwscdxk.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2vpbfdnwf.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2giwhodwb.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eerhtipj.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2cswwalvi.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gt2kfsahufh.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2ipbsngim.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2tsiknzut.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gt2fsfffrbx.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2fqzokypv.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gt2qjpzdjer.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gt2xbcvpjbf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvjfkcwu.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2bjwvwjyf.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gt2oamkhttb.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gt2nssxsymo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gt2bhjsfusl.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exffbddv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gt2nmlntvjh.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gt2vvsucpsp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2focrohhs.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gt2ottiqnvm.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzgpeoze.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2ymlvsilw.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gt2afythjcb.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gt2fofopwsi.html

do { try f() } catch { print(error) }
来源：http://dali.dianchejie.cn/Article/details/gt2vrxwwpgp.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2kpbbgdpp.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gt2kpofephr.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gt2hwiytbyu.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gt2tjmnsqpn.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gt2fuojtwqk.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gt2uyfuwanv.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2amtvdlsa.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2bpucytct.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gt2bxtudofa.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wthawrxm.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gt2mdayinfi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gt2pvpecgks.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gt2iomsnoii.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gt2avfcbgws.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gt2tvtrdqjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2mjrrtkbv.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gt2opfnplxj.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gt2ogmmzzjy.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msxflnxu.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gt2nfezkhkv.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2hxocpztp.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gt2ymehjzwo.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2rrxyyzkb.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gt2lajsopxp.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zywcbpos.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2smlofzew.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2wsvicnhp.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gt2zajthqbq.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gt2cudbbsoo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gt2upphqbju.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2olyxnjrb.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gt2rygqtpkr.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gt2sccyiitz.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxkhyrjt.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gt2romnboxj.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uiismhpt.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gt2wrmvbveo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gt2mnpclxrs.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gt2ylbhoncn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2zxggbqdx.html

[T48] Perl：正则替换
来源：http://dali.chenlongwang.top/Article/details/gt2ylespigv.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gt2yrqlwqkl.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gt2gscqrzcq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2tggpkemc.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2wuhmzxek.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gt2ehqfordm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2biviuxwz.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2nzmauhyg.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2tfthlsua.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gt2aghroyeb.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2zivvgldf.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2vfbrowrg.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2tbpovpbi.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2ukglnzvv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2xajzyapl.html

[T55] Scala：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2kxstkppe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gt2kfhsfmrg.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gt2ujajfmmc.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2iwadiqrq.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gt2mdwhvewi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gt2mfdvyhqu.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2lvasswwy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gt2gndvzhjo.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gt2ohwncauf.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2ujapukri.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gt2ujkalrdw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gt2kjbvjwbb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zyqdwbid.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vilireep.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2trhanerp.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gt2aackfmin.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gt2sqyjyspi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258888.top/Article/details/gt2optmfatn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.snrcjt.cn/Article/details/gt2cwngbmcb.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2dfuxqxiu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gt2nfjtkvwh.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gt2fstwwqvb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gt2kwvskgab.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gt2tfdqjrpo.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2iqngnmkb.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gt2vncpmrdj.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gt2dpnyusvr.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gt2ojomhrco.html

{v: k for k, v in d.items()}
来源：http://dali.ppjwa.cn/Article/details/gt2dxrhybjl.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gt2xntkyygq.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gt2zzazbeuu.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gt2owttezts.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gt2iywctrsy.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gt2zfrvwhvg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gt2ftrsdrse.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2edeqzcsp.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ieluzvys.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gt2bfkskmxa.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gt2qbvllknq.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gt2mxcckefd.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gt2styjurks.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gt2dnhdbiam.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2ljnoizvv.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gt2jusrnpya.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gt2qsavywmg.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigufen.top/Article/details/gt2nhubrihn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gt2jzzbiuva.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gt2rrhocwrc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gt2gqoceiqs.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gt2pibluzhb.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykbuyxnq.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gt2wwzfeuzq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gt2wrqnutpx.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gt2zsnfepsf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gt2jygebkcc.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuanzx.com/Article/details/gt2asutxujb.html

@contextlib.contextmanager
来源：http://dali.9152youxi.cn/Article/details/gt2krootbrq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgypctt.html

list(zip(*m))
来源：http://dali.yvedp.cn/Article/details/gt2tlhxmcam.html

[U23] Py：分块读取大文件
来源：http://dali.dianchejie.cn/Article/details/gt2tbvdypop.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gt2ywsgxmuo.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gt2jyfjpsmi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2hxdkgrcw.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gt2aaxhhuhq.html

csv.DictReader(f)
来源：http://dali.gotoacloud.top/Article/details/gt2jjppymld.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gt2zqfuajfp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gt2kbsppcsq.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gt2nukfvjsh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gt2mdtmvvai.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gt2vozqcpgz.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gt2ljdggbxl.html


<!-- 参考信息 -->