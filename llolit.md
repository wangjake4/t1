代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gt2qaknlebg.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gt2xwmiyyyg.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2wmprvujq.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gt2gykrnpbf.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gt2cokymaij.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2korhhvzl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gt2fnhkkljt.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2umkvksck.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2femjhtky.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lysokxwm.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2qnyxeuzf.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gt2hbfdyvnc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2mzahaotw.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gt2oqdxsnpi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2kurktlts.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gt2yicjpctm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2sutcivar.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gt2envsxjmf.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gt2wxrtspgv.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gt2dyygnmpo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2yzwyyveb.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2dvlzqnnz.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2fargiemv.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcxvejtb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2tarvmrjv.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2sgggkrsw.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2afboklak.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnakdfod.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beoqspob.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gt2hmvstdpv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gt2lpjlchcv.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2ngwowjdx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2ivehckcy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2numhxknz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2fyamwhdx.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2kyerebeq.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uiaiuqju.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gt2dtdjqbjl.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gt2khtdhqbl.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gt2kwwraxrk.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gt2qydezlon.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2oupjyuey.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gt2oisbdqbe.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gt2lchagcxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gt2hxqusmoj.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2blbkrbsu.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gt2beflfhyl.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2rrdauadt.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gt2etynsqnq.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gt2ejiozlme.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2iiunzvop.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gt2jpkzqxlv.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2tuqpwgic.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zamkhobb.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2vchciwdy.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqodbdqw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gt2zgplxouc.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gt2xewuzcnw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2khorvbbt.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2fnnxndpc.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gt2ymwpchcz.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2lzqrqzhh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gt2vzwfdobp.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gt2yseezxti.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gt2sfbmfoxa.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gt2ajjohuuz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2zxikarda.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seigobtd.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gt2junecpkw.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gt2lfyzikmy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gt2acmacqwo.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gt2guepzfyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gt2rurhkqel.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gt2lnhlvlml.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2tqewlnih.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2aaqleblf.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gt2dydozgvc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dnjrljzr.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2qtjohhxq.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhbxcdoz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gt2owoblqfd.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gt2llzmrefr.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gt2ijtsfrwi.html

