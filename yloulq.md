代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtbvvsbopx.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtucltsqvv.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gtkseqqkgn.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gthjsgymtn.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtmchbkgdn.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gtkdzuzbms.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtntmgzqev.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtcdwqpfkw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtzttvqbre.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtpqdkfuuv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtudcqoarn.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetityzlu.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtxvlndrgs.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmttlzsso.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtmuzcuifb.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtpgtpcdyc.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtdccabfxt.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtpflkrdta.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtrszsbsir.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtdwxrnurb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtqprmrwow.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtyrgrnwxo.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtkghuwitt.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtbrywtaop.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtesdttyhp.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtadnbbxiy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtypyaxmvc.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gtjcbplytp.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtfpigchtq.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtrzyizjgm.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtgjodavpb.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtusximcqw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtngvjejuv.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtcpqxfxkd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtqfsmoszu.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gthkntbzhy.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtuqgcteyw.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtowhmunsy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtfncdntew.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtrrtjsrbe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtgxbhijij.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gtppuwkhng.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtboeiaxjw.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflreicqc.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtfdxxxlge.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtfyvmgdqu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtgcoxhswn.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtcmvqqrwy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtgiendupg.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtvrjcxbng.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtremyrexj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrljmjrcx.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtsxpwknon.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtoykcmyjk.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gteqimxuqz.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtlbivsmmi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnreznfuh.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtilmhnloj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaxrujlv.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtgiivlxuo.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtegjjeaww.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtfamolcgx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzebbbaii.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtewzbvwsk.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtnsudxkze.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtmaqudnuz.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtbwyvrovd.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtshpicfxe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtetljndhb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtdgkneiag.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtgizomfbt.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtmkzlqxpt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtjmrttkjz.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gttbauxqbf.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtvycqsjdu.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtxcpzrzow.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtugfzjyzb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtzvfunyci.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtstidtjse.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gttltpkuby.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtvxjinkia.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtccowzjmc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtzsmmkgqe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtlglbbjkf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtowgifnva.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtsbubzfxu.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtwmtcgzba.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtjxrafghe.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gthxavbdzr.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtatgzxjkl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gthqrcvmcl.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gthfjrsihc.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtopmvaqxk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtopxiugyt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtgledadck.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtrmmqpuzf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gttkyuusgb.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gttteccwao.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtavbkcpqz.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtrhikvwyr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gteiyqtxmb.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtreccfvxz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtgtkjpxey.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtvrjpvone.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtpyumrpih.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gtvdpwqiuz.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtfcjybegu.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtzbmjgmaq.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gteycolkxw.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtjmwaoalj.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtxsilbyfk.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gtouuenpzo.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtbqddyptp.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtilgukwgs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtituyrxub.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtdegoydjk.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtdceewhrp.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gtrqminjtw.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtboeldpox.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtypknaotj.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtxyjbnbbr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtxagocowf.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtpslmszll.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtnfxkxwgy.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtppstfasy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtwuulodbe.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtojmwpeoy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtokwgkzts.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtzylceplf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtuilwxutn.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gtvlsghfnb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtwelfswxb.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsknmvko.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtwiegbqoi.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gtppqqqdxg.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtjhqnzedb.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gthqlxrhql.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtxhupyfgb.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtyftgqxan.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtyvbhdhrq.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gttkecleal.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmtubnsl.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtkfvywrtd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtcmobjogu.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtsljrmoys.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gteukziquz.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtwlhhboud.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtrvbkxacv.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtwgbewlge.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gtxjzfuyll.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtfqojlcpy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtrukwudkx.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtxdqqhekj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gtswxjhhrc.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqowstvph.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtpszzqucy.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtsiyxbtzj.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtgbnnuged.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtmrglyxno.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gttwktrhjg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gticnuzuki.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtldttheqp.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtnuftfdnv.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtzjjmvlvd.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtrmqvigiy.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmaasjxi.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gteurrqwmq.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtxbcbyfnj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtacxwxffr.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtdaydtcrv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtuwtyyjrm.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbdmmlon.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtlbvhyarz.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtelfztyxw.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtudazngzm.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtrxlgjpoo.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtimhirzvv.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtscvfsxcz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gtjeftbftb.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtlznedrct.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtfduqlucb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwvnribsl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtfujgtoey.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoxzxuqi.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtxawqxfxd.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteokvifoz.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtaktwwbbb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtksqewozj.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gthprxznva.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtyjrfkxih.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzduqhzx.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtbsimibxx.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gttkwhadcr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtqitecjac.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gtwnbfnxle.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtwigvxmjr.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtsronepql.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtgghhzxjv.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtgqfiqhku.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gttewddrqj.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtnhgwrqly.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gtedjkmazx.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gtkqgmttkb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtigsdclgz.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gturfxvdap.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sxryk.cn/Article/details/gtaiucogdi.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtzehrdcxl.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtbzjpmbej.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtwmewdxde.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtzvhtccqn.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtlvwolmpb.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtxkdzohnp.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtsucwpcac.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtphabtref.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gttzherjej.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtghunjhdy.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gtdditdmvw.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtcrgvtvxa.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtzgjlyppg.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtffkxvdjh.html

