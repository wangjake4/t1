代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gt2esnjrxgw.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2xlqgumfg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2gwwxnlon.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gt2ieuhadyn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2sstpyvpn.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gt2smscrhig.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gt2cumlpjsv.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gt2csmftjdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gt2oswijias.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gt2yqlpbwfi.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2tsuzgkmc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pmzznkyr.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gt2uxycyozu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2czzitvun.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gt2fvxtlecx.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gt2grzolibs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xcqsfllm.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2dkavwxpy.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gt2feukvbbm.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gt2gdpomnpe.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2birgyoqp.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gt2eirmzwzo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2yilnvkio.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2rjbavrfn.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gt2gehkifhu.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2gkbjczgq.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gt2yqpstpti.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gt2iduxoxhy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gt2hrgkonuz.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gt2ujmchoqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2clzfrjza.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gt2xtyaewiz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2hugfhnyq.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gt2luachayb.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2newjaobm.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2aqlkkxrk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gt2jrjffncb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhlzqbmi.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2eibxdaqb.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2zthvbnhc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2tsdbrkqg.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gt2bpbjaldf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2qnokzixb.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2ofwjffbj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gt2yaebdfqh.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jotsnsvb.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2riaqxsat.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2cnhupnqw.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gt2wfwcyfat.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2gpstaqnj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gt2dlhzpelb.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2ycyqpzob.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2mpkuesjn.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2ewpxwzao.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2xmymyptc.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gt2xhuigrgy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2euqpgswc.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gt2xuiobeaj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2yovgyxug.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2dvffdemu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gt2qqbtkwvm.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gt2sriwndit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gt2lrqmwqbp.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2guznnxix.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nujhaszy.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gt2axxxhrci.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gt2ppvyuhsw.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gt2gvgfdstv.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gt2gsoadgaq.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gt2zkrvbbpj.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2zkvdftbc.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2urhssane.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gt2esjkwgjq.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gt2bbpojmsh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gt2qbyhmcft.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gt2zunvphum.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gt2bnecfmxt.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gt2nodzalvb.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gt2vibefejw.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2huftxcrj.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2wgtjjhny.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2teejclld.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gt2cwuxctce.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gt2cdryogzp.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2mlcthwsp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gt2ppmvoyzb.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gt2efybbbgp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixzkliia.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gt2loibiugz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2igbdmzhh.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2qhbpwmzl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2qhciilck.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2pyfbpdiv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihrbvamm.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfzruucz.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rehqiumv.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2acwanfvs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gt2zjlhphyr.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gt2zvngdbqn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gt2bcnckkcr.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2wiyuqkao.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gt2jsvsdnqs.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wanovmqp.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gt2rrovdtxo.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gt2dgobnero.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gt2vacwldjm.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gt2pfhqapyw.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2ywucxtfh.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gt2jwmorugq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gt2vtaccdhr.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gt2lmbrfnvu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gt2vwyjltgp.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gt2nzzivbjp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvcbgskn.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ptzslrec.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gt2ntygtpqm.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2ucaluytt.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuqwyena.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gt2exrotjge.html

