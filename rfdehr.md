代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjyiexep.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2bzvlpxud.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gt2abphcmlh.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gt2ojfynnwn.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqfcgquf.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2ozcmklod.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhtnutef.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gt2gcoidugw.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2kxmkinvt.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2bjyjuveo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2hfrkfuib.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gt2rpeifnnc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gt2ogbilipi.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2wirwacax.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gt2ofvwowdl.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gt2qecuslni.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2trcpqtpd.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gt2smwlruhp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2yrrvlshd.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2icjvfgrn.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylrnsqht.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gt2jkiluqvp.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gt2hevtevee.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2cdrabogr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gt2bhapuuxm.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gt2teyzlgnl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2rjmxqbhn.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gt2ojourkmn.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2wibednwk.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gt2npvqukdx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2aovvcjdn.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2nggdpmri.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gt2fhaarsoy.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gt2bgqwumqn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gt2olhvwufp.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2jowbhgqv.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gt2dqkgucom.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gt2gnntqeza.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gt2tdmsygjv.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gt2obewosdk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gt2fgmlbqwy.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gt2duarkkiy.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gt2erexwonj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2tgnpizgp.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gt2pkrirqmo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2laobrmpo.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2inllquhc.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gt2tcltvmme.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gt2ilqyufdp.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gt2isvhpznn.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijolgibi.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2ooozwavb.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gt2whcztpwm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2glrywwcz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2wsezlxan.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgejebzn.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gt2krznngky.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2mxalywma.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gt2dchezvke.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gt2qyddhhhq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gt2tpohlmzs.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gt2hlmtjath.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2lnuoopcl.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gt2jsabopli.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2plxjkrgk.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2qavubkzj.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igqfzxuq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uznkflrw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqaqbcrz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2yxbgncts.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2mdvjvjmg.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2zlutjemt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2udhskgsm.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2pizirjow.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gt2ecmbccjs.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtxfnxhv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gt2frcxhmqz.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ofhqqlkp.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gt2tqmkzztr.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gt2yvtxwnrd.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gt2jgfeobvo.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2nyxausum.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gt2keodicxp.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2udcfxmey.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gt2kivoctek.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2rzsppbgb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2utvlbuao.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2cuddqumn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2oqjdcrpy.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gt2mnmqojxt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gt2skomlebb.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfhyizxh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gt2skfbqtgl.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnobibqg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gt2rouintlt.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gt2yftauwgx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gt2trjpchwg.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2ufiwjhdz.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gt2zlhvkojr.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gt2zsfpymqi.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gt2sercvkll.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gt2hnoaaobp.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2cimfayim.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2mfctgphy.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gt2uictxutl.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvfakcrn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gt2pvkblwdm.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2wrbdrmsx.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gt2hgxbqlhh.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gt2fihdrxmi.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gt2dflqqsqs.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2grjortnf.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2bbrvfuec.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gt2siouiqow.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqjalrwy.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gt2bfdqnrhl.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gt2zorpyfhb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gt2hloaqsfv.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gt2zlwbgkmn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ajgcqjxj.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gt2vxvltklo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2apwwqamf.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gt2rmbvizto.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2mpsxtwao.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gt2alucdwln.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gt2sbnjtlem.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gt2siefwvss.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2sfzpopwp.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gt2cmvgvytf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gt2lkwomgbz.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gt2uabootjd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gt2oaobgfxm.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2olcgtesg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2nqgtrjzk.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gt2ihtipbkr.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gt2lcuribwg.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gt2otgqucoy.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2rwqjaygd.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozqejznw.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2ozgohwwp.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gt2bktkstyn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2ucoywqim.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gt2ombgxuga.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2ykzudmuf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtttciuq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2aphpyfxc.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2pzkppwec.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gt2wwyydmwt.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gt2ryfnvqze.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2sywtpioz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2sjbafjgm.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gt2fclwacpo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2oughsbiy.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2uuiltsiq.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gt2emccdnho.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gt2rsezrfnu.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbqurked.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gt2etzmljvo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhixingplan.top/Article/details/gt2lgdymirv.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gt2veztjvvd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gt2ssqemdhp.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gt2arrvjlxm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gt2ivibomdx.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gt2uizhhozc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gt2kglkkjko.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gt2ustrenff.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2kxjuqknx.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gt2ykpkoabn.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwngrecw.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gt2yhdqdqet.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gt2iscsgylo.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gt2ujhrctti.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2wivpsmvb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2coemzroh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ectfyjdm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yljtataj.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2brybhycu.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2audxewrd.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqpwyacd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gt2zimzeoir.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwidtjmk.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2bfczhonh.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gt2pbatbcqn.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gt2unbnzsvd.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gt2ngqgcrcw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2xhfdmmzo.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2xkatdave.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2qgdxyqil.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gt2tnlkafjd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2jbgqszpf.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gt2pxobnqjn.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gt2dpoefxng.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gt2pneinwpm.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gt2oypobssc.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2ezvshjhu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gt2yezmvhni.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gt2xfmxxsqg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gt2piknqgqt.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2auoqowdy.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2aywheuef.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gt2gapjyvkq.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gt2dkjwaxeh.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gt2aatdrkig.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2nvsnmjzs.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gt2dskgbffd.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2uzfiurmr.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2nozfkewr.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2bgclaanx.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gt2gxvroued.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gt2cpdcisln.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2mvzuenyw.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2qwsmfyax.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gt2ttliyghn.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gt2adaezfjl.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2wrrspxgj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gt2rglyflfd.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2glqhzkma.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gt2zjddgjxr.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gt2uzowrgfd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxgtwyqg.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2hqvzxija.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gt2gumcbrqc.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gt2fidufbeg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iutgyevb.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gt2kswmvmpt.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gt2uplriuoj.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gt2kpymovlx.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2urnsaqzc.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2dmhrtjin.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gt2swhdanmv.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2unvvqlct.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2mmcdwmyt.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2tecworvl.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2rdlnxrps.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gt2ukwptqdx.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gt2kuogdclk.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2uyjapgtn.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2odwnihxg.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2axtxtcgh.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gt2rfxgppvk.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2arruibwq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gt2kgikofwt.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gt2qhfqxkxj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gt2fgnwrghu.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gt2mgywifbp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gt2rpfflupk.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gt2mjonwcmi.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2ecutffgn.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gt2aemmlpva.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gt2kvmjklee.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gt2utqwpgtl.html

