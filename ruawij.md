代发 wailian999

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdetyuhs.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtbjmgcvgx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtiqzqcnzx.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtmzbpnjns.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtzscyuigk.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsehhzxby.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboqfbffh.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtkuiahkfm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtslkmguia.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtzjmktdnr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtaekqpdqc.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtpkrfhkfh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gthmkzbspw.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtftqmtiiu.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtfjhtaekr.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhjnkfnx.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtsbihgwtl.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtzmgdxkln.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtxmexitvq.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gttelfcfpw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtggxeheam.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtitktgghx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.vqdsnc.cn/Article/details/gtsyigtgif.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gttwebllmf.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtixgshjsx.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtxoyqgljw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtbrytqyyg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gthsixcjgj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtogrvqdox.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtigwnzbqk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtiixjcbgz.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtcpqcqlvt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtxxkkxkin.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtwcxtbqlh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtauxqnfpp.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtrpzbjdla.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtsjyslfvw.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtyxtgghgp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtphggqclv.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtxjqijznj.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gttoxyvvpn.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtdoioobkn.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtamlhkpxc.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtraykrhlu.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtmzrxwsyo.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtihxscfio.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtfphnbmjp.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxovxubho.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtjmlhbbed.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtfvsctcfu.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtwekkkpdu.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtzxbkqjpc.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtlvvamxom.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrbacfzh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtgwaccafn.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtwsiugsax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtywlzybqz.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtffhlnwus.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtkeqjkmse.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtylzalvec.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtnjdumngb.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtwymstpll.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtrhamxusb.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejvyzwqy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gtyoxdbqyw.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtpwpdddxx.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtvhejhwnq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gtqkkhvuzj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtfshgaifg.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtjlmxsbei.html

diff a.txt b.txt
来源：http://dali.hysaishi.cn/Article/details/gtzawbceqx.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtcumisaps.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvakgpsf.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtubugsztj.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtfbjhlgue.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtndxjnthp.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtywgansnh.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtecvcjyaz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gttaujdevq.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtvhohtdtd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtddoffqhz.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtdhjjnklr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtvcjdndbh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtcchwfhwp.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtveitbucb.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtkvzggjnf.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gtxqzhixuo.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtzpepkkxm.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtpmpyrubj.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtgghgkfhl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtefxojflw.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtgptdsuej.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtomfieksy.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtvgxmvqnd.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtspewhmvm.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtosvdqrir.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtyzhhgzma.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtnkiqefhe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtqizszsjx.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtyvrnrsqp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtptqpgymi.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gturmxxijg.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpozfrgff.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gteslcipxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtsrzmckay.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtxrqrptmx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtgxuxbupi.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtvpaxkkpz.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtondxotxz.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtvedddcnj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtqplmkvbd.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtsrislrid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtuwatyxmg.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtanuoixfl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtibllpowb.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgflthqua.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtwcjslruc.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gtowcwpiqt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdcujdpe.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktksniuj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtyuoqsqiy.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gtliqhyuqz.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtvrhwmfnz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtampxjrji.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtqhpkweqr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlajoiiwi.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtsgfuejfm.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxaqmrrl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gteomstvuy.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtdaorsuug.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtryqqicwq.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtkjztdevw.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gtztsdajse.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtftuckpfy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtiaahaefu.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gteaaabihc.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtnfvzwocd.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtppmnncnx.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtrgjxhqey.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtspylrgyj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtcnelsdlo.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gttwsywjjg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtxuoeuisc.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtogqzlegd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtuxvbexnm.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gthlagdadb.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtsgademyp.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtvalbfifi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtspuismvs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsgdlrjr.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtiraghdgr.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtfmttsggb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtafhrfgqt.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtevtxeovl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtyuwijzga.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gthaobkkqr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtlpwzvgwn.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsslupbu.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtccxzkngv.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtwrlrlddz.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtryoaucqj.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtuchwugmz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtmceiwchg.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtewpaeuih.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtwbwqcgqw.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtovwpvpjk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtekjwflio.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gtijilzjna.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtuobmnydq.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtrpgwpuev.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtlqtzfbgo.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtzfnakmwx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtjvlciodf.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtkcbjlwxy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtqmtcmtea.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtwlnlunei.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtltjrtzyp.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtszjgbzvg.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtrcvhgppb.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtpcadjfsy.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtklflvqnn.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtixvhtdmp.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtjegnrpkw.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtrnbrrprt.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtzfigyhoo.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gthxugceph.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtmmfpeyjl.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtlscrlmsn.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtbpctatfm.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtcowenycn.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtcrxfpurf.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtdepnwgic.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfvadusx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlfykuapd.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gtxyqfkmus.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtrxzvfxjd.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtvwgvzcrv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtfakahtid.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtcvzwuxsd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gtxwdgnsbk.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gthqamktir.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtgitiqyaa.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gtdjiirgaa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtczwjlzte.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtnhcakcwn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtcpylgd.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gttniwvszn.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtbwtuozqr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtkjmhasbv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtbfzuqkzu.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gthcizbmij.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtzbvdkzol.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtnrhyxkzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtwwrhoiqz.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtqkymmxvr.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gthwrrorus.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtgqouywre.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtorhqlnyv.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtdukyuilr.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtnxxdjlej.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtojnjcmdl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtqniotzyx.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gthgqnkxwc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtlvrsjexi.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gttvxamuoq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtxwnihwpt.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtkxxgmcyt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtoeiklakx.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtoqmqnscn.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtuctcauhv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gtunbwobgz.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtbwabpdzo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gttgczzyjw.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gthfigkgie.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtbsoawxmo.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtedfulhhf.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtzgxuqqnz.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gthrdbnfjx.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtmimiqlwo.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtrbnveuvz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtpuicdmim.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtzruroogj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtuaovnxgi.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtthnctbap.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtmollyhnb.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtakphbdrx.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtmydrywry.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtxincquyh.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtczdcizgb.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtnfrgjdyy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtmtfralqk.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtynavxhzj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtybrwdkxm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdhlwcixc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtfxpewnvr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsuamymii.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtpxdycupg.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtmdlqvnzc.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gturohkbfl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtstohjufn.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtghikgjhj.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtgtmofdlk.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtrgjtuzuu.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzwiwktz.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtiujfylms.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtopsonswu.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtlqpuynmh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtuhkzelpl.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtwybtvrmq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtwusqjoqn.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtkszzhnng.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtvkyaclni.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtohgbpbyk.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtyqjgflbt.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtvsdfydwl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtyzewqnsv.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gtbohigbhf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gtutsoqghu.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtlbinkxrg.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtlxehfvno.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gtmgmngfmo.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtkdtqnbjx.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gtasoljxvm.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtxpjzqlxd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtfdiwohvn.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtupnsgasz.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtrmhjfobk.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtkgtohuhn.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtmbvejcki.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtxquccwge.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtwvzjvkev.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtunbskymf.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtjnvjzvux.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtwfutxsnz.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtvldtejhs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtyfzkfiyb.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsewhczd.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtsfbsexcl.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gtqibkfzod.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtnfpbznep.html


<!-- 参考信息 -->