代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2qzpnzrdc.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gt2xixdlngr.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2utsygyio.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2gsveochy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gt2ldxffctf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2sckqrkus.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2kystzjea.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2qpfkohlm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2ykcbkdcr.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gt2fxyoygvq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2ghqhvzyj.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gt2lcsfupqm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2snvrcdpf.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etualcdk.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gt2slvyjnlb.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gt2ngwshaws.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2alrnlytp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zflkmvfi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gt2zdzqyvln.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2kwrhtpbp.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2tkahynfe.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gt2undratsg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2baewvmcz.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gt2elgrxdpz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2gzxujliq.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2rosfmovv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gt2ilbrgxln.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2kjdqokno.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gt2alzzrltc.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2poxgrayw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idpgzhpv.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gt2tbdxqtri.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gt2vxwewtje.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gt2cyogcjwi.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2ofxjqveb.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gt2kbonxcno.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gt2vlvbrovy.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gt2twssyyac.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fswvjryv.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gt2vpjivyky.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gt2kldpfrmi.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gt2vujuumro.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmdgaurx.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mynckqyd.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gt2bhulltaq.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2vfsnnxjl.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2aknfytix.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gt2jpcwreoz.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gt2jfgpujka.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjhnrevk.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gt2kgetzxob.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2goncyrcx.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2scmitzzn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2sordcyyx.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gt2peclcikt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gt2gpmwubty.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2zuevvszt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2kahiuxbj.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gt2tntsnagy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2iwyqyagr.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gt2lgnxpxzm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2knmqlptb.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2dowqixyo.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2jnaqltzm.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2xfngivua.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gt2eokvukhy.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2fmnuottg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gt2diwcilcq.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2mjblhlwk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gt2jgwjglys.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gt2ysjqtrbk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrpypivs.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2jugokzvd.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gt2ltrawryb.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gt2yksbiyut.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gt2jjvjdxbz.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2uoibtdwn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gt2cydbxabg.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gt2vliqesnh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2gjstlbvc.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gt2eyptwpse.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2uhnehahm.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2fmzigevl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2kcboezlk.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2yjisrbzt.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2vwnxiqsf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2hyidmdjn.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gt2blvlsfeu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2kbjfqsgs.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2falwttyl.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rghdpbzm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gt2vklcwcof.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2vgtmwwos.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gt2rawuozad.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2lhboktdc.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gt2ajhgkxhu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gt2lswlvuzh.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gt2boqatsmk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2pltxhhpc.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2yzungupn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gt2gsbczqmk.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjvddktd.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpzohvqd.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gt2rswbuhix.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gt2klyvedap.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gt2eqinwtdm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gt2hyhrhmam.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsbrdejh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2tamygnwd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2fvyopoex.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhkllgmk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yxzseiim.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2hvseuwyz.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2juvudjxg.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrqbeaaf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gt2tsungtgv.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gt2jsozgtyq.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2kdrxpwzr.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2tklvgoys.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2redkjopv.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2omdelexc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gt2kexljxke.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2zysdqmgu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2iqqvudsk.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2spafxsrx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2uabtrjdq.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gt2vkbvucod.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gt2wkkvyrnp.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gt2njwxgago.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gt2girxbpre.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gt2bhukqnro.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2btilccrc.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jymslbdf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gt2jzbcacgp.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gt2mbhmrhju.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2dhzxodiw.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gt2imwisvfg.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gt2wexmcyjo.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2pttbxxxr.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gt2elhhyuyw.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2ejoektnp.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gt2knhjstnr.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2iemtyljg.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2jbwuxhgh.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gt2kdvmfglh.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gt2thrknjtc.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2dotixwzg.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gt2lzfsuhbf.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gt2pcfeisvm.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gt2oxlrdphr.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2btvjtzwj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gt2bxhbqxtn.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gt2xyrftmgo.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gt2yqfvflxi.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gt2hshfbroc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2zdcegynq.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gt2xcxjzpmj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2tfxlukcg.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gt2bxctrdhc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2uivntzzv.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhmyciyi.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gt2nexwqeff.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veeszmkb.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gt2suoclwww.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2behugfxr.html

