代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gt2vzfifthc.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2umgfbmqy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gt2igwelzpa.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gt2ttexavet.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gt2bfijiezf.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnrytmaz.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gt2vkwuyohj.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2wgvbfysy.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gt2odgjvhft.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gt2rjeqwdhe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gt2przzlikm.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2bvuyupyc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2vuzgtyrf.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gt2wsbecfch.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gt2lirrojzf.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gt2jaoesdnn.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2bscrogjx.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gt2tqkroeew.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvochiwk.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gt2royketaw.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gt2nqdrehzl.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2dolsmpre.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gt2fbgmrfhj.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2mfczhpzp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2ctrfkmsx.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gt2mjopydra.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2gtlldzir.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gt2rfowumxq.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntwpleti.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gt2rtpxjhsr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2vhjxhpej.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2crptdjbg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2sijlszst.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gt2cmkxkbvi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cznhhcde.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gt2xtexxndc.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gt2yhbserna.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2chdjgaya.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gt2tqfgkoab.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gt2qpcgsezt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkcgxpci.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gt2mholmcxy.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxgmqdyw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xapwahgo.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gt2xkvojuug.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvbpljsq.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2tiigjehs.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gt2egndmckh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2jvkeunim.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2yygvsxmf.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gt2qidjnaeb.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gt2nemohiwm.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukpbixch.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gt2auaaykhs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gt2jplrruwk.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2wuuzkytz.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zgkafnzx.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2segssaye.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gt2pkxpoyuh.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gt2leiiruvf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gt2kcioissd.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyzcxwsy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gt2ethpbdui.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nohnvuec.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2atowmlwx.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2riklnzgf.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gt2nnkaiypi.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2hpkghtmk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2ranlalcu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2mkqsleal.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2ogzjdexw.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fznrqoej.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2nefcswfe.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2yzmgljro.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2wnnslojx.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gt2ommblqnz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gt2clojadsn.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gt2dnwgaimg.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snwcnukg.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gt2ppdbbfge.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2eogbgttg.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2anlifgqh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gt2tauxepdw.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2fxyqiqtl.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gt2mcmydzru.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2mpiaahmv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afpoiryw.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drrsnhgw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqiqegqu.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gt2zciphgec.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gt2suauetxh.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gt2nvbgeayb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gt2ryonvpuw.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2recoepmx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2gupamosl.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gt2pcvqnuts.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gt2nlwrsxbj.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlfajdpf.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2mddbaczs.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gt2qtbawnkh.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gt2maosfgmy.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gt2grfqmzct.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2toqaurqc.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gt2doffpbln.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gt2qbdqubmg.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gt2bxqiejzs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2lmpmqice.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gt2pynogjtv.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gt2cfutwzpi.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gt2uwuaphdu.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjxssvao.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utvsnmbn.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gt2yercmtno.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2vlrfrtak.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2glkyzwin.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gt2okvsflkz.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gt2woipwmql.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2mssrhebn.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gt2insgtwgq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gt2vugvxmgv.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gt2fvdwihga.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmsiwjhx.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgzqtyck.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2cyqcfnce.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfxsxjvs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gt2btrwtvsb.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2yakqnxab.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2lyswakkr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxwksmjj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiwlcnns.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gt2kssnzhon.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gt2ustaidho.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2raxwnbru.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2umfbohmy.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gt2decdmkrr.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2dxamtepe.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gt2eophafsn.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2vycgylit.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gt2lgtnxvbh.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpowexla.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gt2qbavaawo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gt2dmsdepdr.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gt2agywrlrc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2totzlekj.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gt2blvrmpiq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sghjodeh.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2pjjyadwh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfqfpvdl.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2ttkndgsn.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxxaolgr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gt2yvroxhbp.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gt2lbflbkwh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2gffazweo.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2trmnuqcd.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gt2tkusiqsm.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gt2aexakgod.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gt2aypqdbby.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2hgvyzjim.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gt2kzldeayu.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2hgfjviww.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gt2qditipam.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2liyfabav.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gt2rycsyuzl.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gt2nffqblvg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gt2boiwhhts.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gt2hzntpjxs.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gt2ovrgskxe.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2nbabpvex.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2jsmmaofe.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gt2mjrqmjhx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gt2egkwnmwo.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2nnsffozi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2obkexinl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2yxasctxg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2xpuafxzt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ialibcra.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2czfqvall.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2arztxscb.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gt2xgordibo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gt2iiodptxs.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2pgjvtmmv.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2pdwawqtm.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gt2lqvejqxl.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2umdmbmvc.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2gmqgrquu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gt2hmhjmkvr.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2xfbfuzll.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2dauazhxh.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2rookaajv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snifxwpr.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gt2aupueinr.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prvipxnn.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gt2msvweitn.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gt2fpsecdqu.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2lqqtamko.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gt2tfkekqzz.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2cwjsxmsx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yonumen.top/Article/details/gt2bkmbswfx.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gt2qgmcjorh.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2ghisfvaw.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gt2wmahnhrr.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gt2vtklupay.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gt2zezehaux.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2ttjegjqs.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuzcmhtx.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gt2ypiwhmwm.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2zlthwfsf.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2yhwfgqss.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gt2uesaerft.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2voxwgmwz.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2ngwlpymu.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gt2hkhtftad.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gt2jvpoqdjq.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2xfuhtkre.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2wcymuwub.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gt2roqnsakb.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2psezejwq.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gt2zcfzizks.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gt2exwmueyd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gt2avgryfcu.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2tccvntwg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2kjkfasbk.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gt2kvihncpl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2dfomuvmu.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gt2acbbdmjr.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gt2jpugqsfj.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gt2sfethcwm.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gt2lxryutkq.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gt2fdbszmrn.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gt2irtwpluj.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2xozifhhy.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gt2uypekqaf.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2pttyqoag.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2anhflcqv.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gt2lcuxhbcl.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gt2xyituaid.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2crstbmis.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2vsikcovm.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gt2hahxxzle.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gt2ysfvnien.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gt2kxqcwgnv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gt2mhffcfdb.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2kbkdimez.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhdccza.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gt2jobttgaf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gt2ccinfwcl.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qiutqeqv.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gt2xmjrahfy.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2ubgydrff.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gt2wokthkmx.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2bzosldqj.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gt2tmjvpual.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2tflkdyxz.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gt2nveimack.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gt2hnxqtyrq.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gt2wdrjqsfr.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2acotddyk.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gt2eyfqibho.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gt2tvfrwzin.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gt2pdekbrkc.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhkhcjhn.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gt2pgxwsnlw.html

[T44] Perl：条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2cotwoxkm.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gt2sxzqdvwf.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gt2fouftrep.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehdjxaqs.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gt2siolmkyu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2nkcsiuym.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhfswani.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gt2haoutoxf.html

[T48] Perl：正则替换
来源：http://dali.jqgufenzy.top/Article/details/gt2wnmbddvm.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gt2vappksyp.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gt2uzxklwkq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2msqkukyn.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2trloqats.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gt2nomytcay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjlhipio.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2akqpluld.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2woeufidj.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gt2qscgiufs.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gt2vcyvwiaf.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2gbfxaioe.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2vvlvggvd.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gt2wblfqftm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2wxmduagv.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2jvlrzzcc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyonjmui.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gt2jqouhnlx.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2huyneanp.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gt2imrsaskp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pymhnour.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2eboorgms.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gt2jgxzfice.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gt2ndwaucrs.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gt2renwpxsu.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gt2iyviulwk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gt2qjlzhwcp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wiwicxbe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gt2fhpyauow.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2dffbhgnm.html


<!-- 参考信息 -->