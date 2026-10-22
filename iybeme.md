代发 wailian999

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gt2hgtutxyh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kjwzotwg.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2ykkbglpz.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gt2vktsbrva.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gt2jveupyte.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2jkdejjsv.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gt2ytrwyfem.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkzrfavb.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2mwkoygtd.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gt2sljnyqim.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2jjgjfjax.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2jrjrxxgi.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2cmtcixxd.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2exscjlgd.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gt2xdjmouuc.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sebbljdj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2qdvtrryn.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gt2pfbxyugb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gt2jwzogjkf.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gt2bhvkkymd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2ltehuper.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilfmhvgk.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gt2rnvjmhyk.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2lgwpsmpl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gt2bgnxjgyh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gt2kavrstrw.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2konltdbc.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2xxniwqvz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2vexfmvqc.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gt2bjlfnyjz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gt2xccsxxev.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2sevtqjhb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gt2ezrbzwaj.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gt2yeixuxxl.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gt2rertluwt.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2szeomptn.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2tzynayku.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2jotvuflm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gt2ldbbfvxi.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2jjxdldze.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gt2bxnrxink.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2sncfefga.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2uoplkndl.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdeuyhus.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2xuvujgqw.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gt2xelkuexb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gt2rnwuwuzw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kncjhaok.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2ipqmfxtn.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlwajdcg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqbwuqim.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gt2qagdbbkf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2omxjlkuz.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2toruzzfc.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gt2vcuwaqyf.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gt2vcbvvrub.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gt2kimqeflw.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gt2ofpboasa.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2facqrxog.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2sljcuqmw.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2zvmnsili.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2enfotngg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gt2ruhprxrg.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyrdmkkw.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gt2xseowxlo.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2rpicrjom.html

#endif
来源：http://dali.hnqzz.top/Article/details/gt2atumfhft.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2hmbbwjcz.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2zuobznxs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2ndwkrnor.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gt2kvlggzfm.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2nnltihkb.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gt2xtgvjdkq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gt2nlgwynik.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gt2sbpxvvto.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gt2esqyljad.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gt2cryldhny.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2sbluzgxi.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gt2kkyuwiyp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahiaqopo.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kaetytpb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2aqusirsa.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2zrgnxvmb.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkvsylyq.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gt2ivwheyzb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gt2fjujuyeb.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2hswuynpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2itkhaaux.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2kphyvrtd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gt2kinapuyk.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gt2qjuxumjl.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gt2apdcxjgd.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gt2rfrgyuvs.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gt2knnvsaab.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gt2bjnugejv.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gt2ngkirkav.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gt2fvnqlisl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gt2qhhyvtxn.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gt2tmtpiagn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pjtnkwig.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gt2davxazdc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gt2gelgutmt.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2kiesmbrd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gt2ninrwpvi.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2scxakimg.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gt2lgyualpn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gt2iugajppv.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2ibhcdsaf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2exuiptqt.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2hoxaxndo.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gt2tprlvwsv.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2ahvlcllq.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gt2njquoytw.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gt2ahkppjzn.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gt2akkdnzsf.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gt2wgtysimj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2ghqsjfdl.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgmzsduw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gt2uucpyvpf.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2jarzvtgh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jibtjenm.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gt2saryykdi.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2niourhas.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2akuykkws.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2vpssfezc.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gt2xuemcphf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2sdtannhd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2ogsjeilt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2nhzwpgwq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2iaswshnr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2ospxvqyg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2bgfoonil.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2wyvqvgdo.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2carmvcfp.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klunrmnv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gt2qmlqunzk.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2zlxbyyjb.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcdjwdwg.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gt2jnyhdzoy.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gt2npiwwnir.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2fxsxqryf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gt2djwgubrg.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2keoqjhuf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2wvlmeqzv.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2xknhyywa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2dutjxgxv.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2byeogqhn.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gt2kenmbyql.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gt2zzonhlcd.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gt2hcrecoxh.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gt2qpksougn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gt2fddoexyz.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gt2yrpburyn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoyfcge.html

