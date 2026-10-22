代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gt2bppkesoi.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyfeduad.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gt2jwyxhtod.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2reccxjuy.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gt2aawoovvw.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2vmbynjbs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gt2btkiaipp.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2auusirns.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgugveax.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2kblowmej.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gt2abxzvrqp.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gt2ecrnform.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gt2imixhqyx.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gt2zitefcrf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2oyfddgoq.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gt2pjsqqemv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gt2veymbwuj.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gt2ovhgpjen.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gt2gzwtdupb.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2zakglzwj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gt2vtmfaebd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2bwkgwppw.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2yenxqoiu.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gt2zlnhgmcv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2pncruhbq.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gt2myowyeke.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gt2pktchzzj.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2xwznveqn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2blnnasti.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2kcqibnle.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gt2vlqntvxi.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gt2utharhox.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2ecyzsagw.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2jipjrbhy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgsphphl.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2nstpwxui.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gt2jfengbtw.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2ykdwuklg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2oitmjtfo.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2chyqkmbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gt2oxarzmsb.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfurvyur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gt2wbtaesmb.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gt2uikcpabu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dramgmez.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gt2zfkuzbfl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gt2uhqqewps.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2nprkobfk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gt2lsmfrpqm.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2wlhyzdmt.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2pduddslp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2auirzhre.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2adhpnzrb.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2cnuwawjs.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2xwjdmwur.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gt2zarrbzsc.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gt2yxqsykbw.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gt2boysvkvt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2gjgfjhmh.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gt2smddjvtu.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gt2mqmxcouz.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2reqnzivh.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2zyisjucx.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2kfpzkpsa.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gt2xqvkqthg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gt2zglmswjf.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2abiavttk.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2egavuuyz.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gt2reurguqk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gt2ccxzvvsg.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gt2istvgjvd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gt2zfoliety.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gt2zgexcmwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2rayolsyc.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2jcognobm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2pizfhoix.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gt2unysrbch.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2msvybzmz.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gt2jjcwsdqz.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gt2uphfkjtl.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gt2qratxcie.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2hmajezxm.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gt2sqzsnkwt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmhjsbzx.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2uwenkgfr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gt2wnibudrc.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgnzmmkp.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gt2kdsudxxg.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gt2onufwtkp.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpgdjdud.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2hwvecybu.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtlcyhru.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2ltdjmjou.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gt2tlddmrwm.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gt2mhucofuy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gt2cvdxfups.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gt2nogdcevz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gt2hmpdhuxr.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2pfodvwgn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.feifeiyinyue.top/Article/details/gt2voljrmog.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2jhbyartt.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2jaxhnhrp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gt2rapvbytr.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gt2ywhgzsat.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2eqhzrhps.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2mbwivhsi.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2zjfjywcn.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gt2euabtiqe.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yonxqxcs.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gt2ckbyzmvr.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gt2foiwzkux.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptfuahve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gt2hlempiev.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gt2keyuxqaz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndxnjwpy.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gt2sudlfodh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qoinawzj.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gt2yibjnaqb.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gt2csznnsqc.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2gkaicktv.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2kkxznvrq.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gt2dgwrefqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gt2gylnvygk.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2gnntokpf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2mhsgtvhw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2jtewdilr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gt2rkmpuqvv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pzaovmmr.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gt2dbdtkrbg.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2kodeuvpa.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sltfwhmz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gt2axpiednq.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2txmerhvb.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2asqevlts.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gt2wbxlkqci.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gt2dezabqme.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2usxpfoag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2oypuaqal.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2ypuysgoe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gt2lvuxwqsy.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2eefiqduz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyhwtjcl.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2irfazuir.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gt2knxmkbqe.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2iqbiblbt.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gt2ptyzvemn.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdnvzujz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2mxqbugqt.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2kyrqvqco.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnwyysao.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdwwbfga.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2zzjsdfyr.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gt2lewqnwlg.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gt2bpvmwyia.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gt2ihuzhyne.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2hsrsgmqo.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gt2kbposcrf.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gt2qswlflni.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2ynyscowz.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2ycmpcyze.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2snhqhgnt.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gt2ynflxfqu.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvnaifvp.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gt2pckmbudg.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gt2wqltjlld.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gt2qkznnapd.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2mdtxcoxu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gt2nnhttikp.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gt2cdmlnhqc.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gt2cehpknma.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gt2gzjzhebe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2dfsfklck.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2lfzsqnkn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2pxomqlqy.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2wkhkyutj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaibkghl.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkbpybuj.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gt2ovflrckb.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gt2cwldhoji.html

