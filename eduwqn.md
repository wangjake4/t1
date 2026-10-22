代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2yfdaoemr.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gt2eamicuyo.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2oxvhghxt.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gt2gvapodei.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2yjnjvhof.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2wjirlkyn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2ruhviynb.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gt2brxnxjqo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gt2zfoefybw.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gt2jgmjbdus.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2guzouqbx.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gt2avtawvcx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2mxfsswug.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gt2qcfqnukf.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2gomqynht.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gt2xuhizdhz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2xijkgeym.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gt2mywgwtmi.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gt2tdctncuh.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gt2zklhzkaf.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2egtllhvz.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gt2uosbvbhf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gt2epxblght.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2nhamvkbo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gt2axidbyzm.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbdjyaof.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gt2pntjzoka.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2ofkixpbb.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gt2ncgzanth.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gt2pgcwscrh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gt2bqotuans.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gt2sbkbbrkb.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gt2hlemgsuy.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gt2psmtucvk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2oswexhwh.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2nmmrbmfo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gt2gwwjtuud.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gt2crrttkpb.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gt2xfhrikox.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gt2ifmsxctu.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2expgbxtb.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2vgaupyep.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2qkajytfj.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2vafxzcuy.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gt2otfvakrr.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsyxfjqj.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2xldydwhf.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2vrgxtagu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gt2rbdopesq.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gt2vdcdztfo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2juzoeyet.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2xolrtkxt.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2vilnsizd.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gt2nxzudasc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gt2zpzkqclw.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2jkjuhunf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2vmpucgev.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gt2acpmvmse.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2apqavmen.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gt2fimfpqrd.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gt2anskssxb.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gt2syrlrebo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2iuigjmrw.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gt2xmvymbto.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gt2fevuemxp.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2hrcmkayw.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gt2bgkpsvoc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nifrhiar.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twouxkrp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2lxuxydpt.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2milajbbo.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2zvrtsynw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xogjoycb.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2rxqjrfsq.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gt2kaytjiqj.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gt2fgbcpxgy.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2rnseklrj.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gt2azagckea.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2rfosgmiv.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2rsekqwja.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2kxjheyba.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2ocssutsa.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gt2mhkxphxt.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2oapsvxph.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gt2dkbuxyml.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gt2mxyrxwio.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2kyvpdrtb.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gt2lusjubyv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gt2nlnyxedv.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gt2apyyyofi.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gt2qiiigzji.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2xcpkmzxd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gt2mezwoqgo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2rjsaumzs.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2fjdprswv.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gt2ixvslwbu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2mforejud.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlojvoay.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gt2gcswzcnp.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2osgrndep.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gt2qxbgjdox.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2zjjfyczn.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gt2uwfajpvf.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gt2lcfntuaa.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btwxhdnp.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2jveccuod.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gt2eugxdfcl.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gt2kuwirbbs.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2hniimeei.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gt2oeqjhnic.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2bvncmten.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gt2hfwixdhf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2vogngvxy.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gt2lcqgbdfw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gt2wrgdlocl.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gt2uebjtvub.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gt2myzwpdxx.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gt2vcpweigs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gt2vfztpjhs.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gt2nfdnncpo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzjeubqg.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2fszlinqw.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2ekgafdsx.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2mtkbtlqp.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2lxcgrvon.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gt2kmsugmcf.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2wgvqwnvo.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwgbkeny.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eilknctg.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2begmymmc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueklzdoo.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2kcirevwq.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gt2njhqnzrg.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2ndbpesef.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gt2vulopllg.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddurdqwl.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gt2mdldtksb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gt2dinhqdgw.html

