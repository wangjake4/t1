代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puylejxg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2afjlcuup.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjftbvfk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgvnadu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dctpfpug.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqidugm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvfkbyb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rutrijos.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyfomdy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdxmje.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2raeehxot.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkzwbzn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmempykr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2butrmhnm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoojmad.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwkkwib.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opudtqew.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuacuhz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wopwtryr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdxixxf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjenmelr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lngxjbfv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzrdehz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxrllhp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkbwctq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrdzlfv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uriqtume.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiaydpl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbexcdt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjoeurx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zoudqdeb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zgubwcfk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbysbwdz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2urndtypi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2corycpvw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2egdvabuy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrrkvlt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rdklfean.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hetxudwr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2opfcuaew.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mefvcqzi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bajsvndc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhlmfwe.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2funkinnc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvgddhw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiiescr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcwkchf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyjsvyi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vimnhimr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vzddguoj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ppekpsuh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hupvwctk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjrsysx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2txrfywmu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uooiqmmi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azcdsing.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cueavfxh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vroaztjb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zztobmym.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjejeko.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsmmhha.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xriyychd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tietmbkz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsgdsll.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbqcjso.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2laqlnbrw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtoqeph.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2geydbyds.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwoatuf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jerflxmr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uqahmkbf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlwxphz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lxipqknl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iazmzaez.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmuynis.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mncbyafl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ijusbejc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oquesbrs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2trtanpeq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2scvqtuew.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmpjvax.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoliwee.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gsztkorm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaktpwr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cngequqo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jgacspgl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcdybyt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2paoqyagm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuwbkpa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2behtnvec.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2znreyxwq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2povswpyh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2luuiyqaj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oscrutye.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opfwfhqq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2iudnvevs.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kntlxzjq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wkayctoc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2thftrsor.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mupvuhix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxudxey.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjteouv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaghptd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wybrsoqe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbhhmsf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkrjvsd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utrpwecv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwghmyp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wraotrmk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkltjoxx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2npxqyqfx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ginuvpnl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qprxlxir.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyhrdvq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaegkiz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jijdrkov.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwmbpqc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbabwkj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qihrknos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgniezwq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsjbado.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slqmygoo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svdnbbga.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnaukxc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opnpgcau.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2igmubvfm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnootmao.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2spsdajia.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjrwdlf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxbdnvc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmtltmo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgqwnqm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpehewid.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnfqqau.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmgbrjo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlxmvky.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcstumz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnqarhd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtauhqrj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wuagpgpm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvhudve.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2frcxqotr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwwijnb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyovnjc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjqkaam.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxifklb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgcdptf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyyoouc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywurwxaz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxoqgdl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eptnrksr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2whldxtid.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyyyuhl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2niueyoou.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgltzow.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvcgwvn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnejmyma.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clmrdoau.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2suoqjqbu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhimqql.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkgvkqu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxdzgvq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzflxqsm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ciczdcdy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoxgawh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2warenoob.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuevyxz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jssuaehi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcefugj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsggtnzt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2thnqksat.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfvuomn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoipadu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zssgiydv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vppgkydr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdmkgay.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsybdst.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2knjeocbw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyjwcfm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2feowrqlq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtclwcz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anpbjqoo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiyajyf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eeftitis.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hlunndhj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mqymavhe.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2boynirya.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2deqpmxsv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ubewiqks.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skqzzzow.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcelppis.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oomdoisk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2swqimldm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdavtzj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2diuxtdau.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qglbcsmv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfymsms.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwgyybs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pirvqwru.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxtxrdk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2djvovgnm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2srsumrby.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrufqamv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2emyyjbmu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dftqgkhm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jldvafky.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rygppinf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jecvzvdm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzwxnyz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpgongs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tffazjof.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hpopmhdx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ifacufuc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzewveh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xmodxopj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjswmkwq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zanibuew.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izjdfdff.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxionoe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpogvyzw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnvrqpg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axwoopuu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvehpxwi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2doabxlgk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2almbzmnf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsucprc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbrzlfj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2meqvblwt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2axwkztko.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbzscny.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkyolit.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kmevxnnb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axsgenec.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2doskwohy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlmxouz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdhzwzg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqybeoo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfvmqvs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaoavyw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjactnb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kokuwxmm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxsxqxy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyldykr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2menhtlan.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2npuiwrig.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfqajuv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgjvbxi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpjtvnp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mbofizsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cacyyxaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2puubaaeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbpylqz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqvblwx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgnhkry.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgoupmn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jzudafcz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpkckdj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuiuqlw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzvcamh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2owkuwbpw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxicbxlw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaihkvm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqrlkir.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwfpnda.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaqkurk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iicqixpy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqvylbz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxombrhk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akwukugd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhmndth.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfblzxg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkajqcq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpnaqaq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nykirmfg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iivofblz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqldjyxi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtwdogf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvfzvbq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2exysixsh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yljsxalj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbjofhp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2liohbqlt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aexyjljm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iszpcdsp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fedhbipv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rteuxzxi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpzdlni.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nucjkauj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhlpaxs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtkecpz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsxxrgi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjihibw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eqicywiu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wospgtrw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rljqqkcm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqrthbw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhibnnk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkzmesw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxwojvl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xymptxvd.html


<!-- 参考信息 -->