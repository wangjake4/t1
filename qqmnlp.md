代发 wailian999

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gt2fohigkyd.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amuwidqr.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2tvshtqbu.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gt2hmmuqpwc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2vuobiuid.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gt2sciofnjg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gt2pefvzfzg.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2yymxhukl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2otfwqxjm.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gt2pxdmschk.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2alnryvaq.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2btohnpwd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gt2ffktklvv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2bckubwul.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2lcxgikkd.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gt2eyujppup.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbgmleqv.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymmapalp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gt2jhreatlw.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2jotwfmtv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gt2dytzedkr.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2tyzqszcb.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gt2juphrwkg.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwlgkxwc.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2xulelyug.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2yxpdiqfz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gt2hvdqzrfv.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ootyzwlm.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erzxiggx.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2pkmrfuto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2pjacgzjv.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gt2ztvnikjv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2flwkwqcr.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gt2bwxvchdl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2ugdqzbcz.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipzaljsi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gt2dazbnksk.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gt2gznxpcex.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2uoezokqj.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrtiartj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gt2jgurluty.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2cvllmghs.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gt2hxhnwaqj.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gt2dutqrxai.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmjhmqyf.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2rhtgezwr.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2gtlnkhyn.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gt2bvchqfke.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gt2iuwxugip.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gt2dltogfaj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2prlfftem.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gt2egdqeuhg.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2wjjrpalp.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2hjjgvymf.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gt2skpkcesy.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2rjgspfid.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gt2pexzrkug.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gt2tlhdsypn.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gt2asdurcag.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gt2qjgghzbv.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gt2luqskolj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gt2zadpaeac.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gt2anbtfyka.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gt2ucympuoq.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ychltlhl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2agsxveqm.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2umzufeya.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2luwtbmia.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gt2bzmrgoix.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gt2fbbicgqa.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gt2pswxpcmg.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2ptoydzrh.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gt2ewuppxfp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gt2tdwlkwkg.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gt2ykzwlkde.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2hxbyupfk.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2xtbqtarj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2kqdmumoz.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gt2cvwczugz.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gt2pkmebexg.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gt2vazmdwgr.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gt2bplrpgns.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2wmzprshb.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uktsubup.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gt2izrmtjmp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2hbfnjmzg.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gt2tjquprwe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2hxjevbaa.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2shaxszqk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntamwvok.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2mfkeqkpz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gt2mofmbckp.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2alipbrna.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gt2siavlrdf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gt2eykszwor.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2aaeqenks.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dryiydea.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2iqwcixyy.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gt2rqnsjzrq.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gt2mqlnihep.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gt2ujttbdmb.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gt2vsstvhdq.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2blkaqivb.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gt2wshrogzl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2bblzkbea.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gt2mopcavzv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gt2wvfsngqv.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gt2kermojvz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gt2amjcfaln.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gt2cujjdioc.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2mzrghmkr.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2hojlsdhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gt2tqhzucpd.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gt2qawgfrqd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gt2fmjyumzj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdqjrxgr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2eiljynfp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hwmhtblh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2gbbxqzro.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2hcvuepxl.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2onfbcfju.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gt2dbiawzkw.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gt2obhsvtfl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2gtygkmkx.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gt2lsukiigg.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2jbitafsr.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gt2unmnbxhw.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gt2wpozrjyx.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gt2obxfcffb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2pplgwzph.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2vjzcqzcy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2nbhanazu.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2gmdxzuvx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gt2qbrezrdw.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gt2ptdyeozu.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2dgmpwged.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gt2pkzamwcq.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gt2qoleqirq.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gt2obkhspdc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gt2bokuxmqu.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gt2kjmiuqvg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gt2tnujujdb.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gt2hvbtfyip.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2oeytfwss.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2mjknqtbd.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gt2ezwzfhmy.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gt2vcadicej.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2chbuapsf.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2jedajwpr.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gt2tqoggiqs.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gt2igazmmkc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjrhpkm.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gt2fscqdmyo.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gt2duqpglyk.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2vespkgrd.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gt2vrsdoyrs.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2wrpldtlc.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gt2kuakcxbw.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gt2ziwgppag.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gt2oerhodgt.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gt2cvgmsgmk.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2bkoeitjx.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gt2sngmeker.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gt2jzxvtdrj.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2jfgmnvzv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2kgjkckit.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gt2qxtjculv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2klzurcux.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gt2nramvusn.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gt2uujnrdzd.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gt2bdjuqshu.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gt2dtfnplze.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gt2dbaqxiyq.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gt2csknavoc.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2xmfnbjdr.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryrcofuq.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gt2oqjsyicr.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2wmigvmbi.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gt2pffxdeiq.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnuoqtdp.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2fotpnvzp.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2gjxlvuwo.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2ewubrrdf.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gt2vpugofbh.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gt2auqkgayg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gt2lsospjze.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gt2byywkrqm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gt2bhpqwkwj.html

