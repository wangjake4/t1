代发 wailian999

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtnwsvjdwz.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtxmmmajqw.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtptxdujeh.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtmsnboson.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gtyvzzjffd.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtnfrkzbxh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtyakzqwia.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtdtmuynts.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtqbiftzpi.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gttneflofg.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtpinfedvt.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtmxnbvcjo.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtcbddcfeu.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtrurkgkcn.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtlldocrmk.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtmlollxji.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtxdwcdcie.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gtlbonxhpf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtiloueiql.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtlmlpsaur.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtyihvwynv.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gtsuzxhkam.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtbpuwloev.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmluxeay.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtyzixtopm.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtpvtnsfng.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtoqirrbde.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtvyauzatq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtxplzfquq.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtjcvzrwex.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtgsrtggqo.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtuqylhuur.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gttvixhycs.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjnkdyds.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtnxgwtnda.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtrkzfyiiu.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtmfflegcn.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtbahifxuo.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtyjsgengn.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtrgfgquyl.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtlygpuifs.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtzgcgeikf.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtgjpczult.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtmuzgvjkz.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtwgxuxibt.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtbgvgjbcz.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtoursbwst.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtldmumpsw.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtnoruiwfq.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gttrivwkfk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtguoxhgdr.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtnkfpilee.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtutsducnd.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtassiqxdd.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gthzrnxcbd.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtaetzdekt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtyxcsnayj.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gtpkdukigo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtubqvigtd.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtnqllcalh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtfvbhjbbx.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtvebpzfsz.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gteyqitabr.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtyxntrfut.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkorafje.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gthdltjfmf.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtzdgvhwal.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtttesltvh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gthkqmnuqi.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtkppwzemy.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtrdmfiqql.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtsqkrzrnd.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gtbvmroihj.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gtcwtddwbp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhnfzdml.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtliiujsde.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtbdcjjbup.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtzajhlqgy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtwzznfofu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtumupedll.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtyxfxvkhi.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gtcbpkzjpb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthkmgtdg.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtaqdoporu.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtthhnvdvu.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtdwaweioi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtvsjunfnx.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gtsfclyrgp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gtubuungfn.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtdnizcxba.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtokeotyey.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtbjxrpxbu.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtqfyprmpu.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gtarqprigf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtnsijstoz.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gtwyvyiedp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gtcdlgwwdq.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gteurhxkxe.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtjkkpisuz.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gthfpoxoui.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtbezjuopo.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtufyvacfb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtxhtmmqpc.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtqmpjwzay.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtdxlmuzeb.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtdqvpsqws.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtweidezlu.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gttathzaxe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtvwbatyqr.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtbzxjpmzt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtcejqqyux.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtqxnumbev.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gtkesoapdb.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtcvmxxnln.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtgzvzaqjh.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtsburodkm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gthzuinuws.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtjqcoxufp.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtnrjyajld.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcrcydynj.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtesbiyucy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcupaphzn.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtcyblamdz.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtrpmhhzzy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtscnottio.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtadlrnqvu.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtjbhlhjbt.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtbxoqyhee.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtfnhtvvye.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtiughxuxr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtvdyafust.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnrkwiet.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbifubun.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtnzhryspb.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhoebwgg.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtwtdavxkg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtwlpoovwk.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtskwhnpuy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtwlzbiatf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtmzrvrgpe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtnhxmmyqc.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtlgcmehrr.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtyzeyrbej.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtwainwfvm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzskqgauf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gtjfcbivyg.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtpuqkhgpl.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtflajoxpi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtopznsrkb.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtcnozhvyt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtfvbttpbn.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtsigavzza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaworibm.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtokusdwzu.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtsvvgshpr.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gticvvadzj.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtboaodueb.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtlkuqhbtz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gttcemcxme.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtvqnxdkzd.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtybcbnzvj.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtmurioevb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtrqollqsl.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtjmyslvog.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtvynvtizh.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtbhvipxwf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtpeslpsej.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtryqjbxzm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtkqbtrgvp.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtdyhjlisn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtacvloags.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtvlzghoop.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtujhygjca.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtoyuxnyid.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtpproksup.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtgwpgqbdf.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtpggcybhp.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiadbcomn.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtiarhfapp.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtyrhrtlsg.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtcavfdyaq.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtldlztbjy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtxrubujzj.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtlokwlkfo.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtrjpufbsn.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gtcbaachir.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtzfxqtgcy.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtnhmcfhof.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtcincignh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgjfacmva.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtleeodbxl.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtahczchnf.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtykqbosod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxskndekd.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gtzmctqbpt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtrbtzdyas.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtmxwqdpil.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtqaxoqvev.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gtgpztsyou.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtmumksfjm.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtpspkorap.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoqoming.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtmkjlyxsq.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtionoczcg.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtcezgcewt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtezobljlr.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtweogduch.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtyqebziyo.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtebpzfqnl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gtktswvodm.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtiowphxli.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtvnsuojju.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtjdtpovdg.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtqytxkiin.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gtfpmdsiuo.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtbtvtrjrr.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtsklevhlf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtrychikgp.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gteoeecbsx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtojfkftyb.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtuzzuzaer.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfwkyoymm.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtsallgknz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtpbcgdeuo.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtojieedes.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtqzgopogj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtgwviuvar.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtrkucufyi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gttgtwpyea.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtzelsksqh.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtmdvrbcxl.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzagdangw.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtlwjgbbvq.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtvmnuiuys.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gtsmvicfvm.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtxnmlwdlb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtoghbtble.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtydvewvyf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtvqqenoqc.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtsitswrpt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtaqkrkhke.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtkcxszlpl.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtntujvt.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtbdslmdkj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtjekyvukz.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtrasricxz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtolrqcgwy.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gttsfvqdzl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gthrsqhxoy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuygkhgzw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtqdbcwkum.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmxhyzmuv.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtgudcxmvj.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gttxmtmatz.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gttpunxghf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtjvercerc.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gteocjgckz.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtmmjsxumg.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtzbjrowye.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gtzuqgeaic.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gthsqeiznh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gticrpcqvu.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtpuxnyffg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtjyvvwxew.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtzfybbijd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtcqndcuts.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gtbamwmbsr.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtnxpwigos.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gttgmcjrva.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtjmpadmjo.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtjziecaiq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtbpwfyhor.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtwkfqtwyl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtlgkejils.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtpalxfpjp.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtegpyndol.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtwttiyjjq.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtymjiphka.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gteudwndxi.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtupgimfhc.html

[T15] Kotlin：接口
来源：http://dali.hysaishi.cn/Article/details/gtenpunesj.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtdcuuzzqc.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtlqlzppvh.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gturzjgmwx.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtirlsgbgu.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtknsckuqh.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtygazmsqw.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtsyzwkhke.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtysagtprf.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtgkjpulvj.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gtbwowxbzf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtklnlcdtx.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtfybritbm.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtihcrmwyl.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtqqqsgmir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtvtyiqdtm.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gtkiglysny.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtzotxswqz.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtulvrsvkz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtytvujzpa.html


<!-- 参考信息 -->