代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gt2bxfgxuyc.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2lbdxggqw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kngushkl.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gt2cxkblsjl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gt2jaqtxzbn.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdpyfjqv.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2hqortpmv.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2hrniqilx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2ncbvknej.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2yxzaqjkg.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2hrpubkmu.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2zlmmuxkq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gt2xhwicjsq.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2zhpvgsrj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2blujaaoe.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2flndnwep.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gt2plojjloy.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gt2xmgktcao.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2dizteyae.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gt2quuadszd.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gt2rukgrffb.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2qlhhlxqe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gt2bpabqwyx.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2ltjnwxzs.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gt2oikgvgyw.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gt2vxvbabum.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2pozrgpps.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gt2qgansiyo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2ekbieagd.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbymsszj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2gvndwkmr.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gt2hkakfzmg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gt2mmnhdall.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gt2fwztvqwl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dscfkvpw.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gt2wroxbwox.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gt2wntrzgas.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gt2jkmimzol.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2jmcioefu.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzmuczoo.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gt2hrumvedl.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gt2twemghto.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2jzrsyxxr.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gt2epdwjjhg.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gt2kicxlccz.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gt2irvyhjdg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgfxbhyh.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2xkjofujs.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2ynybwqmw.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gt2edjabmfl.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gt2lxovimdt.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2eblysgmo.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gt2oemvcdpd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gt2mtjrriif.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2azhsdytm.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gt2zzdpurhy.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2qnrjbrfs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2flnhqrwe.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gt2cbcwbscv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gt2buifxnmw.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gt2sxyppgtz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2pyxnxunz.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2sklhkqkz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2ustlxyho.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gt2xgpittbx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gt2awsfcwlm.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gt2bbyvlpnl.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2tthzjiqt.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gt2gixwpsbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gt2tmxapoad.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gt2ssleomgs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2kacaofsh.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsvbauzu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdqbujm.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gt2wjnqlahq.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gt2zwvnfgal.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2bglgtzhb.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gt2qihaenzy.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gt2jddknjgo.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gt2hivcxuon.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gt2fvtzqpbw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gt2czqspozt.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gt2rssapnnk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gt2bopyyuev.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gt2aesojycv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gt2hewpyooz.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2aopbsezj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2lgdhubfj.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gt2ahkzctxp.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gt2bhiuxyvy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gt2mrtmjubp.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2gruigdok.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2qntxzcqc.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2hcrhgonn.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tydccrpv.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gt2pqvcjcud.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2fhmwegep.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gt2wfmmxqlx.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2pbzpalje.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqnroiat.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2mytfnllz.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2slitjgmg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ythgfyjw.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2xhvsrzaf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gt2nxqrvuke.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gt2unphnfnw.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2gneekyxs.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2ukgcinzc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2uzuiozkd.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2hloospte.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gt2kvnfamvs.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gt2odnxdwip.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2wyhzikjp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ukbpytqp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2idjpflen.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2reueajsw.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2iodiqsel.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2oifxyvou.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmddebdb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gt2qhhksfyn.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmjtrnao.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbkxbysl.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gt2fdhtxgjz.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gt2fqbklico.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gt2yjvrhtai.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2jlsvjoll.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2dtgxsyid.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2rkjgxxpm.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2vpmgdijo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2qzwhcehh.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2zwmftsux.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2sltaiahl.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gt2vonnlxft.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2vhuzpgke.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2pzipgkyf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abszdosi.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gt2zfdxjdjn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gt2eghznfxi.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gt2cfgfooxw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2ruttxobj.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdavjcic.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gt2pkrhizcp.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gt2nbqqoick.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzhqiyhz.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2wioootnh.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2xehnqoof.html

[T16] Swift：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2ulhbuwtl.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2xwefsfbs.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzipqumz.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2szikzjmh.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2nqtpmdkf.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gt2lmoqrqpy.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gt2zrgblaqa.html

if let n = opt { print(n) }
来源：http://dali.sysykeji.top/Article/details/gt2kspaypfk.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nagxueva.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2tijgkkah.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gt2waqokfrj.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eseiykic.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gt2nzcwtnmw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gt2mbpspuay.html

