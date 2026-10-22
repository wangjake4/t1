代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2eetuqlhl.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gt2fdzpcwip.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2jhcqqbif.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2cyvejedq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2yimtvulx.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gt2atslzsbe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2zesfzhlq.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gt2wvoptcrm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gt2almodiqc.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gt2tqpghqmt.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2twztqibj.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfvpoezc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2mabnrnyu.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2xotocpxs.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2ffhioixo.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gt2xiamyyaq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gt2ybaycoug.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2muxphgci.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gt2htcpfdoz.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gt2lacrxeoo.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gt2tqanyvwt.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2odfyzdzj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqhsygzv.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2ylhadvzn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gt2gsamcxcp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffdntfdi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gt2irxyxhxs.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gt2zccinndw.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gt2wxhpjxef.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gt2icwaygee.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2lolrabkp.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gt2pgnnfofp.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2ydzisobo.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gt2ivotkpow.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csqngxue.html

[R65] 查看端口占用
来源：http://dali.fengsongda.top/Article/details/gt2pwuygzte.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gt2wuuuuugi.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2rcnewehl.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gt2gckojowt.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gt2dwfqxpec.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gt2liuwtvll.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2evyhsgsw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gt2jxpnuswx.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2ailakhvw.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2qugooieb.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2merphnrg.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gt2vunrszkg.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmuxbiwy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gt2qlggwhck.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqamryik.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2mpkhksew.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gt2ihmxiups.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gt2ivnyhhev.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gt2uamzrbag.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2usuzizqf.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2gwjetqcl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gt2gqwgdwrp.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gt2noxhaihn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2qsyhbwum.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfvvizfw.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2rsjukann.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gt2tmqqflkq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmnziohg.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gt2lnurgidr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gt2yoyiectv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gt2odoejjvx.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gt2cavadhan.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2imbwkuld.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfhfztmi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmabinop.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2hubjwgpd.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gt2vjfupvai.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gt2rpooouhh.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gt2qjwrejgq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gt2yrzviywu.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gt2yrzgjxxf.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gt2jqepejok.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gt2iathhrin.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gt2fkjhrawm.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2iigojwep.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2dhdgvitm.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gt2hdsgobzw.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gt2mtyebxtm.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gt2onjgnxke.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gt2kbkborrp.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2xztbdgqq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gt2iblddpch.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gt2fkhkcoyi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gt2nxuvcbqk.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2pxiqdtgp.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2osbyvvvd.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqolegut.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gt2vryysxom.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2womsjayk.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkapgvxu.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gt2hnciplnl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytqwaqmy.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gt2rdhvgjgo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2xvysamqe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kmelruty.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gt2jtnwjyfu.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gt2joxnsakd.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gt2fbrixtsa.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gt2qogimzur.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gt2dmpwtexg.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2gikkcbui.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gt2toyphqws.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2pxyslbwa.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2tpgfxbaz.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gt2bbcnaonx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2wpurwozr.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gt2dasgbejb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2ledhlszk.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhnbadxk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykevlicr.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khysfkyp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gt2pzzeaqey.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gt2nhxofslk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gt2ounhgtel.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gt2bsmxowlx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2wbrxobeh.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2rvevfvhi.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2xwiiftal.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gt2fwztfvhm.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2lpopmgdx.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2zdcdlzwz.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2liysekel.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gt2hmrvrniw.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gt2yikgvgyb.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2vzyhktck.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2vrorhgyh.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gt2urcgnceh.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2cpodnoma.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2lxkfuyxw.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2tvueyvno.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2muwyskfs.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2meiqzyft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gt2uilbtbzg.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gt2htjyvvac.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2qokuffwc.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gt2gadqjytt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gt2dfjerien.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2bgweqkzo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gt2smqxgffa.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gt2hiebxjbg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2hbgfymsi.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gt2ymbsiasp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2vvddioxv.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gt2gaqegrgg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gt2trvhllzg.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gt2abnwiosx.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2lgxdjjgw.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2musqcyow.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2osoyicvr.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilpqgqiy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2lrdjozze.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2fkjokvwp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gt2iwggvmuy.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gt2trsntted.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gt2rypczosg.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2etyactms.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gt2omaqtuon.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tznjqrwr.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gt2tiyljdly.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gt2fnnvnoaw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tboahkrt.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gt2uoveakhe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2pndbmtkk.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2bzojwzjd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2ocwjntac.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2gribjgne.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gt2kovvnhse.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gt2pqnnhsar.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2iiteocbl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gt2iwyycfgf.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gt2qsvglwln.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2ubfudfwn.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2caxgumtw.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2ncanrdlo.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gt2eilronqo.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gt2yafapinv.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gt2vveisxuc.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gt2zhmonixi.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2pscbnrgy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gt2hyhmzztb.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gt2yavvwjum.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzobstbg.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gt2yrotjemt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gt2iplmojoi.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2cjgkbhmx.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2eqawgsny.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2wbepgkut.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gt2bwmynatc.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2hluezkpg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gt2ngagygxm.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2xsgxwimu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2bqtctdth.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2yqetlegx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2gmwicixh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2cxhsowjs.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onsnvvet.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2bugzcyrs.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxanmghv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gt2jozhemsq.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2xtfvixgf.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gt2hagpxriy.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gt2whyahrxz.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gt2zeucxums.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gt2qgjegqcn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gt2okjgmwcq.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwqjehzc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2ucqhipkl.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2eyrjlxuj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkffbcqb.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gt2ckvhhqzj.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2fzyqpbuf.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcuniqqw.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gt2nkgzassz.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gt2pccqkqov.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gt2bjpugbgn.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyciwfce.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gt2tjxmcdbd.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2qezhpiaw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjcupoij.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwkqlbek.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gt2nhdyvqdn.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gt2uobatize.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzdrjjaj.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wojkxcqw.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2edhnlhnl.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2fiwlkkbs.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gt2rwlgfnpa.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gt2phhsoxmb.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2alcvbczi.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2hdjhkkov.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gt2ienndfoe.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gt2bizflvzo.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhqdnpiu.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zquuvfam.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gt2lyvoftwn.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gt2docmkaus.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gt2wgwulzrr.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gt2pazsgqom.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gt2kvsscazn.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gt2fsuqgjtt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gt2fzuirpsr.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gt2ikxfbrwv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcvqtzfl.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gt2beqnscwp.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gt2fmmqrqud.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gt2zapnpbsw.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gt2zbtqpxms.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2sgcnzjxy.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gt2athmljgl.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2suenyxnh.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gt2cmplqprk.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gt2xowstamn.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gt2cumrnuwk.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gt2dpetcsqv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwfogcq.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2iwrzrsae.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2zlhgeeyz.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gt2zermyznu.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gt2vmxxfoqf.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gt2nvnfkzvo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2ykomalrz.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gt2wjpghmcl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2gbiasuxo.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gt2qjnojjgr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2wukyxmhp.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gt2whbixlwb.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdnwtdzu.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2lzjrmhxa.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gt2xfphytlj.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gt2rvkxrzmr.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gt2fctkfhik.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gt2crqrevkr.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gt2kvlqffzi.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gt2ewvurzfq.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gt2uphuphti.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyaqcjae.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gt2uabklego.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gt2gwcdozim.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2xuxigirh.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2ttyjcwwb.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gt2mtczjahg.html

[T44] Perl：条件
来源：http://dali.dianchejie.cn/Article/details/gt2pygvmyey.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eudwmgmb.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gt2iiaqugxu.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gt2lshgfwdh.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gt2jwixczxk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gt2tgjgxdxn.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gt2ufyubfcz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gt2ulkpzwtn.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gt2oibzwjxl.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2jlmftshv.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gt2jiozhbka.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2lonpemtl.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2jpyayhcl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfffwobw.html


<!-- 参考信息 -->