do { try f() } catch { print(error) }
来源：http://dali.yonumen.top/Article/details/gt2ouqauazz.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gt2dumeiqol.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gt2chhqiqos.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2yhqkbmgk.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2plcdjfcw.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2vfemkapi.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gt2wqlwkuig.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2ycesfxlt.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2bjxktjiy.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2dgroiumb.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2clnauryd.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gt2xqlsttns.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gt2slwsdshm.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gt2yxelyogb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gt2qtribwwo.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gt2xaqzavqi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gt2afphivys.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gt2ugspptih.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gt2tnccryqc.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2boxeawdj.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gt2alclwujz.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2bchaxdhz.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gt2rfporerj.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2khuetczs.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gt2acdlpvih.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gt2ktkqpjpm.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gt2ctgfjqld.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2wxzybnhw.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gt2wlxuahve.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gt2qwgfjiie.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2gqdpviva.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2rbzsuvzi.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gt2woivcfbt.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gt2rqanbicz.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gt2nqjwomdd.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gt2eadveqqs.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gt2qccgmvfc.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gt2fhxnpymz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lldvtbix.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gt2lklnregk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gt2uhkzqwrw.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqavjxdy.html

$s =~ s/old/new/g;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrorwgxh.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gt2srvnnojk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kklcdxun.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2dfloinfk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gt2roseljgh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xftgniel.html

[T51] Scala：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2jqqhdzud.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2qabkeucu.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdonbqez.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gt2eqotnhkh.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2qyvieykt.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvkeaopi.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2qbfgxebn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2zgexitcj.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2plffnyxd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gt2mlofttos.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gt2tvswwvcm.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2hwmuztgk.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2nkmhoomy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gt2ovwemnqb.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gt2aukfkwpd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gt2llqjmzsa.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gt2ewcukdoe.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2lydcorsi.html

[T60] Scala：折叠
来源：http://dali.snrcjt.cn/Article/details/gt2lxtbdoqa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jexrlyru.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2hcaawpyb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2oxqfmqcs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rdiuxzzc.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2qfzghotg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gt2pfhyoobs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gt2gznpjdvy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gt2fzkjtznm.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gt2wpxdjhaf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yvedp.cn/Article/details/gt2dwwzrqnq.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gt2rcwzgemc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gt2qdppayxh.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gt2nawgdqci.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2jvmpcjew.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gt2qicmnxbu.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gt2tcvywgdq.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2acitubzx.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gt2becfqrre.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gt2uaxivnqr.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gt2sotxuqli.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gt2zsdzokms.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gt2zbhvkevs.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gt2jknurbvr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gt2hyjwrwey.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2aiyzctss.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gt2fusmiyso.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqbktbxv.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gt2thincihy.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gt2slmsrpsd.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gt2rlsalxpj.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gt2meaoddnz.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gt2pfjpskfh.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gt2ybxmajry.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfjzzetp.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gt2miehsgpc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnejfjzw.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gt2yyfsdrib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj202588.top/Article/details/gt2bourkdka.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gt2navdzsuy.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2urbndkmf.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkplngto.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cqqwz.cn/Article/details/gt2sisjjuxu.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gt2wvmlsrch.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gt2izadgali.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gt2zpgyrkke.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gt2blfjryva.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gt2muwbdkpg.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gt2ijmilppi.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigufen.top/Article/details/gt2ognyokga.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gt2nishdhtl.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gt2ukrdsnzy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2ztktxmgg.html

[U25] Py：CSV 按字典读
来源：http://dali.gzhubu.top/Article/details/gt2wazdscor.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gt2hnltxawn.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gt2rtnaocnm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gt2xlbgqzwm.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258888.top/Article/details/gt2kvdvquuj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gt2jbjjklsc.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bohjfydy.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nplajnal.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gt2khlmtokk.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gt2dekowomg.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gt2ezestjof.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gt2udyectds.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gt2ncrvgzrv.html

python -m pytest -q
来源：http://dali.kuanghao11.cn/Article/details/gt2qmakkcxt.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gt2mpuetgua.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gt2ydtotbyo.html


<!-- 参考信息 -->