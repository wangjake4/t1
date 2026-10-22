代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcshalns.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvobosjb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbnizvu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jfarlott.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxeyuwe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmjefyc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyipqhr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frohvplx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lymmyocu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsaraej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsznzpfo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrkgejb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcfupai.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eomjuwif.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qycxlarn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2swlugiiq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkzdqid.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2htnlgwgi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrtrlhh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyxahrl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2awwwnocm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfadzud.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qtublxfu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkysgztb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nckjeegg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2suvcbemk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyhhtib.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvkxsmt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfwgsjp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhlcsrn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2glnxhigx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spgjvowc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kizlqvgp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlgozee.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhqqyhy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymshvdnz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkbsvhw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2labeebhk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2idfipjmi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2azlooqao.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2glszrklk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qneabfpc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdonpjp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bktgqpey.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgjnvhx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lyefwsma.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icmskyke.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hparfeoe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2apzddmcc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uchuqunc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xingfxtu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2enkpvqkj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fwynbqmd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezexoaco.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kklxfgrn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2owwdcrwq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bpronlmg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpgiefv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krhlmqyc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uaftgapu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2symcqzrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhakemr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2izlqxhln.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvcpqxl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2swtdruxh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhnslmw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2regpbref.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iaowlqly.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfdzlpc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvptuhwk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2roqrpppu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkiuewi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwppfdq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hamkmpxz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2noxusvob.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtmlhta.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ubquclmd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwpcvno.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgjrgsw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsinfbf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2purdatyi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjornfh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlxlnvi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2budoybpg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cohkzaab.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtzicrl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyadwjq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpcvwap.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mcftmnwj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdlvoco.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sqigufsy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2unsmklnr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vahxfsso.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2auenouum.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmwykji.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cznrhsfm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2smlxivgh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hwipvkew.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyiklfb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtsamlx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfajxalj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkijupct.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjqjrkk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pprelzqs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxcflty.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2othtkrda.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwcfkqu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhnofda.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svsezcmg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2scsouxrq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmgmdtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2durqgrzc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2guibjunf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sekskwqq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbkciit.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2taiymejh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzgycdw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlylimn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpnnjto.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgbzqpz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2syezvuyp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtenwwa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kczdqbeh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgeumer.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfexqog.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfbdoji.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2boudyfcr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvxztib.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dahrwmam.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgwtxjy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xivuttkl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjjhyfe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqmvnbm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvyqoyo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvtydjv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uomichun.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tarxcvyp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hforotnr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2galgvgqj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egipjejf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjlfnqg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxqfbha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2khfjvsdc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjfxzwi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhncyyy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxfwkwc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhigfeu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfeufrr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phskdngh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvygtjxe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgqldsy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bffjwrvs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoboqee.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oknrmxea.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxlvihk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgmehpp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwrxmyi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2anwgyaav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvekmlr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqyqamb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeylver.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfceergd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaumswz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xditplxi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2izhkrlbq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qtogovoe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2siafmysu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgunlyu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrgvsox.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2akkwixwl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxacpvr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dycqigfn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2akgywhsv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utjwawxc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2edtzessz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdwuybf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rpumojzn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuykfqn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnwxjuk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uouafdqp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2glcqamux.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgapapl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vojkfyiv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xittczhj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxilirq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2efmdmmek.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxugtrr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqbycfj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wwffkrac.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsthapy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrgwsbf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhbzmna.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfucibw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vindabwx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqrxdbf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2opzjigye.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvfysjs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcmuazg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfxotit.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhqgju.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjnemjp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdyzwh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcunjojy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkofkxlb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gevkijse.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmqbhob.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uetyonoa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdjuogl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2haeetgjv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hitzxwzc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2anzivodx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuzayjh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbbpwfc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkwjvyu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vltcdmgv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsbvnuf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2upycgdte.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2waofymgd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cofhhqjh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhopxgv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmghijt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fugezbgm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpxahzu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnkfdry.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaqckol.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2juawbigj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbbynzo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbgzpqv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivobmrgw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfizzum.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aidcxvxh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhwjrze.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shyhcrdv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2odefptkr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqehqmes.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2txfihsmt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2euhggyqx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsuvzwx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbpdbhu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yesjncph.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmhtyvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzumhrma.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzxcsjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjpxdwd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmshyeo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbzafoo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcszarb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwbxrgr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gulgpigz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpittbpz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvqnoqg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvfeyen.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsrmppe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wktqzvsq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gbopeeyz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqbcmkb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tntnxest.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgadmicx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pltelaem.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmirykbg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjclpelq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2llhmvkuq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aarvwbod.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iekxzagl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbrmzcn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2emweggtt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yypodzxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdrmydb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2swcbaxhb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwxnpre.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqdcwzs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjniuxgi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2geyhkyjz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwlqifn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzyaggc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2luchnyks.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2efafzqlv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnwplcx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxufrawt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iizgvegh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uzctkbgs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfjhglz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvrbvvu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2buybmyrp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rellfyiy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgxlnbd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2epihpirx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyvbciv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grzrjekc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbxgcjb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjxaryi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskvxpum.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwxejax.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmjpvrb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2scvnymxf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ankicnsz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2isvxjzsj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxxrzyy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dphvrirj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hglfbvqp.html


<!-- 参考信息 -->