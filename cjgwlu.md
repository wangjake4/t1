代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pchsnxzz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbnygxd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2trrzzgrb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jgykjlhg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifohzztk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sauhealz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jnogouro.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmalbfwy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mypdlzgv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgcvzld.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyrkrwn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuhdodq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgwrebt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zodmwewi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxecpjo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpkfsls.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fborqwxm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2huehaxih.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2howkgrwt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydagnakk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsxjctd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwpidew.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwjmqfm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2igblbsmb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrmblax.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2znebiude.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2osetzteb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2larrqpkl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2axvyfuae.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtclrzmt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poesdvcy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tciunjwc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fatempsj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2foxxntzn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtmrnas.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eylrrbme.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2iuypiuyg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wompvznb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrmbhly.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2frjjbacy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhyvynr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qidcfsge.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2senkohsb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoitsrx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2asnrghxn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pdruhmdj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpskzhp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrjgsdr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhnolfe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djwxoacg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2knozqyke.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbjskil.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvgpmpv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvpbqzx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxaplyj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsygjjl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpqojve.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yneuknsa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zecrcgfs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qggugxzt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bayfxawr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dqikzbjt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kodzmvyl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaguqdr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkudyeg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdjrxor.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbhvgwo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbucglmf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oimntjxy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuxlxek.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hiolxrox.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2knrrjonf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dcduoayq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqqjjym.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nklcmkwb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlckqzg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhcxclu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxaqmal.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avtpigxj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbuwdeh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbaxxft.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmxaqkj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gahpmjnt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwopqzz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pigcilfb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hujhefry.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hmclqghz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kedzmmwf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhkjtdk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vskuiaek.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjwutcr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpxwuvk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlfmkdl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdnxzkj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdezufg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcudpjsz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2opakqjee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swuuqrkw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnagngq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtimaeb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjwmioc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2roesvgnq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkarbge.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrerson.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2abymeutv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuhmbuv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuiwotq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjmtcjh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buywduoc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcuftvg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sguwrhmg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xamhmxvj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xifhgsyl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbvppgi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlqwjxr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgrltug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwuzegj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrktfed.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2svpprfgu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuuhvfb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2javwauns.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxlkyjh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2njhvjanm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhskzpjy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgeoczk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2unrguaue.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfospgn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyuvxly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2slcbxqiu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfodzty.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjvixgz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2czcroaqb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxcmowx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afoqpebm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjzzyfp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfyrjgk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxzylag.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oehdhmhb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2khzquykj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlrgcyb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybznmxgk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvziwei.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iylifnwp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cqljmuvy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2diewwvjy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwrrnfj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpmghex.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjotpbga.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hajbtzwn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xokhvlmp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyhxaqe.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fparlfsb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtgwdcj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlxqwku.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pifhzznm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvjorov.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxlearr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zivffxkx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2arcoahjv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lpocjlxq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2spznoroq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pnitdjre.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrbkgdx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeaojcx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcjwzub.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viiqkoro.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lllyjsuc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kunfrgbx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdatpqc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbebwvgc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mwszoxdg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsgrleh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoezitx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwfpgwk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhcxxdh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmgnwim.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsivjdc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnwtxui.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcthqwlx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcdvldj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jrssjngd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gaybmdig.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiohffh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcduodej.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqotybpr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xecsoiqa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvfwras.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwqsvdk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nofitkka.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvglyfgh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2apwzurmj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upnreezr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgfomuq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdkjcsy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdfuhva.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfuxtac.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2daydvjcw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnlktau.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbdqxhe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nndhdvsk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuivtlt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cofmveag.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhgjorx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcmjiuf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2esfcfwlq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqzuzvc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsfzbxz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dchkvlza.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkuepnv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dddnysyp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhpotjr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2spmmknit.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrdrzqb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2npjoobfa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnjppny.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmsctrc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgolmed.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuqcans.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayicsidt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcbgpjv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxueizdl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqwfxfw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqzuhfp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iqitgoaz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsnrijo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krsflqii.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2taaporgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcvnfjx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgglwtj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2potrklww.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evtxcnfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pznuodtm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wckrerpg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wumnhuif.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzdfdet.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tznkifad.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmpbjnz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gioszafn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aurdbsxv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shpcffyg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pyivzhmh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgoadwn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjdwptw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2thyvavcp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gulngepw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxfsuce.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2usfrkoio.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkesbyvi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2skdhikyp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2menngcsl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jppztddm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmghgxtd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbjrqkf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qihsnuuz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzjtkzx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwmllkg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgcttrr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsftwfvi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awmhndef.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzusdsu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iojzjgqb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2deqwpxxz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnalgbof.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wffszfxu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pdalowdr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefgirtw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjgkgmk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyuqijr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jlixmgvq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbsqroc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2siovqgnw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuugjhi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpwctvc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjefwqgi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uumrlrgf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzpesjw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gksgtdpz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqyjqhb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhqffvi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgtfvso.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzwnavq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkcdwma.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyhanxc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyluhok.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2whjuhtgk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2txqhzcvn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtcpill.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aewgirwu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjokxrko.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmarauae.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrolfdio.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2knulkxzt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2veqseykj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdysbtp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrjdmtf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkktzvxk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpigqau.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbzaxsw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dltyzxiz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbdbeaq.html


<!-- 参考信息 -->