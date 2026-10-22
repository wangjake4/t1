代发 wailian999

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtzfzjsfhe.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gticvqnwzs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtgppmykgv.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtttqunbnc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtwkjzjluk.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtcpqvyeiy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gttwagzxej.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtcyzejmbg.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtamlbfajh.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtbsmleiwd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gthebxsifj.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtpfllgcwv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtzvkdvexd.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtltoaigic.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gtkdsnupyc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtphxqqzfs.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gtzlkwwwrg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbslvfhac.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtonsrxcps.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtpucjisve.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtuwwssbpc.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtmokwejoz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtccjgbmty.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtgvqxurxb.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtlkvusbuh.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtikxmhbez.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtwoeuhcta.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytstcczq.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtooqdtxly.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtksctsjeq.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtxrehzgts.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtwzzavslk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtlxfekxje.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtxpjexyjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtejvrfgge.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtnscgvtug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtlmplscqb.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtqrnykmyj.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtjwuersgz.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtvjbjgrqm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtxugzpozo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtvakjywso.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtjbozftju.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtclmerruw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvgwtsov.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtwyhahycu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtyubfabkw.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtgcponkox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtxmkkixes.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtzhtvoojs.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gtrycyfflm.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtlmkhrfdg.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtzdcwzazx.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtgdwahxba.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtzxelcgks.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkkilbsx.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtaeynwxjw.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtvoynfspo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtaywyeray.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtooylzzwq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gthkoovneb.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtymxijmjo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtztlwuqhx.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtzeccpogl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gthlodmczb.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtprwfpmof.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtimzfzsif.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtaimidfax.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtqvyvvonl.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtenibhfgv.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtihrhehlb.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtpunjlwdo.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtnrecfskd.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtxovamvpf.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtkulercfg.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtvpbkknin.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtnpqzxadg.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtncymthua.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtycmnqbpq.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gtayzabihb.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtcarqqgiy.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtoevujznz.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtgpxthcyb.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtabfqdzof.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtuklagjom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtkqydpriu.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtshjczsmo.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtfpdmqazr.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtiwuxorkd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gtiviohaco.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswyizzqt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtcawwarix.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtxhjchbat.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtutgxvkei.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtuspirapg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtampyxgqt.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtjniwxyxn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtfqxjmqis.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtqdljwyyz.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtyjfutxts.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtjfuglwkw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtpjwpyoae.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtxsxgzcrz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxefskrx.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtfbzbieui.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtgxvfqunp.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtcaanlsqb.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtuaqtsxsl.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtsijqfdsu.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtecnkfodw.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtbvsgrlts.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtjyvrrkwy.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmczmocih.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtftdfueos.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtpxyicftr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtptlbudjb.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtovapnfog.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtpahvnksb.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtnccadimu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtcecttrbx.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtkdlwzoqe.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtzvnmlrbx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gteswmfkxc.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gtevologed.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtkmqaqwip.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtueucfjcz.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtuyxbwavk.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtxmaumkxp.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtjosgmruu.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtopmjorea.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtuwjaqfph.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtqceewtsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gtwlrvpytl.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtbcuquvhr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtwsqtitun.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtihzxmxpu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtrpoquvus.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtxqmqohlp.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtjrgkkino.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtdqkmmzzv.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtzawujnjf.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtzmqwswpd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtbwncnaxs.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtgfuryfcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtjctizayw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvtndwqnd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtingfmabq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtijtwpyid.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtflzcdzsv.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtpxdxlzgp.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtnajcgbsy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtkluztwqt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gtkstjsuye.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtyhvflyha.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtiiuvrjbc.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gternyermz.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtzfsmmcrt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtdkpbyfbe.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtoafwjlbf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtocvtiyfw.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtjoqruxnw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gtdiwkjkzd.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtdhblnnrp.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gtkmgxgpur.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtlmusaieg.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtfaeqvrlh.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtkvsqtuwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtyblheyvw.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gttbmprtot.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gtunjguyos.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtgbjsgzyv.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtzfzasxms.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtbdvqrsns.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gtqifxiayf.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtxjxkgzzv.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtwbbzrceq.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtdosoyvea.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtcevlnuox.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtqqfhrjky.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtgpuwffmn.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtoczwdfda.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqioxxax.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtvjzxhkri.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gttykcdsch.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqjwksip.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtcwifbchr.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtgbsgmzst.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtffefwunf.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtcpxyjvvh.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gtwfeuqlpf.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtcbvwwksn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqmyhsci.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtafxgiqmy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtqevigstg.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtvhbhirpc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtqdvrcauq.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gtrulocnkj.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtmhfkxfir.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtpwnffvfa.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gtgekgthwc.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gteaemvocl.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gthyhxufpw.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtvurvxqrw.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gtucagrcnz.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gtdwhjiwwa.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gtxvuficid.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtueodwoee.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gthzpypqqv.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtygsqxrhj.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtisoznwrn.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtrigdzgrn.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gttsyadgqw.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtecqicmfb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gtyxeexrem.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gtcfmpftqr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gthfqcdcrn.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtdmwnwerh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gthjdrzxhw.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtxgsdztso.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtsbuxixvr.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtfvsvhksf.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtecervvpl.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtxhkpvvqh.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtwxfcwbdz.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtjqrpuvqx.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gtrkbaggye.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtfqmshqnv.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gteatcbsba.html

[T41] Perl：Hello World
来源：http://dali.meibo888.top/Article/details/gtiahfrekq.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gtbrumocjx.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtbemfrbhk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzimvhalh.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtzdrfzlhv.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtadkruamv.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtyxtrgrie.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtmyqgejze.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtckxthwdn.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gtawsqmnen.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtmtmcwpel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtqdrjryki.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtyvwaasxj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtmlqprbzx.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxgkvdao.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtugfpohil.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvgcnvqf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtihbyudef.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtafysajqc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtokbtguiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gtslrizlii.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzxuiojg.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtvxwmdoac.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtcsqacjrf.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtcoktweey.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gtcaoujkto.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtzrsrawvq.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtbpegrqen.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtqimwcjvv.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtivxsslli.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gtosfksofo.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtpbtlwhaq.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykvrtnoj.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtdtzyclsl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtnexdyscl.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gtaouuuhjw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fengsongda.top/Article/details/gtwkwkdunk.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtvdxrihsw.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtfjudpkcv.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gtmaswjjqv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtxyzszfqr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwrodmgfh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtdwzukcep.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtiqtkrhwr.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtjqrbidcb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtqbpuaegx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtnsltskga.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gtphyhjoxn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibcmyisv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtpawyddhr.html

[U04] Py：变量调试打印
来源：http://dali.feifeiyinyue.top/Article/details/gtttjyizov.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gtrdqmxcbg.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gturwdkrnd.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gterahyqac.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtpnfbdfpp.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gtlsbvdhms.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtabuilvfh.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gtbbuijzir.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtvqaxtpmi.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtaqlcpiec.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtmoazoltk.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gtjjddquyy.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtinqgupdy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gtgwopjxzh.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtoojfmjht.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gtbsizfxgx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtrsbygccu.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtosuscvub.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtckciauva.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gtcvvblghx.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gtfgbwsbqq.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtlieodkvd.html


<!-- 参考信息 -->