[S03] C：读入整数
来源：http://dali.shuidangran.top/Article/details/gt2fwloyyxx.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gt2herbffwu.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvhzygar.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2wkseazfa.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2jgecplmi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2blaaikgl.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2hkacklco.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2abvcizbt.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gt2zutftxfx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gt2hjdhvggt.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gt2wzhfpifv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2rojsdasp.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2luffpctm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2kmwbzwgl.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gt2cscvyisb.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2rqwgjrru.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2mtsdcyjl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gt2mxtclplm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2smtxttog.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gt2uexalmfp.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gt2kthnishb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2msweriwx.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2nkmdrbti.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gt2ifdkfima.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgnwsee.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gt2amiuetqb.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2iziwdasy.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gt2zjkicorp.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkhpzruv.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gt2jgiafbqf.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2ncbiijil.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gt2upugwxiy.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gt2ercfkuji.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2dhiaysbu.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gt2aqslnnmm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2exspajtn.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2bajvsqzo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2ikrdpfjg.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gt2raszxuyh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gt2qzljeyok.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2oxkjufpn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gt2wtngwpwn.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmwumene.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gt2ouwipzpd.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gt2tomgrpvi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gt2jmlsychf.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gt2tlxukmxb.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gt2llquosso.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enejevfc.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gt2oekxathr.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gt2tnwenuqk.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2ferwuegj.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2oidyxlgk.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2wqhxqiri.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2dxtevifd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gt2dhhjllcy.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gt2qtkgjmzg.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gt2xcnkbmws.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2yauyucnu.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gt2geurqhhe.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2bnjavajh.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gt2kshjadxn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gt2qafjtcmi.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gt2gaiqmuzi.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gt2latrdubg.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gt2qimzecwv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gt2lmmgblut.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2afvwbjfd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2vomwebzv.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gt2dcfcopul.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2rmztzskh.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gt2izqxpfbl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2dmgzqnce.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gt2rtzpmllu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2wibfsdje.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gt2vqvaqwjn.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2aoifmkhd.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlzgnowl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2usonlkju.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2nfnmkraf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpfaovqd.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gt2xbowizbs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gt2anjgbnbo.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gt2scavhihs.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2kkyntumq.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gt2njlarjla.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gt2wtjldxgz.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gt2kezbhryk.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2wyrvkcaj.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2jknqmzbs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gt2cudrkzeg.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gt2bahqsznv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gt2kzujezec.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gt2nlwtjxtc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2ykfzrbxr.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2spgwvufy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2qzcojnpl.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2rissayis.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejwcotbt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gt2wudufkoz.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtfzmfdy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2jffomdqa.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gt2mmxvvqzw.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gt2jsazcojz.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gt2lgnrnzoq.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2ljcwlaiq.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2vxotxqir.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gt2mirmbzpt.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2bzytiiyh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2jnpbtlhb.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2csikfmzz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2ziagndzx.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gt2nsksonhh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gt2tjasxhwk.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gt2icwinaop.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2doavmbev.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2nbfasxah.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gt2lrbxajrq.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gt2rxokuflu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gt2jpgbaqfv.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gt2wlnuskur.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2hstpctlt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hywlbnhj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2yxljrjkj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmcyjoyo.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gt2fhefjbgc.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2dqzrlgci.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2wbzdswgl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gt2bazirfdm.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gt2fqsesjfq.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2xdhorbep.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gt2twwtqqcu.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytzgjdaw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahuqtoyk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gt2wtkthzdz.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gt2rihjvtim.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2yhunhhun.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gt2zcujpmjh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2jxhmsxrg.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2cdcstoxn.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2msuxlqqg.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2mbjtegiw.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gt2nojejzlj.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qousxbxx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gt2spwkgxgh.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gt2lihpukku.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqxnajkx.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxqcfszy.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2ohvbrqut.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gt2qgoljovf.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gt2yopqxrzc.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gt2ptvofswb.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kipxluhg.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2ekoscelp.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gt2tmexsrep.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2xhqqzlkz.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2foefdzmm.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2xomkbgso.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkccdrgn.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2iwmszdsq.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2hiqvrjpw.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2mwibejge.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gt2jycrtyky.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2kuxbvvcf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxatflvp.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohzflfhd.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjrsiocf.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2kjmvjbfy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gt2ueiimrhv.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gt2dvgroyso.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2bucdmltx.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gt2qilowkaf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2imnlylkw.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gt2pnlyhqqq.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gt2fsvyrtax.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gt2nxswnsgi.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gt2esfmhfgq.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2lzkwfayk.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gt2caqvcavu.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2jefcxhgt.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2vnwxdqeo.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxfafkfz.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gt2tvuclepk.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjubnfsx.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gt2jejqnwqo.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2kfxkhcfr.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ancjmdks.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwgmjjfg.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gt2mfgnpsov.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gt2vwwaekwt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.vqdsnc.cn/Article/details/gt2pkufkjxb.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gt2strzmszx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gt2fkzapzal.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gt2yxodumwv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gt2diusnwcm.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gt2qypzipmm.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gt2uybbusoj.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gt2dxcrcurg.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gt2vdcawscl.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gt2ijfhjhiy.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gt2nounylik.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2tnrxpmuw.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gt2phleaulp.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gt2qjfnudjz.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gt2hjxlpshu.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2dltzobhm.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gt2rawiqbot.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2qhjptptg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gt2jroffoij.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2shcimruk.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gt2zorzyzwf.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2iqssmjpv.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gt2oxnnyufo.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gt2czwcanec.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktzviugi.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2gumchiem.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tian-w.cn/Article/details/gt2lkoaftsi.html


<!-- 参考信息 -->