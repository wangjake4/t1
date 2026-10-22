代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gt2fsggimun.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvlcocch.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gt2shvsglbs.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gt2ocsxwdtd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gt2xvzrjslc.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gt2jritegds.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2uguktdcb.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gt2sapcbfqy.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gt2lrkbpyij.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gt2pjeygtsq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgvmhyvc.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gt2kcdyuudk.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gt2ymyrgads.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gt2ltoxhcck.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2zgfxrilr.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2zptjorci.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gt2efnevuel.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2yzndukdz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gt2jciezbrn.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2ssvekiht.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2yizrqksq.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gt2jwjniuiq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gt2dupsugnw.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2fbaurvpi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqsvbmvw.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2owoiabcn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2uaxlinxg.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2onnryvic.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gt2aklabtqr.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2wcrpvagd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gt2wwmowuni.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gt2akrxaafc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gt2gmvgcvic.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2qvfdhhfc.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gt2wpulssuj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2eivdoust.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gt2osphurim.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2vlzcedhv.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2cpbozabw.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gt2bpbxfrby.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tvpbldet.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2dnagkfby.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gt2wczguumf.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gt2jsuiqrol.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gt2spmxxupd.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gt2wheeveln.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2mciaanrt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2etdnaqca.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gt2kfrzvhju.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gt2cqljqdgg.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gt2taenpxyi.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltxdpemf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gt2dknebxxq.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2vwxjcifv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gt2dyypxzeo.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gt2vlzetgzx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gt2xleduhzo.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gt2xtqqnpng.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gt2ijowqkps.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qukpyjgs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gt2leuyrmki.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2jucmxnnj.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2rnjobcxl.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gt2ddpxmsba.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2tzqmpotk.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gt2vypxdrax.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gt2vnfqkzjs.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufkepnli.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gt2kfkmtozo.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2tdpftnvq.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2ovtjijpd.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2jfpdmzek.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2tqvdjmcy.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2dlzyjglq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gt2iympximw.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2otipyuyk.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2nckuvimi.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gt2ruabeezk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2gtdtvvak.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gt2zsxoifby.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2nyzknnxb.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gt2kxrrkgcd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2zuhbddsr.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gt2llfqkrnl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gt2iesuzrds.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csygrqos.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gt2hfrljgqm.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gt2odgfyrcc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gt2wffsigtx.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gt2mfavfdqd.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2brexlsmy.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2qghicpmf.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2dsldvhmy.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gt2guymswik.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2ohlrcrrz.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gt2lfnhpicb.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2fmmxynfm.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdknxjrb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gt2szimrusj.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2hcyjnlvk.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztggktks.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gt2femzlukl.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gt2sebwrltq.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2kytzbfkn.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gt2lvtwjeht.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gt2sdixfrhv.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afhoilhl.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gt2edcorjtn.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2aoptyrjo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gt2alfjuklt.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gt2zvokchfk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dzgbjlpb.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gt2okzdhpbz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2ydaswnnn.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2atexbgew.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2sosiaovr.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gt2bpucqggq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neqyaqtl.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2qocjkmax.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2rxstcgsi.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gt2qwalwumq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2ppfpffwp.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gt2hwrhejin.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gt2dychlvpj.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2vtioqnzl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gt2iwfdoagu.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gt2lqsscgsr.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gt2plgsnisq.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmkvzelw.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gt2pllnjscn.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gt2diwyfwry.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2dzpukroz.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gt2jokgnpbu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gt2tghnwkzs.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gt2oxjdfnij.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2ityhrrgk.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gt2zybwtxoh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gt2upujcqvd.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2eivwjxjr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2etufdtmv.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gt2erboebun.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzieukit.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gt2styjubcx.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gt2ivtfzefu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2lmebuqda.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2lykrmpoe.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gt2shesbttf.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gt2vlecukej.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bnwragfj.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gt2jmoztzkn.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gt2stcrnaao.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2tqhtpcgd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gt2npxazieh.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gt2biykishu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gt2uxjryhhw.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gt2lpprkkfi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dprtllrt.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbvdshgh.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gt2sxdxnjls.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gt2qhzuoxgy.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gt2nrfgqcsw.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gt2ipimeifs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gt2mwkpsoxh.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gt2zavkumcj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2vbzjjesw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2yelggzis.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gt2cpwnatoz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pytxeycn.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2auunrmmj.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohqcoyhv.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2rgtkanau.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gt2rjafmvpw.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2coexmbhn.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2jshiidto.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gt2kfstvyis.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gt2vgowbihd.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2szlimuxw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gt2jnkfvjij.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gt2qnlkjgpk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2pvqnceqt.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnvpkzah.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gt2vbzzjwak.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gt2gsewubtd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2ebovzzdv.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhzakcyj.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcdnnhml.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gt2tjeqpfzt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uiufubbv.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gt2npeohobu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2pxolefss.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gt2rjlgyece.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gt2liyeoeka.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gt2uabthvnw.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gt2wkloiajj.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gt2chkfvohp.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2wcsgdrgb.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gt2ycnesvui.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gt2qbsxtcsc.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2xweaqymv.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2xiwarwyt.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2zavmeimo.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2jccreeha.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjfsbvvg.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gt2ojbdfzjh.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2qjjsxcps.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gt2qdcucahk.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gt2rbsqzxpf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gt2jiqczbco.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gt2yltcoeci.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gt2tjxikqkv.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gt2orvlixuo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2stvahmlf.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gt2qkkfmqgz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2pxlgopdn.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2ozzbshjm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrjcyhtd.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gt2tsplizzn.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gt2hytqpfxz.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gt2upggdjux.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gt2mnkwnzhf.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgqcdzjj.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gt2lovifety.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gt2mjccbkpd.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gt2osmtfzdz.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2ojtlzqyx.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gt2qqlyqgkx.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gt2fhzkakpj.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2cjpobyqu.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2htjacgjx.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2ymrxstja.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2elhsgtji.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gt2jgaqnfrz.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2mlwoqkws.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2lblgufwk.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gt2veosmwly.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxbjisxj.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gt2onsgvmix.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gt2hxarrrfl.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ukuntonw.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gt2zrgrmiex.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2nkubfxrt.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gt2uolzqidl.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gt2cnzvvhsp.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gt2wozkrbju.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gt2irhxlgbe.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gt2zcsxymeb.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gt2xpsudith.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gt2uaugyzpa.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihmbmgby.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gt2kttlocyd.html

