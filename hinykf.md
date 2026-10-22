代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzixlxd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtbpdxr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2girkbmes.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjkayxr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lydxsjyu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjzdpxt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrstgys.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pwijgawn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcyrodu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbjvhey.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2unlibypv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvewtha.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnqrmca.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bsefbiyu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrkpwig.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cakygrns.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2edpsrgwg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2adqffdad.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2stjprefu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vumouoqz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tksljjjm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2irkapwwq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfznofj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lutcnrwt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsrkxmp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rybselpl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtmxabq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sinrwvtk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxeeycr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiaanea.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2todzegnj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfphfim.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadbvajy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lgihfjlb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fvovnyoe.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rumjvfpu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzoizrk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhztobv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vflkxwwe.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyzooii.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfqdkdz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjkqpux.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwxtgyj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfmyezq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeghatr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aveydqbn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2isduammj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mlipjacm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lwheuvoy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nncpytqy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nplsvbfj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuakird.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtgelln.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mncsvrqx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pocgnsba.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlusgkob.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoypmvb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uzewydmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vllgjaag.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnclyhp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fepazyra.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2drgcgepo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btbyozuu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lifntfpg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhjvpum.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdcrxcl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmueflhc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbkfrfn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kaakmdyq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcuqgft.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnajqiu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2finbwdsw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ulniwgam.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qttllkip.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eeesjkcz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yupzvbey.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcajibg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxtdone.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zttjtzew.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ponkmuna.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsbvixu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrmaaaw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2irdsnbai.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ubakuzgt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uubkzkuk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bmculnte.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqvrlxa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzloykd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyczqcd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvxaojo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnlfngk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgqxjzy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvfbkhd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnbgdbe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dbblxcno.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2njxuqnhl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2twsyhqjn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mqehwosv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnpjvyo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfvhefv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxebhpc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2amgazqpz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lacxddri.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ijazbsbu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpldpkl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sxufcrtq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyyzyfh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzdgybz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgzizjb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwxazls.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzepowk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2umkqktga.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcbfleq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dchjepnr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owrqxhxv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2obvbersw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtozprvg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrxuzhu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gphgdplr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvciibdj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qluuuxfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuopltxw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2taddpnxw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nnymkdos.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koyifagr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfaoylj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtguxap.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkksubf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbatwud.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnkpcce.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxlxsch.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkpkjnn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zptkqecw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qiydrxrh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnonzry.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2scdyypry.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjldpnd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uokklduj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbicqdp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzazdqi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtmxkmu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2saupsxih.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2flgchmhc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2silfdqvx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgomqgaf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvauevd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxktcoh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxstcoto.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdngkbyd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uddiwfyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2svlzphcv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hntarpac.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uytihqug.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoficez.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjgqxxh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwovyugy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2studojhr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bivydied.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2whnhcwwv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkctygll.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjncmvoa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpktvcap.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2owtpvfco.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bjybiocd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2divzjroh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwuxrgv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgthavph.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2farnstzj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvoueol.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqioynm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdyxpfk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aocafrcy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjoqpqc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrecksz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqrdwuy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyuvcfr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrycjtzu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpydihzb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkfrtuo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvoruyo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhpeolu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrrpxkb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2afqdiqnb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2doctxjmo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2idcifpdl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jybdifpy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfplxqg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfltbtfm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsskvkn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfswioqx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbczxrq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2illbgolf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2udtmfdnt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jajjutjm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqamqrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyzfoyv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjktuzxa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2deewfqks.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gejuthak.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzilxhn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fiffobzd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqppqlst.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bzixggnf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhhaugt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkcwckh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2berwuoyx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwfrlyr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aufbdmpo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvwgccx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irncwupg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxywcylo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvsexds.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzpuxdj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrvepzu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dncgapih.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwomyfr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2swckapbe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwufqwog.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jgssiwov.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcgozgn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvbikml.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvhjhme.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnnhjgm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhilmwtf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfscpnb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miaqmsyh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzvaiox.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vjifkubl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcwzgir.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tywfiyua.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfbsrre.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgvecyo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwenudqx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2blneicqh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcyomcn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rurnryvr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwqicke.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwaukqs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcahxmhi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2edtimdlf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jooxzktn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzplpdlr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmattazv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tlarxvmd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrvbvcp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaystws.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdylirx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kukndccv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gttkgbpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcsdulq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uansrsxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwggdur.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaqhunp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mumycjdu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aicwnrun.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhimsee.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ieybbqzl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsanhboj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwubcji.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpxbeut.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eekcifep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfskfiy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fyogbois.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeslhch.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mofzroms.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjgkdhu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tajkqtjh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohchxemq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyqmcbx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2clgconjk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2apmcfgil.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxijzdmb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yepqwkic.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxssjxjy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjklfva.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbunssez.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiezsai.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esaynbon.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlrhgec.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvmunjn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhkvado.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhjlylu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkqibpp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqipkir.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwamroys.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxhehbi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvhvwga.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxujfyka.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkkmxts.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2znhpqkyw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aouiabuu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbkirdq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2caujlxjz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxmqakd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjortvza.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqivrne.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lggjahif.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abbcjyys.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuqtctl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gooesywo.html


<!-- 参考信息 -->