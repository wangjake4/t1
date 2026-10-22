代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lawnifgn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhqrgvl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjapfqjb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqkbtlb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxlbjhg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2whczcujh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdugevxz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atkypaqz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvktldi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvriwvsg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlwljcv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxfhepu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qltnmdyh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoqdfti.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmksmpd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzllkun.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trsipvgs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdihbnd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nviylscd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jhixeppz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bixkptau.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fubtgnvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tzovspcs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clrldbvf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rimzaszc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocleeugm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2madybbng.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pjapouab.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chrtufub.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2klmqqtsg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhsoyin.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dunvylaq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2axzdudrs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzibphq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvlfbaq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lzebtygu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wattdsie.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lcygbzbq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvanati.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2forqbcbr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomgxrac.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvpczzb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2roxdxpdl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpgjdac.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdthtep.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnphhis.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bvznfavu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2trqqcnyd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2abhvwpaf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aojixkrr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrxlggx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdruwpdn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wghxijpg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuhtygi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fllnwykp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdwivsq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lksptfay.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyvtjvn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkjaofa.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzdlext.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcpmeji.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiflyyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmantnwc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2conujsly.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsandxr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gamvjvld.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyabcqan.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eseotkea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mrviqizw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzgkvbj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeeimzx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lhawcswa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvncsyn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2teiuadpu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smybjqgy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wctgnpme.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlhlbup.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfpxwzt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tbayjdoa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kbicewjq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2furxmoyj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvodkrej.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gzayyvey.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuwrgjt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dbedqvop.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbwnlwr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2orwbsqnt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2odmmolfl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcedefi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sydmrtla.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dymbvbel.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrrjxal.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeanady.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrsxcki.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vclvgzvc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2apjeiefh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gjphgcsf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfraxiq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsvlnaz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwlpjxj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ynorhbsu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jerrchqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynorlxes.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eosqkiyw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vklblkap.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbygfpb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxkykfz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jkauoozx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvymict.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xpujwexa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbcksvg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fsctqnsl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxjmenx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nmntbwod.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbhlkun.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wizkabjn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoturyrx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pabaovrw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrgjzsp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzcwobk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vcafmkas.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ludkxlcy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2revbqoad.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlgcjxw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2difousfx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jexxzpkm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kvshuctt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xleijqrh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ereipgjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvjyfwe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uevlmnnp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwmbtwo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fduragly.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fujgabgt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcptzftv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2urppvpzt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwamxpl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcnkjrc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2crexswwp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jssxfjqz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiikkigl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbcoued.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lypdeetc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbpudcp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhjwzyy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eimgciuz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pizvlskk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbmqxbj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xtifbckp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tfirruzv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsigzwe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnfmahe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhefannu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fobtirvm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvihhgaj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbkrqbw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgwcxzb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2smkuoevv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eadcenji.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oacqvett.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2izoileil.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lglpkguu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pljfjhgd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjvndgh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcphwwp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcchqunj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzcfxwr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eekrobaa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgaswhd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwfjzos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxmllwm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zztmhgzz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqlmqcd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tcafddry.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2leghumbh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jxowdfkb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgflpexy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaaynjm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvvqbxf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrvlxgx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpkmcgf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lizchfof.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvjkpba.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rcknlhvq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjceinkr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpwswuw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtropif.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxxoarz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxokxna.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vizhzkle.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2onheukvf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuomeeu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jzctlpxs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrrsgdy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzltwfa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ildoalfz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbylibc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbrxvda.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqbjkqz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgooxxry.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyhuepp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2frgrzpzb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcfplrl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzelnlyz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcvwhcy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwerzaz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2adgdfdip.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnelbjq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiwuydw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2amyggdvz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hddmiisc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfksqwm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjolohth.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2saxahlro.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdvnprx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhklgqia.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qssrdkfa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2srhyccin.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqjtlgf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2peixddng.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjxasds.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2atosoche.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cniffuqy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxlootl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwpvhzo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzckdhds.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbdjily.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uppxjowl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2inhoxyic.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awvndrat.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpotqeu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnnxtil.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcalibpn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgapgem.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yuufkdij.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxcvquc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mouhypbe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zghexxjk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjxdqge.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrtleii.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdwwiri.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wgylsoqp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjxzgnp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lfghtzar.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofvdxpv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvkdbzc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2datazqlc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgcovex.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hasurkib.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpktsscm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmvhabu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjqnujw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfanoyl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmvkxhw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lscncdjd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjgvkpj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qlysuuqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxexazlz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2edtfrqgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnndvxck.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jobqgrmx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcadzpp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qihbfucz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2btwmjcwa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kklizxjj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsjvtix.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2irduwfgt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cylapdzf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ueumvgmz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tzytpmnd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xobgxmap.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyqfyvd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zoansuyw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbinnsyt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mknhuimi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbowkuf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzpcwek.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmbanbt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2piwxaqum.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoiiuwp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2novhwpeb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfvsmsq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyrxouo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2geltdcsq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cejeyiqo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnypfua.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2homgnpya.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtwblft.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fawoetno.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrzbeqz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwqkvgq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkbnucb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtkzpco.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2srjubkxk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpoglzj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmccayh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyfbayi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2twnpqfmo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2acskmtte.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqurlby.html


<!-- 参考信息 -->