class A: Base { override func f() {} }
来源：http://dali.hammf.cn/Article/details/gt2lekbkcig.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2pylanyhk.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gt2wurfrild.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gt2kjqjuqbr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdcgxwk.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2fpuhexua.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gt2laepqiur.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gt2spuccpck.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gt2unhhurds.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2nozbotfg.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2qvdmgdbc.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2bardwwkl.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gt2phgfqbed.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gt2tulcpoxk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gt2gcclzhpk.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2ycbipwtl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2uciexguv.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gt2rtjdlrpp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gt2nlrfkaht.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gt2ymfdvqfb.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gt2ategplfw.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2emqizfyj.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gt2pekejskv.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcbugmvb.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gt2radvdwna.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2ifoyqrbe.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gt2czjkzvcw.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gt2neawajbs.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gt2lgwojshm.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2nxtqqowf.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gt2jycnzkzv.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gt2ystjlnso.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gt2xwvozjjl.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2avcovnae.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gt2fpzotipq.html

[T44] Perl：条件
来源：http://dali.ehwqpu.com/Article/details/gt2wrlipyei.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gt2nvfzufoz.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gt2eevkqyul.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gt2jtgzmtdq.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gt2entryvff.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gt2prjvnplx.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gt2khzkiapn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cheryme.top/Article/details/gt2ypitnspk.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzdeojsr.html

$s =~ s/old/new/g;
来源：http://dali.iojbl.cn/Article/details/gt2basuwjrz.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezkyfkdj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekngyidz.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhmppmgp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycrcvfug.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2ohtvalbx.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2ywxtzvbx.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2tlfubapd.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gt2ugxkabwj.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2fdunmpei.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2mvkcelrf.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2vvavysxq.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gt2hudgaxeb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gt2sbpdjbyq.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2aykjnxde.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gt2yyubjuxe.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmfmmess.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2zyjboiin.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2dwzrusfi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gt2fgrbswjc.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gt2ojkdowoi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2xafxlcev.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gt2acfisysy.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2drreseul.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptnppphe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gt2ohgzdpzm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tmnrxyzp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mymfwged.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cuackkxt.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gt2lhniytgx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gt2jqbhxzkt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gt2apwtlpnt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efegquif.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gt2sjunzihg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gt2lbkiptsu.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gt2hdpgdjtl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gt2kmsnvkps.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gt2enhlubod.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gt2iarcqtgx.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gt2zawngiff.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkktxamo.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gt2qarfyaqk.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gt2vfpgzxut.html

[U08] Py：展平二维列表
来源：http://dali.cucudq.cn/Article/details/gt2yamqpvot.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gt2fzepifai.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gt2eoxiaoth.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gt2odoyxtyx.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gt2vjmrstpb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gt2aewgbquu.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gt2zggiggif.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsdxddmr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gt2ejisdmuf.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gt2xyzxwwnd.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gt2nkmfcuax.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gt2zhofcssl.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rycnuivr.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yruazaff.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gt2fuasvfud.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gt2ezpzejom.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2xmobqeel.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gt2cffkuzud.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gt2hqbfrwqb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gt2ofihacjs.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gt2matspmna.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gt2fstyfvkq.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gt2cupeapdp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gt2jytmfbqh.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gt2dornwtkm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zdqjudy.top/Article/details/gt2tnfwxiht.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gt2ajwwofsx.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gt2yanrqgch.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gt2qhvlqpck.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gt2ulbauziz.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gt2iitxemju.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwyqfejp.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gt2lfqaxtbz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2cjcrjrju.html


<!-- 参考信息 -->