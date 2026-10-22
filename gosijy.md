代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2vcqkuuim.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcezdnky.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2smetsjro.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2vwxrckrm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gt2bzpxrekj.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gt2tkzlerxx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2ismflryf.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gt2ukjnjxtr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gt2ulryijej.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2mkoekqym.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2zdtqgvba.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gt2wqeyvshm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gt2fppktsqb.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gt2twnlfosp.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsuywcmb.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gt2aqrcoskv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gt2ymfgbnwa.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gt2zebqoybc.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gt2insfhtjx.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gt2mcetxhoj.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gt2jstsvypx.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpyxltxq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gt2oxnzaswc.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2dvfoxdhs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2cyshioqn.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2tjtceixg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmwrfgwe.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gt2nowhenwz.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gt2adxsfugh.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gt2btkdizjz.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gt2datpiyjd.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gt2ncgidgqg.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gt2qwojazdd.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gt2kpmymohc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2quwywhcu.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gt2fputcwto.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gt2lrpksglj.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2rktcnuzu.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gt2yxqigxli.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gt2wiuaxods.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gt2rxagrcca.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gt2tmrhtsne.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gt2lexvoynk.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhlbigcy.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gt2qeuksxdn.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2bhnxjekr.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gt2hoivbtjt.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2lgzhqfss.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gt2udtucxgy.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gt2nocmbkfj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2lhkqjkyt.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gt2arqipwso.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srtqdtme.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2fqdnjerb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gt2odqoxumn.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2daomclte.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gt2vyocsyol.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2cedkjoie.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpsdklzk.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gt2cwhgrjvl.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gt2ynowcdzi.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvjlfajh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gt2otfsvtgy.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gt2ggsqktll.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gt2twcajzff.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oewnrcla.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppftvcdb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ulznynpg.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2cjqgcudo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2heqgtvjh.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2sxnnuwej.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2igftpfli.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfgwtqry.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2ucmmsgru.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2cfoerfbs.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gt2ohcuexwf.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqjxafcj.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2txkjgmoz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gt2qwllhmcz.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2hxxjxpec.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gt2nuxwjngk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqqbfya.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gt2uhpjqkac.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2ilogpdtx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2dojdgrnm.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gt2qzifthjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2yczsvvxz.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gt2ihglxwhe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gt2aogrinjc.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vswvaxkm.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gt2tlazxncf.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2eqegbjkn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2jpfcjffh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2wsqrohod.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmolzycw.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2ljhxfcgv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2mugcvaoy.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2igayanip.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2keukwqtt.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2qvdqcsog.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gt2sdvvnvge.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeuuaxwp.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2wwdgypwd.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gt2bddtjkus.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2feohykqx.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2vnsuwaky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gt2aszbqblv.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gt2duuuoadb.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gt2kykzvhhf.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gt2brmyfisd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2sotnscst.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gt2swbmfnnx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2akeysoks.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2pkvniqny.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2rrkefzdk.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gt2ukpskyfs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gt2bhxibucw.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2uapuogih.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnbfsclj.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gt2fglcinwb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gt2teeklizf.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2wzlhdwgs.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gt2mimcnbbq.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvfpzwjh.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aeoqfokb.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gt2aydxjitv.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2hbcxtrno.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2ukxxijyo.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gt2fbvjjfnv.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2rrbojhlf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gt2nrukvjyp.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlutilzo.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gt2erolrcqy.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gt2xskbxzob.html

