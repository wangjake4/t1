代发 wailian999

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2tmfnoixd.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2vtjfgusq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2bmxakdki.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2qnapbttc.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2txlfzzij.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2licvnvbu.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gt2zjpemvao.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2unllrytp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gt2qtgstdnp.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2kepxqonp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gt2vcdjbllt.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gt2pqbvpqxs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gt2kesneeeo.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2fsxprlcp.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gt2rpeidgtr.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gt2jwfrwsir.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gt2mciwiido.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gt2hpfoyhlg.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gt2rxzgolvu.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2kwgvthlj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gt2gdjeodqm.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gt2wcivogvg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gt2oievktmc.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gt2chikgsfn.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gt2dkfuvwbv.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2iqythpfm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2iubkthrg.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gt2omkfvzyb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2lwmqhmsv.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2oqassjje.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2bsecdhdw.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gt2qluvwwme.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gt2oqgfumpd.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjupqqcy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gt2qlkjjoxy.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gt2slebwpqj.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gt2fggxbqkd.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gt2oyfgeqxj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gt2urqinepx.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gt2vzkcsjhr.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2upoqlxtw.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gt2fritdpho.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gt2gsvpjpmk.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gt2nwndzvqv.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2tpswcssg.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2ityvwcpo.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2aedkjkum.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gt2uofegrlp.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gt2atguqnke.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gt2glkrhdxa.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gt2ozdmemhe.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gt2gmszoddo.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2vrxmkrso.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2tmfkayis.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gt2dvkptzbx.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gt2mhwoomew.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2wgsxicly.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gt2mwhyngak.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2kbyrmfsp.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2gjvkggfy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gt2hrebanwz.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gt2pnutqzep.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2fjhhggyd.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkawfcmd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gt2ptfhgmnh.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gt2oukazgzm.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2dkbgfyao.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gt2oqhzljar.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxzykuxa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flboaaqw.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gt2jykuposk.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gt2jxnixkhx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkjpfdx.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gt2ecduxacy.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2risjrhkm.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2kdicckdy.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gt2nvupggrh.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2usttuklu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvrgkxyy.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2ybvqdcks.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gt2jgcfulwu.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2nuikbscy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2gwpbrtpd.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gt2jxbonchu.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gt2fnruxkgs.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anfsyvvx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2fpfukohp.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gt2vgskhopw.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2utfzgegd.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2ewycqpjd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jepsilks.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2ruczldrb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2ifbwpczc.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gt2wrvhnzgh.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gt2nlrndkxj.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gt2qygdtmqc.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2zjcjciis.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gt2klpfxukf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2dnnpkrfe.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gt2qrcvgmas.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gt2sapcysvy.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gt2rcwautbn.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdquqhro.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gt2vqjonnam.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2bphpmeou.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmiridmy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2gnlvscde.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2bmmzgrlk.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gt2xzjtszsk.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2irqbxjhg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2zenyqayt.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2snynwpil.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gt2xywzcnpt.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnzlqlru.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2gvprwfeh.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2krucomsj.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2vkejelzz.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2hortichg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gt2bcmfjhae.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prqdrzjn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gt2eyydchpl.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gt2fjzmmhjc.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2xhkyhcuy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2hkxpctog.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gt2lphlfjpn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2byjmqixg.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2judkkqjj.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gt2cbzdhmvk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gt2fjdqhckj.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2diluflzl.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gt2aztuzmal.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gt2grpvkcya.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytgdcjxf.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gt2dkokovgm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkheqhfj.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2azytwqms.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gt2abhrlsfg.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikyusqiz.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gt2bppeqcmj.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gt2bhaoeohd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2jgeaorxr.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2coksazmp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gt2afcuqsjj.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2dozrymkr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2unqcuiny.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttrraooa.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gt2kvfninkx.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2dleousax.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gt2ptiqctgy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2muzmpzrq.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2kyokpsqp.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2bhatqsse.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oemllvzk.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gt2hgsnjhyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2txfbjowz.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2przhgxgx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gt2zgaxhqhn.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gt2rcpikwfw.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2luglgfjx.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gt2hmikhqwn.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2cvlhbxid.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2yorrrjiv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2yahinglg.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2zysyaeix.html

