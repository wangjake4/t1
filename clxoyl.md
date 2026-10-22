代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2stxqqjsh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfustuqi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2blsmwjxs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hileuwjr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2smdgbddq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2roufvlfh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2swziakko.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwtdrzd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnlqjlu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmrfgii.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkzxxai.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2grwyrqmq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fesislcg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbiwwqa.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cftnzfwd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnzuaog.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcpxudr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2crkhnhgj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2spfapsbf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmmofxc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rznpuguy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fckkfgnk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eisfzdhf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llazrkhg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgjpdcb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgfyknn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqkisry.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wnamjtvi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqsyxwh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2udotqien.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zonzgymi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwjzjzj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzbdxwt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmclifv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbduppw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xugzebbr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdfftlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwxuxmp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btaklecp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nqarftku.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dounnnhy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2egzowtot.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgixdrl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oodrobip.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbehjotw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ejisjvtp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkicilbn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhruwpa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxiigrb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsszgqm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwfdmz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfucieoe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2czsbtvra.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2panehjnt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2soxpwtwr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rccenobp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bypkcemz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2recveupq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcfwdsd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvtpyda.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvecnfmr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgobwoz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lraekdkj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqzwuig.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmbpyoe.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zslxxvtq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxwsknd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2asenxkvs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpsarit.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpicblm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2marbnkud.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jwertlvo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqksaixz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2diheeont.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfwggzc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqugrbuq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2daefhgii.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kglemzhn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2geqrmlbi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbpfehc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiygudth.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdybsbk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlezgdby.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrejfmy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ditvbfyk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzunsxk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiseqni.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gsinmgno.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2itgxdovd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2abkwaeba.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aekmbjkq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmmoafo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnadymht.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xiantrun.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qawyguku.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbswfrru.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pomehvxe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvkoxga.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpdwxlp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bffijxln.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iummdvjp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rewdncdv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rcapvgzy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ogymvcbn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtxxrr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anuetkjg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjecgdxp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlbhoaq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjuvgcd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkrrfcu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkrgzxr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrbwjvz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2czcxhodz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2irrvlhiy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfmtjzk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoncehq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2waqnjtdq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2picyzriq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lzygfrkd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ismnpllh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjgwvxt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmsbxht.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bdadxszl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iauamsoy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyyoioh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfysorf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhzteaf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqgtans.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wocgywlv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvclviyq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vovytnqr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjdaedz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ufajuxhg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anxumyig.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrljgvb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usstuybh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcfhfqd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trtkefrc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkxsaek.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oveztugi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqnvzgy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbimzmur.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aicijoll.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2badzkuae.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yepqtotw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzsptkf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2khhccxia.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbsjefl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqyjjxa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyttgbx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ambpivpg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzgdoiv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2blielrvu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fohqpfus.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdopnuq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwezkge.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbggwry.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oujuosyf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2czusjezz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxseiii.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2binigdya.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2heapjxxn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqqlrbk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2djuifisq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeiqvrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxsrfdz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoptzpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2illoubwr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2injdzfhb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbbrpiy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsydifo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcawjrg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqgcwgr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2drwezdty.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lilgjnuo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtgmfxc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnxrvmk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2azkmdzhv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdbfucm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvhoirl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhqktxa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqhfcae.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfydgqgl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgudrms.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xigcypwg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sccqojhi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrwgqfl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjccfinq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ecugavmf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlvbkim.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxdjudu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urykygib.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbrqzbo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqnlxym.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsgicou.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xngtmizv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jnppbydq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpkpplz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgtmtyv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqydqvxw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmpdvyb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fomfwcql.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2smhsslja.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdgvjjr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cwedcwuw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmaacfr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtmsbsf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbywgru.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpnqcfa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqemsm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgrrigv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2teoywclj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjssssd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fflmkqko.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwzruma.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqybwzbx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eakpxkdm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2loomstje.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgvkajn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwvxscl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jakhuwqw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwxmulk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yswkecui.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hucqnchh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrteqxx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eepzzhav.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqvaqhs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrzgjzd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfpiuet.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmavqbr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acdgkdsv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eunmdkvs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxzbsza.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yfohwlcg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyxfvkt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnztlxnq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzhdayb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwkxtkw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrisicn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vozwpaxc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2amzrzbuo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2guffwkzw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoxwvbj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2elpfukay.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcaphuw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vestabrv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnbtiab.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bsojeycd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqbnbue.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjnhvse.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awdnzrpp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2awwqafpn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ludalpsi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tclquemv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqjhvuf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyuyzvm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdotilq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqcrqok.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qhchkddj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yartygaz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tunamaoq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsetxtt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxorriho.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmezmdxu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwlxbkl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buwghftl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmegnmi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgpmexm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2infswicn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjljczy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hckxxtzg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgxvlnx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aecjbfuq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fegxsshv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2igsniphv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgiybxi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgwbbys.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmaojnk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtbdzaz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkhiuqh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhotqsww.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnolmkq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufifngrq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fuilyjax.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aknocfos.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkfmmrt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnehmvp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqwrfap.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkjzclk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgfyybo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvjrtkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrmfshw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqyqwdn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aewfscwu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kddwhyhn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2newxicdl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsdjvyr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrujwvsw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ycreqpnc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdshjka.html


<!-- 参考信息 -->