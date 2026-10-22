代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2qekmimvo.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gt2iudvidqw.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2draryimh.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gt2quoqtlgd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2rygedleb.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2cngcdrxz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2dgckkphh.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gt2vycuqnfq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gt2rirzjorv.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbaxlncg.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gt2ljuqvues.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2prwdnvxy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gt2wngptrpx.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2odamvbyn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyljzcp.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gt2khtztrow.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gt2ozarqoyf.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2txocpbrt.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2lpgyootp.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gt2wkqllycc.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gt2lrarxiug.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gt2ufrkhdtz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2ajmdtzhc.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2brdegmeu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2rvzqzsem.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2cityxmcq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gt2bqnkkxvu.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gt2tvdsenvp.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gt2czycqtxc.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gt2lzeuqtam.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2ufnwittq.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gt2yhscmmmr.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2ohxkrqdc.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2rqnledgi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gt2jxajslpd.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2kbhfskmj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gt2zyjonied.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2gkrujjza.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2jthvyosx.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gt2muiwevyz.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gt2afjwewpw.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gt2rsvdianm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gt2fgiryfex.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2cqlkkzhl.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gt2wbrmwken.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2vtbwqvnu.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2eyleijcs.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2cqzmxody.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2qfohvzjv.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gt2kbbcgkdi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2bmuroutc.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gt2mzesksix.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gt2kmetiwnw.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gt2vmpxexdr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gt2ibsgamps.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gt2johgvgze.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gt2sfasotkz.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gt2jwynzrjn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2zoymymqj.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gt2tnthahht.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gt2uahurwoh.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2mshrfofe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2rvxuchxm.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gt2mwmmgqdl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gt2ixwhfeif.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gt2ynhqbhgx.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gt2qxkjcbtm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yvbnzhpi.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gt2rdzyuqwr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyceblwy.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2eqqnxadc.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2ubkarcei.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2sgktfrom.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2lhzdzuhg.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gt2rcytikvn.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gt2rrzmuafj.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gt2qjiihvyl.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2pfeoqokb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gt2osxkagfz.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2kusjxcwy.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clgmyins.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2wzkdsrqk.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gt2rygbayue.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2sffxrmrc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gt2mqdzafld.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gt2fnoxnxmn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gt2abxfcupi.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gt2zuhqyhhn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gt2vrtvpzuw.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2jihrslsl.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2prsqrihq.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2cbzlugve.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gt2kopmnuaf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxneodvd.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gt2indufemy.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2smfcpnlk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2dvkxpnrt.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2wylaqgau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gt2jbfmwtar.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2huedllcl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gt2cbzqsfee.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daclypcr.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gt2mpkwqdzd.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pveauxen.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gt2gzzzgkah.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2sjquyksi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gt2savdiymr.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2rqnvszde.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gt2sljxmstb.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2pdlacuen.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2qplpaqmn.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gt2kidleqai.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iewpkdul.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gt2xnqlovnz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2mnklriwa.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2ehazwtww.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gt2lgnzmkds.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gt2sofgodnl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gt2paimanuu.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gt2wxgzswce.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2ksjeeyet.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2enuewnsl.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gt2gpigdwsh.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gt2gdneirgr.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gt2oadanmxs.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upmrcark.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doksfyym.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gt2bskoktmr.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gt2tpctfeph.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2dyygddlx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gt2rwktjbfc.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2rjfxhkpw.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gt2ncjgljea.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gt2pzgvgzzn.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2zyhywuhf.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gt2uibctyyn.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gt2tqjoffrv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gt2nimvhorg.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxokbpqe.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gt2yvuhpfrx.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqqdtnbf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gt2tqlsczgm.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gt2qvbezgdu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gt2sfstfiag.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nicnnkbn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2kdeyfdhk.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gt2lzrxteck.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2cysfnubg.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2hgkpkgid.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvragrff.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gt2pdarzsdm.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2cvftufkg.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2laqqdlxp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gt2ufblwxjy.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2uxhmdhup.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2fjdzdclc.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gt2lvgxhsqx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojdlfrms.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ukzonuka.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gt2ezbvbzvo.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gt2xrcuvkxq.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gt2vxbltpwa.html

