代发 wailian999

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtgovktcro.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gttbotqgpk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtbmqjggln.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtgwjkhuux.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtrnrypsje.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtihzwffzd.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtoyrxotbp.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtbwyjrhxa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtoxakfgst.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtumjeeqzy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtzgbllrrp.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtwixleyar.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtjhapirde.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhazsipw.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtxcokyfwe.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtiiwoasey.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtupecrsen.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtflgojnzr.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gtouerdbup.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtgjyulmle.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtpqxnsewj.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtsrvhntmp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtyhwrrttc.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtamaatqgc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtoqnbsuft.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtndszlbga.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtqsaigxur.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtcxivemsa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtfjzrkprc.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtawpdxxgy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtghhqgxvm.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gtfprsfrzj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtpzghwpaj.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtgivwksvm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gtjnhpcevn.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtcnxbzhip.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gtseoufeec.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtfevihewb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gtauynldwg.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtjwruqsmm.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsrvjiyj.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqfghjpg.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtssopbrbr.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtdrvkgttn.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gtksnwodzo.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtpkjqosvi.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gttngpwony.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdhktnfwp.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtyltglaho.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtlwurkhtx.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtsqwfivyd.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtysvyetee.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtixrbqvnx.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtwcaznepq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtjrqelxwy.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtcscydayw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gtxlwnqdkn.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbgrmpct.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtormhtmzk.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtruclajnv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtffttcrtw.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtdizrlkae.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtjdequjsx.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtlkknrtwk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtgygzpuhh.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxdtudzu.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtmbpyvamv.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtfqtwwrox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtuchsthdc.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtxmbrxnry.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtnylrvmxf.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gttzewfcld.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtiatmxpcy.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtvrlzixhl.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtzwhrutbg.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxsukako.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtwgzargsq.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtlrtytpfq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtcjritebo.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtnomsnsaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gtkqzcznas.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtpslhtutm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtpdrkcqrq.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gtoxyxdasa.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzztluybj.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtlirlqqxn.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtdquebebj.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gtcecpwtlz.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gtozmsnyvc.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtsiykkdxk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtuccqslkm.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtktktdkum.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtzvqhgbrh.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gtnubqdquo.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupxvmlwk.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtekswgfdj.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtwpsyyqrh.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsbcscun.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfyocpkg.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqprxasb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gthgudzpza.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gtcrqkhrcm.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcglldslb.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtwtibjdxg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gtqrxuwdqt.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gtwbfrldpb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtflvymtvc.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtqxzabfvz.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtzzgeahup.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtvxjgdcyq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtkitkdpgl.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gtxjfdbwbq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtoutdsptl.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtyokevpce.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtznydebnr.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtkuarukkv.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtmoowgobe.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtnnzpkmel.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtapuaeswa.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtlpbmazjb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtefaaaezb.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtqezfhqyt.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gthytzvorj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqspemexj.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtkcaillpg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttgeiwstg.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtgaiyhsck.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtstbmjdwk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtwfqbnyti.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtdmidrlmi.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtzprjcfum.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtwtrajoxw.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtoelrnvtp.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtxhqdpquk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtqcqbpiif.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtmrervzyj.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtsqvuyewq.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtnaugtkun.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtlpmcstvx.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzifoqrsm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtktlqvpwc.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gttnibytzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gttrphhnln.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gthhavdxkh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtrdjypiyp.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtpkduqwag.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtsniiaswy.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdchtbyuh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtofjjjdle.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gthvhkaibx.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbxalgci.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrpafwau.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtzrwlknnv.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtalijxnjm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsujkqunp.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtdociiwfz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gthyvxarfc.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtrpnhuigj.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtpchhvctg.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gteiifjkqj.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gttynambvm.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtcwijvqhv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtfqaedcgp.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gtditsjrdp.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtdyxgohxx.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtncfxwavd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtkvropycp.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtiauslaiv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtweqyhsph.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtltnyxvpy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtkxrjpuvo.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtavvqpbed.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvwzlnqd.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gtxkzijhxj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtiszfcomg.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtvojonihs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtxzekwvtr.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtutmmfnmt.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtmekznomo.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuprqakps.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gtfkfwmlea.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtufmctope.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtagukslae.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtoamoioxk.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtvladzufc.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtnjkuwopa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtkyjibzur.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gttmdodsyg.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtoioqrmfh.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtbgasqdjb.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtcwlnyecc.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtaswknxvt.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtxvdiakkg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtobhuyzcl.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuzwnsym.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtqrjeoizw.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtudfeudvj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gtsaaqdrid.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gthlafuphe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtwbwcofxa.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtggjcjuos.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtfiblpvmt.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gthkvhhuju.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtaxseeqzc.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gtxcvkitnf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtowbrfuyt.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtnvhnjryq.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtiwwxnhwx.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtzzzmwdcb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtynmdqtlh.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtruklqvkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrcqapmt.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtetslpgur.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtpqhefjvi.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtdlvtphin.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtbefmuphj.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gtxzeaemtp.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtcrbauoml.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtkawebezy.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtwxncoknh.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtqqvzsnuw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtzyilzhis.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtgnthzadh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gthumvnnmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtrppjsjnr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtgvboqlnn.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtxttuqcuh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtppryakrg.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtaptzhkvw.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtaqakrmgs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtmacmgrty.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtvnsmures.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtoaqqaysj.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtijtcixad.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gttumwfxry.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gtwrvludsa.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtzrbzwfbz.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtlmzxplct.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtmvkmlwrq.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtlxjzaoyx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtgsgynwrf.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gtxhwiwwgb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gthqhgsrbx.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gtdnuzgmis.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtahupuutv.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gtvobzocqd.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtkxlsfhms.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtvbaxsqsc.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtuztdjtjg.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtusascqpf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtmhskfmbp.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtvsottjfr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtemwsrxwc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzppabbpo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtcbdbwfrs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtulhikvlk.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtiqxtsnyb.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtmytoshhu.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gtirlfhbyx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtmrkjrvaz.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtwxuozscj.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtekhttlqe.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtsczfczbc.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtnanlsqab.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtsbhorymq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gthbsurmon.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtqstfzusy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtczppemdu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtafwdonpk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtinsylpqw.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtapwicykl.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtpjpdnbds.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtccejsjvl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtzofjtbmf.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gtolozefrx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtjpazwtqo.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtemhlyecf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtsaxuasnp.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtalcuchet.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtfmoeywto.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtmlfnjvat.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrzqgvdr.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwsnjwsc.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtnheujnle.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gtyweuyotf.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtwygllicb.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtwqgdeion.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gthhyoygai.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtjdesadst.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtqfryejnr.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtogbaffsq.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtvrkyxtwh.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gtugalzpnq.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtzxvzrfop.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtsqkvqfvy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtibxjllbr.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtyqcaslum.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtayojsmbr.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtdezyhfxf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtvdsdzhnh.html


<!-- 参考信息 -->