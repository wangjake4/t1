代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gghbajrg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ikasljum.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sekganhx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyitrih.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jannyjdm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqomdddd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2potsnjii.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azxxqtsk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkqbnkd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qptfvwic.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpczstq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwayqou.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnlgvjm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2awjcvtoe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrtkxhi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxvrohk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsnvdyr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2muvsuued.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nnflbxsr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxydfju.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2almpjipj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2coihkwpl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2acyehuhc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhzgwxf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zebjojjv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhrbtek.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ciadgtpf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njzejpzi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpxgcwf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfwemhu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjisrwai.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thdtswkp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpbdtbo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fanxouvn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kajvgkck.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfzuyqz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlmiztt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2izntssby.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsabnqs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzyljfu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpvgsjk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aidqnpkh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfdtdgi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qujueria.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zrozfzpx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdtnfel.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmrxqpp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhfhqwo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kadvkfby.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twqcmfwe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qomwcrij.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvtuljk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2molhanpe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzqfaic.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdbsrdp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjksghb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zufvjmqh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwxhvsx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlsuuxa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwnitnw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyhpror.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpqhvfv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtipxzy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kioydvwv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkczwjv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eqowxxjl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyrmeqe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iyalewey.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnnyyql.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2okeruazi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyqhpgw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrsuytp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bznvsqoe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2njhkicbt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzunpje.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gecycjix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqayhhy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvqbjfp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eahmctrf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eabbayfh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kocmnpyl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nqljoxlf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wuslebbc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2weqzxncy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhhtrsg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqblajvj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2driapmdw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2acrxlcpi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgiohzw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zthlkcgv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfxmnve.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2homwcxuv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hazsoyjl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsvlquu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqpthiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrqswyp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wacxdybe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwogkra.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fhykyitx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qeceyxut.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osepkpds.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2szqgpvor.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaoabvo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjitwsl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cykdfmoj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2banlvrfx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xeawvnwc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2muzcnfav.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljxasxc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnwhfxp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtevcgw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kelvyluv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lieuofzd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2frtruxhe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rimabmaf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfmxclj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjqlcgv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yfizhiet.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvyyqby.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxutyoha.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qubgunhp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uppaagmd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbnjpez.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrtevqc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cprvnixl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpnqxnf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpundhqa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaxxhcr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnglzjse.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvxbogr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ophnqola.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfjuhkg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2byvjjirz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fztskkyf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufususin.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdealsxg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkmdqba.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yygmgxpn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyvakke.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxyfwch.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjwucyj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcpryuy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oglnzbtv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbtdrzu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbztxwhm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2axqypero.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2weyddemh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2scwsakle.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjbkfws.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oylpupel.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvqmjem.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hzasvjgx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gllykleg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjcyswq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegjrifg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nneokidv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwopjidj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kenxcoox.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2klalmwte.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aoycacda.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vohjsjhu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrhllub.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvtweuk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrnybnv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gafngmfo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvabuax.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lywwjbml.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvojtejc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjengnj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyynnicw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkophoc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdfrffx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqhsrii.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeftxuq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cifglqxn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rofqjvyu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmyezdz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2byftqyfz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaboswc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhlbpsc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxrausy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyuvzcs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pigacaxx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2umrxzosp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwydjifb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwrpmwx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiuviwm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiihyvd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vevivcgu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueseqxre.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqnpcxc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjevjlx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vwufmwks.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvrocxs.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlmihma.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmahetdl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klsatgdw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quzpiaqf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmzfqgt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxymbku.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dajnysjg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zanpwdet.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbcwzej.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eadwejlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjcqhjw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hujtbkrt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2exszvaki.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxworrq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yplrglvi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2etrantoo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnfjya.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2syidqvau.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihxedm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ancrkwsi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2riuzswmg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pseheryo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjwjylk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhloahv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dazsztpj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyzyfax.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoqbpbt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hupjjdgw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgjdtks.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmejphw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhkqoqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgavogqb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pymloxrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maklpxck.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfakjoc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2awzqubtu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2widaheqf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhhpoej.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfiwrcq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iguyreuf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmjreet.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhczbhp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmjbpki.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvksqpk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2twfbskuj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrtecrw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmcrdll.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gssbmnmp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjtlxpd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2clmvmzxt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrycuuf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuwnehy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxsoyfk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwggbvnm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xzugjcej.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcunhqnr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgfudao.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupdfqao.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghukbm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtxdyet.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kshybkst.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaypwck.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hbigvbgg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyjpcqi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awmpvoyl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssakabuz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjmovbn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpdenuv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2adhyowqf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rllidkbz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwcynyx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2psioehck.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cacioymm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2apzgcksa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2woijunud.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqufgqut.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fullbzdf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnfirla.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjurdpvd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdpmimb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeswwso.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2riqlhzeo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtdmlcl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yegtrbin.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hotiwjql.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qingapkx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2beuedmro.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eppxjxuy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwarpjz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmlutwc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpguhsl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2byymvwad.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kjprffxr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgjawpi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmxlqgp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjzbgmv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pezhnmjs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvyqygy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wauagnpa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwgvdky.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ceifyktu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lleucftf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxmzacx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lshoezme.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2klxfjelu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fusbwifs.html


<!-- 参考信息 -->