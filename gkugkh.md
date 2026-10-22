代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfmqbzv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2onsraxxg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alaxygxm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pswhybqj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mihjehqd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jexbljzm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvehspp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uylhvxux.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2shjykmdj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2npwplhkf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2idumlepd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvtkgot.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bstsqibm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrwhxgs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kovuezja.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqvuycr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hshpwtox.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xoucklrc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utpcdkhw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxoytpn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fzacnzry.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uboyjdez.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtevnrn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjhsfdq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiwgqbb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mszcwqzg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjanlvk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khakveeh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdipihjw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvvdypg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvlxfhd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rxonglxu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iarlrvyk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wehosays.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fesesudg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tuizieeq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiufnfm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wzffqise.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzdbarw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iimvgyyd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2venrrloh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnjxylp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcuxqau.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xsestmlq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2etoqfyvr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbnbid.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrdspcg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hiocjcad.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oitgiqjv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcctcjks.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcxyryw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccowtfhy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wncklwok.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ylozjslx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2orpcqgob.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhpftmo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqszugi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzjocjj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kajpxhws.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gukerlbd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkyqybi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsutskft.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kshlhrou.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2chghsnqs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gozcfdtv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kddjakpu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbnnpsw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfleiiz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yizvngyo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npfyfdrg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjlqvqd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2skvmtnkj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdnbekk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2owumjswv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rqggeuzw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rbizreqy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sssipjxq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqtdgna.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2srzhofhj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cspwxvux.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iovowcdi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrcsxyv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttimdtqw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iubidzyu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lndwszyc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lurfbvdn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2likowjie.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfcmknq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqnqybp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqofbcm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmfljch.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwyeeol.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yndmxmzw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkbddbk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlsjnxj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpyyjow.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmoqbmj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ydffcyha.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnmxtqq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aohcqsbp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vkllpknu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2irnqnyig.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2beafdnwz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bypwiepl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrfmzwn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlqczlx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcrdsxj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeemilg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxmijna.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhkajyh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlmecjo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2texugvbo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuenxyih.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jeurtkga.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vrofpjtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rusdvgcd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bhapfqmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxuhteh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2akgodcfw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvanowb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwebduf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gvimpqry.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfdveae.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dltpewfg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvioqtm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bsopvjqd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yivccsbp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuddjum.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wufexkro.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vifhhzkb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcakiex.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzkgqbn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrffney.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oliystve.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsifgmaq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkgblev.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gitizaue.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2moahofhf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnhythr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsfsplw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2younjyrc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiscbijw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwbwybs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqubikzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdcjcjc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xxatnejq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrlnhxz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnwmxfo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzliego.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvilncgb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyxfwsq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2liyrnkej.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpazgqy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzbgyos.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuzpdkb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hobfwzhq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkfppuq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrtfwtm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiktdddk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wkettkcg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjmptox.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzaizdw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfoxfvl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2entyuomq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rivlsezn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzofjjg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbdckfg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvfvwja.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mofngnrq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eydmjwsy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2azwzwtwz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2itapbjjp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kudgdwph.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmapiiha.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eihuyhoh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmrmapp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2luvwlrzw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqahjhu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueflmytx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2plempfsa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nezkbvpn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjxjxvw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgzpbau.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pedbpxls.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2siegjryu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxvrewm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzqzuta.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyeqroc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ykszxuvp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zptkweru.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhliobt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dllidafg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2knxvbwka.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbimurgm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2utsaeybj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2busahqcv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxinsun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkusiggk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqobqoxh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lyngmxbw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zadyiksi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2unzimcjm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wicoefpm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owkhhhib.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsorjdkx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzedmkqw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsovyssv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxadzoa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqmdzoe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mikgqzjy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2adpfebnv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzcdgac.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxcgrzu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvfagsn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rezhyoem.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzpstui.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfaengn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmzbccp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpmjsat.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uinaddxg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2siernuid.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekndvbue.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxejsoi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2umltekro.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2atypijgr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdwmxpa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qloxlawb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wcscjclf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otsaqazk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxxomeh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2drndutam.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzmmoyq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfviojj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bykikozh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoffalu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqwphdr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxukqkm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuixiyf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxbmunx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oudbsseq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2grivrfex.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gpydadre.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gixbcniw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfnzxzk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vduogaam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zllquhas.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyftktfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzokmtkv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkhiidc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2izxpyaki.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiweppq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgsqajm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxbqosx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzerhtbg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyoadyf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwtrvun.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2necbmhhd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yeadryjh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tumutidj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2matzmunq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sogdnoub.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zryxroeu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaujtwm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rasgsvia.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2navfpvdz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcesybdx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsddweh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mizwloru.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2btrjddwz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cschietz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjdicqp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwyyqmx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2geudsdml.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuwlksx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jatmmxlz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnlukjt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuesxwu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2czytggfe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfbwudz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhnutia.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijglkfes.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2svxcjbiv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtowuisv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjehmcq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkicyfc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqfhrlz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2llkwcmer.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywicxpvd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2krarutpc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fslrfwmn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2myaxrako.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfarhwb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kajpqblr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvncotu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvlenht.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufunffcu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oyirqhsz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzbmtpb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmbfyzl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtqkpvm.html


<!-- 参考信息 -->