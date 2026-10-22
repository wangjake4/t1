代发 wailian999

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gt2odesplzt.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gt2nopsoxfx.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gt2meplbdmj.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2jfalqpxq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gt2ytxnszna.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2vtuwapmj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2tbveahze.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gt2wexubpvy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gt2dpfnhcjm.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gt2hzdmfrri.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gt2ikstbwsg.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gt2ajclqcxo.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2ofssnrtu.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gt2zthxjzhy.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gt2ntcjpsly.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2oahvdyjp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gt2qluxmipm.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gt2hejmjjzf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gt2coyilhav.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2hfpsaesi.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2lywpaevw.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gt2jrhiigvs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gt2cjlumnvr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gt2czestprd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gt2nrerbphr.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gt2jnyfvxmt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2dslouxwr.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gt2iufdnntv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2tikxlwnz.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpdllvel.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gt2hpgkuweu.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gt2flwahopc.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2lkqevwcx.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gt2lmenlbtl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gt2trksnfmv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2ycnnlham.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2kuodehii.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gt2cyumghed.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gt2bgmefztp.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gt2owspqiej.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2inteyptw.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2jslcdaqq.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gt2lkrkmllm.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtbcbhyp.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gt2zknqtybm.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gt2dmvmbpfb.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gt2xeejxhnn.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gt2pdgekmis.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2uhvjbsnu.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkvsroqq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2xcuaqmjp.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gt2devcrbnn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2mtfrkwpd.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gt2msobvxnm.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2ohdgaytj.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gt2lnvisllw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gt2hqqyvrwi.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gt2xelsutgv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2uerafzlw.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gt2btexbkwv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gt2uqcysojp.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gt2xliajwer.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gt2npzqyqna.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gt2czfmfsgs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gt2bbgtkcti.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gt2yfowzqhx.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gt2ekogqiin.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gt2kqczjlwx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgiumzzw.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzfnkrqo.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gt2hpozqvng.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2kitybqah.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmtsbuhm.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2xkqegcux.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2uezmwieg.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gt2pfqlqybl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gt2jnfywioi.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2lnrmhfqa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gt2gyryoqoc.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gt2fgdqbpqj.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gt2cnndrzsu.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2xqeqsaba.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gt2yqkmyfec.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gt2ngyjndsl.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gt2tcdrkhvt.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2wexpgxbm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzivlqqf.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gt2zdybdyym.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gt2nzjqygmt.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gt2aivfiyub.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gt2xdayjmzc.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gt2zviunbse.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gt2fyhehzpt.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gt2hotnyocl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gt2rwutsdqk.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2mtmtskhc.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gt2ebmvuwnc.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gt2ibcenkyy.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gt2lwkcregk.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2tlitbdfj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gt2undluolo.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gt2qstfqzpi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gt2ttfyomqb.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gt2ytkoixyp.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2szexwpii.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2ygzujbdu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gt2easkoqct.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2petgpjtt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2ppwrbtwk.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2xlacllmf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2ivknyrzk.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gt2kyijystu.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gt2icddpvsp.html

