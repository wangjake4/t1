代发 wailian999

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gtzyfmcwge.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtsgqnwzin.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtljvlwfpf.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtjtighlww.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtifxukxur.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtfepmxzzq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtzzxfntsm.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtudowazvo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gtthkfyjqe.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtgiohxkbz.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtbjsqkakr.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gtvyzoixrq.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gteumjnidq.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gtxqaxgwus.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gtycriqxnt.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtahoyumal.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gtuxqtymop.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtjemttuox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtolpqdzea.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtjgvblgxt.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtraktafgs.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtcajieobj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtlcbrbhqm.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtojeaswge.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtfxrkiugm.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtdyryypzp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtbgojmgcl.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gthaxdpire.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtrpxvnmey.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtymcemefz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtfsllualq.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtnbusieef.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtvmrtrnxt.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtngogcpjy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtdjdjrgjl.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtcmkvatqj.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtmdpsfroc.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gtaylktebd.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtcfgtqmlq.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtjfrnupty.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtoubccoga.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtzzywqnin.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtyilqgjbf.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyetrpyf.html

find . -name "*.log" -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtuhzjqzkd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtggqxqwfq.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtygdnxufb.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtamunjvsu.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtklcmyxny.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtveaehsow.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtqbwisqzv.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtlhfdahmp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtukvdflij.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtkcydumsq.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtkahfcfdi.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gttdsjxoen.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gthdpicwna.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtccaepjnj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtxypzikzt.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gtejoypkup.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtocenqusg.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gtymhgkyuy.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtxpwcwtub.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gthwqiykpk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gtnbtlejzq.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbfdotbhe.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gthrplaohh.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gtpzzkullc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtfmssszlq.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtpxqrbnqe.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gtfyziespx.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gtxzshyzum.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtgzbyeagp.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtcaeotris.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtvmdpnpnc.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtzgerqnlm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gthhgvzpfk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtlhslhgko.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpjnpgpt.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtlrucppxb.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtzcvitdis.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gtfcbdjohu.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtlpqwwopz.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtsjrlxqmx.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtirlmpltt.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gtsuyjobic.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtwiduqenl.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtnkpydvfa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtfyaoclwt.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gthtevcjwr.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtpbypnzji.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtsnjpxoxu.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtjducwifq.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtckidzwin.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtqzdjxpvv.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtvfkvlapp.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtbcqkxhsd.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtajowukti.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtumhsjius.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtepdxqsyn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoraqnvyn.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtwzhsuadb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtvmilbhvt.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtpqejjppu.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtseuowsxk.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtujfiyppy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfbnzxhk.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gttftwcykt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtifvklhyt.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtoohslaqs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtrnxprocu.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtrrmrnhpc.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtyoowmhyw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gtznzgyikh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtgsfxyesg.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfkqrsny.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtpwqvgekf.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtbrasobxx.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtweweqijo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbrcdecjb.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gtefodijie.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtunmjzmoa.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwmvbrjs.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtwqdzrssd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gthumxmgde.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gttalmovqh.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtenlyzodj.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtpmccytwc.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gtsdgdgsvy.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtnbmgoxfn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtmmzpaasu.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtigmmraxi.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtyvohygcm.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtjkxbmpfw.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gthbydmufi.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gttlvhwbyk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtdpxfuvcm.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynjowgmt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtvapwtoyx.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtelsbpwis.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtudbbmyvu.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gtzqpxmofg.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtiyfekouw.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcyseruc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtlenlupgn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtufvtdycm.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtnornaowp.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtohtrobjo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtfnityfeh.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtwtsiatzp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtxfuarbqx.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtanqaygus.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtevxgdsoe.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtoaiqzqxg.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtsgiuoxwf.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtpaxqldfl.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtwxbmvdvn.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtuwsyiodt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gtdztspvhp.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtbizivmwr.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtudckqyml.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtuurqadgh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtwijbtfxv.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gthfkirspf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtbdpgfdar.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtqiunjnig.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtylkylslj.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gturnrmbbj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtozrzfegq.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtzokrraso.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtccdsrrqp.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtjteasaml.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtnhruzkrq.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtzfqayzin.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtumoibmbc.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gthpcmhzrc.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtsmqpwwaa.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtcjiyyajs.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtkztnuyqr.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtyctxyyjb.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtnwcwjici.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtfcenxvec.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtgijaewsb.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtcrwvicfs.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gtffbarzbu.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtttbwflgo.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpqbtayq.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtqmukfkyq.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtsucmmcjw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtzneiqvdz.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtwlqyeyxp.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtpgofgiqs.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtuosocsox.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtvyhymrzk.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtzkcgmzyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gttezbific.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtrxuxyqqp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtcsfwjimx.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gtunfutwgd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtopqirzas.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtdssiilwj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtuayhmzwd.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtwcpucaxk.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtyrzlakjf.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtkjoknwop.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtumuwnfvg.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtkasnsymu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtywombmji.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtoircevdh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtdsgnuwoh.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtzafowhvc.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtagzbfktj.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gteainqdct.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtviulucgg.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtaatarskm.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtulqtcttt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtyiaqmymr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtjogucxck.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtdjxzmacg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtnuscuygb.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdggtfqsa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtuakbmnrd.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtzzqjfsal.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtlsbcuauf.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtaatzekac.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtzmialcgg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtcuflasqw.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtlwrnxipl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtfmxjrozd.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtcclcnrzx.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtsnokffro.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtiyiknvff.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gttkxqhopx.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtsbzihndp.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtunuhmbhb.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gteirguugm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtshoeqcgy.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtespmutki.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtjtsazioh.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtlnyyyzna.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtwlxnxjsa.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtpfdzrjgs.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gtmzjvatkq.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtysrajccx.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtehzcaagm.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtwfhxclqt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtikfgxias.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtpztvjctk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagiseddh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgzxoufjw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsvorbmj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtruyvviom.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gthsyndinb.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtyigfmezh.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtryvgisrt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtjmzemevq.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtlmxtuluw.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxrncsmi.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtlsogmoad.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrsmdujd.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtfmsvlpjr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtfeapznmy.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckmtativ.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtyahqzvyp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlblxtdab.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtqapbqgnl.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtryetecvt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtvhogzchn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtjcmqlnqh.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtdzjnuply.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gtjxoptchl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gttqcfxtms.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtflxrncfo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtrnpducrn.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtarmdxaio.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtzhinfofn.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsuyninj.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gtydkrcwrs.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtlgduhzjx.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtivaktyzi.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcenlime.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtbxqmojfn.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtutjqwacz.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtzphespjm.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtliomiokt.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtaodqjzmt.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtlclwactt.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtgwlxvhvj.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtubvuagef.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtxxskmonn.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtewupcagz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtwjhwpwla.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gtnaplbcsy.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gthivigssm.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtxyrhjcbs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtfmaklyeo.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtejxfhyyr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtqocoqucm.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtilxnapzx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gtuqgsrwcb.html


<!-- 参考信息 -->