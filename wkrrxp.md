代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2httlalzc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xaildtvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyspatr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cajoghcf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqgsohz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jedmfapj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chywjauv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmdkfxj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mdykkpyt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhetxka.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhhualt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjpzxar.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kexrhjpo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsodykm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcpiczm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2royseeus.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfueoou.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2axpvymec.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oblskdzp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2scgwdulv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2epwkzxem.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzdoptk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxsvrjr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfaawwm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzwieic.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2syxissmc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbnzkke.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkxvfaz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkvhkxc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjbdvsf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2smsrvysl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvrtibe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uajlmzyb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hiymwqtp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjuksnw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhclhgv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2urusqlhb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2toidcgnh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlxzgxx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvvylav.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2obhspqlh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aumbttsm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbviecg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbmtckh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2eacydaib.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkfyhws.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tqajlrfa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjzjamd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsuedqr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdocdso.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgkjlvw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aaklshky.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkfwqyt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eiglocxh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fphfochs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiwtnrv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2luhkjbee.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfjofrd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyjkapx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lymybyvd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qcumacwq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kosnpbsc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzfjnij.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bueuhjtm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrmumro.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmmbwne.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ieurdffp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdffwqm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mffjyxie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnhcbai.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyqugsc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xicetcxh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoubbfi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2atlfalsj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaakiuxi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiyxahe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlepbxb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vbekvwqd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ataakali.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kirtowec.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbqhgfz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbckxfs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ujknsnhg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2csclrzcz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgiugqv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdxcrjx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdmtdh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnoahwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ashclarf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbdzdcl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgkzkbg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeuwoiw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjefxxgi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiulmal.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkgvqaj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzquivn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2slboemyi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvbdofk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfvcrau.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvypmqqn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mewglrig.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaytfys.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpyucwd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyobyrk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvqukiv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkrqgrm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2udfocggh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxpqbeq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsyreli.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsaumll.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eznkrpzx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoxoojr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbgbrms.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bagosfab.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yffzciio.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mwonelmr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ingiffzf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fphowdvo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlimcmuu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gfthtbhn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2phypqzfk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2olzfuemn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rehcuzrt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxbjxse.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaoayfd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxqlgil.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qglmeyfc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgpywji.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqclhnz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfccmcsd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwhliss.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpbrmjc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zszscpdt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvtdokh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvdejis.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjvycdn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2carxhosp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxkrnwc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxtixlg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcttbqh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hpztequk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fymeepou.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cefwilsc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmxxdxb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxeriuz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctasdeel.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wufwdwya.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naalrqmw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjpghmb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdefrjb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uepoddjk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaxndid.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnqrssu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeghcll.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgosaee.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jstvfaqp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pumeyzck.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fynswqni.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smzoqpsw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijofwvby.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2swlhwfqj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2exzefmfy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kijglhgl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbhwnbr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2flfirtdw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlngiogc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ndltdcqr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whtpeqks.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwtzazq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjewlpxk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqfvuxz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhefcfp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bacwkswa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaajroig.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqevcxy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dttxrruh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgapzxdq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2feaercfr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zccarqtt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjwjfdp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tderptxy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ooobyxes.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2opohmjpu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uveiigyx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2imipqqsj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqliphx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqiiwfd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoqghjs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrycvphj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkihzope.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiirvapk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswrwok.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2djilwmrw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xmentxhj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfmhhms.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoisngj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaulcyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kukaaflv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2geatjaht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niuamtti.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btozhcts.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdyxtfu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itanrdkt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkgjzti.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2etqiwpok.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgrmyez.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zfboyfnp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdvyhwj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2olyrrjjt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlkacec.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfciwwk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuogwylc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfmpngo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwgrycp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2msqwrpfo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbhwxdf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbpwhgj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iagdvwcc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2upatukbh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvilxgby.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2puqxcxfs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsksekmw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiutppq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzdrqjj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqrmmbu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqooakgn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kchhmfhc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrpznbo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eayaqhfs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbuzgzu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsroglmt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2levpusux.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cuztqmzo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqethdac.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmgivbi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlcldwj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmfibsh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iybscpoa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxixtzp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2inikhhig.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbfstbv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpsrawm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cqekxhau.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2srijysoc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inngjlcc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgojddv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqvzyfd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2meaiyiyv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zyytnhmm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwhfotz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrxzmwg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2asohsehq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgakoqmp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcukgyqr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdiqchw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2eosmqnbb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxelsra.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzrcnps.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bsymknys.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mukpazja.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuhwhjy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdanlhx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvosmgp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lahimvqz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzvcret.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfwfkyu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2phhpshhe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcxdfvi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyvicqu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ieazfvui.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idctjmua.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgdfyys.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eheekwjz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yezaljkc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtmstqz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rieamdsi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrkxxxk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrrckgm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jppubcwq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhsdqdx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbjgiih.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsblvoyk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xffmobkf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whoxljnd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwvmmli.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiorkin.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbvhpqz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fguxpqms.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfkhvmw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmejvens.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2msmflysx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfiuqyb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdrujdt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsiekti.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsohief.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2twcelnix.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idskcvuc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxflaobp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zelntbnc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffckdhtc.html


<!-- 参考信息 -->