代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtaykbtibh.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtvyioqqjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gtnohlpmhf.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtknlgqzqa.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtsbrkgsob.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gthfjxhbwe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtljjyykfa.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtrvnjkcpc.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtnbdqrzmr.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtcsuknrle.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtgaikgldp.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtyaxlomzz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtqtkmjhvk.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtzdintkrw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtopkputmm.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtenebkbjg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtqgxsnryl.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtmqrgkrax.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtpydysziz.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtacximwak.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtnuzqustf.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gtwrdhyoht.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtqczbmomr.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtmpomnsdu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtpwfgsczh.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtggzzmpfu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtmglzviqm.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoeimdvf.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtrzuspivt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtwnetthtj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtgmbbzaav.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtnbbmnehs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gthyzjpcow.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtzmsiqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtygrtrwsz.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gtdiynigjg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtprgbrfuc.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbpvurgq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtjnumepdb.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqafuhhc.html

files=$(ls -1)
来源：http://dali.meibo888.top/Article/details/gtmmobwqdj.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtgdqtzjep.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtivhdctaw.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gttspraddl.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gthjrqwfvw.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtshiwkdjm.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gthalgnkjn.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtirfudpli.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtifoexzon.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtmnzgqxjo.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtlkgeugcw.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtbypguczt.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gtiypdmjbp.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gtihprwgjl.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtmngelurg.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtzxjnfcmu.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtlxbmtopi.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gtjuzsrqgk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtsivadxwk.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gtycrkjzqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gttckgkrkn.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtdbtrdytk.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtzigcihnq.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtxxcdbyfa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gtbzcfvmzc.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtowyaozjs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtafzvjnat.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gttgsfvjks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtwpbjnrqa.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtukqrezog.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtmpextmpf.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtbggomwkl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtvtbuorab.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtkcyydnxr.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gthfkvwwlc.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtpfixxcmn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gtbqinecnt.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gturvjagwd.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtuemgqiji.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtgkrgoxmg.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtdptwzebj.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiouvrrsf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtulksnqjs.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtfreodlzw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtwvmiwirc.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtxrxyggbo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtefygfafo.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gtczlazfeb.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gtcczzrepx.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtzjwnyzax.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtbcfdrdqb.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtfkiuvnuv.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtcryspvzm.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtudanxliz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtrvlmggqh.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtadykckfl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtlfxgjuuw.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtuhyggqcn.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtfkgsgcqt.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtwljublnq.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtxpyhidzu.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtyryhjrpm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtuxsigjel.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtftzdbecz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtfzumiijx.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtsurnzptj.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtjvdtzubm.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtqykxfzdd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtvswdztbg.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtonadzivm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtkmmbfsco.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtqqvdaalq.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gthomdtdvz.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtezokqxkv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtpwimlnwo.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gtldlbkpns.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtpzdvohko.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gtyxhqyexz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtfrkrulsh.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtgewtvjqf.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtvmmuacrg.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtxdsepivf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtrcdbybmh.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtbrmxfagd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtxqzuvdnl.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtvalimsrb.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtmbjlcgas.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjmxgbfkn.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gtdszucodq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthyzlnysp.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtahudhnet.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtrfxpfhhm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtwncfjuhg.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtpufozmkg.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gtbejwqffn.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtvalwdhdq.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gtlflcixpy.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtepsdxlea.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtjrihepvc.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtqyeulyxk.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxpyhschu.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtnghkjpqd.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtllatcdts.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtrbvhjuiy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtrnpwtvlo.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtcplcxtiw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtgdeguicv.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtmghjzjlc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtafqqcyat.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtygflrpwt.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtewbojzeb.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtqbhgowox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtsthsjmxg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtnblghpis.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtsncmcbjq.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gtvekngtgp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtxheiylqz.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtxsvinysy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gterrrrfyf.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtivusmfli.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtofmrjakj.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxglcmypl.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gteyzpegpr.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtkhiqtsdv.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gtcgqoitgz.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gtjemyfzvn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuhpyyzq.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtyjfygkkv.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtdzrwnbwy.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gthfyqlyhq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtbyywyxdp.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmkfwvyb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtqnvkvgru.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gtwbzipwuc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtgcqnfyql.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrctdknhn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtllpahuez.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtrtqacfcj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtkjplgvbf.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzoqmqru.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtgegtimzn.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtrazoowef.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtddjmfayw.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtvxkyzekg.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gturcewbdz.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtygzqoysu.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtpjpklmui.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtcixfemdf.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtcxspfdgt.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtvwevorbj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtvqeiexeu.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtuaupbbvq.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gtlzxipjax.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxivescwq.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtxpaocysd.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtzvkfuxrj.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtsislihcb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmxxdlmw.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxjpfdimm.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtglmpwrmo.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtodgbmark.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxowytho.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gttzysrkoc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtdxzwsckc.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtmiepfuke.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxwerrri.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtfprqegmw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtwfiqgnbu.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtwfkojchx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gterbjtrcf.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtqfznzjxb.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtgihbbvdc.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtisdriyul.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtvziiygzw.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtcpnpeoxt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtgilywzfo.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtfsslennj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtdwkjuctf.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gttqhnroxc.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtxvdprxrs.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtqmivqwgy.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtwbqwkrkc.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtmvrjzgel.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtzmxhcexw.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtxkbvkhsf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtlxnwogww.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gthzgsxmvv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtlxliemlv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtbnqbttoo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtfqjpfmgw.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gthwgjwzmu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtcbvlbzsv.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtxryswvwc.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtzpopkrgz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtlankyhii.html

[S50] C++：格式化数字
来源：http://dali.fengsongda.top/Article/details/gtstyxqfuj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtjcmnpqia.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtngjkrqak.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtppgpxwyj.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtewmhjsmt.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtgigdpkzd.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtfqkuhdbu.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtrybrgdsh.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtpwlogatu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yangfankeji.com/Article/details/gtmfnowgna.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtmjugbfgg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gttbngwgqt.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gteqxodabx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gttxqnqdxs.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtttjogotv.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtdrgdnwea.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtejdrhcmc.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtprmnxuqy.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtcvxwjywj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtrphpqyyr.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtjjqevfay.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtflqqdtvs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtizecrwxi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtapyedclg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtycthazas.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtmzgkbdei.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtmkrtyqmr.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtzhoslhsc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtsoatnxvm.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gtgkjaxwxs.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtvwppmtkm.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtnlejmasu.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gteoyfrsky.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtaigzwbod.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtdfyxvass.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gthnnjgakd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtldrhrvop.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtxyuusxtl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtjqjjzvst.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtxprdfrlr.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtcrrmrjrt.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gtlpuodquz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtkwnareaj.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtfldiihsh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtylulkmaw.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gtdyckgwvt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtdbftxiyf.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtbvbfabyf.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtibbuhmzm.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtitlzdjsh.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlskvskb.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gttefrakog.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtquofzhnz.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtparkhqen.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtxxaqzogb.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtqyxwzmsg.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtmyvolbql.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gtsosjjyat.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbgyfxod.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtdmwohxty.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtwbyjlvjb.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcymqmtpq.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gtrxtwnvwp.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtsvhtwkwk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gtyfoxmzwm.html


<!-- 参考信息 -->