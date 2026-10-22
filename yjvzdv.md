代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfklmpwl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxkrwkh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiogqrc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szerzciy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kiarzdhl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oasblkkb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhifzily.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhlvwhr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blqbavyv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdxkgvm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqxkbtb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfamutt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2urejcrqf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lvocosex.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbhdmeq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqvzsev.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mberkvhk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aguknlrt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmcvjis.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kucgfubg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drlesptx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfpgpwg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utsxiqny.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmppsrv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwkwpbg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fudqgppa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmkmqku.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2offzpfgu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcwvrxp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2crkpugvn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdueddp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfheigx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlutzsv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uutkkusw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbushxq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lszruojs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxkulxc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyrqwld.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2txwiofxy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fejvfxlo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgymbsw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrzkgvu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aejksmbs.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eumsujjw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2trrvpfvk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2enkbklzx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqzlyed.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nynwsscq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tehksikp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ulunorry.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwtciwm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2undyjmgv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2leqhjqko.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2guhwfgxn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwumhun.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfhvzdn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnapxxy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uymarfjh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmahmux.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2znhntrad.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jauwntnc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2imvhilyu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umlgfgpd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqfkdoy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2flehlsbn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyobpue.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkirgnzf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbprqds.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkqiycw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkhpxzo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzcddmx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxkkrni.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuzytyv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpltpky.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgvwtlx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrubrnk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeiwwxk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hhefztls.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wahirfej.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqiaqit.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2piwfgorf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoyxxwa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpzgxko.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcypryj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uejcifzd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqzesjq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zslkzqca.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2alpisgtv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2euxrwatj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytghyjok.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxgqfjf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dadmaunn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jksdvmou.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeykwmv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqfikhw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2stvfacci.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmunwzu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iubyopso.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2iugpsphv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jihtjsvx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtukyej.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ybovwlma.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mduqkrmj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2txfixjrj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdhkhyi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tbswbztq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbqtwqv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeswdjm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2plzzxsyt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaxtqbt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oscdjrig.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2votpyafj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnsxjwr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzuauqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqmkiuk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjzkmda.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgmgqmq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqljcqr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhcihcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2athbgkhc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzemwrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrjzpke.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjlfbjg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oaipkuky.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdnvlxd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pvggbekp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nedephtz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdfidsj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajphsoby.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwltfbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2chlerhts.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeoxndd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfbkpec.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tllqufqp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2msdgkuco.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxaoqom.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyxtrek.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoectvn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yedpnynu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2krpgdhpi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkgfuid.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ivontqhi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mltgspsg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbntvfss.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rurzmfmz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cweevrpd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2opylgqeq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkkmdlx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfclhrrr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pguodwut.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgqmfgk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfoyqst.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjbjrng.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnduthbc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2txxekzwp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpbayft.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkmdvap.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rffcytvs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgxubar.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sliebipq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcixwxco.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfnongw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oudeolad.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiozefg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2htbsysgg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scsvhtdz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hczzqfft.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiipaky.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsokjfkj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeqglqe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2riyfnkus.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnzwfpw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzkrajd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbtfthe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyumtdxo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rvftltmn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihjotzr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcphuzuy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hegmeoms.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgugtoln.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlstjxn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyuajak.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdeddwb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwoohxv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2relojhjf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2omiftpiz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuziave.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uakirizo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbytomd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkucnwu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoiurol.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eumkzyox.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyblqup.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2geazmclp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2utmfhkzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbqaxwx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wazqnjsj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnjdazm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzqkagb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usbexmdy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ludypgky.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaphtto.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uellgwav.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2inafawvg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bygsdutx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmkurqs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yncowdqk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xujwvdpw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mztqzhft.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrkctpn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uovaasot.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2znffuqol.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhbcwiu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbawibi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtqlmzz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjtfahx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yraiszfi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nitzjxqa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2aconzhgt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phvcepjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njyklqwh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xupgmjxc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmumdwx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2przaungj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcxjqnr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klhggebj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kegflroq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqfkchp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uczvuqvp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2edwqrynh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyghyfb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aatavmim.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqlqlhw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuruihi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwszvgt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2koxusrje.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mehpqgjg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2btuzpbaj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhmwdzb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlzvtie.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwmkhbz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsltsoaw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucozwfqe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfiqjco.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiagttk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2prtocsdg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqremgi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yewrllxd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdtfsdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nglemakp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2phxqfskz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaunnpx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkvpeve.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdejubm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkgpedn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdeuwsk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ugknaedg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvhhyde.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgpzvsz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyfuxfb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxjtgzz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2otdurqmh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qviyxfba.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwpvefy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpklzxo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cujjkpcx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2avkuzjuj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cguhuxys.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plqmubgn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoklhmr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jolbttfh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ascqmifl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbmidtp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmleffkk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2amzdmkwe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iauuswtm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjqkpbp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odnwsdoh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjlzhne.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfsiiys.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2inlcryca.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbonpmx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvynpgq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrmnxoo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrowklao.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pnflraju.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tccqfmsq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqxolpd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdzyoge.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzsofzm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dznkwfla.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tamztaah.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2etqnqvvi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lodjvzer.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhfllwf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ysddcooc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edhdvkhx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomgbdu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjubzhv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrksrxo.html


<!-- 参考信息 -->