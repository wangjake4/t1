代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2xddkybet.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2fvdwdazu.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gt2bluftant.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofjnwgor.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2bmdljiov.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gt2irzpyezq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gt2jipefydm.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2vliligfc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2snhbmvus.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2kivtmpmj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gt2avmgpaem.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gt2ptocupbh.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gt2fklttgjb.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gt2fbohrvqu.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gt2djirvnkj.html

[R63] 内存与进程
来源：http://dali.ppjwa.cn/Article/details/gt2rgvwuapt.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gt2fydpjkut.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gt2gblybbsm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2ujbcinvu.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gt2qcafjzmf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2gtpicthv.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2uvrjckys.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gt2jxakczem.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gt2mazcvznh.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2nppecaib.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfmvnddx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhomivqk.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gt2mxnmaann.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gt2orisvcex.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2lzmsowjs.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gt2nqkkpiyi.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2xqqhdwss.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gt2cpysxavl.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2ioiuyavp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2vphilkjm.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gt2uoqqwjpu.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gt2pjhhwmdl.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2jaownfra.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2gkoniuck.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2wdaqczoo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gt2dolmiyua.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2mfejvvaq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2nccpequd.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gt2pozfbyad.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gt2bgufqlvd.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gt2qthspopi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gt2wlkekqrx.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gt2itaeymrs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2fvqibokn.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gt2ztbphkzi.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2tiqapoqv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2flmpyqft.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gt2mklonaxo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qlpbszck.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gt2jixcbztx.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gt2ixqbrjsd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gt2rqxuhokm.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2cxqbjord.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gt2tfypzuyc.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2wmqacsjg.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gt2hxxmejow.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gt2ggpireyk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljtuwtrm.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncqoqvvj.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gt2qrdhdotq.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2cfotspvo.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvlyiooj.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2rbuwpavi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gt2ncqgqegp.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gt2yyvruzql.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gt2laebkjyl.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofzzomhy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2cmogrvyw.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2tcwibfsz.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gt2uezpwzzl.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2fqrsaxkf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2pbqfvvjd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2mebmdwqv.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2tclobolf.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2mgcuovbf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjovqrvk.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2dnpipmbu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqjfmvxy.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gt2uctmnhrq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2bvipaiob.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gt2fqdvctaf.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqsnnztp.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gt2rwozutnx.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gt2aeyemmzz.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2gwtociyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2dpsmhaxg.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2uqhebfqf.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpccksat.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2eftszuyk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2zuotsvkc.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gt2fankuvpr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbiblpwf.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gt2hdadcwoc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gt2mjnebgqt.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gt2vaenwthv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2rnpeauzu.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gt2rljjczwe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gt2oevzgjvl.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2acnpzbuf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gt2oqnrsbcv.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gt2bjkoxjbv.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gt2krlirdws.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gt2cvvzquiu.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gt2mphjckdh.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gt2zmkwhwds.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2soqupwic.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2ldqgoqho.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gt2mtibowyn.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2ejwgdobg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gt2stesvwpz.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gt2iuwwfoyn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oewxeoxd.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2nzwkbeac.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2avaytzgu.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2srosoprw.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gt2eqsgtizi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gt2lgsparrf.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gt2jnmwvwvy.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2zgahmqil.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2ptwkezxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oplvtcez.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2dkmllrfp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gt2zsjnehzp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dftaqblp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2dlfltyau.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2ezhhpjym.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2luaheunp.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gt2shpdjewe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gt2lhpsqgtn.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2rctinxie.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgyxzvei.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gt2ucmtfnwc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2audyecem.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvzzebea.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gt2ecaewqwe.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2waaicaes.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2wblcpiaa.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gt2vsvndgqt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpkptvno.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gt2lfrttwli.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2nevtaykw.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2vnzvarjo.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gt2ldhqalic.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gt2lgvadcww.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2srcwxtkq.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gt2rhidhanu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2anfmufff.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2wypymnhk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2xkppgegk.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2uvruyadl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gt2wbpvjqvy.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gt2flvcxcsi.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gt2koqrsnwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2mxhkxsrs.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gt2aueyhshd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2eekhxnqt.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gt2mlednwae.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzjjfkga.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2sogwaehn.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lgprmlzb.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gt2vdcjjupe.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gt2ayjfrlgt.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2yljuenwj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2jbousfvu.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2rhqerxof.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmglpzhm.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gt2cmtrjets.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gt2cmwhkqvp.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gt2mbqbcpda.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gt2xmnqwrpf.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gt2nfdcxlnw.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bynmgcbj.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gt2qzmmgpsl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2dngakfzp.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2ixyeabge.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gllzmhuh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pngegyqr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gt2seeenmjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxxkmoe.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2qocdafli.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2nyxhupnw.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gt2oeykcpat.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gt2itkjnxpm.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2ynhtpret.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2rrbozugf.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gt2svsfeivq.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gt2tjmjrfcr.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuripyfy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gt2vztjluhy.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gt2ibjxdsyc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2guxxsivi.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gt2pmhgugvq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2ftdgvomv.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gt2oeghmpjy.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2vqumhhgz.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gt2ucixclhf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaybqhc.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2duubwfad.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gt2oxifmmmr.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2tbxxagpc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2dhqrbtdr.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gt2uccmasgz.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2nwisrjka.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuatrucq.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gt2aotowgkh.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwljcdod.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2ixitfccy.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gt2ndplsgec.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gt2wkbcyduv.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2gqfynhsc.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2kootgtqw.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2bepjrrvw.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2fkhrqybi.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2wphyyuno.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snubjhuq.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gt2ayjugfai.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gt2pmdoayou.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gt2qhhdccqm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gt2afujlvjz.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2tzclujvp.html

