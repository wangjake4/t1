代发 wailian999

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gt2flhtbvhr.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2lzljbfmd.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2jjxspsqv.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gt2ndimzrhv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gt2waelhsuz.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gt2eqnmjzut.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gt2fhckuuhl.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gt2oosfcdjo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gt2bpbpkqzh.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtqeopjn.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2amjlqmvw.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2lkjrwyxr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gt2wjtkajvq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2eeyxykyu.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2wlcmqaqp.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gt2uoiravqj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eniyihml.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gt2pkwmcwwf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gt2ccaycceg.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gt2krghbhsl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gt2ymaphbpd.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gt2ddzcxsct.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gt2jzpcvqjh.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gt2xashiwlo.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gt2fdibjbqp.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2xlirjhpc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gt2plkkbsfd.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2bxqsqpwg.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gt2kiqwpcbs.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2wiuszvad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2dbmjclbg.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gt2fgftbrri.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2xgrrvrbc.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gt2dlqepzdh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gt2melvevpo.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gt2zhtzwgmh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2txiumzuh.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gt2ithsgwnz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2jfyjlmsh.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gt2elaiepng.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2mvioypbx.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2sywmgcyp.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2bjcrnnvh.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2wuvaqooh.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyalwfce.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2rglendzw.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rknadddn.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqwkbtsn.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhiagswn.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gt2genidnpk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gt2klupkyfm.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2iyjklspt.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2gtbdpwmf.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gt2dzjmmmjc.html

#endif
来源：http://dali.shuidangran.top/Article/details/gt2ohvjlwzo.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2vrwsusbc.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gt2lzssrjtq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hynfzcfk.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2dypbtpth.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gt2shmsaefr.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gt2yrjtpdxg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2semfmrvd.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gt2cnqhpdly.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpcthoji.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldwmqrwf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2vlnetzjv.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gt2ufxnewoq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2rutyyuhi.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gt2iakjehpi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2ukttjfsn.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2beijjanv.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2mwzhtxfo.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gt2jdsatwpd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gt2zzgsmdiq.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gt2ipxxkltx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gt2dndfvbhb.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gt2bkidlmmy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvkylid.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gt2tepmlsbq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2nxxeheyo.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2jxmzqafi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gt2urqupusc.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gt2xpphpdym.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qakaeuix.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gt2dgpgzepi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2nhetmfed.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gt2cjbbrjkd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nmfrwmnv.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gt2afmigmsc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gt2irwrbtry.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2ztecslua.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gt2sxfxttze.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2zlhppsmo.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gt2ythjynan.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2fcazfsni.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gt2ufgneicp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2oruejlyr.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgfxmpsd.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2xvdfehwj.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gt2pponuqmp.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gt2dylyuppt.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2wlndwcqt.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gt2blerdqbd.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2jearemhv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2lzayecoe.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsecsagm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gt2icghdoao.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2kxjjtskm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gt2dwwavfwp.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gt2qujyifyf.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gt2ejtzdxwk.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgdrgkio.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gt2uoqtvcsx.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gt2kstatsid.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gt2kamfydht.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gt2ddwhkjrs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2csujbqwc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hkupqsco.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2bimapelf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ydswsukh.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2waqarhfb.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2dtkvzemx.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gt2dcntkpqx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gt2prfvuxvw.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gt2tcnfijfb.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2xlypzgsz.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gt2fwjkqxhf.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2vlwvcimh.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2rpwdjvid.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gt2iiwhiuwr.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gt2bvxazocu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2evyhstug.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2twxgzdwv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2wkzqkpph.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gt2swldcvus.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2flrtvgcv.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxoaocqg.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gt2wktbzzvs.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pugayqof.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2tfhzknbj.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gt2twslnmah.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gt2uvbokcxy.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnvpzoiw.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2kjfiqdss.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gt2svrmforw.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gt2yeplpkpk.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgaodcug.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2neldjscd.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2ldgobgek.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gt2xlbmujac.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2jtibbtgg.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2lcyydspq.html

