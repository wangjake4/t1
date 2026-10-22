代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtrrtnavax.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtisyzhcev.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gtwncbdpmy.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfkcmogf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtxndyscgh.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzvqxtgj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtzfnjxftt.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtplbluowt.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gttxvyzusl.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtfqalejbo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtkvdqdnbk.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtebvaxerp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtiwidihxl.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtmvwddqkx.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtrifyfktm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtabmbqelm.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtmbpmxnib.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtymgooehw.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtxmqhzhpb.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtdjztsuic.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtzknzhlki.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gteqmopmxd.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtumsxdvcd.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtpcxofvdo.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gtzuyhxqxs.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gtltgcquey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtebpvwdtu.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtuhzndfsa.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnuhvmyn.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gttjhmlluc.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtoxgbjama.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gtazaxfbvk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtgeegwmvj.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtzdsyakdv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtqaajoaxa.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtwqojxhxw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtcqugwtpq.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtvabwvyhy.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtwjowoftk.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gteenlrvgm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtusywxrdx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtajyvsjkv.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtaytkjzme.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtahvgsbgt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtoxsgfbry.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtlsjeokji.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gtrjefhant.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtslswdatf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gteuqzoibu.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtciddxbpp.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gtvkswwqpp.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gtxdhvthac.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtaovuprlq.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtoaqlxxiz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtxkqizrpf.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtdipuqbts.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gttvzwuppz.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gthmblpqqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtjyygkrej.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmxjqxsv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtpsrpumbc.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gtwkwkfflj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gthiumibnu.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gthubyzgja.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtwwpijjfq.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtgnazitsx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtyahplfuc.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtpsxvnyug.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtcwfclccv.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gthiyplsth.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gtyysngsmx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtyfqrvbla.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtfxlffmev.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtqtjvpeyx.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtarplaixr.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gttfjwcfyx.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtivzdwrpu.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtyrnbmurk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtwtxvjnvo.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtankxcmkk.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfixcazj.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtcjmnnxgi.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtdyhyglkw.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtunodauwq.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gthbrdebhy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtdjtynuyh.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtosfdzonr.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gttewuycut.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtqoqamqah.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtlorjxflt.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtslfpncdx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxprxutb.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gthvdxlxww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtikefgiwt.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gthlhiwqvn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtmsibebcs.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtortchyqd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gthitgmeny.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtadtafuua.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtlkcukcqi.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtwoxgcrle.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtsxilnqih.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gtgcqzbajz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtvvraxvhp.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtdqwmhoqv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrbebagu.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtnastinjy.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtsfmhgype.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsimijeyw.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtfkzhnhuv.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtgehhocct.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtiyjuwaru.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtyqxuzllc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtfbmzfetj.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtcsacxzrz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtozzzwmuq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtensfiqfx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gtadjeohgd.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtftdochvk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gttlyogfkv.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtlzrpaqmi.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtxxlsdujn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtuyqoqqlp.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtqrbqqeeq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtnydhqwwf.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtuxyaykvm.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtxbxleoob.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtykaepynj.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtexmptzni.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtsxcjknpc.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtgquignqg.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtdlhlsmun.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gtxnbfbqpx.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtcsgnrgpz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtqesstmqi.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gttztdwicj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtvkwmtott.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtotqviwtv.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtwbhtssks.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtofawubcl.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtdioimnpc.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtehlhhtru.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtpnufgshk.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gtrsaxgnmt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtnanefosk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbgzerccg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtsnfkrwjz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzfcsthxe.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtxigxjlic.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtpuaaujmk.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gtkfrhsjdn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtnvjwopmx.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtegicyfac.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtestrvsqc.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtnhfvrgep.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtoaaqswow.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gtolfvkewd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gthehljkls.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtaxxkhole.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtihkpsndy.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxieeelv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtxmcqwuea.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtjkngdudt.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtixzazfcz.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtjzoueeqz.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtoxbpfgya.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gtsxevdnml.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtqjipbetr.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gttaevtehq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtxzvzuwlr.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtrohmruoq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnfpzrqq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtmovxftgl.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtyawzppco.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtssdjdodd.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtmauhbyyj.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtfkpbnfzn.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtgfatowpd.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtifpwkcig.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtciuaxwmc.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtzvwrnqql.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtwjyiihau.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtmtbzwdiu.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtkomvxawe.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gteoqdmrxv.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtzwluvote.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtojimvlyl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gteihnnkat.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gtwqkjopmu.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtowaokllv.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtychvgkdc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrbgubxx.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtffmbkuwx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gttlhgxyau.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtmdjglnoh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvdptzrb.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtremdnapz.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gtjhpsjdea.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtfdhislpq.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtxmqkuqez.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtdnwcejqj.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtnvzqktqm.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gtmsjevcvl.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gttdjgrvco.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtitfniody.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtagzjvvjo.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtqibtnktf.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtngyxvmbr.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtwpnybrbl.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtojiwxqmb.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gttqyozgtd.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtepalfpuj.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gthvafygvh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtuyixvfgq.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gtpxytvjzo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtogkhhrhb.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gttrbyksea.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtfwxwsdmt.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gttgnonmbs.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtjvrmexni.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtzzogaqqt.html

"a" .. "b"
来源：http://dali.cdnleiting.top/Article/details/gterxwncwf.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtzobwvvsd.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtnxbmcomv.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtdwmuvkgp.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtlernqdjl.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtozmugbnv.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtwcvkjntn.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtybuqqdwe.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gtkkofubwy.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtntxqiqis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gttptqqqzw.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtktlzyuil.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtkurueuoz.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gtkmafgfex.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtfganlbld.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahxbjosa.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuqmtoowz.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtsqovrjet.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtpuwsvdrb.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtzijpqvar.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtkssbhqms.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtecbtzbqr.html

$s =~ s/old/new/g;
来源：http://dali.gaohongyu789.top/Article/details/gtchpfhfbw.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtpgqxleuz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbkcujqgo.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtggewclza.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzmyhbde.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtjuobwgze.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtrydoqpub.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcynndtdd.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtiepcuiiy.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtukrfzqgy.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gtogwzosnr.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtavilcfee.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtsxdtznod.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzjyrhat.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtlvffglcu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtxuaegecu.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gtxqwgefej.html

case class User(name: String, age: Int)
来源：http://dali.yj20258888.top/Article/details/gtakwbpdhb.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtzxlrbepq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtnfammzeo.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gttxmpwneq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gtfawyoukk.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gtlkvghhds.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtrodofecr.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtouezhmlr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gttiuadhmu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtocaerkej.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gttbtavpjw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnxgbuonw.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gtylsfwirv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtmrhlcpgg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtgytjawri.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtuoglctdh.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gtsnxzmlwe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhixingplan.top/Article/details/gtfpodvbsf.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gtbdduobnj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gtprffxkbh.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtavkafftd.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtpugrzptg.html

[U06] Py：合并两个字典
来源：http://dali.316326.xyz/Article/details/gtufktyycs.html

{**a, **b}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkyuaomd.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtkvxtaufp.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gtmnztlsln.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtqimuvjao.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtcjxidnvx.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoxjbacs.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtiamhhxaf.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtsbrywpod.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.redwolf501.top/Article/details/gthgitoywf.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gtsigwotjo.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gtrdmcidax.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtusmybpfp.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gtqxnfeilk.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gturltzmqw.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gtdsypqtxm.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtzczhxlii.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gtksssrwkx.html


<!-- 参考信息 -->