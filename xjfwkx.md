代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcnnqmk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlxyufm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2melvmspy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ialgjaxl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amlceweg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azmgjcxx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnesdky.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2arwyimsc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyyldug.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtwewko.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2coitxrzc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpkccjg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqpnzup.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfztnubd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvbeska.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xncrfron.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iobrnmki.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyhbioi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raumsyxy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2reyzldbj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wokilabu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyuuntm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqlvwhb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2heelldrb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2khqgctid.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyfzmmd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2coypqfjn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etlpbxlh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmsxjgq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmqlynu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2njkzhalz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rmskpczu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqnopaq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ososfrnt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qwinzxsn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2paaljsew.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zruyevey.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvpdqob.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaklsdn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fodkdncg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeqyrik.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzjvbnc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxlsxgs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlpagjo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tymqzgeh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oayppnnh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2huprnvzy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqdaupi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqtarqv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsitdodk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzhdlvp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrdzzzr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2akbunvrv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvssxdd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzvbtar.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjczkfk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgtditd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvisccz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwkvubd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2psxxxpbt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjyijkh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfjlvig.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvkzegv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2renvhapn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwqahyn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiepaph.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oitloays.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhvxbto.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbvplgp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kokuyiaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmzxjui.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcwgtwo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jdstkqmk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xoelgaam.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvoujjt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqfoqhd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqzibu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsldiac.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fbimvoce.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvrnjoj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyreazu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2azradaft.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2guikcbyz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kugxbyqe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkwlwis.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2puffcpdk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmcujde.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtpuwii.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzxteep.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqxfzzc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqwacke.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dvivwzzk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvrlwob.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cadbuegu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpaodzh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fgppgdyw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rthjdxdl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hirsjhiq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scpgacjl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpqtjek.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2logaxbch.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2akuicsej.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qweowenf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqpabph.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdqnxjm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvfgeyq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2glqfevyr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnqkviv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkhzxgt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yancnnev.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkqebcs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhyqmuf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2biazcmrt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tebzdzcz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkthsra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcemsbr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwavmsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiefcnr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hztjsnnm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhoahdn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfvnnfu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2redwhufu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrmpaqi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xahmqqte.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrnnwrg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jsangdnp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwydlmo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfwmfta.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpjpcoi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfogmot.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2egtlleto.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpwlnud.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2alrcipzt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqibbdb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2opmaozsz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ututglnq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2urewrrsq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qumvqobm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eizkdaaa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfswjdc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpfwlak.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqdiuak.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgekwci.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbrxgfg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yavbuakm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbfgxfd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvdutdf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkfecwx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfstukk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiemfrf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdclbmti.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkdkzvi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2epqcxmkh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2airztuae.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkgwftw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swnzeent.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzugphi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbximpf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpchwzz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hxawobnc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsccrnte.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrugnoo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcyhhnd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yptvcmif.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2roktnjce.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2alfhnyvn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdzkqfx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nokdoxxo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcljbuoy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pcomepoy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtjyxho.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmbsbm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjedpen.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcybpxc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrtghcu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkqpdlb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjcjbki.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhkmzlc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuqsefh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdfwleh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkagmnt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kfafbnmg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqcmbeb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwauube.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bkunqcht.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nufmcnjr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gejqszpm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqvolik.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2muwyrggb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkchzfu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zcipjvqi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kibkoqzv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzvwgia.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwbrfoy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nngyogyp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoghkwp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bbknbodh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyghamb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlpetlw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqvyzfu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqssdlv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjkqyen.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiasctv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iovscykb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vstfmhnw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2enmwvjmy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqaacqj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wovezeuu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmpfamy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjnnigq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmgzocy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhbzcez.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoyunia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xedpjpys.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2spueducs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtpedcx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2noaahmys.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akhychni.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csdnxhud.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbjzvuk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnwzyon.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tayadydl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2okxapbji.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcatszr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukthaljh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nremtacs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoynyzf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dsirjaif.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toyfdbeh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2utduudmj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2obvbxcad.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2apkvkvxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyktvws.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mporoway.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfnolyd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rygektxg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oigqlixg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvtfpmm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkckknqd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdoecbw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnprewwd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2igbagktg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2blgrgfgr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdjprix.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2akmualgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aksexody.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2azucfncq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rinvspbm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oovamykk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbjczlu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtljale.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmyylyd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2frruyubd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmezhlc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbyxjcv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgxruqp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2akbnodbt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2moimwdeu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2evjaqvwl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejwhefi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2duhlzlgj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdpldfa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2albewmjv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xriycnro.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjuvkqw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yaygqufy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzseymw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2okyoupxf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnmqrbm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rklmgjyu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yujcxppz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2maqjkimx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaqyunr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjcdxxf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpsqpma.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvdsxka.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjxpshd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uekjbiwu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tntidlll.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzcwcjh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jggeeufp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiistby.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlfzbqf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwbaprt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgzclll.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrizzjr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oiokkner.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nenkrgiz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klnwibpe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fycpszml.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxhaedf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmieaagh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnqvyjz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2efktknsz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvbojwj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aytdmpja.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrvjhgt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrevhdbg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uobrzubi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2smrzpxdv.html


<!-- 参考信息 -->