#endif
来源：http://dali.iojbl.cn/Article/details/gt2ipzelkna.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2kabnkzyn.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gt2waekljfh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gt2fdqsotpw.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gt2oqxkwems.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbzxnhsn.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gt2xbemqlvq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2loknadcs.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2mhgmcwmb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xdhdwold.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gt2lfubnifg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvawlrqa.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkqbenog.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2fyqxdmtg.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2ldbrzxop.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2puclklkj.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gt2fogewuvp.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2vehyduup.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2nlscqmdo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gt2bjucuyuj.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2yzpuqtly.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2oqrvoitx.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gt2cskimnrp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2upaqttaj.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2onjvbimm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gt2gxwronqy.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2unkpbzzs.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gt2tczkvuhx.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gt2zhpwgdzh.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gt2itnsxqgu.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lyzgaogh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gt2ofliwqco.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gt2iuedqrmp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cawipizh.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2nywdsrts.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gt2xbmqpvxj.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2csvyzcrd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gt2eljeqawf.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2zpzosgqp.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gt2eezmuhvl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxkdwkco.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gt2ltphlhhe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2qvnoermo.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhgmlxgk.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gt2hpedlqaj.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gt2eztxbyux.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2rubvykua.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2rstvpnsf.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gt2hfkyrhee.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2zujgmmly.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tibdblss.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gt2zjidamxc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2iyjandsx.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gt2nnzkaxyd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2gilntzfa.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2dguexyok.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2hjxmvvem.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlncepem.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcssgsoq.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gt2cmwufesj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdetvayi.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2cvyviern.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2ifswkxyy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hhbsusel.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpezrcle.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2esozmwrl.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2ifrwpuyh.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2olgvjagb.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awswszew.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2cffamvnp.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2sdybvvcw.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2tckfaynh.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gt2cmoihqli.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2yrmtlrlh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2zhgrfwpi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gt2hkadpkjp.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2pqvubzpn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2tfzeyoae.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gt2osfkfohb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gt2gbuijuqv.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gt2wzpycmif.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gt2heltkdst.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gt2yeacwjpx.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gt2jjygulnq.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gt2immvcktt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gt2cndoxoki.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gt2bdknmrie.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gt2abrnjlvh.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gt2oqfiuzly.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gt2cxqhtegm.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2xefufptf.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2snagffes.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gt2onneipdr.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gt2sbyihkgi.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gt2quaiplsc.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258888.top/Article/details/gt2gnnmqzsa.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2oeeizncy.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwkkskaq.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gt2kpjylzyy.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gt2ybhclhif.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2gfuuhxej.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxjdqqj.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvubspbd.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2xqzwgrex.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2nesjtrlf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2egzzdkuy.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2fpzbgwlj.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gt2iifyinez.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gt2cxuyojfe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gt2mcuhppme.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntrcsuxq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gt2bpnxadla.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gt2civqixps.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2cpokbfso.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gt2spedasod.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccrpfaui.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gt2yyeciura.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gt2nzkycssn.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gt2himzfjry.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyzynexx.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gt2wmupcjff.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gt2nastgxsc.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2ojvguoyl.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2befgbvze.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gt2ytvrxacb.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gt2ufhlpgfs.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2butypdyk.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2wzazhbkc.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gt2mllnnolj.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gt2hreptfel.html

[T33] Lua：表（数组）
来源：http://dali.zycfv.cn/Article/details/gt2ztqlqbrh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cihzqlsw.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gt2obyrnech.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.kuanghao11.cn/Article/details/gt2qzcghors.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gt2gkjckykm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2hqwflpjy.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmdaxehl.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gt2rzpooukt.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gt2tcvwjuba.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gt2lyunuvex.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gt2xgwovxdc.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gt2igxayuve.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gt2rxrddgjy.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2jenikzxl.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gt2enrqvite.html

setmetatable({}, { __index = base })
来源：http://dali.sweek.top/Article/details/gt2bjqqcnrl.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2vaisxsuj.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gt2szvjivnt.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gt2geyulnfg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gt2ddsgdkdb.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2pfckxzjf.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gt2aanilpot.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gt2axfpnnrt.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fjmtmhws.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2tszqfkhp.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gt2sovlgjyc.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gt2fpntwfzi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gt2fxeavnql.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gt2ohtdsgtq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kittokyj.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gt2ckyyqbpk.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjdppexg.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwxsscio.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2pvudfhyl.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2iizaskrs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gt2laczeixe.html


<!-- 参考信息 -->