[S32] C++：字符串
来源：http://dali.cashguo.top/Article/details/gt2bfewsegg.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2ycyhwifi.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gt2xglwqgyb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2kaibmspc.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2rosnytsr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2bhrxnadt.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gt2veozilbx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2ycgolgvx.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gt2komrabdv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2qiajjxwi.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gt2jaweggdx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gt2jlpzzvqo.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gt2ctekydml.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2pjnqflxh.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gt2jpfxhexc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2qytfbkga.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gt2haxmmryx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2boryikfw.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2esmhhbaj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gt2csoananp.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gt2mzmbzidc.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gt2fzfkflpd.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gt2raozdfpp.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2lhhuecws.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2qkdjtwvj.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2ncgeplkk.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gt2jqibsfxe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2pumrsxic.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gt2iwwivpve.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gt2lldturxs.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2ztxwjqar.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2bokcfmbl.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2zqybcltg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gt2isnfethg.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gt2rwxmzbne.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpxgndnx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2feltuucp.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2rcpuukws.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2rzozkqcy.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gt2ymbfwjhb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxrpcfc.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2lebgebyp.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2obediuvm.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2pfkwhpls.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gijteetd.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gt2qikfznlh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gt2hrxolrfo.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gt2ifzbtxyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2yjqemdcl.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gt2rvxcxbeh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gt2lxkukakx.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gt2rtznuhrf.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2blhixlrp.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzjnpvln.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2daygzmhe.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2apvjtiwd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gt2kcervkpu.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2faqlcoga.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2glbnjujh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2cqvtqsod.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2snxmbdcj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bpxmpfws.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2wajrygrb.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2wfcmolvd.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gt2msmseldp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gt2amiiiqdi.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2nxoqwfxh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxlrwgk.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gt2tzvrrecu.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gt2hljauycq.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2hzesrzgt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2vhlharaj.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzksaekp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2gzjuupfi.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gt2bevbftui.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qukukvqp.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gt2tnodggkl.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2cudymjyl.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gt2nuumutnm.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gt2cbhluuuj.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2uovffqff.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gt2bzlraztb.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfbaxlal.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gt2hzxpsgxf.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gt2snfrukfo.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ndtuxhjq.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gt2iqeepqab.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gt2kxhzrvzy.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2stmjrfej.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2ceyykgbu.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gt2gevweplv.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gt2pwopiiwu.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyirgtiy.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2munzxlnx.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gt2xnaeddtw.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2mcefsojt.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2yuyvsocm.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gt2wcheesho.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gt2rymjiqsm.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gt2ijqarrfj.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2potvtpct.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2fexaoseq.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gt2hcbqkhwd.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhajxwif.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxwquoea.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gt2nzkvvbxg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzomgktv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gt2woxaxtau.html

[T24] Swift：闭包
来源：http://dali.shangyingyoupin.top/Article/details/gt2djlibvxj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2qsqzepjg.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gt2sgclvesg.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gt2zqxgsasa.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2mdpfjssr.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2cimeohqg.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gt2cohbflpx.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gt2ipjsfadx.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2tppejsdx.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2xbtrrizx.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gt2qillnvye.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gt2kdmngnqz.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gt2duesqebt.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gt2lldoplnw.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2cjeeeukt.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2pkbbshrc.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gt2dgqraocq.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gt2gnidwixv.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gt2ehjmgqkb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gt2nyzibuxm.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2lqnocunx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gt2fdvbqrdb.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfbpgugl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2svxwufdi.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gt2bvoqythg.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gt2hyrewsat.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2ulbecrhq.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gt2evlspmek.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gt2mglzuacq.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gt2vcdtuyio.html

[T39] Lua：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2utcmzloq.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gt2qplitmsw.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gt2cmxxczhu.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gt2helopptj.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gt2dgqgyykz.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2ukggehag.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gt2ncpmohgg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gt2amodiuvj.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2jdyhasfi.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gt2tiovpixy.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gt2ehfjepax.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vdbydkpr.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gt2gqrpbdmp.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gt2puybewzv.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gt2piebnhll.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uesasqxa.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gt2jivvpwxw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gt2hmcnzqnq.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gt2jmwrgeou.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gt2ypbinnfz.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gt2tayhceld.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2xnqoqduf.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyupknkb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gt2ubeljsmw.html


<!-- 参考信息 -->