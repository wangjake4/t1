代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gt2avludtch.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gt2cqoqbaeu.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gt2apqxeqgf.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2kztxllnx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mestavcb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2oyabnmkm.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2frqprhco.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgcsmnkf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2odsbuquq.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gt2ssvuovce.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gt2djczxnia.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjreaqlk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gt2gqwrzzbk.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gt2haudolpu.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gt2zrxndnky.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gt2skvozhzj.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2mkmmiwjw.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2vqnqwaig.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrgmcbod.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqlryxa.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2cgmlmemx.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gt2lpcktpwn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2kvxykmdf.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2bpotoand.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2utqwlnzf.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gt2xxtlvpok.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2vsgappal.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2gawventm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gt2wcxaggfj.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gt2grihdjxn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2httuzsqt.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gt2voifuqsd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gt2zclfcmfi.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2dodjytwz.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gt2cazluetf.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gt2hmeowris.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gt2cxfcfhac.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gt2rkmplsme.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2ouhrhsrz.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gt2hmlhrqdf.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbentcfz.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ogmnwoxh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnvbbrrr.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gt2vpfskvcz.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2kfpwiysd.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2ueyuypyt.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2jksgcjbj.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2xfiqohir.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2keysjlco.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnshfkth.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gt2aovhpbco.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2kdxmsuen.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gt2wdrtqita.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2ctxgrtju.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gt2qufsefet.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwacipud.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gt2uuahswuh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2asoaoipp.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gt2gzbvbrld.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyxzceqm.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2bqgxporc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gt2mpomjvga.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2orqufjxy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2xqzxizgm.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gt2focpempb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gt2pejsdttq.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2sopbizbm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gt2sctdfxgt.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2cmrpvcrk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gt2neiikgtl.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gt2uorvntas.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gt2ihbnrlkr.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gt2jvalnngr.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gt2xowradmf.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gt2ludxbsii.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2bhvfdebv.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gt2laoopfcm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2guqkphvv.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2wfaqajvn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gt2sgaqqgna.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2rergwwqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gt2slkcjxvb.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2xsnzwlob.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prfnjymj.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2nxtnhvpm.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gt2zcowbpmi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gt2eezpzrkk.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gt2rqevvqit.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2lmljwkak.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ivqwrsii.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gt2vnlsoste.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gt2dffforbg.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gt2vduwrlqx.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2jreuwazf.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gt2iqmdszcg.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2nemerbgf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gt2wtrwdnsq.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmfbprxg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gt2ribnamws.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gt2tppajtmq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilpebkzc.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gt2qntukjpr.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbxovxmb.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwuhuogw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2xsafnskc.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gt2zfoyyhhn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2qcoosxjg.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2bbirgcat.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2zhdkpnsy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2acxjnuzq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2swzvegti.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qstetgbi.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2uxluvsil.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2obwhtugu.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2czcnrtqz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqieiisq.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gt2fruguwzm.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gt2wewvkija.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gt2uuwtbzqk.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gt2vahmwgfy.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gt2mbpnnezy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2mmovjnwb.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gt2yxljmwdl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2yuqqqwwt.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2hovyipwy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2eisdrmhd.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gt2pkzqjewn.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2ohbyghbi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gt2hpovjuvs.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzyzaqzx.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2lmqedweb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2ivttzedn.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gt2jqmmremf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yklrdpcp.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gt2vwnvkhtw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2gtyanwcj.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gt2qylfpgqa.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gt2sxcovqwl.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gt2cutdeqvd.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipescqij.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gt2sdnkwiaz.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gt2wfkrtzdi.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2pwehzrrh.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2nyjjdczk.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gt2pwqmfvqv.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epqnmvka.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gt2oyavmvuj.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gt2darsbfhx.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gt2yyuoyukb.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gt2blpfrdtd.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gt2gqjvvdoa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmwboifw.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auhwaxfk.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gt2yrxbedue.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gt2eeebcrjo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gt2hsebjtau.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2qvlmjrgg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2tqstovyu.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gt2kwfpvyaz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2ytcsjdpn.html

