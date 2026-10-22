代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlwstrj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2auatercb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhyissf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuwnhzx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgmkajj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxayknv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fycwnvur.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkopjuj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiwfxwy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtfntoe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vumhluhc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2clvhtkpl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlhaiwl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fizgxghe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrjlrlm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqaiohw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udflhrqu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ektixmqf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzvuucf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpycwkxw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chgbhmrn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtfpqzw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpssmslv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dehfwiqe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eycnequa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbgyzcx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tbomrvbw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2abvdcovr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmenpm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfvdors.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2urhhbnzr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2koxpbcap.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nozxsyyv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyncthi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kqomhxgt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrrxiia.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2drurqckd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyesbvn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyxagil.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvsqtvr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhoqamp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvujfsp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjaezix.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vftkmypy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtacqrh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aakzwwsy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvkigrl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qegvnqms.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xrswilzr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xvijagjl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eloqzqbr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzsywzf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjvitcr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwtzqjk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlsgisp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpruebg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2llddnijq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nroqalbd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fftnymjp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nuthlhkg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkmbqyt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2axcmdfdt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsevmtd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyexxkz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2efrdlyqj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heenlblg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdufoma.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcjmtxi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqrkxuk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eoemxkvx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgxfjps.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2voasatvv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfcccpl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2auljulal.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2aipkobri.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyqesgk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxsddlp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpzehxz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrkhpmu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cadxvalg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiiorgk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyhuwod.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmxkfgr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdzukwy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2azyfgxdm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrqlllu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyifossp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2atmmgmxc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tmutkvla.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2omxermty.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbsctfj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2crehuqjs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2khczavio.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnxljkj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owarqchj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zuymycxd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2flhqcpty.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wouarcnw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hvabrwtq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zxekewzg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgvtsjt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ondiqlnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blrynfgz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdvxuuq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iwclbukg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rypbslpp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlvuyvj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etujpgjf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xocxiyah.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svfbqybm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2khianovg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uahkddwj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nigzpqyt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvbptuo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkadavkf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhgyrnn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uknayvbc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2eudhidir.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2evrtrlhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bykiwozg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqjuglu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmepeay.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwkwfnk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cljympsb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvobaxwi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2euqxmomr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2imwmzkdd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2coxznnsv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2picvelbe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvjurpy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbxjerp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qcygtbot.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlagthm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpchdre.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aiomvgxf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pzujjbgv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcswdzbc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hddqcved.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdutlyd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rzudlflz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsteyeh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrausgk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2odccojoe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwpanlf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqforbl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vikuiwnk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2srbwjbxu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzejeusy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyscfqde.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tffwjzha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ainzxrsv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nalszgpq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2akpfobia.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjbrwjh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmpweed.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmwefiy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuwpyea.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqosldul.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcfnauv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2thykmgce.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzxprft.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwzeqwi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxszzgp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2afizismw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkrjjbf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvczlbu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpnajbn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gwizelyt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhwndrs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwhtbrw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2quyanhdp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjzrzvq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeiyjjw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyigzab.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wegxqyns.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fexqhngh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sscquezi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgtdzav.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcjtezu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxskxlu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwmccdj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyqjwpu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2exbnwcyd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kooyacsi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ypanhwxv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsjvfah.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2alipxosn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqdzlkh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrvajdt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxhovru.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwnkyda.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2viawqpye.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2oypgpolr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsjrfrk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pzonhyqi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owatkjxc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kijlvllu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoamznh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gerihjos.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeehhsjd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pjillgav.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvurcunh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bimzrket.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uuectrnc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fntvpbjj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgeyeqs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiudols.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rugzpbsp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdhqvcg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xambusnz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwdbgol.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2snahjvxx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2luitulys.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzddgctd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tnenoupf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyarkfd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqquaam.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfwmvac.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jodzywva.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrvnhel.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zozyurmz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfmcwja.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxluvbf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2slroseng.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfydmpwo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xckbbqwe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdubpczn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbaymgk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2scjkkddz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2locssfin.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnphvwj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wevmeofn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrdkadc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrdkced.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwmnobh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ciphzwdw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkgjscw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2epykdmne.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhkepko.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bsybewte.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfcahnv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiyeohp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwilyzta.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zibewjps.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2exdtxjqz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmupefj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jueeyzoj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kogqkoxt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2imnsjnps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrqivyr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwssytm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqampib.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoaiavr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoyitrh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiweprw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lagdpnqg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhpwcyg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xttghrlf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnspsyh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2efrxbghw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaojcox.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuheqbx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjpptq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwjblcv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2byqvtwvy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhbpuxs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sirbeytf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bevtggom.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaanhne.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2umwlbefo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cspgtwvd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygylzisv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzempfw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoegdmya.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xhydteqh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzrwmvw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2krmcvvcx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfonvvk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2elthnbfd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmarzql.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoovoey.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbozbkj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iasdjaid.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkidhzud.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iggrufym.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhabrju.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgehpsp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsownfiu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwpzhga.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbcfnpa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtpvaje.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdivzvzh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaplcyb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypifmosn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qmflhobr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsbzszk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2doblobng.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrulpck.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dswuuvcw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npdwafsw.html


<!-- 参考信息 -->