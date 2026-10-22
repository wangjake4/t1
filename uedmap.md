代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhrcjkl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrdsuxb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmfcdmy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2onfhzydf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmzusps.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhtdmgh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjgxwem.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrztdcux.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qczvjkxa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2njvwnfad.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyffsdp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2geswiqad.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbepmpk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lymglucs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xxalydnh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kboirctz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxgeuhb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnppiro.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gakmebjx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiitlutd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjkwsqy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xhygbjcw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcrpqgm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbpwftk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtivwhg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2erofvrhv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxtzqrp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdpwreq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gumtgcrg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqfcpnh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfngtpj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwbuijy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kvukxpzb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjncart.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yenzasil.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2atazvvbo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgikcff.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlxkglk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fdatyoxm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hffsjtyi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzckvjp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcwdgfu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lrufrzqm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjlqnrd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbqthul.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yuotwbvp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgmybhi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2caistjnk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2devgzrat.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fccdupmm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2whqnlnds.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2czvdobiq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2seqbnuyb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pylmvmdj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxwpnrk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvuzelj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoetikv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cknzmabb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmniont.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gynvhitf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2azkhtdhd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iifdksue.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mtidpvlj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jjofajvi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeuudcw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkzrbpk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdtmxng.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2necyvgwg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgjdmqq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlbxpua.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxnrflh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kupiujiw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2twhptxvu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjeodtf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfrgumz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2azvtfiug.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wwavdftr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lfquihan.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwusjdjn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oeriqyzu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itomsozh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ietdepqz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2adgvvhtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oysnaywp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2khcuxpma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hplgqfkx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gexlvacf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2femmfnir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaamqqqn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjscygu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvxvqka.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rysskukk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2usuuoxhw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cbocerzv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2niscwpkr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iofkogtp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbncbaj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wzetzpqx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ephnfkun.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lihvlkip.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzraxxzl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuqyufd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrmrxed.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgaxoju.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2usrlphbx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cviohzbm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcrtnqw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izhomcvp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvjaqwy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vinoeqqq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykepkhlh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdshfbod.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2evqxlgja.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbhnyyk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjlqtya.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2efknsmdx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmxnxwm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxpxgzh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sfntubze.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2siigelkf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xubdsepd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxugbcs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivykjlhx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrtqjer.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ierxxzhq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2acqgljil.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuytywd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhiljrc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjavrsyp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtnpnwd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2grndszvn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmlpjds.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rczbksjx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzsjyjw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvupmvo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtsimsf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zukdjwqg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwmjyhh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsiexmt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aiotjxjx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqbrxoy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2btuufuia.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yevnjger.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zusbyfls.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2auquyvak.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwrymkt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2duslebxf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xjheuoas.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vsluzihw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2firhthbf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jtooxvcj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfpzfoo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxmndwr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rltdymrs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcdukmv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oytledfa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dmotihlr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izeothtx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2etiruuyl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upfedwpv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmnecfs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knhkbchb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrwtpyb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtltsuc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tfptlydl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2naxnxtht.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yshdvtjd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dytoaseg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzukfhsf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fivhjdts.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2moguodzi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtvwfsf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2licoubez.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdrsrxs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gamxtqzl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjrpvww.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrivggs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2svivgewb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxfipu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyvmeat.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmqkqmp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2esxncltr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvzvsyg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neradmno.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2loeghmhv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzayabtz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxqgzkp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyxqimt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeamginn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwjngmf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2reiyyyng.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2esekzbim.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmcmbeb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwafuip.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcinrln.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdvkwdx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aikyxwma.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjumcqy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeievibt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkyjfwe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyszwjs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgwabme.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfamhiim.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2szjlfrvg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhjxrel.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfxshvi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkigbeyw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2twewzgtw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgqmtto.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xpycepyj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ashkxdzm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sokdqaay.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhdpjib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfgerxf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyfcjre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqhvucy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2imnjrprq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbibbix.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjepvgr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhytqyb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpjikcm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqciuhdx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcuammj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqrdchp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wgofeuqo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvriijg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2offfhlat.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2censilba.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eradqadm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smsktkiz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2weifonwn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmkxrfm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyilwqm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2igxnefhy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqmukuk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvozxkfv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2anrnnypa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxxxuxh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqohcah.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzoaahq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnoshsq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2giddajpa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2luuljtmw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzntvgx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcyvvsl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcpvpzt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvxozwv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsymjrv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmppftf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnxumao.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2shdglpbt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pccocfkp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmxcgne.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2obzgdfjx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrlrnui.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2edxfspyd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtzacru.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqexxvn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyxlars.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zogqzhxt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glurnuhz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfazjba.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbbhorw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnxwrfr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dapnyhbt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vickwnca.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzkuvis.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vomxdsrd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dolidcic.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2atnpovwy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2whwsawbo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlseeppy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyarnik.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoxsjix.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2apaykems.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pblrlipx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yoohfgwm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjfewno.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkawijp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfamqqg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxkcqav.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gydufjvo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbkfceq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsurqgk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqskrsc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdzfjls.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wprqmiax.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxyqxdr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jexsrctv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrdzpeu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2odninqid.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqezhyck.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xenrfpyt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aessgjtv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2awjektpf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gcffnphe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uasvjaky.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bttqimcy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbngycgn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwukvog.html


<!-- 参考信息 -->