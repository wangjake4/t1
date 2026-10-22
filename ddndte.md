代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgfrfog.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzrrovg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bklbsnuk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xshnuscv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqaokip.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ujakrnvl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2huzhbjdx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qttxrpdd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwowqwg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zimpudbj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmgambe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgzntda.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnlpyiz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2znjucklo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kksiluse.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hjykzuwf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sqocxclt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbshjqmf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmuipwj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pslgyxbr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pciuhtuj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vntsdpfe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2akcvfxss.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nreryjvw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbwbtcp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sarubjwt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxlddmp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrcncsf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwuayow.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mevqprgw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eozrencz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2icdxespy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2orbonhjo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ehipotfm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2aukykgvg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpyvvog.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcralqn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wviruchf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zybilkdt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgogfjc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yllmzrrx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtyfsrq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwlvegi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhpbxwc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoccoar.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rucacdbd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lrznrhwa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhjvkgv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2flahmlis.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2brnfamim.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rigkwatt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ckobwfxf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omhfktuc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lezrjtqw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqinehr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioumskyq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2flbirrag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhftxcc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxrbtpp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pajagidh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwysdlr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwfqlkd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxvnost.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqgtckb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2chotkuwu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2geymbrrq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vshifgwu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqwawwb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efmejaep.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upneuiit.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhsaots.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yavrvqdn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2olvfoylo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjkbqlh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlfkckf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2phbaqmrp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsbgwol.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlchoim.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtoxsjx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gagspufz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2suyftbda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxuwokt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbymbqm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpncevc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pioqwsny.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtcyekl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2njguzcgl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbessvx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nshysiso.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xorcicsi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrwxthy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lezhvypo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnstjtko.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2knjwblzz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgaqnww.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfibars.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2afhvkmbb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxezlap.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2edrgalpf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvghtye.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lchduzpr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxbcdka.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpyebfl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvmzorh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2phfvuszs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mblgktwi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2heprolnb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpqbbfy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fldbfrwc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsnwoxy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbsqeko.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vchnuydu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2czzkavxl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qympzbmt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtsxmzw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yobxpefl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjbpcnq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jreepfpo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbutbiz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyezamk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ooshccbo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvmkqig.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlerauj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxkcivc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qkupgrjd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjtuouv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2idroanfq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2imftxkjp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsomalv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxbhhal.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpjvgmn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itsebvhc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvtvpto.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2apdtcjwl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2umxonjcc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joxnmykb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2chyezkwa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eksytigl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vltpctcp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpdoyxd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qunzrqca.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kuztfwgb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvapbzb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qskffvkd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgafpqj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2keksugyb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfvoelj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxljlgd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgwaijm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsqqlwr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhbxkgy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blijovbf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxtlfws.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxblokix.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgkcjtm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cydpizue.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvfplay.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edelsmii.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gafharjx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyrlfyj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xszigbze.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxohpan.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgosbptk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsdywda.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2blnqaztb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuukkxi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwtlwmf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmancmb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gahkskuf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wujctxuz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuftiyw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgjsgrq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyhfjge.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjmlivm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoqfwcg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqwkpzn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nylpkogw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2almakbsr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhatngxk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsjezcv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbkfyhz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvqnvsk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2klrjskgp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsmssle.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nlibpzzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hndtejvm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrlqgne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rilmlbej.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvhfgxr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjomlwf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ierwyanc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaisjgp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqmtmyk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2glduablg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhfhbbv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cukgafwu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpbywgn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoezvyy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kpttdmsz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjvjcgj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wwefegbt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwauhrjp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2srlbzryh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2adieksed.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsxomvs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkabngb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjhxouz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfdvbck.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnpscrr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbobpho.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtljlyp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjicbte.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwgohkt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlguknv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkmuzeh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dosqdfhv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyanijn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxrxuft.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaagbfv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hghyqcxb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2atjzjqax.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlariyx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2stsnhczd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2imeimyop.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcymmxj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnlioxa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2soxzmpot.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2feyzdaac.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axgrzhoj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqtmgcm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exkxdprq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuevrdp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiuasjg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdufmyvx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wyblkzwr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgxhszu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrjbzxs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yujqtmok.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwrwfqu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeccrtzx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nylvhnhi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2krhgwjgm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tecgftva.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjruycc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qsacasqs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmhheym.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxcwazz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzcxalv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlojhqnr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2durliqqw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaezsik.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvbmqnr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ponqufkh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyvmdcd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pswlkzxr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyrhnnd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2quvjnwqz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2juodhmtg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2llmuehcb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2imiqnyvi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwntmjms.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eluxzvhv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2elznhqle.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dywxduka.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zianhpva.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfyurtb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yujzgttx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2krckmwlv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnyripn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzddwdio.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nopevckw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsfjpty.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwowzcd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrivrvqo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jejcguyh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiqnrwa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sktsjgkh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggffqawr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfednnp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luotlcbf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2phzhmhtk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trirnsqd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elmpgxow.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzxmyus.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjhklqw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvdoeyg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyufupsz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwciyqb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afxgheyo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fijmlmln.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmhoanm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kicguewe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qzytzrzg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsxndcu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdzajjw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnowrpp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqihoczg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwqioko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnhwqzq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrmgomf.html


<!-- 参考信息 -->