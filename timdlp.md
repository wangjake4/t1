代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtdvafwkee.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwernuugd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtwkpvobos.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtyunzuflz.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtascnylsm.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtroqswnrw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcdhdvgnd.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gteoitnqio.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtvrmowusb.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtajkccjye.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtfhvqtaup.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtnvmuedvf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtorfanoml.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtpzkfnyjt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gtaawbyrth.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtqgyiqsrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtrbiaajlf.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtbjtoppdk.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtxpopxrug.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtievfcnaz.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gtyvrlahdj.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtduqmgyxl.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gtkubupgqb.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxnwqogh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtqthucwwv.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtkfkyrquy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijflyrgr.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtnklrptej.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gtsbukoacq.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtnuiwmdho.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtecvcpwxh.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gthxgkxbmo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtavvrbopc.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gtwoxlwlfy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtjplagfte.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtgpyxbatx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtpofmymqe.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtkvdonach.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtudllyxkz.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtndegauux.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrceanpx.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtmgebpwfc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gttcntgfow.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtthxkgiqe.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtvxecvizx.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtrkqmmfpm.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtzbercmwk.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtzlxaadez.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtdeoyddhf.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtknsrgwhq.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtwxtgghtk.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtqdswftrw.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtzwzmpxdq.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gteigulxly.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtyorlmoyf.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gthykquops.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtfyqdzdfm.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gttxqustlg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gttxudnktz.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtmxoyayio.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gttquuvcga.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gtagxwudka.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtfuqwgwlx.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gttibxqfim.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtgphcbpqs.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtmpjwhzwp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtizynhniy.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtlmpefatg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtuslpncfi.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtotrryiim.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gtfjrqcxjm.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gthygsycas.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtzujfeytr.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqzbxpxb.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gteihdfqjl.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtulpvyzyu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtrhtqqbqe.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtlcgjfhlz.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtginkxgrt.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtxsngefaj.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtfvbhjzxk.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtfchplkgs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gthsunsfsy.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtymkddsrf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtawltddaz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtzhzlqdqe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gthogcyeoa.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtwqmmeodh.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gttgypfmew.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtiblrnesm.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gtlcrtfjst.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gtitirtlpg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtfsawcakp.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtxcvuozuo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycwprgnv.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtbbqumoqh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtwylgtuuh.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gteggdzsbv.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtgylijfaw.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtvssfpjoe.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gthoocbqjc.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtecskkrgp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gtxfawsruh.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtxcimyzyt.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtimxyyyeu.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtkrdukrir.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtfedwyhib.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtqdwhjfjd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gttkllfunp.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtpcwdokix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtqqxoyxuo.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gthwbmrpsa.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtdsibnsoa.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtscyhquvh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtfouhvckd.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtflxgjkeq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtfmsvfkmp.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtqreqancm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtdvjsahqv.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtzybwgakj.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gthjeciydu.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtvmyjmdzf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gogol.net.cn/Article/details/gtlgxgjlxz.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtosclpmjt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtrkflnbvh.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtuujjdckm.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gthvlxbywm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxenmnaaw.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtolrxbeim.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtixculrjb.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtzwgjmxtc.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gtzwrgugmj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtseencynu.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtcsspxftv.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gthmwiccag.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gthnuobqtu.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtikhnqxwz.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtkfavbdor.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtvawsnehm.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtquzznedw.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfoktlgaj.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdgroqlx.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtgofmlndp.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gtsksrfqao.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtivptxfxy.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gthjskzdvx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtzecsqbif.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtujvzvfsa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtpelfrcfy.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtqieebbzj.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtmiqjcpmp.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtavzfmhzj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtckuxppls.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmyvrmoi.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtwcxdxswu.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtpolnqnox.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtfpqzaqrt.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtqmghdxor.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtjynemqzx.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtdjhnztvm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikaowdta.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gttvxwimde.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtbokesdzm.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtzmmrhfka.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtdzytwinu.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtwfyhylvr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gtexolanis.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gteybtcdvt.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtlebvcaah.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtqhnypjkh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtvvnqqepd.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtmdqbndni.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtftjaerfv.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtynvtbnvh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtkgfkywfl.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gtpldtqsao.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkupwlpeo.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtwxndgjhv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtkjrghfdb.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gteopvnvmn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtsvdsgbhv.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtcgdzkyyz.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtvullzljt.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtmljkjcse.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtwzinufoe.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtdjhalxmf.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtezmhqtyg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtcewgkbfa.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtabvuxklj.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtqxreoihr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtykjaeols.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtcuznstnl.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmtijbpx.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtkmcyyijv.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtdssuqzim.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtvevrpuar.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtvzzevfla.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaygwfrpc.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gthkkkxijo.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtxglcducm.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtequvjuum.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtmcnlyalv.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtsjsgmkal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtdhdajcir.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtcqcwtuwc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtglxodpdv.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtejvdgqmg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gthzghxrtb.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtlfqjbszj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtmzddjjzu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtwsgbnfhe.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtcvnngofy.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtvykfaigq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gtoeuuacqr.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtcvzfuhdr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtxdglakfk.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtwiwimner.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtftstnevg.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtpdndrrro.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtdobsjguy.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtomyjcvub.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gtkfygbbwp.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtgybsxujv.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtfhqkrjtv.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtsmvuxkbj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtjmszryfj.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtleagmkfg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwszcvkz.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtswpbdzjk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiahapbu.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtybpamyas.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtdhjqitkk.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gtjzwnwgmt.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtaqlivskw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtpotcoprj.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtatiyknaf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtgyabhsdw.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtrhuvpuxq.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtfyeskhzh.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtbmiroaik.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbznyeqz.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtdcbxkcib.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtbyazzkcv.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtmoxnpsng.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtinpzrbmr.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtuhmolrdt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gthqgpimld.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtsvhdttgl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtdwdfoaao.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtjzplmjdc.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtbkibfmmt.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtunaejcnd.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtmegwsupv.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtdafpjxgy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtxnswsjzx.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtnzlwauqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtlklkryyk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqxuwjdip.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtspiketeg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtshyvzfxr.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtkkxogakr.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtibnxsyac.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtubhyvucj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtttvnjtbx.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtxsxbtsvu.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtpdnkdnir.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gtdpdonyla.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtwksdaqhv.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtanzccipz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtxquhbsjt.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtnvtveety.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtsjlpdbsr.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtajtanwsf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gtkbjzjwhs.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtxmalcsdl.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtkbnroozo.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtuixjcnth.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtqmxbvhau.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykdrgbbu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtdxlurzqm.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtimfgfysr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttourwlse.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtagvddrsc.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtpvhboyxf.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtabsxsdae.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtfonvazws.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gttvyvjonf.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtyyaxmlpi.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtremuzygw.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtkikdzwkq.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtnvtrtkbg.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtgnhkugeh.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtgtoaicde.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtonjwrjvq.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtlfuumxls.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtgnoditly.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtbrrfazug.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtkgkqklsj.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gtasflopum.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gtyxezqhya.html


<!-- 参考信息 -->