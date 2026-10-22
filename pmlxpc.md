代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgpfagw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzmuoxe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtekpddl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgnvcpt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdbnnef.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxibaxhl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sddykivy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exzirdtm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gllcwrmh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuncjum.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdyaowq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wovnbhaw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpohabid.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tenaitvs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2twtktatc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gclbmfvu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiqrbvi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jmswkzzp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuzdahc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmsbuwu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xplssfsb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmgromx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gekbsfgt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjsjhud.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnymkpzu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmycuhh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqkzqoa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuifcjn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eklmtnsc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2grrwiast.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrazotq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bgisyvmt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2erzpdowf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rhktqrxd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcjycnm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrogefj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rourgbzp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiuhanb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oyulcbzz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsjzqhr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2njdglnvj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eukqkdmv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjmxmri.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zdspwthg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtgbxgb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fiidpxkn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sauwaagu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdqejim.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qqunwcdm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkfknkz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfmgmpv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2upvymswt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfgatao.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsjougi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2svnomdkc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvktdlc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrcrfvw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuyezfa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpqdpbr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtbxigz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dnahkgwa.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2okdmbzqn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtmqvsi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2isoqkfmn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2azvhebrs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kclyyazu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuhkcvx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vioiznex.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2brzgkojo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2goziehqy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzzejva.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmsjmes.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqkvnew.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpwqzqe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdmilwc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rlihvihw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vafionhm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnmljzu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yovhbazw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuagtjx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ompywuas.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxopauyk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2crgwfjoq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmguiipb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2webdigga.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbujjxb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2krwffshf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcsinio.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkgldgx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfraqae.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gigvcftq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gacewlhw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2thvftfww.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2awlhuolf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxhodom.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmdokgp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgziqth.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gshjyqys.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kuidlltd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dalovpnt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnetquf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xereprva.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lcebzosu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uptgkjkl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcujbqd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tegmsllq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rtchicth.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wuglgstl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jabqvwos.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlxudgi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgqwtha.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkrwzpb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cybkcvqn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqmaanp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tydvdxhl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmuedgs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvaomvr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnupgcd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfujlgh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oiynnsbk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vubtxtag.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xbglblsc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cumhytxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhpuysy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbggalm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avskzrja.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmmzdsl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjmblfu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cixhqenf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mvefvxvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzkbvug.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dijdghwa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlzetao.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwqrzqr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jftzqieb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpulnon.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuhazvc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2betmtlwd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bhomxtbo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qklfwjgx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkwmxbp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtaxhfg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iadzzfhf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtbxjcz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxycebj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2obeihwms.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhzgnq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpccjfm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgujfxw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupbrpsa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bopzcchm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwybptbt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oltfqdyb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2knacwnyr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gagnhtsa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgxvgeh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2emvacxnw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pijbsiee.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qovwocoo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lulqnuwz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoibmtf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvibobym.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2haviblfe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oezvcnzp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lybfoeep.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2awnbqztt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkwodhi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2htnpgnfu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkackuhu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vdomlnii.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaggwbdc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2unafbvli.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2evejpbxm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2okbnrddz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hozwkpwu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyymurw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sptqulii.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2waxcywjm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeoegwm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gztfnudg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2djtrptiv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixruchpc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxobckyk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqijlzck.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxepuhb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxsivoi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgsdkvt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoyhinq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcnnlpw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2alvlbzbz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xogzkzyo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vuorytza.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dhihgbpu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiprzxzz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfmtqcc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfblznfn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2accuodda.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaiiqyh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2anionsed.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsxatcx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2smkeuvlf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xspiyrps.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gemtozqf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxmexsg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjrwqwz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pehdwdnr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2csywynpp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcwpzoy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzmgqeo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjeepyz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2psqbzchp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvombrx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djhlkhrt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfikbcw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2siclknnt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbenlukx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2auadcxql.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2grxbjqsi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcoercz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgvfqwa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qttqxyro.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2obymtdoq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mcofeozj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxkpxma.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgydabm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pykqvvdf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpetonlp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjxhpwn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdwdzce.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abyacuvn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyvzfmf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkeasbn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jenntlgm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohykowgl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zebtotby.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qbybwugs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaopbjm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2coemwqdh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pexknctd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mctzgcnl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeilyoq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ceydevqt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gegixomo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqkjqnu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaquivf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulshuhrf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cptvscjp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbjblfr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2haztpglv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xtffwvfb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftkxut.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lyleefpz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrzygne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbqyxju.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrdplfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irxbietc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzikgkmq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysptsxfg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hajfyqob.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgmoryg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkvrdzg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvonahk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsqzric.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqjlhfq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmyinmu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjndbkms.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2godqigab.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtapxwl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsqeahs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sojpjmwi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaickgj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuqpedw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlemlvpa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2furytazp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xslghoye.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2skceinwe.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzznlgw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2efzrvrtz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ordsauhs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnnwldq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2esjfasns.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnpqhla.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrjufmp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkyecxw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnkfzrk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfqakiu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icsmcifd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpxukqa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiyxamo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bifimgnm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2egrxlpsl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyynpob.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhsvsaa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxnudvb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zzymshso.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2drjaajcx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fkexrxpm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2scwcmchv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsfklvt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2odgtlevw.html


<!-- 参考信息 -->