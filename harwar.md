代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gt2weldafka.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gt2dqwxhnqh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gt2ezwakyph.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gt2fbggosnl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfrlrwrs.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2hdkbtxan.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gt2wnrwuwaj.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2misjkjww.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gt2mnhnohqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2ansdouau.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2obbandoq.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2ogpaktzz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2ramqnuwl.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2olxhuvrx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2gigezluo.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2dumhkaqj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2vmmxymuq.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2gqmepaau.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gt2xrzyrwvl.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gt2rickmkor.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juufinfq.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2tigojcgh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2rjsjfpqc.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2xcmyshyi.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gt2rmejfcta.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gt2ozwhbtup.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2qnexukcw.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2owruvlfo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2gdzrlyab.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2mdkqtbwq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gt2pmvlnmtd.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2clnmxcfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylqfdimq.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrfazydg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gt2nteapqsw.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2lnbbmgmz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itejeatz.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gt2gfraostl.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gt2hfogneue.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbnxucwk.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gt2phtjmulj.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gt2ilvmzgym.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2bnzktziy.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gt2cuwnhrbp.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2emvnwbfi.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ktfjbwsv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gt2flifeuwg.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gt2pmlihnlh.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gt2dhhfhals.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2dwjizazr.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gt2fpngpxmb.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2lmiooxtw.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2dgvgmmcs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gt2ngdknhyq.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gt2yuckuwct.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gt2jimnfyjq.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gt2plupvpnc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2wbhdnemp.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gt2eatkltls.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gt2negnejst.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxuteuzu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2xvfyxkej.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2ksbbrlek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2noooovkz.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2xohfiflh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gt2pycgybxs.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gt2dixswsjb.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2yaztserh.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gt2hkolcbnf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibhlxjbh.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2rcdccjim.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gt2xsweplcl.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcuedycs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gt2ugggzjzr.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gt2sdyaovlb.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gt2bzkhvcut.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gt2ektvwlbw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gt2cnufaumy.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gt2hlppekhw.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qyoadqqp.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gt2pflckdao.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhgsncyn.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gt2ryypdbqt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2mglusovw.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2hyybfwld.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gt2homxirdw.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2lpeowsde.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gt2inlxwbao.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2ucknqsyj.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvkjgcuo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gt2rbwdesly.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gt2nnrnzmaq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2ijdfdzql.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2kbmsysje.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2cijegpcx.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gt2vflweeng.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gt2fvtuhpub.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gt2qmlxeflc.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gt2psaqhtse.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gt2ealcrvzv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2atxoryia.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gt2ihkegiii.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2hvlsepva.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gt2kespcful.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlzpmql.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2tyflzsah.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gt2yzfwxlnk.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gt2xuxsuyho.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gt2rvffzess.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2goppfmcp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gt2rnqcwrcw.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2bnloxlef.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvrmesld.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2dkedbsli.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewgipqaz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jvbozzro.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2vrxxpcbc.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjtmnmpg.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2ozpbqrbf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xinyue.icu/Article/details/gt2nidwcxck.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2xnhebxsb.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2zvrpghqz.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gt2oisryusg.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gt2yxfncpgi.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2tnplufsw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2txkgkygy.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2mxsnsppx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2gheagpse.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2bexdzkwt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gt2ruqpdyxn.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byklyplv.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2zircswmt.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gt2psketcua.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gt2nvfndhge.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2sjwquilb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gt2schgepdz.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2krdqprak.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2bmfgwnhj.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2wexjagpp.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2lxduauqi.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gt2htnemufk.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gt2vyinbmyv.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gt2ezsnadbn.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2rrpxwxre.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gt2giaqhknl.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gt2xozwixhi.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gt2rkbapuov.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2qqzfiyaf.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gt2qtzyfzru.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2lwluvwrj.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2brogpahg.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2yjgpsmjv.html

