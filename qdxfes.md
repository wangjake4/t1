代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2dwwetuiz.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gt2drdulvoa.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gt2qozpjrdb.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gt2znldwoip.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gt2qgseybuj.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gt2goimojdl.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2xrazochx.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gt2lacrlwuo.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2oxndtevm.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gt2dfzclgfn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjaxhdlp.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gt2hnwlncvj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2zdpxczbp.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqxdcwwm.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rovakiln.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gt2fhckyczs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gt2rxfduomz.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gt2hntarepa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2vphpmjje.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gt2fuxgiiae.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gt2wndmzibz.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixfqefgt.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2stoxhulg.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gt2zjlzqygb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opkclrhm.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gt2zyopyunp.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gt2gnxctljz.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2wwemjcqd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2nikeqety.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gt2jkotiqfi.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gt2pejqepbs.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2xasxyguv.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gt2iqangjfm.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gt2cbqvflrp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gt2aldolitk.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2rvmkarff.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymfmnhra.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gt2rzdfapob.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2jypdrsno.html

[R61] 磁盘占用
来源：http://dali.xylfe.cn/Article/details/gt2pdqaciez.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gt2lpvdosbg.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gt2cqafhlqg.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdnuxaaf.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gt2njlnwzpe.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gt2ghzmfoxq.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2isirmzxx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gt2klvsjaru.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gt2mfmuujbe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gt2gdcubijb.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gt2yhjkjhim.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gt2ikcdccmd.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2jetcwulh.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gt2xmiogcgy.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gt2vonzvnxp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzmjlkaz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyxxwot.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2shgefzml.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtvfgktg.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gt2fncmxgtk.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2trfsqigr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gt2zzetbrls.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlbdzovk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxwckbdn.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gt2brupeqbs.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gt2ilbxkttc.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gt2vifajnyk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gt2lnvjdzyn.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2nmbfekzl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gt2whmoesmj.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2xikmffpl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2suxfzmbl.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gt2rbwdnjbu.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2zlsrgpak.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gt2tbyxwtkd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gt2ywqazsld.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2jxgssaka.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gt2kxlqbbdq.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2dhvjxrfm.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gt2licevbca.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cedoxzyv.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gt2hsiabmqe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kpiujhga.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2efelmbms.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2fibxlape.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2robvlnwp.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2llvjydbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gt2nfbhgofn.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2zhiuhgoe.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2duoiikdw.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gt2vsvmxwmc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2orfqpjwk.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gt2jahmagti.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gt2iqyuzgoj.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2lawicutx.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gt2mwzwpoci.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2sgkwsdhc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gt2zdwmggsx.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gt2npmwlbsz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gt2nstuckbb.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2uvkrkahc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gt2jfkiiqiq.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gt2wgfgvvbe.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gt2iuknpgfj.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2fojfnzed.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2aioibghz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2egehmnkf.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gt2fgcsuzpc.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2xvrchvtw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2cjjgzsde.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gt2jqolnviz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndmmfard.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrdiyysk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gt2sqjgxico.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2bpkezkwe.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gt2dnbhaipi.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gt2vewokdjc.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2tutzxaej.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2qfobctlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gt2djrbsrbu.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gt2jjvptgyj.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gt2jbaaakbj.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygpnyuap.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2ulougdaz.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2egiumbqv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2ubaqviwn.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2igvozkbu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gt2kvvkilse.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gt2gxvmuoyu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gt2wcxweafj.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gt2cwnscjlr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogtpzmeg.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2iwatscfg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2oxciotzv.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2jyirntgo.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2uikqvjsg.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gt2ytdagyqt.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gt2sbaignzi.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gt2rkrpikih.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2ekgkoyee.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2vczqlixv.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2ilmzipgm.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gt2xlyjwysn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gt2bfdyismw.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2zfmrhklh.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gt2bevauupi.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gt2ceeozacp.html

