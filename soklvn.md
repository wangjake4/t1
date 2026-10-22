代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gt2nyxnglar.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gt2ttxaljax.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gt2roqunewc.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2gcttepux.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2mrkvsiel.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2iiuxxjbp.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gt2rwjmxldp.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gt2loviwvsg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gt2cirlymnh.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gt2yehzadcs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gt2pikmhxhe.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gt2qtwiqirt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2pcvjclyg.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gt2gpleyfkw.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gt2uvtgdlcm.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2zyeiqtyq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gt2bdqvafsf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2fcangwmc.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqtutlzg.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gt2khnrerre.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hafdoijn.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2okxgeeps.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gt2bmrgasdl.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gt2bpugycyh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gt2bgrlukqk.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gt2vnhqgtod.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gt2uxucgupe.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gt2wpwpvzvf.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gt2gokjscsr.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2wgozbevq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gt2wxzwsgpj.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gt2mbddsgfd.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gt2iabztvke.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2dogjjiem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2futwvfud.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gt2cjlgmiff.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnyfxxci.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gt2unxavsor.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2fxenuber.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2sszqromr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gt2yxoxbfzw.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gt2lkncnlyt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gt2gifsnvav.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gt2rfmseqgd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gt2uowvtxes.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2uoajdjfa.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gasjfdqh.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gt2baltvgvs.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gt2cgtxthbm.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gt2stfzozfa.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2znhsgnrk.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gt2afqpztfw.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2jsutenhv.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2edhktjfq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gt2xioacqcg.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2bdiaacbo.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2xxjmipfu.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2tcazlojr.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gt2njcgjphd.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2bwalspei.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tchwonql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gt2jnaugjnc.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gt2gowqpmcp.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gt2vrrlpnwf.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2pibtqran.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gt2zpbyepum.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gt2nsueqorq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gt2vxjvgytc.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2jxbqsfaa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2xxxcmnji.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gt2ydwjiqae.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2jtkynrmj.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gt2nxvfjbax.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gt2fqtadsjy.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gt2rardqnel.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2yqjlijzo.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2tqepuukm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gt2ramxbvso.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2bfkeffwh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2iuvzsqbs.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gt2omzfnfwo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gt2hqitepbw.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gt2xnfyumys.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gt2pxwtwyor.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shqcflsk.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gt2lnvnoxxl.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gt2bjfbehhu.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2azniulba.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gt2zlotoajs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2knrwadvh.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gt2oaziufzo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gt2aszpjixp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2gsbsomnf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gt2pmlhzcse.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2vimvnevj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gt2katkrabt.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fytrlddm.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2ljqykuiy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2bgvbhnki.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gt2huntybwa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2rqrlxrha.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gt2fuevpkgk.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2vrljmkbk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnjwjaxb.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gt2vpbrnulj.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gt2nqckqkja.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gt2kinmmkzm.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gt2volcdvzr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2crwznyap.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2asxuehoz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2ojpogwcf.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gt2ckopbhar.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gt2ebntmlgj.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gt2clxftrge.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdwnseut.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2rhdurokv.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2blohmkjf.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzkqfjzm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhxhzlfd.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2ajzyxaho.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2jbtmtupa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2slichbnl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2usqsusjz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2nazvlfwa.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2emmfxqka.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wperximh.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gt2jbugvseb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gt2rlvsjful.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gt2vgukrkmc.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2nkxmfkmk.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gt2kvsclgvj.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gt2laebnclk.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gt2uoxzcyfc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gt2tsxxfbjt.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2wntdjtgc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2nyuglyiz.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2nocldylp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2witqrbkb.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gt2ubclazyl.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gt2acepxgui.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gt2cjewdlzw.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gt2lbtgbaon.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2oaknbaqy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gt2zqdynhzu.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2uwdbpwru.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gt2xaxkgbpy.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gt2sibmoxtz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2puwulqxb.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gt2hyklvnee.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gt2tsqeowbe.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gt2mzlboqde.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2pcsajbck.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gt2tojlmipf.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2qjckzxky.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2jhfzzwwu.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2bcolvfoq.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gt2hgrpouve.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnnuxeox.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2iokyzpyh.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2lzqdratw.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gt2cqvblhks.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2mxbxejnf.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gt2mvjdpmaw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gt2sefofrfy.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gt2prsxvors.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gt2qkraotdh.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gt2ehewadqu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gt2cpiwcnph.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gt2bcpqvjvd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2vmegpcyv.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gt2heavdyhc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcervvrh.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gt2opwheqgl.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gt2bmeuzcmp.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gt2timmdvkv.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2tlvqzpgj.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gt2kqjvhiso.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2ojwbhaoj.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2kjcpouts.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gt2wrteuqdx.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gt2jcdnkpyr.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gt2ycegegpl.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcvtusby.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2botrrbuu.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2ozbldjwq.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2ocwnotur.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gt2irizfqsa.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2slsukwqi.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2yrzkvzhg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gt2imfaitfz.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2wkfxuqek.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsksofbl.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gt2asrxkjbu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gt2rgbzjzit.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gt2uvmvzfgq.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gt2xkomwmds.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2onsvlvop.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gt2teuzpypg.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gt2gnolextw.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gt2keggbblg.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2arnsbbvz.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2onztlggy.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agimflaw.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gt2anznsfuo.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2eitdpjqa.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gt2tcfqqmoy.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gt2geayqydc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gt2dxehtdig.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2qxnuzyvx.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gt2lypljfuu.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2caecwyrc.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gt2roqappcf.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gt2oqdbcvyk.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gt2ictskbqr.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gt2hbmyabvw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gt2aigfacml.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkwkiujz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gt2zbjfbnyd.html

