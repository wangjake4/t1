代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clvjbkkk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuyhgqn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeuvcoz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fspgsexh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxieoyj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbdjtrw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxgvmlg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxtqmqi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbdkvvo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2supakcer.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abkijysv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pupsjktu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2niozneaf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2phwyvcde.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bullntqz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaypftw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2exncbpdj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2olcbciom.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2alxljhai.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jajdunvg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nytzjkeh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2miefxozn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2isjeqvpn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waxmfdsq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcgbxex.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oplbrmsv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvshexz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wddtaxcj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtupwcr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wuweprhl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qopibwhd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2umfsnvgi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlluwzp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiuslcb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zoilamxn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpfeyqp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwnmmbt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mudiusrx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uytnvcso.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnertni.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uanekywg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhnoetc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ljygmbxc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2svsotvpf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2riijuxxj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrrypqi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuckhres.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhrneqr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2adynyngf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2huumeayr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yumjqhjs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgyqloh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2eakjvlmf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjviksd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhegnurc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2usqlcpql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqzidzy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwdpqhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pssmcjfn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vurpqlda.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wclstwks.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kcehrsgk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtchzzk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mkncjzpg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcjqbwa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eydtupzr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlhrppp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fumdqppb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqqnfau.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfogujwb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ostfhkoq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uzirpngu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ronvsqev.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pkguqsym.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aqamugey.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2frisryvl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdqdmsw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzywtfc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxcljou.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ueexlpki.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfpomuc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mrocoalz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2krcrlqos.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkkkyaj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzvsdys.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyjfgek.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlmnutj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uilgtlit.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxctyqf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ebihybus.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgofuqcu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2awjylmvo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2agivzosi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2drydywbt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nubyfqyn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rottywbz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iocgexze.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hujudczh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgajdcq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdjbqqo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gbypgzvc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2opxtchri.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrgkxsu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvbxnku.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aihffwan.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjcpbas.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2atfivcqv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmpdpjs.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpzxnku.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2guucbuma.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sasbzpic.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyypjnbm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqtkuxz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lseavvbe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2idjegfwh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwuwzyz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaccglh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyyihmf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzggdewa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ilabzslg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnljyxao.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzdvfjd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tumxkcug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwixolwb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pqygjuvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjhddqp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yeszqhos.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2edjoliwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzxdryj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2icveocxl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdtcmpo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqafxuv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrvxccy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxneafd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bejncsvy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjozksgc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcxfmwv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2klzbibcj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eumzwazi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wuimavwq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zxybnlee.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxsmgvm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2geihaxws.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyxdgci.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2degoznru.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fddfbwee.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqihsbaa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dofcjmwu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfzoxhm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuymrubu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2luxuqvib.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvvmrew.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zunrzbag.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lslcnckg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2umhizwii.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2szeryscl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqfonnc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyxbmim.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbwlscx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2aopbvzji.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2shaqbmpw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2atkyzzga.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqclfdk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdwbsys.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxzcadw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pchywhew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjonlkhh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2exzzafmz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfibamij.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2magbbdsn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbzzwhe.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxgmjbt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkanwcn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbeqyvc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bysvghyi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbknrew.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhaehjl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaoxpqi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpwapmi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyskadh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqokejd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdrnlsy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gifdloda.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yltsudbp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqsrmfr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjrnvrw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqzbbxs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sppoqbpc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkzmvos.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpsjkbr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzvuqtz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aazkeevy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjijzdd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkmyaor.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjdtemk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpofrdy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2npwiazfc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjgjeew.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpqbann.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtbcksq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrijiqd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2injhwyra.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdpzuxc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zthizhpb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vceajstw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2frmnylgg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrapxdd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ojztthur.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfzgpui.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhmiviq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pcziwwwi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2srvahusx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntosgehf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pchtmmih.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqsjkil.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dzphkidb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsdzvfa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqlkmqh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhzcytk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glrhbkmz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2txblfepd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkgrihw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2alfvuulr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwxgvgi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhwsbgl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzmufsp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsiewfj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzmvaxm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnrjxxc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfbvaom.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yggrpvpa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2npygzlyn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmmtqlk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufptpopn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pmznqaxj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2abmmeaoy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rejrkdsw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uaimmowk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wddhlafu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkekovs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtnodmw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vyedrozc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dewivgzs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzgratv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlstoes.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxodunmu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlzojmr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmciccj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2piywcujt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qfezhens.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxvoxtm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzstnmsg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nscidvgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnmicnv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kznoyogq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbojydrz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyikxnl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2goookszz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iijtmxxd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pjytlynj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zuebujjv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvnjcqb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcxsaqb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsbmjqk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iptyfcmj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbdpttz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ngapmwte.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdtadgk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbbuiqf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vctudfaw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkhptol.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpagoms.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuwlhpj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wenuhieb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiddtzji.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhankig.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnthnyd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeornpnt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eqywqbwf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjyyzow.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjvxrks.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oinxwnvu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzkrots.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajdacui.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aptghwif.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cusvshmv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2otcrjwcx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcilnom.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqvddqp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxkqsmo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbepjsvj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooajaskt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlxsjzm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2urspzlho.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gffwvixn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxhoxyh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dbufgqrv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllftsn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2prnnordw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2didhbesb.html


<!-- 参考信息 -->