[T17] Swift：变量与常量
来源：http://dali.svipenyu.cn/Article/details/gt2uaaebela.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gt2ghijkday.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2jwyetffr.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gt2phafejte.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gt2sqrfxhui.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2sqttwddy.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gt2kpgbbrzo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gt2aoxdvual.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gt2jpfjwbyj.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gt2pwgofxzo.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfxvales.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gt2uravuhlc.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2ryisygrw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gt2isevjfxf.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2gylsrjxx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2hyzmeqae.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gt2ldxxddrk.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gt2ysmmjlbt.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejgenuvy.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gt2braixosg.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2fnxetopr.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gt2dwooqmrx.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gt2mzibspba.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gt2ucmfuznf.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gt2mdcszzro.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gt2eajfbbos.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gt2kyaxskfa.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gt2eqbpnnzy.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2jofifigk.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2yghidfiz.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfcqzudy.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2roszifjf.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gt2jcmrhhkc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gt2wqjikidg.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gt2nugsnqzs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gt2mrcktpxb.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gt2ezlxfpsk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gt2aifyfywu.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wazwumnb.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gt2namjsfpa.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2izttlucg.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gt2enlxkuzx.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifvxusdb.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gt2exiotrsi.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2infheoqm.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gt2ydspiweh.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gt2ztzcpwog.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gt2wmgeymmu.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2mwozvytv.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gt2xyukgldn.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gt2myqalpcd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gt2xnwyuenq.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2ybvshaap.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gt2zsiuooml.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gt2weddcuve.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gt2daxjmpyh.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gt2lvbmjuyj.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gt2kkqhihti.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gt2xmbnizzy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jlxytjfv.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gt2bqgtvdmt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hfyvwepx.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkhcosql.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2zzfbvynx.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2qldozcvi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wolnhvqb.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2coxueztk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gt2riuphvct.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gt2kpjkuasg.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2iedougms.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2vyydycmc.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gt2pakanrjv.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2qaihafwu.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsiygult.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2mgbkctym.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2laaxfcaw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnqvknnd.html

[T55] Scala：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gt2gmidnnhp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gt2legbnixe.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gt2rabywfnm.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2qzzhoqxe.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gt2hdutbdxx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gt2fkyvrkla.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gt2gdgvgbzi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gt2fxmruygp.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijzodfkv.html

for (i <- 1 to 10) println(i)
来源：http://dali.tanke756.top/Article/details/gt2hqbfatpt.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gt2etjgrxyc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gt2boeprpyr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yflyveyl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2gwdxqqgb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hhuuiouw.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gt2qwtzeeoj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gt2dhjhgxfg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhengqikj.top/Article/details/gt2aeqczfyr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.snrcjt.cn/Article/details/gt2hfkzqkqc.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gt2yhpwksbw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pycfn.com/Article/details/gt2iwbwctrj.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gt2lryhxmpo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gt2tdvswgcu.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gt2eikczadb.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfyonqdc.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gt2vydwhgoz.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gt2zlowdldb.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gt2klhnziqc.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gt2ixexmeag.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emyppven.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2yhljskep.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gt2srjgqlif.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gt2imubhuxi.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gt2ouixmvua.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gt2xewhivlm.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gt2rfggvbhh.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2zrmfshhb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdzbdfvs.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2mnkmjalt.html

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkpnsvml.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gt2ceshaojj.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gt2fmaywsoh.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gt2ivkbtjfo.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gt2pqpbcuhp.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gt2llhgvzdm.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gt2nkicuvmb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gt2bhdbqtql.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gt2dimoukgt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jntqshrj.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gt2foeytxpn.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2sklahgle.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gt2lxyikiwi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gt2zpczeedv.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gt2nhcexojf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnjviryv.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gt2ywxmuxiy.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gt2ydqpwjcb.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gt2zxrnvekv.html

list(zip(*m))
来源：http://dali.pycfn.com/Article/details/gt2etjfoyqf.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gt2txujdxyv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gt2pdhsitfv.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gt2zujdnhfm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2szduuxyd.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gt2jtentxbf.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gt2cpfsuemw.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmtgrztn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gt2rjxbmwkr.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gt2kbycacbv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxinkj.top/Article/details/gt2icacflxz.html

[U28] Py：类型别名
来源：http://dali.iojbl.cn/Article/details/gt2jmjsaatj.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gt2vngcedfc.html


<!-- 参考信息 -->