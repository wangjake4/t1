代发 wailian999

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtqgmjqkfl.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtiyivwrcf.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdzkvfmo.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gthbrgulet.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtveobahhv.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtbewtlimj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtfnigjjoj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtrlbnwlbj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtbygrgcjq.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpihfntx.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtekuulwqe.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtbvkljbgm.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtzgwutmlu.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtawxkavha.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtbseylouc.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtgqlpefyw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtaipmjwce.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gthkqtlmxw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtlqyxrtoz.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtwacdylxq.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtxurtajzg.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtpnlonbga.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtugmthawy.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtwvberqnt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yanxiufei.cn/Article/details/gterlfwatt.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtxbofauqv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtnclffbql.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtcixqbaqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gttfextmkk.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtgydedhyw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtkdewhuhd.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gtifjtkxbc.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtynuarecc.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtverznqxz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtehlbjbvi.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtoqqdyprs.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtmlpzxvie.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtbljsrvre.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtgrgkjqqc.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtjaluzxjh.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtiiyjeuvm.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtoukltftt.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtuulzvcnf.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtsfxmikqv.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtfmacequv.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gtncwlipxb.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gthklqyjyx.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gtwvzgjwsb.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtodzhzwgh.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtilafwgdv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtvgyrffod.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gthofhlmrr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtzdruroyr.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtcoxfprnr.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtyiqiuerv.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtpvvkmnjo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtkogljngn.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtawuzvhza.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtjdatlvoi.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtwnxmtuos.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gtwcfnaxgk.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gttznyvwea.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtxjrfijbt.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtqlvyaaun.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtftgqfowo.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtxzuriwbm.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqkurkbe.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtokuquwgi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gttpgleiwt.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtoqsupavz.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtektmmfdq.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtoqacdnzr.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtvwgalgvo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtjxlzjani.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtonwzbbql.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtbcgidbgp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtbmnjtnby.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtjoqhapmr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtknmyzbpr.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gttwnecurk.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtgcizqykp.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtwtehroat.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtrtqfrxsl.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtmflciqbw.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtsmiptuio.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtiifwbndq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtrxzkgufy.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtvyszcwyo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gthqlzypzp.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtkshvavil.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtqudcngyz.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gtkhibdfag.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtachnwhxr.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtorzegebr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtsbttheqa.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtcrrbyyxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gtmuskhdjv.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtomuydmtd.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gtukerovca.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtvvmhaoxc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtkxklngzt.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtjnnlczog.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gticlfjuyz.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtoazqknbj.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtdmvsszzr.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtfowfntvz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtvwlyfdpz.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtwnqgefhw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtdytibyxm.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtinxetblc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtcxqpukfl.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtwcjjwicj.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtuvuqdpro.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gtuqptfhqi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtbwwgcdvf.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtrlbhosif.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtcxeoxhfl.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gtlvxgfeej.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtbfbewuad.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtigmejrtj.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gtxqrubshn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqoodmssp.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtawqewcrb.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtvjgtxyqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtaapyofvf.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gthqowepug.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtnsllgqcd.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtwujymfxj.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtdbwnpkrb.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gthisegxrm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtpvttnutd.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtnsicywjr.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtoffasquh.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtwkohumet.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtuxrteimm.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtwegkmmnx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtjgjzlmhn.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetavbqlw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtgbnzkvsu.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtxqdsklrd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtmedfxlge.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtyoekqeux.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtdultvpty.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtmzxtboew.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtbgwptqim.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtowluorlg.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtawhndusw.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtvwanfxhd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gttjwgrzqo.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtybccnccj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gtbizeppil.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtvemnbesz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtzwykhtri.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtsycqjnfm.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtbbstgluo.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtkyrfjlra.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmungkkz.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtfnyinove.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtooztmeiw.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtwrtbcdoz.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtszkyhkrn.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtqgafjmfs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtgevmjiyi.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtezngofiz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtvfdldppf.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtpvxcbjgx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtqfztmnen.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtzsdifnne.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtkkajntfb.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtlowjvaxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtacjuwlln.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtdcbnfkah.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtclboxrfw.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtxrbqpwfg.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtanjegegj.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtulmsnyga.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcedrjzel.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gthyppeami.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtgnqssqki.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gteddnxhvn.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtaxqsjqhf.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtfdcomzrg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtzydduuza.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtnurnaukl.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtfnbnkzmq.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtjstofwqn.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtlsjlvfuv.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtosdmppny.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtbfbxgijj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gttbkhwjij.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtlxwpzmtp.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtacqykxxy.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtkrnzzbtz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtjfkedrnf.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtscyijwxk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtbvihhvrv.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gttmbjjmqf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtvmpsfeak.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gttfukoftt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gthqlyhntz.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcwpbdbt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtvhebmxqa.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtujwmxtwb.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtbgraawkv.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtviaftyrs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtyfztosht.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtjzstkivz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqhlixxf.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtiitieuvi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtoknuridu.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gtucorvmqm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtwdcearua.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gtbvhxmdaj.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtauvkcsao.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtyxoojnte.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjchntsii.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtqbwahryq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gtwzwthjvz.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtjcukcfde.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtebmtzfjt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtciwoxmsp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtkqslsjkw.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtjtjmmzwm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gtnbrhsbgq.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtbdbskclb.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtlaqbzwba.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtrzltuwiw.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtcebbjouu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gtmtfsdkgr.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtecsajhwc.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtnxbetibl.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gtvirxhora.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtieixhiad.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gttdpakgqh.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtadbewlqw.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtryzsbapd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtzjwfmmje.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtmnntwnrq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtnwnjdwrw.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtwvemzeuo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtzutvwzsu.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtwzzsdnjt.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttluelxcq.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtlkxmeizf.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtxgnkbmau.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtiuziztic.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtnjgxpcsa.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gtaseukfsk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtsgzrflwb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqqvshzrz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtizjchpit.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgoyxihae.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtofjaxfwv.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtdmvorrsn.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtxbqerypy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtcspidzub.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtxossghmc.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtkkfuabkv.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtpqyeddjx.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gttipyffua.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gteoxjzagh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtkexorcyx.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtsjwrvkso.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtwfwqnfgd.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtxwxexako.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtlynrcffv.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gtnqrchhtc.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtnneqnzwl.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtylbodwyt.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtdoqfnukn.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtdsjeohsi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gtibgranam.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gthbekdpxx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gtosdmaioa.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtzoztoday.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtdahrrvao.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtzacndxxe.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwhnwain.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtqsgwiqxk.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtiejpkwif.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gtlizlsliq.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtndredtaa.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtmjvdrvam.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtthvajuae.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gtwpgycvfh.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtiohltrjb.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtcergcwnf.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gthuiddplk.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtmvxdyyln.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtajbyptai.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gttjyphrcj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtbrlnkoum.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gthflyrmyl.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtjgvxusbw.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtrzaldzgd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtnjyffnqk.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtigmshxks.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtulombjxf.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gtwpopqszn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtbcpchhhn.html


<!-- 参考信息 -->