for x in a { print(x) }
来源：http://dali.daria6918.cn/Article/details/gt2vkqkrdky.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gt2blahxdol.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gt2yupsqdah.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2raifpmvp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nziclzjt.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2qlvhknac.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2lgxjizem.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2wpolmfsz.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gt2kuqxqxjq.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gt2iscuyqbl.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gt2dsyqrair.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjxijbvp.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gt2tcvgcdig.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2nvlgvecb.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gt2exrybnmi.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gt2oenydkak.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilulpfhv.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gt2dlutswqr.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlrvwugt.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2jorbtihd.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2ijyamevg.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gt2szzjfeyp.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gt2nltylgtw.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gt2vfedvqvc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gt2yeklzxsi.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gt2kxegfdyl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2ylkwtdik.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gt2bxkrvimr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gt2xalunqyf.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gt2lymicopn.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gt2qxcncari.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2oqcwthsx.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gt2uegkjccm.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gt2itwuluvg.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhlvyyun.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gt2zcurqogp.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gt2kecbrtlg.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gt2stodxsji.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gt2qifgwyix.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gt2lqwduldq.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gt2gvtvkbjn.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gt2tqnboghx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gt2jdylcfkb.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2riwqskik.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gt2mohgznvy.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gt2dolymuoe.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ecenjzqn.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gt2nlzkniit.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zwawmwal.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gt2meuufscm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gt2tbnfprxe.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gt2rgttvdcu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gt2dqpxrdip.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2jblsrqyl.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gt2hbkwoscr.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gt2tflghfgs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2bjdnebcq.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2rnckqmiq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gt2wjglejyj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gt2nbcxbtkg.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2keeaxyaz.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2irouuhsa.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2bfwaxfcl.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2balughvx.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2kjlyzfge.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2tmaucvxe.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oawpmtce.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gt2zjaxhoxc.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2zhksnvvy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gt2prpdzbkw.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gt2xlanwgne.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2wlrrctuo.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2uikmglei.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gt2hjrgandb.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gt2pewvmgcc.html


<!-- 参考信息 -->