代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itxjbwki.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2frlnwxwl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdajcxry.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2anaxhyud.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wanxwvyo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsmukya.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbflqpjl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gptofffu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prmmfdrk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2slqcyoha.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxlqsoe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuzmcat.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgildgq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzzrfxb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tylinjqh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fplfhmhw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgttduzp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeiilai.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcshtmpx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbwwpcl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yziyssqi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtuiznp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rezgvhip.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgqwmlh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkhfgxk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ligvvirt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2amzfzfun.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnhhwox.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rctmnpts.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdjyvtw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvqrwuv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vlizfxvy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmsubqi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2aobxqwqb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ktizcgjv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nektxdgg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxbiqjd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sznajask.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2opcxlysu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mckcaplo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2appkmmun.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqnoola.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2auuyylpb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfudwtk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvrwsme.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzijjyc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2umybjfaz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lorjqgri.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrigamyg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fivwaenp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eibdsncm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vawprowb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2awictumf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlpzifw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ncavncye.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2brtmhrkw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjczvqh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzwlkvb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2majvwtcp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrcwboj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvutcoj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lclhlfwo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rttxdxsp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngecuccr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxfflyg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeffczc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fylcrjgg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvbqzyd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2impwticb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyspxen.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kidqjqlw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2unhjutec.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfdguoe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfhcaep.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuktbna.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2alqfindy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xznotbna.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnigxyc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkqbxoq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqanuti.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdqpsvg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmrgjky.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cizijekq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uhccycgo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2byyrrbuo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrlgrwm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaqczpe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvsfoyi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sckchocr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmwvzlo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2unumsrmh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmdralg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2effbfcis.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjhxvhp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkvxaqp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeznvxb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aswiowiz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kbazxsvo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsrypnb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxnilhy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyttisx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvjbrpg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fweyxgaw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yngkeuqn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdzpazm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhhkwti.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnapijn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2doglmqbw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xveicojz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kfytqauk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdhisfr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2smtcdjyw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2osuqgppl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jvezghba.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iarfryjq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhcrtsm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nckhmctq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2toflyqwy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2anmcbhhp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2stcffxwn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmnhwyz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2axmlfiea.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2opvetffn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pjklwvcr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwibkqvh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbelxvh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgydvbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbvnter.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuzgqkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoboycae.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frvbxgud.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cfslarfj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jimhmxcu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sccxkqsj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2frekmnak.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2adsdnbaw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcsshxo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsrnqsh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxfkrtz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjqqacq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xahmlmjh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upbgogdx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdeyktl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkupviw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wqejlfbd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yevfglpo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjtrcnr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ghorspgw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2laytujda.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nczxakji.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkflicoq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqskuflo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zojldlde.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxmmpza.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sudvhodv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfjpuxv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqqilzp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2coyqivnf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2adgwfosz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdegjdy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsqxlpr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyyvprs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwizpxu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vqirkbso.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieacoaed.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xobwsjyj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqdwnyz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qapgqeom.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fholdcre.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpoafic.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthqsbrl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfxujky.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubljvfok.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyathyy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rafalxjz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2myuuntfh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aspvmwga.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmcvlse.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqywbdtn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhfchvb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwwopkb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbgzssm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqpypnw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sgndjnih.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnloxjvw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbovwzzf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2psvzpsvz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjczrjfo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcmegyr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxwhscf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdimpqtu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uqblmtde.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmkoblk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dqywxcxo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ropjskgp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgozuemf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwdykdq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozatjcsk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2utnquxiy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kghdnpzi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2opfebbcf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfpvhsg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmzyqqp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxvlynb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ionszhxf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxyyanh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnhkvvv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vinioxno.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeskspj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzulhyst.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rihkmbon.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxczdqk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfwjvhk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtitprs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cmebwrez.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2srfvbciz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exrxqlhi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbblugqs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amqcvjaw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvrqthw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2agbbjgse.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xquzpekm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaxfozi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqozmnpj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmtracp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygecqldo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpzpfqc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhzigne.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hprjrtub.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piwuonla.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qljlwvve.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cphhfnib.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtplwts.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmehbzlu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2abhjogtg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hakmqzpm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwryjnq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kesdtgfr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqrfdsy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcqshym.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubutgvfs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvrucgf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljabkauv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fzimnphb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzhytgb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdrxwko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbedmtxa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rluzsfzf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hslpdtjc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxwkiic.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfppwtq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfdtfmd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ardcmbtr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kiosooaq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gopijbnf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgqtxon.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wukntvus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lijlzeza.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xebrxvnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpcpuys.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyynjjx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaidtrc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qiquxypl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gehpwccu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcsxhzy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkcvypp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcwmosx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tuawaqyk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgxbrzx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sjytvsam.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dolotxnr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbtkobp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmqlzaz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxfdcas.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eejlqgog.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnjwvqz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmtpczu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vctlrjps.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdneajwz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cugozbdt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dykeaiph.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzubufr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlodiin.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyruopn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlusrzz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbzumzq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwwpkak.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iykicwcx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbgjody.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpraklvu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeuyosn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2suddzvxo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yltroltw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfjlezh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2angqpcuw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpflqriv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlfqgtg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqohrwes.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwisrdg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdohuao.html


<!-- 参考信息 -->