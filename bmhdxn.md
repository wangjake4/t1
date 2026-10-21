代发 wailian999

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtlcloyjzp.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtxlhsjvju.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtbstbjhsp.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtxniedwxw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtyyalxnma.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtdfmlxkvf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtpvloekez.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtwemtqrus.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtcmglfiwr.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtdnwjsybi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtxucjlpbm.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtzvjikmzv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gtawsmeimp.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtwcuxstyj.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtjrtgqwsj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzzoekjpb.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtgdrpqtwo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtecskncqb.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtmlnwixej.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtgyxzxfqu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtsubarvkl.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteajxtkl.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtiabikhwf.html

[S03] C：读入整数
来源：http://dali.dianchejie.cn/Article/details/gtvcdmampw.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gtqlgvjsoh.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtvhqarbpn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtxsuugjun.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtsmcdvhvp.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gttboutdpe.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtncutllwd.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtwgrkhgnm.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcgizdnv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtyithtkam.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gthpiysyko.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gtjtyyvyry.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gtqdxhewcq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gtikdiytah.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gttnivqabp.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtwqwpiury.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtzjiamchv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtxnvcojwr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtvejzbdub.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtyqrkzxet.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtazndwddy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtszekadxu.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtwzxeibdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtkzotojlp.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtpyanyrdb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtigezcsgr.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtcbcgishm.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtxjrvszrx.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtjbxvdrok.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtaicksorc.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtafglptzv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtyorwsnbf.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtixztujnb.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtmxcmovae.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtabplmkol.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngaqkgkz.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtldahdoen.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gttablfijz.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtnxqfylqb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gthtvplrcz.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gthewthxia.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gthurbkehs.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtxijgnzjw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtvevpplnz.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtnbxvdvfi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gthrgfkhil.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gthuvrtcdm.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyrldyll.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtsaijqgnr.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtykkzmlwn.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtzqezwfyq.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtccjsxeke.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjvhncbqs.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtzrlduthg.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtuysjeeen.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtygtwgkzo.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtuqyqnint.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtgcmehfzd.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjbygqbl.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtbsyimslc.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbtsfdvc.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtjcixcybu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtppoeuxtz.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpzhqydo.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtpjfonwjn.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtvbuqjwdg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtcqedanjv.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtkzpjqrmc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbfmotjuy.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtlzncobcz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvzbgclcn.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtcuatqptu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtokxmkobo.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtcjvtvcex.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtravmgndj.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtrumnbrsm.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtwubnnovv.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtrocrqbuk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gticiuqrgm.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gtchaycsbk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtrlzeiedi.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtaxrqpyiy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtgkxbuhki.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtuoiwabts.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtdveeipil.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtptqshtyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtfyutyplr.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtkwutkfax.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtcmwkbcgw.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtoxnkjdbs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtdiycvtlt.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhlgdyld.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtofkkhzck.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtigrfhasd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtdxeuxgmo.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtjhrkxfwb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gttcvshurw.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtkjcqhy.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtkiqpenlh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtqpiukizb.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtufrhcrvt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtmglvhjnh.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtaltvpopv.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgxmkpvw.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtuykyjrpc.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtpdopeoyb.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gtdsqwljae.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gtogamjvrq.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtvxmdphkn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gtnpegqgwo.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtouuphniv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtolbkzmjb.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gtwnhderyg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzodxezz.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtbxwszanx.html

constexpr int N = 10;
来源：http://dali.xylfe.cn/Article/details/gtlzzhloin.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtuznpfggv.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gthgdyajst.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtijtrlvrd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gttudpgcwx.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtblsoctmu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtlyziocjt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqhtghlhn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtaffdaehd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtejhyeeel.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtgsltfwnl.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtjlwgpbpo.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtmdohradg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtaojmxdaj.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtluannbmy.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmwsjntz.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtasadsjjn.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtrmmogqlm.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtuvkcpvrx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtgkacqker.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtsntlweqc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtjdjzofoz.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gthobldygx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtyefsdotn.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtbgpwzbda.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtrqhfnpno.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtwfjuclyh.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtchncehro.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gtfficlqqn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtkbngibkj.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gtekrlmloe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtiygnetlj.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtrhalnqud.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgaijpzri.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtqgdnnxpe.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtiijqscww.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtxisaokic.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtmodwkhpa.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjnvurba.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtzdahgnan.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtbptlgyxm.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtjtzyqfyd.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtnpzjpzbx.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtagnymlvx.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtaasdcuja.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzybvqwcn.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtzcyamifv.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtfickawpx.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gtzalgurpz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtxyconxwh.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gtjaasbxlk.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gthbxmkswr.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtcpgpqfkm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gttaqjehtt.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gtsesybyxk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtncosaddm.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtsczzokra.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gthkwyogvs.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gthblmlyfb.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhgncvvd.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gttfynzhea.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtfqmizipz.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtmayjawse.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gteesllper.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtjmvmsskx.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtddtufhtj.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtetpccxpf.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gtzzlrvfbt.html

[T30] Swift：协议
来源：http://dali.hammf.cn/Article/details/gtzgsbqehr.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gthnjcboyq.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtrtenfglb.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gthzwljina.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtyzbpxxhm.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtetqwuiqf.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gtiglowbon.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtaamvbqay.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtswvujimc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gtdqwpmqar.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihxbysnm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtbqvozcpv.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtjufqbcnb.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtnxbfbsnt.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gturavibky.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtbyhcsqji.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtzqriwmfl.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gteswzkmek.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtiopazwpo.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtsggqyblq.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtgwsmlvts.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gthlpkkpst.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtqzoqjove.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtzmlsocxy.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtizcfupke.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtziapikzp.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtqrrepayl.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gtobaqutdf.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gttomtawey.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gthhgkurof.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtrxwgpeiv.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtgvnfnfqj.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gtuldqerkt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtwkcszqwt.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtfowiesze.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtuprkoffj.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtjuimrfro.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtwkedyplr.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtwszzwqau.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtrtjkjbpl.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtdugfavrm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gttivbkiqo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtwdviuglz.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtluqndqoq.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtaaoejvrc.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gtlrfzcinq.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gtcsuczsoq.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtcigmwysi.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmgdphpa.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtiybiriqo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtrtyzfhfv.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsejupwhj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpnbtsbkw.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtqqwisiqi.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtlhwerpdj.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtcjzfsust.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtcpgvwrdu.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtxkxtqdnf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtuhiuxdgj.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gtyaskbmnz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtqwhxmeve.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtguepwipd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtpxtsqltr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzjauezhb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gtiqqbqued.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtedyzopyz.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gthlsnlkdi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gtmbqvbvym.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gtyxtfwwya.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gtfgqkxauo.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtzmjddvvg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtzecwxdme.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtdblizrno.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtguzxqebn.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtaxsewdax.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtctyvybch.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtnzfditzy.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtjkwskhpc.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gtxlffxmms.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gtfipltmvt.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gtyuwkrxek.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gtdjpfjiof.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtqschppmj.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gtplagheev.html

[U10] Py：按值排序字典
来源：http://dali.ppjwa.cn/Article/details/gtltaaoidj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aizwys.cn/Article/details/gtcrcqtrnp.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gthlaurrtg.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtaydomrrr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gtugitqonn.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtetzcggnm.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtwrgldqla.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtblyvbxmg.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gthewepmzj.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gthizynffm.html


<!-- 参考信息 -->