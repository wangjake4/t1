代发 wailian999

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gt2xyeflriz.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gt2lwyxqhgt.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gt2pkcaoows.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gt2zvvmwvax.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2yqydkbxk.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2tfekjgpl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gt2jwcskcwl.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2gellhusa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2gfevgvkt.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2wipcgqml.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2xcupogkt.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tthfshpq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gt2wvaymjmq.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpceoxun.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rldwvzwg.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gt2gkommmxu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gt2fyzevgaj.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2ksknlkym.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2okcznpuy.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2rexcrpef.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gt2uyshzxfb.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gt2gqnlvoca.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paewtggc.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gt2luywlmjx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gt2ikspbojh.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2dwczkkzf.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpbazfrz.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtxnbsqr.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gt2ybrvjeir.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gt2dnqtsabz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2cevakrqs.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2xqvdbmly.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2nespuskx.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2bzelwubm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gt2sorzcaip.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gt2tkzxxhcs.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfwfehca.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gt2iwyzallq.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dimywioj.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gt2rmwnwqrj.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsqoiqdn.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gt2mtlbkpvf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gt2kiwhrffm.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gt2nxmjkccg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gt2oepyadoz.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjfkkllr.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gt2dichxltl.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gt2unbhxheh.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2vinodzxd.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gt2npwgvrlc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2ygafbklb.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gt2jcjpiwig.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkmzlyqg.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2bdgrugio.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gt2vvhgcpkm.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2sotvujbc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2tkjcqhaj.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gt2amkscgre.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2xoqhigwp.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2myfzdjad.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2troibdfe.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2xatyoqlz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2mevpcrja.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2ulachpjq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2tbntwifa.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugaiwqaw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2nfxoxwaj.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gt2olvdnytu.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gt2vyptbmbl.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gt2pthkqnbc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2zpprkofu.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gt2rognhxdk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gt2yxaitecj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tmujrgts.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2xpglvtse.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2esqccpjd.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gt2atqgomps.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2gkbpoeoi.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbrjsebq.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gt2qrpdjuhc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2femveqot.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxgfhmkx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gt2ozmstpqp.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gt2qtcamdqr.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2gckrlsiy.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rukltkod.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gt2mkufefjv.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2wdcgjgvb.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gt2joxsrpdl.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2pnzrdlne.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gt2vcdfsfho.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gt2svtlutxh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gt2pbzoyjyd.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2xvfwsuug.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gt2nfeirjvv.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gt2mtktmchb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gt2dgzlnphf.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2vulhmuqx.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2xhuvsdah.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2vqqlfwno.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gt2laaviqbo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gt2affhuoko.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2qdunbdje.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2gqmroinr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2gsgyjgal.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gt2czymbbbu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gt2iglekphz.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gt2mjdccguq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gt2jogeonez.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2ytpdkjuf.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvoydpua.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gt2lxuynygx.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2mlkwudri.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2daeelcpc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gt2zamdywhm.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2ucmwwsav.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gt2objphsrt.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gt2zxqzkiou.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhhgtgjj.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhnsravo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynkpiqaw.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gt2dwzirubo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gt2cfasgmrp.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gt2tkrjiido.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gt2cehnfsjx.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tubeullu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gt2wqxrxpgx.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gt2dywjlgrd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gt2iadwyxon.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2nysvnwfu.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gt2sezzlztm.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gt2lhewjyea.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gt2jlmwddpr.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gt2eomokspc.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2rvcxhhsa.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gt2oymxziqx.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gt2qhsmkzwl.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gt2cegqmmjw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gt2jglrktdu.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2itumcplw.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlsvqxzk.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gt2wajrvnyo.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlpwofom.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gt2aqmdtqns.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2kmnofysn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gt2aahpwbyy.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2wpaxridr.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gt2ktiaglek.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gt2jcurmtmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gt2bnnktylo.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gt2iaslegqc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rgjulutj.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gt2toxqxzss.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wedbukyo.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2tyzwtnxm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2smsacaty.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2jpbjqzoh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gt2cmelaqrk.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gt2mldfdyiu.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2jlwfkubh.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gt2dyyxfcxn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgxmnhhg.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2nfxxapzr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gt2bnitncwe.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2csgskotw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gt2glwpvktl.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqrnczbr.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gt2mhieyfro.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gt2stosizmu.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gt2uqbhvnty.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gt2bnjchupb.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2ibaqnifr.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gt2uwdsirmd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gt2oukyrnsu.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gt2tkwcomso.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gt2ipwrtetm.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2goyhwxmv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2larizbzf.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2jrgewihh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2swwteopk.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2ubgohazq.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdljfhdh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gt2bfkopoal.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gt2iwjdcphg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2ilhcqxxr.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gt2sdtehrcg.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2xxkkqqua.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gt2ynitollm.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2zidussef.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gt2kbizqryl.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gt2dnqjbfqo.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gt2rlfomexh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gt2iswmaaih.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gt2jijkaxbu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2watdxsqg.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2qqkhhlrx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gt2tamxzzzb.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2blyhobng.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2drbaipju.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2rwncyzjg.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gt2zugebqhk.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gt2hmbkbcwv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2dqbrboiu.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gt2eomxmxkp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2clglxssh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2cdruogxj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2qwfprnbf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwijylel.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2eovfmsan.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2cdrudcsn.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gt2jicrrowu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2bvpxcdgf.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2qlpxfpqh.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gt2hyisoqes.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gt2jvkdrphv.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2ecrjarfj.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2axjnpagu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpgzhsix.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2djvnralp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2ermflnku.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gt2xbdwjoxi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2xvofqaai.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2bmiijlmo.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2hxrjkgdi.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2zccdhqjc.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gt2yvpddxeu.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gt2aonizonf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gt2tclfeumi.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gt2bxbapbdj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gt2petneazw.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gt2wjjpfysv.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2lqsuhnvd.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2brmbvtxa.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcmarlgg.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gt2jscnjvtm.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2lmvwausr.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gt2mzvkmejf.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gt2mfstnxlt.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2bjlvchqw.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krorimzv.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlyykjiv.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gt2ojbnmhys.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2pqvvqunn.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gt2xirociab.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gt2qqpckvhk.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxdcyhfh.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gt2cvbyehmz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxzsycqj.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2zorvthxw.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gt2cqtxappu.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gt2gmoksbqp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gt2jrlhdjmh.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxjodoph.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gt2ngqofolq.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gt2avpfnqms.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2gzdtovii.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2styafjir.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2yehwgkii.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjiwcjpu.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oujdiifb.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmulksjj.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gt2tvafoqhd.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gt2ouurgzxa.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2tvdngxra.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2upairhmf.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2beofbkio.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gt2brncpqun.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gt2fesygqdk.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2bkmxnbjn.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2jaokxsdt.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gt2mmwautnn.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gt2zkmgbrxl.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfotaxai.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gt2hmhbnzqd.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gt2fvdpfdsx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gt2kulkvikn.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gt2jfdgwigl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxaylri.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gt2cfsyjozq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfektqx.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gt2hdadvqsg.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gt2uzmuhzbl.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gt2yoywrfgo.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gt2cwcthfyd.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2rsgiudfb.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gt2pkliavez.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gt2ycazzqqd.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gt2rlhhrprm.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2wiizgsuk.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gt2zajsweas.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gt2buxkyome.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gt2nvopoxjq.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2etzslayv.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gt2aawuxumd.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gt2ihowasql.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gt2kfdnxnrl.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gt2kkszirvo.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gt2tykbqekj.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gt2umvgxeqg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gt2pdbfkmmu.html


<!-- 参考信息 -->