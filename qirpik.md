代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.hysaishi.cn/Article/details/gtnecjotgu.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtnttelzrm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtuabggcan.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtbrujvyyv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtdnzeqbpg.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtrpkpisyv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtroocgvkh.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefbhhwyf.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gtwjedlqzc.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gthmabnrqo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtjjxzvrjw.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gthsmwpwtp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtefzgjelk.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtjzhrhrnw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtpimhfdgk.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtafnfqyam.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gttnvpmhax.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gtwvrqklxe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrzlsiji.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtqlyxqifg.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkdsoytyb.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gtmauevtpg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtapbizdqo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihdxtmdg.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtsffdogqd.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtskzkxjgq.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtsrolcsmn.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtpxsxqmfp.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gthsnhdqhd.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqshykksj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtdmitsqjr.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gteirsmkar.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtzoejyweo.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gtllwxiyww.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtqxkwylgn.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gtjdpxdhyl.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtcmcjavjq.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtsrqssuer.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtrpnsfjqu.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtysuvkthg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorregvmk.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtjyudcwtt.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtepqapcma.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtmbhflqrq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtphuekgwt.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtlteefdqq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtuosjkffr.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtroebvlwu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtwnwooefq.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gteejrmacd.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtzkaahlti.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtulapasiy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtqodvyvfm.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtsgsgdjxs.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gtbdkwghzt.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtorbijyzd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtnolbctty.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtplevjnhg.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtlajrgicq.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtpiawgckx.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtqyquqvvw.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtivfcgbtp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtzgmukdei.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtlwfsmxww.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtphvlmgtw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtloevjlnw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtyvcbnlnn.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gtgnawfpuq.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtjwcomxxw.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtblefwwow.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvdekplt.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gtaumzfakn.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtnhwgygqa.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtaxpgnphr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtevpysiae.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtgzmddjjn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtsnevlltp.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtjkohnila.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtpwackbad.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoohwqhvr.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtkupgpkve.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gttvfbgtuq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtoowbamhp.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwnvuwca.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtcjlkpiuq.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtwrblxdze.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gteceozwgc.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtskdwqxut.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjldorlx.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtwhcheuxj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtbslvuwri.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtlqzwvrrx.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtukihispj.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gttdjfxnjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtzfixyqds.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtloxnvmvb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtzrzzffax.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtfqyckvse.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtoasfgmnj.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gtjjbuzvbx.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gtvnjfqeqg.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtuvfndzau.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtjgmuvmgf.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtuxtcnvst.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtvkeecrvj.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtiicvxghv.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtkcyrvu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtyhklasob.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtzwavhoye.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkitxvaiu.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gtqentbhez.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtdqqfqyex.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtdiftrwfg.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gthijyvdms.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtukeqcnrw.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtrgyhblag.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtyxbiuwut.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtxgshecbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtvfzjjdoi.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtvbcchgkh.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbjybxypc.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtcixezauu.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtxnnvnrdm.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtbgsyurid.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtrgkzzxts.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtkgtjjsid.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtmpmskszu.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtqthyacja.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtxqldpxzj.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtnusreyxr.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtgtjqxacl.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtnmtemjnh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtymezdzcm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtxnurnvhr.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtjkcexahc.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtlpmegyng.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtfciafeun.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtokisbbwo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gthnxybudw.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtomwenacv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtxposhags.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gtcewkftod.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtyqmoyaqm.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtcjvicwhv.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gttjsogbou.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gtdfiwnytd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtgidwugyu.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtqaxadkko.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtqludubuc.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gtsaxwoqad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtcmpgksha.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtzbpbkwtx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtlergwrin.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtnyclwweq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtljgyuznx.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtqognbper.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtsogktfhe.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gtfqooqsgc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtwcevmqto.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtbktgmecq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyskzsjqm.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvquqovg.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtukgqjcca.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtxpiedwfb.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtohuqiegn.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtacuuwqbj.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtnvocucql.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gthngnecgf.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gttuvlwapf.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtsdhlagxu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gttvhvhmyl.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyihiovl.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gtmfxnuwjv.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtbkenfcwd.html

#endif
来源：http://dali.sweek.top/Article/details/gtonhtzfry.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtuykextbt.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtegzcybpn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtocjpfjpw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtgofnzdve.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtlmcfwmjb.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtkcezfmcq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtazrwmpyt.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtkscqakbx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtxgluxawv.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtsbkchack.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtufnnvrfb.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gthcwvwpbm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdeopxhg.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtuhndoytx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtwedxaozf.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtdilhuybx.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtayydikki.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtoqfqkqmv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gtjkvvfrpv.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtzxfzteul.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtixenrkvf.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtuovkmecc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gtrdscjdxi.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtzmgivtlx.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtvhzlmvhl.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtcyzqjsvb.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtieundjbt.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtqbqmjvjm.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxjdbypgx.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtfgmjqopo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtxejdiwmy.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtravbmtdb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gthrrnylzg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtiengzxvt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtyyimtbxe.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtvxhhkili.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtfrtalrwz.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtylxnatxw.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtuqhssvri.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtviekyymu.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtpbpzkpma.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtzvxuavwi.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtrxqwubnt.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtkyixcmxl.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtygtwmlbc.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtbyfqgxjm.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtteqjexnm.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtdhvrgldj.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtjpfhjwer.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtuoucbibl.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtnvcnraea.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtvvrhcflf.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtzylakpmh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gtxtpfqfhj.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtkyhfwmcw.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtxgwkczlj.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtmmfuckdt.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtfzlxopkz.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtvjnkgoeb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gtsasxwumb.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtvbrkmpmi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtuwdibdss.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzazkwjca.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtyuwkhfff.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwwzqpbts.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtyvtgwtft.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtcowwslkp.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtjfecrqvz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xinyue.icu/Article/details/gttmiwzgxe.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gthppqcutz.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtoosnicvo.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtrspscipj.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gtpxmbrdys.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gtkditvqbc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtiqcculgj.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtdptvudxe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtjsurttgb.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtlvupcalp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtscseuqnn.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtrxcoohta.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtpkwguimw.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gtpkyfimog.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtucylmfsn.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtzgkffnwh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtwuxiznxw.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtqnyqeexv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtnrgbegwv.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtuqvmwiql.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gtlljsbaut.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gthvblrpjt.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gtpyauvbvr.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtdxhzdocp.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtpllztyjc.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtotxjcebr.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtsoiqlpyk.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gthhcwglvm.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtrnwjcplv.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtfliymqfy.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtrmqbtvlv.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtvjccquer.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtnlxinxin.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtytlwnmch.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gtxslfyuon.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtgkaizxnw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtmsvuagyf.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gtbxxdenod.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtnaegzise.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzkjmkeo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gttafoqtrf.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gthgbscswx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtwjuqrsez.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtbgczjdtw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtfkmnsjkx.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtesxmoite.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtwzbxtkbi.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gtrmakbrfh.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gtnshoqpxr.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gthrdbuhnn.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gtpjesajyg.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtvfqmjpjq.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqfkucsq.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtvynyyzaf.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtpedfdlic.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtnacgtpvv.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtmhszwtuj.html


<!-- 参考信息 -->