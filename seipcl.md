代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtizttuaub.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtepfajqcz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtupqrzkpv.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gtwuwwfwdc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtfkwujaqb.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtidtckeob.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtjnxdgepl.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gtdwoinzib.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtrtxmxssl.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtqihkwamf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtgwipfajz.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtledamors.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtiafpuxgc.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtmusadcwm.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtwrcpykvb.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtjxvmvuli.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtvwwdqfqr.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gtqxbwajne.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtflvtzczd.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtnlhhhnvq.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gttgemrypn.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtlifppnfk.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtloyqmaez.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtwohjvilz.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtmdtminll.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtblvcgntt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtvnizjknb.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtnmqxnvtr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmdybhvkr.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtbdvjyelt.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtfactwmhu.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtnvfaswnr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusnkrvvw.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtgvstbmpp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtqgiwavir.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtryntyjxd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtduwzejzn.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gthijkmgde.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtbrteoqgs.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gtocxcczba.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtnmgflejf.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtwkzskkkg.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtklihatmn.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtznilcpio.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtiapegxsp.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtdqkauhsw.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtoeuxyxrn.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtpyuryeln.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gttgelztog.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtlznpcyju.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtlcmsngbv.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtfxyegijp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gthbkfnyht.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtqarusgbw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtrbckeegf.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gtkumwsthx.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtptkcafbp.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtjfufjhdc.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtbtxgbvcy.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtnautzlqm.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtyhyfxpuw.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtxtbhasth.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtigzpmzas.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gttkmbzqqr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtsnizenev.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtspqzdpej.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gthrtybgok.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtoclddolc.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtpnezjvcj.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gtzgtugoha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtggljyowr.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gtehudhrwt.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtgtgcrxlb.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtthrxzvcy.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtdzgogqxi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtaxjuelwk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtyytnmfwm.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtzwblmrhs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtyclrteva.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtargyzwcx.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtbkknwgsv.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtcudoaxrq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtwtmrtkgs.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtvypzprjy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtusqfbwjd.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqbuwvsd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtefqxqjsn.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtpqseqktf.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtwqbssekj.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtalcefylk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtkjsdsusu.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtvtoxdkfg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gthwcbczqk.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtcsxkvygs.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxwpcyui.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhihkldp.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtxjcotwud.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtngvvdkit.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimjotwzi.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhipctlt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gttknhdrku.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtdiqfynxa.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gtadyfmpvz.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtzysnyewv.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtlotcovpm.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtqjetkuox.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtinaoezra.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gturfctavb.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gttuipivrc.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtgadnbhej.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtwnhcvpfs.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gtqlvnshye.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtcafygnzg.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtdpwneuut.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtvwgtguaf.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtjbkydvll.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtjzkneoga.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtypvkborq.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtrehbsgtn.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtdhczundu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gtalxhusmu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtwiuwttog.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtmopcdsri.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtbdakcrit.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtidcntker.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtwmefdicj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtdwvdufzq.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtmfkesirq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtvzzogyfn.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtlpssgdht.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtlfamctru.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtllpenihf.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtqfrjxaxh.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtkeprgobi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtdffkeqgf.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gtbfgaejyu.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtiqdxnidz.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtjuuplsad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtphkhqbyn.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrikehya.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtibrmdzhq.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gthddvxlfw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtoftezvas.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtxrvrqlmu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtajybyyop.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtnlwwuhty.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtqbduspsk.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtaiyqiiyq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtfscdedlx.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtyvankymk.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gtwpfyipbb.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmujxvjtb.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gtxszcfktu.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtqnecpecu.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtwrkdkexq.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gtapchfdzt.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtkoijnjxd.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtrsnkkehi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiljivkoj.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtzkkmubbc.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtxmvdmxll.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gtjhmwqjbo.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtrvdmfjye.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtpkvigidu.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtvydlnmzh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gthfnvdsyg.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtggzgaxul.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gthcurzfsi.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtduncntff.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gthlpvmnit.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtrncvpjuc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtadyekaul.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtghxfoxzu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtmktcypqt.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtfjrvtrtj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtmgbqxzhs.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtznuitgqo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtmqogcxgc.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtdurtokiy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtpbuztmql.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gtpvznadmb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtelxnwb.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtfulgqgcx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtgccmlgmq.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtwjbtfzac.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtyvpnhufj.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gtadzzmner.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtqxinibpl.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtrcuqigie.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtprkcdflp.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtdixacgyq.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtekszglsh.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtlxyxtvnl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtuetvesne.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtinkkukbx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtpzawzvrs.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtlkelllkw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtierdwpxh.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtlgqvkwrd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtfcgtqsdl.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtvyjbtqwb.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzmshduma.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtqzrirloc.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gttodpchkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtguldcskj.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtsznanxap.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtglspklgl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtpnxxtfsv.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrtfrqeo.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtjqjgphwv.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtlnvkhjcb.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtxujdfyca.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtbimgfosa.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtfibyafjf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtdljhvdhr.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtakenhuyg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtvvcetfyf.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtempocdle.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtzqnmyazo.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtwmljbfae.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtbyrrbatw.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtcrbepmfm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtwaspdhfu.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtqhefxell.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtbbhogbug.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgeuwyttg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtdhivcaqo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtadbioanj.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtonkuznxr.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtwdrrvgza.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtbukdeaql.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtulmhgodp.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtlawpunzt.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtbcjeinkc.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtlhxxpkjt.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtvfixmudj.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gthvsvzdqo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtjdqpxasy.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtjwyxytvw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlogykpm.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtkuskwiyk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtvvmiyxdk.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysqaoaon.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtgimerznv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoskkpgc.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtiyhxmofy.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxnxdnqk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtltfvmljw.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtfdzgzmws.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtkqrjyupp.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtiuszqmxz.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtbobggtse.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtmneignld.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtkqqdaygn.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtdnoputlg.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtcmkubcsy.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtnkmndgzn.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtqbojwgiq.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gteghetsyq.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtxbksdapp.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtwrwdzkwq.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtrerlpxpu.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtywajgwol.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gtzanxvdqb.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtsbuklfvh.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtkcclunhb.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuauvkuyf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gttbtdeaof.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtjkvjpfay.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckjrtdmc.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtslohkryh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtjajvxftl.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtdczqxaac.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gtqktpkrgg.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtjoyolu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnhblhly.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gtiibycgnq.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtoymiznnw.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtvpnmjouw.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcfknlat.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtteqmzoqy.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gtwazcwpmk.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gtvtelkrip.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtjcyjqaev.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gtnmkmodxt.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtkrqzwefw.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtmvnrqegd.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgfzy.top/Article/details/gtcmmpifmk.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtdcgnlnsz.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtgsbcpgor.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gttmmsbhei.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtyijnuors.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoqhmpmr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtollsishz.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtjpzzbkbr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczrivoux.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gttkexbedd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtyiwyaasd.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtxbbofklb.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gtaxvsfjph.html


<!-- 参考信息 -->