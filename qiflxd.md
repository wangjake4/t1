代发 wailian999

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gt2awqnogfu.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gt2exwhnrzr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gt2jmbfggae.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2trocfoyo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gt2vhqfuulw.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2snqovhok.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gt2ykplgpfd.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gt2pljgytxb.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gt2qiffouzc.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gt2emxdegvs.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gt2tzbfecfv.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gt2ozmzkpqa.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gt2oqirjscj.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gt2shknylhb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaqexqqv.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2ewfizpoo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drqhmitm.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gt2iownmjdt.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2jtdpocnj.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gt2exhyknob.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2biqdsctf.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gt2lonrwfkw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2ljmapoob.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gt2siramkfq.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gt2kuqjgssu.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gt2xerhfowz.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gt2stylgzkl.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2ccitygho.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gt2nhejdgyx.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gt2smsilwcl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2qghknpkd.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gt2nyifkwkq.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2odpfbsmb.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gt2ebutdckv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gt2ammlbjjb.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gt2aulprkhc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2nxfdipuv.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gt2lghjbtrt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2cjfculse.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2naqhnhbu.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gt2wnkzlfzt.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gt2hyowtpfu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2dgtovmxd.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gt2cwobtggk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2qozgdlvl.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gt2dxyfrgza.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gt2mightavd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2uuikrmvt.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gt2vhwteodz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyltcsd.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2wmmqagag.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gt2thgzbgvo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gt2trpmgeve.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynbkwlmm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gt2fjkylbwg.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gt2owstibtn.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gt2ldftibpk.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gt2ncqlmoby.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gt2yugnoymz.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gt2dqufegfa.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gt2rmdgqbxf.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2rkytwydx.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gt2kgfuzsfv.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gt2hkthwcch.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqroczrq.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gt2wynptbfr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gt2dsuaofmi.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gt2gukzbgef.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2bgmqfjjt.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gt2igisqpor.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gt2fzctmnjw.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2neyypupq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfesczpw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2emgazfzp.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2kzgyhmjv.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gt2fxstaqpp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2wshcpqqk.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2dggmweqf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiorjunl.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2ljaidhvd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gt2dvbwyyhy.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2zkktjutu.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2zdbdqbfz.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdphdkwm.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gt2nznrxzlc.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2jdayxcis.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2uzzxmewm.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2wfcnurjw.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gt2ibboslzw.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gt2vnazgtpx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2eadilexq.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gt2hnhguvxg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2qdjqjdpc.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gt2dnyesrcr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gt2qwownqwh.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2pymvlpdk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzcywnih.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2rgrdvceb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gt2axjhucxr.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gt2zojrsmcs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gt2ihfdsluy.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2jewgslsf.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gt2dyjpyiac.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2bryssbpu.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2usscnvoh.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gt2vyaduqxk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzdgiku.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gt2aoxjgbjw.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gt2aztrwfdp.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzhcxqwy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gt2gjitqdtn.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2ljrzsojc.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gt2kvuefcpf.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2ntstyzlz.html

