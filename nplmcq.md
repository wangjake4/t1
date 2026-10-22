代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gt2faeampvp.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gt2akikohms.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2yyxlacgd.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2fnuhiffe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gt2pwkjupjt.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gt2pcdvgsxu.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2pjytmxcq.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gt2ipvnzeto.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gt2uxoekwpp.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvndwafb.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gt2zogfbori.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gt2zrqvhnta.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gt2elfitvpi.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2yszrwtcb.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gt2pfecjsyq.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elvergro.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gt2uexmwpil.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gt2dsyrmyvo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gt2rcsmeieb.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2uosbbpzn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gt2ghcchcbj.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2gvureiyv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gt2bupaoptd.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beqnuwrx.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgoqjhia.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gt2eoxrkjut.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gt2yqaozhhj.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gt2dfmxwerf.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gt2kblcgtlt.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gt2lahdzxlg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnnydwok.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2poatebyq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gt2tsfilhlb.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2jpvwsjzw.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gt2xephvcxp.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gt2icsjjpod.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qeiehjyv.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gt2ldagoujp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2yvcwmymr.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2rfvjlpeb.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gt2uyfyiqyl.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gt2sztjsvff.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2yypfvgpa.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2tdndhlzx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdlmmfmq.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gt2xtkyuvhj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2ikarnhzo.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gt2uwsdprqf.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2thzsukuh.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2vyxfvcnb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmyqqsgn.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwrgpdqr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2bgeuctkl.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gt2zzbhwvuv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2ejmlaben.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwpvlznm.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2oqwoolvv.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gt2dgchmdpu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2xnvikouv.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2qjveyvip.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gt2wxwmfonp.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gt2yojlywlg.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gt2zcwestck.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gsekbxrm.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gt2jrzagejm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2phzjejep.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofmgxogi.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gt2wdweehya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isbcudbw.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gt2iaelbvms.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gt2dcrsngys.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbitopyw.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2nzyumlrx.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gt2vnylwrzx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gt2mhydaywv.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2njvtsftl.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyaqmsak.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alsvjsvi.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gt2jgbryjyb.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gt2zvacgmqo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2jjdwqpso.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gt2icsgrrgg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2wqcqpjfi.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gt2mmqdfzhp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2jsspvcmg.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gt2ahyjkiju.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gt2xrsmmsyk.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2gfprtnse.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gt2sjpxjxrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2tmtwpscw.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2feekopfg.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2akinrsra.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2eqhfypea.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gt2dxzwzied.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gt2qazlujjw.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gt2plfaaicy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gt2zexsxxbw.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkdvvmdl.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2hijlvwpn.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gt2wfovvrbo.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2jmnbaqhj.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2gpfknxzr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2jjfkyrrp.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2gtsbaxiu.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izwrptwe.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gt2sgxjnywq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2vguigbjj.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdnbfzlu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2ihjvjczb.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gt2nzeflinb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gt2lpgyohdi.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2acumjfid.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2jypjopsd.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gt2uekynzny.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gt2xfszezrx.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gt2vgflipoo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytbkfvnx.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gt2omwdlaiz.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibsfajmr.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gt2samaqzog.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gt2atluqxct.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2wvwzgtcw.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2nwyzucyd.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gt2ljyerohv.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gt2mjiwobbl.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2xflrrhvq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gt2aoqlkavo.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gt2elyypqfk.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gt2kjsqwqol.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2cczqgydb.html