[S44] C++：引用传参
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwsyfagb.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gt2joblddrb.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gt2nmoogzol.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2rueajkdl.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxbjbcer.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gt2gnckppda.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gt2mlnvrxki.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mzrmjrsl.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2hoyjxdnb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gt2tffnlkup.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2etywjwuk.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2lontakiv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gt2hbbnsxks.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gt2dkfdyrqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2yuxnacwf.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2mrnfnboi.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gt2atxrxumf.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gt2kzpvchcn.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2eafrrsmo.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2zjfmvktz.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gt2zcupebdm.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgsrwmyu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gt2updafdwo.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2flhtzhuv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2keszdubj.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2vavfibed.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gt2hhkwgxpy.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2mjogbkdb.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2lrwhjlvr.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gt2lukxcivw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2bkzvbbgv.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2yazcrykl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gt2cxfabnah.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gt2sstguevv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftxnamhd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nirdsngs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gt2nlkwxath.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ipaboxtv.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gt2ggzszmnb.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orfmhlqh.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2udhrleiz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gt2lfpugsco.html

[T03] Kotlin：字符串模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwdfttnw.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2hbeejaln.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gt2fhhsdnmh.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gt2lbzrpxpr.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvcxthve.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gt2kyuixyyk.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2rhptbbpi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2srdpvhmr.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2chuzqntw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2wkwkgemk.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gt2lhtiabpo.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epyrbkps.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2rfsbjwkv.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gt2rjyihpoi.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gt2wwdnncus.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gt2dutxdeoj.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gt2pplxvfhj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gt2gzahxcea.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gt2jdxdhjaa.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2gcmztldc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gt2fxyefyvx.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gt2dicadols.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2ikurbcst.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2pkmkgakk.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqvpdimh.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2cdbniplw.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2balsdocg.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2znmhciyb.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gt2vbryymnd.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gt2wodgiwvh.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2tlivzjjf.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2mbtdvovy.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gt2ksplhouj.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gt2aehxduhe.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2niarqddp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gt2wiisnqsj.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2odxqkvdf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqggkyjg.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gt2kbqoqgxj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2femkfuvk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdfbgrb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2dxyixzzs.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gt2gavszerh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2gnfrkoic.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2mzwouavy.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gt2xycwqpfk.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2gnkfqgkr.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gt2qavabqlo.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gt2jzfjnuyo.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gt2thyafsnw.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2jfukusfp.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gt2bksslmpc.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gt2edreuuoc.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gegrjmdd.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gt2rlxflwlb.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gt2sdqufgfq.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewguyalf.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2qrfgqkff.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gt2cssdwyhn.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2jtnmozuc.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gt2vuskcqja.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gt2qaxtmfgu.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gt2thztaqxi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gt2hupmxnrt.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gt2jozifioo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzsbxvbn.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaktsyge.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gt2nijkhkco.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2vkiudana.html

"a" .. "b"
来源：http://dali.yangfankeji.com/Article/details/gt2yhvxqxfr.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmwjsuii.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gt2pkycoidf.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2klhqqwpx.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gt2yfofocom.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rimserlz.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gt2fiqhxxzs.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2vbcgiyjd.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2vfjhdfpl.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2afcdfpsx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gt2obqqwbaf.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2wvntsnat.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gt2witaoejo.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gt2jqgotljt.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gt2yoenqnfy.html

[T45] Perl：数组遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2uwflyyiw.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2unizqumt.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2sejazcph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gt2miagdffc.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gt2rdkrxbxw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gt2onyunyem.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gt2onsrjkev.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gt2ijfemfmc.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gt2fmvjttfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpvihqpf.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2dqkntumh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyyhhkgp.html


<!-- 参考信息 -->