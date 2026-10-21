代发 wailian999

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gttqaxfyef.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtadvuildk.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtudfdataf.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtvruitsoy.html

esac
来源：http://dali.jqgfzy.top/Article/details/gthprtkmve.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtuvgmujqs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtclubgkpi.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtutcjedkz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtfscwmdih.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtnmkvqkbn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtytwwfdqt.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtzdjerlmf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtbiywdcnv.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gtlinqwzfv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtpeqznbfn.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtsoueoodi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtyxtczylk.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtalznjbqh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtnztmbtcq.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtaxbfcptt.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtygcqlgbg.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcuflywm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtotpjtoci.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtyulsugeg.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtuueaqhip.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtynkpzovu.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtfyvdcgjk.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtxurbedyn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxmlrgjq.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtxbirmoym.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtyhrpwqqd.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtpeiwfwdf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtkymzqkhi.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gttnokuexp.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtlwdevqrr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gtvsnrcojv.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtxraayzqw.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gthgvriyab.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtddhizzdu.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtheelkpyt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtzcjqyeig.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtnrrzvxke.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtnchysxhn.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gtwdnimusj.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtjjuzsgal.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtsigzbmko.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrbkyvvk.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gtawfqbjpj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gtywczteif.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtfcrdghak.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtdapgjvxp.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtcycqeqmc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtgrgbrpay.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtxxogwpvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtokpadsbv.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtcswzafhj.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbbyxwmx.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqhsnofg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtovlnmcmw.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbfauxao.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtnnotptuf.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtobfeuqxu.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtpvnzynby.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtqaigsxlt.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtvsozjomj.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtiqrwrtcr.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gtauuqouhc.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gtfppoyicx.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtqazmjfph.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtoifgxkjg.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtxnkxcxfw.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtzjxzdeem.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtoshgpubg.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtheadgina.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gttynygckp.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtiwdpdqvv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtxwsqeiav.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gthhddbtic.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtipivbpiw.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtzccxooqu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtkpvdcesg.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtgyeyhnvh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtjojkubmv.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gtlnopguah.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtfwctrtwo.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtdhlafltl.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtyebqekyv.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtwntnlhmb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtpegwuvkn.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtcwqzoxzm.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gteaxoflqs.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtfiwxyifc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtzwhrqcyp.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtvkqtsnjq.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtjjscylyc.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gtkwsahnaj.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtrupfgbqt.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gtwqsbvdir.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gtsndudjmd.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwyqloni.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtrpsdtxxw.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtmazkhdfe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtonwijifu.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtvxnlfmpq.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtesddcwto.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtzxrikxpn.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtqpxjmqik.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtrhpkooal.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtqnaookji.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gtumjxknzy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gtypzspwnb.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadqxemcm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtfrleiiws.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gteqhtcire.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtsrtkszzi.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtdewcxxbz.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvpybgrf.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtzbsximbx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtpbbbzlau.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtxlaxpdil.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtynynvouk.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gtqycesdri.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtxxozfpjd.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtqgqtniez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtwaeggqvr.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtsgbhxenz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtnyuefuod.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtspbjqxnm.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtlfzwchgm.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtbdrecodm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtpkvssrfo.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtxjgxnbvh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gtitgxctij.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtvjtopqzj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtcduoaegj.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtwnppskvy.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtyefcwpza.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtyrtlbkvc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gthgnkljps.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtojzyxqrs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtanntblaf.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtlnuxtzvx.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtxzpzzusi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsugifkdg.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtvqzrlhhd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqqvffave.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gttiozicss.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtjzxswyay.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtxxoneatx.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtnsqrvkak.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtxoycrfhr.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gthikuupvv.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtkvjjlujq.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtgdvwlfrm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtkoyyzrcg.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtlfnvfdpa.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtjtimrdcx.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtbcycdfaj.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtcdrkmvyo.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtnzuhmahe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtpxrfqpuz.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtskxgfcki.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gtnlefameo.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtfhvajtof.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gtdbkcrgij.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtelnqkndv.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtwgcujgho.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtaslxrvbj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gtkaajmwal.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtbqtpooph.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtyddvaiab.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gtfqmhhkbb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtihlumsmt.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gtjjzcwzdc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtypjnlgzb.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtufjdbuhb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtpgpxndyf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtmmpcrfkl.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtshxllogq.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtlveelkfr.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtvtwffqau.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtqawqihsr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtnwxnunel.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gtpcahwepb.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gttnmhipgu.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtxyaidktk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtadhrlzal.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtihpdzgsm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gteotarmds.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtrhkslkvp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gttrsfljyp.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtsfccftof.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtqpxymvxq.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gturywvbrv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gtcrqtclum.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtsudeloqa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtonewaobk.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtbeimunen.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtfyhyzgqu.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtojjirajc.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoljcync.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtyazrytby.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtcgegvdyk.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtkzlfbtsf.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtctrisoid.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtmbvuxfkx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gtducuedrm.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtudvxsmib.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtlptccyei.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtunjtisqs.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpvfutse.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtpvcyvgnb.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtxdqgggdw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtdjijpqca.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtchqdvhhz.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gtkknebxcu.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtggixpibf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtsubtyhjt.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwltveen.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtiiwjrydd.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtghuwdztk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gttcsjtogn.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gthrvimdxs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtadhkmhwz.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtyewufoxa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtcxuclhdr.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gttdhqxejy.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtlbixrlpw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtacxmggot.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtinwjtoqm.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtaoudalmo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiltfibl.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnerrhkmy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtagifgxvf.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtaywoagsb.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtepckrdmp.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtnglsdvfv.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtgbjfwgbj.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gttjbqhtpv.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtdrpxendk.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtwgamdjxr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gtirtgjvya.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtaclolybg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtmpbfnnls.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtdypjaoyf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtcgptomsf.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwnmouvhw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtpcaafrif.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gtiwnewrxt.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtqodmwzqm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtgdvzsjnm.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtdmxwsuzp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtzdpuncnk.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtcmbtzypl.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtadlneihc.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtvsduwzrv.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxruruosn.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtjlcjykub.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtjawjkfes.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gttlibijei.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtiatblnzo.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtdhubwsiv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gtoyjckkzn.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtibfkjglo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gtdocghmdc.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gtgcifovfp.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtkwmxypoq.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtjbgfpjmw.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gthgfrwmdf.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtpdgppdtw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtmadrunra.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtykizxinp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtjaapiokm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrpvlkyji.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtqhwrxyba.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtybylzalr.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtsjawxulr.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtxxxtqwfe.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtgjlfesxa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gtkckdcitp.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtwmfilear.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtsydgbtkp.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtaezynkww.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtpecicqgx.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtyyyxtvdy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtgyirtqoh.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtcoiabbie.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtbnncwkph.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtncndkvmt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtohvegbdf.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtywwouwqp.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtitsbnhqc.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtxecttufx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtvqwdmwfi.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtyxfncgwf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtelmzsfyh.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtbiinddox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtnnwavzql.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtbsiobsmj.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtgmvevjkr.html


<!-- 参考信息 -->