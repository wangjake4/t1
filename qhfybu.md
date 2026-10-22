代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2gxljkilg.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2rloxwqvq.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gt2agjxypvp.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2erotupqq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gt2hpojkskf.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2fhxsrjhf.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2zvolpcgd.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gt2rtvyvfcy.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gt2apwfzabt.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2uevzqwmz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2gborijiu.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2kpapwvae.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gt2ooupibbg.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2itddqgfj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2gsnpkwfj.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2foxhzplt.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2minirxrn.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bruexjix.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gt2asaujpmk.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gt2xboihhft.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gt2mvstcutf.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2qfuzvaar.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gt2kznppwyx.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gt2ogjmtsau.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gt2rqirjfet.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gt2pbxpgcqg.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2ukaosrop.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gt2ecdxpqqz.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2rkutksrn.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gt2pednnzlc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gt2kyeyxefq.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gt2iptsgsoc.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gt2qkemqwix.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2rmqzqmse.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gt2zzhjtnxi.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2tnkwissk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2vokaerhj.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtbulqdd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2xjhkzbks.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gt2svsbgohd.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gt2lkcihgjq.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjvgzpvn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlaedygq.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrocxmtw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2ajfmlrsr.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2nfvsybkm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2hzlavcyg.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gt2ifbdgyry.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gt2mqevysff.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2tnhdewyb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkbynzdr.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2oakrybqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2xownlvla.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gt2tbgkeuco.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gt2fnsufeqo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xntjncaq.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2ivgtzizd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dnvamcbs.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gt2fshewykd.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2uaotaqfz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2uhvjwaxx.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2aksmrelb.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gt2lxyymczt.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gt2rtwsoqxz.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gt2rhrvxgyv.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2saijtzbe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2fqjmjdxs.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2ntgxchcy.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gt2zxmqjjzy.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gt2fndwscmh.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2yqeyqxue.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gt2tjfbvrak.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2ujkfmftm.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlxefcrm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gt2grpdvjpx.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gt2umsxkzuc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gt2wrndpfxo.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gt2urxhthla.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2qpyzpoha.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2janxmdcj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gt2aulaziwb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2gfjhxglu.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2xyhrkscc.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gt2rkklgwac.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2twmcbnrv.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2jlmjnzpe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2nwunthfw.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2terhzghv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gt2bpislmbr.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdglnhip.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gt2ftpedmjk.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gt2edlsyeva.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gt2rnecnolz.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dwggblso.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2qrqtolpu.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2ygrlbpca.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gt2wradwbpc.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gt2olnetgyo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2nrmkgnav.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swbewhss.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdxlmdsp.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqetnuvm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gt2wzbdjzui.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gt2qwhrhqrx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gt2yggwoqwx.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gt2nagzbiro.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gt2kssjvvmq.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gt2ubaifcyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gt2bvoghrjo.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2rzbxecje.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2mqucckhn.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gt2fhzyijwr.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gt2wwbbgzcx.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2seatbqba.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxwslnsp.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gt2ndfzjron.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gt2hnegircl.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gt2aqnreczz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2lubnjlsd.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gt2yzimdwqu.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbodfqza.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2posjwsou.html

