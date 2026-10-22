代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2srakygka.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwjgpbq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yndhmmqf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qavozpvu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2krmtmlxa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxvsavm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjnomjy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzvhoxt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2olosmuhy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2plseztpw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfhcjbe.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzusgsfb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmeoiyc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wjblfdef.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nztfizym.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkmjtsb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmocfbp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvkhpbo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glxkgjfl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhmzlzi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpmujcv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uikogxvu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpwhwth.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2estjakru.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vplphlly.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2grxfslvv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2efpioyda.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxhzrke.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2llkempjp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eextgcmr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsvtwje.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2evbdtymj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uusdusxt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2egdhadmb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kuihbden.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxxqaas.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jlayvohl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuzzmfl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxujbjf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqjlttx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iorfhpeg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyxcmbd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbihlpm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsbdaaz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzqjexf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hykezrmw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkpjyux.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bobereyc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpvdsfg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2onhmnydi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgdaryp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmabnegd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaxeytz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iglktwdb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2koghzatc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbzdvxt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhqbnyf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfnpwbw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akdgqvkn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbucxtf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hofnegew.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rtworlbz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzfeqpu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aevjgtmx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnalhxfs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sicsxovd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxwbljn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2btmnrsru.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2icskdfbv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2slcscguw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaaqcpd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvpzppk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2supaqitr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzgvlng.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfagohg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2delldyog.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkzvvjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqlzkco.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cevohlda.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmfvpjj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iygijfxt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsmmcna.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzjpudm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtuhhmt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgtqoaq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2emlloovz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdkbjjy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2teihxrbe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2symlqzqq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2getrsgfk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbwvems.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxilttb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocickwqz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgjdjek.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xecwcxqz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzyrjuk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gymkroju.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hojchbln.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yurfdxft.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anrvswks.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnkvlbr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdmtlza.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtavoua.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llaoyarl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooppojjx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dznjwnct.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnnbszp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2voqroelq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofjxdt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dperofiw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnglmmiz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fokeodef.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfbbkuj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvaraln.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgebhk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cesdpcsa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cawaxbvi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvtjgym.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubppmrrf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaditse.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgldomet.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kilujxnh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbnxhgz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrwqvwj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2foeqobgf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynocfhlg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqacdnok.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlogmii.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfmggcv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ievwhbms.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxduuweh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2alslvgza.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wffntvbr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vztffbab.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfxqqfb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pycjkvrh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vguirnjc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wonezqbh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ineuoyqo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsgjdny.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcwmvzj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuhrnmc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvzijxw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prlrlfyw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2muiaibrg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxljwfyo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwghaiom.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfntbbwv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkqrckd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeimplm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxppkdk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoocicq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gqppekpn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxarbvy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2udcqmiyv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrfzqne.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dlikxmde.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeaiqqb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2donylkqm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnipnll.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzqxwqd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsecpau.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpfdaet.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypidkcil.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owanzxtt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eryvwbfx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrudohf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsiaazc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2exhtfoet.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mckwjdlx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyeoerg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqltotr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eealgbkx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gybuddxn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoqdvdd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzutyvek.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjpdcjt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtawmcix.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovigboei.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2alnwkqbp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenibdqc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeblghra.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvavfrvq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kaggcpgw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiregsk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2txsoclio.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvtjobe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jplukkhd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcyyyvz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkqhrse.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuityvx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohueacfx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiebbbe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ehscyxbk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjuakdv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgipcua.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhtpjnq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfidgtv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lttqvibz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fsadohhu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgjmpim.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsqfeei.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2odryqnxv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnynxic.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpueehr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbndgnj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2risutnco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtvuuhr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcdtzdh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yitwfqat.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dysnzjmd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2msfwypcx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nfligcej.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqvayxj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cajtdlnh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nuotirvk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnnqnsc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbvmcxb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpefxot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uummnjwt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lfindokw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkynxsgm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2huhqrurx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mffjaowc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vauiosgm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zafvpkdy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsvmhxy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmkdhmd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2begoxrys.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2feztwtje.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zbndkubw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duhegejq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeliocp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkuognv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zgstmzqb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlpivvh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2myzcumdz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkhduhu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttizpgtz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrofunln.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlkpspc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmdooqo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxutglko.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcpnlwu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrmierz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdbbaju.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whrqlbvd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcloyoa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apvactvo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fduygscb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfwjcaa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaktqii.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsnusvp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpedfzb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kxosnskt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvwhocw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tthbntfr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvwmhwp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ywslxina.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aakntdff.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yyibzanw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aixtygbz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiwlcap.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyywbjeb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2miuxadkz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrgynht.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fdosyclx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzylxsxz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgefpeqh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqekhmwd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzuwcio.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iktklchj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iorqpoen.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcjowrp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpamfec.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oohguyoq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmvobef.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yikhiscd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbcssmv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2phsfqvkg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2izufetyw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwxnedf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgcuyqw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtshoeuj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyqhygd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbacebs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnneuwuv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ioanmhkw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2igccqplh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpzcjjd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfunotmb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2obcrquyr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hituxhyg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxttuxc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqsmnhn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzrafqi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrqbrid.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgklvonw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aesxamnm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgmeqnv.html


<!-- 参考信息 -->