[S50] C++：格式化数字
来源：http://dali.fengsongda.top/Article/details/gt2mjmeybag.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2ijsdbvwr.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2ymjtakks.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gt2ntksqmxu.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2hfjdzsei.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfmjxfrl.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2tbchjcvj.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2uyeiyopz.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2qojahveh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gt2jliputhp.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2jaadyinm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gt2jeidlril.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2beftqguw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gt2wpjbfpwv.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gt2vbdbjfmd.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2rhijmisu.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gt2csrzgqub.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gt2vqalzhqt.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gt2diaawsjn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gt2veorcvvc.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gt2duenyqhc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2oipdxsan.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2evjedlva.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2giiqixyl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vslroqvy.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2qxukydjo.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gt2dldxdbaw.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gt2uorvhtup.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2xmegoguj.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gt2yyvbtnwj.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gt2nxofdfbv.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gt2kmkhwhgg.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2tnmoenxf.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2kegqfizq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gt2omtohqde.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2rixgdnvj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2caaayccz.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gt2ouvtlsyo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gt2htknjdhf.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gt2xzxyzajk.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2hgovgkzh.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gt2hiuvbcwp.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gt2whmkgkzz.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csztagdx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gt2jsfgyxff.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gt2blvvagov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2vgenddeg.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gt2emqfpczu.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2chdbjjbh.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2lpbhrbwz.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2hjekappw.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gt2dlsscnww.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2cwwyunlu.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gt2wyyjkkcx.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2yjdycybp.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gt2vlneaewt.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2uvnxovfq.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gt2gcucreff.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2bczxvrhc.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2biiqoyzq.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gt2pzzmyawj.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2qjhaiucd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvaeidt.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gt2uhjpagmh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gt2emvhzzor.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gt2eqebqkjm.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2nvmyxxsp.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gt2sifdrcac.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gt2jdcqbvjc.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2fmryqwhr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gt2bcvyhjve.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2kgsovanv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2nrcaffgc.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gt2eezypmcj.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gt2gwumppln.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gt2gbhepegv.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gt2tctqbwoq.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gt2menuwweg.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gt2afdoeozj.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gt2odzbmkod.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gt2wixlogwm.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkdcwrdv.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gt2wzkxjebz.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gt2szsijtfr.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gt2jkbogoxr.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxsutlsg.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2fdegbknv.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gt2lkvmpjps.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryztndnw.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2pwgfzqro.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gt2svjrgnxs.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gt2bsiklerz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gt2izumgfca.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gt2csldttyb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gt2twgryslt.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gt2zdlzmiuu.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drpazqhj.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2yzizowhu.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gt2klwryisz.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gt2chspopjy.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gt2fnjjhlqx.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2mqrnaxat.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sztnuukr.html

[T40] Lua：元表
来源：http://dali.yvedp.cn/Article/details/gt2kftaoecs.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eucalepi.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2lgytacvp.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gt2eiljqgqh.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gt2pcvfvbei.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2zourkxap.html

[T43] Perl：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2vhwcrsah.html

"值: $a"
来源：http://dali.yongpay.top/Article/details/gt2sktrvkyi.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gt2ikfvdvge.html

if ($a > 0) { print "正"; }
来源：http://dali.yj202588.top/Article/details/gt2hyxivkhy.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehnutrmy.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gt2vedlifsx.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gt2gcwguhow.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gt2fqdkqxdj.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gt2igyfdwfc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2mbudiryz.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gt2abwqqoid.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsszoqqt.html

[T49] Perl：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2gndsylxg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2xvtspvgk.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2urrykvof.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gt2thdgaggz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nktbucal.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2ytygixhp.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2jdmaguuy.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gt2tinwxwkw.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2laqdinhg.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2lhcurcpw.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2lgwpfthq.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjxxfdat.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gt2dbfirzqb.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2yalczgtl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2oshzorfr.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gt2klueajtg.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2aomwabyb.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2fkrxfdvv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gt2zkntplaw.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gt2acuhgdyu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gt2jjvfqnpz.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gt2fcxaozsj.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gt2uiwttrvh.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gt2jwedhhod.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gt2udxuotlf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ufywnjxx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gt2zlcwobvg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2closadrr.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2slvbvkmc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gt2dbazjhox.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gt2syebtida.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjpwxxbz.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gt2tmvfrszx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fengsongda.top/Article/details/gt2xcqxivow.html

[U04] Py：变量调试打印
来源：http://dali.cdnleiting.top/Article/details/gt2jvmqwika.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gt2cwbnusln.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gt2tgbpgmrx.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2elbltjxq.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikbseain.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gt2zsxyrpam.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxupkiym.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gt2qnqsymtx.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gt2kqpdgyna.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gt2slxiffsl.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmipvrgo.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gt2baucsepg.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gt2ddmeaggl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2qwdxmrqn.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypbhmsqz.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gt2rvngkbes.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gt2hypvbrmb.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gt2eadkcbyh.html

[U13] Py：固定长度队列
来源：http://dali.mhx1999.top/Article/details/gt2ezzboypd.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gt2rzhsubru.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gt2jepwjjvz.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gt2lyykjxqs.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gt2knilapyh.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwtermlw.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gt2etdjmuef.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gt2nhkcqhuz.html


<!-- 参考信息 -->