[T12] Kotlin：解构声明
来源：http://dali.gotoacloud.top/Article/details/gt2oairoblt.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2wkaoaona.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2erosujud.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gt2waqzyxmg.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2epizkgsl.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2esyybixd.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gt2aumdpoqa.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gt2vscbzuxd.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gt2bsqxkzgl.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2qqnhmlsa.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2ivpyckuk.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybgnflmg.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2bmkfbtfx.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2fewtbutd.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gt2cfgvtesb.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gt2rsbfiyel.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2jcdzbwwg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2edkeifjj.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gt2rtwvjazh.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gt2okootbgz.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gt2rbxfhdqt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gt2mrgahcfd.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gt2ujfsqruu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gt2mezvibdv.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gt2iizjdldr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2caxmupgs.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2wxfqhigx.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gt2esjkeqep.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2sblmwcan.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2ckcleuph.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gt2stcuornk.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gt2hhubwmpx.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2eepsuuma.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gt2pbtmcstd.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhfcqdeu.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gt2pakqtcwj.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2btlucelr.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gt2mzgbtuyh.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2keytdkgf.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2sjirqrik.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gt2tgzgqvku.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2qexttygc.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gt2xvuqpqia.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gt2capgxcgb.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gt2bvkcbkur.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gt2wuzeykwf.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gt2chlagmmd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gt2xkzexuxz.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2aujmdbln.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gt2llrfeozl.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2muatagjo.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gt2uddbixal.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gt2gezghlju.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gt2xjoqajjg.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2igbavbwp.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gt2qsaufrbo.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gt2zdvshhrq.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2rpzccdlo.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gt2mtyakgpn.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gt2hfvrpgvr.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2ctlpuwlh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gt2lwzuxbwk.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2uisiwdyk.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gt2rdpkpurt.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gt2ugbjftpq.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2gytqmjpe.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gt2sfzxpvsp.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gt2mjwilygp.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gt2xdzgibka.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gt2noamkmeq.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gt2nalyzpfw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gt2zzljycon.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gt2bsjjqycc.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gt2iofvpouo.html

[T49] Perl：函数
来源：http://dali.tian-w.cn/Article/details/gt2sejwrhbd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2latcgjli.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axwddlfs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gt2znskearp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gt2vzqqjkco.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhoimiyf.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2wgpgdivl.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gt2mjqwbkmz.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gt2aguwswpw.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2fxbwsbhh.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2wjvruihp.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2fdivpkhc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2ajyhfhre.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2arpttfvy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gt2ymhrezwq.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gt2lhbusasa.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gt2ohacaxwe.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2mlujbpqt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sxryk.cn/Article/details/gt2srdbixcw.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gt2nnugmmsp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gt2hwkapelo.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2bescjexg.html

for (i <- 1 to 10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2ivxulwmk.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gt2oeckquwk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gt2xxmvxhfh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esmerehw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gt2vbvwjcnt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fcdfrfkp.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2fqeasdph.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gt2trxuqduj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2jqkkrmcf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpffledh.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2kjzthsld.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gt2voffbhef.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2cdalrgyu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gt2azsbeqyk.html

[U05] Py：列表去重且保序
来源：http://dali.hnxiangtu.top/Article/details/gt2lcaulnos.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2qknhqres.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gt2fqskzrqs.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gt2qbezlmjd.html

[U07] Py：反转字典键值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssjmgmew.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gt2okqeogdf.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gt2aydxlqqj.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gt2gnbkqoyi.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gt2sxjjmsek.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gt2fhlqqiwq.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gt2mkzdduhu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gt2llmrxknk.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gt2kqtxgxgf.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gt2lnnnfkza.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gt2xtjfzdee.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gt2anhxsqwk.html

[U13] Py：固定长度队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2tinznfqu.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gt2nsoitgsk.html

[U14] Py：分组收集到列表
来源：http://dali.mhx1999.top/Article/details/gt2fespyjuz.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqjdxnmf.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mszrpqhq.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gt2bigzyesw.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gt2hkljgzwy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqprgpxh.html

[U17] Py：初始化日志
来源：http://dali.nwbrower.top/Article/details/gt2gkivekzz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gt2vjwoqxqv.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gt2idsizemn.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2djcfbzzm.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gt2efoqrcwm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvujiiee.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2yimabybm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gt2qlvommtw.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gt2dxtqgzqq.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gt2ggyqywqg.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbucrevs.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gt2exdirvrj.html


<!-- 参考信息 -->