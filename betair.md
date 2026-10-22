代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2axntysth.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iughedoz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thkohpbd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjkxijd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vvukneru.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaxpeut.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kcthdstx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhqxfxg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2slqtlxbd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuawurz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tifikfmd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmfydwn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2olkqucry.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzxzigx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ricybaoy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlpjqtq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsmyhiw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsnetot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnrsvie.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yszgkqmq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qlufxnya.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjsuepa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jepplyew.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxzdijn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zcesjkda.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzijfkl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dknzbrzd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2abjziszy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyzonbd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2poigermi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2axfgxcol.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwutdpyp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yolrfdpc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqudfau.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwvugid.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2huhncnpd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2noejvqdw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhsxmvc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tujgsdbv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdgbrsz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dulbhwzx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuykczt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efhglbuj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwwjbbm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bkktultu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrgegst.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odvrhiuw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoaaefe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhlwtpx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exyknoxg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdlujds.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lorvouxm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrmwqvp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2serizokb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbsarsp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zveliklv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aofwcpip.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mridxqxc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqlfnmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bohjfkdz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgjxcsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbllzrzr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isxekxcc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2crahhfpk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvsrrde.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcqxccy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2idtdwvgb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xavigpmz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkmdchx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mubvumbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yycipicz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbittydm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmstifzm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2emjctwjo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rooqbumq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wetmuade.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtjvfea.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbslyuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qidcncpf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwlcmtp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uhshlwoj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nwittzgu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqqyioq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shpblnmn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcptwrew.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2reptwopq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwurmft.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnolsqg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbkjniu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gubuxjhc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eubzjzfo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ikynnkmx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsqqgpk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eodiccgs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhujstan.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2svmtjpeg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txauqorb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stmolvkh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvogamgg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsupihof.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktafsky.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbsvfvy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdmgyyq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cjweqfgd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fghjgcnq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rqphhjhv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvajhltu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmxdigh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nomvkofc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gamajupl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzewwdjy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfltejtd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyiasmu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwprwre.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclgnbbj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwsszac.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ricgqmad.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpajepf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tufcerwq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2caztzmec.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmewmfpr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdgjdhh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntohakbo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvzoxlx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eybxumrb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2czvnzatp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hdddfnua.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quiytqlm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhpjacq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwtadnx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvvincd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2destesbr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpggeqi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhdwcnx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjmtyvv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkabtdpp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dnavxdkh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsuicrd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rcljwuhs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mortcngd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bebnknyz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkypwifb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwsalwh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sofqdmrq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jisjgolh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhxiyoc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvphpugk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnxwwpf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aduyuatg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwlukfm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqilnvcq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuyedqg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xylxevdt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2htsktjjj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2acrqgbll.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlavize.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oslpkhew.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbajxrj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsuynzx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qumsagbf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqnsgdu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sppbgwtn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eykqocen.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuvzsna.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkomgwzr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tupbqksu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2efwispoj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxdgvfa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czeudeoq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndakxgbf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzvqegt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2szrnalqp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlcoval.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcwsfdb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sotsnpyf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2upxufrdo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2btqbzqzg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iwougdxq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmivpqs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nvddpivb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdwefth.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2enlxstkv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bseypmha.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xatiusbg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2radzlhfq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlapqbf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2htipugvt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnmiphg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2scmwmjaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suzrgwxw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcggces.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhjfzcp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2syiamoqs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sijwzmvv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpepipl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2amjtjmpi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2btnodmxy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2airoixaq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrhljsy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gncwfjzl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsbsrbx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fylkqxbi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqzpbyl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwghkapy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ihubstay.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpnsxeo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuohjlu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdwkfuf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvmbgtt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sszqscbg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spdymama.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwtadgt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zquanidf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjxggoa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2izwjcoht.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuqqref.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2egeyhsjn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jceqytem.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vosflklc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugocfgbu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqtpaer.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbtikah.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwncsbg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ergheszo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzgrzqy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmxiryl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaosdif.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqmytea.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvfvlqx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2znjurjqn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wxobwyvw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvvljog.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igpmistk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfwdpok.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmkgybd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2shnitnoy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxenvubk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sadljsgz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbvguqc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrjlrtl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsqimwz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdmnlmn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbbvlrz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2arouhnup.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yqulmnid.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsrfgrt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qkndjutx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuxjdlb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbvwbye.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aellmhpa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2udehpqfu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohiljem.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvirkneg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2atlskgwi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzydbsli.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akozpzls.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2efkipjly.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbdhlct.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsawpqo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaejuvn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rasptwyl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tueisyse.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyfddar.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xymwounx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxukrcb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lctlkcsr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2srsypwuu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtchdwyf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nheyrfhc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjjdtaq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqsvznq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgwwmgx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibobaqpt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jogjqgak.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oegohbre.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lribmbvh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfejlif.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmbnmdt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2akeuosjr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgvwkli.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lurncawu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otvdwmvl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iycdjsom.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sseilgpv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaixftj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmeafwl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rihykrxe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtmwjaf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvtfqxi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhnpcte.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfudctct.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpdufol.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqgympb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qegrvfyu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxubbctw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyzdfsa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdwlaea.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iadauywg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxqffnp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kveeqtxd.html


<!-- 参考信息 -->