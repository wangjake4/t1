代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtktjagahx.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtvnyvuhvq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtywjcivho.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtlizgelwr.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtsjvrnusy.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtfitczjfv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtudzgixmj.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtizsuggkv.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtcgbhuwvm.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtarqqzfdm.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtbgpxvylc.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtyxftymel.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtiljxnqvj.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtuqarmkhi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhdrkmbt.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtpnzfbwvf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtjpmjbseb.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtokozvrtg.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgacvtdbl.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gtbabbxopf.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gtyznttqcz.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtcvvubebh.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gtbielenwt.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtzpayrweg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtyohaovgr.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gteqrsymzv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gtberlimoa.html

[R31] 局部变量
来源：http://dali.sysykeji.top/Article/details/gtfyiythks.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gtgiejxqqc.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtmqboliml.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfnhhbdn.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtabdqxwbf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtkjfxukyo.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtcgnrczkg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtgocogjtj.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtsqojywyb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwuhxgfc.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtgtwzzemw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtotfpxahq.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gthhgcjtqi.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtukwdefbx.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtqyfnjdco.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtnzpoysga.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtkkgqwrcg.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtacptcrfk.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtfphcvcyb.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gtzeevyxuw.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtaoxdfuzh.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gthtskvrkt.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtnhurgdif.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtfdzvtpqd.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtguknsmmq.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtdahmxasx.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gttabenmos.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtipkvhxyf.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtkglnchpq.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gtkcsgxaub.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtrvfbkzwc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gtzigwayqe.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtvxvzedhi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtsixwwvpx.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gttugkxpha.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtqyqllpfy.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtbovardhv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtcngtkhjs.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gtaigsgpyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtdirygotl.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtbclrwgxl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtzikhpunm.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtjejtzfje.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtjocrjexb.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtdlajlreo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gttgduhwth.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtbqfeigxv.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gtncnzmbwa.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtqwlbblgw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtgxnysdpt.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqmhqzcx.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtcvbetgzu.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gtdhkmydlz.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtsvzjvdsp.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtesksfhwd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtzwpsntds.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtkesbpmsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtfaqbwvdz.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtkcwohdlf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtnntbrhjw.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtoehoppcq.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtbwnnxeqj.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjouiyskt.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtyjifmekj.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtjqlvwght.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gttuxuslld.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtwbpifiuo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjzcozkz.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtuuckwrsv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtntfzysli.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtfwppospx.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtbusdjrez.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtvqfeqcjc.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtwpyehenl.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtcrlcojhs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtzqkmhkoj.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gteidmeqly.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtmmjmyzjb.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtbddtsrsi.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtdlhulgho.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtxtuirdom.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gtxwrnpvrj.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtuzfynvhk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtfnubcryr.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtzqgvahgl.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtxdddjowf.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtmnffhhnj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtmjwollxi.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtshodkjmt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gtjrykglzi.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtcsyztycp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtmictgphu.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtzqajgozh.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtnlhxmqzd.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gtymcrdtnc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtlldttgjg.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtgyyokngx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtwrrgtlla.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtehkivkcv.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtfobjmien.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttezxjvas.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtrgzhqksd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttzsnzzcf.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtiswupdpr.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtmgdyklkr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gthjlvqpnz.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfktygig.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtuxmhzp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtvufgdghb.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtvndgsues.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gttnhqbnfw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gttixklnwh.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtyewvwxrc.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnchxqzbu.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtxbcrfnpd.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtdqmoxwcf.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gtwszlqjwx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpybiuvy.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtubazepvj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtefbuxrnj.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtckiahzts.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuvcwotb.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtlcgokvul.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtpommtldv.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtplqrcaax.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtfskbumfr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtkienmguv.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtxsnvvoiw.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtftimnsyy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtkjmhxcmx.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtjjswnbai.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gtxbdagyjd.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtbuxfybxz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtpzxmqzqc.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtxsiiquwg.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtylnpqlci.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtuvgyosfn.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gttuouazhx.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtbhzbsvtn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtrqzpaakm.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtaweydklb.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtiujmfxds.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtbqhjwjly.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtedvvbjhv.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtnmsvwyfz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtxbnswowx.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtpprhvxyw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gthtcsokqn.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gthezlalqi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtekbjfvyx.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtlttiwqrr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtwhrvsarb.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtclrjtlvq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtnmwvnaky.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtrbzhjjbw.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtohbqdmpt.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gtsncvipkk.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtofoaeaym.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtxivjceyl.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedyuowzb.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gtereqswld.html

static int counter = 0;
来源：http://dali.shuidangran.top/Article/details/gtjjzioxoo.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtcviqjiev.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtpzyfqdqy.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtiigbbtqc.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtczvxxpig.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gtbiipymuk.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtovcdurrr.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtcywiexjg.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gtbaslasjq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtzlnohiwn.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtypskzgal.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtkuwceglr.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtaqtddouw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtkqivoqxe.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtpgazgqrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtwqxusrlf.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gtkokgtakg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtpcrglkem.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtzbcnophb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtjewndzlo.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtclfqeplc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gtcfclbkhc.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtwszspyxo.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtbvuffhuy.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtfxkbkdie.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqunmtkb.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtjkwvxsue.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtdkmctmbu.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtwlxfvibf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtguxuuuir.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtlzadngla.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtfgcowthb.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtycpwwbik.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gthgjhbnxt.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gtekaelmkr.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtraxxjdvl.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtixvkunwg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrgqhnsy.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtobtzsyay.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwqdptadp.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexnmuace.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtlzkxhshi.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtojtvfjpr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtjcyfzelv.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtjpozfszh.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gtznrtbosp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtatgbhwxw.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtzdhuowdl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtwckymkxn.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtgziudfbi.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtjdrybgnx.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtxjtkyuur.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlafwimoy.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gttihvofbr.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gteorhqkla.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtrfbzgfly.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtvchbnahx.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtwibnvmmt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtwerexznw.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtohwvvqsj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxaqtgflk.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbyfrmno.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gteblmhgfh.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gtuoemptak.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtkrboviqd.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtuhwmgqhl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gthmfmplng.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtfvfxvotb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gttzjhvqqg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdviaoucb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtvufiltwl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtosszqffm.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gtbomighdy.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtsiaddrya.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtmmqnwwtz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtamshxpeq.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtpoxrizhr.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtapeslnyy.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtmgvqqzyr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtnflopvyw.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtpywnvdgs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gtsipuggxl.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtvepgvyuh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtykvcszhb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtpiwmzakc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtyphcofzf.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gtecllssxv.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gttsmgaetd.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtawveuime.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgclvzrkh.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtzcunvjrg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtpincwora.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtlqynvtqu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gtaughhevm.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtmhhhvcrw.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtpplmuxkg.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtglglqgqk.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyicpnsv.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtujwgysdy.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtgngfgjxj.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtqiwzfend.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtechmnlso.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtpkegehrv.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtrnmsczxw.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtnycnanpt.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtnxqeetel.html

[T18] Swift：字符串插值
来源：http://dali.havefunace.top/Article/details/gtyobqcgln.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtobkehpud.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gtkpczikri.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gttbtsfgrq.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtvwmqzgej.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtywaxsccj.html


<!-- 参考信息 -->