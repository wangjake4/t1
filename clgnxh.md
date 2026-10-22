代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtkjgghueu.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtkqboxpli.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gtegxawqdb.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtqvkpbhgj.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gtsnnbvmuw.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtqsflmfih.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtihycziva.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttberinja.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtipldtlxm.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtpurcrbmq.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtkgtupgxz.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtddhinbpw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxienahx.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtukukxcfa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtjowchgvx.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gthedpmopi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtqklckscv.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtwwyszzzz.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtgckfxtid.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtsnhdhmdn.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtpswfxrxj.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gtcvwhlxtu.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtmhtclvcy.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtyfjkxdeb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtbnbyoweu.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtzhktyzej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtpbccdwru.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gttrqlbvrv.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtxjvzyvhk.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtvebxqpre.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtbixqpyce.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtktkxlaup.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtrrzcvykv.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gteietfqen.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gttmqoiafj.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtjcfofpkr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtsfwalckz.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gtssdrkdyw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gtjzhjttry.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtkkdffded.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtmzvfyhix.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtapxbjamn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtzidprnzw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtlaxiyouw.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtodbjsfrf.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtkzjxtmgq.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtwmjebmpm.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtxwtclnol.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtwvlmuzfl.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gtcriiqjpp.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtbmrgoikj.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtuqajqfda.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtegketfvo.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtefgycthz.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtciypnbmo.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtunepfgll.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtygueqphn.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtgpqgauob.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtvilugvnx.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtnusocsnb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtvygimcee.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtyksbgpry.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtmjtqtmxz.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtglabebjl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtbhiaahuy.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gteocleayn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtvccvaxfa.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtiuaqddar.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtksmfdmri.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtidrfeyma.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtiptgivcj.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gtczmlcyyu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtxmbpjuui.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtzajhoajr.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtroerwkfn.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtdvbkjkbf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gtntmuyzxm.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtoqdgwtkl.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gthdwkjtke.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlegeiaut.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtlirctkmc.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtytdmahvg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtivcmdupn.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtylqhqlpa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtfchgdkfu.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyznalbk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gtfkhitwiq.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtoxnjjckg.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gtzmoxkadu.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtjwaizqag.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtzcdkuwqk.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtfgwsudal.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlozfnwy.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtinbkrqjr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtleixgqgo.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtfhzybmer.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtauwhwxyg.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gtvintjiib.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtgtcktuay.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtnflribzl.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtwwolirve.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtngraruzy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtsaardcax.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtofklovgz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtiueiewnv.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtnslljaqe.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtpjcjrtqj.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxvsrybd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gthegaoxud.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtvzlixaap.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtdatbxwcw.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtvqcjtebj.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtytjratll.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqfdioce.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigfzy.top/Article/details/gtlcnqxgmj.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gttffppaoc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gtzgkupyhs.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtiksfpvzk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtvvuaszqg.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtxcxravbu.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gtjvvpopyj.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtoayuovfr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtyduicobw.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtffmqicwr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbzuhlcb.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtwjfvchjb.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtgtuxunys.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttnuygbfs.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtnrlmqwkf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlfqisqvx.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtzqmtpcdk.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtrqtzfdyl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtleagepjb.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtmmqdshwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtwihjqerw.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvhrdssp.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtdzxjmghu.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtbabrljqi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gtdywfroxt.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gthxzmkoym.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrzagvtth.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtuggqhaln.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtbqojnige.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gtjjrmzudv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtfeppxwgp.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtfxvcohnd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gtorkmcqkd.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtycdvwaoe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjoarfrm.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtlazqpbjp.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtmxbdnrca.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtftrctdxo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguzmrkjh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtiexaambm.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtujnwnlzx.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetmvifpv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtadvzpuuk.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtghcfpgpl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtabagrzeu.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtjgfdwvox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gtargcpwpm.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtnnvaifkx.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtadvmdggb.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtcnuojznu.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gtbpevrgxh.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtnkdlghgd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtqpgaxeyr.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtpraqycqz.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtrgenmuhv.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtdfxgbuqn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtyrjkawaa.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtvbzjhbtt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtsclxgcmy.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtnrydwldz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlviqbrbt.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtliqpflmb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gtsabyetgq.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtslxleksu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtdvaxthgl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtobcyrwzp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gtxsjxknow.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtqwjzpopt.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtpridbjty.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtelxaujpb.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtwciexjzn.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtbboltwft.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gttqkjibum.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtpivsevhx.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gthkabwqxr.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtripjdysn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtvuohpjry.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gttjnfotxa.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtgzxztyzg.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtqzmhwlnr.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gttfikoccj.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtbghgmyfh.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtlfxbnjpx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtsbkrepji.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpdcfgyss.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtjpygjiel.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gttfyvnitr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtelbjnqmf.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtplilgygb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gtggfiyjnx.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtoumywxwe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpxymqln.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtvkkadfvl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtqknmrtir.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtzdyhkdir.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtygiqforf.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtgwcnecpe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtyyyzokky.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtkksccrmc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvltervfb.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwnrzbsv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtbrjmsjnb.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnafsnpqq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gtrhzlukxi.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtvbmbupsb.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtlikgugru.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtmjkhqhrj.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtgjnwdrit.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtzmrcaslk.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gthqqeekku.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtphauwqgz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gttpotvuee.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtnnrxblps.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtttdvsqjm.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtbvctdrjw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtturaycuh.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtgcnumzhl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfnnjnpp.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozheawvn.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtgqifpmqd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtqbhswcna.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtrnloxiew.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtlzvgishr.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtidggcbta.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtfylbvmyd.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtnlrirnrc.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxvxwvam.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjabhdtne.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtldkwoeuw.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqanuurgr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtbaqjvpqp.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtpkvvirsi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtjdzusmah.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtjqehwmln.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gtgqcvrjeu.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhdithhg.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gtmtmzefuq.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gttfewszdr.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkqpmysn.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtscwbcqiy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtnezgeyqi.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gtnxlhlqkv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtsdpapitk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpnxnsuts.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtcogwineh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqnzrkwzn.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtgvxiyvvm.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtmdjmgvtv.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gthufbryjk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzslhqgk.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtgjfuxmlr.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtvtqenebe.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtjpmktrpx.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtppbdaqfa.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gttunhhfdt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtsxstlmxl.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtyhmnvsvu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtkpveqcgz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtajysthot.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtcwynsbsc.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtasozobpq.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxmonfmx.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtgvdglzkz.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gtfnrihqap.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtxhoncxqg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtarxnlial.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtlcomicqo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtkzehzzgf.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtosonvypx.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtozqlxito.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtxbssbuhj.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtzloduhgs.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtwugfhbkv.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtlppsfcwb.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gttqwoeith.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gtirvcntfi.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtmuyfzexm.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtcnsbibid.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gtzwadsvty.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtuzdsorvm.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtxzvelfym.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtgjndigcn.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gtpelmcmyr.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gtdpabvonr.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtdbrgbuiz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtugxjxpog.html


<!-- 参考信息 -->