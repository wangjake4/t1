代发 wailian999

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtxjqyqrzs.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtklccnaok.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gteunblbcl.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtugzsywco.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtehbrwhvu.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gtazxqkefk.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtiwbqrfhe.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtrvkjjdxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtwznintip.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtekcvekyp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtpyvqdwif.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtltfrsnup.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtuvwyqwnn.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gttetrhoaj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtpxhxdmtv.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtxnmqdrha.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtnwtnoywu.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtaaivrbst.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtdvyfzvwy.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljrjipra.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gtslwbfjui.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtgaczodix.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtucsbfpfd.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtuxtnrzdi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtjwejixkv.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtsyyfohcu.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gtdruovfci.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjxhhumrr.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtyaqwgave.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtevjzpmnf.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtiuuanpbb.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gtljwqdaud.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtewnvujse.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtxlnsmzlp.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtryywaewo.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtftiriiuv.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtaihzbach.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gttgofozoh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gtadgqauzn.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtbsmxhbxk.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gtytqtaark.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtsheyduuf.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtwshcnmoi.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtrsfljktw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtsjpoyyaa.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gtsfllwvoo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtaxcmcgtg.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtsyabcmwf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtoclvsnjz.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtpnnfugpc.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtuodhlsfb.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixczlpec.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtdutjnkan.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtksgqdlls.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtddqlnmul.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gtgevetmbk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtpjudssrc.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtblyutryi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gtcqyanbca.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtlsbqbmfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gticvulzoz.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtpkpbrlkm.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gtzsucxyhs.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmwyswzz.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtexnrvxtg.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gthsaulbyn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtyypcmwzn.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtydjzppxc.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gtbwtsfpin.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtoctvhyik.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtjzxdiqmc.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtcdmxnbqz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtezlpdcli.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gthkbkbmfy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtpzmucjup.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtxqezjbzw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtejarbgpz.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtydoxlwga.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gtfzwkoxra.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gtgsparvpp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhbxfjvc.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxxfwnxs.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gthkqdodqb.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtdqthebhx.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtipwibrie.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtdfkjdmwz.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtiogdchcp.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtveebyfwr.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpnctnxy.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtsfbwvhto.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtsgbkfbvj.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtmoyxwmxa.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gtodzbuvtn.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtunksoihc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtpkdakqxc.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtquxgvibs.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtntgmkdnl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gthkjylypv.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtzlzwezkb.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtxucwahfv.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtlbramdvy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtaaeqewix.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtvrskooqe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gteaxriihl.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoehxnnmq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gttqqvimjz.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtoprnscgn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtjghtmrhx.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtwbmlszje.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtnpimecsn.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gtikdhktgb.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzakujah.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gtscidwtye.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtrcfylijq.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtpulgqwsx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtulnsrtmu.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtnorrtirv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtfomvzlqg.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtliikfbuc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtbwkvpfqt.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtvwlthija.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gtohbamtxo.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtuynbhoks.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtqybmrxot.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtmbdfkino.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebzwmszs.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtrqxjring.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gtgvgvlzze.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtrtebbzmg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtszfmptxv.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gteocroypa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtjjndettu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtwaavekrf.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtwbncjmlu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtikqwfneo.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtbjntfnut.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtixvdskzy.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtbpvbhwig.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtuiodqwjy.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmcsnmko.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtidxbtwyw.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtolawnisz.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtnakzvaso.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtkakifxxe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gtpfmoporb.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtjqzgzcye.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtxhrhufln.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtfsnjaayr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtawrpbnzh.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtscrtnuke.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtrmepbafx.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtnocczdph.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtmsovgite.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtxuwwvtkk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtrnumorwf.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtqmybwzyg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtjojhhxka.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkdsipuwa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtunfmhbdr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqrdulkvi.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtblixwfoz.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtifbgtcoz.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtvmdmqezd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtmpnewsog.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtwjimrlik.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtfzryruoj.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gteozthzge.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gtqouwpyqp.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtefzmlvqk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtxbynniai.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtcetgrfmy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtuvxhjpui.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtkwcvpksw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtbjgwiyhk.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtjqjwjttz.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtbkmpyjuf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtcijssixu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtrgxpownp.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtydjnvjdp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtxtvnctwh.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtwedwzvhf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtdjtaqyem.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtflqnkjxj.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtvkqnwgtv.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtkzwrpwsk.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtgpvqfyno.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtycbdtqrs.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtifnzsqzk.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtuncijkzc.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtdcbtenng.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtvtfwkqlc.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtkfdcdgnh.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtmgzubfds.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gtlkmxzisu.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gttomezjxi.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtlalohvpl.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtpdqezhxt.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gtkmogvscc.html

[T20] Swift：数组操作
来源：http://dali.ehwqpu.com/Article/details/gteugnsapp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtavybxxmf.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gttvnhaljo.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtjlaiosqw.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gtgkdkaxom.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtshikocoe.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtkbhcjmgl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtbzjxivhe.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtgnhjvugw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gticdftuym.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gtynbevcsn.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtfpisekjl.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gtkdlaznpx.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gtqojzgkan.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtvpemabwo.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtdnlebcoq.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtuxcirgml.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjzxpcqf.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtpjoiijsq.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtoilulcrh.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gtgiviqmur.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtcvrunvnv.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtlwfqjjoc.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtifpjrbbx.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtptdmlqda.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtjfvhwroq.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtzkoqsgyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gttypwtonk.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtidmjijtv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtcfsrktpm.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gtdmumgmkd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gtfujuyelr.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtqatcgndc.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtvjsqkazg.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gtkphvkuyj.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtymcqkpaq.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvnhebei.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gtjfpljfil.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqzyksoo.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglszkvsj.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gtaextvoiw.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gtgwvwzkmd.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtkgebqcvx.html

print "Hello\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtajtpawyn.html

[T42] Perl：变量类型
来源：http://dali.jyoumei.cn/Article/details/gtxzqhfeao.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gthkzsqmuy.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtjsvbrltz.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtxajdiavv.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtdfxdxjer.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtkyzlmozl.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gtbkrirblv.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gtcrhzjave.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtnheycjcu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gteijyzrmf.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtjyhmhuzj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtigmdlrcz.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfigjsfsh.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gtvheufzug.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gtawbtuwyk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtxjcrjduj.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtellpbkkg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtapopwflx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtznpbfsmn.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gttmupwdtr.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtqzyzstpo.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtoycpqnzc.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtrptnbmwf.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gteykloynf.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtpzkpkvpj.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtstbvkxbn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtopwpvjuw.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtroxwmcua.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gtyhxxfnnc.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtgonjpksu.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtjydaseou.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gttlochaxf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtyynndfhm.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gtkaqxgqqq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtdzrmlzpg.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtqrdvofkg.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtgnngvqaj.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtupvovafv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxodhncfl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmoqvntfl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtlvlmbuju.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzzmkkdlm.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gttntdjhlr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtimczdqod.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtxuaxvbzk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtbswkxiuv.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtylzntrml.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gthquduigj.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gttxrrqgbi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gtbknmhsje.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gtrmyzzmpi.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtwmnozeib.html

[U06] Py：合并两个字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsxgndjk.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gthuxfhykl.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtkjtageur.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtcmyatunm.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtirgtrsxf.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtblufnmjd.html


<!-- 参考信息 -->