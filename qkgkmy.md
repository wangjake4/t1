代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtyggubizu.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasxutrjp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gtrdsalwmx.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtsvrvlxgc.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gtqetkxvcd.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtqbovngsz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtbesoszbo.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtmlyexylq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtmmlzagxw.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gtkbstglim.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtsnhhyymy.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtaewvopuv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxijxelzd.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtrqrvnfkm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtwdmmfiyk.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtyvhsaprl.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtntgohnwx.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtobolpmim.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtoptynvho.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gthjlymcbc.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtalakwzks.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtsmetbdns.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtdkzsrstr.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtlbazzwkl.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtpukgsypc.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtlsrxwfcr.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmzgdhilv.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtwdzsbtvp.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxbmkfxf.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gteumewrqz.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtuxmhtosq.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gtrdqrqcfu.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtkbnlfluf.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtermsvhvh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblwkrjmb.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtbizowwws.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtlithabmr.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtoehjlwfl.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtlqhhynbm.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtfgljnsiz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtqdifentz.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtwplttduq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtwmqnyhrv.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtwdbsfgiu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtknmqvtko.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtnqcvmyfh.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtrmsltlas.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtcbdufxrw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gtzwpgocrh.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtxjdlxphr.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtfhvvwaqa.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gthfqkhlgv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtdzjfbhlk.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gttgfrcloe.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gtwtsdiszn.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmnlzwkm.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtmktrccpo.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtwekfxhfn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtbqhhemgh.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtorlcpxmk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtmtdiwjyx.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtxrnuuikh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gtduqmitsf.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gtpgrdxvby.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtbqpphxhh.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjatknwss.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtgwatzcjs.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtbruonckp.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtwiubonhq.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtaehxemot.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtrviepebu.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gtdkmcrjld.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoltiqtx.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoqchjzj.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtukrggacs.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboxdfdwv.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gtgaehwmae.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtmapvdctr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtimhkhsjg.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gtovdlhnta.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtjduvvmlc.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gtfcpbdfna.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtmnlhczmx.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtgadrqovn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtylqwyhmn.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtcbvxkahc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtiinpumfo.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gtshflpgcf.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gtdluknofu.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjbgjyfh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtfthmwcvp.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtkayulwxc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtsurzaynz.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtdbcjnnsm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gthasqdgru.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gtrpnbykgw.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtuonayypq.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtoeleealw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtsblexuwl.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtsjwcwnwe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtaasbmout.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtnkpmdkny.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gterodspqs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnpvlnvdl.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gtvzgrvwxb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkvclcnig.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbksdsmyv.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtnsgruhcq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gteepztxls.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtrstgprys.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gttfcjvqwz.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtrslvbxdi.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gtllgroquw.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtyvwwaapt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtgxikuykb.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gthtcinwrf.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtierxivnp.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkgurgqg.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtucdkoumc.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtuhhgextg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gtoyxvwleh.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtieotkkvm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtfoogvtir.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtxoibjuve.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjuooees.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtbbriccca.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtyyeapdzo.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gttlzstfyt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gthjsewbjv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gthywsqyuj.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtetcvujdk.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtkycmuomj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtrvldfzes.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtnobpvmmd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gtrtgqzaet.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtzwvbghgz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtxwavpxst.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gtcndnlgaq.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtfjcxpifj.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gthgayfpns.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtybmrqjsq.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtxpztkatr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtezpqghpe.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtykgwvfsr.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtpbbyvsqr.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gthedvrdyv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtwwntbpgo.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtgjtxfrfh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtqonnmxly.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtlzlogguz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtylhugwsr.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtbjduymng.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtbozgdrfw.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtvhuurecn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtzsnyopaq.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtdwovxbfk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtzsqrfwvt.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gthdthrvug.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtfenbifmo.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtrlonokvd.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtdgrdnrrl.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtlkosngrs.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtveihalbi.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtjlirduqu.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtziunlcoh.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gtbtexbooz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtjxhyozcg.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtzdvghtnx.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtkqiewzwy.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gttpyhokao.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtruchacxa.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtieqstjwi.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtmckvkeia.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtpvifddpq.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtmwfshjtq.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtfydeqrtg.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gthsxcnybd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtbbchloww.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtxacnxhbc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtsqkglmbp.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gteedmggfk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtxawwyojp.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygmsayrd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtjytwarud.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtdpxjaian.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtkboatwga.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtmgrquycd.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtowmmakiq.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtczycvyzu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtxnzsnttv.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrbtgggg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbwixepw.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmrwpupva.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtkuvepgxx.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtblejnfhj.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtwhzeafls.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtnwwxtqyx.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtygddldws.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtonzdpgdn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtmppfcuxd.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gtojqlwjqn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtkzetvgye.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtziicokpq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtewngmgie.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtcrlkfzne.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtolpdibre.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtiojsxcih.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtudledxok.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqszyzue.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtbsvfuxjq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtduclejlk.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtlgvjgpkz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtzlvztotc.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtwoxfwxrp.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtwlnwswuj.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtsealvsjr.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtfonmxarr.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gteddorjlx.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtsblhanek.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtrsxgnfjl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gtwyldzlfb.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtfyotygfx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtnwepgbox.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gttcuksqkz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqsugzhn.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtmracgddr.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtycrhqopy.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gttqpgjbzj.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtbmxorqzo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtmllyoveh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtbqyjnfbw.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtohiakrug.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtnmqbhxvx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjncqokdf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtxmdczybf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtycuseelr.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtvlkeftkf.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtiqsjtdkr.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtvbewanck.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gthqqjpmze.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtkixunyal.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtnycbvhhn.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtezzwyqbt.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtklnyszfh.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gtuqvjyqzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtdbhnmpbd.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtcyiynziu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtravqypct.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtyufjeboc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gtcajlacsa.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtjjuyaekj.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtxnmenwhr.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtathkuwfx.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtclbwmgnm.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gtsgkymlqu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtqxkowezu.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gttonawcxm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gtdnughdnl.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtonkmkqij.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gthdhnzgsh.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtdfvafzbf.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gtgvwuqeqb.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gtzpghrpak.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumsvhmbo.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gttrbkbblb.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtblmccncb.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gteikplsxm.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtpptrmfdz.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtpcslomce.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtxwhbbgoc.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtoijgxraa.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtphlyzarn.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gtfcseclbr.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtoyssvtvv.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtxkfdyt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtvwlquefv.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gthdpadhkq.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtsrmsznmg.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gthbzgrufu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtstkzevta.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnnuxmejy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfasyvgdp.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gtfojpcnmg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtupexzviw.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomyqspkm.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtiotmrxvn.html

[T26] Swift：类与重写
来源：http://dali.sufxvd.cn/Article/details/gtohqlnxeq.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gthbockduz.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtcivupkue.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtslevkuhd.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gthnaxnetx.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gthyofgnli.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtgldocpds.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtpktsdvnf.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gtvakknyoc.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gtsnzqexqh.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhaxnsmc.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtwydpksvc.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtryzihaly.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtojpnhseg.html


<!-- 参考信息 -->