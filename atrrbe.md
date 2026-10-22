代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dowofeyd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjexlhv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtclfnfm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsrpier.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idnskjmg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsqdywt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgabexq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mttmbqds.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjrlkbf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdvnrjh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmzqpxb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ronndepg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ompognrm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoqfgrc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvpprfz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2khzcwawj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaalkge.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgztjwh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mxadqqnm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sogaiisr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utegxkvz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmgmrpy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqszafdm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dreidqvv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxwjgpn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyilejm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uksimune.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnbldhb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cmesensp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oekybtwi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmzofbv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2edpeoqpw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nigcrrro.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwosump.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbnigwn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyijbkd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfqkfck.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlmxkho.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmjosrr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlxmkcb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pelserfr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aspkvsqp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfszdcp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zievinol.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aalbnetk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdwtrky.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2piqtttru.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqzrfcf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxnkjdr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zfubstai.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2djvxwrcm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoqngzu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2myeuljyg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjtbjqs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zblzihll.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2plhlifsd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xobyvqdb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjarbizv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xshvouis.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rejonmsk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mnptwgsu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtzumbc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzmmtbg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtcynna.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzdiwkt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtjmiyl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skbhbkqx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtxksru.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xivcmiio.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sloprnuw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urhrbfds.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sspqvtsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2izyfwqob.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2klerydva.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rogcxikk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hyybjhhg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjibytm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dedvegcv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzyxjns.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bbffgaui.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdoarek.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlutdlq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oqugzuzy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eejfactw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpbvsiz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sooqvbns.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqtoywd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzournjj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvcnmmv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvnzuho.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovapaxjg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vycplsdd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xsigslto.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvikoell.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpaeaoe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjwyngr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cubmntmt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfdejpv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2axoehqlb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2enyjeldb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnvuesh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgiwaoa.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jfodvhac.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbimrluj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sinxwexn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2slespywa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2szxbjdoo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ameqowcu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vivdudve.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2olbpylvl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btzrnsfl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yborpwzp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjkbmzp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lktuxepd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yffqqbsg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmhapud.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvelujd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2haueqrcv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oonlapyg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ttglcjzg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oocxzkbr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbsejag.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qltvvsld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcxblwo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2djldmjvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pccmzirl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvbntfr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhrcsdg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxmoaby.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqsxdhe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyucltux.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2knatkyds.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lunbbath.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mylgevvy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2brmxhnuw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hozhukaz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eipncuje.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qasdoehi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdqhunz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cilvnvrj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwuxsgb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bzictpwt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaojnbv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sirhzspo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkatwgw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxtlupo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnoirzk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdmhlvx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcgqqqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2caojulbc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzlgwoq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtreljpd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpfuzfy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhtwekp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqonlqr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdgwuqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2usfyohtt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yditfnpp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tmawjgkg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwfytnn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyopwzaf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qakvjkko.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2itgoacew.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dohggjkn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhcxakl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpdfsvj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2amxxrkzl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnseuxa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rluwnxwv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ekscuwxb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcrzytr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zlusittm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxymien.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwghhax.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzeihyd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ogidfetm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2maqiytfd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2plgimclp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wniahful.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrezplh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpwgeyg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcxesch.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwuimmt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjznjhy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdzaank.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrdsljf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjysjmjk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qayegfyf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uuybvcqq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xulsfczt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cupumcsa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unduoxzo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpktdft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzhhuqw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvstrp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tftllkwn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxwkhob.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuptunwr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2luylhgbw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytunjnyw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jzccbfhd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjjknzs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wzppqpgj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxksshjl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iferosfd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2extlvjqu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gpisolxy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjjnaax.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjkifkv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxxuvzs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpczrlw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axwqxggz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbqebdl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtbcmyp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2radqhscs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2etstvpro.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxbgqq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uclkbrry.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2agluotry.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjlroaa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmkxvkf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2akmqchwb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fxphxksh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsjncac.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2teuasrzn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpgtbgh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziauzjem.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrqhcjn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxejgbl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyydwjsq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhfuvyb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fsftqwsr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2awolqzsq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyqxrwa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjnfzwv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeszwlh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opjiwnzn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtopuns.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtgliuf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmzhbnq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaojmel.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnzdkhu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxydutos.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bubdzrwp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbwsqms.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkteeghi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2akionshn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlhcpjk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjnqstx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hbufglbf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lujhznhz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2csbipljb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2darurdfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxqzbgm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdrcosb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyripwn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2igunbdvq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwriucgr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdaluot.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqzegqc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzgujjs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuxcday.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcqtabh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cknovhzq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvetbty.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2elpyhemb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yspreqhv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsvnfvs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zecwpzxf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwrohmw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fjadmojj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxzkuxq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxukfqrk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuodojv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwcsvcb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbwfvct.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgbyapw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabkwrpe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtanagr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqvwuza.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sxryerks.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsndxxh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rouptjzm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbyhsdl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmpchvb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqgltqo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkzqfag.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2folsxsyt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eupbokxx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eagvbjtt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlufono.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbsaixx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iabizagp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbgnunt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmyqnyt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoydfrot.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzviodm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2foxmnjcu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2llpykrwv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gzctobcv.html


<!-- 参考信息 -->