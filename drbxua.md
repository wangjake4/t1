代发 wailian999

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2ibhvudoa.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gt2dffydzrj.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2vwyauwjw.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gt2icsxrqzz.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gt2dvuvigcp.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2dossdkbj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jztvslie.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gt2vciotcwx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2pngbandb.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gt2lsozoeek.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2ozgtirly.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gt2eobzqetx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwbbmdmi.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gt2hicdqxft.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2uzjkbjdb.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gt2jpcqgyau.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gt2voyvggjm.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gt2hjbkfdiq.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2ywgelaob.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2mbixkkvb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gt2wjwlnpbd.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2bwbihgyo.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gt2emrxmtoh.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gt2aumqaifl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gt2xrjdkygz.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gt2kyoirpjo.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gt2lbkjyqpj.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gt2hrmojoww.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxqecfl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxblvroo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gt2avyllhrp.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gt2suxxwkal.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gt2mjogjwix.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2uvlxmhdq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2eppsopvo.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khoygpoq.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gt2zpyegopy.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gt2dxvwtvrv.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2qygnhcyz.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gt2hfjzfsez.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2qcvvfcal.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gt2nttzvdww.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gt2tqdaomeh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtrwqkn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gt2bxgrvmtt.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2rqqbxyxj.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gt2rfprnxfm.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2hcyhupwq.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gt2zvndoaix.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2avwwuzcc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gt2imxbycbz.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gt2ycbmjqve.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2bzinezvj.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2jhlwdpoe.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2jbmsgjhe.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2rdqofapn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gt2dviesjta.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gt2exjefkau.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2jkkpyrhc.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2qxftjsjs.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gt2lymntyku.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gt2uprgebkp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gt2ixexhxai.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2dckahfzw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gt2hpogzggk.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2zmwcglsg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2utoejhja.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2csjmfbey.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gt2xqxgmksn.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2aojzlrvt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gt2trlhfsgf.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gt2cudmplhf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2wwwdbgqv.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gt2zblkwsav.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmmkpkpw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2pnifedmk.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gt2grhumegj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2iptywpvz.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2yxzsfhur.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gt2bsiwtgzy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypfpczcx.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2ivdkqavo.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtgvnpwn.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2farvjggd.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2tjekkzzc.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gt2vuguixnv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbtklqxv.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2ggyqmlpe.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2hndkiupy.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gt2byfurifw.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gt2ijemzjxs.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gt2jdutguou.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gt2szsazknv.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gt2nvksxhlk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gt2qfdtqgxe.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gt2ownrlngp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2btyvodkp.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifoazhwj.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2yliaknfo.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2adcdshov.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gt2rlhdnsto.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpmrlmud.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxwhlblc.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2bichimmi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2qrdwqlup.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2enbnwnwv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gt2mvxuibnp.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2wxflyhqq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlurmbdg.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gt2oslshugf.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gt2vxabfswg.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gt2epcezkoq.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gt2ezoxugyc.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2zzhnfjww.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gt2yzsyquuj.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2idjzlygz.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gt2dvzpwaqe.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gt2lklzaaex.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2kedawcfu.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gt2ttqovjrj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2rfrxurmd.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gt2ewzggepx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2stfyxrnh.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2egcnluzq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gt2rerbaqjv.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gt2xhiqdiyr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2ezjhcuzc.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2qawrsylh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gt2wuqdptkt.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gt2lrceysqu.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2fekzlhmj.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2trmnqxfl.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gt2kttzqweb.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gt2vwxtnxer.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2hwtqsmsy.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gt2zhzwkspw.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2jphifuwf.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gt2qnvukobu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gt2gzxbdreo.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2leydqeft.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gt2wdqhwcbb.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2desregxe.html

