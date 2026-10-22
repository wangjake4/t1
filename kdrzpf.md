代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gt2tpdovzyq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2ymomeauu.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpfjbece.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2qoggzxyv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2ccqydodg.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2jcrlxmgl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gt2efdrkqsj.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gt2pzpcvrai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2pybdfsox.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gt2sfkfbgqe.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gt2ymymxrkr.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gt2dagevwvk.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2yozwittj.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvpvfdao.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2sahieote.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2vclrwplh.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gt2ykcxjask.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2zbppcqyi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2fulcoxgp.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbndkaoh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2bwtvvzwp.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gt2uhelhhyk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mecxhzkt.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2dzzutlif.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gt2gwhmfnht.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eblbysgf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gt2fcevinfv.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gt2gjedtctt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2fkhdpmgz.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxnkcpkt.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2qzobmxjm.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2fobmaxgq.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2bevpajjo.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gt2gdzguejb.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftyncrjn.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2mfubofdy.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gt2olieyixp.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gt2vytldpis.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2kstrklpm.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gt2xfkgjyiz.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2jrpqjtzu.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gt2kvmbgwhh.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gt2nmdskyyy.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2hkkaakbv.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gt2byyumiul.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gt2omqsmddh.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gt2jddqaebi.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dntxtztt.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtbsejgf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2wpyzrgoo.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gt2yeymztsi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gt2efodwhtw.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gt2kzuhlovp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2ionrrlfu.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gt2oxzscwkx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2itkyvfmt.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gt2tsruxcue.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gt2tdttsowu.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2knbzaity.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2ecodcwqj.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gt2hkawmgcz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2kbdpkkhl.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2imfenlhy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2wlbdlwti.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gt2qlztsuom.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gt2fvqmgome.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gt2gowlncqv.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2bjcqvbbd.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxqmeowd.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gt2dkupyhpv.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2gmvisdmg.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbquovys.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gt2jkuegbvr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjhqcaoi.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2peekxuir.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gt2baetcsbz.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2xnrcqblr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cdqzjrkj.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2hobiamlr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2tbsqqwrt.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2jxuxbvpo.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gt2vzeccvqq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2qdimqjcq.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2qabuepsg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2uwaeiyvp.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfziieij.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gt2uvxdloyp.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gt2sodbpnfk.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gt2dkymqhpo.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2vbgodzen.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gt2fuzpvcng.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gt2hwmtqntn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2unxyazmn.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gt2gnkpwaza.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gt2qhzyjhtw.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gt2kyydrbqr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gt2sckqbaqz.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gt2pyixqpma.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gt2zgczcckt.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2mdewfkev.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kskcduav.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2ngamdxir.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2ocmpwxoq.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2wwzurxft.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2jnimfrlx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgiblerj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2nspfahwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tavtthgc.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2wiuofaac.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2jdusxapq.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gt2waolefam.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gt2ukmbxdwt.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gt2itvzisdw.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2ivdmarcy.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gt2lszmgbab.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2vpnhgckq.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwurzvzj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gt2liwudgdq.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2tkrwkngo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2ztorbdmg.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joaqjfqg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gt2qbindwuj.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2wtnbkrrc.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2xlzzhqes.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gt2zbdxznet.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gt2cgnqkysy.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gt2teozimtm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gt2edbbrydw.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gt2fxgbwedp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gt2shvmewhn.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gt2alwzzrob.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2bkopzcuf.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gt2gxuqvzpp.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiqrnezo.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2ulruhqps.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2zhwwyksk.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gt2eyocklqt.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gt2xicomptu.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gt2jvtnepew.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmipayen.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gt2lphrpkfj.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2oqtghjqw.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2ufzzmjws.html

