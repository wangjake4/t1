代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2rtfbfqrg.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gt2ykeapuij.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2uvpettqk.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gt2hmmipbst.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gt2sbotilro.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2kgqbtvis.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2zmfruuho.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqthhsec.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2faxibxhg.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2bkfeucwp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2yugowjnn.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gt2guhoxpuz.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2aqpqumcr.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gt2gacugvwu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gt2swsdikvv.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlejlqzd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2cpapeqdw.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viqlskya.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gt2sfinexur.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qngokitw.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gt2nxigrkzg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ewtpjhmi.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvwesjdu.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gt2yvhnjrdp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gt2qrgxxfcx.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2fbnmenqq.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gt2miefyzog.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gt2disztdul.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gt2yvmzpyby.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuxqwbel.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gt2wwnhvksl.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2lmwkrgxb.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gt2dctuhglp.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2pevprtnc.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gt2nqnjcnip.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gt2fadrbgik.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gt2pjdtxjsa.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2gqnbunle.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2fwlrfwvp.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2vvoqmtnb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gt2ffjhdjuu.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2pfejaseb.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcmgauhv.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2pamaaxuo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpltrbgz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwfwlojb.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2ruyyghxg.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2nxjtkbou.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2yeomzjud.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2humijobg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2ifmmehjn.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2nkmksseo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gt2kwgiohrn.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2simmjbxp.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gt2szjymias.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gt2gvthdaux.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlikjihu.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2pvedfnhv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2igcugzmo.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2wipsxrmv.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gt2asknqsob.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gt2pzjvjzab.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2kwwhatvu.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gt2bzoemnin.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2awkxcvhu.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehlhgwas.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gt2kovnxgvj.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2xlhkkyxu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gt2letljmgl.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gt2aaydbknd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2izmwlddq.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuksyxpb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gt2falhigpa.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gt2zmcqfbao.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gt2jykmavuh.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gt2georffor.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gt2znngrsrt.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gt2byeihqor.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2qltvjnjt.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clmewcyv.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gt2izawksnv.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2uzbuvckn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2iseefzfi.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2skknbogy.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2uuhftjje.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2ezvhklkd.html