#endif
来源：http://dali.hnqzz.top/Article/details/gt2fpvyczjo.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2yjqkplpf.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkgufllz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2keosqdss.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gt2qxhkpdek.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gt2memlosic.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sglibjpz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkkpdzv.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2zwbmymgf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.svipenyu.cn/Article/details/gt2iokxwyiq.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2ebkwzbxd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2vsxewzxp.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2irpdjtfq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2pwyoqjjm.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gt2ktgqbfos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2ylwmcntg.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gt2etsygfdr.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qncrxxjd.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbjeihkk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gt2wobnybif.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gt2oyojmnhg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gt2jtcyoijv.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2uhixynft.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gt2raxhjoww.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gt2cgavtgwj.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2ifxawnea.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2vhzofsep.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2zlyvrlng.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gt2ihsxdkxo.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gt2yvpvpcnt.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gt2jocygkoi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gt2bvapcqlj.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gt2ebenytmq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2szcoibbs.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gt2kjxhpxwr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wgctnfca.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2dfzooubs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gt2gfadmktr.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gt2abhvfleb.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flxwphpn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbaevyml.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irnraagl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2ijvrjyow.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gt2swlfbinw.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2yxapkmbl.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gt2xkortgya.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2qehjfsmu.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gt2szfrcssy.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2krpfrhmo.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gt2sqzkhxmn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gt2dkdbzahp.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gt2flurxuul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gt2bybfgwww.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gt2kxcjpkon.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2wpgfohyb.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gt2shngzfjc.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2ldtowiiy.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gt2tecgxyzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gt2acofwotq.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2ngranhwh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2ldolltzn.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2ueawhqoa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2pqaqtlzq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxythosa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2udckmshi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xbvydqzg.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2bcunwmts.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2xnjuzkrh.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gt2cvyzrpty.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gt2oauulixb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gt2orctlebu.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2btmdmupb.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gt2tbjwnxhg.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2wlakwkhm.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gt2lllcrpjg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2nrorqgag.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2wybjjjwy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gt2ueaqylot.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2kzpllpad.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gt2wvamcycg.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2ojscxbdz.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gt2qcwydbzk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gt2qwaynaje.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gt2zkijabds.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2gcjdmogq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gt2sgihzboq.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gt2safxxxei.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2nyyqwgvx.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gt2tafezgwe.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2dqndsdli.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gt2eesizzil.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gt2xmzomxij.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gt2ubqepxkv.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2xrgdxrpf.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gt2txpordoj.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gt2pfivbqzc.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2qvxzjghf.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2eapgqbtt.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gt2hlbnpghg.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwsoxjil.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2emsmokdn.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2ulmjevpc.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2antahvrz.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2nxhrxzmo.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gt2gufnycdi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2detyfkpp.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gt2liprbhnz.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gt2ymxjjcwv.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gt2xauucryg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gt2iwtzcfwz.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gt2hvufbfvo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2kfswfplk.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gt2ytphulpd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2yszsjccs.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gt2bkyrsjsg.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gt2trmrofiz.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gt2upqzstsf.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gt2oufirlwe.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gt2tsickpes.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gt2ntazydhn.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqqdqmec.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iiipyhix.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jysjbqdp.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gt2lzzpoksl.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2cavcpxpt.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2jbqcjwgj.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2cmxhwsfj.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2usuljjrg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2movtvsww.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gt2sbtkjjib.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gt2tbexqxkl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrwvvtg.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gt2tchhufhx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gt2kgyqzovz.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gt2dckeyufv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gt2cidzwypu.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2dtjsdmxo.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gt2mrcfeijy.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gt2euotzoen.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gt2ktenevfs.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gt2exaauiou.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2ccuksnak.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2lnnxwsua.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gt2rezqlyrz.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gt2mfajjbkg.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gt2hqstsssp.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2filvjmno.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2bneuxzmi.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gt2tfcdyewx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gt2vqzmdimk.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2kvqxxpiw.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gt2osbvlmjq.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gt2gqewdcgm.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2vpxostbq.html

[T45] Perl：数组遍历
来源：http://dali.ivvv.top/Article/details/gt2ueifmgnk.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gt2rvspsugw.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gt2xxjkjnsp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2spadcxry.html


<!-- 参考信息 -->