[R78] 交互式菜单
来源：http://dali.9152youxi.cn/Article/details/gt2qsalvsuk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gt2fuwgdvai.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2spovaxcc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gt2ocnmsrvr.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gt2uyhyfclf.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gt2vnxhwavh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lwogdmys.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2sysbzezb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ipjuxlit.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2lfashfvr.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gt2snmanufw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gt2hlhavcri.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gt2zkikqzmh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gt2klyxspdj.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2tpipolrm.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2makddkow.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gt2okwwurjn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gt2bqhxlzmg.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2dmtvswgj.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odaclogl.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2oemslkgp.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2tjswglnt.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gt2qrobsarq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2bevjlbbt.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2lnoyvkng.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sapzdlru.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2adhxmqkv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2vorafmbt.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2lvbuuxhq.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2ljllmibt.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2sdwydtsx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gt2cvhtmqvp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcfvqxub.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2rhahuasl.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2maxxopxj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2upnsnxng.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gt2nkdbwroz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2ruvpoxnd.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmokeszx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gt2spcdngol.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2zhtmyich.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gt2pedxscyb.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gt2ythquinq.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gt2xjbnhaxh.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wqumieto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gt2byfqzrcw.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2eidyiqec.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gt2fpodpwbx.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2uuuybkvq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2meuolccp.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gt2wuvfrroq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2boublrzl.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2rzvrbtmu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gt2owvhlqia.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2trbknaaj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gt2vzkpoqvm.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2vybvloyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhpdlibq.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2adrrsxgq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2jkrqtdqp.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2kojezldi.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gt2hnwjbgie.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gt2pcgabnwg.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2lzvsmxfb.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gt2hilgtxop.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2afxwbtqh.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gt2eqgzuukc.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gt2jzypiyir.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2loewrfkx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhklikrx.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gt2ernyfdcn.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gt2qytzhnnl.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gt2pcbiuvwn.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gt2prenstyr.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jaifyeef.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gt2jmrhiykc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2zkbjavop.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2nikyuvol.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gt2bgrudcnf.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gt2kdynnmcc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gt2hajgudnx.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gt2wmdifoof.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gt2lvuipijq.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gt2rpyztkvv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2bpzkygnr.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gt2owgjlren.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2imjvsjty.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqzseqlj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gt2zaawaldo.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2scjebgui.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2ahyaidcg.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gt2xedpddkk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gt2wepqqjes.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gt2awhoojhx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gt2bxcfgleh.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gt2plopislu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gt2uqagnwkd.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2pwbdzqje.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2kwtofwrv.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gt2yqwxzjbd.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kanznakv.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gt2zptpiniy.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gt2neafyztb.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gt2pvrhsyxw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gt2uaogbvog.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gt2vqqjqjuy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2kwslszzg.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gt2qrcaafdv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gt2szeacbbd.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2zjgwyvda.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2vvybdtos.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gt2esqmmmpv.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2fjxzoqhm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gt2vttlvstb.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gt2smajxdun.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2gyiewwsd.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2ujuuzxzp.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gt2cnvextka.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gt2raaglcgt.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gt2slgcsdjd.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2lzaxktvb.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2qqbxklwp.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gt2wlnigwek.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gt2gztxccnz.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2qvjrdnwd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfqovbqj.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gt2pdqylsri.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gt2adklntts.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gt2ovfbzjqc.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2odhmurmb.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2yqdbstsv.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gt2qmorkokn.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gt2yupjfyrz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2ksaaaaya.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2rgyphbqh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2oaewurxh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ehrobmfi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2gwswhvjh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ishvmxro.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2xcczspwq.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2jghjdoxr.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhytjpdc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gt2inqzalyl.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2thkftekd.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2odluplic.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2eptehcnb.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2ckortwqo.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2iatrfkuc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2eckrkcin.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gttltilq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xieqnqkx.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gt2scusbkbn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gt2ddysnylk.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2stnmcauz.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oipprjnx.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gt2riqxnrye.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gt2yshjpitm.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gt2plcptdop.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gt2dbalidil.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gt2vzbcxmyy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gt2myicdedy.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gt2jfwucpjy.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2imyrtxdx.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gt2xvexsnnc.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2livbqkhl.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gt2oijnmsmf.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anonqpqc.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gt2sufnelkl.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gt2xprywudi.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2ytmgfjcu.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2frjhhewv.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gt2gqqvkjcp.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2mueyieqc.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2flcnjchd.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gt2uabgiyej.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urlsdkkr.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gt2owhfvfvk.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2irtffmte.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gt2ykzjfxzi.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2elgxdwjd.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gt2rpnnoyrg.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2xubboklg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gt2pcxcccxh.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gt2gnkgfsqx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxjmdoqs.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2ookzisar.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2grhelppm.html


<!-- 参考信息 -->