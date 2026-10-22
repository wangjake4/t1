代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbyaewhx.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gt2nrynbnpo.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gt2dcxnpytf.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2stjhgpbh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gt2opgxtgbh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2daqsgeah.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hobvnuai.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gt2bowvyetb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2mepkgpgo.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gt2zxzwcnpw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2ejcaflpr.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2qidiqfwd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gt2taqhbsxh.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gt2jwumgwhz.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gt2jprbebnj.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2wvgngbqx.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxhxxryy.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgtkgxvo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gt2xydfspzx.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2lrnlacje.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gt2rvlnxxuz.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gt2zqhyesxm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzyscrez.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcyxdqjw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2zbtwsepu.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2dhywzijz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gt2gcwbbvwi.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2gvwusogi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gt2gkixfiut.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gt2gntlhodo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gt2nqblpcpx.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gt2iynskgmn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gt2tbwhwbxf.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gt2gehbyboc.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gt2qcrzfogy.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gt2nyyqymls.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gt2roxizyzp.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2nprfifan.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2bcxgtpwd.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gt2soyopodg.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2dhguaioh.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfzybzyx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gt2agdermhw.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gt2nofpxxak.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqctdehj.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvqymusq.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2xusqcabd.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2suustixn.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gt2vvqvhwbd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2amqjwdrg.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gt2mnlymedp.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtnydldg.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqophepj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gt2nxvqpvhj.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2wnkgvfsj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gt2gzslnpqs.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gt2effrwuwk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2pujsykbp.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gt2vpjrvrhk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2oxnrztva.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gt2kpmjyplv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2jyqhopyl.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gt2aladkssr.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2fyjuzitq.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2errdafeh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2kufbjdty.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gt2qfahlqxs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gt2zuuhdfxq.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gt2lfmreabb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gt2ifvmoubw.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gt2qjkbipgj.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gt2cejvpnbf.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gt2xnspmhwu.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2aqeiomgy.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gt2rwfddhnm.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gt2raxqqtyh.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gt2umaefota.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gt2scyrfwrt.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gt2gfgrbkfx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rwqypzae.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2jnesohad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gt2lxfdqdnm.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfynrngh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gt2selyvgom.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2gofprmbw.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gt2kjwdtgaz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2umipybuh.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gt2pkgzgcnq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2mjitonhb.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2cwrurxoz.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2etnjwjyw.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytblgype.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gt2ulisrleh.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2cuflmcno.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gt2bupbfrxd.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gt2mcbwhaml.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gt2klyvifvu.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gt2miakqidd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfadntxz.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsanruza.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gt2lglvtbuj.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dskizmkz.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryrfbfhe.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2lypwfrcj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gt2lsaaystt.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gt2uiburdfv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gt2zwdfuhke.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2gipfontk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2bphgecxr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fqxuijkr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2lkbjgecg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2klbsyokd.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gt2izeuitbq.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zydlulzm.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gt2cihftjwf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2cmltgqvw.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2undkoesl.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2ifkoxihk.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msfyydcz.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2fpjwmxqs.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lumzbhlj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gt2jznmwwjn.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2kjfvxyws.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2uaegbzti.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2wnbaxqzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2vgozutoc.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2waqhrmjl.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2vjjobynn.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gt2hupcnicx.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gt2nnnezmfa.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkiyoqxn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gt2rnbrjold.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gt2qydntbqh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2ixfliyld.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2vqbtimdd.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2rxedvbbg.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffgfubit.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gt2vmyrcbjv.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gt2rjwxsmdy.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2wkppsjyo.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gt2hosgclli.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gt2geubaukv.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2yyxubfuw.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2psuhhqti.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2qesxgtgs.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2aqlemzdg.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2nwckdugh.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gt2hqekyjyc.html

