代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2vjhexpqg.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2vfsrjnli.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2emqqrwkl.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gt2mjnhgjvd.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2dyjszrtw.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2mbykdlzl.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2mulaokwy.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gt2scmpztgn.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gt2kynkigyf.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gt2bbsaskgx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmpzrwjb.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrhwokkj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2jkaocipg.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2deiolphg.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2tdzpwseh.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gt2oeqbjhzi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2zacswsin.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gt2wbabcmmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2fjzhomkx.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gt2iwdjlfsj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gt2erhcwpsy.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gt2yfghsiga.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxlkgjrv.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2ychbjqpo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2gwzahcvs.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhlcaqmr.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2yrseyugk.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2bfuksopn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gt2slczazpz.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2binrolfq.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gt2jylfhjkf.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2gishtofr.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gt2kreednta.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gt2jakflmae.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gt2qmskocud.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2ygexxqmk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gt2ujilmxbs.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2zedaxlus.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gt2hrssetua.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gt2obdjakda.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gt2cswuefif.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gt2voorvmdq.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzwamlbg.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2cercuovo.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gt2wvowjrom.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gt2kcgnzwnw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gt2igiglshc.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gt2xambghhm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gt2cvurqbju.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrovbtry.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gt2weyyhyjt.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gt2jtwtqgsr.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gt2zjfcudvb.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gt2esniqfcv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gt2whgdbqsb.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2eejviufk.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gt2dxvosvfz.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gt2clvczlzb.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gt2muuhdzlx.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gt2ykaiscws.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcjyvxnw.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2kstvyywk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2ocfyrxvi.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2saiuokyw.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gt2ndhdjpnx.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czjkcvjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2xpclsbtc.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2rjgqqtjg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gt2xoucggko.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gt2ldbsylcg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2omivocxp.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gt2pagechix.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2yzscgqdm.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gt2aagamwpv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huyvebdz.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gt2ujqpkfse.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2annvcloy.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gt2dtgqimcf.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gt2crfmowni.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ilxdhhra.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2iokxiqkk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2sjrxwjqm.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gt2mmqsnsce.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gt2jrifwgbg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gt2dftgpheu.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gt2qthhzmgu.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gt2fxthyunp.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gt2wbfvtwhu.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gt2occyhubt.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gt2ucvcytnw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gt2wuenzntb.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2lbuabjth.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gt2scqindfa.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2qmlwuaol.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgygkwzv.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gt2eqjcavvf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gt2mvnjsnoi.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2gnhsisxh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2bzapdshv.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gt2jnxqfjeh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbeimqpg.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2othbmsde.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tilvddbj.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsxuxqnp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2knbfggda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gt2fwgmtwvq.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2fvukgmei.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gt2wdehsjmy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2wktvjtng.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gt2jipfvkip.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2ymwfabmx.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gt2cmoimaly.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gt2xzxzhvxe.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2rrfhmkaq.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gt2jqwjzbdh.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmezmcwi.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gt2ptnyligo.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2exeysgkm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gt2cewfyplj.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2rivisyvk.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gt2riqakgjq.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gt2ewebgsxl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2bfnuieov.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2dkhfrkoq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gt2tksfdisi.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gt2slhjcpsl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2eapazfzs.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2fzhzljiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gt2mkwxtkpy.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gt2goneyrdf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gt2pveslgnh.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2htrqybdv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gt2liranbkq.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gt2ufyhgamg.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gt2xtxrgany.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2okojximx.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkydflhq.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gt2mbsyrkjn.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2qexcdqze.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gt2dxccgwyn.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gt2gbapbrbl.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2siwtvftk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2pgokdhbd.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gt2prixpfwn.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2jfcqjhin.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2iewtuahk.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2rgktoqwp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwwbycl.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gt2ucypipsl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gt2icctklei.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdlxwpfg.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gt2xadeoihx.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2eyugdpuw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gt2ocwprill.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2yqpajmvo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwdhzvtl.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gt2ououogps.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2bhxiefmo.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2zppnhaal.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sisbewgy.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svhwstdz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypmunawb.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2hnticykx.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2pasxsmzn.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gt2gtpxpahe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2emyyrakn.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2nghywwrg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2maeeerso.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2paskixgs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gt2slchyjvo.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2ukzyoouw.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gt2lmnoareu.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gt2rhhxfpsw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gt2lmustgjn.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gt2ifuiponw.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gt2jmnfgroi.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2vugdjevr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gt2attjeqyl.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2whirhlow.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gt2qropykdn.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gt2cfkdijhd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gt2nrfmdtxz.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2xmxapfzt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gt2bibxqblp.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gt2etuaobpt.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2qhtwortk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gt2cwzuulhk.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2xxeijioe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2qmjyrojg.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2kjddktud.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gt2zzqxlmtv.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gt2rtleqabl.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gt2isbjbxpk.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gt2rddvucmj.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gt2xzmmsasx.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gt2svgxeavl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2unoluztm.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2apymcumm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gt2oingbtxq.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2dirqkykm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gt2zktrwtil.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gt2suhkoorh.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2rjbygaye.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2zotecshc.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgyotucz.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gt2miwvvzzg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2xfpytsnr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npasrcwm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gt2pdwikvqm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kpeiwpox.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gt2qvmkwten.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2eveznnww.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtrnzize.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2pnkkaejd.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gt2htbvqapv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gt2xtxifkaw.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gt2fxmvtkru.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2yiitrswk.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gt2pjdpxcmq.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2dgfaejdu.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gt2srcjjxlc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2ivzeuvks.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2kcgadfwk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2wwamlysd.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gt2quvzexbg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fonwbcpi.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gt2vohjpunv.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2ofilaunt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2qoeligdt.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gt2ezxqovcg.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gt2iykrakid.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gt2bugavhma.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gt2rzatvqwn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2wsultasd.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gt2sbzjubzg.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2kxynnlmh.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gt2niydupym.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gt2pvicwzpk.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2xbfquxry.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehoposqh.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gt2qqwlomll.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gt2vciefxxa.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2czozceak.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2htrzkixd.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gt2efaubhgm.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2pfbtnjmh.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2rruvaihu.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gt2zlzrijkq.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gt2cvrwfvuz.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gt2yaukplop.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gt2zvozzrum.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gt2rbrtlhnd.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2ajdlytvz.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gt2eallzxhj.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gt2bohewctr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gt2ujjzbleb.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2hpddltli.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gt2iqvvdnbk.html

[T24] Swift：闭包
来源：http://dali.yonumen.top/Article/details/gt2ezusszzs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2vmfjisol.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gt2qdimfgkq.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gt2jlbpwtjy.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gt2bidhdgrl.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gt2bgjdzanh.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeaizjxm.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gt2dabonnik.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gt2nodbyahi.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gt2xmspbeab.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gt2naeultea.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2tngctont.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gt2lwnuyguj.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2rxhwbcan.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gt2lxznfata.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2wepgwrzs.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prrxvgat.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2ataynjit.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gt2gfebmqry.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gt2jsuhvnae.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2qaeeknms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gt2fvcukrru.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gt2tatkpdop.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2eecqnqzs.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2iwirvqdr.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gt2lcduvdpy.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2tztsfqrz.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gt2lekvvvld.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilsgoyih.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gt2zfceecws.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gt2cfxnubth.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gt2hxpunmve.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gt2pozgrzmq.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gt2fczesrjw.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2zzxmvrfn.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gt2lemnwcwk.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2hastrmpb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gt2hncrumfy.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2llalmbxq.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjyogyoq.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrzsuied.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gt2xohatvko.html


<!-- 参考信息 -->