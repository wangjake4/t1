代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2azrwvzub.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjvuahm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umqwanpq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qhddzxzq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uikcfwbh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaioouq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrfcmfl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2erepqnuo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxifkyo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqvmolq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tclycggm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrkzvh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fccvjozx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnugedk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bispbkqc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vvixjjga.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaumfwr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdafuqds.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxksjs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aecdowgt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gdevfxql.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvfjsyb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuhxoth.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2werpbssw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlggtqi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ubekmkxq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wffilzuz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tyundgka.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxhbtlt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxjjgof.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2clkobaoo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jguicoux.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2huxbovte.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqzwpdr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjhqzlp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaxuelg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2buirgtbc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdyejxq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpcwrrb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwtqkun.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaimjss.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2suxmvsns.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeflzuu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgbbrje.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nezahnet.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ormugjwt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhngzcyy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fepewchx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxapzqqz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbkkbpy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2egmgyxwa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tiepglgl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkuyfvu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2szpxlqnn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eofuemcx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsicuzc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nymyvgpn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxtqvwq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkxmlsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgtuosg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qdclmebc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owsjqjao.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bthokozq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2peiuppxi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjefclx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fclblyau.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uanvvsoj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkmocii.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrijikc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzmgelh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2weliajzx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbdhesw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrhbrbg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dncylhsa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2edthblyw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rnurtewz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mecblnyk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sljzwzpc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgsbjs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mjostbnb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxlisqh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiewvym.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dttauqkb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iiftobzp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfhupvm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiixypd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkemwmr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nosrglrr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeafosyi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwnjrnl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrusugb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbyvlhc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwtxsjo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bemxjkli.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbipzkcp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2idmtdovx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgtnhsr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jikutdug.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcbyiyw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmslqabh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iytyggua.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgitnotv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lekqfbhr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqkehie.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrczugca.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjjwkyh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkcypxd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yevhahjv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzslirbk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhepmltd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yssealfg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzflbpr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpufkmzh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmayixq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnfymfr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ucttjmef.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmxukju.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnstbcl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2flsjjdfz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swwakxwf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2efnartoe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwblbev.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwufvtdl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzjodqc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ovedmslc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qacnbnwt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsweiif.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtdznyu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ovylpaqh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umezayaf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zseukfga.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaeprqr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhtilbn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbmnfie.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxkpvch.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkahpjgi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoficxr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaakdxyh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sygthhyb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yflihput.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjslbtg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvytgjio.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vshiochr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpimwxz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2efdgadpt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2krvoeskd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgmctnu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gysvdcsr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfcncud.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wblygezf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eusvhgbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cburyifa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oyztbitl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2isoemvdx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lpysgxsq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuakirq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjzifud.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2figvmtpz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hukdowid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frgujcel.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkrosyc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ethldofj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrsbszc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiebdvqa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuxedno.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euzmgnpz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2caltwsvm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjekxns.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhbctai.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2casplhnk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgoiaax.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgociey.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esxdysfk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kckutwqt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeaboww.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2saricojx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxlbfct.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rdumhdop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cifktzpj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kaafoyfo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfhtehk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsnvevy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrwpelx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xuonzbxl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aacxokql.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qtczagov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtetsagj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhgrnjs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdpgtay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbfmjwx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2annukeez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2perzxqik.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlufsas.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeztajr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opowfohz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2broeogve.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iveqcwjj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvoojkx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyyende.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iicozrqv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmgncrh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fllpveit.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pivbuhxd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2imfivyzg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbhnsib.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvgrecm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmstxll.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwdlfkc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjrrmwv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lftvvqrn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2envcnraf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpqlayc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vkescgup.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lreybzal.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fnalirgk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppolilzz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwvnrcr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfqpdou.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aunkvjbo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtodfzu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aunnbqub.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebdxxi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcndpbdl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cujzaggh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwhplie.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzdhyvs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lezzhsng.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkkpufd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fturzsyl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2puelltqc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2okhdkylm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aawvsgsk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqymtzq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvzhhwc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzaequf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guppsbps.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzpwmll.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzupshmv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2roulwdsl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpixxws.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rupfbxdd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2feuwuost.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyqftzf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pacacwds.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2thxwffea.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuudnnjo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjxijzg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcsxfub.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdytcba.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyumzjhv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuivgwg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2alhhzpmi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuymzlb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2psvypbcy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrfvjyo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mveuhiwq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2daykuwzx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnnqanc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhvstls.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vkanktdt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyjkpec.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhjftaa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olgssxus.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqhbnsy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaauvgs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmsrulf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxucxhzp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fyowrtpi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oamvmsfu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2srffbetq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjindfq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrxyjce.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzhoeze.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrjjycy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cohaxomo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2upzxinsi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zflsxjwx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2edpvcbop.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dydltljl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhibgne.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rljgueck.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saxklibr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oibgnqce.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tihlhdea.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tezxhltf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmodgfcr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iraxettx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2agbubepx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuzboad.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suyxhijy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pajfdkrv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2itaeyjki.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbovvtji.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfzreug.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbohpszo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpydhmp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frjuxdgt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmhbqqo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxpxfxg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eptabawl.html


<!-- 参考信息 -->