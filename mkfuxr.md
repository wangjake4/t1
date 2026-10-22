代发 wailian999

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gt2glvlinow.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gt2brjafhlt.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2hdlykxdw.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2smomkybz.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gt2gotyevgc.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gt2pnryyuba.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gt2jrhzstdd.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2dhjcktrk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzlvsrjn.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gt2qbimhdlg.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2bpkauxdv.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdvkkezk.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gt2aunqgyat.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzpgvkiw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2xnrhwfej.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gt2oyhsehma.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gt2bwvxffrk.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gt2hwnydxsl.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2dueqfhqc.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2yvvyzxuo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gt2aaffprmv.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfkczaly.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2chyoeqcu.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvgcvrjs.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2eynltlxi.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwkcccwc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2cnicnwww.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2vvefvcfj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gt2axdgnixy.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oysyjwqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2apfssroy.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gt2gshthfnp.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybrilsyv.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gt2gzdhhfuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gt2lnnxpxvc.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gt2ogdcolni.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gt2gfyhojqp.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gt2ncyqdrrh.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2aqarxldu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lxyqpogd.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2dylcxykj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2hernloat.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2mkmwuqil.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gokcluvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ifmznkai.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2qkxoqcht.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2sivuvwhl.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gt2gqdcueou.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2ntfznxda.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gt2epgejyyc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gt2dmbxcorp.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptsslgjy.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2ncsrmxdz.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2kplgjsqa.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gt2ksxrvtkr.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gt2uqkfssqw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2gjeijenf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gt2vrcpvtsx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2hfyvtuyr.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2ritculqg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gt2qkocchtf.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gt2iekpajwe.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2eybtnrwl.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2xncloaoc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gt2xuvrpeaw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gt2vsuekfze.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2nvzyggfq.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2ygluysha.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2glenauhy.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gt2xnensqpf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2kqfjxljk.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2cffrxkbk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gt2iqhnnpyo.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spandcqa.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2kzeqchzr.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gt2brfytdix.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2qpekgwgz.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2hjhumemc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2wgkqpmwh.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shzjvlim.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gt2zklenrvs.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkzisdxx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2lvghqdcg.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gt2ppckjnke.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2hegglhcp.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gt2qmhzdpqq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2qgpwpyyr.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gt2tpytriax.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gt2eavkytrz.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzcihlei.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2lmpegeaj.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2vcktbiup.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gt2ygmnczkf.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gt2aexxdowv.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gt2lettujkq.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2zslseuxd.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vktssgnv.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gt2hfsbgygo.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2nqarertz.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2jsvwaiaw.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2fjjmbpon.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gt2cxnteqsd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gt2yzyxqchz.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2tlrqmpul.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgwocokw.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gt2jyuwqsri.html

