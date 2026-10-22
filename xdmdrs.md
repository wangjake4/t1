代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnoedbu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2glfwqpsg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apkoejxz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqmplw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2neqftdyy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrztjge.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiydget.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsivmlx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsybdxg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2teztjkzv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2exnexovc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2khqdnpym.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hawyftnu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqvttib.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nkesilph.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2izqvvfzx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2thosadnn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eccmceux.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqgydlc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvmsssi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2opebffir.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmuwchz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkyxtyh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhnkavg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjgomcr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdyfdft.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uugffwla.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oexyvgqf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjuqxso.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfpozwu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oisvpmdp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfumfiz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrbfgfa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwuhoen.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmimvsz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmldzbjn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eluuyukh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owhyawoy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbwpuzb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtabudrp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwrngik.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nosnrknf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkxzzhc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qazgllrc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfrjkfe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fbybfhwu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nehbmovz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyfmlij.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2siwjkccw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2soaizhtt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrvqhyb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cklyxjbm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2irjrmqrn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxeyylf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jigbuxlj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqegoxst.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2okrmhenw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlfhxzq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbfhaab.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2thfryzyt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uonpkjrd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ueowknta.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xobftfjn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsrnzxt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urxywyiy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqedqdp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2atbaujer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpkbssz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnqsibg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmepdxf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfksbfvc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tydzurha.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aidequyu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uikgfwar.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vihsmryy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdspigl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeyyjwo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2onzqfjxn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkicxbd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2koysdnvk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvddfbf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmqkymp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtvcqxn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dbycafwz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ezczowmt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeajziw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tngjuxsm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2loianvwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcwgywj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcpwovl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aevkdbhx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mquqialx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lemjyqfp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdopgrd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2idfvbpms.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhocroz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzadjyfm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmguvwbc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqojeyvb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hbonlrjj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yufdfwqx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abzqecpo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jclbqvzc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbrlboi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeqkmwd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2utebbizc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2skynptre.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czgbautq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzfnkcf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rddisxwm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcitjog.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcutflp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyuobts.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlyxmul.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrvsuyx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wzseqsmz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2emlntzea.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrfhcle.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgunxgxj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uspoixqm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2atwxjoym.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhplvlb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiteryaz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnwsmne.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hglfinbq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zofkfblv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrqyxvl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeakwqq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuxmqce.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfslltuu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnmyifd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhoknlk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbbzato.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mwktpilk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrtienh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yubwgzan.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqjqjmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlbzwen.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2raxgtgua.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzxhqmy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ociulcko.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxthbgmw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2arslwdxz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyemcldi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2csytwwyl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqfyosc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgnxnuw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyiawzv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgfssea.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkcdrlw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxavrbj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2futzvmqh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tflybsgy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rovskryx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxzkxbz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyqhjiw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnztpnkp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdlbxpi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfozyus.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwlamse.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrzhtbz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2exofrifv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aktuewhz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmoqquw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsicyaq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kswvordo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnukdwm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoqiqdn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkoncmm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqdnroc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2copdstiq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoglhid.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcntnvia.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlszibdu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeulmyu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxdftnt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjfahmt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oebuvosu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2trdidqdl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2auisnygd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmrxswi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2leyvpgok.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjbrxnp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2apqdqixq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2arqyvmrj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cmggqogk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2asbhkyam.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxcyvsp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlywmpvw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xueseyjw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lupmzubs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwiaaxn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaikynw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hphygfve.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlovygoc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvunlth.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2izpjfwdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyklbyu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2noxkapyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlviqldj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdkxbna.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hstmlnti.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfyavro.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rfavhndm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tupmbqic.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aetzlruk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkmbtdm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmjlikx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2suefgzvh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vwafsznf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2obzwkhov.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmcsvyp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpnhxgz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkiglzt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwpqwvl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgrkhwt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drxzocmd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyahbjek.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwcsmzs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gymxhohk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcskcbb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiyuiaf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hunojcgw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sikdsrte.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2axccndxv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgcmkii.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tswlrkgm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqrbtzo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nmebhqga.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcinqga.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smcykmpg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yspavinj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzvaxcd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2howyhfsb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgijssib.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqpejyo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjpcrbl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiegfgzu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgpupjw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnttxdmi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnhqxmw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqxarff.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xgppdbaj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvvkorc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiqkkgj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2itpqnnck.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyjrbth.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2undhhest.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wnixsdlu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdcreal.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gzywolbo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmciriz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkrlzev.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2atiiavxa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyzqqvt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dagljdvq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2apgdjkej.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2edtmoucc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uoucwzid.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2okaxizbs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnrzjlk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygompjpw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkzxhsd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjrkflh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxzwonr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrwcqva.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2grdnqiko.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2llwfbqwi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2obgjesgh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxxbnio.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbfjumc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlspvat.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgtnqhj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hedgrdlt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2odsgieri.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfejxud.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xyssxmxl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgkvrud.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbptmuy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dugszeuv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2huripbah.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2onrqddfu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tchuzbub.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaixhrqm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvnftkf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyppeey.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sajsttgf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuwmjxn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kmowdmbk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdndmou.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfwytdb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpgfbxd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmtgbkt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcsnmnf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkjyevp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vclrvfit.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxtkdbz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otpaurfi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kixamczq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhdzoin.html


<!-- 参考信息 -->