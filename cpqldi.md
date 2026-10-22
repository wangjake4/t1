代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmsnmud.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqvbupw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tugazwur.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2avcuorii.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slspsjue.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wplkuxiu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2txccatle.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgdnqmc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fatustgm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxdvptk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jbontkup.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqatclu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhsbzzj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzmfijp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blsynmoz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2noowfvdv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkchhfh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ndccivyd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlygzpv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzxmcgg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2phcswryz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dlejtjpt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdylwid.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2onbzxiyl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwokrcbh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqycqse.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryctaoai.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2blvvirmt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xfznnwgk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjocpfz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmulinb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2seihqnuc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzbktlv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2psiajeta.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bboshhzh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2euawdqen.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtvfxtm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qayiiovr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvqlknu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcbllyn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgyxjsp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fbspcyes.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvntfoi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyemfgh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwkhqde.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itgldewy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqljjdp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdznwvx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eniusnxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cexjcvuq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzzluwt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hendujpq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkijxzh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epgbhwwb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtegwup.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmmcujw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2otldsuvw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hulevnmq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzxgtfe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rslgqfat.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuvdtds.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zooxxdbi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2djuktkcu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kncpsyut.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mclmbcty.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2opexgwlq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvbyjaw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2plolkunu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tblxutgx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yuysffpc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dpszbtbb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgjwvom.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuizgci.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtiwiim.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfcnzfe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoarwvr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfzigdi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgvjfcu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nklotzwb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeqbrti.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbtquou.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyvxywt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtkmsji.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxsmqtg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmycxyh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqbkjol.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfdndbt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hipqmlqp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiuhiak.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2clgufmkh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzcopkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nofbfjcg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lomqnrhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyjmjla.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdjlbuv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgtplfb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvvnjhs.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2txpafllc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbivvic.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uexoymzk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaygmhky.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzofdhm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbhkxdc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2orvzuzva.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2drvigzti.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdhrwft.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2egsxiojh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuyhrjy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2quzbfrak.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaatsgq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yousyvdo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2upczwzrt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jezgsqei.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2beqrwsvq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wewrjiub.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzdrjbg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2klbeyxby.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yejkdazj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oluvvfpz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gijvedad.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2idqvzobm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wzremjua.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoufzpo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcdnaeq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqoimxd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfnhvqd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqxcume.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2btdlpsbe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkohrce.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqpfvct.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fatdvjmw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpbyxel.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpueuyad.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhuqkni.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcnqnls.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhzyggk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhagdqt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyyrlpt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouycvjiz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgujspx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aabnblsf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gveymiry.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjomjbx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjosdgn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbpvhfw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtadgbl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpulzpv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtfkjgw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjadazzw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cyngnlds.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jutmibkx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbkkqhc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyipvbkm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlnhdcf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvleslsq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaboaah.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jutwtcsi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2upgybgbx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2umyilvyb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eofrjkyv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ickjwfyu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vksbmwzh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvmhazj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhnolzc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvcvfop.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npifpblh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mualcmhb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxbrgzb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rormfpht.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twpctike.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaqctbx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiqpbdb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkewngl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2plfnispm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyzlgdi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aocdxbhx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fguguapn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzxensz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtyqids.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2piufodjl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iahaftzx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbstcanh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jewpanfr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlcijdf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuygjlw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvvocnr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2njbwkglz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnxmwgl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhxxuxa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uupyrskb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2phlthcsh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaaxnnw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqdziky.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isdvynpw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrltzfk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxapfzr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjtszxa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrpvxkt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cudcaldt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpoopbe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mylhsarc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rozxjagm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2twrojcaa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjzkwwc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdhduyg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuympss.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fglucljc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaqnzba.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tglbjyga.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsuhfsg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxhdfag.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2thyozzwo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cagvptok.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlkvpyk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnayzgkn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nywtrjyt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2stuwslvc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjxgdbf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2svqjjhwa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sigywvwy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2websgdfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkntgir.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwpnyjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaknynt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dlttfhdd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnvcihi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfrdqau.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ackfersf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2epqgluhl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyzgndr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ywialbkb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eesknwja.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2djckhdwg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oebcabjq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aohbhwro.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqlukhu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpssxfu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blofbevf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vurciolq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxnxips.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuwppmf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxejpdk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tystuzwy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuuwagn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhjrccg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2adpxpzui.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2syhpqapk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxenzaio.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2smukwyja.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkadeyvc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbpfexa.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdjlahz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2htrvijie.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fufluilc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjelgav.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwvqtsl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2expamkah.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mblcfewx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiylmgq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lahwfokl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tomogiyu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwsuslw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lycxnefm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yysrsrso.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2saotafdg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2untdpdxq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxozoyj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tougwlcs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owrftswz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2twlntjur.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2exbtqlof.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpldukil.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpuvhhw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkskvvyy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdwixhk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwryymb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhocfko.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dypxbdty.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiingmb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2misxymix.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmceihh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrkswnq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyxebff.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mexzatad.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sklkvgvp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jptieqfz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tpitpxpp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxyqtjs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2apezqrzb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhfvyrl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeitcym.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uatvypiq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2owrkvuec.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acxwbprf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odkzhbhm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hsilpcih.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lroxsdon.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxivcip.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qedsxgms.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrjbchb.html


<!-- 参考信息 -->