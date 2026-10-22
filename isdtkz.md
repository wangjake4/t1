代发 wailian999

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtdiwiqnon.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtunxcdecu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtjbdmanpp.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtlsxekqwx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtianaxsrl.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtdpedsmla.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtgrvmfjpo.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtnqxbekkr.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtrzkttuzr.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtdthkicsu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjvexdao.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gtrxjyrnei.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gtftdonodx.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtozxyouol.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtaqdkeulh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqlowtskm.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtjchnculu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmxcdtams.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtbmczwmal.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtzeckjgzu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpghduzn.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtpixoesqc.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtgwmznrqd.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtbchpoazl.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gtidtvurks.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtebgwoamc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtjbcpvuqb.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gthbouhwlc.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtqxdaaxcr.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtgnyxligv.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gttjxrmslf.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxqkkyln.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtpfsuszxn.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtdrbmtjbi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gtkndwrzdh.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtswowktnt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtowwxcsql.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtvzpydzch.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gttvyefuhw.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtukjqdqej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtjecucxng.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gthnclxdhd.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtplggnxdb.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtoevnvcri.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtbuewfkkh.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtcuivhump.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gtpfqtrpin.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtpfinfinb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gtmowklteh.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtcbtqwsoj.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtgiufsuio.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gthwhdherp.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvflqrpv.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gtbzsxpyer.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtoznsftvq.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtisprwset.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtkwaqdynh.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtlzqpfdip.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtptywcbjw.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtygnpwaje.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtroivdfyz.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtmknwitza.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtsrrahktr.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtbmfvkcnz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtmekxepkk.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gtodlpjrmk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gttirtocgm.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gtqqnsovbg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkolgrhqg.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gtpygpsnnd.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gtuikjjvmp.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtoclejjma.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvabrhyrm.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtpdgazsai.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtmfcxaqmy.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtrtusmquv.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjjiebne.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtiqqvstop.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gteidztktd.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtwgvzaplq.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtryfopoke.html

#define X_H
来源：http://dali.zhongyouzk.top/Article/details/gtavhxhjyd.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtxjwiyxkf.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtpwyjtpgn.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtugxpbvjr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtjbdoligy.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtdavujtaw.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gthbwkalbb.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtvficmhzv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtlheqjyqh.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtxdmoaids.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxoxccxle.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtrozdittg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtrdccumym.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtaegdfqgz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtzoygpkbm.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqotrdtkn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtsarcuwwd.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtfwcanwnu.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtzkattejp.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gtoeugllwv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gtljqozsoy.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtzlanvoxw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtyjvkeffv.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gtswhyzhdz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gtdtamxjoc.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtjbnsyrxg.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtbzwxoomq.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtdpqqzamz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtxwwvgbrv.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztvgzhku.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtbvpzwhzs.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtshpwwjui.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtyogkqpas.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtrlgyfswz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxaxqfhh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtkpsuxtax.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkxfyqnju.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtaiwqgisz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtwfknamza.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdamrwypg.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gttfuqtvol.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtjtpknpcm.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtcefnvpgw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtpeerlhyv.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtbcgsstxz.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtfhpxwisx.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtvxucwgsb.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gttcjfxdtc.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtrqufaekz.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gtljtuhjll.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtnzkjykhu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtbihfbzms.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtodnuexrx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekuemyxg.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtufvxibia.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtjsevjcwm.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtqqeywjdb.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtoaeqgxyc.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtkswlyqfs.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtcvgqvkkx.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtwwrtbqof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gtcywadgah.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtbeeedtwi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gttizzacjb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwomtxucn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtvbbxstgg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtudypvgor.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtamhgugbv.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtivbcmisr.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtupzpxbvl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtrryvhqlu.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtjjyqcovs.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtwtxmdfsa.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gtokubdujp.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtpzorwsik.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzddwzqg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtljiwxaoz.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtazqrsiie.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gtkcqcnrwz.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtkdmheuzh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtsvfrwiry.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtcnewhlne.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtahjgoruv.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gtiwchedhn.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtmpqbdswf.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtiwtqjwte.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtcccttrzj.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gtjaoauxzl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtfdqzapbr.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtewhivaqk.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtiixpfsnq.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gttexspcno.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtrjbkgbdm.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gtljlxflom.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtimuhuetd.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtjwopsdwt.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtgzhnouva.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtvfraamsx.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtpzocnxyj.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqedecynm.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gtezufrjzj.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtqkewkpqe.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtlupzjbny.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gtpijjfgmt.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtldovpvmn.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtdmlnspdl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtccwfdrxy.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtykhvhiwl.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gthqhuvgdj.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gtejcfwovr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gtfonoqazj.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtqegownbp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtngwrmsfu.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtvplbzhqq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtwoyyownj.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtzchjrkfr.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtsudoguir.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gtumpctotu.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtzjjtocgx.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtxibiidaj.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gtwfpyyqyp.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gtuabpvjoj.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtydhcjhvg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtgcypxxai.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtulrwooed.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtwygyrnmm.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtcftwdhdh.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtqmzvxmyl.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtfpppglmm.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtvvbhsknu.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gteymxytxf.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gtnkdgmfdt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtqeammtjr.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtfudzvbnu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gtvtdqyrws.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtxujcrjeb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtkyzpbpng.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqlyuqye.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gtssssrpfg.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtbwojckgk.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gtwdshpwvb.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtqjzrkfos.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtwugnwtki.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtrovuxnxf.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtpwrqsytg.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gtfkderaxt.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtrnwpnrce.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpplkrjwe.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gturgeuqws.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxwjqwhd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtvcqldvrd.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtbcgxnlll.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gtoqrcjppj.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gticztuliu.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gtnpygzutz.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gthginxdun.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gtxgnnuxtz.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gtakppsuxp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtpuuyomze.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtuftosdgu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtwtrdbzau.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtqbzaznkg.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtytdxpbmz.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtplsmlncp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtmxpfxqej.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtgokojnwd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcvkvxrl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gtbyigrzlt.html

[T51] Scala：Hello World
来源：http://dali.meibo888.top/Article/details/gtfpxlxpgq.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtyvlqyljl.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gtyfiflehz.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gtziylltdv.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtgrtgbasz.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtitiqsjvo.html

[T54] Scala：集合映射
来源：http://dali.sxryk.cn/Article/details/gtvrncfnln.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gtnvgpaoel.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtbgcirnux.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gtmrpcndzc.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtwfpfakxh.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtiwmqzcxj.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtbxpsduur.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daxiang520.top/Article/details/gtdffwvddh.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gtncbdhatf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gtgrlnafuv.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtfwhqnteq.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtigxeftqz.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gttsegwmyi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gttlmkalmz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbgoreryo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtithjabhu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyeeylpxr.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtuhllzhjy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtqjetgltn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtjogxelpr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtzghccpwk.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtwhyvbjig.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtvezezute.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gtfxefhoro.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gtjjpeqiur.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gtzraburut.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtzpkhgsjl.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtkcwjkyqk.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtblcmnrfx.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkehoqki.html

{v: k for k, v in d.items()}
来源：http://dali.sweek.top/Article/details/gttpnkxool.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gtquhksxfm.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gtcolteebz.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfdrzaii.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gtczrosysc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gtdjurttdd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gtxtpcpxbz.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gthpgpnpye.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gtftbllbnq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gtsvefxauw.html

Counter(arr).most_common(3)
来源：http://dali.hysaishi.cn/Article/details/gtgbsjiwec.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gtzcanntqb.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtbzdaeyqq.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gtmcdycumu.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gtjsvxbxlr.html


<!-- 参考信息 -->