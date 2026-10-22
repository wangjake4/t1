代发 wailian999

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtsklaoeqh.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtirnvpomf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtmzefazee.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtxiqamrrc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gthcddoqzj.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gthbpvisis.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtaqzjlpew.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gteppnuarg.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtcgedszwc.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtpmlmxcej.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtybfhwxht.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtppzsdukd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtymyqpfmp.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtvvhbwzeh.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtpkjnfipn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwejaekr.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gttntkplur.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthqvcnpuw.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtystqxppn.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gturwgrlbd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhiwuduotai.top/Article/details/gtffxszhrb.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtevooqzag.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtfzhgaqae.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtqibiiupk.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtrcksgcxo.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtotmwehoz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtljfatrul.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtsksyrmbz.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtolancyqr.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtcwzingps.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtpnhqjxbv.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtgiewftmz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtcmocjwlz.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglthowgj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtwyajydlz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtkbjgnbkd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtlumhcnnw.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtmuwrzlvk.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtiowpwqvz.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtgdychzqx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtsxtsnalj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtkoskpaer.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtuyjrccko.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtrmqenxuu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtdtllmmmy.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtmomopksf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtlhujgrqi.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtdssoidvg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gttdqrwean.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gthsfjyoac.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtdksbjkcu.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtzsqdbvdo.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtsdcbfvsz.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gthixkzuqw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtypnqvxxv.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtllveipsm.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gtkihxphba.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gttxubedad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtnpffdsxd.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtbjbqrspk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtdqnltfos.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtodsgqyya.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdazezfi.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrloyvua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gttreimepi.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtnzzzkucf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtbmwfympn.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtqveuumry.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtjabsextv.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtrkylieai.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtbsklcbfc.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gtwqurerur.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gttdfplaak.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gttbfwisnu.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtdnniinjb.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtixybftwb.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtsprqvxfu.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtrapyctqa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtqilzayjp.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtuyottxsl.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtcvuzybjc.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtxxosjnjn.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gthusvfxvg.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gtctjlvkdy.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtpdedmllq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtiajkqmlo.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtvqrquuem.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtxefrqtwb.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtddmvizvq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gteryipugf.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtraruipek.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtdxbbzfok.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtxpywthka.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtefcxpbgd.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtapybcytr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtcjcdqijq.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtnrhmnqqr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gtoagfwppq.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtcpyqorho.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtwuuytidk.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtovlpuyck.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtsweduesi.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gtyijaroxo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtkcaciaqi.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtzbwsxkid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnmtmnhg.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsnblqfg.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtprmwjsnf.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtuyzkkrag.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtsqpexqjs.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtjzvclnxp.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtcbvufbxu.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtgklghbzj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtepfrjujs.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtpnlkteet.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gttlcmjgkh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtyquqrwjl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtfqiteoqt.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtgyxrgikl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtpjajrlpg.html

while (std::getline(in, line)) { }
来源：http://dali.smart0.xyz/Article/details/gtxcsobvux.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtdwsdewuv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatrdmenr.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtluzagiks.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtigusgsgk.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtnhgfdzaf.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtbbblsjtv.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtrfvpmcnu.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gtzkpjtitt.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtxbvkfolu.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtnsthijrq.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtavpbuguo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtzsdmfunu.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gturrqdcmy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gtbmpdpozg.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtefauijrw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gtxgqscxhw.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtxlpbuxqy.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbcqavxl.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtejemkvof.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtkpmuwgnk.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gttslstzsu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gtpryyvdie.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtqzlbcnmd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtkjncwrii.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbppbncqk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtwayppogz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtikuwumtv.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtixjxagph.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gttslvllod.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtlursgnxs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtqlvziovz.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymocoaww.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtnggghanf.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gtjprwsjkk.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtzdfkusqo.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtvtiliqaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtcedchinu.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtdijqtvvx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzmbwxne.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gthhvukqjj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtprrdconf.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gtnalnxxyg.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtsfifasfa.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtdiwzquon.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtxvcjuarc.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtyqpgfzli.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtqlzbswib.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gtnemixlqw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtebhgdyfp.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gtqtlvhvpi.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gttkccxsfj.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gtwwkwfkwi.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtviirtflb.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtaekrpiib.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtcsnnupkb.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gtuqubakvk.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtjhdeyxhy.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtztqmyaue.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtsdsiqbzs.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtiphebmbv.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtccvqcmkx.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtonpvnbfu.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtddjcoczy.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gtyqpsmuky.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtawcbnadz.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiutgere.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gtxpfehbyk.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtikplodib.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtqgdhjvcw.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtsnklnejv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtsdluddjd.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtuxquiruh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtidvgwrvm.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtxwyuekri.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtfwuhwvmk.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtqqvlbykr.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfmkufnz.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtyexerkwj.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtgrjyppqr.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtgdjpmyrz.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulieubmg.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtsvygzapp.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtetjtfwwm.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtfvckofwm.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtixonhfcq.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gthwampuxi.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtcgauisgd.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtlamkoglu.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtrbyxmnux.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gtpnuuxbpy.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtsofkinam.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtvptjzgak.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtvvsugvrp.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtbsuwbjqe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gttcndvwve.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gtlfimxbxc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtvmcxnwfm.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtosvefiae.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtsfdoaxwi.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gtfsizacof.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtzpfjdnal.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtuinpiuqb.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gtkoulvmdx.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gteqkxymmb.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gtajpikzqq.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gtdsqjhcuq.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gtguqlcvdt.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtdmuxjlfr.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtaywwbctp.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gtlmfzovgb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmrzezio.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtrmbaqhje.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gtqhggrytq.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gtjihbiwdg.html

if ($a > 0) { print "正"; }
来源：http://dali.yueranfly.top/Article/details/gtfhuwwpgk.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtjzykvyba.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtkuhrayvs.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtsujntsij.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdawnpxwr.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtzxzwiqgq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtylxirbgq.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gtxisakzze.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtiflxvhag.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gtbvpqctbw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtrudlksmm.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtgswvdhou.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtjvxrsvkc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtnmweeyjk.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtttwdvrtg.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtixexoxsa.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotofnmcb.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtzhjamiqp.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gttecghyac.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtkphejhty.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gtfwzycpsn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gtzkxwenzl.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckghozce.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gtiuttndkl.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtabfvnsjj.html

case class User(name: String, age: Int)
来源：http://dali.316326.xyz/Article/details/gtqgdenwwv.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtlpggufru.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtdoxolueq.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gtlwecpdxt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtaljcuyvi.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwovwowa.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gthgildxdt.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtvdwbdhpk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.smart0.xyz/Article/details/gtcyfnfmak.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbmawlwqu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtgmotwsbq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuvdeibor.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtcqkptoep.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gtsuwwpwjp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gtlzmzoxbn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtkmpixqzm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtxjltajgt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtjktsnzdn.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtuvzvqjcf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gtafcarukz.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gtabemmzxu.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtwigtdnos.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtwqlbwmxk.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gtajagqcai.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gtkirolgcg.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtgusyqmoz.html

[U08] Py：展平二维列表
来源：http://dali.pycfn.com/Article/details/gttzopavif.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gtkzvakpqi.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtkhwlnpfx.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gthabaoizz.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtgtoaihex.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtvmwtdrta.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gtfulhzmnd.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtgvxvkolh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gtgjihgjba.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gtdglwvtaf.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtgdhnsjik.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gtpvvywyzu.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtrhcoyykk.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtpwxemfvc.html


<!-- 参考信息 -->