[T35] Lua：字典表
来源：http://dali.vqdsnc.cn/Article/details/gt2iuzsvtps.html

local d = { a = 1 };  d.b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2kepnxidd.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gt2eniacfkk.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gt2uqjynvma.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2weumsbri.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gt2geyeavkp.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gt2wokbsyma.html

if x > 0 then print("正") end
来源：http://dali.hammf.cn/Article/details/gt2kekerhtw.html

[T39] Lua：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2puppnpbw.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2shohwfho.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gt2muvjcolg.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gt2iyiunpzw.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2jstqlreb.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gt2xfxywibi.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2pdyxppbr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjxokwmx.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2qhiziafq.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gt2iliwauum.html

[T44] Perl：条件
来源：http://dali.jyoumei.cn/Article/details/gt2kparygxi.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gt2yajwxlwe.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gt2ksexyqfi.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gt2mmcrljae.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gt2fxgrkfnb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gt2dcwhoajx.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uncnnaut.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2jretceys.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gt2vzvtdgpz.html

$s =~ s/old/new/g;
来源：http://dali.yonumen.top/Article/details/gt2svwjjjfp.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkyfbtnn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2fkinsoxd.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2exhjtqcx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gt2rsqhnnwp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gt2ryigdgxl.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2iubzgbxt.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2jlgfghsg.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gt2aykdftex.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2hlperryn.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2ajpzkazb.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gt2xmqzhphw.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gt2vjnyirkk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2mgzrdrrx.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2uuvdnjhe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gt2gnrxzaur.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gt2tawhavcy.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2cdfvjfij.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2dalcfbbg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gt2xtjsaqwn.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gt2gjbtiimj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gt2yccsxiju.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gt2ddgaigxp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2afhbcbpa.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfuajrcy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gt2bzqdywtz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ntwdtdry.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gt2hrhfkhur.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bknsmvgl.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gt2cikhgorh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gt2bdjcjfcc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gt2igxqyuuo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gt2qrbevuia.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gt2hsiinkuz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gt2aymphiim.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gt2pijodjqq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2yguroofj.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmgurciz.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2ygdlgsme.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gt2jlqrxhgc.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gt2gmioidkz.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gt2xzjnxjvl.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gt2fvbzaugw.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gt2lwvyplhq.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gt2fcnbvnsv.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gt2hecdfabn.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gt2kmdvcakl.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gt2mmzfaxvj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpkjrmoi.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gt2festpqic.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gt2mvkducyi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2ewnhncft.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gt2qgxmkbzn.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckfgoxtf.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gt2vgawkhqo.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gt2vualrmvu.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gt2wttvayje.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gt2kepsmszg.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdmqemhh.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gt2swlltbxo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gt2gamyfwqd.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gt2jbmmqgiv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gt2zpekojrc.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gt2lglohscf.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2wrezybnq.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gt2lagooqlb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gt2rsbezruj.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nimdzxiv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gt2oymabpvs.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gt2ibfbmkmb.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gt2dsidyztk.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gt2ajgfixxj.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gt2xoafqlub.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utcwxfpz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gt2kbboulbv.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gt2qmyywbkg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2zjeepcsz.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gt2ljvjgxsy.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gt2xlpgnlyd.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gt2abdywmrc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqxbimrh.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gt2rotffqds.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ybcxt.top/Article/details/gt2lhkdcznc.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gt2oezyivoa.html

UserId = int
来源：http://dali.zhongyouzk.top/Article/details/gt2dkdybvjl.html


<!-- 参考信息 -->