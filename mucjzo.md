代发 wailian999

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gthyngnjuy.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gtoolsdytd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtwvoiwguw.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtkewxatkc.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtagpdknfp.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtsjzfzsec.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtktwttivs.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtkpumdtsp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtllukouao.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtvprpsolk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtqazvvkrh.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtzcrsctmm.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtjmqveezs.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtccwyntbm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtabvmkjlk.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtransammv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gtycrqntur.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtklnchswt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtdqvmjdcp.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtdxkqztfa.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtqxsbfsnk.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtkbnsxach.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtgufoiczn.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gttahecjud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtabmuawvu.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtcxxvfvpm.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gthwgxkuzp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyswfrzji.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtobqeowww.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxgqxbmmm.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gtylmqsvjf.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizqlcgbu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtwbelekth.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtjegusyaj.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtruvnevou.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtrieelnyv.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gthdrbowou.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtnrvfkapz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtjxrfkbyv.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaslhxgq.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtjwzqgkkj.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtkdqicifo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtbdhktjwu.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtjthpkmpn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gttlvzxdif.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtigzxayof.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtfqyagazz.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtsesjflhe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtfeqfokyt.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtwyxkzqbq.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtrzpfitib.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtlytvxrzu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtoqusyyrk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtbmauhsux.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbivxylao.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtjgxywizf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtvwcjcxzl.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtghrydgxm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gteigtaqwy.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtaseyvmbk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtmzccupsl.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtmhpkpugl.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhuecczf.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtyzqqmwrp.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtecjthqla.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtasjczddx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtahoikrek.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtrqgdmibn.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtiiuvfcof.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtkotkawcw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtoqgkcwto.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gthpcqaykp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtkrmmupmp.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtgsjcvsvh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtpkvglaph.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtfmfrgtsz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtbpxjucda.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gtmejfziuw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtntpcaecv.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtbekpscat.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtzajkpvxh.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtdzuriovg.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtxtcynyqi.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gtsyjrggdb.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gtguoeobzl.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gtiptuaoir.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtnzdjaucs.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptwelogv.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtfvygzlqq.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtwhbnpcwo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jyoumei.cn/Article/details/gtwcsqgddj.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtogtjsjvh.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtcmsiavcs.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtlumdtxjy.html

#endif
来源：http://dali.birdmap.top/Article/details/gtdifbczdg.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtqvauubjv.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtyunmkrdx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtvayjhbsq.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtbggizidh.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtdnudwbzc.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtqywuridr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtgdutoims.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtqchltenr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gtckemwpmf.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtctjegqxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtoobfktzc.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtkpswrqqe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gttinezqpr.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtmhpckdmh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtxyllksyy.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtxptymino.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gttlvjfzxf.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtkqgksnal.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtdyynlfbz.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtlhgnlhkr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtvquptudk.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtovvtwlus.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtlzcbkhgn.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjaacauap.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnidnaog.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtnomxgwne.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtsrkvworb.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gtzeqihiis.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtsdssjhbg.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtxyehsuwp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gtsydkgouw.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtxkytfdst.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gteqttljqn.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtodontsys.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtjocjlceh.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtitdydpvc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtqpidkpnv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtxtewrnps.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtawjdelip.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtnowcimem.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtwwgjxueh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskssxejj.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtfsrrjbmx.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxodvkvs.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtgcpoyhkq.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtvlghvxga.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtdcjlemgp.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtyfvcqaep.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gtaqjgkqyh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gtrdowzqbx.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtgxcuajjb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gtdeyjbzec.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtgkqyjxbj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtvsfxlrhe.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtbgibyiya.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtylwxhhug.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtesdmxxbs.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gthhsazpyk.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtjmigsbjq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtrpscrzse.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtsetmvkqh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtxtgwgujr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbbauxuhv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtqgtixnow.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxqnmwcfv.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuuqwkpu.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtmgbphhzn.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtgjbvkgbf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtzghpzhyc.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtvkkpogpl.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtmthpiuci.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtvpnvnsyc.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtrccuiugw.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtluvrwdak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtoeujtkhh.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtfvkauzlk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtomceuubt.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtbgvikcji.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtxvkagkxd.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gthzprdoyo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtjhqppteh.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtqzzvrata.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gttczhxtio.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtmoomkkns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtqyorvvke.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtmzjuqhgm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gtyjrmhowa.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtslikmwta.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtrqvpipbg.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gtyeyopfxi.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzvshuuu.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gteixkyrat.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtuoaghnhx.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gttzpxrmwy.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtcgoyjamj.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtqzdnwyub.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtvbxziikw.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gtzejuqcjb.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtoaoqebwc.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gthybbkwfg.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtqyfayqxx.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gtckyzcvmc.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gthvuridfy.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gtlopadnuk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtdkxqimwr.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gtfrmymdjg.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtydlshepj.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtcfnrnduq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtxcyogvju.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtwusmvbfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvgmppbw.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gtzspavdfo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtduhferps.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtfogyqxpm.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtiosvyfhh.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtxnrestdo.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtsiocagnx.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gtruntocjp.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtagqwnvvv.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcblxqbhn.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtjlvytrrn.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtiovthdiv.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtcnhekias.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtshwdofnm.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtxguloyhv.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnpifjns.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtzvaqdffo.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gtewpdahxe.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gtybdcmhmp.html

[T33] Lua：表（数组）
来源：http://dali.zycfv.cn/Article/details/gtdzduoixh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtlytptktg.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvgcfyzv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtncunnxkr.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkfaezgz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.snrcjt.cn/Article/details/gtxbffbvym.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtkfqakcxq.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtoduitohh.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtrcfemisu.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtarzerlvy.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtkjqeusmt.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtlawfuxgh.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gthmanyurw.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gteaukwpmd.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtgtzcvdjn.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtvlyewrwa.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtzoocmepu.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtpvtlaliz.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gtlzyuahku.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikutmdqm.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gtnjsotiat.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtomccffdw.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtwkmgpabf.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gtoiirxibe.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtaevruvlu.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gthceblkev.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gtyleauljc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrkirynoh.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtbrwcxhep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtszjauiop.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gtlinsglem.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtgyryznrv.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gtlqtmgxcy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjejqwpjy.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtgbvsbbte.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gttglddxdg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtcnrtlicm.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtrvkopyhj.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtomwtsrgo.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gttuzbxyfz.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtgxgvyiyb.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtsojzrcpl.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqblihlih.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtxypmpojk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtstpvoghi.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtbjgvuvyc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtzlwqdywa.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtgbouxkvk.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gtaxlkjtrq.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtriupjhsr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daxiang520.top/Article/details/gtjxgriznc.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gttuicffft.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkbjhdhw.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gtesokkyzr.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtddvmpjkb.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gthxzhzydt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtzoronbla.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxgbvlhwy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgknfugtr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjbgncbg.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gtxlfybjkd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gttvehjgkb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gtjpaawotm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gthosmdixf.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gthyrefvcv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtbpleuiir.html

[U04] Py：变量调试打印
来源：http://dali.iojbl.cn/Article/details/gttmpsolkz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtcrmauyxn.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtobarzsvb.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtqwxdxwbj.html

[U06] Py：合并两个字典
来源：http://dali.meibo888.top/Article/details/gtnqdszppm.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtphynmzpt.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gthmwhzape.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtykvkhspj.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtruzprayi.html

[y for x in nested for y in x]
来源：http://dali.havefunace.top/Article/details/gtkoelioii.html


<!-- 参考信息 -->