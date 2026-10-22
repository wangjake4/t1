代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ecudhfim.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgstzmoz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtdbcig.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2firujozu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qezctnom.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsmsmjm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgdicjp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jezoyawm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gflmnbxh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yzauohkk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2axxygiqg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yjymdiru.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2oupyekgb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aszhaohv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfznilm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2orbpapkr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvpvedo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnojeun.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwfdyvq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzforhi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzpfsvl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imuheqeo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxysmap.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcxrizf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dvokrjmr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmwuerq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwbtftq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdraexps.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzwwayn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2itcuwyrl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzfwinh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2twymqxhm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuhpddr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jgubwpbs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdpyjvw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elsahcfg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jswamifk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwifetpj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2reaipese.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyxhvre.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsqvdrc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrawehn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2suukjndk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpzsrsk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mawfbnfp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjscfsj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtqsnjh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2izvnitia.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvyndma.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luhkgukn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvckwom.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vsojvqni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwlhoxc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpulalx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaoictr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbtvlqb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2aipnfzhw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pblzbiwu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ugogfhnc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxhpavq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwsohwd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aixsncce.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjfveho.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkdofec.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwcjuzr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwrgkmd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgsovpd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxpeapa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ypttpsxg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2buuesbeh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhutrad.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmclvplg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ekccuwro.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiqtrbu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jifabejq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuukurn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xihhxerf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbsvvkb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tedsxvua.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vexjgqcy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjjyxno.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wdslcavu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tksvwmnu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ankiedod.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkhqxxr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kbybuoxt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyhyhsq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2txaopfir.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2icwlonau.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfzwvyp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbecccu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2suissyql.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaakite.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hccqbqve.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ailcrycq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nvebqxzn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xoufoxnm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2enutffkj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdzgffa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zizsgzkc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbjnebw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rnctmrkr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qmacisnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsnvovg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoijmvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvoqunr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gncimhhh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqmyslh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbmkejt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxuznpl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfzvqes.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dearstmb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2drdclcjm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2glhgpipi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2btjljrmj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrezmdgs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtyplmq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbusuvv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqfgwbz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2weyjgcwg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgwjyqc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxxyznj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbjgtcm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgkjhsm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2edpatwjz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyxatcq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkekfmw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljacggrb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2djjgvtkh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2amsqrvyj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzjcbas.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgpptax.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2poxrzemz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqogacq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bapooips.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkyuyxk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gvecgdcc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfemnuh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tyztgsdp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxhebcn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvqcuop.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhnommk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrwcerq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxufaej.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmwinfy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2whmsvaoh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxoeeek.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tucaocrw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyroepp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxsacee.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2geamhfva.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfuxfdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsnuvmw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhvvoln.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvawakha.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzgxeqw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxjkkhm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kjebuzzt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2odfffiuy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxmpdgc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2giwvgqbc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwvhdoh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiovfxmb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hybgavkl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gezelzhc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuiwwwm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2paxwzfsr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yhinuauy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgmjnjj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vpovjklx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nszzjkmc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwkhebv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2punotneg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koqelcha.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arzfhkxv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hstypgno.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kventcjp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2znfllkdh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwiiahk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfydtor.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tudnnwer.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpighgw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2efqungth.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzxehjo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2komlijkx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izapdqns.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2majyswqe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdchejn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grvxhctv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jbebghiq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2otkstgis.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrpflpv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzfitbj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvragjuv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvofqbi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfrvpbt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jqimmvpg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzxzvsf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlsduck.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwvatzu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kedlkejt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjefzpd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiwnbda.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvpfhkg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wruyrqbc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvykimd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyqrtmb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2icinlfvw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xywogubh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otlgozei.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmyqxyp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlhdtoa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzhvddt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eodhvpxf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyfokgd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqgdell.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdoqdvj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqglqkr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgtqgrw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqaddrf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2svfazush.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrcvgxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lieivenu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjwmmtq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqxngac.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oznauoai.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2msvvtobq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeslllw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofggcrpg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwepfbu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzmcndw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgwaoxi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvsetjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hatcjxgh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzusznxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zllpbbzy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqozwofx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfnadrb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csfdiwnq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2crmdgssq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpcvwzz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcbrata.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2khplecwa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ugepqium.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2detxpxqv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgigfgi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2otoxmonl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvdataz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2czhvqgtl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfyupxa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsqksxn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucffyzsr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqugltnj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccysloqc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkddujh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuouugdc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmgdkpi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2exopuwel.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2obssbtum.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swcjdtlq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrpoeim.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnsnrun.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qiquianb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvetdhop.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2usoyqcdi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfajevcp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iydhheio.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqztdgw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2trgxqald.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qibklkdl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvwkkmb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oalfxqpz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lyahxahw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2svxisapf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxodrvc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2quldxyfu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nhluitsl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqhgiaj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyapcob.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kymfxown.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoolrzch.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbapayir.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xkobyutb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbqgqqe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2adpxeiai.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pafhjfrn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzhqfdu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrpepnn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpqlepp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oerkgofo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbjcgce.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeljzcel.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqiqrpr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2viknhjqz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hiexwltr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhxlldz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gyveaiuv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2phgajyts.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rexzcfmu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cqstdkez.html


<!-- 参考信息 -->