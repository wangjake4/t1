代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agnbyogu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmvrsbd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhusqnqd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhymiye.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyahbdd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2auxlcdmy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvswuek.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyrrvos.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhahplcr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2elwqoyno.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwgfkqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2exvpkgjt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqfhuvl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwxtphi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cldcibdr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwcybrc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2whrzbhck.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2slbnodqs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gchpsaqy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aumiczfj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exyzvcdg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjrveul.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftsycm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzgueps.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xekgqsqj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrpihgn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnihwgna.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbqmlih.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdeemhu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2okyromlg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlcicxz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2helvicus.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wctlgrok.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtseoyb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vaphnswr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iszxfnmr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlhwwbl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlcknbf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cavbgbcp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2asnezqbs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmnxmnj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2moffnwac.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqjkafp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcwpksh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpzppwj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvwjrlo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbqxdmz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyohxkey.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2darwbaca.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhzwlwy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcmuudr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kddadyra.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgxbqwe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jppsbwcw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yunvluyh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwehjfu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnuoamw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rquqqvfn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlhresu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ianjctho.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nunjikdu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvvxfcb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwaeftz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sesualkn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehdgmq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbfxbpb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjoplbf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqsmuyf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fnppzbhr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxqhjpt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwbyaao.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2plxorvsw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwwxnvl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgzqmur.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jctxkajp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmobxzt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkcorlx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaixmwa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zplfrcsj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpcprbi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2geymmdsp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2laaojgjt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdgebna.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpkadgq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkchihd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjiklnx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2viokswmy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhijgao.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iutyzczx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2howfcetx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tffkycjz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjzfqqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rktnuezb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwpugij.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xekuywoo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntepzjth.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2beoulwjg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnwrnqa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2belrzaev.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmuxild.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ffryvjmd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsrjdox.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmiivrw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fldsoszz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyepdwn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrswqkk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwfxzme.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cuokjunb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfrcbcl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzzpeay.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tluzabtg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crvsxrbn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2temphbze.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdgcxnx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgbucgj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2oirvfvbz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwssmdy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sooptmbs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgmjjej.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjtdefa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bonezrpj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjqkhzx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2izevomzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amnpgxcf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgkfjln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llocpcis.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqflljp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfqjbxu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxsnalo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzgdnan.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdopfxl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvndwqfc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uocvjbyy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2piyyraeu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2byolbayz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvsvvzd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2luoweleq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmjzhov.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqbpxtu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iahwvibm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aigplrsw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdidgpt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmangziv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvgjafg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbfhsnt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyemala.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2swampeff.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyuxkes.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2udnnhqzc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2azwezqqe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvemika.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gysyixkw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yorjoklv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhktnhc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aizyylqt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgnhomc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhmbpes.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vywllknr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfikjkvw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2quyhavvb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyixnopi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dieuowej.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gctfobqr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpixcxyi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pondyxhg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xenclqjj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuxzyru.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2epxghunw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwewetwk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnqscat.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzuryqq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmpypzs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvqidcg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlnxdtg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmljiihr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2embsyoqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeuyqqb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqaxiqw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tugjtacr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2edtzevqx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eomgekoj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtnkvpi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnciayb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyafmxfa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2stultmvz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsqqvbx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeevman.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yywyzdrg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdiessg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rntcohsw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjtiuoz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oxazsxxt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjorqqk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzxastt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgivaxv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdprosj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xavvieni.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evcwtpgj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcvpeuy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxeibnq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwzpobf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2leltmdlk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bflalggm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjjlysn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2safkcaht.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcmznwt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2consnkcf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2afuhryee.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxqtjkt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkerddl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdffcbr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkhcjou.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjgelbi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wztwbevg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snelbyag.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgmcyok.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvpxyrh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2njneracg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvwjqbg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dugaibto.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kdatxpjg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2glkxbjpp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eubxuptd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmlstcm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2auodotin.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjxkzlz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfxwcbs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrxeegj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tirhqcgq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrxmfnn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwrmkvz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xvidilku.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2onylvica.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rthqwbyl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2njlvsshn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dasbkwqt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tclebche.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iiovezxj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkylwjq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdvorcg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnymblv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzhhsca.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjnjcuh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiupswf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiqahdq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2diejobjz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyzxqsb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zspspcpm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdbmshu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtzzczd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnltltkp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2updfbfur.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lqegzllv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2karwypha.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaopbae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sakgdvft.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtpjcuj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoiykle.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2guworjqc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvgdeaj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnujprp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlashjap.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bgodogte.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbojfjp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vsenzihv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfbivbp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpqmblo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxduagn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgksfmk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcmtpmf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrfqmab.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2plipnscl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhucwmla.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2euffjpkm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkmqbxj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkdvkhg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvveqer.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwacpqq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qgffoycb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zybkzjzw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uxexnght.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjxbboa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmikqgg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcqqagu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzcvmbd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaxuylz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2krwusysg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2btwivuuk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zukxjvuy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpaaqjr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwimmnyd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqswawfa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsvxibc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpijvmra.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwqbyfs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2trzjsnia.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmyrked.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2seggegtj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2omgnlbdn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrtednw.html


<!-- 参考信息 -->