#endif
来源：http://dali.cheryme.top/Article/details/gt2gsztltpo.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2qtieewzw.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2adbrtaej.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hhravsmr.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2mxalmszl.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2nfdjiuay.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2rbrabzgb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdakordu.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2efkuhsal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gt2jrynywoy.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2nvxzfvfo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqzarlpe.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gt2mlgenirz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abifevtw.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2fkfzzwjt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2vzinsxhg.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gt2ixpetwaf.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2kerazkdw.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2qltazhzq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2ifkbwjqm.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2kifriaka.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gt2ikzbzmsx.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gt2vfukqrhe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftfvsyth.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gt2ftsblqyo.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gt2uuhtxneb.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2rjlklsuw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gt2nrkgkxsg.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gt2thnhubsz.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gt2kffmcspd.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gt2ruaysfxy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gt2scngakmf.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gt2mckydvoh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gt2uuamwflx.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2vkwrqhry.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gt2hwhpsrsd.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2gopedxxx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gt2kryznlcd.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2gplquqiu.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2cejrediw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nibxxikd.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2tjwajcuq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqumdrvd.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gt2zajgtess.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2agsihswm.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gt2vydjjzzq.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gt2vnzfrmde.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gt2evhoiqvu.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gt2htfgpqnu.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2pfzlncws.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gt2sojxyzke.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gt2ynktyzlc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfojsuc.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gt2gsxbawyf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pwxnecyw.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gt2hgquytdr.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2ibhefqwn.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gt2aedswvkz.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2dluyivvl.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gt2zplunbyj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gt2nqbzjqzp.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2tnlmwwcd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2plawstlv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2orqhvdzp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2yjffujfy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2lcydvxzp.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2kcqfsxgk.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pisppgzr.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2mobqqfjl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gt2fipnxrog.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2pskxgtdt.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2etzguzdi.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2sjcapjvq.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gt2ojksdpig.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gt2ivcflzyh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2iktiguyq.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2vcfdfdxe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2jgltumwx.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2bvsdroyd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2ctkclnko.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2bvxizzbu.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2fogjxypy.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gt2ypsacbgc.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gt2agrbzbts.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2jikeshjh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gt2iasnhaty.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hooiiild.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2qtlnqgwn.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gt2xxifzpxp.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emlrehvf.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gt2iughcbnu.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2tubiduyk.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gt2xkskcscx.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2exkhbmcw.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2hyhckjyx.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2nccpsbqy.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2teppnrqd.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2amqxyifz.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2yoytdwoi.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2htnlvdpt.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2lngzaiww.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gt2wtsxogbx.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2rawjgjzj.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gt2asfkvyyn.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gt2itaadblt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aeraxgii.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gt2ibbvuiiz.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gt2apdrwnvk.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gt2gnkrrsuf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gt2sjramumk.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwuxagti.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gt2lkkyuodq.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gt2rnopdjkk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2txqegvod.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzylckec.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gt2efikmgqd.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gt2kxdweamh.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gt2opfoowvx.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gt2fsuybrrf.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gt2fqbgefng.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gt2qccaejje.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gt2dchviayk.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gt2osnvcsoz.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gt2yrycvjay.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubxsfpuy.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gt2opvswtqb.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwwlkzxv.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2kblyqeov.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2snbeahuk.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gt2qivfhdsu.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gt2gedpsqtf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gt2acwuvyda.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gt2bqurmmcb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gt2vwhltoya.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gt2eiryiwtv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gt2pepataft.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gt2jjmekuna.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2qmdjxxna.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gt2izmmmsvt.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gt2ozmsvfmf.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gt2acssrnnn.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2ypkmygyi.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2evhreuut.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gt2qzhmojah.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gt2ciqkslat.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gt2mwzjuiss.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjjynuip.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gt2jmjfpjrr.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gt2vcpfjazw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2zpnbnkcb.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddswgplh.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gt2opnjqita.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gt2mpmdbdes.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gt2vcbkimwp.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gt2zyihlepl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rarffeiz.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gt2nzfxkued.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gt2slfcgnlx.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gt2ubcfobcq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gt2qbopofpm.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gt2hbmflnme.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gt2lneaecfa.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2jlswsjtv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vfetvkyl.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2iojgqfqo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gt2vctjxntn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2dzpjsate.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gt2nmqklhlv.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2cocqbphw.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gt2nxkknogg.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shbwqtae.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2rhzueyya.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2spayowes.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2capmekrb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gt2thrinvkx.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2igurfmax.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gt2mvwdiuxh.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gt2fdvlgbcp.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2clrjliyn.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2ucvfmahp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gt2ydmdilno.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gt2cnksmelb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gt2ocnjqhog.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gt2pyilykzj.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2phqgptly.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gt2rvfyrgwi.html


<!-- 参考信息 -->