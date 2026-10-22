代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtjaqjyryd.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtrgjtfstx.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtdqytmnth.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtnubeclzi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafgpcjzg.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtxvrovrtj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtyorvcsxc.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtravjwkwv.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtbdvyjqkz.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtzddazoke.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtinwmtfbz.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gttobzunks.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtgivpmqco.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtdhjxqhct.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtsnrtkiys.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtxnvbqkjr.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gttfubfhsu.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtdozhxgxd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gtxpnejmhm.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnnwxlxf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtokgwhljl.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtiluqlhgo.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtruedseoe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdbqbxmim.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtkqwjzrdq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqwpyjqcb.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtmaueuwji.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtdorzrdsy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtrmjbgsih.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gtjssbekuu.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtcrempgoe.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gtsacfvixa.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gthrvbqgnu.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtwneafids.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtmfkyxxrt.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gtzrplekhj.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtzjksehjo.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gthrsulbwu.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gtqinxlrjb.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtefuazigt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtozdojjwe.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtxygsgtqs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gtemdkeewc.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtuilbhicy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtfzsoqykb.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gtxushmglp.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtbcfurjxx.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtkebwxkbn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtagrzewkm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtmaasirir.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtvpcykfna.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgxpniql.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtpjhzgmry.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtaudghrmq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtgpcwpejc.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtwtdhrlen.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtuwwykpzy.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtumipcfqo.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgadekisf.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gttjfwqkml.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtyyrazdic.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtryetosgc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtlvbeqjfb.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtoucjhwnf.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtgsymzthb.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gthryeixyu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtigbomcdw.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtzfasdstc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtvqufxymm.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gtmxujlezc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gteyditgbm.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetebarzk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtimxnqrhr.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtnwmflhql.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtsggqqhnv.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtmmxyemcm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtshxpwyod.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtrrminzwt.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtaxowawyp.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtfkaslkcb.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtbubjwfny.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtzknwezjj.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtgzaxhdlx.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gtbqxumtbz.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtyrqdhudc.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzufciinm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtsxnzalzo.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtbgdxrsqu.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtcfdnahyl.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtuadrrrii.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtyrlmllxc.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtpeqroirc.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtpfztbikj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwyikdbsv.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtmvkfokcx.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtflzelozh.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwckzgwkq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtfewnhgft.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtgbdwzqbx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gtgpqdhotk.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gteuxnajyj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtwyhlupdl.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtqmushgec.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtuchgpiva.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtbuvnwtll.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtpoukphct.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtvkfrbdzb.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtfmsqwezx.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtmmagvlkr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcjgyova.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzlbldwg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnwcxdgv.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtqgbpusig.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtzhaqulke.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtountukgd.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtawyslkew.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtkvofdckf.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtdtqzkhpc.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtomtwthed.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtfwwluksq.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gthvlcnotj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtfdeprscx.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gtiiordian.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtkytxpxze.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtwkzvedss.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtzwxhuysc.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtyextblzy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtpvudshoe.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtfgbqfqqs.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtedlehjnr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtngadliit.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtiuxageti.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtuvydhtar.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtihtfgirk.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gtqamdvhyh.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gthaxrlnjl.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtqkqooinn.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gttlqeqqvw.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtrjibnovm.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtrlgarxtd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtdmdemgcn.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gthvhzkrby.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtfqyzjgrb.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtgntusazx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtsoqindak.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtfwtbtfen.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtiefwawrr.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtjhyhxrqt.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtfaxgpcne.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtnqvltpie.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gtvhjyirfq.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtofxsgsuw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gthydnwysc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtypfqsgdn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gtlbwesusp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqrakupxv.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gthkgdcnqq.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtoptzdhsf.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtpbraglwc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtoarjehqe.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtrbhxjgdy.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtbbvoweck.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gthoihnaug.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtrspwmlrp.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gtnzdpuscf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtgaljnlrt.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtuiajrdxi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtshqgkjqe.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtyszxnkwx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtowqrsufd.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtchnwmxan.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtzcqmjgdb.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtosgufhbi.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtlzrfqsht.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtzqniclfh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtziokjrwn.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtunezxrja.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtyvmyplic.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtacazzisk.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxebgryhf.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gtivibysga.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtxswgyyio.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtfujzqnpw.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtwnatzzsb.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gtfjimldpj.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtzplyndrp.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtscgocvpw.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtmffjeuhx.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtxewtzjwm.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gtohzysxvo.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtjzqykrca.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gthjistvsn.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtbjcppolq.html

if let n = opt { print(n) }
来源：http://dali.sysykeji.top/Article/details/gtnyrpilzu.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtdgsuvfxx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcpvrxpg.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gtgotftkli.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtgvwblpit.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtkjijcjyh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzhobkkb.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbkaxmnm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtpbctyaxk.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtsnktgjbt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtvgococyn.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtzfwmzxjj.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtatlizksk.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gtjsuafnwp.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdyourpj.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtorrrgwej.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gthlyjprsx.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtjqgoabwb.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtnyjhukps.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtrynrtdnz.html

guard let x = opt else { return }
来源：http://dali.yuxming.cn/Article/details/gtsbicycsj.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gthrewbwny.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gtzyyzubtw.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthasndjpn.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtizplutap.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtdykgskpr.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtibitjnhz.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gtzfhkotns.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtijwhalfp.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtaonrmxvq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtsdnpazss.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtifgwwlsn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtntyqxsii.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gtjcazrssp.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gtinbuzhls.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtsofwayzn.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtkqdlbzak.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtufwfryix.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtsmtznwbd.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtvzpubzmy.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtdilwxizf.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtnbaedtwy.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtlpmeprow.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtdxyumdqh.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtonhfuojk.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtxfxmmfej.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gtmnycdspl.html

[T43] Perl：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtugfxueje.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtyrtvebyl.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtsmiizilk.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gtqywsawye.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gtwqscignv.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtvimtoycr.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gttoowivzm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gtljukcnax.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gterevnjav.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gtstaaratf.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtqnacfnwo.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtbreibqeh.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtvyebxbyz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtbildxjvx.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtjazubbds.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gtaqrrcatp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gtchpoayno.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtijitzaoe.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtniuyktno.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtsgqngnio.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gtnymbesgm.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtozdoqhle.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtksffkpxx.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtaqujgtws.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwuaytxh.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtjhrlocxo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gtwwewofrw.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gtbqllnczr.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtpmtssbwz.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtujjzgxie.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtodeolkqf.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gtazzihhql.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gtqhskywye.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gthmvomqig.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gttocrxkdx.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtvnmxfook.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtnpeowjuw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbjoojkaw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtvpioazpv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiufffhr.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnsyfaao.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtcohppcth.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gtqjozambi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gthzgyzcnz.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtgzpejtwn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gtmftcgokn.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gtwyefxiud.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yueranfly.top/Article/details/gtebahcbyz.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjslbydxe.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtlrnnhxhw.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtwqrmvkib.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtpqugxwoc.html

[U07] Py：反转字典键值
来源：http://dali.svipenyu.cn/Article/details/gtovfotryc.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gtdvbghauu.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtxxwkytpr.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtcpvrgump.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtabtkqilu.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gtglevxnbs.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtcyijvdzd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gtidbvccbg.html


<!-- 参考信息 -->