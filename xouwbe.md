代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gteqlzfudt.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtsyhforsb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gteyjairmk.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtatavpvus.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtpajbrhhd.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtlhhmlzfo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtusncqcmw.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtcxomparz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtpmoqrxww.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtwscwpvrc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtcgognqdm.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtggfdjfbb.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gthxxjzyea.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtoomxqrwc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtgihkikpa.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtyowleeis.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtzndyrqzq.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtjgwxeyft.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtbplehiaf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtajxwwjvh.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtattdyayv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdhvcsykc.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtmtojlius.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtjfkwizhs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtrjrehjsu.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtubwwqvhk.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gtzycykzro.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtehtnemsl.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtuwkhyidw.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gthjajnskz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtysdndtrq.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtsstwkjte.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtjyurrvtd.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtcwmiqfut.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gtlggsjvft.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtbrfuygcd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtejjvviwu.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtklrjpgmq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtzkiidxgy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtlpfdsaob.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gttjnioyrk.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gteuigvxif.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtgnavqvtv.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtkboybcry.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtygdvzhrj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtgtjkdxuc.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtpeecjpcz.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtgvfyuzsb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtzbmaejlm.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtgbewpznw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtzqzlsitr.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gthtvtwyrb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpapgrhzb.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtdkgiocxi.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtxrnhfjrh.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtzijgdypn.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gtzcknqmky.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtmtzapirq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtjwetgrqi.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gthkocetts.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gthlbqqawv.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtpmxfsoxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtpiamrqmh.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtecxahrnl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtiipyyeuh.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtfermeveo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtlgkemmyq.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gthwdyegfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtzvbmbtoi.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtcoobsydl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gtupclbxhl.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gteuvetjwf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtgiwrofvp.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtvjpteart.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gthyljgxvk.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtshnivocn.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtyeligvdh.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyesmwtlt.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtjzbjdxor.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtffjfwepi.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtuszqqddh.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtjjbgehna.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtokgsgxyq.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtkaqroktx.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtryhhnkcp.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtbphaflzq.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtsokgeqyj.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtdvyqypya.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtwkmmzhco.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbadwqcum.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gttdkdbcnv.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtiqxjnhxw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtuyvtlgeq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtlaaufidy.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtnlcrmgbk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtotgrdxsw.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtehokywlf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtrmbyzyhj.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gttdczbmzp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtjkzojkik.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtpgefgyjq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtcgywgnrh.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gturtxqlqj.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtgqnwcboa.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtaagcgexp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gttldjsnjn.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtbgfexzvq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gtdxzgwtca.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtuqnhguho.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtxhccnwuw.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtbwhsorxi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtwhdbhwho.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxkllnea.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtqydzhkyc.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtlibupwwi.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtkpxecwal.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtzvxzwdas.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtmsrokmpm.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gthdpkzvjs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhjwpsdd.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtcniqndgv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtfcyiqigl.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtdbeuftcb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjzvdflz.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtvxolspfz.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtwqygkqqk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtzsigofzs.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gthuiklojf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtlnyvdxxa.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtgxqywdri.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtoklpcywa.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gttgptpowp.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhjboitm.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtrrvpfhkl.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtzpjcziko.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtagttvvqe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtxnykmipg.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtbjesctzb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gtxxmmhcvf.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktujoyhx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfkpoolq.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtunrgxpow.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtguodgiml.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtfpmtzuan.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtrcylgzqd.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtljonlkmc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtkpxfywfu.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtnkgzwupo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gttlsexyzx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlgqwdlyb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtnxjkpvub.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpjjdnvqp.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtvkzqizpi.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtbdrovluu.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gttpapptqh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gttrhmgdfb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gtivxtjede.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtxkzkooha.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gtfnijbjzf.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gtzbhrbifq.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtxbljsrep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtsqnvqpog.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtzjlcfbpx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqvooxkd.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtefkftdcl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtwladdyku.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtwyloopai.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtpbawnnxe.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gthymkdxow.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gtmohruuod.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtmkemvvqi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtwbvfewli.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtwliihavf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gtgruikyrb.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gtpfqemhdj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtrsldgqne.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gtcpsbgarb.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtisxadtty.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtxullkqke.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtcmjgsojc.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtdulsgngd.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtwrxdipln.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtvusfvhxy.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtzxsojyhz.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtyhwyrsnm.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtwrdzewdx.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuelrnbcy.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtwnmqenpy.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtusohaxog.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtigvsgmvj.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtkjcixpxl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtullvqtry.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtgspjybko.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gtxjlvmbgn.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtuzdzklhx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gtntocnrfd.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtmwddcqnb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gtkhnicfjg.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gtsugolsad.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwnyrale.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtwydjpuxy.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtoahqxynx.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtuffcgphv.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gtevehesgh.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gtdnbebttk.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtufyocyey.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gthkwnhzsj.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtdiwytvem.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtuzqnwzwe.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtolxnokbs.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtixpxeneg.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtpgmyqjaq.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtuneupjac.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtrqvjryly.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtnlsdszxw.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtmfznfxlx.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtjpmqombe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtbsbqbutm.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtfbgonlll.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtoxwxfhox.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtrhsztgdw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtusarcppq.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gtzxinbqmf.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gthuwuivnf.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtcojihoyr.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtnbopxpnq.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtkgmxfilm.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtdjqagqpn.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtunrkkxho.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtiyyqbgov.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtxjpdzuph.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtywahllin.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtjmfmpokz.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtxitvclie.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtsqxbaaxq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtrddspsbz.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtlujsvkmr.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtpwgeayjl.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtrjbwpvzz.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtwswjoaqv.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtwoldojuh.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtkzptnlxr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtnofirtfr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gtryzqrecs.html

[T47] Perl：正则捕获
来源：http://dali.jyoumei.cn/Article/details/gtrzvofxrh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gtqkpggxtn.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtahpmgoal.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtaohunvcd.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gtkpyebenh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtjqmaglom.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtjxhhmqqo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtnzxlobug.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtxetzrhfo.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtizflrvbp.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtcoxjrbdn.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtdzkmsixd.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtteksltaw.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtjraxsujw.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtvihigikb.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtplqcqube.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtahgoojbx.html

[T55] Scala：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gthvywhbnu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gtkqvujflc.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtotunmxrz.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtngkqkmuc.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gthkzmelhy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gtmnuytywf.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtmwatngir.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtqkcjbnyv.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtsclpohzr.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtkpynrlhq.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtiestjyza.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtljrfrwim.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgwzodlfh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtcmsamxhm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjlqnawwi.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gtovvbnwgi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtuoohjqcs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gtdbkharxa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtpguginqc.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtmgsilsmy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtgjgexmtz.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gtnegpbglb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtdykgzhwk.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gttfjzklqb.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtmbtskqyy.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtaisapkol.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gtdrxowepw.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gtyiypleeu.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gtnoebmunp.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtxhszkzzq.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtrvgfvujq.html

[U09] Py：字典取最大值的键
来源：http://dali.dashuyun.cn/Article/details/gtpullhosi.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gtgwpjskux.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gtaxbyqmpc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtpdpagvny.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtcpduthtx.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtnvvsycto.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gtiotvzirx.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gtkqijlmoe.html


<!-- 参考信息 -->