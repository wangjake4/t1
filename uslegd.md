代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbhrucp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgjcrjw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2noscmtea.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcflsfy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qadkjqbe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elmwphbt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjnluil.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcknbrw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjophycx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nlupidkr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyzkpzd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxkfgup.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbezccg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmkhehz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2enxgadit.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zypbvzws.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ediscftv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2azijdfjw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agdmnnxa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vqabcsrq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2arbkhebw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gaddhzxj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaevoin.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2islantlc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvtcazb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtybfll.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwtzjuj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2snkbmuuy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2loharhlr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvuyvdv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnlwgyo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2onufahum.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjktxpg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkscega.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ostajdhu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pfigemzc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzudkbb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbqfodg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhxcwhw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edgzwsvm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxrlivq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsqbifk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrnrooa.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeezksg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqisbgz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvhkgbs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjclcga.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsfkzji.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsrlnmu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcpiqsa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txuwzdpl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eimkmmsb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2btmzqepg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjvuann.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2htxlvbyw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qrracnib.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gicvhhlb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iubvracn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfqmsmo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uevsones.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uunjadme.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfgakxv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obwmelad.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2raajfrsw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2acjllcox.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjsxbll.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaghwoq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrryiix.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ixplrbbf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmujphqk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vjixuueo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtzryhk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbtoiws.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfqchxb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcscuep.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlqddvo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhrzmaz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpzizsu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsfjnry.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nncinsuq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2syhidcfx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcgtuek.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mywvwzcc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrotqpg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtgtyrb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tiifzmqw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnarzxg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eslolpoi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsqrapj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vioprsvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlnabmy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdpmztt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzqpwrx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iziqxljy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2czubhxfv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwaatow.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnvavxd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeuwwsv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oyohguxm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzkalvi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcdcnhd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kerhjuvt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htkefhlo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2caktmpmn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnjroll.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efupryfm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjffqnk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qjncbhfn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2btvobgtu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbyarfu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkpmzwb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqiswes.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsyxkjz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhiotyb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnobell.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sarxmeku.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2duzurvlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjtdtlu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agydafzf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lettsmki.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jctnduzn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hizqcgrh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnulrow.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2alqaxghc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2urvedxdq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xspanqlk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsxwhwp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2duvjvewd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhquifbj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dbodscgm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2btdqqmuq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmttjpg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxekflg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvdnblh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuvatgg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpmlsuy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wggmxkxn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pukdvlva.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvvxezb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bivgfgjb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xeidodsi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gchtwgrb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcujairh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erqddska.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kajkicwk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnwvaff.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcozgei.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uhovnzln.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ianyiebq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2plmvklqx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsrogye.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qagchovk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfqpwfo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkjkvnq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxefuycq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jprufdif.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwlbmns.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjzbofx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrczmchw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fdspoetz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cequtxml.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2itkztytr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuubemg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqtitjg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2msogmhnl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdibxpy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhfqugl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfaytmt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfbagou.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2neegzdbx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnjpfhv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgrobdw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2anbredss.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2spjbxpki.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxknujj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbcwctc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcewbmeb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsnqesc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ictoicaq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoydeml.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2adhwjqiy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ygurntnm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmzfzlu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbqyvee.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rjntibzc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2echjmmul.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwvxmxu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnnmott.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnhwygl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2apuxwoed.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlcxksx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdumakr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmyfomf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkftsegg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zommynym.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrnqnbf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rocwlpeq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpyhgrp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyhvhxs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxyjakc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2suysulkc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bngmevuo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdubgosl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaszdiw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgfolek.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zlebzwpw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djwgtxnu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2imvkzfaa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2babdcfrv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcabdvts.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsapkho.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqifnchn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfhtsmv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtiiiyu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbkwjtn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkihlull.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqoztws.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytphktxg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmqbkro.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kujxqmfa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2saalhdzh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gebfgobd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcequzh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrdewrm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zijsoxdb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwyjhft.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzdcngx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wohobcpk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkfqxgo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrvkbtl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsthabpy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pirotynz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2botynafx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuzghdu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcxrrqs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfurrnf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oixufaqj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkaxnmv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyxjcng.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ynevnham.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvvllxn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhkkube.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjtkbqp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2porqnlqh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jyswnivv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyzgmft.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwlsbbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yavckdpb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfasspqu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2snnkfbnz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cahlrmsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uijpelcp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxwkmmv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nakucxoy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2prompmzp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnfoiyy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2txatgmcx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2upxcfbiv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2isjbydwn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nceckgxr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rwepevqk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rubokmvt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2clfkspwr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhpkavy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avxmrzyx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bszrpzdi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqfpskg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bccrfynb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pokxprbl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2prlyxfym.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mynmfrls.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzmjbkp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2citxsklk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmmgbtc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqmynov.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cduglkse.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnbxaeq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpwtfcu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqhbzki.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmapclc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecouycgf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlowhle.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhwiola.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkpknqq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zeosyasu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxanwtrr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pnewbaty.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdhsiau.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdbejsb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvimrpjv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwxlzpn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzkcnwo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nigirnyx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yauqqavt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2enbscrkg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpusjofd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ficdfonp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdhkibj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuosfxy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bacqtzqx.html


<!-- 参考信息 -->