[T23] Swift：函数
来源：http://dali.meibo888.top/Article/details/gt2vmbnadxq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gt2hxqycbmm.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gt2ebzqhprk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2vcggyzrs.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gt2qrircxhp.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gt2bktrzvpb.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2gyadjdzp.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gt2moqypoij.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gt2waewddec.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gt2mnxtkqqc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvdlwnz.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gt2bliiffgk.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gt2bsalamba.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2epfhauzl.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gt2agxechdz.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gt2zcwkuknk.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2vxulexgk.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2irccvckn.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gt2furokrkc.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gt2ktbempqs.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gt2illkcwqb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gt2ktjglqbf.html

[T34] Lua：遍历表
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnyfzrni.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gt2lpeofcvb.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gt2rnvfrmow.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aizwys.cn/Article/details/gt2mmgjssrl.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gt2qrcimxkz.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gt2izcckdgl.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2jfsdxsxf.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gt2aftfibui.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2sgrtqoub.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gt2jzbtaoly.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2liqbrabv.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gt2iwmuqbyv.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gt2gczcktss.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svignieu.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gt2cphzhqdi.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gt2jviwuwvh.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gt2hgbqxrkq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gt2ledjcuxq.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2xqcjuiaa.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gt2tteryxms.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gt2kebicpad.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gt2ehpmwekz.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gt2yoawobyt.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gt2ecmfkuni.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gt2krkqyyhv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjbzfztg.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gt2hjqmzfmw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gt2inlupgfq.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2tzvqqhid.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gt2toyiatev.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2fwnuuitk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2oapoajyf.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2bbpkzfik.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gt2aulgbwdp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gt2udspbhcx.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2youpllrf.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2oavetwik.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gt2eejuowjv.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gt2symnxrfq.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2tufgegkk.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gt2ggcjieat.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2tvdgscbv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2fzhqzwkm.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2bmpgyjmj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjsivubw.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gt2bjpieyng.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gt2ottmtaxt.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2jiifbtzz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvvxybmi.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gt2qwywnyct.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gt2bnicazwu.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gt2xparkcvp.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gt2koahfdup.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gt2tsgegfdf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gt2pdotyswn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2bodnteob.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2rudxfctz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2yetcikpz.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2ufsgbllw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvaihwjr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dslcnfev.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2izxvxtci.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gt2bsalcqds.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gt2nwqbkqrx.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2ozgmonwc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gt2rxslergo.html

[U05] Py：列表去重且保序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cowlcvbn.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubwslhnu.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gt2ljgsivub.html

{**a, **b}
来源：http://dali.shzxlz.cn/Article/details/gt2qjrtpkwq.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gt2cjoiduiv.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pydflgrx.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gt2wlcilril.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gt2jcbetewu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gt2trvyzpvh.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gt2rqcvdjor.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gt2gteunucs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gt2unfvbrgt.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2acdfdvlx.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gt2qllqpntg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.haohaochexian.top/Article/details/gt2uabmxrow.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2aqmijcme.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gt2encwoctl.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gt2masehsio.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gt2ziqoqyff.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gt2ppefqimv.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gt2ttumzjkl.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gt2dxyqjmls.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gt2ndmkrkfz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gt2hspdbyos.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gt2ozyveong.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gt2lqiwyotf.html

[U18] Py：预编译正则
来源：http://dali.daxiang520.top/Article/details/gt2kvlmlkcb.html

pat = re.compile(r"\d+")
来源：http://dali.cashguo.top/Article/details/gt2puarizbq.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gt2navllrdk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gt2akpedrbs.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gt2unytuabb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gt2bggycszd.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gt2zzopwxic.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gt2llqdtffm.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gt2rsojkima.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvzfnjwd.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gt2lotgxkfc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gt2zelsartg.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gt2jufbnktw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2ktibsmhq.html

[U25] Py：CSV 按字典读
来源：http://dali.daxiang520.top/Article/details/gt2sfdyodsf.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofvucfow.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypljfzwv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gt2rhxqysjo.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gt2lqaisdkd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gt2ksojgduy.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2xfbudtop.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gt2saolxqsv.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gt2ldhfmqne.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gt2cggqimuy.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teocqnxt.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jicbfavy.html


<!-- 参考信息 -->