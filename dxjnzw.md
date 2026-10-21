代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtvoqpldog.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkvewqzxl.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgfqvgzn.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtdcjgdaxm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtrdbxdfmc.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtznwhphjv.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtugnxyxtl.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtbxkscqcp.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtfszhrpil.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtspdseuvm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtyyjfhzlp.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtrwpocqat.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtypxpxctb.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtycoavhja.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtvgzfvpak.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtknfukbfb.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtzcupfsdz.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtvnhgbxyz.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtysufmemb.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtqwtvhtxa.html

free -h;  ps aux | grep nginx
来源：http://dali.0kj1m.cn/Article/details/gtfzngmevl.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtczmuiowi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gticllhgav.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtyzjmdshs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gturmpxecy.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtfbfuhsae.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gtksvufvcs.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtrlxmvbyy.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtsvjucbjk.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtxxvgvkvx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtejmdazsf.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gtoalmrrfn.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtmkvxclns.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtbfcvtvik.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtezgocvod.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtrwejcweo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwhlmdrg.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gtyklrjyrg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtstdtqjyn.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtmbvdwcrx.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gtwwujwjso.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtobahsiny.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtiwlwwrvu.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gthjavgmse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gteblylfqg.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnailwlil.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtfgpizuba.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtvxkbfiup.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gttgbmrhez.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqivhmkxy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtgotkhcch.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtswgzaeow.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtvyuufjrh.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gtziqmnsub.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtkfwfwgyn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhtqhkbm.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gterhpjnde.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtymxocupj.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtwujnvfnw.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtmgxqibos.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gtfrmreyow.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtukuikbbe.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtiomujtoo.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtezqhezvr.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gtuayfxknf.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtefjsrjgt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxvbvewt.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtoftwyakg.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtyrwgdpgu.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtttbiiwjc.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtiotnhdxu.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtzrzxzrzt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gthgwrnwjr.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtdcpfguip.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtsedmjuit.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gttmfbhksg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtatxlwfua.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtwaevhusw.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtmknbhvtv.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtufdryaen.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtjfvgqdcs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtxfudjmin.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtmltkqzps.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzjjxyms.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjsxsiuu.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtullhydfl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtbfwqiwlf.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtimnjvlgp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtqbdzsjds.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtxbokzzep.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gteutnxaro.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtgpzadzuy.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtivhiszar.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwpxycnue.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gttfbfctdl.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtikeozbkc.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtfouwebdu.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtbcbqpzme.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtuvoffvzr.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtroaruaez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtqydfidhm.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtjnpseakl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtnovjhfdf.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gttpybmgud.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gterpnmqpb.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwalgzth.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtbkurhgnd.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtptrlykih.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipcuxegs.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtuyptrgwu.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gtroppldai.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtqbfsepdb.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtfojuwkoy.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtzaipxmfp.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtgtkjfurp.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtxtltkudp.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gteainvqsa.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtuiinrrru.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtrowxrvks.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtbnhggmli.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gthwtaidwm.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtyiiilqaw.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtziwqcegw.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtwbztmqkc.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtwswdtzjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtzjtswvie.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtwgkhguge.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gtixrrlvwe.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtanclirep.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtegjjyivr.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtjzsyzckb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtyqpuipti.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhpdmulb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtlanltzup.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtmqhyhkcg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtahfydxtp.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gteoyeoqrn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtfgialdjd.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtnviywawo.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtvcdgpihk.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtquwwjqbg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyugvelkj.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtvappyfna.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtsedqhtzi.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtkivndlxw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtlrcuibgp.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtrcsofpan.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gteptviynz.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtzvdbddfg.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtgitzeeyv.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gttpqosdch.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtihtydptr.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtpcuxneta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtecdjvddk.html

[S46] C++：函数模板
来源：http://dali.ydzc1.top/Article/details/gthhepyyye.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtlbnkepjr.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtuovzosdu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtptowrtis.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtmgdmwsfe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtjmspkbqr.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtyuidclej.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtovcrkwmn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtzhnkgbbr.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtejefbzuu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gtnxiptkwg.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtidrhhbxb.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gtyukfuflu.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtbvgydhry.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gtqfvsuzha.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtvfoyxlor.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtcoezcyeb.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtlaxtwqrg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gtzdkpckzy.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtgrrmqpxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtcfmgtrjk.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gtizpqxcue.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtbhqacmqi.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtegtbfcmm.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtnaxbpdtq.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtnckketqp.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtbdxxdxyu.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtfzvhgxgs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtxiyiqybh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtbdeavfcf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtphwitbko.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtplrxdejw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtlmrermbb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmhfqvyvg.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtvxnlgpvw.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtfnzqjbno.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gtrsuembyd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtzddkrnry.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtdvjxkaaa.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtdozsmrum.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtwdzyllhu.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtgbsxsyhv.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtdzfztmbf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtkdcwsckl.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtvjfefkal.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gttljxulbr.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtoqlomcra.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtqifnmoar.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtciqoncrl.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtfoywiedi.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gtloczyhya.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gtjexluate.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtrbkdrbut.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtgflxcjro.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gtchosxjtz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtktuzipku.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtpuaoyhga.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtqlhkradu.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtoiykenou.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtlvvavedp.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtksmsqita.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtaiakknad.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gtmpqjxbgq.html

interface Shape { fun area(): Double }
来源：http://dali.ybcxt.top/Article/details/gtlkgiravl.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtfymwlhrj.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtqypaeihc.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtkimttffq.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtdwufoaen.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtspvibswh.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtttgvnzxf.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtjhtlkypd.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtrdpvdxba.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcanbsew.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gtmhbvhzru.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gtttkkcygd.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtajthdssp.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtoywehijj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtodvmzbyw.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtbvjfmbis.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtmdzaantc.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gtbgobrbpj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtbxshtguw.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtpwdkixrb.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtllhuakpe.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtixmrxilk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtdbofgaft.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gttdcamwpt.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtnkrvlgfe.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gtkgzncyxn.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtbqgpqubg.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gttungojmz.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtwggzizgy.html

[T30] Swift：协议
来源：http://dali.hammf.cn/Article/details/gtscptywui.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gtfxzfgyvf.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtnfrksvdu.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtxfmzzdmb.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtcfgkqfgq.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gtcjkjohfa.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtnvmondvf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtonogdzmh.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gtnimksnlm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gthmxcxvcr.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtvinonarx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtqpzxkvru.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtlaktbfhp.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gthzzshytr.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtnffsafav.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gthqsfdxra.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtygjzymoa.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gtkjpuhtig.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtcvapluec.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtziqzjlxq.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtgffgfklo.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gtlcyjxmso.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtlzydorfq.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gthumbtbxs.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gthgfjqlwe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtvieegicx.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtbdmrlrnx.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gthhhxqzuq.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gtaswrguzv.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtoxacnbla.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtweleoxbc.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtbqmaaezx.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtoaomcxhq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthaianzrz.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtbyahjxau.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gtqgskqdvt.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gtnkuuerna.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtcivcysnw.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gttrbporpw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtwvdzyryh.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gthlwalbms.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtreiwzmuy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gtlbdefyfo.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtlnccpbxd.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtmhejtkdl.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtiscwwoya.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtjllsevpq.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtixnldcei.html

s"值: $b"
来源：http://dali.ydzc1.top/Article/details/gteabxbiji.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtvdmuzscw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtloejtlmp.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtvnstmzvb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gtekuvmzqp.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtfjpehyzf.html


<!-- 参考信息 -->