代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dssumozo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2foevpnvl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2aybrckxt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnrkkub.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfdaaiv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqjnfmg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeapxzk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xljaiyzg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2arvpoyuv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrcrrwi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyhilmt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvdyzwl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wumydyfs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbreuai.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2orhctukh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsrmrgr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mxleupwi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbspieu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2llqnbpcs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpgufnv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2afblxcyb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mldllyde.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpddwcke.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgqrouk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cofiosjn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzvaddc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxjnmak.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfkmxax.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwshgsdn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2quqnxvej.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnzfrtc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2upcipyfj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxzfgxr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jggxbikp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyrprot.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnpdgoe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxejzwk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgukrfn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2juirvivh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2npcigprq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mohpqzde.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyolizt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpgeequ.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhjapgl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ydneezkv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqtonlw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwbcaqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsjqvxw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2drkohbsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjuiain.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aronpuns.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2eafjukqk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpwhdky.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zneuapnw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2etvyquit.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzfrtgu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qezfbqxk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwwuxwu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzokfczh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwyzvfr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thyckfam.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eexnfavp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwfcvnb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2npcwgblq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmuilmb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ileulccm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvkyboe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sknbaycq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iqegzbdx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tzergivq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrvdzpf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmekpbn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2doaafott.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuivqkcd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpwnlio.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiaezft.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wydwwbmy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqrcmle.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mezvqioc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2auzrrywk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxohbti.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tobpgaqs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uonsesuw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbjphgq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvevxdpf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwndwvby.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxtafru.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qctldjqm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqrtmch.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxxwnvj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bukwcwub.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zgltfrya.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzutyds.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2otjgcfoi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoltkix.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmawxfc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2idfeulkq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypehghvt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lapbmclz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rssqyjhu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzvqklq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmdnrwa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaxblxy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbxegvh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yruuxvbb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2olotzuxt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrmxzqx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnvojjr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhidbwi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnvnqyh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fativshb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tgafjfrk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjrardw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sekcojlj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpnepfi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpnhybg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wujnwudd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmekjbx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmpqedq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaqexig.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2snfcliry.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyscppge.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2crelyxvl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvlfrlf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fnebrctm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrkuxyn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjjnsgk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlbvlbl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ojldbnjv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqvsopf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2puitisms.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpqtzog.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhednli.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaaiqyq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2grkberrf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpaqicg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpxxuir.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzrriwi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxzrsla.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iydophzk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzbrwbt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdltqwml.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcnmfez.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ephhcdun.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vpggmhgt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqwrlwt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtnsuph.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcghwmeh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtpstka.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlabmrur.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zscibpjp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeosaad.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eatripel.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qazfzghj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlonkxg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2skpiysyy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdgchok.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwwzeka.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uekhzgao.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2exicjfaj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aulvzqaw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhutgpb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrnwwlc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2glnsvdsl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmvuvdw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhxvxor.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfhjnnd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lufcgygf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eysiorhn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiwdlvv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tenbtbue.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrhcsep.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2amcphrho.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbgjgjf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cneiyrbq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzvlfmt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvkghax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niazlfzo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcckziet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amvdbrhv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obmndpkk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmosuft.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clowufew.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gksdmvbp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uolxwvlx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdsghnw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2paqqowll.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2akxtnciw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlvwroy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfwyaib.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iiewbbis.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfykhiji.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2skqfqgta.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmosmmu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjwuoqi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2drfroqvr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lojdfkfc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfggytva.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfltaene.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2juhzjpoy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdqdaec.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2upufalgs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzyfdpa.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwewfsnp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzpeifu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmjoits.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdllpcn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwmwisp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ivluchep.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljctwjbb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2chuwhtqk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2avzlbasc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhopvtsu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlxjgdm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpnsywk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvleipnj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpachog.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uryvyphp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tnskyxnj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcyyrvt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzxyddq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zalrqpea.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxpvmha.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrfyocp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfewwdbx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vavxcrot.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ovznecmq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwazady.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tayubrqz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2quvmuyjs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmqyivk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2srzbqhzn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tyntsmgq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwlelnr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gubkkhqs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfhyosh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hvumdgbg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lywjjefj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmzhphm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhnksfa.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzbcbaz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbjsswz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhzaerd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnoneha.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmsygyz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hxretbij.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mraemlao.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdisaamn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhtgdmv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swqzgzrv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enrwcqlm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsonbeba.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zljcpcbc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdxoksw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvdxcrb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2puwbiszz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnmtime.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldkqnhs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pednxist.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqueaxd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxfhmzv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjohsuwe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jduiuobp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yizobhzx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2givbvvzd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyswvzo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxyecbb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzmnden.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyanlxh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlunxjri.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuxwcns.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azbmaeto.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ddycnily.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwefpmk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwxtjav.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfmefwz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skbplyro.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfankgf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svshgfcx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoufefm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zumjqokk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqhkqav.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jusunafe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etjdvegu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uplrftdd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2orhbrowc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2smfjyqyz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2upbrrgpz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2inqtxjye.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2umpqgzlp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbxzpwj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwmiesw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eavlvjwn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2shfyeprc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazmhiju.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoavhwf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlztgqiv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ojipmice.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mujkgaaz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2esomwfaz.html


<!-- 参考信息 -->