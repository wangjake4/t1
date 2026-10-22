代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcavbrjm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2htaydbku.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dspioxes.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvrptnw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dryzcvps.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlxvfvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbpxgtj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2opmbxbuo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qogureqr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpquuid.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cksnppmb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uelcotve.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxtvxtt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iirpjyiu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfexghp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkrpbuv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdetqdib.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uynmzojp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpphwysq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uazwuuay.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbmoyow.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmbutqd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shudlplr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqwtrht.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvfpolb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2idjkubiy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2thuoionb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcehxik.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyfppml.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbqfdac.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbbsmqr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkhunsw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlilrto.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tywofvjx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2chfdgfjg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jqilccxe.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcgalcf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkxglqk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2indrbnjl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sehsbfmw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2igsfbhos.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjkbpop.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epukvqbb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dslopjge.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2veuxrohg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bndqxcxh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iuratnwx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fejxeowx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxstxei.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wchoyxcd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnhpxzj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uukkveor.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvlwipw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtclpptb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgngqfsu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzguiiy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdfrzbl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xowcfwas.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmwqgod.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2iqculmso.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tajmuerq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2piuvcybs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2roknwadq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kirrvwxh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nyagndun.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmaaali.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wndbfzfg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrgscgk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyawwol.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfczjim.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvlnzxi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2owqvuzan.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gucvnvxo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxxbqwz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hgafuues.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrmmgni.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnibzyj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sermtcdr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2isyjwekx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmyozul.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2iybtiqjl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khiwixfv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsykszj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uhydcvrj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2blhyofqv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcqtcdl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcgzsvb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouihudgq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ybubyift.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pupzbhub.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcopgvy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvtxfuw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmpvsfr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bounjfbl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xudzozvz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gruzpnxy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmdoofj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhkkfyd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpakcat.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wpanyzmv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiydgltg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hijyerwh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xorzbdvk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mfftieet.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjwiryk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhftsrba.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usbslkde.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqqyxts.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkshfdr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsogais.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pawovthn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsqnkfk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmhrkwf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ursytdcl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgghycot.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jqllfsqd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtspayv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gfchkuma.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eghtrenb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbncktza.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlrvcrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2somduiaw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwsdttt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhwgplg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txdlqrsj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rkprktrs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoplfsy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqjqtxo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfsrqej.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eavihdpb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pngvjvcw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgikrwz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fthfyzgo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfwrdqj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tateihbh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhreflx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbwfcip.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kobjnxlw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqklfbg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmhtuvn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvsztvz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqcmdri.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwgcqpq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnvjbrs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkznrudw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2juenffla.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyiydjd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaedyhd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjlppsa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vkleydns.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcmfvxp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmbfayp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuduqwk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtooepuv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ugconmmx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ppodpvlv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ispzlwxu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiaubwq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2obuthonu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2deydupbx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkkuvhd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iffdsilk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdruqkwg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sonxjrbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jffcciaj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpehmkf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ostvhjys.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ktakjapr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuypcvkk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jljfjyen.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswtmpjy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwyeect.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvwifpb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzkzimf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbyyyfz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqrphhl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbughyj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlipiij.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pccqlgyx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvrrxsw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvnprff.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urmwfhzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2utowisio.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ljleqipz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aanemeda.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnuhpin.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfofpwm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zizvmusf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yepxcplb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtbllut.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtsynxy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2luoirrzz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjekve.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lorahlsj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdhsbbc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwledps.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2opiaynzb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvjjyyx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkinqxmb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evblhyhu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsgelgj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aitjhvxf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbbkupc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhcgylw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvhvcwr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jkltmyez.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2whblylxk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxywunhe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asiesopi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiydnyx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vehjyuif.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdzoest.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuwuids.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2njbllnxv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rinmpned.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevybvit.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xdujurca.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkjftax.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmbdwgv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwplxlhr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yufvysbl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqlaubh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvamzazg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtzmeat.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2scfimdhs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qetsvkkq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2clwowvfr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjttwru.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhitovn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjajpusu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuhwhqf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2olblemda.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrpxrla.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyhmcig.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tytduvce.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcpftsp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgbojte.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzxtlbq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mebotibc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrmudqu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnghter.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwtpuua.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxriketv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2atrvxsju.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfswnur.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2njauydfh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2meverzel.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2enbtmlkg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzopepuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnuakwf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxmzzde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuodyhv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yptdbzcm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzfujsh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhsiwek.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gryonxzu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2omrpnlcw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2evvxlrpv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kizjjost.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dddnyeyu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pugxqofn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrrvewd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lbszttpa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pujgztai.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvubvio.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dicrkqxo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbiskbx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2avbxorlz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyhbqma.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwowshqw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvxlvpd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2arolarbf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyiwpka.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yucegxpz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaxdsyj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjrzfar.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjyxtl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcmyaic.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2syevbzpo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnahskb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvfyjkn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzfycwx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evafhzok.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyceyef.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfazysdx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kswpbrbk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2glopsbxr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rukdzvjc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jsifaend.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbojogal.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2otcfljif.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xboiymwj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxswjhg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoeqzzo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxdkbi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmydyybv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoyhvcs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhwshys.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnzftdx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsasaqo.html


<!-- 参考信息 -->