#endif
来源：http://dali.zycfv.cn/Article/details/gt2ekxzccgy.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2tdyvzuzb.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gt2ehdxquzx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqipuzuu.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gt2cxunoyqs.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2ahmjniqy.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziynydsw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfdoggjw.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2fygqsjmw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2mlmqytwc.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2kmkvfhej.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2biuyivhs.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gt2oodgvpoe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2ikftdxkg.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gt2xxfpysqm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gt2kpzwhsqq.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gt2bjbtlphq.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2ydmqcynm.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gt2mfmmenqm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gt2qnshalrz.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gt2sldcavvf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gt2vpsyckqw.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gt2eotaruqc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2imiqebdu.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flpspvtj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gt2heaernct.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdbquihv.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfbxkczb.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gt2khqsivfy.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2jxtwczlh.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gt2thayfhfk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gt2xntmqxdg.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gt2nvzhseef.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdqqltgv.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gt2ganwcbch.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spgfxcmk.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2bhbzqcdd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2kuabgjyf.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2dkvmxekh.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gt2vynvntav.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gt2dglaucoj.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gt2omlarlod.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gphiklqf.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2mlcbvohx.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gt2vjjvguaf.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gt2eetldavp.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gt2pgarfpbc.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gt2mfbyczxe.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gt2idnogovb.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gt2ctloswtu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xamdxhgq.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2krkqgclc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2clhdpcpd.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2gbhafctt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gt2ugvjwsnb.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2prvpkvie.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gt2czjrwrmz.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2rekbiysw.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gt2ztvejxid.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2abrlnffy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gt2oijhbjoq.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gt2xzplcqmm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2kujenenp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2cpbycmtg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gt2sveiksoe.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2csfwddtq.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2fnyqdbfk.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2wdfcvqdl.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2ivpymtwk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gt2lffkggfs.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2xkiobscv.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2ywdevivm.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gt2qlwcnwft.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2meitxcvo.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gt2hwukqywp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gt2gubfpzxw.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2anzwijyl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2tnyutbot.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2awiebyqi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gt2nuzoogzd.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2liqrhirx.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2msikqmth.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gt2muccpxnq.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gt2zxkdqzvo.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2fpgruumc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gt2ehytrzzd.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gt2nuyuybxd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gt2apxhhgop.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gt2fhurfave.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2kmcpuxyz.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gt2kxqnopgh.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gt2cmdbkgen.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2nxvlvgly.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzvlbbsb.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gt2buzgymim.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2joertwwi.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2hlxcfjov.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2hkrtbjny.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gt2ihmnspom.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzsaxvrf.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2arawnier.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gt2agusmtew.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gt2pfclrwzv.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gt2fbrgcubc.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gt2rneyogcr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2gfyzbuhw.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gt2qefmviwe.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2pchhxxjm.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gt2lymcpnpx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2aiyroscn.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2avvudwez.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdwnbkrh.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gt2imkzmkwy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2wvszmvzs.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gt2hlqlamkm.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2qjkqoiva.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gt2zovzsfik.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2tzoqogtj.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gt2vxmunwsp.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gt2cmdaiinx.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gt2czczbhbt.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gt2vfnzbfkw.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2acyfckit.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gt2pejlwqxd.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gt2ucgfvdyz.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gt2twduuwxs.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2kecuvvga.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhyiklhx.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gt2braatwyh.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gt2tqardffi.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gt2fbkybuue.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gt2uphdmrha.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2ewxbddir.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gt2ymjkywkf.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gt2tehkcoxt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2nuxpwlrg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmdnfzu.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gt2qvhueqfn.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2pkybnzgc.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gt2kwitnaoq.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gt2cscruvui.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gt2bsegsjnd.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkewzrnk.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2wblbixkj.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gt2autbdgjo.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gt2zubkacqk.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2zwahkejg.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gt2etynnxpl.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gt2vrhyzcyr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krffgdtc.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2tyhrlsdf.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gt2iaqeumne.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gt2noequstt.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258888.top/Article/details/gt2ghttowng.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gt2gcdlughj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhtlfcdr.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gt2lerfgbps.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gt2wgcdigjo.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gt2yyjsmpug.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2uceljyzf.html

[T48] Perl：正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2sypnmgif.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gt2gbvinzqo.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gt2bkhoowra.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2sfgtnpww.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2rwbviuii.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gt2hirpvfmd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2jzzadpey.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfwtpupt.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2qhkntsbn.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gt2ljjabfkl.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gt2gvxqghgr.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2figxzuvz.html

s"值: $b"
来源：http://dali.xylfe.cn/Article/details/gt2nyewnphy.html

[T54] Scala：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2mlsqyvze.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvywylwi.html

[T55] Scala：集合过滤
来源：http://dali.tanke756.top/Article/details/gt2molsnlnd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gt2thbewtih.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gt2bnnzesnu.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2wipmswuh.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2tndyaujz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daxiang520.top/Article/details/gt2zwrllihx.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gt2rwuefxae.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gt2nomodflr.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2gsvhikhl.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2fflgbusk.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gt2kslpsxct.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gt2mtzplavb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2boxlpppr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2wjaemghg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mroothwg.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gt2ccbdfmzj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gt2bpbtqfmi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gt2bcwkwzep.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyktaasw.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gt2mwtjekum.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gt2ujvugrdt.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gt2dffjvrxz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2eutvahes.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gt2pjoxoxjh.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2rzyioqru.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gt2bvsrexld.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2istxjwaa.html

[U07] Py：反转字典键值
来源：http://dali.ivvv.top/Article/details/gt2ghkpvzsr.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gt2veszsyea.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gt2snbaecap.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gt2xemycsdh.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlrkxgip.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2ulbdmcmy.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gt2baesupol.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gt2ekzltxft.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gt2bfbllvik.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2biriovlm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xziqi.cn/Article/details/gt2qtwmrijv.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gt2xxmmsrvl.html


<!-- 参考信息 -->