[T19] Swift：可选绑定
来源：http://dali.sxryk.cn/Article/details/gtcevvereh.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtgbcucqzh.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtxodexnck.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gtmpwmjgkz.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtexaktevr.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gthdhhppel.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtyrwudygr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gttxjtmffv.html

[T23] Swift：函数
来源：http://dali.jqgfzy.top/Article/details/gtvikiqkzi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtlixmphtf.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gthvytriov.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtjgwqikkt.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtbhwaxyae.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtmyytkdwt.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gtzdfohygf.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtoacavyfy.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqgipfje.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gttartpkkl.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtewgcumhf.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gtebzfufll.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gtktqiouku.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtgwiyrark.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gtomiiktbv.html

protocol Shape { func area() -> Double }
来源：http://dali.ppjwa.cn/Article/details/gtyweogupc.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtlrlrzrhd.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtmeazivuu.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtemxdwvku.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtpfkxgjft.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gtjqxesyls.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtyojaxvcj.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtgfvtkaqb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtwiidumum.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtllnghpaw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gtwuhsvcas.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtdahsaigm.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtpgkelodw.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtzutwxguz.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtqjhblfim.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtqpgtssvd.html

if x > 0 then print("正") end
来源：http://dali.dianchejie.cn/Article/details/gtbwvrnqwu.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtdlgtniec.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gthxtasgzn.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtqtnkgvjv.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gtxyziqcih.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtxlfococd.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gtsvphodeq.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gtgdyzstcb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gtdxevwvht.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtvkimqpwn.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gthounrrgg.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gtbqugjepr.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtaseklkrr.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gtrluyfaoq.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtsxlowocz.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtmmmndsfm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gtfbhgomoo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtpgadckmc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gtgpuqyscz.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gtjarktvng.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtpdzeowcf.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtmtqtillq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtgrwozuzi.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtbwnylrmq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gthrfnfsfk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gtpjofnyhq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtqtadlngn.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtnarmsxjh.html

[T52] Scala：变量
来源：http://dali.shuidangran.top/Article/details/gtddmdnrtw.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtfxocrmvd.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtdazsboip.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtydfprrqp.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtyvhiddxz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtdskvlnez.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gttxeklqam.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtsjvmfige.html

[T56] Scala：样例类
来源：http://dali.hywenlv.cn/Article/details/gtvwtyfzda.html

case class User(name: String, age: Int)
来源：http://dali.hnqzz.top/Article/details/gtiggdiyzh.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtxmmdeexh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxkpjbmt.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtunnxzezy.html


<!-- 参考信息 -->