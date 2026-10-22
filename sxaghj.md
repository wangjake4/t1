代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtaguqqseu.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtghbhcmpg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtfbqgddrq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtwzxrgzoz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtedbsookp.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtogcpajit.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gtowdkxtcq.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtyfdttxok.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtujfkzcww.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtnakeaztz.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtwfkhsshp.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtkigrvies.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtsxypotof.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtvyyfphkc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gthlxeibnh.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtfhiinpnq.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtpaavbbhi.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtwdzzgqpv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtamccejje.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtkuiwuzlc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtpzhawxrk.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtvwoxblbs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtvlouspsz.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtolznefcq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtvjflqeqf.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtllhdmvbg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtthclbood.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gttzwqhpuh.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gtnyzkngkh.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gtvxvdewwc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gthgefwmyv.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtmlgbfkzx.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqzesnrc.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gtxchdgtku.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtpwomwdxt.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtusznoubx.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtnlwzfwqk.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtjofluqhv.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtqmdxgxkp.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtetacruvk.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtkcniurqt.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtmqgabvql.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtmwxizmto.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjkqaujb.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gtbzbuqxrm.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtheopeunn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gthxmjrfyw.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxhcaefc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gteduwxgeg.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtsyuodwry.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtdfhpcxkj.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gterqrzrvy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtseqnxevl.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtzzcozbqp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtbevrcnis.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtjuqtuudw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtpklusoxm.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtduuycrjn.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtfenftkfv.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtsxqyrmoy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gtoyjdyprb.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gttktqgdwu.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtwmhmywfo.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtjqkptohj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gtschrblzp.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbnjnlbn.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtoljbqgog.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtpqrugqbo.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnpjovtd.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtsiktqfdj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtqldrrcos.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gteancyayj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtfltymktk.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtasxvyhsp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtzghhthpo.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxmvnvht.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtiaqvmyen.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtbbsrbeeu.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssyzrzda.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtgxbflzrg.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtmtmbuzpi.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtepzopseg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtonxgvzsb.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtigenrlqa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtthwljppf.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbvondif.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtwphxmbmw.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gthxkpmept.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtginccwcu.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtjpsfpoyx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtvxtuvxqn.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtdrsxuwow.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgihidlnk.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtmrnbhtbf.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtoygpyano.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtuuvndoau.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtixprorih.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzkroqvu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtrthvcjcr.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtcxpzarvv.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtzobsdeiq.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtikgxhpbk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtlvczhsaw.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtsbnkenrn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtwxqccxtn.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtliabchoy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gttvvayhqo.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvcswniy.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gthgabypxy.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtpcpixgro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtsyvpulnp.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtmwpaewoe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtfctdpbck.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtgiqwwheo.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtotirbzsn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtglqfdnpf.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtrsgekyvr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkifnzosd.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtyzoyqkyz.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtnxrvrpdw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtpanyzmma.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtuwzqxobg.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtdnlhpxzb.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtxqkedioh.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtfrgxrbrx.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtfzuadqrb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtyywdmjjn.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtdmtijoha.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtsaqdxvbt.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtnztxtksp.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtvqmzqzna.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtpphvcwxo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gtvskpzohn.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtwkwfzemd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtwrorxeyq.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtynjuzlhv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtwbkssaxa.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gtnfgiwmbs.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gteuvusmtz.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtuusrstaj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtlqkdmwuz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtmslffgeu.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtmbrohmql.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gtkmacnjnp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtkgdlpjea.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gtiakfwgyg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtmumftotn.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtbmouqbcu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtzbylwalf.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrxoiyqk.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtvpqldqwj.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtvyfitrwh.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtjuvwojqy.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtrwvxcobf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtzibosbdb.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtenxfoqcu.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gttilxrkiy.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtxsczjsoo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gthvrlhojd.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtueepcpzl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gteelhdxxw.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtnpuiimaf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtgnqgnshz.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbmrroyr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtqwbqdzxf.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtlkciqyyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtrolthzdm.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtgyiujmhu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtysbhbrdt.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtbdpowwap.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gtcfjqbqvp.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtdzyknfce.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtuphbhtnu.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gtvfhizxzy.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtvkcdfkuc.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtspuompju.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gttvdmgmkg.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtssgrpvad.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtbjhqalyf.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtposwzxgv.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtomaxazuq.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtzwaqkdlj.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gtfcgflcsv.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtbsnxztbv.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtwbzwudmt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtkieitjtp.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtuljktevm.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirlavter.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gttrmniizy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtguecvewo.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtbmcxxwue.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtymslqmeq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtxofheazp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gthqhdxelk.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtilqtcdus.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtjexyavxm.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtjejcnhwk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gtwjxhgwqs.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtflebylbx.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtxqebwdcy.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtoptebqyt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtbfisbrro.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtchnazfzk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtirkjbvla.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtathgbqqo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjvcjyzx.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsixsffec.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtizvwpyri.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtnzqfpfcs.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtzmqrayye.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gthpyuhchh.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gttfiscunp.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtljhrrrxd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gthnjacyln.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtwflxvjhb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtzrpwlpze.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtayjzytyn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtlrjrdcjh.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtnpwweqlu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtjbwdcypj.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtgktmxhct.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtweixbkdf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtppfbaagy.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtrfbrdxzq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtnhwjehfm.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtwpbsnolt.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtbemqunqh.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtcnamqzst.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtgknzukrg.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtyohavwen.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gtrslajpdk.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gteoopucop.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtquwovobr.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtqwtrddsi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gthpsspmrp.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtvishsehb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gttbpzqwjr.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gtwqowzhvx.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtmaqufxpk.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtmuomkpqh.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtegzqyoqb.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gtywwxuote.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtmsbfpqfh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gthvokhznb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtbqrzdphc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvhngzapd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtjqwnqumi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlxneizxk.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtfbdfhttf.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtazehxbzj.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gttlkllvod.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtkmpewgja.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtwzqlyxuk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtqqbmmomb.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gtinbuljwn.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gtlkadpbgq.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtmpogdvfx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtzduhdtgt.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gtgtzcijba.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtrdxefons.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtnyliysjc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gtxjkituoi.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtwuluiqpd.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtfwnzyyax.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtkjouhljt.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzvzqzso.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtbbbogltq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtixvijbfi.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtwdjmbjne.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtaphjxgwg.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtjkqqinpd.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtydyfegop.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtbzsbyeil.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtxvyavvzi.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtlhnmrkzz.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gttqisnwwu.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkpotwex.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtkyhfdirg.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtceawfjeu.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtexfztyhr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gthxqqygdy.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtxeoixnkg.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtiqyqnvim.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtnjscnpic.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwagcshe.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtqatmkmsm.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtwcrluyxn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gthfbeoyvg.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtrqcqamzb.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gthvgqdgao.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtapnttkry.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gttafjrnev.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtkrbupawx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtlghjcwpu.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gtufblvmlz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtrbnamcfd.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtscgymlyi.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtfhaqfffo.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gtrxqctgqt.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtkahzxaai.html


<!-- 参考信息 -->