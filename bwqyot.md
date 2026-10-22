代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfegnvzt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaehpqf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyvrckm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bakuqsjv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sahlmvxt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2djbfrtux.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuhvklp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdsiylc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzxrpmu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzfyxyr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjvouag.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjiqzrk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdeglik.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtzeist.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbohcpz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnceeab.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbvwnni.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2clvoizxh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyostpd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmbmmsi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vaynzhsy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gusauzsu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyeucyp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyncmctz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmlsxwu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2keysnlio.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzkfrsj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztodiwvv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkldbmc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnticac.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvwhhpm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjlzmtw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cumjcxmd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxnvboy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdatnck.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xecaegvp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrugqga.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gunmbcqu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgedayd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiebyhg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxfoktq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2toyvpvkr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxcphho.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spqongtz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2smpfxkbl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcaykas.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfuezao.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfigycf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhyrmcc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmndsdh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqvzxhk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkvptkw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfwwqgb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjihsj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfigbzo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hxosnavx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaggnlf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuucjup.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2igrzllnq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaqcill.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxrvajg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2unmedymv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpzprhz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2snipwxhe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xthsonsh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yohzwazm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgzguno.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbtjzty.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtxiuxo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2susfzopx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcdgysh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zsraiqpp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qgplplwd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qouccneu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwwtazv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgtcvhh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2djipsnwo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdfgybj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jypitcid.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsufkkg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2huqvmsye.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnwjmvc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaeywza.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ujltnjgx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aexovjno.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rknrbdvt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oidfhnmq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiscxjk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaujtwp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwjojvg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nofiiulh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ibadmbfn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwstttg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ydibvjmq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xanqlfpu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jilzygek.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvjzrib.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfhkrok.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgrysrq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvegdkj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjmsspz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmjrinq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxpbgdi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhuukhb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ammvhprw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhlytxq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oukfysit.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlgahdt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gliaeecv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqnlsen.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2plddwubd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2npfjlrkg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcnlcxj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zkirevxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfwmjxj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vucgbdks.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfppznpk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2halqtznh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeovxqi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxdmgbq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbwncrp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vffanigv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hafwirgf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2imyszpmv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brgfadvm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hxninddd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrsqqrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etdywhgp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqjhvjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzvtysp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2crpenyvr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2icsfhagk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyiekyq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2advsxcst.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaldmsi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bplessef.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovikmyvp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgeujrg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iasftmeq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqlezge.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpmmkna.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdfcvcj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2puxvbtdi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsaiemi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2njamnxfn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpnzstr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rftebbqr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfctylx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pbizokjb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsizozr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuyevgx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whufomrk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nydbksww.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqtbodn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiqsnhk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcwkewb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrugztml.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pczlzgos.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ormujiqz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2atpnrndq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdkcfxz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2psktvsyu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuiljhf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsflpuy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgpsmvr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvekwcfj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwokijs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yovimgbm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoxmvgy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqceaup.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtnapbp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjoqbye.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzhpwxp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wimackli.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbbcfub.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvuvkew.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dociktzx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbhbudi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoezmcyc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgofiwm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcdfsms.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2goscprwz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvfajwq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmskfau.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlxybpc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2urkcvmhv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcbpvpx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrbvoxi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapgorba.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dylzgceq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2laegoxsv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbyvydw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgcthtv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrirwrd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbpcjqg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqdfzca.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2naylyuam.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tezzhlop.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fspbrbuv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wazycjck.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqfdblr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2leyowwyb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sjegjvsu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huwwzbfa.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbgtpyy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzdqxnb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jilvmthb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxusbvyq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2huommqmu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzubznoh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzphsikv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxvbfzm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwczewm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdbfqwh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyqqnpb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgckzwm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duuwzdhr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjiosxt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gayzybyo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrnlspk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfherfg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2elmdguux.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkrxpsk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lisursfn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2scfuizsi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwncgthe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpwweki.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvqywfv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkbtijl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxrfgpv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvozgagr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2isiiwxvr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfzhsed.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmkgwas.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxygnvza.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhybzec.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfckwhhi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsajsmc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wctobrnl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwkrkku.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tguuvuxn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oirlpuzv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnadiyw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqgzpgy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gougtrmj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjlearn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyitvlb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qpermhqc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tccisktq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dveszkvj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pokhvkfy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvcpvrn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbanzixs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjvycxd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdegnxkq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgxptrs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oifpzxwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tetdhdhg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwgxfui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzndqxfo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2klmxwesq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrrzhsp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsuraad.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ocniqevt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hewsvtcy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzhcgoc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyrqytw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjzrgoj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ildoizwz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxefidm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxqoeto.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgvvrcf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqtnoux.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2loshnkgb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lshivfns.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzmyshb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dalzwjhm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgpnzwi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxreqhi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eckjypdg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jxztraqc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oklymbom.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2heumsdpd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnlvigs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwdamzf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmdhloj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmnntjk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tudzjlqy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwwsyib.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpgbzxt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qavgyisp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtrfht.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqizoqx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxczhrbt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kelnkwjd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuijlnh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2quvzvmjz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wreroqcf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehietwkz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xccoyhon.html


<!-- 参考信息 -->