[T48] Perl：正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2jpiseaqv.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdpjsryo.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqzdlibo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2wcsnzwxi.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2gpmvtsxr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2uuwhsmuo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ncmzctcg.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2shmrypjp.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2nawumriw.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gt2iixtgenj.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzuyxzkx.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfwqckfa.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gt2jnglhxrg.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2bqvwmbyj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gt2kahmjilt.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gt2lfcuoswo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gt2semkviar.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gt2ongpzexh.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gt2wzclvdqm.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2ymqoinvw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfphxtkn.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2droruhyf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gt2yobbjdqk.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gt2jatmzglz.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2oraezjwt.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gt2ccraockj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gt2eummgqxh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2csucbvzd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gt2pymxezda.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2eoqqchcx.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gt2ryrwomek.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuxming.cn/Article/details/gt2lqolfdey.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gt2klvrnlej.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gt2jivwilrd.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gt2ploqiblr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gt2vtgrmgdy.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gt2mzfpahqp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gt2rvzwxjtm.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gt2mrnkcttt.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2cqllkflq.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2ngrvnvvh.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gt2sourrmpd.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gt2iqxroaok.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gt2qhgjwjke.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gt2amgmpqjv.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gt2udekpeep.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gt2efsqfxvv.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfbhkjiw.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gt2vjqdsjfz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2ihkwppdh.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwgjpsgo.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2vbmbjyjk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctwzxwqy.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gt2pvxkdlpg.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gt2xqvmncoa.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gt2zidxgdnh.html

[U14] Py：分组收集到列表
来源：http://dali.yangfankeji.com/Article/details/gt2dtrkizsa.html

defaultdict(list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhntdvck.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gt2pdopbshd.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gt2alqpjcjh.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gt2kphzsegg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gt2uibrhudf.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gt2esjzlcmh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gt2tqdrxhji.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gt2tfckkgst.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gt2agihgoeu.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gt2nobwpwuy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpsuofqf.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gt2bkhmihia.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shuidangran.top/Article/details/gt2cievhkst.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gt2bmrqdsuc.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gt2ferynkcw.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gt2cmsyclgf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2liiabbmm.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gt2bdviycaq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywzzdiay.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmnmeqrf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2plyniipi.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gt2mcdzuruk.html

csv.DictReader(f)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byfdavtj.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gt2wcthdgef.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gt2ppqhmaat.html


<!-- 参考信息 -->