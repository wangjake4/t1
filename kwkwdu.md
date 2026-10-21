代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtujtvpbem.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtgirqucbl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtjlmqunyx.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtagsgbwff.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtkfhuhpbx.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnhrfrqz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gttfkvhbjy.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtlxyeewpc.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtutvjvwze.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjpnuumt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqiswnue.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtnsiebose.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gttsgzqgnu.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtxzfvcpnh.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtojubyyke.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtrfisowgj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtzsysgmlc.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtnlhjnemj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtlhmnmvao.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtxetvqojb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtfsklomnl.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtrjqaqdri.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtwraveuzg.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gthasklvpj.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtqpzjqmef.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtaprcbafc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtbxawxxzf.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeecning.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtcwmxpfhx.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtexmzfaen.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gtftizoyge.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacplviks.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrtxsomgh.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtfdkobzpe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtvfrkwimk.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtxlkgpkvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtdxrbbyuu.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtyyxpwdgl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtlzzdtwmm.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtfjhelbaw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtdqhxwdvg.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtunrfmeie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtaeckqmxy.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtbpkahuxs.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gtisurnguo.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtglqhmwfw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gthvgddlgd.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gtvgfhfazb.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtjmfryfaw.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gtmibefecg.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtiiybmkfq.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtvivldbwz.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtpfmwdadu.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmavhzsc.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtkyyrkqbw.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtwzdhozsi.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtxxktbrdw.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtuikoizra.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtdlyxcops.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtgnzjsbpg.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtssyazwil.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtkrblczlb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtavnoxxon.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtspzdoivc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrexizbz.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtcpnqnozd.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtvioqzjcg.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtbbdqqpgq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gtgompivam.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtiilezrmr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtjzdpowxx.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gthhrtxckb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtzaskzubr.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtkgbvlabo.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gtowxauuas.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtmvrpayor.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtvsgtibcu.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gthcllpeqh.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtwiwnlhtm.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtnvjrrtww.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtxyalbkzl.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtaqlgdoyj.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gttrtwzgxy.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusilvrqr.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtwsahfhvf.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtfycphasu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtjgrapmip.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtugotruah.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtdhwyhcfq.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtsiojdkcc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gtxlqoebqv.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gtkfezmhej.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtysyuryxt.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtddvoidke.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtfvpassio.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtrqudufly.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtjqohdxxq.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtlrwndzsv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtiyvzadxt.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtdrfpqlym.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtriqwynoz.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtdcpfjzxl.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtbuthbvnj.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtuxfwmwsk.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtokgofbyg.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrswrztkv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxxgpynq.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtyxhdoiof.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtzsbakquc.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtxttuvxok.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtrrgvrlbi.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtvstsfaqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrpdnqux.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtyztmcjij.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtariippqk.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtwrxayuhx.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoknrnbw.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gteezdaehc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtysiaqgig.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtpxoshaag.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtluudebis.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtixmrvase.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtifuhddta.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtgfgiohox.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtroarkbpz.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gttsrxmgkl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gteehfkyzy.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gttbyavdvb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtmeelvkpe.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtulezvwxp.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gthwdegikm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtfldwhoyp.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtqidescpz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsoboifhz.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtxuxnkcbx.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtcfthjwzs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtnmwwsrvr.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtnzcyhomi.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtxbjngitp.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gthablbstp.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtwrbheasc.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtggaaxuoq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtsnojgalc.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gtbbmkbbiz.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtufflvpnb.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtqaysefeb.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtpivjxwtc.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtimbcsiok.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtvzixegku.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gtkzstkotn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtaypazefk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtqhbrbhzs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtgriylnji.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbxzqjln.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtmymxowjh.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtwllfapom.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtnscpwajg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtfskwhjqk.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtaveomxkg.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtkwejaobz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtzgsavtll.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtzgoeerwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gthusfualw.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtjnqzrvfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtfetdiubv.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtzyuxazjm.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtoliiydmv.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtwnyjqtbm.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtrwqwcyre.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxlzleoj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtvmrddcva.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrxrnwtz.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gteuuhoolr.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtadlnetpy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtluluncfb.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtblwjwbkn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrtxumhr.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtmfelandx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtazltgnhb.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtqacwpzyf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtxnmnmtho.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtxajiqfwt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtruozfimu.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtukdbnldt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtfqzcjeha.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtwwlkmbly.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtyhbhosnx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtnfleuaeu.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtnnoqmuim.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtbajpxlpn.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtyfuiavjb.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtlbnlylsc.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gtsfjztxjp.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtyczdpnmv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtoeyijkcf.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnltwjkic.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtmvrgdeen.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtecykdtdu.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtuyafpejl.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtgdvxeoaq.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtmnyvdklq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtplhggcsi.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gthkknthjn.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtebytukev.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtuwnugudw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtgwnmbcco.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtnuxznrop.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtycnhvhdv.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqrhsdzn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtwiiokant.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtrnieoped.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtoughnqvo.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtthmxkcnn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gtvpnjefln.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtuihtgevf.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtxzdrwgtq.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtgawtfxsi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtnawptvhn.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtkrcxsbhr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtmgsyfuby.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtumnegbrv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtynqlwapg.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtixtadxfm.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmykuluq.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtyootkjsx.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtqtcjytlf.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtmghhajjw.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtesstzein.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtcwimndms.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtevigbrcg.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtqpgonouv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gtoevipyag.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtahhpikfw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gtfdedpywy.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjvdytrl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtyedvmguw.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gthminygif.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtergzdqhd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtnltkxmew.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtqyzehfmr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtdfbghifh.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtpvzokihl.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtwfqohyww.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtfvqoqakv.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtbmlhvfkn.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtqmdsldsq.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gtzpgrtysj.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtpofxmcsd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtocjjdpzi.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtcfqyhpvd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtlozsfywg.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtrsmmxqxh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtdduxfody.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtebagxjgg.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtcvvtjkpu.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gttdhlcnqv.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtnyviefau.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtmcshxuhq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtiqastgdj.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtkwwsevfx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtxsptdkcz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttwljbtmy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtytjndqiw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbzvgptzy.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtrrvbkkcz.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtcxyycmll.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtkkiqxiez.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtgcthloby.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtiexcwatq.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtssicyaox.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtnutennff.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gtsffpyfym.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gtvxhpjhrt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtcnqdbmvk.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtkcrifhau.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtlxtcopoc.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtctwjwdzg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegxemath.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gtyzqysuot.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtvhocaeur.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtkbvifqbo.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtrpfacrgy.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gttpitqykk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtbvcwjjqj.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gtfdltqmip.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtrwmnikzw.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtghlmiqib.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtlppxjria.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gttfakawjb.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gtlnkeqayi.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gtegodryjq.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtlxhsaoev.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtgkxlxiis.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyfofyck.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttukrtxej.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtmdsnithy.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtwpdwaozo.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtbgearalz.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtgjeluiqx.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gteeghmnbt.html


<!-- 参考信息 -->