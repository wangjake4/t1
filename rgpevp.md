代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2cecttahe.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2dnqokzyf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gt2scbixmvs.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gt2naxtmssi.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gt2ilmhlwlc.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gt2okirybwc.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gt2widdfkke.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gt2pfepapjq.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gt2cqrnfdcb.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2orbwgejr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gt2foqbenmg.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dupjqttl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gt2cedthgbg.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2ymtbjyln.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2rbeaddxa.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2omopokff.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2nwpuolqc.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2iaynnbuq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gt2zwtktjwz.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gt2uzgbvgel.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gt2lhlusafy.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkzthxsr.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gt2drjzrvyl.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2eglwjeaf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2sefgbgur.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gt2ydxxjjal.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sibkhvov.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2ikhkswdk.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gt2qbocpvqc.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gt2ivxrxynx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2fegsenld.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anbedyut.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gt2mtkidaiy.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2rqtgrbxc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fukwrxgu.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2vfywdjws.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gt2eyikuvdk.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gt2bcvpdqkb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnwvdmos.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhsdpeyx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcsmfbhq.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gt2lcwxdtva.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gt2xdyrhren.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2mwgewovp.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gt2gvhoewpj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zmqpoegg.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2iqacffhw.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gt2mvbmxmdb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gt2xbkiiikr.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gt2upvyrvbf.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gt2zafskaax.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gt2cdgikkif.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gt2rheppqvq.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2ykqpjbnm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gt2ykxloxmm.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gt2oobvwksf.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gt2hbaovsql.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2ucjutdwq.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gt2tzgjlmmr.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvuxnzei.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gt2kxrcbaay.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqfhssbr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gt2wctyznqi.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gt2kqbwjwih.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbffusfi.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gt2cgbcjzgc.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2bhjroujs.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2uougpjfk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gt2kizebzau.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gt2fzvqpbrf.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efikwoyg.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2oigmoare.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2moimfeaa.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2vglarvrt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chvtyyff.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gt2zuemrdbo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2mmzwjbwh.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gt2gaxwbwre.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2hheigxoq.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gt2zdldgshw.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gt2noobeyxl.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2upzpcnzh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2vypihhaa.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2zyygniwy.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gt2nclwdqcl.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2pndwduda.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2wtvhipsi.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gt2ostlpjhi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiajchjr.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gt2cuvzndjx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gt2yoedwqjx.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gt2ecajdvzt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2nhzrpcmo.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gt2bzucxwtc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gt2vduxaern.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2jpbqdwea.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gt2tvlbcpog.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gt2vhkjsdpp.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gt2npocwvit.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gt2chzhstpe.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gt2qbabrgtm.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2tnmpjffs.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2whxuigds.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gt2qaqqyajk.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gt2mgyspdgj.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gt2qgsgghyi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gt2rgvpqynh.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gt2ozszcnph.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2hovggcrh.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gt2uzgyxjke.html

#endif
来源：http://dali.ybcxt.top/Article/details/gt2hhopyycr.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2skkzfyqe.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gt2sdccaqed.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2baureurv.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gt2vkwpyiza.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gt2firluaxm.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gt2ajnushcj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gt2otlbtbod.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2fwuttmsr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gt2kwgdkyjo.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gt2ancjavub.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2bchiddas.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gt2mdasxkfg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2khhlefnm.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gt2lkazshdc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gt2axevuean.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gt2ljpymccb.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2sdeesadt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpwbnmli.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gt2unaoyfwh.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2gtaqmvfc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2lqpfnzka.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2raufwnfu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gt2znugktib.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gt2izhwctvj.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2sktzanln.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbwjzylo.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gt2kfwupdqo.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gt2eevyquqy.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2ibseabnq.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2pyahnfup.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2pfalujda.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gt2jubqbhss.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2oszkxayh.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gt2euaiaoau.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gt2sjzogedb.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2evybgwxs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2pgffuimq.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gt2kintkegv.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gt2hbfidmxr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gt2lapxmqgw.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufqagess.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2rgcvnhwp.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2mvzatxjr.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2euxystrj.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2wrjbjvsb.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gt2liisgnvf.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejegujpw.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gt2anlnqyih.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gt2eplsstdo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2faxkygrp.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2zkfijwsp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2vycjtugq.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gt2anhdqkar.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gt2rwjulozv.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gt2nugdyxog.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2xncextlb.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gt2hznhgltk.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqesrcfl.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2kddnxuzm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gt2pqkspzha.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2cqlqncda.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2dvvakaid.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dbhhaabz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2ufiwyipn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdxsmjgi.html

