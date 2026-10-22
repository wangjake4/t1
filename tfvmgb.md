代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiqecuj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzidleiw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xttxavcd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2debcjllg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvhcjzj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfzcfav.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zejbpdwq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gygqitsi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2abugaaxe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnjepac.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfmkvkn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uaonubrv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjigfez.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2adbaxxir.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqobhgup.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsqcidd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ytamdvgc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lthltqsp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oiymxsrb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtyefqo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2drrpundj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfhsqwi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2okahtzpk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sknigsiy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2knzwtqxn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vysinmpg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2euzqdqko.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zefqpsrp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrmraxb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuymlip.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfpvhci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxykfvte.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsvrhgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opfvhahd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iluodhnp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqtkyoq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfaxyot.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgwwaiw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjfowxg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2igkuawtq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhbfsdr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cordzdxl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yunmplfv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmbqyee.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oroowqzm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxppqzpu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hgegwmor.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pulaztqo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnucwws.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iylaeqta.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhqwzml.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykksdwdg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2skandjrw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tgittnps.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfszdbkc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzyuety.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvvzcur.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2algtcqki.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2chvdodvy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcircnbb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2igpplpky.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyujupu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vakjwquv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iogjafgu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2muteivcm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwyxplz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsytwpz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eratvfqv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwyxfmk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cijocehf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqioqclp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pohhiddp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffabafwt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgvdzqo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vneguwfc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kenbpbkh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrzerlg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eshkpigd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjhmlwj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcxroqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzmnvbr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzsxusy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qflgfltv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfuhduy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsibclwr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhbhwof.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbncbpkw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlficlg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2grblmfmu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxwchsd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lupajzwc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzjijnc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2auuouqjh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xenukwmk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgkubqj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlawoxw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jpexelbc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2waooybsv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhtdrlk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxczxyh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeqtkdw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ropcqrqp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2otamexzh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtmrgrz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhlrkpw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbudxuwn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2beznwcyw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qateaukp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2timvimyx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2scslhhxl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgcbxmx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlspkxp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnagwjl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmspgydp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsnqcdy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmepdhx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhmkqts.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2orydsfzm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvoeapf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyxmfrz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpyfwtv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpplxafe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uchhyvkd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlqzleq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ssabyqal.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhphemv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uxavhacv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhiogxl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxmkqrp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxovzqh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyqzkcy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjcivlw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fftmexwb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmkgzyy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arivlqct.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2adtrftwz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2almzfqfl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuvnbua.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwehoqy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tlatmdzh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cubrloyd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2brjaodgy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdghbzti.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpfvdbq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnuuopi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2csbgqjeu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeklodna.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnmsdbe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsztftbx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjkiapk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzyxzmf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvaszgr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvvutoh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2scqdxgdd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2leqwvbue.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfwnrcj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sapmlxny.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmyhhan.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiioxjz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qukknuyk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wdunhpez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpynecw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzkfeqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rymexeps.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eftddepf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjwenrk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2juasayvy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmuhgqd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kesfvyva.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqilecab.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyoipuq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2veozgpqh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyupcfu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tdldnbfv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2giivcsgl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cinecnnb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpawsfd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgqnxyn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcisvsl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxyvvhw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jedgdiop.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaleonba.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oakwsfme.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcrnwmh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bumnnfbi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2twwlxshf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhigkrg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppogucts.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyiswdo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zonomlei.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2twutmetp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2foomktxx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bleqndyq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qttgqtym.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmtefmp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnifwwmy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvxryxz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrfdjni.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkicsant.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzzodgx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2giiwjrqi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sexhubgc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lqucqqzi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuezadh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvflzqag.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2opveudqh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmkmiko.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkpafxs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lybefcxp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoyykxw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2swbgezee.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuvnzzs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdcorwl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqclkgnk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzppqvg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxecrql.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpinigb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqzhuwk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2estcsxvk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2inyezdpk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlpmzri.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlygecqf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mluomgle.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jltlbzdo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrspolma.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iysskdsu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyklbgr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zeahtsme.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkubedk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgngsko.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcmnneb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2leuflnnd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkmyemx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqhymmi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaojxuw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2txidwtve.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2htugywwg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2imcnkyvd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcepbymy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2swofixdb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fyspyycw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vieffrsa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2aedomaxq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yygqjnak.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrrvjnz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyvgkol.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njnaxtyj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuirxzw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqgtyfq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2owdkbosx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvgbuet.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyvqmad.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjrhjsx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgmvrjp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2levxfegd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnntrfma.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzklxyz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afpxmkem.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbdhpov.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnclzwe.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhtgnhs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhfbmum.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rohbkgec.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yljksyxl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdfqxaa.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzobnpeb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2znchqzww.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwcsvhf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkggrxnf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2neftpjft.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwztlal.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfclaqu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlpgprh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2flpfjzpo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bleynjhj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2alhsdjqm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aasnelxb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2akjbhxvz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pycohrni.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2guwkmteo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2anbasuce.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amzicqpy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgbhoei.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bqglbmfm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nutktsqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hemvlpmw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csnnqjqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfsrbxy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fvybrnoo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaubgxf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uzintxua.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kaogocnx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2abausgzd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2reotdemm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2leqjscuo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dcindaio.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdeodsi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zecyagqt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hseczxfs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2klrppsao.html


<!-- 参考信息 -->