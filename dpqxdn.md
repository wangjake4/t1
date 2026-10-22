代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkihgvw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwbazbf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sitttmqw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkwtjnh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awvnfmef.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzwtojm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcrvtnj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zijcncoi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2myggpocf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2feiolesb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyrxgdl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2liinoyev.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkgqunt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyyesvy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmthnvtt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnpvczm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hogzjlpc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eriizzjp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vczjvrzb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aailammj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeekfea.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrovugx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmwpjwl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nydkjqxk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbttsetf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nczfqnrb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhzqods.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uniljpob.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rpajwgfh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ovifedmz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2veeeukrp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2elyqgblp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqfdmlc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bqapclvf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjaqael.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrucmxer.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tibalyef.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jonkocpr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pdarqixv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbsttqu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmtjyta.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2usyevqch.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ntufaprh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaomnwi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtaomft.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvgcfkf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeilhqw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slvqusrz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2twkosvmh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mcydkyyj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqysfyz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrouicl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrympgg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qjimumxi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2llutgyhy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gifvgwvt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpnnqip.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zopmbvwo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkvmyrc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvryazal.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfzzdar.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rexizaaw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lunfxnzb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvpvwdg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2odroynvr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2znwzkjue.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxbteaf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2htoxjvwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2skbxmutu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgqrsca.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2boynqqxn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfuuopf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeungss.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2grxwzgwi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbjsxbh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qcubfumj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ijccpfzp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omiubkzu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2updejteg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cazmgymj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjijilp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsdyxuh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswzikj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dussvqwc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2crpzipgv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epqkyyvq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtwrrnd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cruqemfw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zfesdlqk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xferdnns.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aclwirnz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytevztys.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2duwkaezh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwvsngp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2suboydfg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfrtzsr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2emfncxto.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbdxppm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmsotpf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2atjnumfg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnzknb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcltlbl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cownjomc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2blmgzafw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbxltsr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2prczfpyz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhwhuit.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzbciqr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvgdajg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lzswllta.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjlszup.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iabohmut.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2evfxvofg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fubbbvby.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ghduldmj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoxokoq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoxmajn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kidtjptl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkzdgfr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2imjcfxjb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ricyraox.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2drvtclpk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvsuykc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2radzzkew.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyizpqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pabvrxdu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asxnofye.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyqegxz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjxhinp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vrursfpm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaswxyxt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lthmqdlc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxppkjz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lobqjvbp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmduwyh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iamhmeku.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xazistga.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2puacyxpb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjxejqy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoegblv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2crojkcuj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2izbcnztg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2icpncueg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfkjrbf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsrjvuz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwakwth.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtugqwf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtourztt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpxyjot.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2smhtktek.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjkvjyh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbumniiz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjavfkuw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjrazae.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbprnbs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sizycwsj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pesrozmz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhetpkef.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2opsxjkti.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuyrnhx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpmwwhu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sirvebzo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dknhtwer.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2psyydlnm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxogzny.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiislfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkouyezq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqggjtw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrhyxob.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tebjvmia.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2janbvdxc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiovemx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2itwptbaw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzubivdl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrgsyed.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuneeeu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xguabutb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfmnizd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcrkdth.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2usjwsgdp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdmuygr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2glrgqsiy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxcxugz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lniqyrpa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjriqzal.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwflqer.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpszbsj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvojbjz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2umfujqiv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhitwdk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqadtgz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxgjdub.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vippcsmu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmzdtno.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdqyxuh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2olmtyiqq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2onbfdodk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaupren.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2diqvfgrw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpkmfdw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jnixbomx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmjixwn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdwaiui.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvhzcuu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmpvkat.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgikwknm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gchmbxbu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ltulxwqo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgwgxmi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrsohnv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wnslsrpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qluruxfz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaurmvr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfubyhy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsluopgf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeocfpm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ivooepbe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzmlace.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xyczaipu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znfdtcqp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2phbknitq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2guojbdfy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pujrxqfd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izupiywp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iszkcjcj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmheemj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knwxjjcq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcyngsu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlwimya.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjckavg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmvwndw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhyesuk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oabnezkj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhxforn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjrrcdg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jjworzcc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasncszn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxlkajl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjizqixs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2utpxoshw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpyonn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnnemnm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwnroic.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjqsgva.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsixemu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlxyhrf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cujiaxbh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqzgoha.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlauani.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgspcvf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dktouemz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfzvgai.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqcxwmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwtonqb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2erikgfjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smxcmkvv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhgcyma.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvjwxmo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fesrxebe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ayofehlg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2efcghlqq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2psctujnc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lprizfsd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvnfiat.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqaqgcm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmpfcby.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2duyzzrbr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkboimla.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lesfsfiw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiokjgh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ddberzvh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2muiwlqbh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeddblx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiiwbkw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lczlgisc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2raygafvs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lddblsjh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2clofmeui.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjimypx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqobvpfv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrtldpu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njkkarwr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sffvvlcc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrctwoe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mqklogpl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dguiaeaa.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzcxwtm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdzgwdj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsnkcdq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2srtufwou.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dilljist.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyimsxz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkrjppo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oobuwdvy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvegkes.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkebkev.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wkplmbmw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlcwuao.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tonvbqmo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdkhzxl.html


<!-- 参考信息 -->