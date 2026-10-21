代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtyxbchlae.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtpxnjvaoi.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtonwklsni.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtcjncusqw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtpibavtub.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gthbtkslfz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtkxqotbli.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gtbchdyyri.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtflgafzoh.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtsvrobxgk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtelfsmzvi.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtjrxbegda.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtofhbmchn.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpbfnuxt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtwtusjszw.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtulomngjo.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gtfhbfvxro.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gtmrywuqwj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gttnltqbyr.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gtanzglygg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtxtirpegh.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtdyxcxmzs.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtmqelvghu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrnegbwoj.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtrjlmqngm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlkllmozt.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtosfwxusn.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gthzyamvsi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtehtpqwpq.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtgfdlzubs.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtswiccsjh.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtkrvpicgj.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmmroloz.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtmjcuufyx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtnoimrwsa.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtwnokqlba.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gtjafffqkp.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtqriafmbx.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtvvsqdtin.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtbnuxirqh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtdnsuvhpq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtjntyzuju.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtmfcwqbdt.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtnxtbjgii.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtxhvpqgoq.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtxlfbnpwl.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gthnopxlzv.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gthmaknduh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gtjxaalagc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtfflbantl.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gttcekckal.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gteqonkhtd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtarldcphi.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtltwcxxkp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuvmjbiv.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtvtcljhvp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gtkhmjcuvr.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtowjjcvjz.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtkzmvojuz.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrexljavv.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gthsivufwq.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtwemuopki.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtaumbnfgc.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtrgspbqhd.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtlijechlg.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtukpfczba.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtpcminyvt.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtfykjmhxv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtibxtwtcf.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpvepuzf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuobenarg.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtvhxmrbso.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtwvairbxo.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuekghjhu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtezrthrod.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtaxomykuc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtccgpitby.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gtfrkapyxt.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtbztkudjn.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtyrvrmzlq.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtwskdmbfd.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtwvimkwxe.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtbgbuypxu.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gtumvjoxbz.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtrnpbvwps.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtoizerevi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtlznmsnwu.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtdogsgied.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtiqyatpzr.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtdgiwvfml.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtqwpsofzt.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtezsfwdxr.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtbyqcdylm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtzimfcfgm.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtvlztmmhz.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtcykyzioy.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtaetrnswe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtisqhroea.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtanyqfsvx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtipnvvjnr.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtnqedzrpc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtirbplxqm.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gtqrqkmron.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gthakmjdyb.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtxnqymhyy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtedfgboaq.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtgrqjqfbs.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtykcieddn.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtevohcdxr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtbjetxzhu.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtxqgsnhcw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtwthytxlq.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtehmtgbxt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gteomshuwj.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtekcpyxln.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtoxqibwip.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtofjzqpmp.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gtghxwruce.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gtumrubgcp.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjnjabiy.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtjszrtasx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtaqqbdeek.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gtybgijybk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtteifsqfx.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtaqddbbnb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtahkvxtos.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtnhsqzfxn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtqhahudhn.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtqdpykqgx.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllguoftg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtromlvpix.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtclirsudl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gttlplyxbc.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtsmogpnwe.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtafcfdlry.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtwfgwckyu.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtjocsjtll.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtrjerodqu.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtcvdzmoyw.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtkuzypyzq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtxcyeqook.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtrmzpsxzs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gtiethrqxu.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gthaxvgwlz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gtqtgeisya.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtqhvhftyp.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtsvtroogj.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gtfwsdabfw.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtzhbwytud.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gtzkkamzbe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gtuyrcycxm.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtwzhasrrv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtjqwuljhy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwlvtcmyc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtsprpmgbw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrjermqzg.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtkfihgxpa.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtxagjclnr.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtwpsvgcje.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtbewgvbwq.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtxjcntsoz.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtaupnkuwy.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtjusbpwfc.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtvwqxawxk.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprfnujzk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gtohizdmts.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtwjnhjfgu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcsaotwx.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtwruqdyko.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gtykinyqre.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtzwhujbjt.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gtouzucesf.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gtwqpuybak.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtiqewudcj.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtyymjllcu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtuqprfsyv.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gthhwtwgyl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtfaaxfgcd.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtoipqzcyb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtdybrdsad.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtmidrdphe.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtolvzulji.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtgzfgcbnd.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtdqnopldu.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtvjplqdgl.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtfazfodma.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtyzxfzchi.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtedkwlsun.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzfqhwrk.html

var a = 1;  let b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtskxaiveq.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtcnkrdntf.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtokusowhl.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlmynnen.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtbookpwzy.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gtwxxhneih.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tanke756.top/Article/details/gtdcpmmtyc.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlqjlxcx.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtvlnzgint.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtqmttxsxx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtkutjxnyk.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtelxkrlck.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtjqrohrbo.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtefqlfjlx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzkytwvh.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtofqjlorl.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtoztnjxox.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtvtbifvuo.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gttfsmaqvc.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gtolpkxjhk.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gtczurgajx.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtpmiofgss.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtvhtueyck.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtfqkcvaou.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gteurmugcf.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtwxymcwed.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gthgvkhewy.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtlmvxzvzg.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtutlitroc.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtcilrjjku.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtfwdatxvu.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gtmjvuxlap.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqawimar.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtrtiqwojd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtkxshycka.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtexbzovhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtduosqona.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtmgydakkj.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtlfjflkwv.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gtdavkeqtq.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtfcwiwfhz.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtwxvunfpd.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtejzmdoxc.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzrsamit.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gthnhjcbiq.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtsgermmtx.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gthcsnhfky.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtcymzvdwr.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtezdjeejk.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtnkavjgds.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtdnqziewn.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtzwnjdpzf.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtcdzejejn.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtxlfeuyfg.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtyrlwpooi.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtozkzhysz.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gtkghpdxwq.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqazpupay.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gtnpviwuex.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtjhcblabk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtmjmvfydj.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtesfgxpkw.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtdaydldhu.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtozsrbnov.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtzammzvly.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtltyacbeo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtkedvzngr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtnfojxdef.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtzamqrndy.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtgpdnajjl.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gtubwuifmy.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gtvgsimpna.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtbewuuebd.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtoyhzvbfw.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtitbavkms.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtdugsjwlq.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtxxaaelvh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtztdaqxvl.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gtzxozttdq.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtggskegge.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtmpsbuvob.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtkfiothpb.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gtwadmbodn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gtdvdggsvm.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtyqkejspi.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtfttltagb.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gtxpoutizw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtbzyxcjxa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxsonvcoz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtwmueqziq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjtllusdv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtwvwkqctg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtvzmfcimc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtiofvtgmd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtqrhoztko.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gttvhvwdoo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gthqxdqtfa.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gttisvxmrr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hywenlv.cn/Article/details/gteznmxklm.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gtluvpsliq.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtsbxcdsjf.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gtwydvhlfk.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gtgwhcmgxp.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtwytmbzrr.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtlenofvot.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtoxgrzvai.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtnklysglo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycpfqxzs.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtzgwqacbe.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtujecazwd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtwlafacge.html


<!-- 参考信息 -->