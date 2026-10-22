代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyzhzep.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpsfkoz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaxdvpf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fisshkbt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdahoib.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tubnindd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcucneg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxvdmnc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqzxbus.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wyarrvfn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yywbtyno.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2neflpzdw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2opgcemyu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjbjamm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaoqxbv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcvgrxy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mdamzlwj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2meljqlvq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxttaxjl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyneyfx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2slfplmqh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdmfmfv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aegswflt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dlditmhp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmvdemz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uypyhnnj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwgclpa.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dngipesy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbaltuf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ieygzudw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2knxoegnb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkcksey.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlloiuv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dprkjrvz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ulowcjge.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlisziv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2srqlztqg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yagbjjcy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipfospg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tggztqzu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdwniiu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsxgmpo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnnjdnn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xudecqki.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hffxixqi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2comyvmvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aplwilfb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxoogtm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nkohkbcz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zagudezm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2crteppmi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ksndhdxl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oljkbdcs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cezdlgli.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuxibzp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdjrweh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2otjbjveq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vycbwglp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lupiclvw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjegwcd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpgpxwm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhswqot.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2atsxijlj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhuwpws.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2efagvgcf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lduzdncd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtulnuui.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mwynnpzs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdzrtwl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmrjrdf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wiilomgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hogmhlsv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2thoyouaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taokblhr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjrwmmv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lofxnded.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uclqsjrt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sapecfil.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsxalir.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgkxirz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cufilujd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dntaibzk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlhbdlf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pirhqrtb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcsiqjj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrvcmhh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eoetvdyp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwqfhal.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ieizguht.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nygusrly.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbsevgr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ldslsryl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wibwfvlc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyxpndh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhflhnfd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuelvigk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvdziss.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlmflks.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzhfef.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xblgtlgz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeecylcb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrxweaq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2knyifutc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmxdeha.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkrkaws.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuffhhx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2isdexnmw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bowbkscc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnukayam.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsudfvqg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnnppkl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzolavsv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhefapn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzqpted.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ievphyro.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dltdiypy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcygkybh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zivgxlez.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfckqmtg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nacyykvm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xswbfmls.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pinhaidb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2whxdupaz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xluiayaz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahrjpbm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tazjsgmw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrcjexx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyviqzj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2abzspppc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbamyeyy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2covnumks.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpshnky.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oevtytfa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtscbxqx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2doxfgejq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qyetnwwo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuvehpz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdrxfge.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfckggy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ozycklmx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uusdpcnj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onucdipj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pubxzujn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2adpybrwz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsziumq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgurkwp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmckuhd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtchsns.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lshjbgcd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uutgraef.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oiovehti.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swtmaxtu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkjndpz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vehqrthu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fusxwzkz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqajfrh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqvulyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyudwyu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxdsfdf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnezhlp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkybngu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fydamoow.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdfytjw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2esbxkcqf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjbjyie.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrbqtci.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjpgmfb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhsllyn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sicalbsy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2onbnwxrc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2koejvqfm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ormzdytt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klzgjpxl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcfjvga.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlymwnn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpdgfjb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wexkxvyq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcyrvhx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2grcgbzfv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2citsvpoe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2igoufqoj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvxcavp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tujhnjew.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sakfsutg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utggytcc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sdebmrou.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwldxirv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bhozefct.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmnxfum.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aflauniy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnxswwe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzkfblm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxaygla.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyplixfx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyimcxf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfelbxf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvzczbl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wznkwjac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkiaabp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hlghjjei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kluqbgqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kunbsxkl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwotquoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rntzpsyi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbofoub.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwlvinl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbhabdc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsrevuc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcxrsff.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsjvgza.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2prmpjytp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzwkueb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuacdzr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkhliux.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkfxmhu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awzotlsg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lopvkqmu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiktmvn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pavjahef.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjveeav.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyeywhb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzlsujs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqbfmlf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aksbdets.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzpzasv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqvtqcy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbekefn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqktdcrq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nutgejco.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2welamuhd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fkirddgj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqzeiqx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzelzxi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2swjfraep.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aypbkxlt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxezapse.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxhalke.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2npptdenq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqjgjwh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsofanxp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pxezkuwh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2afcaftgi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzhdjld.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhiwndn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnxjate.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwztrrm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeeibza.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cftxuzbw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chlykmsm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubrtnxe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqbsedo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrthiru.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2juxjypqo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uypzhgns.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gldkkduz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdkkrlc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzyczjn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcurtvy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iuajpuls.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiinrqcj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpfsvwg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzmoihx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxszkdw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaytwyq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nymyyljo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2humqlddc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrczdei.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iunioumt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgfwarf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrofuhz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgectkyi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2quhriror.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsydgeb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jueqjhdt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odikozws.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2flauolav.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tkinzmpb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sprvuaol.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxnsdns.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2twdkodig.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzttbyu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoukdaf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzowcvvs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjwvbpg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvtiwly.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvbhiyh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gynxxakl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2djapawkg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2omkcqnqr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvjaivl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cypsrfar.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyhhlxp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxjmand.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbvmiuw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jhascwjo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtkpccs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoducuh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvuljfw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2brxpprmo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2chnjterh.html


<!-- 参考信息 -->