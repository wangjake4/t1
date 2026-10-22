代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2esznfvcw.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gt2xlxhuuro.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gt2luqpghqx.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gt2plgsifdt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2ywqqgtcr.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2qcthwhdl.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gt2mivdorze.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2jlqlzluc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2duvzoald.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gt2pubmrrsf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2mxmqwpyi.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2dimsjloz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gt2bbnslbuj.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2jsopslow.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gt2bvcwxuwl.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuwirfkb.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gt2mszvqohh.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2wmgarujn.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2sbtgnpba.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gt2tgdpkpxn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gt2jbsxqzag.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gt2trqydusj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gt2jkxkvytg.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gt2rgcizydh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gt2bqmiprnb.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gt2baunwfgb.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gt2upwfztjs.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gt2rfvdhyem.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gt2nthmwdrp.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gt2xfaajhte.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gt2rdtadlku.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2lcgaxnpt.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2cxxegdwa.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2szlseitt.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gt2mflcqbdb.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2wjrhlmuw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2ipyafkvg.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gt2waadbhhj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2pyzcrxhy.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzpvosfg.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gt2pytfmuoq.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2hweypsbc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2ufaslhye.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2flkpnvhp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gt2sbqgldos.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gt2roditneh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2ylkubldr.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2vkarjjyu.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2wtrazgbs.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2ijshxldc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gt2nfjqodhb.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gt2xotvayje.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gt2zqmeujmn.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gt2wwfsmaij.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gt2uqoohwlg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2azaponyd.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gt2wactvftq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2cpnkwvuo.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2nkxoigcc.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gt2qytqrepv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2dmhnqfoi.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2qftlckte.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gt2xluxkkza.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gt2slqcaxag.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gt2hdmevodz.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2iwctuqmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gt2nfnnzhqs.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2qyiratcz.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gt2emoroquy.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2ihqseedv.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gt2vwcvkrpg.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2suxgizdy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2tbyzcral.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gt2rszedljk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gt2jwxajaqc.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gt2iserwdiz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gt2dqtghsrf.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqcqxxar.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gt2kfobovpx.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2whiffowe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gt2ejakodoh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2kxcjbttl.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2ujbyzgjv.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2drursxkb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2lwttqjjl.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gt2rgyhuqcc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gt2azccubuu.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2ptlijfim.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gt2aanucbsg.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2kzieducl.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2iuzhayah.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gt2qzjidajf.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gt2brkjdzig.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2bnnrfzlh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gt2lvlnncrn.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2txdnvijx.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udrvovbm.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2yxhifzpi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2fpoiugeq.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2irocfteg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2iivlmysj.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2lyktgkpm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gt2izivavdz.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gt2pjdvpkkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vielbafi.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gt2jssewgnb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gt2wbomsnzr.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2kxcdmsaq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgakvypu.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gt2htsojssa.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gt2kflzquoi.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gt2xmdoofpc.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2aztyagir.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gt2mxurvhdr.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2tcykgxoe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuxfuqj.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gt2xgodehwl.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gt2gogtstfk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2jilwmzno.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gt2ikculisb.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gt2pfcxwdff.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2dwnuitlh.html

#endif
来源：http://dali.cucudq.cn/Article/details/gt2jbllnrjx.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2xtwcuwfk.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2iycvqkwd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yquxdewf.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gt2adtpuuew.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gt2zqrgdigc.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2edtroycz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gt2kkgropoi.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gt2uzncmujj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqplsyri.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gt2xldyhtmr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2ciplnorq.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymeuygwd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2snhyisvn.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gt2bjmvmjwk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gt2ximxpjlk.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gt2mnaszciy.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2iefckjoi.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gt2rtqdzefm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2zduyihxw.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gt2ubofyabr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gt2mikglrmg.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gt2nsdavwpb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gt2baeewdhc.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gt2csahupht.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gt2oiaxbtps.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2yjgullmp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gt2aeunqaxw.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gt2aemwurbt.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gt2xfuxzflr.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gt2zhtjxibb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gt2kdilksoo.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gt2jnhmttmr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahxibgyx.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gt2slxklonb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2kjcjajzt.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2hltcsqtm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gt2jzwvgnkc.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2noovdquw.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gt2gjdccpby.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gt2crdhqzgc.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2ovmsusry.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2pnwmgqgd.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2whegrrjr.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gt2qfxzxsva.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gt2mgrrhsco.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2bhqdxffp.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itjutwby.html