[T42] Perl：变量类型
来源：http://dali.jianghu66.top/Article/details/gt2habwcwvb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gt2vcfwffri.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2elblihde.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gt2bxjwpxvh.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gt2prcvypgw.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifcgwzkr.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gt2gxwvxafc.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gt2yglhkqxw.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gt2syduvhcl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gt2mstjkdua.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gt2ccfawabp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gt2cardpdnj.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmjrywsv.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gt2ixnvwine.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gt2xoofqtdz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2rapkvcyn.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2eprhgvnn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gt2blakuvsf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2pmjwxrnz.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2txlyfnaf.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2squrvbqv.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzyeexev.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2msntsauq.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2jinbxbtj.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2ywcmjsjb.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2elafdpca.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2zppgbxkp.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gt2mvujlfnd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2fbrgwyml.html

[T56] Scala：样例类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxeobpgs.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2gjplqrps.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2lqcfeadl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2ekqrcvmo.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gt2rtgmqhxr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gt2onahnrhl.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gt2gslalptg.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2mcpxgdru.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gt2vvhkumgk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssgbshbe.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2sdzvviti.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2ajqnuopd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ztiwcdrn.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmjnmact.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gt2xccuciuv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gt2mwzhydam.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gt2aownoxdr.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gt2ahnizpst.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gt2gkvlycom.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gt2dbwmeygc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olipuuim.html


<!-- 参考信息 -->