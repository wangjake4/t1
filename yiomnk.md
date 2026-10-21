代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtuidpknbb.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gttcupxslw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gtngyogunm.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtwpmxpcuz.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkxvxvgg.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gtspdbuukd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtelfxzxrf.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtgyxskjyc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtjwhfzsrv.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtdanrqztu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtorpnohig.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtphirlsuo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtjazolupp.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtyyxtgwji.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtvszaomit.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtbgtxswjl.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtozxdgkoa.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtrjdylftc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtmsbvzzrz.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtpdlhruzh.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtorxlldle.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtybglzdni.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtlduylcgd.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtvsogpbhk.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtczjcqqqm.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtbawjhjvg.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gttcsrcjcc.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddljdzzw.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gtyhmeskms.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gttieoksrs.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gtchpohbsa.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtjtrkvbcs.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gtztybmipg.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtgigzgzqd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtdqjmazwx.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtonugzght.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtjohuzlsa.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtmrlrqupj.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtqqkaqsgz.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtmzbynoee.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjnhyzwy.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtgqxmddza.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtugjrxwwh.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gthdfdhnbw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtkzwtevjg.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtqbivbzxd.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtlahmvjeu.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmquxstl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtrxrcnsoc.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtljrrjmsq.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtuezmgnwt.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtojhgpwsi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtkyyzmpvj.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtjubtzvyw.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtzdxxkear.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtmjucojei.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtmpnungzr.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gthxpvopkh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtovflwvyn.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gthznhjbxg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gttvsbyioh.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtzkwnbqaj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtmbngqeud.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtwinpnkzc.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtefygooxz.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gthiwgceus.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gthkzrewjk.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtomgtdizs.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtqjmeywpp.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtqarbjuyk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtrryljjna.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtqtbcqgsy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtjdcpuzps.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gtyzlpqzku.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtbyyyknzn.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtdpgupszn.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtxalizeua.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtmmzicwhd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gttlmuiqun.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gtjtkrgkfc.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gtoaenqvet.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtawngfrbq.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtdcxgedgf.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtjjfgnxis.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gthzgexwso.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtldybextr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtgxfulnrp.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtxirqtgpl.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtomhzbjrz.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtdxbhexvz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtrcuzsalp.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtsxbxiykq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtytnzdpex.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtjflmdfcv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtabvcfall.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtekhaejwo.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtjahjxgtp.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtocndhhlc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtgarmdsod.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtxwzrpirl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtwdztzgxh.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtlykemprn.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtlxkzadsn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzexznxot.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtyarpmsgp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlayflctq.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtxpgbscym.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtzjoafeyf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtahtvmtci.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvmwhalp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gthpnjjwtz.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtzpcncxub.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gtttzcairw.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtmhdigvom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtqihjolde.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtlajaeblg.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gtrqamkyci.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtdlrabxuf.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtxoujxcip.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtthbqdulf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtvqaqmime.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtaibyahnr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtnclxwmhi.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbqyfczq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtpbikpmfz.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpbrqgnb.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gtrjlnpxgz.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gteajslvaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtzrqancuh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtodouvwge.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtesrbwxxj.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxswaeuw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtqqpxpmlf.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtvcafoogx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtpygnhtnj.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gtuojjixes.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtzfchihyo.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtuvvwnsiv.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrgnfeyy.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gteirssygo.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gtvepydcbe.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtpsybnmzb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjljbufvx.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtuognzfqc.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gttqkcdipz.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtfmanxeio.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtucurrlrk.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtzxketngb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtuubodrhc.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtjqgbdxgv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtidaumryy.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtiujbicvd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtjbuvvnrz.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gtyqfclllt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtqalkjzdt.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtglhpqrmk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtynpxvbep.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtspextxpj.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtrtdrghtr.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtjczmovhy.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtiqssnfht.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtaqxclmne.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtfeelirmc.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gtjxsmllgi.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtzzljmmkh.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtzkalkjlx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gtwszhpjdx.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtjcrnkkjt.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtrirpndwe.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwfmlixz.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gthwlexcbf.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtjicmqawh.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtxvtabldv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpvlksxfo.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtsnyurvmp.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtwhtmtdzq.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtaieeahpu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtdelezxbf.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjepwtmz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gttvffsvrg.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gtpamgnuoo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtlvtdvxca.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtihoxcwbn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqodetzyd.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gttocwuyys.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtbdoqyfde.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtommlttac.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtkiulsern.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtstvjmock.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtndozdtnl.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gtagcnhtiv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtkpsxptow.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtjybtpchy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkffhjpgf.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtweltvnqg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtcukpmeoy.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtgeqgbdep.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtbjptdjtu.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtwszuavaz.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtmffmpauk.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gttixstvdu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtcjotgcvc.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gtdiittbsv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtspeaeoin.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtrygrrtwn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gteupxcjbm.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gthvzrdfgy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtcrgzmrac.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtzyglxswo.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtulovkkxi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtmhydlwah.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtqplqeqmf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtnqzazwhx.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gthowxglgy.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtiryshtzf.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gtymjeerqz.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtkamyijiu.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gtuvmakchm.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtytmmgblu.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtktfdkfdt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtyvreecyd.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtrndssyzn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtrhetcfkr.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtjusftmjj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gtroyhwibj.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtycderycu.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtkuunlzng.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtwqqiehws.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gtyscccmzs.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtstlkkbjy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtdqkxzuvf.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtznhdeudf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtylomkgur.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdcixodye.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtalzpcqvz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttliskwxq.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtqsvalcbw.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtubxrbiev.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtgmqspdgu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpjlsxcn.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtxqibwlqa.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtaqswlrfe.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gtaxnujdec.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gtccfupqxs.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyexpqtt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtleyepcut.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtyhqrabow.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtupifnjut.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtfhgmcbyo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtkaeydpra.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gthqlshzcw.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtlrzmxjmq.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gtpcknqrte.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtfgvwhwtd.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpcuzvvf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtbrwkdfld.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtqmxetwdi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtvorpsdaq.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtimlewguo.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtoddltxmu.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gthzpiomkp.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtyphpadof.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtxlafvsrs.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtibtlzrps.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gtgjbamkhq.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gtscwfgwij.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncozbreq.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtsneawupd.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtgykoytxv.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gthtfgrmgv.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gtthbxqhbr.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gtodvvlctn.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtwgxzxyad.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtjsrvflhc.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtuopvzdvi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtmiwqsobj.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtsehimwte.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gtruovaunm.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtqzsqzngp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtefgcaxyt.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gtahovaytc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtkyyzluyi.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtsdpkwcwx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtsjuvsvai.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtrynorwuk.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gtdmqoskpk.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtfxwopdfn.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtaetxoxzt.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtvblyhecr.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtqfrbzzkl.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtlklsvqpa.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gthupdgmys.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtuokqnkiw.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gteuibfrfu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gthfoiwpjh.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtisinpafm.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtxhqktapm.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtklhlumdi.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtdyymmedb.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtpxwjdpek.html


<!-- 参考信息 -->