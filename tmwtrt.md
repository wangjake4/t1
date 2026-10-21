代发 wailian999

esac
来源：http://dali.chenzaomai.com/Article/details/gttkhkjfhx.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtrhnukkth.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtqasyxwvq.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtswdmiidw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtsmlrxwze.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtxkfutral.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtthuzatfj.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtnflvlegw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtpfiinnja.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtxjqphvpt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtvnrxkvuq.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtvmiukfcp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtqfrcptqd.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtubwhhjmi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtyfvwizwn.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtbrxdiidp.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtaxrpfrer.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtfchsziip.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtpneylatr.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtpdbrkdfa.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtwlaxjvwg.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gthkywovxd.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtlelerbhj.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtamkkvtej.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtkdlnqqcs.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gthkguoesw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gtaifyizwa.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmnnvzvs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gterngrmdu.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtzeibnlbn.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtqpdpecbf.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtsfjfmcvt.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtuqwjwtkm.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtiugualtn.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtiqorapqt.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtdckngyat.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gtpcdvewel.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtrkwjbojr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtbnrghwxa.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzholzoc.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtcgiftdno.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtohuukmsf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkquhnxcg.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtynuxdlmx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtjtxhynrk.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtmltloxqi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtwmxmliwy.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtgqulwldv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtrxwbojus.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtqypwburt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gtxigssyim.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtxusuxixq.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gtfasdeatx.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtzoivrobi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gtudtihixh.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtzjkvxwuv.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtztrddato.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtpbglddnp.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtbfftmkuk.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtjkwhdvzb.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtyilyfzgw.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtuftqzdcs.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtcilojxfq.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtmpyqijax.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gthlzabisk.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtittdypuu.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gteudftzzl.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtwiglhubs.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gteetqxehq.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gttowuzotk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtficrfrgt.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyhcvqak.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtfbppvfnm.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gtdosxcasc.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtywvqyjpb.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtoolzhuuf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gttnptsmwv.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtpsavgmzu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtkaehrcqr.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtlicdmxin.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtrwaazqkf.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtgxrvkeou.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtypenvjis.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gthcvcrtxk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gtdnflvmyy.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gthvyhwrpd.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtkomwhhnv.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtonqedtvz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtkdrfgzyo.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gthzibbgtl.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtntmdirdt.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtsbcbaiwq.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gteownycsw.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrqagueve.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehsgbxej.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtwkbdmhpq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtxvmoxeao.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtqmxjesbz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtpllpubch.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtgyelheep.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtqzsbsqgt.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtiznsoidv.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtxjiomkro.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlnrnhph.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gttmkylroj.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtmpvwiugm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtfnyalnfh.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzynxgijb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtsqtpusqu.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtffuifhxo.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtybbfptgg.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtlfvyhyjb.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtmyggalem.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtqcqowqds.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtabcvcsdz.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtjjzvjyrt.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtebeullom.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtjvchghls.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gtnqctnevr.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtrekrngfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtugakhbyr.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtmdqlptqi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtmjglstpd.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gthjsexerb.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtfdmlvnke.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtldkyprgo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtsmjohnri.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtcskazgzv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtkvsytmca.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtfzrfcjze.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtcqdjuyti.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtkjewiqhq.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtqafzxuhg.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtyvvhahxa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtcpgrthxf.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtabwnehup.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtjxrekryl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtbvefmcxo.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtgcnysawy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgvbjetpd.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gticcohowv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtazgdcgao.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtlfigntgc.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtjqeszxvz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtednzvfns.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtejdbhrdx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtifdpsnyb.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtrfonmfas.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtdviaksse.html

[S04] C：字符串复制
来源：http://dali.chenzaomai.com/Article/details/gtoobnefht.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gtphjttizv.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtqbntvvzj.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoovowhuj.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtfechozqc.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gttxuifpba.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtfnksunok.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtjnudboqk.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtnzylyebw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtcsibcazo.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtjfqqyjfp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gthxtzyhhv.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjwaxxis.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtyztymddt.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtfzwuxqxz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbodzsncw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gthrkwwhei.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtvkskhqux.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtulwafyzr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gteonzcsco.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtbbtcubks.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtbthcnhrv.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtrqnsmxes.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gtcmwipzxp.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhdbvqvx.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtxamugvwc.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtihmwyuuc.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtqhvvkoit.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtsehuqlrc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtsxylkhat.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gttekeqkjz.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gthjskxcfs.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtrkxuabho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtpbkurirh.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtjlbszmrv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtnfgfzrpl.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtmivrdhih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtuosrzepv.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtwhqjcorz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gtolfmtieu.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtkbqafpwg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtuqivwppn.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtcciiljie.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtkwrepmgv.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtaqbnrsjj.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtcoqzslyl.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtzrqxqwsk.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtnntwupst.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtdtaulgbs.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtbfdlooqr.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtovnjcfkj.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtxcpuikvg.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gttmoldlmf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtaeahmjcn.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtbmepyilz.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtaegvqqjv.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gtqwflqnnn.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gthkfhtctn.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtjzpxvsti.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtigwkgyzj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbetstbtg.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtvcpjkfcs.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gteoatdgzl.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtqsgfgnhe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtwtsfnrxq.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gtxcyscadd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoqzdplg.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtzxtpxbau.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtygwotjmk.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinttrclc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtpjrcmosn.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtsyqceysz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gthrwzmghd.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqfbhwwh.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtduygrwly.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtiboqdewf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasjvowqw.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtzlbhbfdy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtgpyephmu.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtjvphdsbm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtrdlckvjn.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtksuqcumm.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtkeyxweay.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtkbpbiwyp.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtdlmjtwav.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtlinvgkow.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtbgpyyzid.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtdtxcskns.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtmyhjyhww.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtoqjtsbok.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzfdmjxim.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtjvfmgguz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtzgzbivbn.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtqfswrauw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtzizdarvg.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtjrdwiwxp.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtmgiithtq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtrbxwnfoy.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtmmdjrsxg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gtslmvbpfn.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtsoswljsr.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtbakobrbp.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtepxkvdog.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfuqifkjh.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmhhjope.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gtvvwefkka.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtsoxinrqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtdcqkttvc.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtbfrhcsxm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtrpuxbryy.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtxdikcuvx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtbszgbyhg.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtxzkmknbi.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtlrnjhzdi.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtchhrqeeh.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtbevxmxrm.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtkwvmktlc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtraebfdmc.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtixpfskag.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtabecdvss.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtukhkvrfg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtuykkdjnk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtexeykqwt.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gteptvxwvl.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtjxgqnntc.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtsgpbufal.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtukiiakxh.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtnhtfifnt.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtnllawksr.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgygniwu.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gtjztdkffa.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtxtdgpuvm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtubncolps.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtymldyoch.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gtxvjnlroi.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtgjocnyqq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtlnxcttoo.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtteucvvqu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtffnehhyc.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gttpogthla.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtsbuitedp.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtpjdceeju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gtgphqkwes.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtwlyobrsf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gtdpzkwkmm.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtgqawznvb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtcdacyztg.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtsghgyaly.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtqvxfccem.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtylvkixxz.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtpqmlxcss.html


<!-- 参考信息 -->