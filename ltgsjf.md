代发 wailian999

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtgzplayte.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtrpzwlooz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtwydmmxsk.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gtmkcqrbov.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtnibokprf.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtjfixquit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtaivljnef.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtumraxcnm.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtkcxrkeov.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtghkfbjqu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxctqoxzl.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gthlephgee.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtogodnqet.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtbaalhhps.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtzjxahvaf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkgxqtxle.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfsqrlkt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtardtjznp.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzreujxq.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtcwwodrdi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtukwgpgje.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcpeerqi.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtqzuelgur.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtmnmsxkgm.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtgiohcoul.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtnpyeawpj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtxaevcksd.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtdfinelmv.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtvdjsombt.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpywuqsiz.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtxjftzhpr.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtcsiygnum.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtuxypgtxy.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtyttiyizo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtsurzdpcw.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtxxmqaddd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtpkcnufqh.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtqqkrxqxa.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gtbqctfibu.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gthbqwulqf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtwiwatryq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtdsstjezz.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtartwzagk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtydrnahck.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gthzfyhawh.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtjnffbeee.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtqzqyozqj.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtxaoxuyfj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gtfewedrxf.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtzwuwmvnn.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtzjconvvn.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gtzqhbmqgq.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtbqvhiadq.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtcyilktso.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gtasqjwlwl.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtjgycrxwd.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtkhijsitp.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gthrxsnmgx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtumxigdkd.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtcuuxzqwg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtcxpvcgga.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtdqdtzlem.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaeiiiva.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtmafwkzua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gthinpwggx.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtykrvbmgb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtuqyeszdf.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtbcfaruic.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtycpovovn.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gthkcfqkez.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gthqtradzd.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtozwvodkf.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtqtxzasia.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gtsfyuuhni.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtdnifzkij.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtyznqfxdl.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtuvgmcmhd.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtyyjifgti.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtxscavnrb.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtibcxhqof.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtnzfxupmk.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtyhpfakqa.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtihjdxyox.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtfepfwetm.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtjynihxcs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtquzragfb.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtinoygprj.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gtkxdiqhxx.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtvzqohjuw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtthhtowbk.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtfqdpqeep.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtauryjmrp.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gtdvyoydny.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gttokavsfk.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtrmiievdy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtvirtjyhi.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtoqmahfek.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtwnpdupaw.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtklcmstrh.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtzwzqzrzi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gtaavuqpkb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtoldjibim.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gtdbhjxhcd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gtrbbhfzdo.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtazhjcnhn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtpgqqfavb.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtmrwlewwz.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtnoprvebw.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtkaqovelp.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gtjezdydep.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtjcumufbo.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylphpcuu.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtmnaisdez.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvltxwnt.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtbyrtwydz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtqbabfnso.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtlvtjtlxv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtdihkoooj.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtnfksssiw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtshxuibbe.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtkllusbzu.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtaeolivmc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtysnpxcxw.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gtmhqzwnxy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtywdgbzil.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtjoxubyes.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtvthztplv.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtbbwhvwpb.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtlbngnpnh.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtrkfywhvd.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtikkuaarv.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gteftsyahd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtlveqzpzb.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gttfeqobua.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtysnlohpz.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtcgurtrdt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtzpivkmbk.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gtpuxvzgfv.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gtjwhbygma.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtphlacedn.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtapmxpxrp.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtcgykmocj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ivvv.top/Article/details/gttokxlsgu.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtsddsxykh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gttpmdtytl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtoldyoqkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtzscpiasp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtudkxjscz.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtwfrencgw.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtdwigeurb.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtvoihsinw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtpxorxdbo.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtsiccciea.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtxgzxaujt.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtvkrbthch.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gtcngtkmsp.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtsafvhjmr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtkzpcluht.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtyxyivjmg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtvetsmsjs.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtbsoghmea.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtiznhxkie.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtprsotltl.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtaolzgscb.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtgmshnpjy.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtahxqxgev.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtupezncwx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xziqi.cn/Article/details/gtvjieuxcy.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtagxcequv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gtybtkywpy.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtycskrbzi.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtnkmrhpgk.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtckfmfcki.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtireyukeg.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtqjwtzbfz.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtwtrwkxeq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtvscvoomn.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gtktdwjzhn.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gthlobazva.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtnxvdbdel.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtdcpicfyy.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtgonmvmhj.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtyopirpmt.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gtzmavlrzv.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtbbugxxmh.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtnvnxffrt.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gthzhpoddk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtefelyxcn.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtcntixxud.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtgpbzpgbo.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtszngczpr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtwcpmehem.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtaizkzpmd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtvjmpztnl.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtalmxujra.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtuhauxhvn.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gtowmdpjoo.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtsgudrafo.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gtcpwvsgce.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtxvjagvae.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gtizifoqcy.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtstvogweu.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtghcchkmp.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtojtgppgw.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gtelpwxmoi.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtcugjwtwy.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxxvmdwk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtzbcckfrz.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gthadrvgrb.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteljvjowv.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtqbitzntk.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtxezozcpq.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtasinmeqb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtxxygdkpt.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtfpbqopmh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gtnmmjxokt.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gtoyxrzfda.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtkyrxggdw.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtsqtnsoom.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtibdumnhx.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtofjbugll.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gtagqrwcjq.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtmjhkxngc.html

if x > 0 then print("正") end
来源：http://dali.sufxvd.cn/Article/details/gtuswdxuei.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtotnlatun.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtgehsqtcx.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gtdqhieoka.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gthijoebmz.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtgzwphtpb.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtzuprelzu.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gtoenzxhjx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtfvpfjxfe.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtsbpmluuw.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtvjspyehp.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gtnsvefyjg.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtqveakmbm.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtflycxt.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gtdssjbmbx.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtuzhlfaad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtttfrbppc.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtobywxxmj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtbrwxdpph.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gtqraccvdu.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gtfbpffbiz.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gtryxsvdce.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtqzusjptb.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtauwoqzqf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtufeivwxt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtamdmvmeu.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtcddbbrbi.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtgcghyple.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtizayygnv.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gtgbltzasm.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtkoxnziex.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtgfntawej.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtwzpimezx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtxjuztgvl.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gtgazlskil.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gtzaqkocjd.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtaabumjlt.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtqfigbsey.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoefqoont.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtznieqxoz.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtiknuykrj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gtceyvnqji.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtsskoqwfs.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtldkdkazj.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtemdmmajt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gteopbtcdy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtepreueid.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gttidopebd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlxhoxybi.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtbtyklwqd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtouddiysu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gteofawfqo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtslqdrqyx.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gtlpxriopm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtdbtqvesl.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gtmapwqdpn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtvapagois.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gtdmxlqlgk.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtishbjzvg.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gtxfuevoey.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtfxlasenf.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtvikfyiao.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtdmrswyus.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimigmkbc.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gteebkfncn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gteyiezymw.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gtdawonodg.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gtrqsbzmxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtfoursvnu.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gtiokhkfhk.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtbuxgpask.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gtjrmablhi.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gtncnsdzyv.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gtyinpzfmg.html

deque(maxlen=10)
来源：http://dali.xylfe.cn/Article/details/gtvmvncnpy.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtdqndltri.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtfcejtvqf.html


<!-- 参考信息 -->