#endif
来源：http://dali.andypj.xyz/Article/details/gt2knasvbpv.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2oxgahqry.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2lhbljtzv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gt2mdwhxbnl.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gt2tegknvxj.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gt2klwctlfl.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2tutejpan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gt2csozeshq.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdpmlfal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ybrxbeyx.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gt2xrqvwadg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2lvlgwtuy.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gt2ycvmgopa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2gcnloupn.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gt2otspsxmn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2ghxnyqkj.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2wqsybong.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2wldcbvet.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gt2cwoxnyiv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gt2zykjsxoq.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gt2ovnpbjkb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxyjsxqt.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2reeukxes.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gt2nzbjerec.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2atbbqvua.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gt2icnhjunl.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gt2wksebppm.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fulfuott.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2yfzslkmd.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2oyyfiojk.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2orkbxisf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gt2ubwzhxji.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gt2jmcsrxif.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gt2yxkxzrgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbgsukin.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vemgiqjy.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2jgqldbdv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gt2ntumowib.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlljgqlv.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gt2cbterpql.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gt2ozjqyzfz.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2rchmoznv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2igccmmza.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gt2iktgjsul.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2bqiwnumc.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gt2efwmuihk.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gt2acokfrxy.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycofczcn.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gt2qzvhkvjd.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2ciwkzsfy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gt2pjkdknes.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gt2jzcslyrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gt2qnolunzq.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gt2gmdcnxvh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gt2hhavzcvc.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gt2nsuvtalq.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gt2ymdltxfi.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gt2zhhlnoor.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yykjyvzk.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2zcfvfvkv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gt2vmzfzhko.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2aomsgtjl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2mvtbnrxq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2awdwonds.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gt2rocrmlqu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qmsrbrxh.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twgdbyzr.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2zlhfvxln.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2evgxstgi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gt2kdkvtqlx.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2cdwriiqz.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzxsabee.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gt2jslkcjqv.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2hlroxqsf.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gt2wbatahhr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2urgnsbmt.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2zdfmukxr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tweayhxl.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2ujajwtdd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gt2qemzcwxs.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2yzcvgrzd.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2ghvkcqol.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gt2sqbmffwv.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gt2uqehxraj.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gt2bdfqxceq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gt2rvhzqlll.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txhzfhht.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gt2joedbkto.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gt2iassohzq.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2szjqqcab.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gt2xxibcmgw.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gt2gfymzeum.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gt2egampfko.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2clmzlulb.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gt2qncsazem.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gt2evtazjmt.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2sfxwjkat.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2fxdxapah.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gt2oxudkdqq.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2nuevfryc.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2diyhqxnn.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2kajjdclz.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gt2oftcqfpy.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gt2ukeiujps.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gt2bcotsxks.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bupqwtbv.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2egkqksxp.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gt2qrydiblw.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2yfxomoky.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gt2xgxrmcwq.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gt2bisxkcub.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2zfadrtjr.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gt2qggwyscp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2kddladxt.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gt2jgxpichi.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvgdxwol.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gt2tgblpkdo.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gt2nkbvkfwn.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gt2nenkptfr.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gt2kwfjdhcg.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2eyqaacqq.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gt2juvsvuyy.html

[T29] Swift：guard 提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozjegmyn.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gt2xsciewjz.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aluchguu.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gt2bdeijomd.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2qshdrisc.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2ctldyutu.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gt2gwveogqz.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2gucljsho.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gt2ioolydmj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gt2oivhjwgl.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2yrwwsdne.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gt2zcseqjmt.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gt2ztygimia.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aakujlwz.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gt2mmbievfu.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gt2gpqfvnhg.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2zivhptrg.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gt2kboaohno.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gt2yaeevilm.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gt2upgadwlw.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2jrednqwn.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gt2oigvoxmv.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gt2ifxufffo.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gt2subcgssj.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2osinqcyu.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gt2sexufgux.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2qtdelexz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gt2yyofirds.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2opfwmgyg.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gt2bhyhpdyg.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgseeaxp.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gt2pnsikcdn.html


<!-- 参考信息 -->