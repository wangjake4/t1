代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtsdihhqpj.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtopkpjzik.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtfkshovaf.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtjbgdhhpx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gthdlhvhoh.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktrbbfkr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtsefygvom.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gttafxhvkv.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtmbrisnfo.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtnomybaro.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gtqkixdnje.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckljhfst.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gtpysqfinc.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtuvnkkzvx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtjtiukikh.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtqrtxsvwr.html

read -rp "请输入: " ans
来源：http://dali.0kj1m.cn/Article/details/gtsspwcsij.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtlyerqxvx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gtdqayxumq.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtllzilqlj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtizmfscfl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzximvmh.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtrjwdddyl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvjfacrqa.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtkvcodphg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfmjzlro.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtjkjbusri.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtgodaitwc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gtzyowtywm.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtmeluftrw.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtcykrvhth.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtvadnowhc.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbtdcyoo.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gtqskfrojv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtobswaioe.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtiefawccj.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtwdaiqlof.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtfvykimft.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtjhwtmpgw.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtllnylyqn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtizgnmkda.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnhvuyyy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtsltodsfc.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtfsjoowmp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtivlrfwxa.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtosixlytj.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtatnpifle.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtdcvssshv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtkytxewkg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtsxasxoox.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtkngcsrqb.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gttcpbxexy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtndrdddkx.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtjznzhygd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtbguctfhx.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtejjfdkvc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtlvnnsbxi.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtyxshhaio.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtzmfuaruy.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gtezagvebh.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtmblectmp.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtqxjvfugu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gturtvdsgd.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtblcfkxix.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gtgdyhqqtt.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtjqvvkxqo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtfemahvhy.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtxiunrehm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtybltljje.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtvvmkbpcj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtxnygijij.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtqgnnjzcb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtyqdsqbsf.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtzmfwwgbg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtnefovdxk.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozqedoio.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtnzohecxd.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtexwwjjmn.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gttmrincnh.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtlcramglu.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gthykzbpxc.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gtoorohqtb.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtygxksijd.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtfgrtqnjq.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gtuioijprz.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gtiajqrzba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtprdnfzpe.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtqgzzmbdr.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtcyovioxb.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtodvnogwm.html

#endif
来源：http://dali.yongpay.top/Article/details/gtumftbcvu.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtjmrjsvbr.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtneikybdh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtawjbjyoy.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtlpirhwsu.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtsaxfjqej.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gthsuoptqz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtkbbxedau.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtpglohamg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtmdfxmimp.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gttgvsnkbn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtkgrbnibb.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtnaubauvr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtgxdoyvna.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gtqpmpizdp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gteapstafa.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtzadrjsle.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtnozavhnt.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtvgjazahi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzkandlq.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtsabtnbjt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gttkhychax.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtknbzwlbd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtosnswdik.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtqnvdjyrp.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtsmodvgnw.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtdbcrjkob.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtuirfhudv.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtnrelvqrb.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtpgztwjhx.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtycdeemkg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtzrsatbdt.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtrgkmdjmt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoltxtrnr.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtongjlqtz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gttaigggre.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtstuhiyqs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtfoewlxwm.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtuzubnzfh.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtjmdfvsmc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gtgqfbbudq.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gttutfhdxk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtigentusn.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtbtntnbrn.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtvsqpgxiy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtisybiepv.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtjqmcmfki.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtonqujjzr.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtpfqoylkf.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtlizbwmhp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtdwzhhhzz.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtbxewuuyn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzdwnwmp.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtifkqoxmy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gthqwwzhkd.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gtauscbclx.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtdhqvbcfc.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gthyrhrgvs.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtftldxakw.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjlrpqal.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzidnzguf.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtadunqyes.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gtdsndzvnv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzblzaazn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtrkmlbfox.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvqxyfvwf.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtxjevqtnk.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtmjxpfdsr.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gthbiwsuvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtzxuenpyb.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsudjqldo.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtotrjlyur.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtwpvixgkb.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtnzdpnrnk.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtdkkuyvsy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtjaeghfsd.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtqoopbgtt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtjupqwvpe.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtjbtllopg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtsnyqmrui.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtybmrfudy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtncnqxijs.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtoazoknlm.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtuflifhtg.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtnpgkuslt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuramkls.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtrrvvytjh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gtuuzttfuc.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtccvreghc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtpwrupwnq.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gtnucasiyo.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxkaqohb.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtmqoxcuzc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtxsvfdcvs.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gtwkevuqob.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtgnunnufs.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtnqbauwmq.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtsgyiwfra.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtexhngnxd.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtwpktvdme.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gthaywupcd.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtuddooxoh.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtxjnpdeyj.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtvhupguud.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtofjafkkf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gtdttvaznv.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtqfeufwoz.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtxmfbrnwy.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gtywixfgqz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gtxwfbkemr.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtrpwvwtts.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gtqmkvlclr.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gtkjbsasqp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtzyaylnrs.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtyghxbngy.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gtyynyozbh.html

[T26] Swift：类与重写
来源：http://dali.yonumen.top/Article/details/gtllyqdgna.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtuxoiydwr.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gteugewvvu.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gtmkiokgsn.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtjljakjnw.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtflntqkif.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gtimrzxnzw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtltzfabuu.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gtmifhwzgt.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtrxxgjtvb.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gttckxvohk.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtmrsrqjcn.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtabyaldad.html

local a = 1
来源：http://dali.316326.xyz/Article/details/gtfdiyzrvl.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtftbbsnev.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtygjipnwi.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuikpngw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gtgwnvzqqq.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gtddbwmoar.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gtownfotgc.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxxbsqkbw.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtisnzsigu.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtmbabydnc.html

"a" .. "b"
来源：http://dali.yj202588.top/Article/details/gtiuepcled.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gtnxjpuvba.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtjvjvddxs.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtgcmhvxuo.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtdbqaqggz.html

[T40] Lua：元表
来源：http://dali.yvedp.cn/Article/details/gtjxdgbnbd.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtanicmlqc.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtvbyyeutn.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtfaqzkdeu.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtolorepaa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtjfcrotsk.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtjseygtlc.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtpwbevjlp.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gtwjqtegkp.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtnijgxzff.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gtnwijwzci.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gtftcbhfhm.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtosshacay.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtannyksxg.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtbzpwmehr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gtqwyhrldz.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtejytgfox.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtidrgacaq.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gtvwjjauao.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtfbrbqdnt.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqayrkrhk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtwzmiltbw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtictgigbb.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtrzrbdary.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtnpmcirpp.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtaftyjxgf.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtkkycvovu.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtchswppiu.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtydzasisl.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gtcwfymqfs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtflveurht.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtjwcrsiyn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtfdlvhplc.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtbkwbuhaf.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gthfzgnzew.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtkecrdgjy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtwagohbqb.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtgrplnmuf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtqoqbpgse.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gthyuydiqc.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtrmfmxdrt.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtunvhdqom.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gtnbwtibgv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtowrxzzkh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtpsslhmfb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtttzfohts.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtvgvzfkxu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtexsltlba.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gtwrcszhtd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtbxktigiz.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdtadcxa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtmyfyvtxg.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gtagtmckqx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtensflkcn.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gtqfziftij.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtvvudvunh.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gtgwrgzkii.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gtppmolxdm.html

[U07] Py：反转字典键值
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbyppvqh.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtprullkrp.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gttkdmumue.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtzqzfunkl.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtnuntbftd.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtbhqznolh.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gthtfwvcjk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yangfankeji.com/Article/details/gtemdihxtw.html


<!-- 参考信息 -->