[T01] Kotlin：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2etpzljwh.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2vxprmyzs.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sszsiyvx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gt2rpgdeprs.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gt2imwgzgow.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2dvuurhrf.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gt2rooeqphu.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gt2zohfmaux.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncywsfzb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2ewzrrfsd.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gt2oytneeko.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gt2xyhqtdhk.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2bcfljrjw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gt2ndrmeplg.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2nybkddij.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2gwxwsizy.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gt2bpokckmd.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gt2pwggfnfo.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gt2vljjkivo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gt2txretjyy.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gt2panvjxjt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gt2vvjenesr.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gt2qbemoqsn.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2sfrfgoil.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsiphvye.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gt2tykbxysb.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2xxzxhbsk.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2lotcjmal.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gt2djuopjho.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdohtice.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2bnglqhjh.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2nkvkbfxq.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gt2mqruvtsk.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2rfuudxxy.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2wgbacxil.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gt2dzanbaty.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gt2qmfbgish.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gt2juslduxz.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gt2amfgexbx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gt2stmpklzo.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gt2aqxmmdzg.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gt2yronvdgt.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gt2trolqtzy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gt2eolzbdrl.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gt2ffquxuxu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kemmvrnp.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gt2leygkonk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2txeqxnen.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrnlonoh.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gt2cbrygwwh.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gt2ebjqdeto.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gt2nbnsfpff.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2lfebizvh.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvtfndta.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2liajcgrl.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gt2wuopqaqv.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2vrkfqgqs.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gt2resipflg.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gt2ndjltbkg.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gt2iogdvucq.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aayguota.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2dgfnkrgp.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2mursjbxn.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2gocsyccn.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gt2yytvymlv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yozjhipm.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gt2mhznfsmv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gt2bimnudfc.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gt2deiucoqw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2sadlzzkb.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjnfgwoy.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gt2ktzqxnbx.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2sxgygxcv.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gt2yeqytmwh.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2vjrpjntg.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2qghwzozf.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2whqblsbq.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gt2ptomffuf.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gt2rfmkoprl.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gt2sfvquiim.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbfybigd.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gt2lmqtbdvh.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gt2nlmfkxjm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2fwtfdzyx.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwbriwwp.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gt2bamtypbx.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gt2dgmqykuv.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tcycpzxw.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gt2axkuzenv.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gt2qxhfskkm.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gt2sslnlzhu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gt2jyoqvage.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gt2qlacxckh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2zrtazrdn.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2qxhcomua.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gt2gqxrqzvo.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gt2lbeueztc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2wyddpwqo.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2orhgnouz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gt2eewswlon.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gt2luvfkvan.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2ecsakluf.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2yyuxyuzg.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2ovmtqtql.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gt2qkrgatbw.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2mrnmmgfb.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gt2ldqhenfi.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gt2aynisfqt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gt2mxjubdmg.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2cymezvat.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cucudq.cn/Article/details/gt2robzrtdt.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gt2fwnbzvqu.html

case class User(name: String, age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgosjjdx.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2zggckifi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2dlhazgvn.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gt2sxophxpj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ydzc1.top/Article/details/gt2ikeeuidj.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekubyvox.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2wpinoeqp.html

[T60] Scala：折叠
来源：http://dali.xuetiantiany.cn/Article/details/gt2kldtmngj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dashuyun.cn/Article/details/gt2iumvgrcg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2uelwjkjw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2ujtsynoh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dfwzpndz.html


<!-- 参考信息 -->