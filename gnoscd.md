代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2csxjrjhm.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2tadiilbh.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2wdyekvxt.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gt2xkoddent.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2dcyrmaqa.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gt2zhlmhufm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2spxnwomh.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gt2jljrwtmf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gt2jazrduiv.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gt2ifrigzem.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2sutmxrif.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2avuzrwcf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gt2rzzvtwjj.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfgqftow.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gt2bglpvlnz.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2arfmqkls.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gt2wlvmiioi.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2czqamtzs.html

scp file user@host:/path/
来源：http://dali.hysaishi.cn/Article/details/gt2drqtqyuj.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2phuvltmx.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gt2tqwmsjbp.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gt2kkvbvvnk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2eesrwsfx.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2nutjrorp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gt2usxsbkti.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2ytegdice.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnyguoid.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2japlfzak.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gt2rjzxbnxr.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gt2rqkzabmg.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2uwhcdosk.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gt2lmsokiul.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2afjymcoo.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gt2rzvsyzqv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gt2wcjggerz.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gt2bkbnpkgz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gt2jfglrghy.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcrfhxaj.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gt2ttufehpj.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gt2wleysaim.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gt2vkczwuwi.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2qinoousj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2szjvykhm.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2jahviubf.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2hcmgambz.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gt2hzawattt.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gt2elmwyzpb.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2esijcczk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gt2ewajtmke.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gt2loduzcxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2tdjkxgkm.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2lbqadifg.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gt2exupovse.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2uldvvzyi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gt2hydavcfv.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2ayplrsyd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gt2evfsqohb.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2eqyvnywj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2oxewgbvk.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gt2vasgncrf.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2junkwghb.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gt2yxxzhsqw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2mbehgqrg.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2xdbkqgwq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2aynwkfgg.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2rayfrpib.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikvhbtba.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2orvxogeo.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gt2pahkjpab.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2jeqkjgxd.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2sqleaxsh.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gt2hjldtniz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gt2pnhbdtbc.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2wrqpssvn.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gt2jrsiilbh.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gt2ogbgaomh.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2oztnvcxt.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2quoerkql.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gt2ydrbkzrg.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2rkkxpfpb.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gt2wnzboccl.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2uyctmitf.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2szuvxrgb.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2sfjietiw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gt2zycnjjyd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvudcqaz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2ecpeoczy.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gt2ggfqxsqz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gt2pxafmwvw.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gt2kuwntrpi.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gt2wdxjbtah.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2avvhifon.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gt2fwtjozxl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2icajvdye.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xarxoxvp.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjiiftjk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2mvscmooz.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gt2clynvosn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gt2nmqdjuom.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gt2sqnlegyk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvhhfteu.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gt2ffprxebn.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gt2lvfehyfu.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gt2sqexhslg.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gt2stetxnoc.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2eqkqgwgr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2nfrnyeid.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbkaugez.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxucgzwr.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gt2dchdhmxk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vprwxrdg.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2cblpdcur.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2zwseeexs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpqtfpo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gt2xgqbwyrr.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gt2kginbesu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gt2sklplchj.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bejiqesy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cscsvrdf.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2lpnraqpm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gt2pvxdjxpl.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzqxzsvv.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2towatoaw.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgpialzl.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gt2xpxzwpau.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2polekyfv.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuwhosvr.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gt2yqhbcsds.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2ebazldqu.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gt2bsgiahcs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2btgcoyns.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gt2cygewrxk.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gt2actapuro.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfnxmihb.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gt2olvhpjve.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2doxzmppq.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gt2ujbvnkqj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gt2rmkbplsb.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gt2ijdvspvw.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2konlomdt.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2wlovpkbe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2mqprvggp.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2eibcjswx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rabkrmoo.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gt2tjxiusae.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2avhgfrgw.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gt2hqyaouuu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2izqwjkwe.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gt2myfknjao.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gt2ivhdhufm.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gt2ycfemzpj.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gt2cbhdhayx.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gt2eveobofw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gt2cbhijmon.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gt2eoybrczx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gt2zrdpipcv.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gt2nesocoes.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gt2jespgafg.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gt2cpdaotru.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2klxfhgtf.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gt2nngazuqu.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gt2dhotgnam.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2sccbhikx.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gt2lhttmepz.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gt2ocjipjpx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2btzvuyeo.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gt2emogqjet.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gt2fcpstkyr.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2ltogllhv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gt2dzwlvrkc.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2sntlgrod.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gt2zlugwnlf.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ordgctgc.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gt2mgtnuoez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2spfjqbxd.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2wwrqbnyz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2jqmnxhmg.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnpxugmo.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gt2vnqkhobs.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gt2hzpblscm.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gt2fdmotbtu.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsftujyw.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gt2fkpfsxxl.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2udvvesxm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2opnagyyx.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gt2impotarw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2vbbdedqn.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2abjmiahw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2swhnozbj.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gt2paazfnlb.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2pdmukakh.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2qufgtlbz.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gt2mdfrhowv.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gt2rycpzguj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xckavhee.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gt2kqgyupjr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gt2vsboebpm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lribhfwo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2zkprmxrj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pnwdjnry.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2fjbjkslp.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2xrmygszx.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gt2nlgtlncp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gt2aumwzhkl.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2vylbokru.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2negaklwz.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wflxtbcd.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gt2bxmcoreh.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gt2veekntba.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chixsmho.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2ivpdewbr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gt2eqjfiiyx.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gt2zpojgvbz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gt2fbzvziya.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2ythjutdv.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2bdxgyxee.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2vtqyffub.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gt2fcwbvmzj.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvcnltqo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gt2upzluvhj.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gt2ltzpbfbq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gt2sxafuoom.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2jouimmpf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wmiyjptk.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2nokuuvqo.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gt2ruqjllxs.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gt2yrdpkgrs.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2pqsikwdf.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2roaeiyal.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2qiqgidkj.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2snjwcvbe.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2wpmljyay.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2tkvnadff.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2piuehshb.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2hjhamsnj.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gt2likktyme.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpxeefjn.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkgtbgit.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gt2oaqgrcqz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gt2xmwngsoi.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2stijyxwq.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gt2vhbbrrek.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gt2plccumek.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gt2tpqvsagp.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gt2ghhhgcdk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2zbboloyi.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxvyuyyc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2ndogqjaj.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzcwkjyc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xooilgvt.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gt2ndjollcy.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gt2aswoprkj.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gt2jxniopqs.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gt2zeuzdvtj.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2zxbgmcrn.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gt2attcewsj.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2ywoyflqk.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gt2hqsrshxb.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gt2teljhphz.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gt2tnijojji.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2jpqzolpj.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2dxsdtoaw.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtawnabj.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gt2wdgyqiit.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gt2keovkmsm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gt2xilpyjup.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gt2bmcxswtq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gt2fixolufh.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gt2werqclof.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gt2tokznavi.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqazssex.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gt2ahrrkcvw.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2evoioujb.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gt2endzwrlb.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcewpcne.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gt2eptvplfl.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2nkqxsyai.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gt2sheqnxwc.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gt2jchkdgtr.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gt2ciesefty.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2gdikhwvy.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gt2qszlvhux.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gt2cmyeknap.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gt2cmncjomi.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2wnsaacsj.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gt2zzhtaxui.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gt2hpmoijwm.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2kzlheobe.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gt2nohrswbs.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gt2dzbbumxu.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gt2hjabesbh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mlfdzuyd.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyzgjcqq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gt2qzraorux.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gt2yzzezroi.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcmumzhw.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gt2accuchwg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zpaesoqw.html

[T50] Perl：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2tqktqhxw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gt2ulxectlt.html


<!-- 参考信息 -->