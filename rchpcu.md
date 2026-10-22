代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rusoezsq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sabvasez.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrlmpqo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lchdajpe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkfuicf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjkulur.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwwsqkp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2irtyzbbf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaxuhtv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnerbtx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrfrvhc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtecbck.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2occymvrf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfqvsgo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaqhlso.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tlabmuwm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cceqknlp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nttuqdtd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvnbfqn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uhczuqwd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuqtoif.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeudivk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksexzrcp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odbxyshd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yipjiiqb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkvmiiz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2akszcgnk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2spppdgxs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2viuwwpzn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbxkmhw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fywplajy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rocdrrdp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egplwnnl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuprupar.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbktlgx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzokfdh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjgbjvz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2plxpuuay.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaptass.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2iothbkeo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2diwtuozm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fujigdlj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sunwcxgy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tajlwtdl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbytwhs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyxrrca.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qclurplf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqfmtqk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mswjwtau.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2shkynace.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeehicc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gteqzemy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrdhszd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adxxozmk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2puaagtnn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwxwxjj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jiajgoum.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeryabv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xefxjpeb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bddcfbda.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfhgxgn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcktwxip.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsbvclb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxzncqo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2euhwhipk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xywziala.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtljzxj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iykuqyuv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jytifwls.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfwtsen.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrlittv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqbnrmt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2eivxllri.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xexranmq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqmhdzd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyfmhvg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pchgvfrh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtxqkd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2davynxdc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfuqwab.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2msyuftyy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvmvrzo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnztnbk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qftdhuqj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cczqsica.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjpqpsn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmosujb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zexabjpr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2trptxbmy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwmyjgc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvielsy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2acucadvi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyofccs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2upntvdnh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqqmlly.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2otgztmli.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rquivouu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ukazwkho.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqipgql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gukgjkpq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjpvmac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tukgadzt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2guinfgck.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2shbqjonw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxxlbtb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmfyepz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eltleglr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2viksgrhc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxjigme.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsshaha.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhormjd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cygrtomq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsefpbw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kitkklis.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2trmugqjf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2otqszsbb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ippjdhcm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fwixnbrb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohulshnd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoattsb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpoqfhq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2djtbmrsp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyvkwrh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrfhpwe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eotkkpmu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhelqte.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqalmhad.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnhxquo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyjtmmd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ifglfzms.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfopfguz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ecembqph.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwzfwql.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqotzie.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2miaxvmgt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fforrcjn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qumyphin.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ishouwek.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzhxvqo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbutfwzk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcdutrt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtkybkj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpseobnz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oxezlehp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cctvhvlp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lryjyqjr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ausvmvyx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrrslec.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhpzuim.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiblytk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuxilee.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bvixiqgl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gomirwim.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhxebga.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbgruvc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokbqax.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlxxeqa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjsdho.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2znasvcxg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hatbebef.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vemexhkl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slofpsco.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdozilj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2khpsmvln.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyucnie.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfeideu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gystclqg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xftgygff.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxsogck.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edeqtnsk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szoqkgeo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2adexyssm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2berxozxi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fchzxcql.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfccdfz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yagcclek.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaczfen.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bltgxhgi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2asgmdzhe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkhonyn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xccxhjrw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyddfoux.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvapnyy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbldoim.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyxewdy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeohmms.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bcizrdzq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dorjmhrx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxmhwmt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcptuqsg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmroxmrj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvofwsf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ontgqfnh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2okrgajya.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeswrlz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbhfvao.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2amqwtllf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbulxvqr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cirlwjvu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgakwicw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwubcwgr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nucerwej.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkxasqy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoctgjy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvhajqo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jivdyark.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoijdrp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oquqmxso.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrcnwke.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxmrmfb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2allzfqrs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyysirx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjkvmpx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtcgsfj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoblsmzj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oihldqfd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkfuswr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oerpwugz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2acscdrdx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlebnal.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpqcgdl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwikdhm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2anjspygx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jldxdzbq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngegcomc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2abmauolq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnegvfvt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pebijavt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2btwzdctc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdtrnaq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aocxbxhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvxtmhv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anorkdxw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbwykrt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmiwbbd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tccymuzh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdvicfx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2agqhyehd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dnysumht.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kljdsvgx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxldnqr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkadvjim.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jamzumjk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzpsygs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gurikcbv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzudckxd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjccjzy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jepqwmxl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vapudbec.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhsogqi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2shrlukrw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwcbbgv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxiwmwj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqsmruf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmwagxw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btcdzfmi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzlsaqp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2skshjasv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kslkfvry.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2viixpgts.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgypqyl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypurkrdt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cwanyqbj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fazjbxmz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtvwboj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpihbte.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ielboivc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhpfuzp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mexoczbf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyilgihs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnmlzas.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsihuwt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lxumaqdx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmorsoc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pzldnyox.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbifntsu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udkmbwcy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abasouzr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwmjfsb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2igritwcc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cvylkonn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpcuzrs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbzmrec.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiogxft.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvnyxpr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2owcmjmlb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nhppbcux.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfkhgtl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpnsvvd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdftgttz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjjcjtk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gshnvbtx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbtqvjv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkkkzxy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nliigfnt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2osqejhgj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nklejkwh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iklotgdx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zimtsnty.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2teioxafi.html


<!-- 参考信息 -->