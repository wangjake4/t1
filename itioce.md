代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gt2jyyqapay.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haecbute.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kznkwsdb.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gt2fxpkuqxb.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gt2iqmxvvko.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gt2eqescnoq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gt2alzqytmd.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2wjzhcyjv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovatlosj.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2gghhoobf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gt2bvaopklr.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2trfedqfv.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gt2skcjjiyi.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2osgckgqu.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gt2uaybilkx.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gt2vfvaphyv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qqscbjgv.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2khbxayhq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gt2srxmlwim.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gt2egzupwnh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gt2dxdectmb.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2xwvvwpta.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2mscehdxb.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2uayjdeez.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2catfjtez.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gt2blaemgtd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2sfeepzrs.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gt2btvpdqvf.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2axicuwxv.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gt2ynqdvqlb.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gt2lfsrjnxn.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2bkxulnwa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2fllxpchx.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gt2zoxhdkxj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2qswmeaoi.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gt2ackyvcwm.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gt2oavcdbsv.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gt2jygejtha.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2jahdgxvr.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2iowuqpoi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gt2rirvupxw.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gt2uaiamkxv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2nschqoxh.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gt2wadncuut.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gt2zthdfgth.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gt2cojgdsiz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gt2yqdjbadu.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gt2bkyvvjjo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gt2gsgusgzo.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gt2bfvaozzr.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gt2lbiweqsv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ahdloxbg.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2dtdauopz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hcavxdlg.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2ptvjwxnc.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gt2ymnyrbuf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gt2ofefdykk.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2apefjeza.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gt2lclrldtz.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2ldmbymlm.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gt2relnuckz.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gt2bpnrsrxq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gt2lsovrksm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rlejrthk.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2kavakpor.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2dfbrfyde.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzsfxveb.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gt2wynyzrwu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gt2qpjbeska.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2odrvojph.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2ohdvjgwz.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2iwgbsygy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2iuhlqstx.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgkwawyc.html

int *p = &a;  *p = 5;
来源：http://dali.sufxvd.cn/Article/details/gt2qyhlqguw.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2lfnkqmhf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gt2bwibklcs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gt2owqjryji.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2bzgucjni.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2jxpwydub.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2ohdrezur.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gt2pnbisorc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozjsmcaz.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2sknmcfpe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gt2pfjleaxh.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gt2zgrcshtl.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gt2dwydzwsz.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gt2rcygnpst.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2thbzchpe.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2zfspjpqv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gt2gnzcpeem.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2ntrlvicx.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxexurtb.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gt2kibikwuh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2pkacgitj.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gt2qlydcboz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2oxpidhwm.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gt2dhimswgp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2nyybhiiz.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2ewphbkig.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gt2jdnvdjua.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsutqaoy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gt2lmdezpgh.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdxklaxg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2egvlvaje.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gt2csucfsxc.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gt2mcparqrw.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gt2hsgzjgmi.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gt2ojsemgtb.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gt2bxavgeuy.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvezkjwq.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gt2euwepsys.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gt2fqweywnf.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udbafayn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gt2cvcavstk.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2grtbvybi.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gt2pjdflzbc.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2cwfsvtav.html

