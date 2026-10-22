代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrdpvaz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyawsmr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2siulcphp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azlumuvb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylobkwaz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2owgxnmgm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2srqrysfh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ahowfynd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkggxgv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugattwzt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bahwxcfq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmgkeqw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjtudyz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qnczimzo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsriuvy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lznbguyd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkezqpc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmwrccd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rihazktv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeujpudw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uioijblg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtqvrgl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjguvdbf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuavcbe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjkzgla.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkwlwcl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwrfchs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tweybive.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvgdufb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpfldhh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkrmylo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhjvuro.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xowzgzke.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwjicmq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fysdoymy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjsoujj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qarfmseq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eihiafss.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtuqisx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkiycnw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyhytba.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mplasusw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmdnmfh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anzlnzwh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjfyilu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wagzaqle.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwlempp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zgppnbgr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2unguqotk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2azmombtf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlwonzl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2stvlnqxu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2soewafbu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzilwtkm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2boccalkw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulautzyy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2risudtda.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqkwldm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhjwdrk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2juibkrrc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2smredcsk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwitxmy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvvmfoh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2elsxvjci.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2auiskwpi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtgnfzv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkgkrtv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrsuxqv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qfevqsjk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2guottmxu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2boruadne.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjxhecc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeqcqne.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqlrfdn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2azsrindb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mxygvxli.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2abfasmpf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlocloi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2osinfnbq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaazmli.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xcajsgzr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqycofkl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejozycro.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbyufed.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdkkhmg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2laquydqc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwvilws.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wthuusyv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdugcmu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dclyzdzd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2suamudbv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iiewopah.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wjytojih.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dticdwyi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ocolhlnu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqlpxck.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwacxr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrwtljo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2licwgcer.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fazmktmu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvosjtb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzwebdn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzutgiis.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjgqgja.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2abkaszoj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnmeamv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vltddvxh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjzprsd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbmkllo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frlzbxzi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yfryppmb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2serphtsd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xziocivt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqzgscg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwntoac.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsuzqpt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfovvoxd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tnamynhs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rsemaopj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2piwhgomq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpnkdwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yokruxmx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfgcswm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhafqdm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heouvrur.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2akzyuvwi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nukbbgqm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjcvwgf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmgorug.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2asioqhpb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2utqdtama.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2egyjnsyk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuvigng.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvkjpmd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2enqdqznq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsvlhye.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtiuuul.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2etwmojqg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwkxkub.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2miasueqm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmzkhzc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuddunf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvymmgjb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agerlwvt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmszdke.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sntzixlr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqfakdk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjfbxhy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcbikze.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyuzgmx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnvjjrj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xscapzvs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xedbdcsh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwmuwrw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqcksln.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhxfgac.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsuciug.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfpndbd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmucbxi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oodzxudg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2obkxkjiz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpzxpwg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfybeeo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uotnxyxj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ictuhamx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oywgmnkk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2eprtrfam.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbkyjgj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2knwpokos.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2phgusegt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqklphsf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfrsxdw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpaeice.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjrhzro.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2prgzielv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2veennfoa.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjdlrfu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2meyaclpd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzqqnaz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hphtpiyt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kivmqwyo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouowldih.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2weywukwp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2inrxnpzk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzlqhrn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ticxoojf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwwvusn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xkovirqg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwxdolr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnuimgo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhhdxmz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvoczwd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2slblhbjx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qprteaqm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2effzrbdo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqfwvrd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rywcmowh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2muqmfqjs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2exiidxvb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrdrypm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyzdzxz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqscudwn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2waovrzma.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ownhjhrn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsnyyyz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bipnkpsv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyynbup.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiobmxfo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvmaxhq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2amjxtyox.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iroswrkg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ncngdnpn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uztxstty.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgupwyy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2thicnedw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsaeazy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2akkrlhpx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iajnmnax.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2baxdyukd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyowpzp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fygctcep.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bacpcjnp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbgqgqy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftygkxxh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2psldzsik.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcrjqld.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvykwayh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpjmzsp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuihbkt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vucazgkf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oevgiwuk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2srmpaehk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urkoroia.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhfzjeg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gehmhiob.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fichkgxr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbxkilu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyhvylz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmzpyqi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbojnls.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvpflji.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2prkspjbw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsbpgxr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bmijkhob.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2igiygpzw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kempxity.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqueerg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cancbhkl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzobijc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqwrzlp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwfmne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxwzirm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoaygcq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzlosmv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mscgagdg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqyzicc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zqikatin.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2algaemyw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2frbkqlee.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhbksta.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2blpqdoca.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxejlas.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zptvplsi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkovupx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbhzliu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnhwomx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2varmjbkb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2seebgyoe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnyrrll.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sctyxcnk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxddkxvb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2adojtmjd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vokqntak.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpatzgi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2duaewirk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owcniiqg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wedsifqe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dskjvltj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mcssxxgp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrygkyev.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeykuqk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cklzivqp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtccwhk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmohhxf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhjmzzq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqenkge.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwndsck.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsecvfyn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgxeyqn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztthglyv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2igyxktbb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrsdalk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wadqutqt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbokygxw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsnfapw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zydrzrxd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiqtwaz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xekewwmx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qnepjbkt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jihfpyxc.html


<!-- 参考信息 -->