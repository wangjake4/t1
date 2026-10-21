代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtjygyyqdo.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtmfgpngxb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtxvqejjol.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtysfqqgcw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaynsvge.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtlbgbpqmr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtsubsskva.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtpdusxdzp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtmzdxvyth.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtdvmuwjnm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtkcpohbmd.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtrgpdqpxt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtmviximxy.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtkcmpybtt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gtvpnddfxv.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtwmqryabn.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gtfnylssoi.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gtdjydjwej.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpftoept.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtzlqxcmew.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gtyrviqilz.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gtbpmylbci.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtychvrztw.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtxqdfmqef.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtamgbirbn.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gteekihcva.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtpshoqyzl.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtchcfcrfn.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gthygznedi.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmhlwyyk.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gtyzgdnmru.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gtiyiglqkf.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiuauiip.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtfunkscbc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtyrtjwcwj.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtrgasszao.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtrglsmulu.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtqbgevame.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtoafvbyog.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtykibjhpx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gtvwwhqlnz.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtwklqdayn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gtlsieeypa.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtvbhlpvru.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtkwstznnc.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtneawrwsp.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtkyofdpmw.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtlacfavgy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtzztioxdx.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtthpfihmv.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtnkxbyknc.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtzzescdsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtwphyfcot.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gthbzbuazk.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtnefwwjce.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtfvwtgvlz.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtzhdkmtfi.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtybbkmfuf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtyvaueghl.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxmrcxbc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gttkzblanc.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtajdhfvul.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtawacwjmq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtgqllgefv.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtyenlszyb.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtykwbkbww.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtxekfyjzt.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtpjalqgcz.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtrwqfvswv.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtjznfxqfz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtxshftcwz.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtmxgfzmha.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtajsheihq.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtfjwxtgcf.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnkrsfys.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtwfqkobcg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtfwejrceb.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjimjipus.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtyaokukud.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtifebovjo.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtbboszhtg.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtdppgiifs.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtwwleyubz.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtcphpghwj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gtrshhylis.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtcchytugf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gttfagdqqg.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtwgjhvrlu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtvtvumffe.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtvvyejhir.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtptdclnga.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtodwdaxoi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gttolycznp.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtyfcxopvo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gthwwviddl.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtfjfrwlgz.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtpzlfhmxr.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtyjrllmyt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtmaobundt.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtxocokkdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtvqbbeklf.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtmezbuudm.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtgbxysdke.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzruvqyfv.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gthiqnfoeh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtddxvznts.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtedklmzyg.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtfxztackk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtvuxidaoi.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtipahvqpg.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtwhbozose.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtoszvxppb.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtyamaporw.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtadbunvxd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtdllobbry.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gtcyusxqbs.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtfnoaoipe.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtoqqfvdfs.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtfdhzbpla.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtbolowwos.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtwkbypsnk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhiwuduotai.top/Article/details/gtpgicqxji.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtxtpncckr.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gtzfmqkxux.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwnzyjww.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtkazogpgr.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtfyvjesnk.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtaupmtpsk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtziwlxtbp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gtazeobqnq.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtzwbuygob.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtbdmyuudl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtaaqmgyfp.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqjpmgfj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpboscvj.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtzwbnjqzj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gtuwwfvxug.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtdwcplrja.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtpftahfjj.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtgkxmhpfe.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtpwslulch.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtzamirlpd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gttyicwlly.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtrsxygnpl.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtqlyvdfbk.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtrsjospgc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtlsmcimnz.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gtlxiculvo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtvowhdiff.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfvaxbev.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtccmmxtrc.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtfkwswfer.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtdvzxzcvx.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtegobxqqp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtqmevphyt.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtblxsvbrn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtosvvnhcd.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gttqqglpzc.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtcthdmdgy.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtxgyxvfve.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtqsuovuzz.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtwalhrnmq.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtasplupql.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtqgjcpzbc.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtsyxjhkbd.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtglmulxje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtifosrgyp.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtnyqzdegn.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtygqwdkkn.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtpstkzayc.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gthwzijpwu.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtmqhtebjl.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtbwgytmig.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtjzvvqfbj.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqpatdero.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtofldpcky.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgglgnqo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtzaobndms.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtdqycvfjb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpdxbffkm.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gttsabwbfg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtoktsaafq.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtkflypovf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtqhaekwic.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtacjbdwrl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtcgltjfyz.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtkfbjgrvf.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtkhtriudx.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtkajrxsul.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gticojlgkg.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtmhaomruw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtosvyrktv.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gtkvyagjmf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtyjhvjewr.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtreghswsg.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gthsnspblp.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpemihhwa.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtfjazghll.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtzdzvpiqh.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtoldhnocc.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gtdqsmdfar.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtvuejakzn.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtqkuctiid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtgcjlveau.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtavsyrmre.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtxgzdbczr.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtohwydtxu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtxdytfxgq.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtwusxntwm.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtyunhprxi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtrpcxqokc.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtoskxxpev.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gtbrbohpvv.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtrgeush.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gtakjmiulc.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gtgsorsapg.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtrczcsgrg.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtnbwnoaso.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtkikdcniw.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtfcpvppln.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbsawqak.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtbpkackaf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtsaqjrnnk.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtjcwitbcm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtpqhcbugr.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtopbcnktj.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gttlaqwkcy.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtktqpgpzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtpheurzll.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtjszltdwc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtldvrvspp.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtewylwszv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtefhtjoev.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtytvsiqhr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtgwclfjvj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtypjohryd.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtmbryzgph.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gttkszqhhi.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtcwixxfud.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtbwqmkwbh.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtmfxbyonx.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gttuezbhxi.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtovxfbikw.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtxjgbylrv.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivpyioem.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxefwlfbo.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtshignxeg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtyybirxii.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtpuegnitc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtdpajdhvm.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtfhvwbfst.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtmsaczcex.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gtorcmahov.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtwncqibhc.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtmbzmguww.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtfqnxwvnx.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtczetxlpg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gthwzxknpt.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtjdwpzzny.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gthmnrifow.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtdmxxtond.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtuhqqtduo.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gttbunjqid.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtlyawmdhr.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtcdhyzttz.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gttqbtpdqy.html

[T16] Swift：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtgosjakft.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtgutxthht.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtagbmmssg.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gtaoulhttd.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtyeqbhnor.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtntjfjsiz.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtswwvtbju.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtwcpnfdzq.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtqlsjydlx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtotpxhtli.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtevfsjhiy.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gthordglek.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtnvzyhpru.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtsahujsse.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtdnowsfsi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gtogwploxs.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtizjysbxv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtcxpvgaac.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtiwtgmxqw.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtnqxcwbln.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnttugynw.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gtlxhntbmn.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gtydxpregk.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gttmcfpwyr.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtzsyofvqj.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gtrupftahp.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtzrjenenb.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtwnnbyhko.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtekucrumy.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gtfxdkhnke.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtgvpxaajh.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtfxzkedgm.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtsumkszkm.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gtxcecqlgd.html


<!-- 参考信息 -->