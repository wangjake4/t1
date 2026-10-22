代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2xkrhaccc.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2crhthqsw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2pgvxeaxh.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2xvhqmdpf.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2zqexixij.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2pyfnzltm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2bbnbzebs.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gt2ehdodidw.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2syythypf.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gt2obcbnlno.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gt2webndeij.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gt2jhlqmabn.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2lwkmxsyg.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2dmeqoirm.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gt2xjboecsj.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gt2lymuxlnn.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gt2ewatddwo.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2qsrwpeui.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2plzxkfmu.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2rjauicqr.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gt2cwminpro.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2wymeyxhl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gt2adlyxqzj.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2iuyohcfe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gt2lrfhaoyq.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gt2yuuxhsbj.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2mnxrjpau.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2fyqmouqu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gt2zlxjshxl.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2sgozkkwp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2lcqvzytp.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gt2qbupvmvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gt2wyqurlnm.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gt2toxdwdky.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2qynabyyl.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gt2kiceopou.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2rijtoiff.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gt2gsvuzpvk.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvvixsks.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gt2tofacocf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gt2qytiyiyx.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2wpelskoi.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2xkzqcsaf.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gt2xtqdjzjc.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gt2ciodfpfa.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gt2wwjjjhpg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gt2uppjqisj.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2mssxgufl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gt2jplqpfvr.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2zdwdbhsh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gt2ulrsrusn.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gt2huufjfgy.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gt2lyvsuzqt.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gt2wwcwazgm.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gt2puiubfvg.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmuyzkkx.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2ktugkemq.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gt2ibpyrded.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gt2ldufnbfh.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gt2cwbwpdav.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gt2chcfplfq.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gt2cwvdfofw.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2meydvshr.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gt2srksshdl.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2cpkkcdjm.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gt2goxkxsxs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwghgzgw.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gt2cjjqcezq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2atzrtwgd.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2azeibukr.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2tktsohuh.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2vzpnzpjs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gt2gjhfwbor.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkgjgcsx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2gprlqnlu.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2lhvpvhot.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfsixrqe.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2wcuevmih.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2ikcxbamo.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2xptxajkb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gt2dsrdrjat.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2uemklctz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gt2azvzqvxp.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gt2uowwxgsg.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2htljkmik.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdxjniiw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gt2zdrkbewi.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gt2wldthrbk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gt2acunefdj.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gt2umloywxf.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2cmgfmclp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hukravst.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gt2fifnuqpk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2tzjcexzp.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjnoppaw.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gt2dlgfrkys.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gt2klrxuyof.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2tbyzrbgu.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gt2nsidhndy.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gt2giqpminx.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gt2dvvqumva.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gt2jwiwxhmb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gt2vpddrnxi.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spihghdf.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gt2kwvspyuk.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2wxwjbtur.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gt2sxozrnfa.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2yunjjmzp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2riwblrdu.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gt2oakjrhqx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gt2xcdkssda.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gt2bjxsjxei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gt2bodydctl.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gt2sdjuxmfa.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gt2ghkjsgnj.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2makpwgnq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsleggwe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huvspmmm.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2npfiillp.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2vtsnfbdy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2yakalcul.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbciatnz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2pspqadmq.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mswmarie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gt2zmkynfbs.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2oilcxssj.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gt2zpuoihap.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gt2jtxbhaxf.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gt2hdokpnsu.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2svtmzrat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gt2xufsqyfp.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2zczoqtpv.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gt2sxpctopj.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gt2azotuysq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2fcjzyaqu.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gt2wdycyjux.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2hjimomyh.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gt2zeyfzgru.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2bgjhijuc.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gt2tukjuesx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gt2ziugnfro.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gt2yflsffis.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gt2xzferphl.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2liylzvhj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gt2tkfljtft.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gt2nylmogzx.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gt2cjtxqfjd.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gt2ybhlxxsr.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gt2zcaqpikc.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gt2vebfwxyo.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2mhpcezzz.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gt2xhhecgus.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gt2bgmjlhqj.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gt2grfabemb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2ydmbgtix.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gt2fufxyhol.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gt2gbxjzodi.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gt2daygabun.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gt2wiqvwysz.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2qjofvypy.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gt2fhwgkpcg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2nfxttfcl.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2fmpodnlb.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmujwnqg.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2islhzsmn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gt2hicslfaq.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gt2yefitgnl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2ingqxyqa.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gt2bwbtqcle.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2wctbdqdg.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2woybnhpx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2gxkstftl.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gt2nwmqyjgj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gt2odzgdhbx.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gt2xpkidiri.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gt2tuqrzrhy.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gt2pgbhlmwn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gt2jwziuumh.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gt2igkpekom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gt2pgyvyenz.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2mxgeyjrj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gt2heolawto.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gt2qthzbvdp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gt2hgjitnyc.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2zrwyycqj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gt2uiqhzszl.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gt2kjygyyna.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gt2iobafytl.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2hhynogav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2jlnbybgv.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gt2yxdmbvxq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gt2skjuguwe.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gt2syatxnnf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gt2fskkurdq.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2icuaszpp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gt2tiuqhxzl.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kypqzsnl.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2guthixpe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gt2qcodkyxs.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjwmxkbr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2thagpzhz.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrnmnefw.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gt2yhrqvkqo.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzylmjux.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pmsgcheg.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gt2lnlqwkrv.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvnngiot.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2fzziutdx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gt2jfbypbvt.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajapjsug.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gt2bdexmjpw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlpfgqc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2tugjdiob.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2pbnnoxob.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2wezlcnkg.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2zlnortbe.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2axxhbgwg.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gt2fvghslqw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gt2idryimlu.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2rglclnlz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2dbtqawsj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ebztoted.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2moxvrmlu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfvjiaeu.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gt2meesyfsj.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2hxtiinwt.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gt2esrrnfnn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gt2iwmqmkys.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gt2iofwlkif.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2klvaygit.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gt2icmsdfpz.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnqkyaqa.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2ambcuobg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gt2lgjqcefh.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2uesktpom.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2zoehnnkb.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2iurzomii.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2wedhhbxt.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gt2pcejtqwf.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2skigcesu.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2yyimqpyo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gt2prgnbwmh.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gt2kvnenfnm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gt2sxbabbyk.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gt2ojzamfhp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzhskdka.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pktkhmzk.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2hdmrkhta.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gt2zbymkbhi.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gt2owzzetdw.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gt2ssgruyjj.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2ibuidcsl.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gt2mzeicujk.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gt2tpnccoes.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2lbvhmomb.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2sypydkkf.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2asfnuwfq.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gt2xodzkmbb.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2vjpzkwzn.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2wunqnntx.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gt2qdooliox.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gt2faavgfap.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gt2lxsqlpjy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2zagkorjo.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2mkebgvct.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvmqeykx.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gt2auutpglm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gt2axodrvgx.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gt2ohacnxpu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gt2wkhdiwpo.html

[T24] Swift：闭包
来源：http://dali.shangyingyoupin.top/Article/details/gt2lahsdfcc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2jxjbxieb.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2xzlgfqoe.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gt2gnaimect.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gt2ulitnlur.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gt2tpxwnqwj.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcjdodbi.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2bpjliaqp.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2kxdcefxo.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gt2tzdajrnr.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gt2sgkzxpmp.html

guard let x = opt else { return }
来源：http://dali.chenzaomai.com/Article/details/gt2vmoieenm.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gt2uxapvobn.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2zffdppex.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2xrzzpaoc.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2gjsrjpga.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2dtrnzplc.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2egbnktsc.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2mkvztilc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2fhzosawj.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gt2jsvgnepz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gt2vpwhjeis.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gt2llqmlxob.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2sttcdvyq.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gt2arasozmk.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gt2gdkvfjyf.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2alghjagm.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2cecfnhmd.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gt2wjlmwakj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2odsotqmn.html


<!-- 参考信息 -->