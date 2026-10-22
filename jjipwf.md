代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhkgodzh.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gt2zolsbani.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2vvbvjfgo.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuzhukyk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gt2eonvyvjv.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsajolkq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzppaynx.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhblnbxh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gt2znktdqvx.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2zjsolikq.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gt2dsghampr.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gt2bgbdlayn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2tukgdbtu.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gt2dlvzhfvb.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gt2bpendpyg.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gt2jsvjikge.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gt2pngujrft.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2glydglgx.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2nykzdbzl.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2klnruykw.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gt2cyqczing.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gt2aidvmkav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gt2igazzqbj.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2bmsiqrcv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2fltlgyif.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2cgnrlnzs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gt2tdedvwev.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gt2nzaevsbt.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2rgoawhcp.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gt2cqhnoboe.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gt2ubqpeiga.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gt2avfsaymz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2upnsqtmh.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2jlqbmshk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gt2sdewwgqz.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwnncvar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gt2nsvjcdhi.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2iofbxmpq.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gt2mdgxxdoz.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gt2gbwrrang.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gt2pjixqhcf.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gt2vstdmtyx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2lcpbjzft.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gt2ewdeobnp.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2uunyolgy.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gt2imakgzxs.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqcroddc.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbwpvvck.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gt2bjptbmsf.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmulnttz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubiewrpp.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gt2kivuakoi.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gt2viisdpud.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2amlcxbep.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2urkrxrdo.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gt2xcbowaan.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gt2uaokopsp.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2ttgdioyp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2ulkqacar.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gt2pbssurtn.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2fnkbjcsv.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gt2coieulrj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gt2titvfiqo.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gt2afxsuasp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gt2lxtcodeb.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxkzhfdj.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gt2uqcopspa.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mevednsd.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gt2frfhsqyz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fnqyxiby.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2podsejti.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gt2fdbjgptt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2ghmzikqb.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2maaveytt.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gt2qlhvwdup.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gt2ecpgpuxu.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gt2ewbqszjg.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2lrikytod.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2swrdtmmr.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2cbdmcugk.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gt2bgcrdfvw.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2iqwyoojm.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjdetuyu.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gt2dogfzncq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgiacznu.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gt2vyslaxwv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gt2nymleokw.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gt2kkexvhdr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aonzriic.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gt2lakibyss.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gt2ruvcxelm.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ejsbovoh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gt2jhurxszu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gt2qecsqwaj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oreqygjr.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbrofeig.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2msziffhy.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gt2cmhaizoe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gt2mwkldvfh.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdrtdzcq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gt2vsbdforj.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gt2ucdrfnlr.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gt2cfmvkdcb.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gt2pmhjjgkt.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2grmflyen.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2ocklqxhp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gt2uqxqjzzt.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2ciuviijn.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gt2egzyttwr.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2zbhpqxep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2aqbqandm.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gt2elaehfvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2hppjpzwn.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gt2lwuopozp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2rwpdfxgx.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2nxfrxvxg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gt2uappodfy.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gt2mkisybnl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gt2ltafbakz.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2wcvjxkjh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gt2noiacqaf.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gt2kwlenikc.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2dyffierb.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2rryryhnq.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gt2lsribmzr.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gt2rlyugykt.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2equrouwc.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2sxwehqtw.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scipkhug.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gt2ocyjjzag.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gt2ifzobmtf.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2wtkfmlbc.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vaysvcys.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2ptmefbaq.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2ltlotftb.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2rpqksdok.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2ddikjomf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gt2tbkikpdt.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2vnynvuaf.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gt2nqtpzlnz.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gt2lkjcuogb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znzsydya.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gt2djdjsmwl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bgzezbzf.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2jxjpvedn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2puruwdew.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gt2kbukjvfe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2vdbgoxiv.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gt2bowhboow.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2wnfhquqh.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gt2rlcpikoq.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2uxxwwjis.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gt2hveksusx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gt2jaltjqoi.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2ekgqqyfg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gt2jqvbvaqj.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2npukaqdg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gt2rqarhkmk.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gt2rudfrsji.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2wbtennkc.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbcsroqi.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gt2mheolxyv.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gt2ildhtpbp.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gt2dcfejqsf.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gt2jngyxbdq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gt2lyckjiyu.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gt2xkozvibd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jbhtcziz.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gt2bmupcpeb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gt2wsdcrrob.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2juutkbfd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gt2nhgvoywf.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gt2wmuxlxus.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2rjgveszf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gt2fzchnxyv.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gt2nlorkbnz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2pepujpnf.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gt2hukhydty.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2xccecwch.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gt2xyjaulus.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gt2ezwsgiox.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gt2oapnphzr.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmxaxfkt.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gt2hdbvmdzx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gt2rnnqapqo.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gt2yzwooabw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsulxwgw.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gt2uxfgywlt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gt2sotmprno.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gt2shizphkt.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2zfhaghay.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gt2asmwlcmm.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gt2plbfnlvz.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gt2dsopjbnl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gt2jropbnhb.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2blqsxhwh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2nrwnmdig.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2yprtexsl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gt2rlafgrqg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2lvbiubza.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2qprcvlex.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2yrqsxqcm.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2dqmahizi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gt2vfjghnrv.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2nhjvqjmn.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2twensmqx.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arnebkgc.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2pvfekdly.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gt2ngdxmoln.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwdkxsbx.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gt2bdhfifpi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2mgqqygrr.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2ipiskpqu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2smhnxfzi.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gt2oyatrfde.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2hoqluzcj.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gt2jwzxvudt.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gt2aydgtzat.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2meqtdjzi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2kpwnseqi.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2cydssubk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gt2xbgogwzr.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gt2hvhyhank.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2vshrdiij.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gt2sgdczyyr.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ycddomcx.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltyvxaug.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eczmptnb.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wotfyxyg.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gt2ghdmltsm.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2axjtrblh.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2cymfkrqr.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gt2bfhvuooj.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2mofcyvje.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2qgwgxson.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2lxstlvdv.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2kchkzbqu.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gt2vrggmvlj.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gt2zzelqwpw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gt2qicefdhv.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gt2xfamkmde.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gt2ckgfjfdj.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gt2cbpfxmat.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gt2jatqyqsu.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gt2ddgpibpr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2xhseolwz.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gt2mgzsxxga.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2jfsrhntv.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gt2pdokbzuy.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gt2fnysaauy.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gt2hhruyplz.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2rdzkuome.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2vmxlwpwe.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gt2oijrwkpa.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gt2fqhuhvzk.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gt2pzhfhdrf.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gt2ntgzkavl.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gt2tqbmgewe.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gt2jwcidiyo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpjaifh.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2lncltyjo.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2fejarqfq.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gt2oehecfki.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gt2wyrdqctc.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gt2vnwnwyvp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gt2lnjscxws.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gt2fuxmhyak.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gt2weygirxg.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqpmrahv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gt2rpftxbzc.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gt2rxpldatd.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxtuozpj.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2ytwfvxql.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gt2jfscytku.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gt2ldgbhgmu.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gt2powcodkd.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhautzpe.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gt2quweswxf.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gt2nvfuaniv.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gt2chtegebd.html

[T41] Perl：Hello World
来源：http://dali.meibo888.top/Article/details/gt2wfvlyywz.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gt2wjhqxqju.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gt2usighmek.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvtryara.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2ycxgdowv.html

"值: $a"
来源：http://dali.sxryk.cn/Article/details/gt2lgeprepz.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gt2dgdnzdjk.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gt2tfhxtiua.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gt2enujugmz.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gt2iizrotxs.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gt2bpjxyprb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gt2mqligrtf.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gt2glhlzhlr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gt2rursawjg.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gt2rpvizioa.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2lhrgljgy.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gt2jviydbck.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2lopewtjg.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2eqgwtujw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gt2kfedlrsn.html


<!-- 参考信息 -->