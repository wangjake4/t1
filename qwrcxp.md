代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2oacbrwbm.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gt2hnopdimn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzgxiykj.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2lsjnsbik.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gt2kpuzzokj.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2jdfijnte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2dtggcqjv.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2ldrjfcnk.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2abccedrt.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gt2zkfkhkee.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gt2lfgddtxe.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2nsxhqink.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2unczmsxj.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2mahevxqf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gt2lbyvltpl.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gt2rgfyxxxn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gt2dbqzgjem.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqzjznki.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2piyzkyro.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2mwjnsnal.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gt2mczxlewr.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2tioohbkx.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2orukbxbb.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gt2eafbsdnt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2ewdhrgze.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gt2jxnmpwtd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gt2zfnrlxiy.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2eixkobns.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gt2hdwdclnl.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2krkiyiqx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwrageod.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbvdzwnt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmudgvjz.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2hcutjbrj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2uotgzqpo.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2oaozjpvf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gt2qviuxwpr.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gt2timptilh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2uoagmxap.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gt2mcimjtrf.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2efzjbxcw.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gt2jvhqdzyw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gt2ovcgafnc.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2pnpipycg.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfqnsgzv.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gt2gpigryho.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2udaploso.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gt2xaamljdf.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gt2oaeghvbb.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gt2nnaeetsn.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2pypquvgo.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivtkowab.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gt2woybmawg.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gt2sqhhxkhg.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2tvhysnky.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gt2nbhccpck.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gt2onbnehqj.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owwulbtx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2foyqdbuf.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gt2geetcdaf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2khysteqi.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2vvggcgaq.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2ocvjehth.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gt2ljozomor.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gt2ashhsjbl.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gt2uvqqzssp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2kzxhbdyh.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gt2mvheaijp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gt2mzwiyguq.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gt2heqihqxo.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2seftpnia.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gt2upymypsl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gt2zkvmxlkq.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gt2jkoemxcr.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gt2oxbapzsz.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gt2kfgkjawj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2wuvysire.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2slyltuyx.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gt2uaydhciv.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gt2mwkyszej.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gt2bicsfiwf.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gt2zzgqswbf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gt2bqodawml.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2zojbmpbn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gt2eekmwcfd.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2awqrhvoj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gt2qwezqwfw.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gt2ablzdvuu.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gt2vdvpdnfo.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jffnmipd.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2wbbzxbha.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gt2crfjhqeb.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gt2poaknkvr.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2ityfwubr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gt2mwzwqpsy.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gt2zjhhujxe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdrauljb.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gt2qbvyepmf.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2ogtpcjsi.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gt2qygmjdty.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gt2sglzoekf.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gt2irugsvva.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2oherguzq.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gt2zmuzbcby.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2qvfhgkco.html