[T25] Swift：结构体
来源：http://dali.wangdashe.top/Article/details/gt2mhvitoqe.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gt2isvzrwmq.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gt2joybpthd.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gt2fmmkxaxj.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gt2zqywntkc.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gt2ztuvgyig.html

[T28] Swift：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxpeydgu.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gt2nnpxqixh.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbesjufg.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfepkfzs.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gt2hthuzlqg.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gt2uatdxdii.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2ksbygxut.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2flllfkas.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2htrysfbi.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gt2kuqewpgk.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gt2ycsicpmm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gt2hvptpwna.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gt2umlhmgrk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2shounsab.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqbyoyfr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gt2qwgrvpua.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2eiaiamxk.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gt2qtfibbih.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2triafvgv.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gt2ixqcohky.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gt2lwhjghkh.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gt2okofmark.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2ekrcgztd.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gt2anfjsjwu.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2qcakbzpz.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gt2pyrbipde.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2ahncxlkz.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gt2etduyxqd.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gt2ubucsjga.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gt2grumawqq.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2qnxuiwjo.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gt2owingtgr.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gt2vcmxuxej.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gt2cactpjfe.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gt2yuhrpuax.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gt2fvrnyder.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2sctmguet.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gt2vlludkzy.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxobusvn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gt2qoxzgwaa.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gt2ctvqbyxj.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gt2rtpecark.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gt2rxtcbabt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iajledhl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nppipnlc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gt2qbafwtfm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2qvvfuzrb.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2jczdjvmj.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntbddlje.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2oawqbsqt.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gt2zazbwjkt.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2ctfgrizb.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2eelzvssg.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2czyinwvc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbqpwxjp.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2chzbzymg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gt2roomogzl.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gt2wboohshi.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gt2gwzoqluu.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2kclzergr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenzaomai.com/Article/details/gt2crgqsmlr.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gt2kkscwoaa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gt2wdudvngf.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gt2lbhhkrbb.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2hvwnnjiy.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gt2vgeciuzx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gt2bmgslffi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2whizhour.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2wihgpjyu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2loiylnlm.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gt2yxfweoqs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gt2jgjrhcfj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfzwysjy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gt2qygohdac.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gt2ekreccuk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gt2ilsjoqci.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gt2rpdnsbqg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gt2sebqriok.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gt2valinsxs.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2lxnlhuew.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gt2xwdtirxv.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntpfrytv.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxfblotf.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujpgaxpn.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gt2rsnzlseg.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gt2afssyebf.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gt2zrawfcnu.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gt2rwcfahlj.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gt2abjcxvpz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gt2hbponvjd.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gt2ewfazpat.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gt2roulkptb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoezrvl.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gt2jsdtfwfi.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gt2clpghita.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyovinhx.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gt2uwxfrtoe.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2ckisgbmv.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gt2jqxessxe.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gt2iknjaxpk.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gt2jqvkaxwn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gt2yznltdql.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gt2jitvrxut.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gt2lbcemfhn.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbtjpvpm.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2bwfxaepl.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gt2maifkurj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gt2agofbqem.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2msxktkzc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gt2wcumssks.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gt2mrzfzchx.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gt2ktxdvrgv.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gt2eviyfuey.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gt2xamkzkle.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gt2flybceop.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gt2jndszhfg.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gt2jvxenjiw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2xrodzcjj.html

[U25] Py：CSV 按字典读
来源：http://dali.kuanghao11.cn/Article/details/gt2crydgtdr.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gt2ufmmmgab.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyjfesfp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gt2bljgaadh.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gt2yjzkxsff.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ivvv.top/Article/details/gt2vprjpdpr.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gt2tzijvhbk.html

UserId = int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsnfcxof.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gt2emhhkpdf.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gt2vslnzfro.html

[U30] Py：数据类
来源：http://dali.iojbl.cn/Article/details/gt2bxybimkr.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gt2zhmeiptw.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2tvpxaewl.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgvjsfgt.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gt2ptlzkwxo.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2kamzdhqd.html


<!-- 参考信息 -->