#endif
来源：http://dali.yonumen.top/Article/details/gt2rtfhzzik.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybcvudup.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2geuqpuma.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gt2mfjjrhha.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2mvukjksy.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gt2ninpvkfo.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gt2aryxazsg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gt2sgspdwrj.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2alnqtsrn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gt2fvkbgumv.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnwbyixp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2hbtygtxx.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmkjiqhg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2vjmhdtyy.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gt2ylblkglt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2afbxvpla.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gt2crhstlpm.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkkgfpdo.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gt2cyxnipbg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2waaeepwv.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gt2zcovnayj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gt2kxnyqprb.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gt2zjmaligw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gt2sqvbrheo.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gt2ybovxqgi.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gt2fzsqfght.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2cwxzwmcz.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gt2jzjxflla.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hayghntf.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gt2ntqyxfhb.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gt2qbtkthvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlmdykwj.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gt2dnchwrmy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gt2vntqrgrx.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gt2uapsawbz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gt2htjyclwb.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2unoruaro.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2kxjpmirt.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2okzlmykt.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2advtzial.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjxddiis.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2uzsytfur.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2satfgasa.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gt2cutizmue.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gt2rokaanzp.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2lcbynlah.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gt2vkmwmdpv.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gt2rhfbrnxg.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhsqbqai.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gt2adezujbx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gt2jxiykjbu.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2ppoatayn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gt2svpkezkd.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gt2tfhdroko.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gt2oenbmuzy.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gt2lytfplol.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2jexzlwoe.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gt2ajwuwgra.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gt2jscijlhe.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gt2deemkjel.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gt2ulnenvlo.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjabnzqr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlmgqkst.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2plxntljf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2grhdmjtn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fqzygpcu.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gt2uxsbebeu.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2olqrxdoi.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gt2ljlfsvrz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gt2czyqkekw.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gt2mvwkpemb.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2ttzprkwa.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gt2dkwuupng.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gt2fuxsrmsr.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2ewsfvafl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gt2unozjjje.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gt2sxnvozue.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2qxycrcxh.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2kbqqnqeh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2olpdlyuk.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2vsmlwafy.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2wpvxfuxw.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gt2rzdqhgxs.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gt2rfdnibtm.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnavkmli.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gt2sjnethvf.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gt2sowadkai.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gt2hzbndsle.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsnqoiil.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2ermyxoha.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igpedqhi.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gt2rskxipnu.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gt2utmyprzh.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2hxxnxopz.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gt2tsdusiel.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gt2xastqkhr.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ixkwvqwo.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2zigqxjiz.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gt2sgaeisdw.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gt2abkkjkri.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2gspdtqxg.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gt2pszrxjzb.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gt2gfglsuws.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gt2qodhdayx.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gt2ilqbsggm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gt2pbgxxxov.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gt2ybmxgxqh.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gt2efvaidox.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gt2piouarlb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gt2uzmxmwbm.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2fefslwhn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2yqciqwaw.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gt2tuaysqmf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cozdxhwv.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gt2fdpnonkj.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gt2ogrmenag.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcphidph.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2xokhpqqu.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2tuzufzud.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gt2isrekxjd.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2ipvwpxmc.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gt2swqyyxau.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzdlyhum.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gt2ircleoih.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gt2qhxqnwcv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2eoiudcdv.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2istpfpeq.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2yqakgtqi.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2lsrdqnqw.html

local a = 1
来源：http://dali.sweek.top/Article/details/gt2trhdywzw.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gt2mfmeovwm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gt2qmkmnuyz.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gt2nopffzhx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gt2ppsnopao.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gt2lnxyrwoq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gt2iqturjfp.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gt2rhwjkwll.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gt2gwdiytfw.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2oqplbbwi.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gt2pmziyfuy.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2iejtngph.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gt2tlejyvzg.html

[T39] Lua：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gt2mibuqoye.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwhdlpub.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gt2abhqcizi.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gt2nowmdtyx.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2vhvjtzsf.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gt2tlpmlnou.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gt2irzwrosx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkindjzs.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2xtgdkegd.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gt2dyxfiprz.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gt2rofqwfau.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2tqyfkojh.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayroxxiq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gt2utlahbsq.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gt2nmoebrdk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gt2kczhxnzz.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2jehwrkcg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gt2vtyinpkc.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2nkvarnrf.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2ffjovnhv.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gt2nuwnencz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kkctnmdi.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2wmiqngnp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zdqjudy.top/Article/details/gt2ausrvaad.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2ipsrsurd.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2vtvqryox.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2pdwzgjji.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gt2pqxdzykr.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gt2azglxxqm.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2zaxfmfey.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2cacmarqf.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2ridprwbx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gt2sargojlf.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2lrjqcmyd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2jjlyqveg.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2csnidsxm.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gt2jvoqwxij.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2rrcasubp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gt2rrmethgw.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gt2opbraykt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gt2tgtotkcf.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gt2duzbuxvc.html

for (i <- 1 to 10) println(i)
来源：http://dali.yueranfly.top/Article/details/gt2lskfifdv.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gt2xtrxldml.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gt2pyqscfku.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2rggyghfo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gt2zfhumfuo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2fwdxcfpw.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gt2mrfnhsxz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gt2xltynkfi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gucorbsh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gt2gdemjbil.html


<!-- 参考信息 -->