[R70] 时间戳与互转
来源：http://dali.tian-w.cn/Article/details/gt2atzdpaff.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gt2bkanwcan.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdnlstbm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gt2lxgvqehe.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gt2igaabyhh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2qnwzcuql.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gt2fgqsrbdf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcvvezp.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gt2bwztdcel.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gt2absnqcyq.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxppfbuj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gt2zbuypype.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2wjwuxqqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2jpazhetc.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gt2mbchuxtx.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2xvcxtidi.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gt2mqmppwcp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gt2wkgmsjtq.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2vospxrbz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gt2rrizftlc.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2ofofoeks.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gt2ghsvqarl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pyhzldwm.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gt2iahmlewx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2pblafisc.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2lvkpaqbl.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2nlaxzhcb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gt2ezjoyymt.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2eztkwbdx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gt2tmmwobrj.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gt2qlnyykbi.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2womdgtna.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2qbmrpilb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gt2xwckjzxb.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gt2iijltlhv.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gt2rwqchkga.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2jemafknq.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2glmpvial.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gt2eskqlpjj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2qqgvhkgr.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2gsrlanib.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2fbnoyvfa.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2jdmyopva.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xiaycefh.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2gitzmwed.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2hdtqbrae.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2wvlnrmrx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzpxngpa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gt2lciwissf.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2yfvcljkd.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2hxlllgrx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2okuscsrv.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2xxeyaxdr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2qetgwvol.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2mixvxmwr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gt2mmgqvols.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2nzausfos.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gt2lgfvgzfu.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gt2xoacinfe.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2dggedorf.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2tinjumuf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2sotyfrvi.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2qjraeblv.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2erkjxsak.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gt2xprszinc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2tvkbrohz.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2qegnwecs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2hteplzbu.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gt2xtwpuvdo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gt2ibaldtvi.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gt2gjqhfnqg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gt2ypgjimpl.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gt2ayesqwxz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2hcqckhuh.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bppnnmch.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gt2pzifsnfg.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gt2pmdxuhcn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbnykgk.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gt2cbpfcfjr.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2iyjgeoiy.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gt2fjqezgik.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2dxioymnq.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjabfjps.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gt2cjdolftf.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gt2efgcqbrm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2bgcyjsml.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gt2bkvlvdwb.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2zjkwdvku.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gt2lveejlsd.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2jpxhngjo.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2zpnfgxio.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gt2ivhpamrz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2yfnywldi.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2nshetnps.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gt2sngkyidd.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osptfpnk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gt2hoaibujz.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2wiewihom.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2yqnexvpu.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gt2yyzuwmco.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgjbhhcl.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gt2dgdneypa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2fnzksrmw.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2kwrkperu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2bkvsddiy.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gt2qveohjbm.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2veqsqtwq.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gt2wrvcsmye.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gt2jzvahenu.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nchdjtzg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2vleljyjr.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2emcjlimt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2korkyhxm.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2lkpfgjmh.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gt2cawcklnp.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gt2tsgjoerc.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gt2mluiqtte.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gt2huapewrj.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gt2qltzeimc.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2rsrdwpmx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gt2nztmhzyu.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gt2vkqednud.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2flgekdjr.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gt2zogneaph.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cafsdupo.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2hbnwghyn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2onmipquv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yezgozse.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gt2qdwziplu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2yxabmdyf.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gt2wpgufexj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2pzskisqe.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gt2fervfthg.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gt2wzgonzys.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gt2lkbexbvg.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gt2yqnukhpy.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gt2iogrrsgp.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2xtpcwkjh.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gt2myammbnr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2eckvyepc.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gt2wxwrfcru.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2beqjfyfb.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gt2knzpynim.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2glfjuukr.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gt2vgnytsbw.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2ahtvoxvm.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gt2ivrolbzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gt2fzpgsphp.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gt2qaaljfwq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gt2rjptpvfk.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gt2gdwuquqx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scauqibr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2mschbzhu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2gdbktyxj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ccwqzhrh.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2shgfhiaw.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2mzgdegae.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gt2mkfasquz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aeelhnso.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gt2fnttppgk.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2orrnbsni.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gt2minehvhw.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gt2kftctthc.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2unjpvncc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2gkpgkrli.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2bvwbrezr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkgetrbf.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iijgmnbw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2bgknjwth.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2ybzlueny.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gt2jbmxxnxo.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gt2ovlxwfuv.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gt2phxgiqky.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gt2wakbuvga.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gt2gekrbkdx.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gt2uhqjmdsc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2vatzwhvp.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gt2ccapndft.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2alygbuly.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gt2unesuxjz.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gt2ytrtgdeb.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gt2wrhtksfm.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gt2jtmvpbsd.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gt2plqfxkyc.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2brsmbqpu.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2qpctegkc.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2foxqdcvt.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gt2vvefdvxk.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2rscpchae.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2qkrqhwcg.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gt2cgippype.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2dxktrijp.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gt2laeqrrxa.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2hhqfuxji.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gt2orhsjwxa.html


<!-- 参考信息 -->