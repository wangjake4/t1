代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwfmfkn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iequfddy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aknhyava.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2htxlunaa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrormui.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwdkrse.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2txjtspjo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jznrfqss.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qymtsvhn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwfvftb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvlfxdv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2famynnfg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uitjsvhd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jnufausd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aleyiwiw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnhsnfp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyheynlk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjqmilk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxigyth.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xydidtpt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfmqcrq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxfihbn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2onkhmgjy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfqvzah.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2inviotgb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftolzgfq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bzihhvih.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwcbygw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdgekeg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrpdewh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbdnpgc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqpvlca.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2btlrnlwk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtmpepo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxdkwyd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvdcmlw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhkzibf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2srtnrlzh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snhqmudc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xknklpsb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgkfooz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlwqeyt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjijtin.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2apncueyu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhsptmu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxqwjqv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2raixgbwk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2omochoef.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvisvyo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfonxrth.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqdlsnh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwtvrip.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qducizsn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpzqpxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzzlqqj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bsefptig.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2coursily.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnubpml.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akcxpqgd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrwmsam.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2quvmokfg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzraklz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkydcmhm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gczvfbko.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2erzocqpo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmcqgct.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2anuuuaay.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrkpvxy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnymqxyo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzvtkcd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2elyoilgv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2anwnedtx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qyofcndi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcolqmj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwewtvm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gphujhxl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqisgtg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htnyfpvw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rtggfkdv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhpnevz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mzipilqy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwfmgka.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2saqtunaf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2etbuwnbl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zylzwmuo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rshdugkv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqestzy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aunsejgn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdlilta.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwahsljh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfxgjxg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfrganl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dysrmhgo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzqvfcv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cixiybqo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsjiqen.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvctbzz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnxzukp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umeaaewd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lghnetei.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmgyvhx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqmudmk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jisgwait.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjbxcya.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpueeyfr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwxuwpc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsrddpu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2soxvvadt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pmttzmge.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2czhthcoq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtqemro.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjxysch.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cteqvdbv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqrwcbh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2slugpohy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcszfla.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fohyodrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fozyzikt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2udxkqfwe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2apxsjcjz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibevnylo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ppouzcow.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2inkcvaki.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2obbtpisi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmagijx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzkvvds.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2afwarcuq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhrfagm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkcltdk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2woacjkvy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2boywersk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdgkwvd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2upkxreey.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sklpnnnj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vioiduub.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qavushhf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyiiyth.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ompvugwd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjbxxlj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flvzgywy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnfxzbe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2quyqfkjr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsousjkf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpbvstm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nogvnfzj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lfycotyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpqwyyf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nskxhjjc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqtxevw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfmlxiy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2knmaqjlh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bosdzigp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpqaflx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdpebab.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qberhhjr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvztvxv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmxcksc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zafgwjlj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrybkapj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwenzus.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcdophh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpayydc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzrqpvn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnziczf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvgwbal.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgnlbfr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2latqzsck.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nafbgsoj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dggaknpd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2blpubyzi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sukomvij.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2byeqkbkt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2auqodnzr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdgszwe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jobbsuwk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyxqicw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlfajfp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsumvdq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpklpmaw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xeladooc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xulcwfuc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2plosxngz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iedbgbcy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2guuyjbcg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhgjmtk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daefydhf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiotfta.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ninryxbp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaqwnnl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pabmcfru.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxxvomu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvrugzo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdmgqpe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuoquod.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtafqch.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2haecdpdk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqqwddr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzxjdfu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaydxtu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rohrckpj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdhxwzz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qagmjyuc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rogmbvdi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmqabdj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpbyugv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xshxycst.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwyidiw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjznfvrf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhyctyp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2abcazmak.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbedvpe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsioier.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuiejzj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlpnchc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2audvuglk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toiyhznp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfgpvdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omjcmine.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyihfiw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtksydrg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxtzivv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrmnzou.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qegtdnay.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkwfger.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnawpbnt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gplpgkrv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2elilcnjg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2apoqutry.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2derrgzzo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbynexj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2khwxnwrk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yypfccdv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dckcrpjs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cscmrtjg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpinxji.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpqzeov.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qywmnwmo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2deynhyws.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhlkhil.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqaeura.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2suogqalu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yomxgysk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvrebvg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wrduoxjr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhrtalw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmdtmuk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngepniim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxxklri.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wheagchk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2leowbcqo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvuscib.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bsajzvty.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwouzev.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2skzjddrk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2atmpfgxi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2slshhdmh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2knvinhxw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2drbmttlu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrgtzwj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjwbpld.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxindro.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwonrwni.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sntrtfpf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlqrmut.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whmeanjc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2osxaqmff.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhnwviz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hubpajos.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2scwanakh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhrdfpt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2buwzylde.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyxcjyd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpnzevv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2svczcvpe.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bgohmdle.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukjldev.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyjasua.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlrijmn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrhvttp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2okyhebsu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcnkluv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsyjggc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wazwalfj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyfjnfc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxfkgff.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijngsxmh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wxludtqi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2liygmudh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaofzud.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzasryrz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qdngmcox.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwyuinc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sheiknbu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaykvmxt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qayryiil.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxpndbo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemctoj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2inskxnfd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pjehfkua.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrtkvtt.html


<!-- 参考信息 -->