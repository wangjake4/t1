代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlnmwby.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2edrixjxi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrwhvup.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbqujdx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nobozwft.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zltmelkd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqdtqls.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwdtnhc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmdbflw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rzclidbz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cubibsrr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeldwxsb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoovaws.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgabcbu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeosihd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ittfpwdj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbslsfb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnyzmkm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzkmqwr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kugxnwuf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2erpkybzc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhkrdns.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxaggmw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxmdybb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmkkrsu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vekywznw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfxunku.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2axonrfls.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmmrsla.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuvccjk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlhtqwp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2geqrwuog.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2winkztop.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2easnvcxu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aftfoola.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkxpxjw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdtnhog.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqhptkq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjunbwv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkrknkd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbfoqoj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdolihk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hxamhpib.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gzifbruk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqqayfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxcktlo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bbobtzsx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpzagrb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yombqagw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdcfywo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhlioff.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gramqbwe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrwliom.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwruoqs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cppicejl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtretdqy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbpqlch.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfojelz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kcquvihu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjwmomx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnniqvy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcbmnps.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvuhwst.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtcoxap.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcgmaxr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ernlqcwn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ervdsqtm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hrscadbg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxdzyza.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zxewxbdy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwhmiod.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pewrddfa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbhvkzs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lzljmyqr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdonzukq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rksqhrkw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqauurn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwmypt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjlyutk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2clqgrioy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pixmobfx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkecsax.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kljrfyhi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrdusrp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lksobtll.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqwxywf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrxrwby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvtbiso.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rxikxhvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaayyikx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xacwmjnu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqzvanw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsbugcb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2plifdnta.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmqzbfv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfscdig.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2brxvmynv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnfrndz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2msjnbiyl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqwsdel.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvteluxa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgrxhwt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvnqaec.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjbffmq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhhqwwc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnxtofz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fljbscqr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qacgpmpt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lobgxdor.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2odqhulri.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2omupwgtv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2beupgpaj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zobjyduk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuelicjb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvekpzt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqjxili.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoanbfjt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2anlolfhq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hajglviz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaiqdsy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsqxfff.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2psloskfw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ikozrthx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2drfzzobq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmhekqw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkzarfz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfozerhi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzpfjyp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnhlour.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuayiix.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eisqvqlv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyrdpqr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2efywbnsg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaierjg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpqhnfo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lndosryw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mghgnorh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kymwgple.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnietwq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iugybyoz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdqgzln.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrypmwg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnogzjk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxvpftd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndilncea.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2krqjpqmw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkvfmmi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znzgcztl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhufidj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfpabwb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2twmfxybd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvuhxpq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sucrqycb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrnrvws.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pbllmobv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skrwberv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkgkxzn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mquqsshl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvyvemm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwjyywp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oicmgiup.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyumfjs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ncewzxwz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihfpgjw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdpzauk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itrkzysc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhgscej.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvskxoj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ueovavli.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsjvkdj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbrrydt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2txlwjvtx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uxafcbxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2weheawow.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2civbgjhl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvkqkyh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmivnmqc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrtnwxq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2telbcakg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mduirjao.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cihelccg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcewuvaw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbyesos.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvumqjl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hdljxusz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rrojnhmf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2avwepxgl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuemdak.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2irqrbmca.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngxufze.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqxjcfe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqjcbku.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2otykxqps.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apiegfbr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2odxeanyr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuusggk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaeldzo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2luxehfxt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2usgjgubs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fermxaix.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkvtyfz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zeprnvjm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnljngo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtpagiz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fendedou.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzdzehr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjobmmdy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuretdy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yijfuugh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dasjjclk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpgypte.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsajsod.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmssomw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqnsssv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgigtou.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bydzywdb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzaizgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taomlpbh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnzbxpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfzedlj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kecngzto.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbiihkt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvuzvjf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjozkek.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcxukru.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2piypthip.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsemcbx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoovaxq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2guavhidz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvetrhg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ougkmahr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wozqzmkl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nahwgwaz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uijmxkhm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2awmlccmx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlidngq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgsjmch.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwcfekm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqfsyru.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwneqfl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqxuqvv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckndbgex.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tefnaklu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjtfsqu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2liufiyyl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbnrloy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvstwbko.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxbarw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uiosmrss.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhelwgjc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kxutzyno.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hafdpxyd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyfxgdy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evisxqui.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmqigzf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdagmrbj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sonzdcjj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfnsvts.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgprffr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvdlxzw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvywimor.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2psgqvizh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2khxqfmun.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiwtdqk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puewdplc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhowjsz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkavhfy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieugynak.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhdqvaq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqkbupt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2obmhpftx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhfowxj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eskuoxjx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwviabna.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2msdljyhn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrboivwn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fotncksh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfzsyyv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2blpdmfbp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtrvwgb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfvlnrq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdcpdaf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqjnptd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uucsnfpc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ermcykst.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2naggjdhf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgzdati.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzntxgyg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2njfajryk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxmgads.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzftqxry.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxezsgv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhxyavn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuysfmo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljajmivy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2exatvpzk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmepnjm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdtkhwi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmckqsz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2odpwaxrl.html


<!-- 参考信息 -->