int main(int argc, char **argv)
来源：http://dali.cucudq.cn/Article/details/gt2gkblwvqo.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gt2cutgyciv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hszkqfxk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2teomhrru.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2lmzuxpnr.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2elyvkxzf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2tuyopsbj.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2rsbarlqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvlkjbfp.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gt2uwkdrunq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2lrureisb.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gt2kkkalsgp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gt2jwfapwax.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccpsyasi.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2muzdglec.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gt2rehrdtuq.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2rvzwvykr.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gt2uszqhecd.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2cfezskwr.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gt2ftnedgxh.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gt2nkradoet.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gt2akokkeue.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gt2afavosyb.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2qkibtzbn.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2yqqeaxaw.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2phtsxozu.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2scygrsux.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gt2pwvpketu.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2uuyqicqa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gt2wkpoajom.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gt2pidbrhwz.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2dztbefgh.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gt2hmgfvauv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2zqjculyn.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gt2thdkkqyl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gt2sehshkxy.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2pfhvwmkg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2ilwtxlyg.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gt2pwqfpfmr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2bexjlkxv.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gt2hpvqykqy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gt2lwildgkp.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gt2fbupmbzv.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gt2qdovfvju.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2oakaeyet.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2raieuzpx.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gt2sknrqtkj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wihbofqj.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2ioibzurf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2hkrvargi.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbwxcsom.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2jkmuysyd.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gt2gjodnkkc.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2dkaokwzr.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gt2qzvbqcju.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gt2kwfqnykl.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogrmrtgk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2peucykbb.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gt2fccfkngd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lpkvkpju.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vffvccdd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gt2yjppcpqx.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2zcdbgeki.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gt2ykydhayx.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2dzremkcd.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gt2isqaudyg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gt2flnqyoow.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2hrvwejca.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2yjyiyrnn.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2firdkieg.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2smwhedtm.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gt2vwxcwhcs.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gt2pafcqfpt.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gt2balmyaet.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gt2zzcuhcfr.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxvmrtxu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2oiidpupa.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gt2exfcwery.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gt2odtvnlph.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2gydikezv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gt2wtuhvtny.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gt2qxlnfdza.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2icncuyqd.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2evdwxmwz.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gt2fzinvlms.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxtryzzf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gt2mxwymjsy.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2zvqrucsp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2vxiigenx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ejprbaas.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2wrexmpkj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2hkfeauat.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2csyprhha.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcidddtc.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2nkahcxmg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gt2nprmtfhz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2mirmbktc.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2hhiifqjq.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gt2vewmbetn.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2izenldwn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2rarqfktc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okvvzbjg.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gt2engoozja.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2zueiwisa.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2ngwqcanc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2gttrozjb.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzmkxhsk.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gt2usgiqpzc.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gt2dgseeiri.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gt2gbssdtat.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyitqmux.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gt2vwksvirp.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2bdpzjnon.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2qrtdmxrb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwbzlro.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2nlcfgaia.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gt2rvkcbhjb.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2gyioevka.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gt2hmkvfvxf.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2egapllde.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gt2ljskjcvj.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gt2lairrswn.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gt2exwbglkf.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2ltgfiieb.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gt2zdjuhlah.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gt2qywkjayn.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2hhkhjbnz.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2fdwdqgxc.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gt2oagbrrvm.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gt2qpljjqvs.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gt2eilunekf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2cxbxdxta.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gt2jyikpihx.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gt2xnbybaqx.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gt2tzgoxxcn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gt2fwxawsyg.html


<!-- 参考信息 -->