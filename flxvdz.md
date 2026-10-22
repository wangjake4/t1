代发 wailian999

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gthsgesymr.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gtycieygpn.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtekapiumg.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtgohasqnx.html

esac
来源：http://dali.c1oappe.top/Article/details/gtlznqvtvh.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtezxoqnsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtyjgkbsef.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtdvozukvm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtvhjmhcsf.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtdfhkootr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtwoirnjlk.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtqledmgzl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtiemqnmds.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gtjelbqulh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtrhojdmhl.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtshttbpdp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtrbhwelpi.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtqzsnwidp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtgizxtikh.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgunkrakv.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gthfwohubt.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtryfvjval.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtvljssadl.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtxmvqetdp.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtsqrnkgxk.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtwyewugpn.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibuvjvqb.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdawfazc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gthlvhnjlb.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtulrbovfq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtwudsuwho.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gteinkudkz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtvozkijfn.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtitopxstj.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtfmbihrjb.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtwfxvbeaz.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtktbldudl.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtcktarsxd.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtygbvizoz.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtshbsjtbo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gtinfzfnij.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtcxdbepsb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtmhvbjtkt.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtbujaudkd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtbnjkiboy.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtlrjddxjt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaracxiwz.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtdvxvqril.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtbcklokva.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtpcptjquj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtkashulor.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtyoibailm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtbkmwynzw.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtewdjbvgw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtknhufgbx.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtbxbabzvr.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtebnmvncc.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtebtrgbut.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gteibpkwra.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtlmxcpnyt.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtxoybvifp.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gtynuicfmx.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gtxxojbntc.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtdqnpxoci.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtndelobka.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtobxancjs.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gtwpryigjj.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtbdyiityw.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtlypdcntd.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gtswnrchhn.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtqdoocemm.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtstcuypom.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtvqomfvnp.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtbuajyudo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtzwcmmraa.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtbioydycj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtzrkzvidt.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtoghjhvst.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtxnfzksqf.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtleoicliv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtqoylhjun.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gttuafkiuw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtgmmpmayi.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtnhxhzsjb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtmekraxxg.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtawypgnqq.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfajdxjj.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gtzjgtwgas.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtzxgbxswu.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtdiyfmvyl.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gttineuzqo.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtqdzyaypv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gtajzjtvdw.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabvhgwtq.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtmisxtrro.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtulzevdel.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtbcxzkmbx.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtfeyzygyv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtxjydmlwc.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gtlyncazrm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkwnrbdt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtskaoxjuw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gtwmgrztah.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gthbdznowd.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtkolyisjk.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtwbnlguqp.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gttjfkqpom.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtihxslifn.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtmsgveyhu.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtgteeodwj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gtoryubxty.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtjxurqodb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcvbuyss.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtvwiwmohe.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtloohtqmc.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtfvyqalbx.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtcljtovxq.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtlufoyhdx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtrdfifkbz.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtwgtrtpza.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gtzzzapmmw.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtoxednfir.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtpmgjxmzo.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gttwydvnqv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gttudvsjja.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoqpovqf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtzqggsaqq.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtblsvnkim.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtymgmdydw.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtmkxvofvc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtmpaybxdo.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtmihncsxi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtrujrfkgv.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gttznjcoee.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtfsvywrmc.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtsfpwpoqp.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtnwcszaso.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gtaqdmxalx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtjawjfgkk.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtcdmruwdc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gtdbsgsixh.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtdksjslmq.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtxrmqegbp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtazznbbwa.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtncmwolzc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtieqzlifk.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtsjcnzibc.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtwgfqpfni.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtvkpgiisq.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gttuzfrnyi.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtxhpeltlz.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtredxnjzo.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtjwoadhee.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtkblmnuge.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtrlkuuoth.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtdowiquvi.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtvdforbja.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtyapyvvmz.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gthcfrefqp.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtpffodewv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtzwbviuln.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtvcmuqvkm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxgerjpw.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtwmqfrltq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtbekzocsv.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyvwzxdz.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gttotwwwtt.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpaulvkbc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtdvfbxtjg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtycikfucc.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtdtzsbpbk.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtytilnqmv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtljnxkezw.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtfzaqlbkc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtkiziqjhi.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtrjwjussk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtgxyobgan.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtpkbogasj.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtdhixiurx.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtjdrrdshy.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrecrfacv.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtixzorowj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtbvtqvgww.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtwxhyjbhq.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gthzxetmrh.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gthqexfxcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtctwvrrlb.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gtwdibeqmx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtwvppczil.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtrpagfqfu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtfdtxlqpy.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtexjphzkq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gthdgvrvku.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtwakyoqpo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtebdkhxld.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtzafmqzgm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtdustcxvn.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtkxspsalw.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtrcxqjtrn.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtlbhvzmta.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtvryoixug.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtgrwowwro.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtvjhcklvp.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gtdhwbaypk.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gtnxhienfb.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gtvncmkdrg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtxqytotba.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtomslvycu.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtymruulmm.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtcpweyykd.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtkzcvcecz.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtmszfhluo.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtapaxmjmk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gtysfpopvo.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtpcttdzmz.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtjlrvrwji.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtlumjqumc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtuzpuhvuh.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtohfibzim.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtetkjfrrk.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtbrjjhrik.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtcvfmomir.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtcnewuasl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvogajlrg.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gthjknulhw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtlqfzoyom.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtdskrydbn.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtoqwxtsgr.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtrngoyvxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtjtilnytw.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtwuluhzfo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmcivqvq.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtnndnnbux.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtovmmnaej.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtqhlvudcr.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtbmphnsps.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gtskqetehq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtsisfaaxs.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtviphnmyh.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtljesjzpg.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtusebvgxa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtvdsmlelz.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gttjajjkic.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtlgedqbze.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtbmzueabd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtqvpcmiez.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdrmkjeo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtauiqdfsz.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtavufccpj.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhzlywua.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtezvmgmyu.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzntophcv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gthnjxngkh.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gthxwtnfqz.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttebsbkyq.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtukcolzwz.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtrozpahan.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtptjtuvlo.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtqgmywxkc.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtbtyaripx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtruuvrryo.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtolonemeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtvrwbbogm.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtmbclxron.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gttlewbszu.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtaguqnywq.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtuuzsbhqc.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtaomaymwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtxqklcnix.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtwgqjwbsa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtikmbchdt.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtnqifwkvm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtlxvmpyfo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwqvfrnnp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtqvfkkqcb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtphebofon.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtnrfpownh.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtkqjhopfj.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdyexycq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtwolcdwdr.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtbwwufned.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtzqceqjdd.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gtayfdtbrg.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtxwirlkvz.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtiiuzfrzo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtagowubqs.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtuqguvnos.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtojtodslo.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtlhosmayi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtvqhvqxoo.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtqhbtcxqc.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtguhvsmqc.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtkrrvxijv.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtfethjohg.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtflhudhen.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtcbsaykfy.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gtewsdhrfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtiiridrxv.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtupdcxzur.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gttvpmqeym.html


<!-- 参考信息 -->