#endif
来源：http://dali.yj202588.top/Article/details/gt2lrziqipu.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2ozigbhhi.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gt2djuxzvxp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gt2rskyowhb.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gt2zqsrxyma.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gt2acoznpwr.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gt2hcqxnwnl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2tzxqflpy.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpewgptr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2atajfwae.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2namgjznv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2dvkkbssr.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gt2kcbosjkb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2xxbklaxn.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtnhdvmq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkbbgjwr.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gt2aqpidtye.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2dtnaagpm.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gt2uiajqjgi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gt2wnqtyhaf.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gt2lkglvodz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gt2prmvyorn.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2hvjvptbg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjdwqyup.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2nunemebz.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2ctklfnqd.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udtrenqj.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gt2qbtginzb.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gt2ewgmgynf.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gt2bzhykvxw.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkaqdtwg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2rqirnjzy.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gt2htaiyhrf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gt2mjitqkny.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2mjxzquvm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gt2whjkbmyz.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2wfuyloqb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gt2fizvivze.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gt2jxharuog.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gt2coebneri.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gt2azgmcrpq.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2klrpddeb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnalwqzp.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gt2wfekepjy.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gt2teybrpbl.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gt2rfsoscit.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gt2edhelnbe.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfmeotdj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2niyquuzw.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2uowksleu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gt2wbgkiask.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gt2qqgzgbbd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2cgcuyenz.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gt2loxnhywb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gt2wuwdqvwu.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2ksdkonuu.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2dzsfncub.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2wfynjosy.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gt2mjlqcvcs.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2srulatjm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gt2tthzecwi.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gt2peartbkt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2gezdluqb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lilimtwq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2mztgvprw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nhsphckg.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2yuoruwga.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gt2dmtgwtgn.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gt2pldkegxq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbidbxpn.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2ocgqsdjv.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2cdyludyg.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gt2psxyrvho.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gt2rbyhkmxp.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2hcqkwwow.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gt2hszafmbu.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2rxwcguvu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2diyufshm.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2kjugxnji.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2jtpbpelg.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gt2hmvwyhps.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2mgbjjjhq.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2ggdmzkqy.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gt2agvzpomb.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gt2zedatlyy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2kuuabhzy.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gt2cslbdcpr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gt2sytietjr.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gt2mclfkeci.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hpxxpcwo.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gt2bgjjlsqq.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gt2nbocsbjp.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gt2svzjyqbd.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2erdzqmyy.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gt2znhkoggq.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gt2iumcntxq.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2rxnavdcu.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2ymccetue.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gt2vdpdicvh.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gt2zpzsbctf.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2pnzfzpae.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gt2gzksjldb.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2bwguriwg.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2mebxjili.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gt2zrtwneps.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gt2voygklpp.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gt2ocftncnh.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhnaglif.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gt2jxqxnibr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfgcvwds.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gt2zpzjwiai.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2zyoutblo.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gt2ddwfirmy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2qmozjdrg.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skvqmxzv.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2icpdvuzq.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gt2yovoyths.html

class A: Base { override func f() {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2ooxvbunk.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gt2wrqtucbh.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gt2iaigewej.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gt2lwskxlkn.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gt2pzlozfpl.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2vijqtbky.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gt2chzlvxoy.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjordjdo.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gt2lwvznyvx.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gt2mkbietqj.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2gzctjizz.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gt2yjwcbdqn.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2whzxltma.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gt2ejtzooyp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gt2wedxmdni.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gt2ibsbwypz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gt2qutiycps.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gt2zbxsqxdh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2vymvxxvl.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gt2bsdssqwa.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gt2soemxtaj.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gt2ftqoeozj.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gt2ythefjrc.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kulrriol.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gt2vuddrdhq.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gt2enhiqsao.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gt2qkfvjikw.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuxemnch.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2lrnjoehz.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2kyeydugx.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gt2dhqglazd.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gt2rfobqlkh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gt2flnaoyqw.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2bxabjkmz.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gt2vawzzuvi.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gt2mvflpzhs.html

if ($a > 0) { print "正"; }
来源：http://dali.yonumen.top/Article/details/gt2qegojwlb.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gt2vffwhwmf.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gt2obrgnohs.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gt2nvlrptfv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gt2gefergvc.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbaqtlwj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2xxncuqff.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gt2eryhirus.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gt2tvcfulie.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gt2yrmtsqgw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2tigpycpb.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2kcthxffo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gt2crrdkrye.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2vuwtikfm.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gt2vmsdyxgs.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2qwyateon.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2boiicink.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2xtexcmro.html

[T53] Scala：字符串插值
来源：http://dali.yj20258.top/Article/details/gt2ugatjpzo.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gt2hklgxipg.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gt2zethymxu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gt2jwalmttx.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2invlkckl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gt2phnmsajh.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gt2thrvihnd.html


<!-- 参考信息 -->