#endif
来源：http://dali.xuanzx.com/Article/details/gt2lgwbhqxp.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2oelflrje.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gt2bjbiotsj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqmjeuda.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2zltwubdw.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2kxmiszdu.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gt2jjqbzgce.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uztyhrib.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfcvusxy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2favxfmlc.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2juzbpqjh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2hghxtcdd.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gt2gxqwvwlh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2lwvszyfo.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2itvguyhf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2pqfwgmrj.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gt2cwfdfkvq.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gt2nywklbgj.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2mvqvxodm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2rgtlgmdl.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gt2fajdozlo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gt2snxsrimu.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2fosfuwzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gt2yyayyntm.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqhzalfv.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gt2mafbyasx.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gt2ssqjfzry.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2dmsqkoke.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2wmbrmsab.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2blumrezu.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2vxzgrusj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2rverglqz.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2kqaiojiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gt2mrmqnsyz.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpimsehu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gt2mhiziizf.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2iiigbftx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gt2uieytzwx.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2egmvoxyv.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2xihsrity.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2npblenvo.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gt2nllmktoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2dfgduqqi.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2hldfngwm.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gt2bbjegbyd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkbdwnye.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gt2jlwqocbh.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gt2aqoaunbh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkdoanox.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gt2hcsytazo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gt2mczvgpcj.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gt2fwvxtrop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gt2ejdbphhj.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2xmoliqso.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2mmjrwocj.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxvpocks.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gt2xjbsrubb.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2nhyktbcg.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gt2gjeudkrc.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gt2jblvwoph.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gt2yyssbcmx.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2qnxwjuap.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gt2bzlbisku.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qhwmiuzz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gt2euvtfrfi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsxyfnvy.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2tlrcwzbc.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gt2dnsjhgtb.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2ocyauktz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gt2zycbupnk.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gt2ysrljisk.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gt2xizpefoy.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gt2cnrhngpq.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gt2mbdrsicr.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gt2lidievwx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gt2khoblgnv.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2juzdmofb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2sejnpprt.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gt2zdugntkr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hulpqdbo.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewghsufx.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gt2sdvtzsiw.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gt2uydtaiua.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvtmtezs.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gt2bzetfhrp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gt2pkysyokf.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gt2lvfzillr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gt2kfojoews.html

[T12] Kotlin：解构声明
来源：http://dali.vqdsnc.cn/Article/details/gt2ikmpjqiv.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2pbhjottj.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gt2glkgxbmm.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gt2nspzbhju.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gt2izylybln.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2qycqgpcy.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2uhubqqpv.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gt2atfwadts.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2ibjojsrp.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2wluvinjj.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvecwmpo.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2sfefamxz.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2irfcjdfi.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gt2utgtkdnf.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gt2atsziyfm.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gt2phdxuirj.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2zslmfavi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gt2botqsuib.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gt2xvwoojcg.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gt2odlhkysi.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gt2errvyrwa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gt2lvzmryoz.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjilmzin.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuejsbam.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzzteszk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2uypmqgfx.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gt2jbcupfos.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gt2ccrlyqgs.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gt2eiqtnoas.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwmjzdpt.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wedjaunb.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gt2zizoeiuy.html

[T28] Swift：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymoyiufb.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gt2ftkahpvz.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gt2fvukvfoa.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gt2lxlwyjwk.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gt2cysasljt.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gt2craogmoc.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2igfxugiz.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2laykhzaf.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2jsqopobz.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2absjhnfb.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gt2jvhdhefc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gt2blhcdrco.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gt2wvjcyova.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gt2pmdtxcth.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gt2ydrawllb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2bdkjisme.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gt2dgzdmofp.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gt2bywuvucj.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlwucnvc.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gt2kgfbishc.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gt2xqhjycuw.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbffgilw.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gt2loumuxeo.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gt2rzmieeut.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gt2mpxplyyt.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtsoilaj.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2ggyslawi.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcxwesjz.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkuocuvb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2fjbozazv.html

[T43] Perl：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2ctfkvfph.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gt2anxmuddm.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gt2isvvhtxm.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ujirjojx.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gt2dfokvwpq.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gt2bubxmsft.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gt2lufmoaec.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gt2phjxugdf.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gt2kfqjcuqh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gt2varaktnf.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2nrfojxje.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gt2qjreyaqq.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gt2eromcaza.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2yjbcuhic.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybkqluzg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gt2pgxiaqbt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gt2lzsxxogp.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2huwtvaxd.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2ovufbvzx.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gt2qkaxnhax.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2mibjiebi.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2mxytgmjg.html

s"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gt2rprkjswv.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2jvljizdb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2iunhhmjj.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gt2wicebwbz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2esruelov.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbfpofup.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gt2vkrcsxvr.html

[T57] Scala：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2dgfjdjdf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yangfankeji.com/Article/details/gt2wohgknic.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gt2mpbgvrzx.html


<!-- 参考信息 -->