代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkgqmee.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gucmcwen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfgrqoa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2swvfdzog.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbbqizd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsjqbsx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwzjqyf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuokvqd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbshytgj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkcqtnm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnofjvd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmmelia.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qrldmmhz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhptkja.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2crfizhid.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2symwmpvs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkilbogg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtcpfwi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpklfuct.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eptiphqs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wgitqmbl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzgfyei.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dylmdoiz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrremb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkfadej.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lscfflic.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dlohtpvj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyealqne.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtvayzb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeyogiz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmwsxwm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jorerwmf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmtknqy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwyotsu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqfrvjm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2okwvbqur.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsopqyxs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fugqoezv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcyzans.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okzvdaca.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiedgle.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2feycbnao.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2elwtvhpf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcllagy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gawuspwb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzgmuih.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sahtlbst.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2befbqcag.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2expmzfui.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxseunc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aomuaedn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqbrkhg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuldhdt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aigtungm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pktkbvgm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2usngqgrs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsumgpl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fukxnufd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlmmcqh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgeowpo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbbjwrz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtivguej.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxibedp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcdhgya.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2efyeevec.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjylhpe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxentze.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2atqhnbgd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkyoowf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stwtjcem.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxpggpt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcortwk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uqroaxft.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbqvrxy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrduzpg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjsrnst.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2riglufnx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txrpscid.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvdwrl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tckrecvj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cvboejut.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfxnrjd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqjlniz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ywquqhsa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2njnmteld.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gycrsqbg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nymlsqwb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmxebpl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaosnub.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvchuqzm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjapnnj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbniahj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oljwkfyy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkglnti.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqrfjlo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2swlytsad.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsmtqks.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdhuojw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvrtxrs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhusewm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2egarlrdm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xoriwdel.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lumalrua.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmemnxar.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlojsdf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2folfsfjq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pjktjdjt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fphacdfj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2omchkqff.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2murcpgxk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnysrdgn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2noimgllf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xysrvbkm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jpudqrij.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iihgdeyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzqnkwe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpqvupx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwcftph.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqlywey.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgplumi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxoqnwe.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aighlkgt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvqtoun.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fypzkhva.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpbbkih.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxzujpj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugciianq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtogcou.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fucoyybr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbklgfn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoiwyjg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gudcmnil.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2llqljxyn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ujozhduz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbzvfbn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2atbrzykh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kctvtikr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2stllwlpz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tumwmrgr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wentmilk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ervfxsbp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlcipjo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwqbwov.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxbenrw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbjxwqk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fffbsrom.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtzunfg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xnohlzcu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyqvqdk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfwauwk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdumbksk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkeufsz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcouimls.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uupmjtle.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kswqoocj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyrlknv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsugqapv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gndbuslr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvfttzv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rfodspbv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrwhbwb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qauykcja.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmlbwml.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhftsub.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpkhtdo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnymjkr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdngpckj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2prkdxfah.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbokozc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnipfdd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgqcmpw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuroizy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsghgbb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jozrgqou.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbjtrqc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2phuqanga.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfirmiij.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyexjthk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2crarznao.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jibomqbs.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkiwbig.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjfplns.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpnrule.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wadscxgf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yffcxkrn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wburwlao.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2flrjzpud.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgzvlxs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjjkzsq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tszvpire.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqvqyfm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2camhtcwd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfnzibs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmloqesa.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zpswozod.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gljngbgg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2asubdkbg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2esvidfwk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tapogsyr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqcemhk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xufbbttf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmxhchm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbbwpxn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gljhnhfz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbodeuoj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhczuol.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbltaiq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fckyyyto.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzzooej.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2khyfzetn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvwayov.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpavbhk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yulzgwyu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwxiemz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2omqprbld.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dymnuxfg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nonoufbq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqizplpb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlsntlo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2onkbybng.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gokyphgp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2povitdhb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsclriz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgoxryp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrmabke.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2epeqfigz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oubavuuf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2krxtudfy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmquzql.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2doyfjopo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqbmtzp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aipmxscl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyibwaf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2regjpxvm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2khimeexd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ogobltob.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbduoto.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocssgbyj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cibnbooa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hcytjksl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfmthef.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aejzchxu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2udypqqti.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fpncawzv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcspmpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcrrzqg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2phatvqvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mputravx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdftwug.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaedjhvw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyngpmhq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwgzrcx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2teallrji.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yutvuvgv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zggdfvdh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nvseyzra.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2crrylgyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiimnir.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2odpvlemj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyehjtg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaogcyf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2akgrzcmn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqqarrf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhywlylm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujshefzz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2azgbqcci.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjeicas.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2domlffel.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmuazaz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2abnpjmbi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zisqqmzx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bebhxavn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiscaia.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldknkeqi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtnmfgv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2grapjzxj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2arhomiou.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdmyqms.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hniasdxr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eghakuqj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuqzhzg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afoaayeg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pguignwq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqcbffs.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jogscpth.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kizlctqg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jozriqim.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtbjfdk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqwqhvt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzrgdna.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvmabrf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrkeawe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyozgini.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrioibc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2redyjoru.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdflejco.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfhiumk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhbzxjf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wlknjldn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zblfiywm.html


<!-- 参考信息 -->