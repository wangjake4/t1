代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtgovzsejm.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtnmsgubft.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtzsgcofqr.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtaiabutle.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtbjkkpmxt.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtielcqhcp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtzsaoncat.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtzsnmhyzk.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gtklkqathk.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtwiblgawx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtwcwnozxb.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gttcajsmae.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gthsxhobwn.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtphwzecap.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtzozwsvjg.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtjniavgni.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtlnilcpxv.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtipkyqqag.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtcpqlfuta.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gtncczdmpa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtefbjzqsa.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtwmvpirms.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtbzahtogz.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtjgidqcyo.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtibvudlhg.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtcsxbnjrn.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtprchijml.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtedlbrsgn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldmsupgi.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gttlvcrwlr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtfwcpndjt.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtrkebzgca.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtklemgnst.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylojfhhw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtpzoeybyw.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtzoiasxpx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtqjliuknt.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtfqiitmeg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtgrifgdij.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gtksvokccx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gtyostqjyi.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gttbxeagjp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gttjnpxlib.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtsazaidxe.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtpmjwhtks.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gtpfsdwxwm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gttgbhkfyn.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gttjlkfcav.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtdrlrcviv.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gtsiwqwdwr.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyapmbrm.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtavsqrehi.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtnswampvq.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtvskprmmv.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtvircyyzs.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtsvyrxcco.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtlwvvtfzd.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxvrjeqr.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtbbizbohh.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtesfoazog.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtolghzuji.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtomevhpcz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gttiwaivag.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtxcfhddne.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtpebbylzg.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtbflrtkqc.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtzrvpnbsc.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtptfxtvrh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtddwhgwlt.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtwflwriaa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtmsmeqtpi.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtjrztfksi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtdwytsirm.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gtxbbcztpd.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gtwerffete.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtftjojcwv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtymrgpunh.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtnhmqfstf.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtcrwynxel.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gtzvubqvxa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtszdwevqe.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtjygifglq.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtokmzpzmr.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtcpozitsn.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtkdupjrpp.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtrjynytye.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gtisfdkhfb.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtydfkjibe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtugmxvxmq.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gthrdckkmy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtjbpsdjun.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtqsqvcfin.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtlsdtwgqd.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuqslywv.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtyqpzeqqf.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtdqpeaiuj.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gtspsneudg.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvfwdqpv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtishbjzqy.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtkuaawjmc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtlfitqcjo.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtmoyowosb.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtikxgxzsd.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtmkjijwzf.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbpznmlp.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtzruizdww.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtqacrrwpb.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtpxmylhyf.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtfpudylnp.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gtivowpten.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtddlrudiu.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqjfrhqw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtlcxvzokw.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtuuquvpdd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gteysejgyc.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtvekvyaoi.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtgotopyij.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtnssqbeaf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gthaxvkwcz.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtmtmbjcnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtuccuowto.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtalvjiwmm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtfpgvrgqd.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtkjrpmrgk.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtsucmobtl.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtipkdxxft.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtxwrodvyb.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtbkvdvxdm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtlxghkwkx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtcruasvon.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtbniwpwtg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkcpnyyto.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtpfnjagmi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxjlasdrv.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtgfgllevb.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtpemlzezx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gtnwrmjnpz.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gtiplobvye.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtoxgkagag.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gtmscuzdha.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtjyjivxkl.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtrqnwmvus.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtmwmbmguv.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtogtmgzyt.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjlgrildx.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtemcfmpnu.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtjqojfqtw.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gteloamtgr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtbcfjwixg.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gthaxubahi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gtdjnqrszi.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtrbmvgcaa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtrtpxnshy.html

[S10] C：指针与解引用
来源：http://dali.shzxlz.cn/Article/details/gtiqhwitfq.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtkmgdenju.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtgakdfyjx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtiwfmmdit.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtepxruuet.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtavtrdrtd.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtqrkhcmqm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gteyqkyack.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtshgjkldl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtrzmuvrkq.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtjstrzoon.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gteifhyfjv.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtruwnrvvc.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtvdgcpbzf.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtahmdvwov.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtbngkbocd.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtdnchqhtx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtsnxvccts.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtuikaxsky.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcvsgmbw.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtxnquwpjv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtkhzvwbwm.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtutssbxzc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtzwpklxkl.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtiaoeuwog.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtbwiyxveb.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtacenmsth.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gtrfcjifuo.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gtgativjhf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtxbaeizik.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtzofcznaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtwwyfnzjk.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtgrzlnenc.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gttrcyxscu.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtalmhiafw.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gturhbkjee.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtymgweiwp.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gthqktmdqy.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtajmtgnwh.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtgvmxekoq.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtjhnwhltm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtzfsrsphj.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwodsyac.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtqkcmfipk.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gtahjzjyff.html

#endif
来源：http://dali.yonumen.top/Article/details/gtwmlsyezm.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtnerjdlap.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtozasikno.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gtlrdeauxg.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtsobocrxw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndxbzrmo.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtxczlttll.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtvhjzeqrf.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gteeugaupi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtdgnlzcre.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtacjtwegr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtclytfrja.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gtxhuvjzpf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtigvvbcle.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtmopjhecm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtfyggezjg.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtjtzjnzps.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtncvncnjs.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtiglqthrm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtcwrbtqom.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtqdyrbjom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtqoahsjog.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtrvlaihfk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtlsdcfhtr.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtixxvjzaa.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtyijdvtil.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtfhgiymyq.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtfznwqvof.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtbrqbutyx.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpvszmqss.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtewpqmoxw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtqmcmvcwi.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gtemikeupo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gthorfdaez.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtptgizjtm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtwqpyarhq.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtuugiuvxn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gtljbaqcfj.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtkkpcwera.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtdxrqghzy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtjborxjeb.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtzsabakqh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtwsuunpgf.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gtagmupisi.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtmrxusrfg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gturyaueta.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtoqxmglbv.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtjhengokx.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtoppqojlg.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gthvjibgrp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtflsnxdze.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtwoyizmql.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gtxovhgxor.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gtgqyymvis.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gttkxunaeo.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtkadwtbbd.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtbljyvyzb.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gtfgaakdgi.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgunaegg.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtlonfabvr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtwybvnfqx.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtdbypbltf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtoduzrqur.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnigkcpst.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtgkrlvqgu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthqemlbxz.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtmtpoxftj.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gthfestwpm.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtqwbdpexr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtrrsvzltc.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtvmvxtkce.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gttrkvnmat.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gtlfkbksla.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtpztbhrli.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtukpcacgr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtmseukghf.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gthdbpjmsg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtaljtygtl.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzagimmp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtrhofyblp.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtonxikuzo.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gtlhayfcef.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtkjflfhng.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gtaknctkkn.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtekygeifp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtqckwmzyr.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtfeerpola.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gtfrbtcjrq.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgmlfier.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvgnsesfl.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtovmflznj.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtlasbcanf.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gttmmohqai.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtrdmahmyp.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gtagrnwbra.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtfukrhmpn.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gttegcnsok.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtnnjobwaw.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtoiwkfiry.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtzuqwvkvr.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtuonsppzc.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtifgsofsg.html


<!-- 参考信息 -->