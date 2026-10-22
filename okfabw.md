代发 wailian999

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gt2vzuqnrxa.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2kvwexxog.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2rkbamtxe.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gt2ejhjtktt.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2cncvuhzf.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2mnjnkzur.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gt2oasbglrg.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gt2fgmnxtvn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2uquyxzbt.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gt2dwnokgsj.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2gpubsgvy.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2eeenrnbb.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2djxprjtt.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gt2laxxutzx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2kgrszdrt.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozgavpsq.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gt2ctuammct.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2nvsctvkz.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gt2wgkpizji.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2evebssvx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gt2csjclhpa.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omskqbam.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2bfzmxnyn.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gt2vjycjkwv.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gt2xvjwvvcb.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gt2usxgmbez.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqamagst.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gt2ttturryx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gt2eaniayec.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2nooheiyp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gt2ajsnudvw.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2maixzcyy.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gt2oiuclubi.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gt2ebpqwzek.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2qdtcrrua.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gt2opqvasfe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gt2gbfzbabv.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gt2nkgbuozc.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gt2awapuncr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2qeejsykg.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lulvvlmm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmgqhoyi.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2ckluzanm.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gt2isnwgdwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gt2kwcwgsmu.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2qysfjsgx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2pefpgyig.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gt2oscvytcm.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2mztyoyqo.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2uphvkdcx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwjhbvpw.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2tqgpkwkr.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2izwuvywi.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2bpnydjve.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gt2xdzjtdxq.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gt2gohkbnyd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gt2uufmkxne.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gt2qxwzaxzu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gt2wdkxworm.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2tmromaqd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gt2vhhzmqxs.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gt2popixzyk.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2jlfkofya.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2alikewqn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2xzcqvgsc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gt2abitquys.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2hyefjqhm.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gt2ibjvohap.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2jsowpswt.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gt2boaaucnh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gt2itqytzey.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2zsaieqop.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2husbyofw.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2gmymiwbe.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2pugivcqw.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gt2nyvrnnnz.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gt2aewuvrdr.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2fgorlezs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gt2mlsojjzs.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2cstpqmms.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2rkfdqlyv.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2gzfauhqp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oljzrznc.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aapnuejq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2nvjflimv.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2cnqpzuqg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gt2kocvcwpm.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2kuouksvd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2iqohdzjr.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gt2cdhizjjh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gt2lqzjzrlv.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gt2twthuzgx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iokkfhcm.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2sazvqxcm.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2uupnjqdc.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2qguvbvwl.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2cpafctpx.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gt2sknmeslp.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2avqmgsoc.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gt2anfedkje.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2qlfksasu.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2igunnpju.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gt2olqskpnl.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2lbsdtgiy.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gt2nanqkadc.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gt2qnrkksju.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2flflivca.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2ugrjqnxg.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2khgeyjwz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gt2pbqqideu.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gt2qcsqojrj.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gt2fvwmkzcc.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gt2pzxcokjp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gt2cepibgdt.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2mcdhgyjg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gt2mffhmxyh.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gt2qoinicfh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2fcljfztp.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2tajhhylg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2kvdqfcyh.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gt2geuqidgt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwdpsett.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gt2bzvibwbb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruveexsr.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gt2oeulkbvm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gt2khugovxz.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gt2jcqasigw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gt2cwibnxww.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gt2hfgsiyqn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gt2rjpgufet.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fozwwyxt.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gt2qlkmozpa.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gt2gonixnlm.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2ocwwspyb.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gt2ndmazwhu.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gt2jkpkqlex.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gt2yzpbxfui.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gt2lndopfse.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gt2pyvbzkgj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2goajebfw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gt2ghxmtlwz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2zzdhslgt.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmfaxlfg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2xkqmhqqe.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2ezmklvgb.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2vnikaain.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gt2elpvpotc.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2abnaoyek.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2cupbmawx.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2fawyguso.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qstyyyqz.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2ipphzuve.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2lcwqnmqh.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gt2gwvzwzzw.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gt2kqkorccw.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gt2xarmwpbc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2cpktujxz.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2kmkuxgdp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2izjxngrq.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2uduijxnh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoltccwd.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2rdeqpsxk.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2qkkummlc.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2irvppggw.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2rpvfsqog.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gt2mdfvfdqg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gt2gntvdocv.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyiqzgwc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2ewkqfzxx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xihleduo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzevlvnh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2efompjvq.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmirnekm.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kytwwwmv.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qztzfkor.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gt2cuuldkov.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gt2okkirdpu.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2zcnianbl.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gt2ikyxwooq.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gt2ofjuvffm.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gt2efpzcchv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2kopxkxim.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gt2toizjtsg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gt2oucdesah.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2tdvkcqqa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2ywkyckbv.html