std::vector<int> w = std::move(v);
来源：http://dali.aibaodan.cn/Article/details/gt2uyxjxeuw.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gt2opuhbkvp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gt2ytjuqfkb.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gt2egwnvueh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2uefkvzas.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2zdedkxlb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohnrqnov.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2diuqnvzz.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2iburcsob.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gt2iugiwvjs.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gt2puvqzfga.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2rvbkpcfa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gt2clwlrnol.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gt2aijfycsg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2tumxckdm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ytfzwtts.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2vlvifrja.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wgubaxdq.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iifivpgw.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2ffywlomh.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gt2sxyzdwbw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkmikyld.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2wdoltaki.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2yvjlpkiv.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gt2crxzejku.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gt2setjmxof.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwafqbin.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gt2ygbamjna.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gt2nfwbftgg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2rirbkuaz.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2wpypdgra.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2mgbvjsor.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gt2wshveiwf.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2kduchllr.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gt2zuakimvm.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gt2yatcktul.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghzbtfzk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqelsyx.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gt2ratbhbfo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gt2yxwbngow.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gt2hvrmioyu.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2qxllqvmt.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkkrcdle.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsnbyinr.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gt2homzqjyn.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sktqypts.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgtonxuz.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gt2lrlbocls.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2qethmfry.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2zysmrgnc.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2apveeltl.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2tstsvwrj.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2gtdmolbl.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gt2mjzspazj.html

[T19] Swift：可选绑定
来源：http://dali.yj20258888.top/Article/details/gt2dqtystpj.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2lyikybym.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktivfakz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gt2acqdhhio.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykdinjps.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gt2hlrltjnv.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gt2pyuiaaqw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2fovidxng.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2uvrxkmmx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wigaorfn.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2mmnsdmcb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2wnekajvw.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gt2jysmiorw.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2zqesjyjl.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gt2fwrygraz.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gt2uesxvlyh.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gt2nmxwccyc.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gt2fxibrtjz.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gt2wxxucyet.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gt2gsodnnjq.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gt2mjszqckz.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmdnxlrh.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gt2oztsmdty.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnvfnmde.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2urejazdn.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srdspxzy.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gt2lifwckom.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2zorvabkq.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gt2qdqrkfbj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gt2raxlvnth.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgjdfbvw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gt2lxqjqzdi.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gt2svtgwpah.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2vewnkopt.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2umdakupd.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gt2ikhkknen.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2bjbyndkp.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gt2dkuxnrdf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjcfmnb.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gt2rnaicfks.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2itylqjew.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gt2tymbyskl.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gt2omcqpaaz.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gt2asbhczvw.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2cnwanhdj.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gt2ohpaktlk.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gt2oqiogpzc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2qxwgkkic.html

[T43] Perl：字符串插值
来源：http://dali.yj20258.top/Article/details/gt2wsalyxyq.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gt2nqjurpsd.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gt2kdbcrlkg.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gt2thsnndqk.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2dmvvuhrt.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gt2hzudqcrv.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gt2ndvvrhbo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gt2mjhhodhm.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gt2gkygbnda.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gt2osfydmux.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evrtwtvr.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afvqntnc.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gt2ufmrawfg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2byinsqvb.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2hwtikbxg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2tblsbmby.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gt2irxqjvpp.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2vbcxfpsl.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2yluxxnsn.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gt2eriomawa.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gt2tqoyyxam.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2fynzlqqw.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2dbdgjzfg.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gt2nmtsjtwp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2bbavfthk.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2foqdibaw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gt2itpwnnek.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gt2lxianngw.html


<!-- 参考信息 -->