代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtobuuihel.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtklpesxur.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtgcxhjlap.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtzkzualhe.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gtzpomyigx.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtohyeumec.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtzsbatbym.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gturfkpkxk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtziolxydg.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtgcpkisik.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gttuebtxqj.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gttsdfexmy.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gtqmfqdheg.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtoqzqnrjt.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtaeimyalc.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtugejhqer.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtapamdwmd.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtdybnygea.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtwacmmjrm.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtangfshgu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gttxgooovb.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtssqwozdb.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtvxwljfnp.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtiscysczj.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtdbcebxwp.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtjmtvxcvf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtvawxsadl.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtpjntkwjm.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtqbjokdis.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtlruyipqs.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtgmbkqtdy.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtcqbyaxxo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtnkfnilgl.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtskrzgcfw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtsaonnqqr.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtmqzwjqua.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gtyydetfka.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gttgayggbz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtvcnloxtj.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtjwzzhkcg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvopdspi.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtxkbgqqhb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtvkaoognw.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gthbnobohc.html

read -rp "请输入: " ans
来源：http://dali.jqgufenzy.top/Article/details/gtqwqpedei.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtuajoewsk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtssbhluwb.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gtqqhksfua.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtciuemfxy.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtajtlgegm.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gterggqjsm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqzakztjl.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtsqbilokg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgkjngsyr.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gthbwvegcm.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtvisottmp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtegabqeyr.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gttosivwkw.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtrfgrpief.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtyicnhxol.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtluqrvmas.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtiuriqofq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gthchmxbgz.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtgqspddbc.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtielksezd.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtbkygzbke.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtbjzwbxeo.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtvncuucaj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtzeumkuvx.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtgcxapihv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtbuiipnlk.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtlyfxqzra.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtbqijctsv.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtjaxohnve.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtrtwkqzxq.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtqsjfvtms.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtunefwwbt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtyfqaqfpf.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtjvgxhpxs.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtiowdejtw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtypsnoaxq.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtafkgivmo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gtyshwejxh.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtbqityywi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtxffopszc.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gthuuezhyh.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtfvxoomye.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gteycrptzm.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtlnflonls.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtevvbmnsl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtxsuuckat.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtghbnozvn.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gtkpftdogg.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtwifiorpj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtqljbfmii.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtkmnpfdil.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtypvnwvvy.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtdmpehvdq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtievlisxj.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gterpgjyjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnyglmnc.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtfzvrfiap.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtlkvgiydj.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtwmcvjgxo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtlihqeetx.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtcycckunq.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtophmoipe.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gthilpwjdz.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtysxfnwil.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtpifoquyv.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtwhzdsptd.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gtlvebhwkv.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtyiefticm.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gtimvsufnb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtcsprhoyp.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtgqhnmxns.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtxoragksa.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtbnvbzzhw.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsanhxbsp.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtxtpyezwb.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtgukaicnb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtfzbkmrpm.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtbtwgqplk.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtaedhnetg.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gthkivubqv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtczvvhpza.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtekwvofeu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtyecmffuw.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtosaqxquq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtderjjglw.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtrxrkhdhq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtkicbbjtv.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtiycympcw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtlclkugca.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtbladmaze.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtwjosatau.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtqbfyhjto.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtachqkgka.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gtufcuphtn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtxajlgalf.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtbhegypgl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gturbvgtrs.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtwnfxgdqp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtrhecbcwb.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtwvtabtrg.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtleeeqlnx.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkjuajpf.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtvcwnzdyn.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtnjxznbvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtzdedyrrd.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gtfwhnrjqc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gttsdwqxad.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtgqdiudoh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtfqeiomul.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtbotcqiku.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtwrzkmnsl.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtinflthqm.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtasenknfw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gthcbsvgdv.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gttemhkvvb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtggmhkten.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtgejvbflo.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtiqhzchdj.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gttrlrvruh.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtkuvrdhii.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtgamchclg.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtikkiawya.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtvnahndhb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtlryimuxv.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gtqqbczbjb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gthvtfslnz.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gtlfodzyne.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtskgzykrl.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gthevkrrqp.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtehhnberq.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtjwepvlpu.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtnknzskfx.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtdrfundom.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtwyqplkjl.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtgjcnqmvs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtthczejpj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbwakjvvc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpseanryh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtizfmpycq.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtcgaxqmmz.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtfatgqaju.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtigpitzpv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gtmdyfabhf.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtximrciec.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnhxehgu.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtqqseszkz.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtcuzgaqmk.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtzadhsfag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtbcnuoayy.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtkpsutcsp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtnfvphvyh.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtoxnlmeiq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtrqythmny.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtdziyvsdo.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtmtkrmqcm.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtccqucyba.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtfyjwbwpo.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtovucgfrr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtdviicrme.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtarzdahcp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gthyropstm.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtrpzyvqxl.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtxpjsabim.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtskevqwtp.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtvivriekh.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtipkkkqfw.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtmihgekkk.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxusjjsw.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtjqlkqjjl.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtgjblugdz.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtpbuzfkqp.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtrcfejvwn.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtpzuobsmm.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtzgjncwxc.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gtzitcebrt.html

[T19] Swift：可选绑定
来源：http://dali.zycfv.cn/Article/details/gtuzjdynte.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gthwdjspag.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtxsbumpjt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gttyjvemyc.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtfswpcmom.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtqqelisxn.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtsckmjgfi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtvajsgahw.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gtutnnqzyt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gtxmuzblns.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtknsqxymc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtlcplzflb.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gtwpnnqllk.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtznwxjrze.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtfupiazxb.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtceiyhlwe.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtzdbmqr.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwozsxjfw.html

[T28] Swift：枚举
来源：http://dali.pycfn.com/Article/details/gtpkgpxser.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtjuzrzdyw.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtskpzjlgn.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtauklxknl.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gtkpjxzlsx.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtjsrohvtp.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtqhkidwcz.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtqidlwkvf.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtongdzneb.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtcwrhndub.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gteczasdiq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gtkhckbaea.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtymolpybe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngrvgjom.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtxccxqloe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gtmwnrhymm.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtczhfifuv.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gtfckmjbec.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtxtmposbg.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtdejwigsa.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtpkpewbnj.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyktmqrj.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtdabrtpsy.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gtvyhljfns.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgexfxdzl.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpndqfcf.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtejzedmuc.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gtlkbzqvwp.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtjlylboxs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gtszhvxxpl.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtbtknnozs.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtpyroiqjb.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtruqoqmgc.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtbgrjdyaf.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtttwejtzk.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gtugttedud.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gtcjmuezqt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gtrpelmaeb.html

[T47] Perl：正则捕获
来源：http://dali.yj202588.top/Article/details/gtzkvochru.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gtyqakdimf.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtdoblnftv.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsokrwnwg.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gtgqywlhkf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtjcocdpxd.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtdwzmmxlx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtckmgaxzr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtfdmwkuag.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtfelrfmsd.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtunyjzung.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gtxnveraie.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gtixcgbvno.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtrvyrjtkh.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtklmdnurb.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtfpoisegx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorxqjzdz.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtipnzsoxi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gtcfxzraek.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtcnnipyqt.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gthzyhxlmw.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtwrhzlivb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrunfxvi.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gtmistdztg.html


<!-- 参考信息 -->