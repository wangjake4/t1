代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hshvwedj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcerfqpk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcqvyfg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmywhng.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xuehjdnj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnrdvip.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wsieenha.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2anakothn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgtfqqk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmxdusx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cudqaymr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pyocgogc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lpasbchp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeohhbz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlofrrc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dofxmuhc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wlktqvym.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eteizxeb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2letihvyg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2htcgqhjm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xoppcxec.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdxandn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tarnblnv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2quivrqmm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pplayatl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qzddkybm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbbjhxz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dczpoimj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyfjnqr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnqeszp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdovezga.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fgskufrv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtrvcqf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bujlmtua.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsuftvn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izqnmhwm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmotyl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inmzfqcq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjorsha.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxbgntq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvbbbrs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qtydikak.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwqohrv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mflzdicq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwwzefr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gtipsivc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uypamzzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoeexyf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tvncspdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdclkqb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzhxrqr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkfqjfj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbimeyl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkjnlmy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbrqeqx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfklqqo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrdtjep.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tjesjndt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoqmicy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgkkotw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2erkgeujt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpyelwx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgxmscb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhtxynd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhabakpr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kloiiymq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaagowuj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvsxwfh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2slrpaciw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xetptxdq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2boslnnbu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkggefir.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkgzszu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfasobvv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iohidqdu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqojecoh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqjajcp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvgjror.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kinfriff.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwhpgee.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxlwzit.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hafwmzex.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyqsmui.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdbxwxy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbljtey.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwyejit.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcutxkeu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkggexq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsoejro.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgurknj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzqcoda.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yojxhjld.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqefngi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjubnwl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2upvgpeop.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhyigcp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtubvha.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyutjni.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqicbew.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nabngiob.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2inpddqij.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbjfqvz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbdocjv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdtxyzb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2agvpuvqh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sapdnlux.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cldileps.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axlaolmw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2czbirncr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xohdlaqq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tchlsnkv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2naujxvjv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjhdmpx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hywfhkbj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2drzicvmx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbepneyn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2isfgnoek.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsedgwlm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swuusxen.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvuufrn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2taffeppc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fslwvzdt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbrlhuh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whkroxwm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhxbvzw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpormjin.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2afkegbni.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fznqszhr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvomeex.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqztbhkl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtbwvja.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvsqaxd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xarvsmwt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtypwdc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iwflfbee.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazwjpjc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzksllmc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jttejdpc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zohoshvq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cerhpkkc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2stjnkzhu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxthsrr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhmbdbg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pehkuafj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nplnbxlw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdypotjg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeqtvpq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbnsiac.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtycksb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awoufrxy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqppjos.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbfvfde.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2inrmvcuk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnzglxf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gibabekq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2diwvbiuh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2svpixmip.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kltxebku.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwskhqe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pedaqpgh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzpiych.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2eskvklji.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnbcdxl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmrbbir.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnztbgy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wypdzgpo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2illznxsu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcbzlvf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vklgjnqs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxamlhef.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2feeachum.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxxskak.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlakfiz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnxlkeo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xygqkdhr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2boyrydlv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxndoue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opbdrhcl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2shbbuixp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nudrrumk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibayfksi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2azqymosy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrrxyry.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2orgafgtu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdseyoy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcwdkpm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2igzkhtgw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2emwkkeas.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuccarg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2suwehxuu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ftefoedf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzduteti.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yijymlbs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2joyklzuy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkboebj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvwtusk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztplkukt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvbiifv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgxqucw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pntgproa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwchjzw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhunavao.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dzezlnud.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jywirpjw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuxbklx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzmcjhr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2glqzyzvl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptewxzkt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjmskmh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvizoyrm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlxdxsu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqldbit.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjlwhqp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2earyzisr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqousgds.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbryrviz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2isxykryz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjiaogm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qvizioci.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2evcbpnps.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxggdgc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tltmrkrw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbdqkgf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzhbopx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znoemzgk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2amgfgepm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgsqagp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mirxzemd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bylwzrsi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2znclbsly.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kdufwirv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsujjus.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyoxshu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeduloa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsttpiz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqaymid.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tiopotne.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjussfwt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwjnbkd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iujddifo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxtihgp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlgpdvf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjahhbe.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zvetimrg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jktxyzuz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpjsfzf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuusayeb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbguymqw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2efzuugdx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzjbods.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpumajo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2czxorodr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyovzwb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tryrxnnj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkbniir.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkedriyx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnodxtt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cukkactq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjcmrys.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2unpxfuhn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xcatimwb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxslflp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irweqcaf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdtgyju.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcevqfxi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdqnajn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmnhyol.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzviyqih.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jybkruox.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cikczakv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2waimlbyd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpssncdt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fmybbyvk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epcwimgg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlavifbs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdtzkrl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqdajws.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vivgwppb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxbcayx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdikwax.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zntxybil.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsltkgs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhdmrsc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwrxsuo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqyfmde.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2blpbwpmt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2goqoihmp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2poaxzdep.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2neqycdrx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2snalifpq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmlsmgt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdmjuko.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmrbjyr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2suejvebw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbaikzk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vogjbgbz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2racdwbcw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hynsyrie.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcfnbgh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2itdejaec.html


<!-- 参考信息 -->