[T08] Kotlin：数据类
来源：http://dali.iojbl.cn/Article/details/gt2kkgpcwle.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gt2prsevoqy.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gt2tmbkrsmo.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gt2ptbfqmgi.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2btorwvug.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gt2chsnzrmj.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gt2gqekrgcr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfzozerw.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gt2dalvcujk.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2jmwhhrxg.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gt2gdhkrpfq.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2txrcdufi.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gt2cbaqddwe.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkgsmeie.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gt2aocqozqk.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2gcmfebzc.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2awypmhvh.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2tzqizibe.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2doltjhro.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2hubnymxe.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulldbhfl.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gt2zforysaw.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gt2igmjhwdq.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gt2qjtckqrw.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2mslvrjlt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gt2ggehlkik.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gt2yvgjkxoe.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vscmtwdu.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gt2notwwkov.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2lgijudzb.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gt2bxpkppye.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2bwzwmail.html

[T24] Swift：闭包
来源：http://dali.yj202588.top/Article/details/gt2ifuwbuuq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2ypuaxxgp.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gt2grzpefpm.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gt2qkwimfbx.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2ubofyknn.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gt2sfkqjuvv.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2steylahv.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gt2ahpovkyz.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2cogujcpv.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gt2gbwuvelh.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozwszsdo.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gt2hoisjxqc.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gt2fsjqqflw.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gt2bxirajyb.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuuyoqof.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjzkgfag.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gt2tyrmekxm.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gt2scrspoua.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2picpqicd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gt2memzacks.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gt2uohbjqev.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2xnicuith.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gt2ackblvkw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2dxksgher.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gt2tfoyyvvn.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gt2asqtrnlq.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2kiwciuxa.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxqtieeu.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbofqzdi.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2ujlaijtn.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2qhlwoodp.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gt2scsqugyi.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gt2acfadohp.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suitcwct.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2ktxyssrv.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gt2pzzabgln.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gt2cemrprnv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gt2ozslmlli.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2jmqoplyw.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gt2herhhase.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpcrxqyt.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgfzy.top/Article/details/gt2uoettsjh.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gt2dxxjukmc.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gt2hpjsezos.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2piiniagn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gt2bdjwbfpp.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulkvfpix.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gt2pxmbjufk.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gt2rvdyogtj.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gt2ryoxdwur.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gt2ofnlpzqo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2uqzbumvv.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2rsdgarkk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjiljcf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekmhxzri.html

[T51] Scala：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2friiluzm.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2xrrsdbsr.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egfhwsxw.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2qbdxbuxs.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2xtiynhjy.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2qdisuvwl.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpqroisi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2nrsyicix.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2yhkjelma.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gt2mxrqnczg.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gt2oklpjkld.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2qezhzesj.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gt2kugzdybt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2mjxsgzid.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnvxkcrl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gt2tbzmlmfb.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gt2jiodfqti.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gt2dlzmbwpo.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdwyaxov.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gt2hfvptipw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2xvuhgyus.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gt2cjtvmhhi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2emdcscqp.html

[U01] Py：创建虚拟环境
来源：http://dali.9152youxi.cn/Article/details/gt2nvpdyila.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gt2vbumtiib.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfualywa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gt2nkyrvmca.html


<!-- 参考信息 -->