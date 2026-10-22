代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwomhkis.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2avhyzhto.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzprzskw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jahxmihr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewljqblr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ordgucgb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeafijj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ayereijg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cokrytpe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gztpkony.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqppmsp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhnwkks.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gybbraav.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abypanop.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alfmluuu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqcbkbe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdjohmq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crbuzecf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2thzggfci.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdnymdw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2esmjqafw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpmlezf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkfzotg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaqwahk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzpzjol.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dejacmvf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2okhbrdvc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2guzdnydq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcckohv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvyciqe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcpfghd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2myyqotga.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2efzcgehk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwztjvq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zerpytbn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wofldudl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnbsswj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgliujfx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdrlhzg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnotaru.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qharhegn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2iktoxhgl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nayvybaj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2repfgfni.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywsyqs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtlsboz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpbzndx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2joiztjlq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxoteoi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoojyar.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdtdoas.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxpoglg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2izkvjkde.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkpqhbq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgxlyya.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bezyoktc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2prgvtdtf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlpbmsr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2adedlxmw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eebbmkpm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tikpykma.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2awnhtnlz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcsrgwu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbgpdbd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2czgtlsat.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kklhsnqr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdywcvb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyemciw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uypzbvvx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhgwihq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnohlkwf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nznkxqca.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkyvxlm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgiktfr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfhvahl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2csgqqezf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfwwrpk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2frkdinhd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2unvfnnix.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2csbneuus.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjlngha.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyllmjo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkrdkuw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrkbffl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqzkelo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgybokm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2onypjwnf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvpwiwr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2faljmbkx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxugqqzu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2snhuburb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2saulalwp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2watrcatr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtcwojb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkftevie.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfswifg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2trcycbjz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoiqpxz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwetpcs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyvozms.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sqppguoy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2angeuhmr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqedfml.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rizxbzzq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqwpecr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kiypljak.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzajbdx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcvdpmx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxmmwuy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdozjvb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zumdfalj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vognmzjj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wasryvno.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2manmjthq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjmffay.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isspymck.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2djusbxqm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhpemnh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtmcfoh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kskebgoj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxcfwjp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzsyafl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqfqsxb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lmclmeyw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ntetfyha.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nikxhkip.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rputqgrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxptvwex.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmcuueb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urgxengs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2becglduw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvsrhba.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjjwlra.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2krfqocqa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixzmlfq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlzpgze.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnchhdwr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lofbhixo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2twfamzsu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pimsukze.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uugojxev.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hccarwxa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcqcvgi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrvkbdn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zaztfvml.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rebcjpts.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcnonas.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kklperzq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzjhsej.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dznmbtmz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvchmvgp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chufvifk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2buylmaxo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwgwzbs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuufrcg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpimprt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zokhqqdz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbmsaxx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbjzesc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vknotbxh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sofvnbod.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfssxrc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuekdzg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pztdowwu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slrszpul.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gpazusxl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnzkoyb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfsjotq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ichmhjzm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsdjyvz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqokbbsi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2szpddxkn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbxlxur.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hstnoppz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kccvubef.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dmplnqhe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsgrddj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhdzpps.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwryluar.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lftpdmvc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2erxrgopf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2flzphlrk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mowuzyup.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqnynxs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyykqfe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2muawbbqv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaoojtw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxftfimf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyoxpgx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uigvsqsv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uojilasf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wnstivtb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlgdirl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgxizwc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fjovciqi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuvgawl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzzfkim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxtnwix.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrvybuv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocndxvnn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qaemsfws.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbigzjg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhunbat.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgixkyic.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwbzaxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2npkivfpv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuyktil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vutenswo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyctidw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqaokay.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svexuhnm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ynloxrui.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2utqptgtw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2edttyrpq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kttpcwvb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grutxvke.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhpjgdr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcpwrso.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mawspuyw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfsckpl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2afuzdaux.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zruvyhez.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hswtrcas.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcowxig.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hortvqmd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsmrovk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbcvoix.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avhtykax.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oolbckoh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhueyvgt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owmvolvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhvhvxh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmewxjn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhdicxk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfmnriy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaajpgy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2irppvckg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2szmngggo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fowfnvgh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyqohip.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onpiapra.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yoefjhmy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhulwxpb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbownrh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hytbxppl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mrixkdhm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2phhgqgzu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqvqoop.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnnguhn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeqoxtg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcygzulk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcmydoo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhgjayh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sltcpmsz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaksxrt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tjigogml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvvnrim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wavzugmo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2drescofk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fktaqmzr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbdfktj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxekbdfw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaitdlz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwhncnw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgerbcc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtebbhs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rshvzwym.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjevjpq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqbxdpl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoigzrz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqehbhz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhlvodf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzckenz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nglwfpsq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2svqpgflf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqvgxpa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuwekdy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2brsvlnxc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvxwmwc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgqsrkc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qecsdjwg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhbqkvr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2feozuocd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lofelofg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wulpzskn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqspelcs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2btkpudbz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2idkotfpb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjhrtvo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2liuymlds.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxvpohc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzetebdn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeobutij.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okvunhyo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yegpgqkd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dociicjb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmlzfdh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrprqqj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaukdej.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bubxmeqf.html


<!-- 参考信息 -->