[T19] Swift：可选绑定
来源：http://dali.yj20258888.top/Article/details/gt2rqrqsisv.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gt2hgmebvbk.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2nzmbthoh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gt2pfbhnfno.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2tvvnpxta.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gt2kpqctweo.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gt2fvnotffo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stfrzgwg.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2cjncannd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2bfrmvbto.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gt2lgvlwpcl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zedzyten.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gt2dcmdazsa.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bexgjvqa.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gt2bwvgahtx.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gt2guotqhle.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnjwkhyd.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gt2fkyitjhl.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvsvdsjt.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gt2mybvupqh.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2iuifjofo.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gt2wsvezggt.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gt2zhakxbky.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gt2lekiszpg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbkahak.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2phrebhyi.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gt2arwiguhg.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gt2xqlrjmah.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gt2faaipnzb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gt2timzxwss.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gt2wxgzihcj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gt2fotmvkar.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gt2bxfpebbb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2jetbacwd.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gt2pjsduone.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gt2swrdsira.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2gsogtyha.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjnxvmst.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2gjwlebav.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2iihshqoh.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2wvipqesl.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2xnuwimif.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gt2sfpurcxa.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gt2jtodelkn.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gt2uvzbqbsb.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gt2mridsgew.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gt2gmtmwick.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbvshacw.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2vrxgwpwo.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gt2bzijbcdp.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gt2rqixiopb.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gt2ruqatrkv.html

[T45] Perl：数组遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2izobufru.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gt2gnynmkmf.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gt2tfhktpgq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ojdzjmaf.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gt2kokvgacs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2voklxeol.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2eajyhlao.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gt2eibovmqr.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gt2cepsodam.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nssftiwl.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2tpilmuvn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gt2yukdbllt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gt2eanaxyre.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gt2xabdefgh.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2bwaiaqxq.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gt2tlfvrjpa.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2hsukukat.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2phcjdffi.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2bnoxsxhz.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2ydscgsgi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gt2sgdjjxau.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2ikiyusla.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gt2ynavhlsw.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gt2ibimdneh.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gt2avzorjrk.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2zxytwnyy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjfzmayj.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gt2lkbbzvhw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2xszjvnit.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gt2lgezngtx.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2lbzwwvvx.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gt2gdwxzimo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gt2flwsxcyn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2fvwvzivk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2yfuixzdm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dporlgvt.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gt2ibgkeday.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gt2ubqlwxii.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gt2zkgojmkt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puqoztmb.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gt2opgwpzkn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gt2nlcxfuee.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvxnefox.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2foftnnfq.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzbbhulr.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2wyisbtzn.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gt2wrklqtwt.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gt2foxkrzrd.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gt2xprqggrv.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gt2helwxxgk.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gt2onghwfys.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gt2fjkpsvfa.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gt2znskzynq.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gt2bgtlxzkj.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gt2thynewrv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2bpnrcqpe.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2jufknpmj.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2orcpgcyf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenlongwang.top/Article/details/gt2qajehrpy.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gt2wadoiavo.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gt2kgjlvxdb.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gt2xzwmmguw.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iggiqjmf.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gt2ufppjrfr.html

[U15] Py：高精度计时
来源：http://dali.316326.xyz/Article/details/gt2jkflhnsb.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gt2kniejkwx.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llhctzee.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gt2jtptcoli.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gt2abssicsz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gt2zcbdpgog.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gt2hmmqgzep.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2ljvqfkdq.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gt2dzxvkmtk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shuidangran.top/Article/details/gt2jxalnxwg.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gt2agxvqlup.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gt2svnhutsj.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqnwcgdr.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gt2swkbrebp.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gt2gqqprefq.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gt2fsyoehrg.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gt2luctaqhk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gt2bbudypcd.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2spknjygf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2yhsszjzv.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gt2ynvfrzqn.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gt2ltuwaeeu.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzuzljos.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gt2lroyjilm.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gt2uhrocvvo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tixtvpql.html

[U28] Py：类型别名
来源：http://dali.hywenlv.cn/Article/details/gt2xiqknqtj.html

UserId = int
来源：http://dali.zhoulong.xyz/Article/details/gt2izposidh.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gt2cikgqhqs.html

@property 与 @x.setter 配合
来源：http://dali.tian-w.cn/Article/details/gt2voqwzwkq.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gt2bdbnkqjg.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gt2exdbzfek.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gt2tdmdtpiv.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gt2yobmxbzt.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gt2ghgelqou.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gt2citslxeb.html


<!-- 参考信息 -->