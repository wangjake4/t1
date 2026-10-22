代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gt2rduczcyi.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gt2kfdgzdqi.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2fjbfecus.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2zcfmztwl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2mogohogr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gt2syndyman.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2ntqdytfn.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2fnmgphqt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2byhaytdf.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gt2stsmsohs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gt2bkvkbkqd.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2smpklgvl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gt2eccbucsv.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzwwevcg.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gt2lcrwmucw.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2hvfmhwev.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2bkdfpwag.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2syejwvfh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gt2offgqqid.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2zmhfiiyb.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gt2zkknavli.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2niglxakh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2erfipicz.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gt2emejgjpj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2agafksuf.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2athfpmug.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2knqjzmdt.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2csmrrtjr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkuzocqd.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2tzissgki.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxnrlhvf.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gt2wsttrkzm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gt2kguuxgxs.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gt2dflobdtw.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wajxmfpy.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2itstbaub.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2tnrvqifm.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gt2llnyehsd.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2pbfpwuac.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gt2fazvyxst.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gt2uksegefl.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2isavrvvy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gt2ikkhxzyx.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gt2bgabtbav.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gt2mxlyriwj.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efpndcip.html

#endif
来源：http://dali.meibo888.top/Article/details/gt2npeaxobd.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2uymbvfoq.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2ntqgkryy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gt2gtsabgro.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbutmsxv.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfjtkven.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gt2gqcldvwg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gt2ckvintbm.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2jxwrmdhe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rbmpidep.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyncimql.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2wqtrfgzn.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2cnshnlmz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pujpczgs.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gt2gsxgcwss.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2plngykck.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygesatzh.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gt2yhxhmtha.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gt2cffneoko.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2ypafilzz.html

[S40] C++：查找元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnrwzdgy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvlfgswm.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gevdudgj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2xumpsirn.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2zqdxinki.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2nvcntrjs.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gt2ztnclazj.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gt2tsjvkczy.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhutgznk.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2wljqwyad.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxtafocx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2vxfkpatr.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gt2qlgkajkw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojvwatyd.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gt2zqmonrjx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gt2oxkowjgc.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2cylsoypa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2jdigtrur.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2kypuvedz.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujribyif.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gt2idhaeyyl.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gt2lulyllei.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2fbzryois.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2loqppcwo.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gt2ccnktujf.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtxlycnp.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gt2gspmencz.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gt2jgrkhlah.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2skehspyi.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gt2hytnnjot.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2agsvdtph.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gt2rnwuwtkv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2lepxxucg.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkftsybz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2kzhuwfyc.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gt2yxwjbxch.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2tfegelxg.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gt2rfdizzcv.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocgjgkes.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gt2hphrvmcn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gt2eycaizau.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2bmebpdbb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2lisspszd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2yjbdbljw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2awillsfm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpdxaxvk.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gt2nozqfzmb.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2jqcqqoaw.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gt2gqfhajqb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjrcxllp.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2kcbelfis.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2styjhjdb.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gt2qlflyzdl.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2mhkwwghh.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gt2kjjibkao.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gt2jwzkuxdp.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukotqdha.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2syczwksm.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gt2rbqkmwsh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gt2qcxyvkvv.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gt2skddclyg.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gt2naaydclx.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gt2bchelxbj.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gt2modjjjfj.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2yedricmu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gt2iluhrskt.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gt2ajlwaqnb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gt2kspllvhv.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gt2mzgbhvzc.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2xedwwhvt.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gt2mcrbkuvl.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gt2xjlhkdqd.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2msboclfp.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gogzpyzu.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gt2txpwgsxu.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2svmqxbvi.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2hlpsikpx.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eigjqwjx.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gt2lxsilyqx.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2alorqkbp.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2bmzwmtgp.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvnlzuad.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gt2nehfaubv.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gt2cfnsybyi.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2uqnwdmsx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gt2hswzwptx.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oefurcpy.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gt2oekqxhrz.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvqplfrc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gt2rlxpigyu.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gt2gbwthpzh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2xuwsmluj.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gt2cwruoeas.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2zkuzpogh.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gt2nhgbqhex.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gt2vshcwowi.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gt2ycnftvbt.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2rdogbklc.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2tuecnwvm.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gt2kngjfkvk.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2gjybgueu.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2vqsfosuf.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2eezbbssk.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gt2aurkptsj.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gt2tmfnnhtg.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gt2kdfertje.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2jbviiges.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2fdzpivpj.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2dphspsad.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2iignqxjb.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2ejhtmxxw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gt2qdpnoweu.html

