代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvystqjue.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtquntqxyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtcxjxlujq.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtgfwdqogb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtnibqdnbf.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtwfgggllw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtoanvtfgs.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtlisusmct.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtyviwjnbp.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtfxksulpb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtxvnnkmvv.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtoiyxsjoq.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtbxncvmbq.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtjegwyjvh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtrcxjzqau.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtathobcds.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gtmalilrgf.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtdcueqpdl.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtxdhsohfi.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtubxdkdfy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtwwhpahdw.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtkagptswf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtkhyfyjjn.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtgtylgswn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtxhfblboj.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtggktjohh.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtzyzgfxxk.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtewgoqrmj.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtufpcwjkf.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtwkaegoiv.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtnlytlwdk.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtrharjkba.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gthxwtcjpj.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgtkimav.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtfwhiaork.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtsshdaynk.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtppbjjqee.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtpismfcfy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtigypexmv.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtoxfjrqfs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtgapyzxxm.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtsxweafei.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtzxtymaxh.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtpbksytqu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtfypdjzga.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtvaihubeo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtozfnfxeg.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtiznovuus.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyargncyp.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtypcwwyqi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gteyeufdsm.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gtbvtheeaw.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtcebpixrg.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtidnnejym.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtbcqeuxla.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtupkmrrxy.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtffgjkili.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtztcuvjua.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtezdgjesr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtyvsswtbs.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gttmbnzntd.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtflkbsfuv.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gtcpqqfpjk.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtfnjhkzcp.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtodnnucxi.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtkfmmdzxa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtuujdscmw.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtngdviqha.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtyxamlgwz.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gttoejwpbp.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtujczqfhq.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtnttjkcgp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtxijfjwsg.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtujguvrqg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gthbhlajyl.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gtbuumvznv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtcmdbraat.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtlroxvfta.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gtchvvumja.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtoertloqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtefpiilzh.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtqdffopsx.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtddpysski.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gttoqiuayk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtwgjntsdd.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtynwrvenj.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtlcvdppmt.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtjhxhxwmi.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtwmcyvmor.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gthuapgesj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtwrtkfymm.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtejkieynw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtkxdkfoyt.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gthjsqqyfe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtfgpzndhs.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtyvmuadid.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtjbievitk.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwykznfe.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtusojappr.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizzlsnml.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtcfqrfkwu.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gttdopzjxd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtligpawtl.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gtswajygsg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gtnnhnhsex.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtyzsfnvgz.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtzhyrozjx.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtgyhprccr.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtkyvbzfzr.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtwberqrgh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtcmpdlkwe.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtbeppyojn.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtnckiidxe.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtpvnwuwcm.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtevgyibmb.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtavduutda.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtlpizxizt.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gtbreqcfbs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtnlkkcmiz.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gtwyaggjdn.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtpgqvxcun.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gtbkrktpgp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtkgmbrgti.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gthcdkbxgo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtalbtcvym.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gthnvuwamh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtkzlygtlt.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gtmrvfbufg.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtzsgljtca.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtkshenfrj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtyppcmrgp.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtqeqegzfd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtbtrzzoad.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtvrmqnbpm.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtvuryqcga.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuyerqjrt.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gtpbksfhpp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlbnqrgjk.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtsrnwqcwq.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gtexqjxbpw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtqvxwwbmb.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtcbfyqfgg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtnfovkvqc.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtkohmqqgn.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gthicukgzw.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtbzixxbkx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gteiducmwk.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gternrcnld.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtyiwrimwa.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtvipimgjy.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtdoypdqpl.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtordnmvvy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtvfqpdwxb.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtqccrhwkv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtqqtpdbec.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtrqobkiyv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gturtaiwzc.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtjijadufi.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtrkesdgsi.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtwbxarfuq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gttqfivnjf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtfubeqeys.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtvzzljmak.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtgofkiuen.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtocgfefwe.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtqegnipzm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtmprpccer.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfbedjjd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtjvjbdhmt.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtdujpfuoi.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtwmqhpgch.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gthyeiskrv.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtjadwsket.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtjzitfmoi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtpndczleg.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtomjomiua.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtfpcjdqgi.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtgbopww.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtjdkwktrp.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtgnpcilok.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtmeouzpyr.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtarutqrwa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtfqwalovw.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtfeclkpbb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtbeafarzt.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtrmoqkhok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtztbgofya.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gthzxbvswc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtpxbifbtk.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtlzptlkex.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtzzkhproo.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtnzvmjfyd.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gttjcfhoev.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtkrastmyn.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtubzlatoz.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtxlxmujge.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtsmxiduov.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtdqqieptq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtvotrlgqu.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtecbqcelo.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gtsbqlaigj.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gtpnsqhqvn.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtifmvbuoh.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtvomdcmfb.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtgwxlzpbl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gttluisocg.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtmhjuhhpk.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtmvssdygq.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtlhukenkk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtbdrsjbzg.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gtdifrfutq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndcabrio.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtzglnmmst.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtcdwhpxxf.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtcqhkxaqe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtgbccjrkx.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gtpzztttga.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtxzkoerxq.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtvuofjpsr.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtdctmpjjt.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gthaagqebi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtnfhejluk.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gthvcnnngz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gtyjgxdxxo.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtpmrekndj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gtjuhcixwr.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gttdvgfdww.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtopvufqai.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavdqpfbc.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtqofllxja.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gthxlqvalg.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gttckcumtp.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtsejvjmsc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gttbkikmus.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gtwpypzzeq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtxtxzkzgl.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtznnqvfzx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtjlskbytk.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtvfvnchsh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtypccnfma.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtpexgaeyr.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gtnobqdphg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gtkjmtfliv.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtuyupgqta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtxixzxtzx.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtqqgyrbma.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtkcifjaai.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gttjjsgntq.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtcumiuuqe.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyrzptmv.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtssltsksc.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtwpnwizgl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtgrcfjoit.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtbnpzmivq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtvxbjmbjd.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtptzmbopu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtflmmzutd.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gtnnfqmbrx.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtmunqwylq.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtfmvpioqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtfkzlchgo.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtjwkbcipe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtfenrnier.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtbhghckhv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtmgpkixql.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtuqmqvams.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtykjoooov.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgaajiqof.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtdiaszdlo.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgubxxopg.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gtpitfibmo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtxdpmbtrn.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtezlljkdd.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtcywaqmti.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtcpwvgyxs.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gtyioqhszi.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtqubwutcu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtezthhomi.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtrzhzvkok.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtygzfwgqg.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtvwkegmrk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtjiehupxv.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtxcexkydq.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtbzwpgfny.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtezslheiq.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtgnsvjvmc.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtzclypdtj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gtfouroguc.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gturblgvso.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtjtqtuere.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gtewyiwgah.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtonmjuwpy.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtqscseoyr.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtfcogayuk.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtkpibywrt.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtksrmuxrx.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtutasogme.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gtutongvrn.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtqmqmjpit.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtpnebvqum.html


<!-- 参考信息 -->