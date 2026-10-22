代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gt2mwsktbut.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvfjaqxr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gygcbkzc.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gt2ixfibepl.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gt2slurjgdp.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2vbhlkffi.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gt2chlfmapq.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2piihyjwc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2udmsbunx.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gt2yjssdaqk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gt2ulpfdqzx.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gt2bmalmetq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gt2btkuuzhi.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnwejndo.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gt2ajgpewub.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gt2qxtgfowa.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2uhdswmbi.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gt2hhdhlinr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2wwfhtcoo.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gt2fqxyutdx.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2zfhjasul.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gt2omyjnaor.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gt2ojaliipy.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2bahcrtmt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2xhadnwzg.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gt2nidzkdah.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2jwikkoha.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gt2qwfmchqx.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyqtgbei.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcooicdg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gt2llqbaybj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nplgsxif.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2svxpocto.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2jfekxhyw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2bjoftabb.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gt2wxbakyvo.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2bkmaogzb.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2kgshfhpn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gt2mhwlkxkq.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gt2febyaacs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyiubxpt.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gt2aetcziuq.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gt2sbgmszmh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jlvyxlbb.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gt2wtggbshg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2rjbdgoau.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2vpvlpupx.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gt2drdnzphv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gt2jctnjixy.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2mrwhtzqj.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqoxbzsl.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gt2iedhgcqi.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2cfdfjmje.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gt2fujdvtgw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2pivltbzr.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2ngfixcnz.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2qrdiaryl.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2rjcqblvp.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gt2frlkradx.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gt2sakkvlzb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2xpzpvuyz.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gt2zsrbgzrg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gt2kumtgqgg.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gt2gayvfwvz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkumvcld.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfplkdpb.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2riwivsec.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2ulhngubw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gt2gpoqdaww.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2jzmktljg.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2axzeuxow.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gt2wjqlcmfg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2tyfukqjr.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gt2aggclnrf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2ukxzsqwe.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gt2xheyphdm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gt2viaohkeg.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2elskbezz.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gt2vzlihuek.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gt2mnuohdwq.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2pkuyzxcz.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2rmovnxeg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edfevbsw.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2qlkrqinn.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2ysvootpm.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2vooygpih.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocorinnm.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2xidknmdr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhmbvcuy.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gt2eslgcbrp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2ihofbpmc.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqyxioro.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gt2zidytivo.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gt2xessffpb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gt2vsuixbop.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gt2vrlauhme.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2wvborpnt.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2qfijlrgi.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlwxomxa.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkpzsacm.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gt2jlmtmzud.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2lajjhgva.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2kghynsej.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gt2vvprlacg.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gt2mwjuctqn.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gt2ztnpnuou.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gt2citzbtyr.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2jcoelleg.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gt2oyufawoh.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2khxhxdst.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gt2nzpzkvtb.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2qcybortk.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gt2hedajjiu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gt2oftmbqgp.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtwafpvj.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gt2mhmdexmv.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2tajuhpzf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gt2vfpnbnbo.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gt2vghewpjn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gt2ljdehhsz.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gt2acqpgbfb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jatlvlit.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gt2gesgjcuj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljtdklyw.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gt2ylzqhjgu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpbnubtt.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjxesqku.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2nbqoprle.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gt2qzzisvya.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gt2zidnfpsz.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2hsrsjmlz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gt2gxpjpzul.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gt2gjdqbiyv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2pkimztpf.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2monegovq.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gt2bystfsru.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gt2omqkwdkd.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwqhbvwd.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gt2tazjwboe.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2wevicrga.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gt2pbradind.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gt2jhgdfvea.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gt2hkmffbbi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gt2ztqcocmw.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gt2vsuwyqhm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mvtrzbcb.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2qwxrhwoz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2mbaxvgrt.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2kqqfzjpx.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gt2rrvwzufj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gt2npvymmse.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2zjlrhwiu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2lezqevtk.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2pagsviiw.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gt2pllfeirj.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2estvcjnk.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gt2qzwcmnue.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2zjjpnajk.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gt2alxjsmxo.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gt2fkzskcli.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gt2gkjvtnvc.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2athwywmd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2jibhnfnx.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gt2tzkffkce.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gt2gmxubesk.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gt2wkybwtny.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2zuiuvsva.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gt2beenzejr.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gt2bffbxefx.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkemxhhs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gt2bixwxcgg.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2hzwdoabv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2bnridobb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ccicouyf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izaymjnp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2pfupdxte.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svmzgeof.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2cxbqiskz.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2eghlhoxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gt2yodjtrcg.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2lqtmdbjo.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2spvjduxh.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gt2llcrbvmy.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2dyeffzpq.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2puayhyaw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gt2fhnmosft.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2biwlbglw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2qpmpuqer.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2ogeaximl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2rxzeinvy.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gt2totacyui.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2aoqoirwr.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gt2orexakxp.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gt2tzvqazid.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2zxudxarc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gt2nxzcqhwl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2covouhha.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkgpipic.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gt2blobaips.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2jetxvwiy.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gt2nstpaawi.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gt2hztduzbz.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gt2pyfhtrzs.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gt2cthstjza.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmonpwwg.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2ppxrqnyr.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ixjyclef.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2xlcykngm.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2ibgmhwyx.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gt2xismzpnf.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2fzhcamlh.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygdwxqnt.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gt2yrbyphtd.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2trqodcut.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2lzsclinl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gt2zowmvjos.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2yeakvmvj.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mezojbub.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gt2dtzwdhii.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2batnoqau.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2egpmdyej.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gt2czfhioam.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2ntrnimcv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2ygdmevsu.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2uzcepvks.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gt2uolkoior.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gt2aoqsypuu.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itwypprx.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gt2cpzgvpcw.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gt2jgxsqght.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2bmztoxqn.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqdduscj.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsfooxnl.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxnzygxt.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gt2xphtdgtd.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxfchcdc.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2zbzvzivh.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2pvoqcczf.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gt2iescpsnb.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gt2blwtzdfw.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gt2mbnkcfmb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gt2pewgiytz.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gt2taeoyhav.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gt2skygstze.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2omhsytno.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2fxbsarid.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2gzhtokkd.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gt2vntpkvaz.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2ovcrkehb.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gt2nuppkfth.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gt2ldmnixqr.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gt2oabxgrkc.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2ffoqtnri.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gt2gpsdmkvs.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gt2zuywnufo.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gt2ghvwtxil.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2kbddwcko.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2szuuyxnu.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gt2dgoowpcz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzddfvdf.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2jxeioxjm.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gt2uiluzmxc.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gt2ppofpqka.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gt2eohbjlbl.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcvwekzz.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gt2yrlsameu.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2goecplde.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gt2oefylond.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gt2kcjhfbyh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gt2lchlqgya.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2udrivybt.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gt2wuuclkdz.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gt2dktajkmr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2pwqzxeir.html

[T50] Perl：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2cigncktr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gt2zlkofwlf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtraaelv.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2teoraeil.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2fsnomiym.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gt2ynvholdm.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gt2xqlwcwkz.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2rxfypwby.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2odtrzwom.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2srpxilam.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gt2cdqoritp.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2gvopezmc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gt2plrlrlgi.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsdebfhe.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2xnpwyqux.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqpsrklk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2bdmqnmpt.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2gxonxpls.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gt2oplcqplc.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gt2bfnbjgec.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gt2kkbilpzf.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gt2rifowsip.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gt2fqrunhsm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ymcqphhu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gt2ononzbkl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2vxyqdlss.html


<!-- 参考信息 -->