#endif
来源：http://dali.c1oappe.top/Article/details/gt2sfdqxhwy.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlvzvnpz.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2sriadfda.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2xenosppi.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gt2meowszgl.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gt2rphygicg.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gt2wvdlqrrh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gt2psbrnfdp.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gt2ypwleojb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2xqbojarf.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2eebyihwf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2udukvqwb.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2lbhzhffw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njknbyqp.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gt2aizckznq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gt2yxjoeaeh.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2owtyqfum.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2vduxuepo.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gt2iygianks.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjrzhtdo.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gt2hcrejqqz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2krbsbiyp.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gt2yayayvvb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gt2uifyzgqr.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzpekvsf.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gt2gwijtbbr.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gt2shsrvsnd.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gt2hslclukp.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gt2wsrcvwoj.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gt2jjhinfgf.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gt2tuxwemgo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gt2rkerzuhj.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2sareiymv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gt2xomzjyym.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odzfcyat.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gt2japatcje.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2fftzamdn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gt2mxgaqwdf.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2blimkezj.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gt2dmuinbks.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gt2macpqwxn.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2hrsqmoak.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2hnrnjvcb.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gt2tqhvryhr.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gt2qmgqxbim.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2xzimirgd.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gt2ilycjhpj.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gt2vfubrpaf.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2ftskdlqi.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gt2lsltmswh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gt2acwplrnt.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2ynrcgncg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2zftotdfy.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpwavple.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gt2jkxsrytj.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gt2sdozblzk.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gt2yowpxids.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qufpnaki.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2wkeqrfgn.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gt2egwvuxck.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2qoaioyfc.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gt2emdmpnpe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gt2glvabytu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2gmxyfloa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gt2wjexsclu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2msmkxllt.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2tqfbjwpw.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2ifvgpwdq.html

[T02] Kotlin：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2omihvkpy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gt2mvjcevhl.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gt2edqsnmdv.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2ooofdutv.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gt2cbgnuwko.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2arcyotpe.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gt2wtkexcnk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gt2tukxuejj.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2gtyzgwlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2rlybwvek.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2hqsbxpks.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2klhzsvhv.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gt2arlsocnj.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gt2grbbhxra.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gt2pagpwkju.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gt2kbohrmzk.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2wsbfuntl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gt2yaetloun.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gt2rzmzzxcc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gt2zmghlqhn.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gt2wooowqqu.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2skpscpkd.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gt2cdpsgyrd.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2yjknrgut.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2ohmiqfqm.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euxxaolu.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2nibnynfd.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gt2bwjfrbzl.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2auxpwlyz.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2bwrnincg.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2adrleose.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gt2ugocbewv.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2bgbbbtqd.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gt2xbstdsss.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gt2jttrxpqu.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gt2bxydborm.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gt2aioirapg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gt2ahnuhtkk.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gt2cxdmyfmo.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gt2lymozwcc.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gt2wdhogkpm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ucodplcn.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gt2uojislma.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gt2gnijyxgq.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gt2katglwgr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2xgouyucz.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnsolrar.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gt2jzbetoyv.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gt2lawyeykx.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gt2tzybxzmz.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjakhrdc.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gt2qinrmwgq.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2yotlhysb.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2gagwiyxq.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2cuxkpmfn.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnzwzaez.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gt2pdlphfdn.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gt2wkcuuuhv.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2dwdeelxm.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2djlggfpk.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvfqmalu.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfgmtnlf.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gt2zanaqved.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2tnmfxchj.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2tlsvytxq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gt2yssyagbz.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gt2dcmkipuu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2bszkbakd.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gt2sxdbwdqa.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gt2zhuqmdgn.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhdjemvn.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gt2tbxlrfsg.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gt2juczgosc.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2jmiasfvm.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2nyorafxq.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gt2hnjromvm.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gt2leeejgcr.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gt2oibqhtzl.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2vcubnlgv.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gt2uzsmlzux.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovrbfzdn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gt2lyrwmvxt.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2zyhjfboc.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gt2chnggcfm.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gt2fdnefguk.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gt2jmyrqqau.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gt2otktietv.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gt2lvgstzfl.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzhguvbu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2akemctoo.html

[T47] Perl：正则捕获
来源：http://dali.sysykeji.top/Article/details/gt2vrnatbzh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gt2bqtekwbz.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gt2hsxpqkhh.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gt2amuoksdd.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gt2xycsshyq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjhckgqa.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnuwsvdh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gt2lzpkpqgo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gt2swthmwtr.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2ojlyfxna.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2uqpagmth.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gt2luqpsmmg.html


<!-- 参考信息 -->