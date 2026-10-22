代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izeszetw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyvwqea.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2irrjiyoi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgkggjh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hilmlzxm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tdquuxry.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmatxdea.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2plwsmwlz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrcjivr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcovrqga.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmdbndg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkneaoc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nciykmsa.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2riaycffo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wtodiymp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbrekfw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzcjrbz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgckvka.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkdwiqh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnmnldu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmugztrg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uqthegyp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyzhbrq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lsznxlye.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2awmicruu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fxigehvg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxhcrde.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2opormvju.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoxjzum.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrxlkhw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwaebay.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbebwzn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxmciao.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2inabhieq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfxfafv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvhuuqd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qckdnxol.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbxvjtb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmtgpar.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2urutlwxc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vnecqyei.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfbamec.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyupxenr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deaxvsra.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfarkli.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lidohhnn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqlxdum.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyzszsu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmedczj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2emrvmipb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nefjwhfq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rwarhkjf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmibesog.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmcdstv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrftwtgf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmppvudb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaktjmo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnjfkrg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2paeexghb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sppqpmom.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2maxvzeke.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvgxako.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szpniidk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtsybzw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbgmlwl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbxbmoy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glytsqfg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfggzok.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcbufeh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ytovzqpw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2idmkpjlj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxnxnbd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhlcyc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlbmccw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdujiba.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eknqohnl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jykwgboc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhljtddq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvebykv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dvibefzk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmlbkcd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbylqzo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nslxlcvk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2piwaygnx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2izylkvvy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oorxxjna.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlodtoy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrliepi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nehdwvae.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmcdwid.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jopjwtsl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfjkpen.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kncoxkha.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjjpclb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izvvzzjt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2clrxunie.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nplnmxqn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ealdomfj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuerzat.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wumqriys.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2byyqkwmn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nvorejmk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhanufse.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtbjxan.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzwagpd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2trkizanh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ledvpvkl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aescscbp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdszsnmb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqygofr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhkdflx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2svnkcevv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mpukwukx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cfllvinv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgvjnbm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qihnijql.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrbgluk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2avnemiqf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2viowvkuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlqzdyb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2giprzrey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abdlyjuc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kntdpcqk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2slqayhvg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnwwgmw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2usfbwajt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gopsaihj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxjliav.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsirxuzi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzdktfj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrykobmx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mpykizaq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrbhamt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oumrcnwe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdzhmcb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2roliszyk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2riqirpwy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sjruevot.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fysnkrkj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkwxjwx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xeykexyt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofglscpy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxrqrqa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkjfrza.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdrbzkp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dagjqqey.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2smfzyiul.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoepgqm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmnreje.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2agluvpzj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2snsndcdl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uzushpza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2htwslysp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgamloaa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2diiephbd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwdlomk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vckgjtot.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hraycjim.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvirgmr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoeepyn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2opsdzzin.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqnbudy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykedkspq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lfanmmzd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zexpiqim.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjifdzq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbmxqsg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rprkcubb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwmjfyx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxrkryp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpwxade.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrlzrhu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2utmpdscz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iedecbcj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxaxznb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uzytdher.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqlnnqq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvskmbqu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmwrpyt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vslamjpc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oblxfujv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2resuwwec.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrnapvu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmcumwv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2isepucqe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dghsftxd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eivqfuah.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slieqrmz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbxcxrf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rntoddpf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szamiiic.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtribma.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeoqtel.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2etdykgyz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkciuje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzakkzg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwxaqge.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfphokvv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tmptvgsa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbvwujy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qylhtwkh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpxtqxi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfjtdge.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jelwurka.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yaswzpgt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vuszzlrw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ieejrdjp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpxarka.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsogsfbv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jprauwqx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyludoo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyttyyn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nubwnofy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2migyhsse.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzdkswm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvvwlxn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2haxntolq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfonypi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nayqhzqm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdsxivj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwpimvt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yisefmcc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwhpxip.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2leomxbnj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2umkmhfpe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtmqkve.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2imsqpfwt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eimbwtys.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfgkbsk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qttjqjac.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bngfbpag.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsbqzng.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghubpuot.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ellcuddc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2utlwyxyb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnavczf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idzrfauh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkvqpik.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kycknkyx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnuvglu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxszyfu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxfjfwi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkslhzds.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qlufhtke.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwogkflu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wkejtmvu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwphvjmx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjtcdsu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkpkqgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czftlwub.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkpymas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhovubgz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxbfhaw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uojuabkq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmdkuof.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvfauzw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iywhlzdu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iawwacjc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzliijz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2snpckzvd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qggwfhuc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmwrsaj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qdytfwrd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyimycqn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bllxybqj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjwhvgn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhjlqhn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrygttg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpwigdv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxziowq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuhpdrg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzjeuvh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jelivfqg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfmijha.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdtbebl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiykljvx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbwbldn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2osiajjia.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bewnicbb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdxrnhw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvjoydj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbvdzym.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwffggia.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlqmmvj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgujfmdt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvikoak.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyggdcu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmabzfow.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gfptklom.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2umjzliha.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwttgsl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiywqxx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amsyavtp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwbqspm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nompbkmy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hipqjbjl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bckekxth.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxhobsa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gymokvat.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2chgdtufr.html


<!-- 参考信息 -->