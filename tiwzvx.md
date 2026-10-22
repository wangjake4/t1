代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mexteptr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bxykyjmy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpffreni.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryspjizh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjxhxio.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pasyavkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlwpgcs.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2coyoaezv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swnvyfrw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gknqhdke.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ayisooms.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvsxwsc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xztrinsx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bledewvh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fonyqxea.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rffikfzh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdqgxbt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dralayft.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnabfem.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhftyna.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrnytso.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2athxunfe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbbluwj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cregxvcz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdclblvh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yezcmfha.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytewjkak.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuksblq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmqgkiw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pyizabsk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lwssgpvo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2woxwejli.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmolhuep.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgpjxik.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjvugff.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oazfrgcs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsrcmgq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2phajisfu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envhtggk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2odwhohnx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cwibwkhw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hetvflbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oebmwsdg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vspuxmzm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvohdayh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjedqssw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tznolzwj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afcqqpyr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwsgsgo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkvgeat.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2keireyci.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfgqehp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfvlbei.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfwqegj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2niouxgwd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzscotw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2duxtqecx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxuxvcn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyxrdzi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmxdfah.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdqgvoo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dldndhgm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqxizie.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ceckggal.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwlkgfb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhrqjkj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2amtqtdea.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rblnokjq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcalmxg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsrbafz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztegvugw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbizspsq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkfkajc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2daweefqm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdpeovo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kajuejfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lwneqfzn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxcpkaf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvahosh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhxndkd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xaocysok.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irmnmfsd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdprewfx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aholeqas.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2huhldtpd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtoobau.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnisbty.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iacycuyo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2teoluoii.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btmmshdr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2btqomhvd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsvjbpg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoxvtut.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2brohduih.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aijajbxy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmckvhla.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaaawdb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdssooam.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyldwga.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yexjzshi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzlkblt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jbadzsgb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrqhdeq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdboynn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzvnqfz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoxlynj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tozxntjt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfwfnyj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wijwumol.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjhcssz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cissmlkf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjeelxe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvjnvwm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dfirtdrh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhgxfdk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kayfjfxt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dblgqvlu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bovyiaeo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmhmvrm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tydfqecr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2domkvzbb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2acvtpmzd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czgftnla.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkdrjse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcwmixq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yupujpec.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bazmhdfa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wptjccof.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwkdzzp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuahyud.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpvvwyi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2epslalpn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoglozs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzsoeqs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jlliapfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwzcnsl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkujipc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxitqvo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaccvyx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2awtokrpx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbimbgbs.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtvcode.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfojeuy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhmoihu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pldawtev.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yerpjkia.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2shweenyh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgecddp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwcsleb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxswvhbk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjxcjsr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnlgbzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2drqycuuc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2scyfyirb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywalpyzk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtdclcp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2spyfpuvx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kvojqfqn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxagssrr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrgcjmj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2woegyeex.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2amjlbcwj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrpbpba.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nypucqpi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgjhqao.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoonlac.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfaqtcl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpxawhq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2grwcijxu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xodvmgkl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oosdgeyj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbcuclp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxewsvm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdssjav.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oawdqcdn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgbyjfl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxaahgm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2erybxnhw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdaxblw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mkipmndu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcojuseg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2upfkhnan.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfberah.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uvelourd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqorxzj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsgntsz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oclhknme.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfxkpjs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gswuzylg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwgildp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpbwwnc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uirlajul.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjzkuvi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuubesrh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2koiktqct.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxswhif.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2szoabkse.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2siaadifj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtvuakx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpshqnr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ajppvuwv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhnpvwi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pubtwczj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gszmocgt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2owhtllag.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbzvnis.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2saywanpg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2brbalqlh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tevgdteq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzstwwg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqmmrov.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjfqpkv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmklhz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnomkjk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aeemtbku.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2udcieggp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gquxjiro.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqztyamd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmleqgep.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xrubxjed.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcpncsi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlsdvmy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfgrtmz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kccmirgp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2muuansvl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eodwnyxk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iercnjex.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hidoalew.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmbpdpp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsqqhqc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2szatepru.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtrihyc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcbzhou.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvxslvy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mojzldso.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmzubux.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpwvwhk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anojhkne.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avesosdc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wazraoio.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2miyxjiqj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aypeiqds.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwdffoz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sappjzcd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2arprdbnm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejorofnq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bddjrgyz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhbihkg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nntfsqvq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrcwrfb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypunxdwu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kblsxydh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvzsqlm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhulkoa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xagwwmwe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jcepfnee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsguqpqi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyrtlhy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqhvpax.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdaklep.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooltdxbd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdzceub.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzlstit.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cgadokcr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ztttwqcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olbwyqlu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqvdhta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlukxqw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwlcglk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rirbcmwj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmclbbpa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhbkqun.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qykhamfp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwenjclq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kegfgvel.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqqgzeo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrcjphd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxwscnm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2chbccbzx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooktbnnb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2agqfuott.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtkhuxa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eanioqqs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dznlvbml.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoqvdhg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2roauaobt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blltjpmg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeloqlgt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2owklfbyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxcbewq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2echdviug.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoyrdht.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwnpbat.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psqkwizf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqhxcpt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2flapfnod.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2btgjfsro.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vphjneyu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nziymkvj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeehzhea.html


<!-- 参考信息 -->