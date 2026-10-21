代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gtoptiyffd.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtelkrxgwm.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gttjzexysc.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gthqqgftnd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gtmzvfgfut.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtalhmhpit.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gteszrodgm.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gtyiggwixw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtpfvxiidd.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtupiiwqao.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtusgkikyl.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfivfxii.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtlzbcrbpv.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtjiskeuqx.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtrrjwwydc.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtiqqtmzyj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtogblkbam.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtqkslcrsf.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtbnlalgvk.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtdjuylpgu.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtgxkteryn.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtuscyypey.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtnweonwpo.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtsjhiyjpo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtekwwtomh.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtfqeofjau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtiyxpzpjo.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtkqwufygi.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gtxwpxcofz.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtwuncfpkm.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtnfkqtddu.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gtpvorpeor.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtusopfvgy.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gttwpznuki.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtujueegtz.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvnfgozi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtoddkorcb.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtotqvuoyc.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtpockrtol.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtdeqiuhjc.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gthwbyvayp.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gtmzmicciw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqiowlvw.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtxwclarms.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtdccmrduc.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtqklzlgfz.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtjzawbseb.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtomchogjb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtlekypxbo.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtnxfezyrm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtglijrkjg.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtmlvetvgb.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtiajdimwq.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtvhsjnxsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtakqkrdkk.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtxsqwsbdp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtsslytujv.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtrfynijcr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtcafzmash.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtcgreknfv.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtolgtnpsj.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtwqknjwqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtedhnmskt.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gttbxpavhu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtoumgaaek.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtoucfirca.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtawxndscc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgowsbaow.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtrjpgjnec.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtohnunuwp.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtzbazoacw.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtacknnuve.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtlrzipaoa.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gthegpzjne.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtivggytca.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtnbfomesz.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtnroiwibj.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtpqoowayj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtlwlbvakg.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtvylvnpbu.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtbdikptnz.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtgzhufjqw.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtdsbvdqqe.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtihwukcpu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtsvcpxeba.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtgpyzojwz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gthjsckpny.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtktfbwory.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtaoapnlmh.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtejvvcrlj.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtcykwmwov.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtizlkuhqr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtchbozfdd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtbfouarah.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtpvgsdniq.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtjymdocvy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtqcvfxlxm.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtrugybyph.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtboiisisu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtcqkfvvhj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtsxmlgcwn.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtzqtqpojx.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtjhpcixib.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtwojnquel.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtnkqcvero.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtwkjhrpuk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtflhmqips.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gthzkzisdu.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gthsylvoof.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtuaveywpo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtrnlnqpyj.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtnixshtho.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtzetqxyjg.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtjmfjqwel.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtfymwqmpz.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtignetaum.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gttyesiocy.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrjrbzmk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtabritlja.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtezngwfly.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtgleqbdxi.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtqecwpyjl.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtryfurrcq.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gthianqbpb.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlwwjwsx.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gtoxujknej.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtqaarmgkk.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtnhbytsgw.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtlyxzvfhk.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtvltywbdo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfkbatzf.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtbzgykbfu.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtlpsqnzpx.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gtdidbtxcx.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtomiireav.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtuowwalrv.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtfkbchwsg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gtvhglnpzr.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtsoyrjzxj.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtbdrmjbnf.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtkpfnhbwh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtvikxlioq.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gtxfwguqok.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtosnvhsrs.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtqgexsxkp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtpucxoxwh.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtqyobibgc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtwvdtlhlc.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gttnzdetjh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtygyhcmjq.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtmllllrnq.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtobidgxef.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtfiebpqhh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gtnohapabj.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gturtxryqd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtsrzievlp.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gthpdqrpzc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigufen.top/Article/details/gtrybzoacw.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtzhuxhirq.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtlruglojz.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtitejwlzq.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtxvpjvgsw.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtnunsuuwf.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtxgtxflyg.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gtgbdrntxq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtziaolbgn.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gtuwmftcrv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtqawzturd.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtrkaioesn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gticezaulc.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtdrejupll.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtlihqcmqd.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtsyleuhvh.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtkogghdjx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtymrjbtsa.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwfanouj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtragnclme.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtfklorraz.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtnzuoftku.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gtkjvxlekc.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtqptbppjf.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gticgewzwb.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gtighdolne.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gthwhqkqvz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtyjloyeri.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtzgkhldxs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtbyryockw.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtzbzkvguk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtljsjbnly.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gtxvagcfgo.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtutspcagr.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtuwruckpn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtzribrqey.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtotzasmqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtqkphorgz.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtdhvfcbsg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtuqxhuqby.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtppbouocd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtasdxpalq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwuidbnzb.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliidmqhh.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrowzekh.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtkfazwibb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwtblgrw.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtbvlielfo.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtyscvfhgt.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gttlggmsrr.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gtrebrmkty.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtscylgavh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gticsbzges.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtojhngqiq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtivgqzglv.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtxshohxkp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gttgzdoowf.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtfghypvcn.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtpbjqoazp.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtnnyoirgc.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtiftxymde.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gttjpumhmz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtqsbrmfdl.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtvjpjudfd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gtdqsfmvme.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtqwbquhec.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtwdpvesec.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfvrpvws.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtzfsqulnt.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gttfpqxikr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtcicencti.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtztcwwtzj.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtizrxrrkf.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtuiprkbpi.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtcdrwvuas.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtkttdltwy.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiwyicks.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtttygaduf.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtkhvrszfu.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidbtzqld.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gtkvjwncyh.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtpizzcxny.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtrozejlzc.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gtbujztvtf.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtjdxroeek.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtihyoqawc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtbwcyrqwa.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gtksdczrbg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gtwuwpczpu.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtcqunvdxj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtgzuprjzr.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gtmrnfulup.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtcytbycyg.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtrkzbgiry.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gtywgvjwyz.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtkixsoerp.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtpfrszlwt.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtfgxowidi.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gtflnwtzki.html

[T29] Swift：guard 提前返回
来源：http://dali.daxiang520.top/Article/details/gtmjqliamg.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtkgtbjwic.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjluwgfuj.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtnekhlahr.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtfxphsqdm.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtretejfjs.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtgcgaqudl.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gtpuiktxpb.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gtoqyhzrwh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtkkkctvhk.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gtwuxqtikr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtmxhvbext.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtcgjhidcf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gtpscxgklw.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtpegswjvj.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtpjcdccxf.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtpikqkmhb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtutvgsbjs.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtgcsxcpuy.html

if x > 0 then print("正") end
来源：http://dali.hammf.cn/Article/details/gtqxouykqy.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtuojuewkn.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gtmvrndplm.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtubaqorae.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikajqyud.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gttsiidwhe.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gteztdccnz.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gtgycpdpjf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtrzbrlsax.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtmmvgudrt.html

"值: $a"
来源：http://dali.cdnleiting.top/Article/details/gtxlweansi.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtknexznli.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtegkakale.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtodoqzmys.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfwzjcst.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtmnpmhwif.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gtfxblueet.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gturpcuftg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtryrnvcwf.html

[T48] Perl：正则替换
来源：http://dali.ivvv.top/Article/details/gtdzqyugdn.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtvlswrsdr.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gtdjhjvblp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtjddraevt.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtxyupssrx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtkzzrssna.html


<!-- 参考信息 -->