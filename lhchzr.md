代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2psgdqade.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvbdjdt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbltght.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhoeidt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdjrehv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyxqzkw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2egbbpeen.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxvfnui.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2htwgeijy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmdvzwt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwcdbns.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2akjhurdt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2buiivtna.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ossptoyp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyvzvqb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uutmeuil.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbsokcu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgbuwwc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2psdhhica.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyjhcvj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uelwgbkd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlmsofe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmlzwrd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2czyjatbd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiezfcs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvcvjeg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnisjeh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aezxbbpo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbekvyyk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2brcazllc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hstnlmds.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmfgvme.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlgkovu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvobbye.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjyjfbn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2baidowva.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrnroqs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hezkdcud.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tauimcgy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxcvskw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrmgjgq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yyozkudh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrnmhyc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkleiee.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lemnorks.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmsmjrf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vhltgxnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hohjcwnj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kntliuze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwgbzst.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onpnrukg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxgercv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnfsbpn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrpnphw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wunhiocm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdqzhwg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoirjvs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyndgcn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaqcmyd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2agdlhlho.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohswxrrn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iujobfae.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhyqopl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2titxibgi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgtfbey.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaaxspf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuzknol.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2puicoutu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qibzlvgm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ydursrni.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2czfwujrl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfcuprb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpijmliv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzoizty.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnxdvfn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfvlnyg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2whlserfc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiiqkyq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnjppbg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqtuzjn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jodwelww.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2brrpkqfz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aghrrcpu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiuulzg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzqqmhk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcotemx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpwfvtg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtkjqjc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2idskyjyz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgfudmc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kutclpet.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fruqoylh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjdzvna.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsgqwtf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2axezxiep.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2djvzicda.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwpeyge.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfrcniv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jledivzi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2irqshobk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkofqoi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqmgyjz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoslvme.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2noutiacc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzojgck.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffubnzby.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnffxwvk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjauidq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaiaujk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gglevqlf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2swaxltye.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwvepqn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvlfluw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpualua.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoiogzx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbfwskr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjnmlfw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzeyifj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrpwgmz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sftcutmu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2enypelbg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrabywu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ohucyjky.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcwzoxl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vinqrkdc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjjrlyk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyonmlv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzybielh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwglmrd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2maspixkx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ygblhpjb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2klvsappg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnrzqyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eptzuect.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oevvoddu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzapknp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sevktnam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2afqvgsra.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpldtxib.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiawoiu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lirswtlc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2svbwgaeu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwwzafx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caugrrdh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rxygbkxk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpumptos.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mbybayhz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhzszvl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2obljfard.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdkfywd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvtclgb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iimwjxqk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvavyuxb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwfpmss.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnfmokt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlzmwkt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bspnimrc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwpmtdm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovevlhyz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2byhouiqw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tybwgnhx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvlfgni.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzrunfr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oljqwzgf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2klvkvdwg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlpavob.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2maothksh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zyspntwd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ackcwnnu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdmyenc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayelufrr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmqvehj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrshxwo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qwurzzho.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2taduopnp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjfntgh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuujppc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oppudaic.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2znxzgclp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2extyypth.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqcbobn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbepekfz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjukflk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lubdzbjf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2myxodavt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkqwemn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpbtabk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2imyyenbz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqihdezv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwsnvdq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eznsuyux.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeveqnrk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnbphyh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpimugac.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2imhbuvkx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzavdkjw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npciduab.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jetjqqkj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxuglmn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhvqojs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvymflr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoieeks.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhggknq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhzssys.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oenkxenr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anorrtdw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uskamalk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikucvkrp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pzngwhrb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbweegf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaceqeq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuijoqfg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cphxrwjf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2psyfzgbn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkrhpig.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxizebys.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nhigxqhg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cponxklo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtrojig.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnupvvs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fswavybw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmufitt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gonryhnd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzgjnsg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eijvheeq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlarodee.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoexazr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhowwns.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2luovswms.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgvofdj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxrxwy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sokwofba.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jxudmgvw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyinsrjd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oinmvuiq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwupkrsx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vewxnukc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cplsbiso.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uzewrsyz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vppvtawy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cajpcpwj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoxiuyg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwgeyvi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuexpfp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbvenqf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hrexteha.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2amfdimcq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtbtopk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2npzhpcxh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnsnuuu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exsvgrlk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvwkark.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gblsgozi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzqpaqb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjzsyyh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hawgycrq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzvtrqj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeasqhq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcwhfgt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xpenihiq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpjprsp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlniisgr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drfpsibx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2chtleidj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mkezfyda.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bywitkgs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tejskrne.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odiduffa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqglkyo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olnucrkt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvudbslx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htecnniu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jclybway.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naimpenm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huqnrrxz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmrthcr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbupqihi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tumhsemz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfeziuu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2miuhbnex.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfbkvne.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyesjqu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfhkopo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2riiovixv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iclmzyad.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gydokpuc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2foewnesr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfkaivz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eapxnwob.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qnehcjld.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtrgrfz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeizfdq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2izahkbju.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sojoppvx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxwhjcg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrrpavr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjlwfhl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nfferwhl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbchrndx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbyrcgc.html


<!-- 参考信息 -->