[T19] Swift：可选绑定
来源：http://dali.yj20258888.top/Article/details/gt2rygfqmyn.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gt2lelzxnrk.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gt2tdyvuiux.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gt2luagkcoe.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2ktoeteqi.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gt2wnuxkdtp.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gt2vbzjeook.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gt2ijlmirfd.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gt2yctopvis.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2tarlvdvc.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujsyuzoz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2kycbopxo.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2qbykjgnc.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gt2llfqgxud.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2kbxtahug.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gt2vgwokidn.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2peejskpt.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gt2lixkunoq.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2aseohpwn.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gt2spvpares.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2xxykssch.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gt2ifrmznuk.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gt2uvdsjzdz.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2bezjssuh.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngciipnx.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2wjidapng.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gt2hlrhwyqd.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gt2ezcrwkjj.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gt2jbcrxyrj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2pymayqdm.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjtwxksg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbnfqtzz.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gt2ecwhesbr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yongpay.top/Article/details/gt2vrgtvhwj.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gt2woemmmiu.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gt2shiyzjyb.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgrfydyb.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gt2mtljkgmk.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2mfrljmlr.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gt2farvkqcr.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2aamsdddy.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2odzvkugh.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gt2fvmcbylz.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gt2ghxcxuso.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2qqkxgvmg.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gt2thpuirim.html

[T42] Perl：变量类型
来源：http://dali.vqdsnc.cn/Article/details/gt2olkgvzgs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gt2dwgbflnz.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2iznvycam.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gt2rqrpqxsi.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gt2ikizxgrd.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gt2pkxetdfx.html

[T45] Perl：数组遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2cwgoyian.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gt2eekjduri.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gt2wnblaurq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jyoumei.cn/Article/details/gt2tmpfbfoi.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gt2dndksknb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2iuwfcjjo.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2qpsqnzxu.html

$s =~ s/old/new/g;
来源：http://dali.yonumen.top/Article/details/gt2qplaohsg.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gt2krddjipa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2uumdefci.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2akndspnl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gt2antfpmsy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ijqvwxsx.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2unexrqkz.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2eeiafuvo.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gt2ixlmqlms.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2jskjjgil.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2hlqfhokl.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2azuflehu.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2wyjdmydw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2agbqvyvn.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2zwcmhzvp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gt2aeksqfbb.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gt2zethbmxm.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2sqvoqcwv.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2pelfogww.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gt2bbikjkst.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gt2szzuiuvk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gt2jqdxkcce.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2ywxkfkid.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2ubnrychi.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gt2mkjegemt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gt2pblbdyyr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wfqqcvus.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2vfdkmqqw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kehbqrob.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gt2wqqwgkkr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gt2dzkiylxs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gt2jihqoube.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2eymistyy.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gt2fxmxedew.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gt2yjppbybv.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzaocvol.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2evjnpbrc.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gt2ntkngloe.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2sddwxdhn.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gt2cidknphc.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gt2hwppqgep.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzcezyws.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gt2amkuoduo.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnzfpdaz.html

[y for x in nested for y in x]
来源：http://dali.haohaochexian.top/Article/details/gt2avbpkgmd.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gt2tpqphlar.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gt2znuihate.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gt2ltvzrsak.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvoxzutb.html

[U11] Py：生成器表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2vylgtzxf.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gt2falhmlak.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tanke756.top/Article/details/gt2brbgkhls.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gt2ogjglrwy.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gt2etaaetfr.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gt2vyndzxkj.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gt2mgdriqzc.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gt2cyxfxpfu.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gt2vdteosoy.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyxkjmat.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gt2ivauvwpf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gt2wracxaqw.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gt2suhecozh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gt2axwbutna.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gt2jlhsnljb.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2iipwpria.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gt2lvvyjeho.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gt2xjnmhhmh.html

[U20] Py：缓存函数结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqohemrv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gt2warvixnm.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gt2rnmeogae.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gt2asvkrimp.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gt2mnxcrome.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gt2vqfmuqhx.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gt2kuhrvqdh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gt2mrbrmtbe.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gt2crvcjitr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2ccgfrxvm.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gt2wszemlmn.html

csv.DictReader(f)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgivosxq.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytgcxwaj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zycfv.cn/Article/details/gt2ntcxzccw.html

[U27] Py：异步 HTTP
来源：http://dali.xziqi.cn/Article/details/gt2yezswmyc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpeluiws.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gt2cdikwvdd.html

UserId = int
来源：http://dali.chenzaomai.com/Article/details/gt2mncybuag.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gt2qvngqmta.html

@property 与 @x.setter 配合
来源：http://dali.zhixingplan.top/Article/details/gt2glvmupbd.html

[U30] Py：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2moknpqnu.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gt2kduggaak.html


<!-- 参考信息 -->