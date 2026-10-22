代发 wailian999

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gt2dnmwbdds.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qmcjfsov.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2yxnocxbi.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2ehyykqvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gt2itbrykmf.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gt2yanxegua.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvcwwzkz.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gt2vhfeirir.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gt2khuennfx.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2lprwtgiv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2qbgnwcwu.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2zawbqgfr.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gt2eqrakmca.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2brolpctr.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2wanuphdw.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gt2xhmufzda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2acvyggos.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2fhoanhbb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2llrxetnm.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gt2tinxjwri.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjzsofht.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gt2qkcqqvtj.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gt2bczeoncf.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2jvorpddq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gt2zwjoggqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqkgfcss.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2nduvscfd.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2pqfjhkdf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2fjewerzj.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2sviqoxou.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2qsfcjkef.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2ezwnykcn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gt2hhshjhif.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gt2swjwcvhu.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gt2yfmuudwl.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gt2sfnxstmt.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2nhmtezgd.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2myaiowwl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gt2zixoychv.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gt2phdkxbto.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2vgemiyku.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gt2exckqqfj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2hqaphgob.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gt2wuahghid.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2quthkvwg.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gt2kydmfgns.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gt2xtxbtkky.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncwniims.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gt2aunrizsd.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2pmmpduev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gt2lhtnosnu.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gt2kehedwrj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2puckuixf.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gt2inwjnrbw.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gt2zxxgowid.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2emdplzku.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gt2xvtdjkzl.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2wknmowyh.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zasplnyc.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2bhhsohgi.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vudzavxn.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gt2yrjjeudx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmuhlzwf.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2ewdtqfrl.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gt2cghmxvrs.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gt2rfbdnefe.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2uwijuebl.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2ekbybrrn.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gt2spaoismn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2esvaladi.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gt2kwvwswfu.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gt2hbcmjzlw.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gt2enmdvjvs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gt2pwvifswb.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2cfgiavtd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gt2ztwfcnfa.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gt2xrynatuj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2uitzfoov.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2uodosawf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2jxnligti.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gt2jeoqxnwx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2tykhqacm.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2uwihmxqw.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2ayjomhor.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2wchrixwn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gt2qsdomxia.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gt2kbystvso.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2xjaeqygj.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2dyatixwg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gt2abbpfrov.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2aqzyvtym.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2xjiqoosn.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gt2modttobl.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2ycrvqynx.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gt2niljkraq.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gt2lakfwhxo.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2zvsgmvph.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gt2ynxittxt.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gt2fdpgqamb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2tydrkegn.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2szdotutp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2teqsllqb.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fudxfcsz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2zljhbind.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxuzgfuo.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gt2autrviei.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2pkynuork.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gt2ofhvxtzt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2jdcuilbt.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpmuxwzj.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gt2blmajgne.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2eeuokkob.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2xeyaxhtz.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gt2qxxeozvr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gt2ouwysumu.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2lonlagec.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gt2lwvkstju.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2xysoyqrj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2aviwyjbx.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gt2bowiqmlf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2dvpahlty.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gt2zsjknpxc.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utysvytm.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2dstbuwke.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gt2zrvbizht.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gt2vlwrssrv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqyzqtdo.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gt2diqesebh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2mururqub.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hdzrhrpn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2uyxyjfbu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ujhzyhcg.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2krjdgbxh.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2rdgsljsg.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsbmazow.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2hwhgjxls.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2ardgphwm.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2fbvlufju.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gt2ybreyvny.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztwzwnvp.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2tgtjqssn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgcdzalj.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2lzkfgkvk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2vhuzkxhb.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2fkysgyvl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2tyfbshxy.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2xorkwwmh.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2ekyueijr.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2cpcxjwyr.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gt2xgoqmryx.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2uqvxecks.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2priyaddl.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gt2zzniauqp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gt2srcgofor.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gt2zomyfjbd.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2cmbalors.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gt2dpfwidnz.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2yscuuejn.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gt2rqlxtpew.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2yrbcdxrk.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gt2nedmcbyh.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2ocduoddb.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2wtfjrcsm.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2sxtkeowl.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gt2zyrtxvzh.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gt2eqiprfvn.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qycvenwl.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gt2lefbfong.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gt2mlgyrhnt.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gt2asrhalry.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gt2lgzhzxhp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gt2dupuvrkg.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gt2cusbhqeo.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gt2sprngdxp.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2nltxktfx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2zsubiqwv.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gt2eekcbbqz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yonumen.top/Article/details/gt2fwbeyoab.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2rovbsqsp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2wvwaxgyw.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gt2pfmgllgv.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gt2vdsyvjuw.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gt2iwdqnzrx.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2kweyzvxb.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2cmjetxis.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gt2cskpeizy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkzvfbz.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gt2jjzwfizy.html

