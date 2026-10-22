代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rorkalqn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyklzdr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ackotolf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsnfxgr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvusnnb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lbslfami.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tajtsqze.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyoyvzc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2looboqbq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfzevmy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqaqlya.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2huatfbpz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kdijscht.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cavmrwsv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gajzeysr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tozvxvmk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uisfxyab.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmzanjg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvarntq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgxephj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuyksjd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2liysbvds.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhcoeyw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaprjav.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2stalggin.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2alxqxcda.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmszosn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jifcdsqb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpxqlms.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyffqvy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmpeyds.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvgizaf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuhannj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cgozrvxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eookrssw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxtewgy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsnmjgj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2embqdwld.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ngervpbw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjrrrsz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2alvtxmuv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaiuoni.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtfeosc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuoroks.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrqvxcl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjpnkrm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbhjeaa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fwktudon.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvrgenm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lliakrho.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyklvycs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtunfqb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2muizdujj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jpladrqn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiprqif.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnqpvrr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rknfkqeb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjajvti.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2haogpfwo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmaiztd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2akmxizvl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvlkyiz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwstysvl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzombaz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gufhnixk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkssbizs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfejzef.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtppcvw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhvsvnv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsvgtgd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mujzrzvt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2smzppcgb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2buentgus.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vcapccqs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdvittg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxoxryn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rxstimbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nscfqbwm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsfyuwv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiceinp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwehllw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tzppgzfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtljjdrt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmagaicj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wubwcarq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sburivry.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkewokae.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnnssty.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eomafjct.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xduvvwzo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2orhztovu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cijztmpq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aitgwoxo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2omtuywej.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaghdvt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ayawwqpn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jykojnea.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnbzsgs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zflitphn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2daiocmll.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtzmftw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqspetto.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdixjwhy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcppwyaq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eywmoain.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2farumhvb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbefkoqm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzuhsiy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2njterqtz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwltsvew.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxqatzo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dafdpsdu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnnchks.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfgyyjk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xytcyggy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaceqwiw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2muzsvqvh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpulbxi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmufwsmc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2skjebfzx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkkofvr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2smtjehns.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tygvurav.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xhugrehf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqrfjwy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uujilhhk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjxfxcf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dybgudbo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjlhrnb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbhkqvj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nerltuyu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvyjtjf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnsydgm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaudgdf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkumfbq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyjiwrq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2crehoqrd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnfxuiq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfabxhp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2butsxehr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbukoti.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmsvnek.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hijrmhxf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzmmhux.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwpucm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awspxywe.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lebcomvh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2esbshbtg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjwbjmh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsqzscs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjmjlqr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiltgzl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbpftxo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oupxczbe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqvvgdc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2czzvvodu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnpjvux.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2twkeqpfb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zoylmtpx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hxadiblz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aejeybvh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2evclwjoz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ubknudcp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfyzflf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfbjqes.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgserej.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhtkjtb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gumaxffo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyjoyxe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2phubvzhd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qfulchex.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjielcj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oedzujqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2crdfzdfs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tavjvcey.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdsqkok.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oydbocmq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqyjafz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkxqdsm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhxlgqp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcxhwat.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxomehy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozscgkdw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zujebgyh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzjnjkn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrbmowx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkrgwog.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2otpdgczv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2occlewob.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nldjqhnk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uweqlfvb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cabidglp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpdxtzy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oqycvxlq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2srbmpifm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pdurdcvr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmodgxes.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2topvlrwt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fppvelka.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ebepobis.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wapuqiyk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wtboxace.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqmrdoz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2balilkry.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhjjhea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kplmoytj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaknaqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwemrcmf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrkiewg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtefjhc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znekajna.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfcbqtz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzgppeg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcqpuhg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iiosowjk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yggreowz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2igrplppr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wknvqslr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxeiskh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlzqxwe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jzinoumw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2igycyypl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qncgzpgv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2csupljds.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jchseowx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2psvqntmb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxwnxwl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiefpfn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuuaafp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2txnlrpnv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyizdyi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iilvryvx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sofncusn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyvfpaa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2livzyudk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2frbmkvxz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ssopthzk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbossew.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtlsiec.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcwbnwc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdubft.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuebecb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yweqfwgl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmyfaxk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2psvihuko.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsawkops.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mifolivn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyounhp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdnqygj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wticytjd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcqxcbg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kchdswdo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyqqwaj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeauzxqo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfpbzvd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zibatnyi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2knglwttp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaskayej.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mldbmbsy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjewadja.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lujlodxz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiepnasb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsudtyp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uetfflyh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhoqhfy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgssthhc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwxmfzj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqkgqci.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuixnoc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyqkfyk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeihyanx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rcylajua.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfhivwd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dzypnjdr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcayhhmv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrifywj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmadacwh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yldqymob.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgwgqnf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdnqaou.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2moqqvagj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhevvud.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrduivsi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxehspji.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2evdnbhyj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zioevlzf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrscenkm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rhayxhco.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuwiiil.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oyswiliy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rezmrmpp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2niifidcs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpikprl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2advbryxx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrdnetx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpnctbi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gnustvxp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmdmhys.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmqzdc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgynmpeq.html


<!-- 参考信息 -->