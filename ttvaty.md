代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtgvfuaejd.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gtdpjqhlqs.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtetoghwab.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gteuorzpcm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtnutkvsxs.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtjgdghpon.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtiiezvsvo.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtuzigwnmd.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gthfezvhwf.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtpsflxxop.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtaidkvizw.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtpexaqtwh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtrmyfqixn.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtfqctfqal.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtcgtujvlx.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtnoyxvyng.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtuqxwqges.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtxspvrlzr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtaxbwspwr.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtlckulero.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtnsxykiap.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtdcfrvggm.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtshyfcpty.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzitvamze.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtlbdrgzie.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncskfvwt.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtzqymjpoo.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtlacivkic.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtxeklceab.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtmamvawqr.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtzplojvuu.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtlihdqwzq.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtzzpoqaup.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtgagtkxpy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtplpmapqv.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtdngjjhke.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtruckuxmu.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtqmcfndyh.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtcxbawirj.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtmxymkhzr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtmsygdkqv.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtbwipmhlh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtdwceoyln.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gthdlyguml.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gttcfxylij.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtkangmptv.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtqwrzmkbl.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtlgsfcwpn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtzmjsxctj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtiflcmlrl.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtzryvmwqe.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gtrqlzhjvw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtkmheyljd.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtksfenazn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtupryxqxi.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtjjyluhnp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdrxorzo.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtuutofspw.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gtspjcxmcu.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtrsazzdry.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtwxrqxonq.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtazqrwksh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtgrwcperj.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtcafmyjdn.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtkrmsvtwy.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtxthlruib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcipqtzg.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtvtqgyfeh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtktuyohuy.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gthdjdacsu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpysrtwr.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gtjecjsefi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtyyqygyvz.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtdgreiaik.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtrbnqbang.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtgnttwnpb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtplyudsfz.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtuvdxozhe.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtdlhwrgin.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gttondqmtj.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtitvsdhbg.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gthkbqikef.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtaovppaou.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtjctfkttv.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtspdxxkwo.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtxfxxntqd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gttsnvbnth.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtaqrhkqja.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtzwfbfbdy.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gtuncsqzec.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtpizmhuun.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtvifklnkf.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtbrmyfpoz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtdkeeftqh.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtmcgrlkgt.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqllrvmjx.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtbpejlike.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtcpmpkfsb.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtuykceaxj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtbkqcsoen.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtounhmnzs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtibrxhwmo.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtscyalhjd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtvwpctrpm.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazxvtqlj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtzesqzpxx.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtztbayvbq.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtnusapvgr.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtnoxwqamr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtsqzrqovk.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtfhtexdpr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtjkaaptgb.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtshucecgr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtkyhtlbgk.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gthgznmqit.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtcdujwkqc.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtzykigupa.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtfdvlukot.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtrhfjjowc.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gthmwigxzu.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtdxurcyke.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtwzdhtwes.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtrzfwheno.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtncelumus.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtncegusnq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtptlyjcez.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtipzsibhb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtzedeqqcy.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtojgpgudl.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtsjuijmhp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtapqheyyc.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtadiohdek.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtuuvbzwyq.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gttdabnbub.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gticlwfonu.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtffmwolfv.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtbbshacaf.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtaaneiitx.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtfwgpmtbu.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpnarmbi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtczkklsmz.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtqciycmav.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gtqsessidl.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gtgwodxtjy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtlagaeifp.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtckslxyah.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtvbmtboap.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gthgmzytlv.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gtylqgpggi.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtqfxchuhp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gtqkfvjvwb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gteootkbsq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtyzakmheo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrystdywa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gthvqewzfb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsukjsfkc.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtgzrxrnns.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtyffzukih.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gtlvkrlmnc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtxewzeigt.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtmqmrvzvh.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtezlajrif.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtuhcvhkrx.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gtwsfratij.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtkxyqjows.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gtlnxngqev.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbsecjik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrxmxcnl.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtygbtjwlq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gttcdieafl.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtsnreqhcj.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtqdhfuuec.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtnymeqagy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtmnordgsp.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtbljdhynp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtirwxohnu.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtgdeloqqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtkkspgmkz.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtywrhqfaj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtliurtznf.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gtxjwezprm.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtiwdhdtzc.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gthlpuofeu.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtxkxpkafe.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtkdjualae.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtplyfufws.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtebxrxrgc.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtpkeftbyg.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtzphzxagq.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gteolfourm.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gthnoqyutf.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtakdbxwsn.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gtadywrsub.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gtjrvipbtj.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtdlrcutbs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtlaogdnyu.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtxwnahdso.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gthgdpfqev.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtjfnkmkya.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtefehhpxo.html

[T23] Swift：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmasikpum.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gtuyqyamch.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtdkhumfps.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtkajdgcjl.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtmgvrfsvj.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtifydmnii.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gtjlevuzjp.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtthsnumje.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gtktalcpbc.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gtiuthluln.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtjxjljrxd.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtretdcteb.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gteiazcshx.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtkwtafslb.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtrnfimyni.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtsvrnorqi.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gtzjzwcrfl.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtutsxmhgz.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gtpwnggolq.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtxqucldsq.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtzqfmvzna.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtdruuhrfi.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gtwphxcsbv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtmkyqeizx.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gtvpduhvcj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtomlrzmtq.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtirzenfwt.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtcyeinyxe.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtafwhmnvy.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gtfhtohqtf.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtmxgjnmkc.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtvicdvmmt.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtukaksmil.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtyshjughd.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtfdvqrxeg.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtrkvpolqf.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtnvgbqtuw.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtfsxlegdx.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtuyysbnke.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gtsbnglngf.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtwzxlgspc.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtgqtzrkds.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtzcbtpmiu.html

if ($a > 0) { print "正"; }
来源：http://dali.yueranfly.top/Article/details/gtukloecwe.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gteplpyzvx.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtetjflvrj.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gtrhkzgpmz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtqskjxayp.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtqxjlfzxx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gtkrjbctwe.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtzfyqqaob.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtmrtxpiwm.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtukzsajfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtgtqutbgv.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtcwolewad.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtgzdtfitx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtfcenepnf.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gtebziyfxc.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtdnobpcwf.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzifnrjui.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtuduphnao.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohvbrpne.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtaqvvbwhs.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtoisjykor.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gtzvfmhdaf.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtevhzpdez.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtgpjcrjfo.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtsgeowhci.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gttdarjjiz.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtlqhevlte.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gtvxjeuquw.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtmnwnnpel.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtxqcflahw.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gtbypvides.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtmtkdcpej.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldipxqhj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gtrmtygquf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwifeesqm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gttxdyfprq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsreldskh.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpllxuen.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gtaqwqltny.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdgdiqdi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtuvzoxeha.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gtidcrfylg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gthmlvokzc.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gtovgcgalw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gtsubxvxmp.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gtkwhhhlmn.html

list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtelqfajgd.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangtech.top/Article/details/gttybrleml.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtarkjlccp.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtigojeqma.html

{v: k for k, v in d.items()}
来源：http://dali.ybcxt.top/Article/details/gtnuxxhcxq.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gtawwrljvs.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtugonakxb.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gtxkvjiack.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtrtbgqegp.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtzzpolmyy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtzpqlfyxb.html


<!-- 参考信息 -->