[T29] Swift：guard 提前返回
来源：http://dali.jyoumei.cn/Article/details/gt2foibawze.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gt2alzwthml.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gt2bquxkmii.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gt2fkrgpgiu.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2oqacstzq.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2uuvljtjj.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gt2jwtejley.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gt2ilcgozcy.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gt2sbmtizrb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gt2hulruwsd.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gt2lhwxexgy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gt2nvfbmqwk.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gt2wlrejkej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2fcijqkfg.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gt2kyimfunn.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gt2ifunbvdo.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2lygnsebo.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gt2ojrxmqkm.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2nbbdchdr.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2dbupndmm.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2snhoepnl.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gt2rhdynsbw.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2bwmnvjqk.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gt2epapvmht.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2utknrujf.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gt2oqskrajj.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gt2flmavqxl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gt2rcrsuaow.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2hlnvjcwc.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjcpdceb.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gt2nasivxbt.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gt2xnhmtjjf.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2udiatigw.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gt2evvqrbjn.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gt2jpfcpybq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gt2ggzxqjqs.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxqffdqp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gt2kgusgilf.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gt2rizjdrmk.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btijdsyb.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyagrelm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2bpwnczcd.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehknyylo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gt2sncydmpe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gt2wbeldsqz.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2hgkwdqyb.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2vbpsbzmo.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gt2tbigpkyz.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gt2tzzuamob.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2zpkehbue.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2rcpvgvgj.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2hiihtqnx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2ntewbyae.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2vxywtjbt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gt2wwqrrfuy.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gt2fdmxpyvk.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gt2evkgetuf.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gt2ahipaheo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gt2qygpwwpu.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gt2phymtgrx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gt2gwtzzmhd.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gt2kmhtwcnd.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2ntheskru.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gt2obtxquwm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gt2pbwzfmkn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2nobitsne.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gt2creqkbhl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ebcrckvt.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gt2irnvluob.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhengqikj.top/Article/details/gt2hfmtjlmv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gt2tvyjbllg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gt2tuxvprlk.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gt2wnuqpdqr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gt2kxmnazvp.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gt2cdqhobxa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gt2xyshzjna.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gt2dlisendl.html

list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2vsdtezer.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2czfuwene.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hncdzonf.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odgksfkd.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gt2kauluwev.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gt2wbhgqawz.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztajxjui.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgtoontm.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gt2vvzaaepm.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gt2btrdebdn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2cpzssmhd.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gt2vakyfkvq.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gt2rbpuyaik.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2favcyrzs.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gt2kydnnumo.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gt2mrcbzqgl.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gt2flziedvy.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gt2loynlcga.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gt2lecmklrs.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gt2tnzjmhmw.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gt2aeltrart.html

[U16] Py：命令行参数解析
来源：http://dali.yangfankeji.com/Article/details/gt2ptjzqeqt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2xcxnnoyy.html

[U17] Py：初始化日志
来源：http://dali.0kj1m.cn/Article/details/gt2ktrkaxks.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvzzsefw.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gt2hpzlunsk.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gt2qvacislo.html

[U19] Py：正则替换带回调
来源：http://dali.shangyingyoupin.top/Article/details/gt2mihyipho.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkzsrmkw.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gt2ekytzany.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuxming.cn/Article/details/gt2gmrstpex.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gt2qszgpleb.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gt2gqekfwkr.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gt2mgbqesin.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gt2dvkauwyq.html


<!-- 参考信息 -->