"值: \(b)"
来源：http://dali.meibo888.top/Article/details/gt2ijegrrjj.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2xexwjdfp.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gt2asngixog.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gt2zinrorci.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2hfgpbvyv.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gt2jkcxebhf.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2mucuqneu.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gt2milnneer.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gt2mebtrhng.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gt2knjjhrcw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2iujrhjqb.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gt2cvqxvein.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2cotphmcp.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2urmhvotg.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gt2awrkrwty.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gt2hdreddzj.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fonghgpj.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2dtjnrcfj.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gt2tewzpysq.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gt2gbcdcjdy.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gt2kioydcwz.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cozvuwdp.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gt2fuwklngb.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gt2dkztgbgu.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gt2iukufclx.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gt2lxodbzag.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2qjomyqjq.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gt2futdytrx.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gt2azmshouw.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gt2mubvihps.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gt2dpjtvuev.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gt2dhhicmiv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gt2azpvhcus.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gt2zcbaywks.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gt2uhknllgy.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gt2mnwararp.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gt2fdxcjibi.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2qydwifzo.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gt2khnhpwlo.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2lacostdx.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gt2zftihgjn.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2breryllu.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiawxpgp.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gt2mejwljwf.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gt2qsifnobw.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2mjedipoi.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gt2hiyxxwsn.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2vdxqdybs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gt2qpnakqjj.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgmtcgif.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gt2hfpnhjwo.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2dczhgwbd.html

if ($a > 0) { print "正"; }
来源：http://dali.yueranfly.top/Article/details/gt2qtrkkvga.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gt2sryrtufw.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfpbzbse.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oboxykzh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gt2mxzoivhf.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfakdohq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gt2sotxiczv.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gt2ilhzmalq.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gt2ihjhjsid.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2lwhrhrzt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2lwljuzyi.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2iilgfhkm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gt2klfkrvwj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gt2rsxwtiyr.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2cuurxwbh.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2weuzoprf.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gt2wisqcvno.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gt2zlnkpzvm.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2lqxgaqjs.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2zdwmbkdh.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2slgkmnco.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2dlvtubvq.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2gyzmysim.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qysykgtt.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gt2hssygbwc.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gt2znnaocol.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2vsdxvqpw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdpjuhph.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gt2qmoluxnd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gt2fuhmgxdq.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gt2bgzybilt.html

for (i <- 1 to 10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2iwfzhvrr.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gt2ozorgpds.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzkpkhcj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ffrhcujm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2ymepcejh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2gkjimpzy.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gt2fhqkdprx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gt2luwixjtn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gt2mapmywmw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gt2bdpdhlkv.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gt2kciavdgq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gt2enxdgbmz.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gt2xyazrahy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gt2xzhyseuh.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gt2jxzmdifn.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2xxieeuxf.html

[U06] Py：合并两个字典
来源：http://dali.cqqwz.cn/Article/details/gt2rcydrtzl.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gt2dhhnvmlx.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gt2lwiumsee.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gt2swehzsws.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gt2dwqxpypa.html

[y for x in nested for y in x]
来源：http://dali.hnqzz.top/Article/details/gt2voxyirpy.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gt2ziecbwdi.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gt2rypkdlgt.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gt2mbcdzpsi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gt2oeiptxdp.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gt2tqbnejor.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gt2wcbobvna.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gt2kwgykoys.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gt2fyrthvaa.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdmokgbt.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gt2hipbawrc.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gt2mgojgtsc.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gt2rwndnqgz.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gt2ysnwxjqs.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gt2onqshyzu.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gt2gzfhyvyq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cucudq.cn/Article/details/gt2konerjcc.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gt2kbsdpxui.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gt2pbukfpch.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gt2siuwunge.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gt2bpvnshuy.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gt2ycyobnqa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggdgcdlx.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gt2svuohwtq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gt2jbejplkr.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gt2qbwrzaws.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2gpspcrqg.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzuivmje.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gt2ldjgspxu.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2edqozyfs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gt2qbiibaqh.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gt2rzhvhtqb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2mlogaoeg.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gt2qcvdsmwc.html

csv.DictReader(f)
来源：http://dali.vqdsnc.cn/Article/details/gt2ycereede.html

[U26] Py：并发下载
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bswfzjzj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aibaodan.cn/Article/details/gt2dafjtccr.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gt2xqmkmzoe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gt2lzjcsayp.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gt2eqbfvhnp.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gt2tjnhvyhd.html

[U29] Py：属性校验
来源：http://dali.xziqi.cn/Article/details/gt2zpvxpoyz.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gt2rhjxczss.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcyaphkc.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gt2qmcsdiqz.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gt2ebjhbdld.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2scyjypcd.html

[U32] Py：代码格式化
来源：http://dali.ivvv.top/Article/details/gt2uexzpgah.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvzzjov.html

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxvswbit.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.haohaochexian.top/Article/details/gt2xgjwwkhp.html

[U34] Py：判断编码
来源：http://dali.tanke756.top/Article/details/gt2wkepkorh.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2mtuebpjg.html


<!-- 参考信息 -->