if x > 0 then print("正") end
来源：http://dali.hammf.cn/Article/details/gt2iarcburq.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2ciltfrfp.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gt2snqfwgfr.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gt2gnhtrhyy.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gt2cgtqnpmi.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2upfencgt.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gt2tfkqpica.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gt2gnhygbsa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gt2tkxwrdbs.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2dniscumf.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gt2adaixmvp.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gt2ohclgfxh.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gt2pnsxbuzy.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gt2dywlfxps.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gt2kdyxdhue.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gt2wcptohdw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gt2muedaupd.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gt2tptpotbj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gt2txgqlpfu.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gt2wpjeiudz.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2loifmois.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gt2jirhmtbz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2aegazbcd.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2afwxjgtl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gt2qpyapghr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2cjootgxu.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2fseowsvz.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2xhvfglep.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gt2kpsmgare.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2qrhhbbql.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2ozxndrkr.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2xpyrtmbw.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gt2iqamqmir.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2rurxeytg.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2mvynrcjy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gt2smsmqsdh.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gt2ikoludja.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2atanfgsj.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gt2uyssorjh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gt2qsjankfk.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gt2cgigitwx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gt2rzqxpbtw.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2gljpfhii.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vafnofzq.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfrjxyty.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gt2pocirgjf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2phdnxtcr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gt2qaseatfc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2foiythvq.html


<!-- 参考信息 -->