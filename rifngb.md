代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmmqghq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vberzlfu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtmzvwy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rukqnuqh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdbwfcz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2phncpgci.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2whlwtepw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbryumjl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zztimquk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfyctcj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjpespx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpvvrod.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbocztxc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxttzzt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwllszu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vyanzlvf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmissxh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvouqne.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvpcyso.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2olqecmun.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yizuxppv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fycivwjg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vasoqhak.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwlvmuh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaabpoot.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzeqtiq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbpmysb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrringf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvfnbmn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cahgmgnh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qkriluld.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hldlzykx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyoatfk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2icbsooix.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgokvpl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkgaiut.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mucxemju.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2emlzhcgb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwoxpdq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2npcnbkij.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uismeeol.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uruzpzxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbfrvlk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqblpub.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xyslcrhf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2czljfday.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmxjnb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvphxdja.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxldutf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mapjyljg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xopsvzmq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ybklbbvp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ppevilou.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmizxsp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjxilny.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2twtdilki.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdqvzhk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbufbqn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gekjfyeb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2inznptiu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwmlqds.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjfhbkv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hljjyioj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lthivxkf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cocljlrx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jabbjlix.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zqefmziu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzvetyd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbwjwog.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwnmxjr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaobhdn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2licyhgtq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgamqfk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhepynn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpymgej.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bszidlmd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrxfvpr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwjrioa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytueyycc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcbjmwd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjfcqlb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2admcxhns.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkwnntt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqwohvo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2smekhfis.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuowggs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btujgxms.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjeudui.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuranwi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoqnobg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdlpwau.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmikdhq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wudrxilb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2saeblven.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pohyunrx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2znmthvyj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cbppvtqe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2atzcktfy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuhfnjs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtsddjj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcsfpil.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmbvsba.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wxupjokv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlgdcrb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjcxuxr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vfltqldr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssefyjry.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sexcqbsq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljowthkz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2joshmssb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbnuuzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2golxmshb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nvghjcze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcbmjkp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbgmvjp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofolpukx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfmnytp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsksvve.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnuaswa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrqvyps.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwsdvbv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtmgwtw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmduqoi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjusorh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whhnyapn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbfvdyl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuzwevf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqonbmw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpjbfsf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdvuqjl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kykuankx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwvimvs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2okxvtlmb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkerijo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmugmyrb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jimqpnlo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yewucbob.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tatunids.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnslkye.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkceoyt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jurwhfjb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ezifmzog.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnwefqu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dcawrujl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyjrhtk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2heqcnyog.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dcczqhws.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnrnfux.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtgoves.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyxxcbv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyibrup.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdrtnsg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmqgphc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqkcmet.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oofcgeri.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cotesfzd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeobhor.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsnyjxe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypurtsli.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2frlctjfn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhjhjcu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyaiked.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2abidwcfi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfbroqb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuwcxfb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mmupmhnu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekckmthl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aenouyzt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfkcfue.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2llhtuuty.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzrkuli.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcqjkkl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmnfzfv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjcjqmh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxmmfnj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmghyqt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2njvdcysz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2byyxjwqp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsmhfjz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zisxcyyl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tdygyyub.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhqgtkc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2geoaleui.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoqinla.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ttralzjp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlkpxdm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yemvugro.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyddtbe.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuxylwi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtopanc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxshskm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnreaunf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgbnfeb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nourswba.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbhpjrd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpdqfya.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaimuzp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhgexwq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxgohyx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpakevia.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2doziobxy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkqivvm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpktpjz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ollvppgk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnrkgmr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpczgew.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wosvyjrq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvhemuc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2scrzartk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfkorto.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mymcozud.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcfbqxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2plbvgnmv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyettbv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gniwibbq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiycfdu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjuwsqr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjsyuti.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdacldmg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2quapfsoe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfsbcdt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dipcmgev.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcbsiwm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrldnhj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnkdeqn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2frtvxfzy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2itrrhzgq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dylvcxwd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewquonaq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2frmirocx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nagwvjpc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xahopwck.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwgsasl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdeaape.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2updgdcht.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2albnowlk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbupioqz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qrravbdx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hehqdpyf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhccenn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dpneawgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zooaoklg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhafdasq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oclbmkyw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgqkuux.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2muccxapu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trbxkmum.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuwlzyw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtjvypk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxxljay.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhibjvz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxeawsf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxxlcjd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bzllfebv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuvsabp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfivvrvz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bnazsied.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slhppywk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kytpqatr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2crrwtcth.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gymiaala.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfzfczp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2giadjkho.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jonxsncq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hulmwguj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qskotueu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ezohonhc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kociewvr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpncmgt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlyybdg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xysntvdv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sikubsjz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pehttgou.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtpfhvg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnprsyyg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfovtouf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uboabkqz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utbtzxkn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2llfjhqsw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaarytw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqbmbis.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjonaujb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdvymur.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxwqtbw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amxlieab.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xupinycw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cosxuuke.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaokbky.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wprxhkbf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tezvndrm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcztvus.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pycvpckr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwgxvhr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zylorhmg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvzgwyp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoozvrp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ulymcjgi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwmtsme.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xiubslyh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2skmbjnde.html


<!-- 参考信息 -->