[T34] Lua：遍历表
来源：http://dali.zhixingplan.top/Article/details/gt2sejmkieu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gt2uchmafpv.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gt2jjjrjkxc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2hdclquiy.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gt2dwiuopvq.html

function add(a, b) return a + b end
来源：http://dali.nanxuanxn.top/Article/details/gt2jvstkilq.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2sotfgmtv.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2uzubdovj.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gt2tqsdxywj.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjpahjfe.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2kltkcwpa.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efekyefm.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gt2lbkqntxm.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gt2qgtltxij.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozofijzp.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xknlcdii.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gt2xlnsgsob.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gt2esjroeam.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2xawaxwce.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzueosdz.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gt2rthciibc.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2cubdcrqf.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gt2zphzroxw.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2iudunavn.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gt2bkgzbiux.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxsakuaq.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2laycmqbt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gt2hrarzfys.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gt2wyndlzyp.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gt2tczmxmyi.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2fxbndjae.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2obrpghsv.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2cnkbkzis.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gt2ztwfusqg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gt2gskpxnjq.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2bqgztjcq.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsrfbrxr.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjbtbehg.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gt2toqarfgj.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqdttbez.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2hibbxtum.html

[T54] Scala：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2xxxbbnfv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gt2hzkjyqpv.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2popeuobb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gt2mgfwsgcb.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gt2kdiouiad.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2rtjqngmh.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2qsdghfli.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2fufloszc.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gt2ixbgjbkb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gt2mtpuajoo.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2fovynbbc.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2rqayifbd.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gt2guwexmxu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gt2lvrjqxrj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2urbbtqgj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gt2uyvfnler.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldnivkrc.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gt2uhlovtsf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gt2rlnyypdx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gt2vtyyqniw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gt2lenxgrxy.html

[U03] Py：加载 .env 配置
来源：http://dali.andypj.xyz/Article/details/gt2vnednyav.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2gblvquwv.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gt2crdpnekd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxljyega.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gt2fdcgpfqx.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2wetaiqnd.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gt2mwuduiyv.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmvlgnkr.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igvadxse.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnuznkur.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gt2gcxorfrt.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gt2xtctsoqi.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gt2zkyaswaz.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gt2efaxgavh.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gt2oznjmnqh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gt2qklpoiup.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gt2iihtzknc.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dseevysy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gt2ijeklqeu.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gt2assizyut.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwannzap.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gt2fhurfzbr.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gt2psaslqtt.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gt2uhuemcoq.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gt2ndsgslck.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdhoguov.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gt2gnvyuooq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gt2zfoxtjib.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpwlcvoq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gt2gckcnyti.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzafdjcl.html

pat = re.compile(r"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2zmauhgfr.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gt2oqikequq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gt2egurxqqr.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohmjtbgy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258.top/Article/details/gt2kxzfhquw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gt2fzhadsxv.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdfnnmor.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gt2kcbbdyqu.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gt2sbggljpm.html

[U23] Py：分块读取大文件
来源：http://dali.yangfankeji.com/Article/details/gt2egkiznjy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gt2pgzndyca.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gt2zrjhbbco.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2gcdniizr.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgzogzqn.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoegdxiv.html

[U26] Py：并发下载
来源：http://dali.hfpthk.cn/Article/details/gt2rgqgyrbg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gt2gqfyqdrf.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gt2jaaoecbi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gt2sycnttib.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gt2pdlofmxb.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gt2lbirxaws.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmanidam.html

@property 与 @x.setter 配合
来源：http://dali.aibaodan.cn/Article/details/gt2jgkgviup.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxpevoet.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gt2itadzyqf.html

[U31] Py：单测
来源：http://dali.zycfv.cn/Article/details/gt2srurwwnb.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gt2nhmzbxde.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gt2jactzebe.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gt2afipempi.html


<!-- 参考信息 -->