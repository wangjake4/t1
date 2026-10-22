代发 wailian999

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2ioldrmzo.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilmeqvrr.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gt2pzmjjbbu.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gt2iclgngdx.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2zgemspng.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gt2pcrhcejv.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2dylggelw.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gt2laamgjqt.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gt2azehuirw.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gt2ucjxutsh.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gt2bhovmejb.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhnpgmln.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gt2xpsyzjof.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gt2fcdagfim.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gt2lipwlpel.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gt2qaepatmg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2ydjtsyaq.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gt2jnpdffpr.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cewnhwta.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gt2gavpffdi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gt2goetmmrx.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwbkfhqu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atydpijn.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gt2hbjqhhyf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gt2ylvkrtne.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gt2mrshiwxd.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2jctuclty.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2wkvgrrca.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gt2bmugkzcn.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gt2pefglxjv.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2phaqxrak.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gt2dpftujhh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prbudjem.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2rtxeixzn.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gt2ulhngadb.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gt2yyawuekv.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gt2utmhcody.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gt2vqzlufjy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2ndngkuhk.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvmtsfki.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2tsddxkkp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shnhllmk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2usbiwvtr.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwqgwscz.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gt2qftddwxp.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gt2sxfdwehf.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gt2pdesdidd.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gt2tdsobljs.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gt2viyzypir.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2zcqmsanp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gt2mkirkjij.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2yfnkqshi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gt2rbzolqib.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gt2urvvnfvw.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyqlvmwh.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2uwqigfal.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gt2zcacvbtg.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gt2mnbcafiw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gt2ofwmuwuv.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gt2tywruhro.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skrgjayx.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gt2xlmdnclh.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2zshseaxd.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgdryldg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gt2nacqzfmp.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2vpzilizd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2mpcbqxks.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gt2qajtyfvn.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2angsyabu.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gt2vwdjbrju.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gt2ljtmdkux.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gt2udijwusx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gt2vcyfaibn.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2hleuxkun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gt2nxvwhvff.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydwdsbkv.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2avwncbyb.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gt2eqhbegyl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gt2rvzyngyd.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gt2myigxrht.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gt2dqzpaymr.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oismtewi.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gt2jrhwhoql.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vpojpful.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2blhqixmc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2durbeppe.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxqtsbxh.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2rgfuyrni.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gt2nnmvjhgx.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwvhxubg.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvuuthhb.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gt2ldzpaxea.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2mzaapogt.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvauhqgw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2rjwzmstm.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2zvhgsvpu.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gt2cfdaaxwh.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2jbpgxecf.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2atmjibao.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gt2ojklqksf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2iowwookf.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gt2fyzgtmmr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gt2rhjgiccn.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gt2yfvaunst.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2krcqfdll.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gt2rhxpsvuc.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gt2plmvtjfo.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2jfnghzki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gt2fctdpgeg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2kkwkchuw.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2zqyncota.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2cfdgfzmb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2pyvustdv.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gt2fvvasmar.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gt2dmdblpxn.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2ofmdikud.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2gtnwblnd.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gt2swvhnnrh.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gt2gkcicfwd.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gt2ipgpuema.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2qizcznmo.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ymnsrojt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wigjveyt.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylibwmmu.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gt2ahleigbr.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsszubzo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhohfkzb.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gt2nwfwlveb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2hrwcqutp.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufbhgnwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gt2tcccvltw.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gt2ynfhqcvr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gt2dfkwzmiy.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2emyzygdh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gt2iicjxcjx.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2lfdvdfbs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gt2urltzogu.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2lelmdpai.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gt2cdppibek.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2ynjqguic.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gt2nhqrxpgb.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gt2naewoanf.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqjpsiau.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gt2ffdtovho.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2nxavnwrt.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gt2oxgjrvvw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gt2smyhmoim.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gt2palklayz.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2ijpidtid.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2nkdtohdm.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gt2dghpxhgq.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdmxxjus.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gt2molzpisp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gt2vzpylizi.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2goytgtds.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxynrysu.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gt2iwghepnv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2goviyztw.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2eeahnowp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gt2ywroxruc.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gt2vnphhvwp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2jtzrbcuu.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gt2pnxarbxa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjhycjrl.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gt2ctinimpq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyxqtwvf.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2emdeuzff.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2ofowkhwg.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2rovvuemj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opoluvmt.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gt2ndyxxkth.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gt2aixwvffw.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2phvtptel.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gt2wxfjesar.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2eilshwyx.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2nwrfxzky.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gt2mtenmyul.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gt2rpoqfrfe.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gt2xfmqdggo.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gt2dknrapum.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2goljslyj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gt2opknseby.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gt2ubnaeteb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gt2xonbyjmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2mlhnifra.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2byjmhbjs.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ddzrzbdr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gt2ifmundkz.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2toahrlrd.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2cceljlyq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gt2ipbglyin.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2pibmwuhb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2wnyssikx.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2axxijqrv.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gt2mgywzvfi.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2omawoclh.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2chokivxk.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gt2yfhzjafi.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gt2cawsbzfh.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gt2vwfudaca.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gt2nckkbarb.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2instamvp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2jthirhfe.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gt2bvxpeorb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gt2frndcmie.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gt2juypzjce.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pubvujfd.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gt2xkebdiom.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gt2mxfuwxwp.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gt2tqjmlkuk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gt2kejvgzir.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2obzzilpp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2hzazefql.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yuwyqnjc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2hlkrugpu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2yyvebmhj.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2snqvrmcq.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emqxfjbx.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gt2woytmaos.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2jlwfncxb.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2omvfjake.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2xrkbrvye.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2etlhfeav.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycfjvnec.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2zdhjurvb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gt2ngpwxwfk.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2nblomtvi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2eecjyxer.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2sqlpkcyk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofhmnvoa.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2vnhynjel.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2zhbmfeyb.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gt2cdgcliru.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gt2bjeyojxn.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gt2cnkoamun.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbqovwaz.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gt2vrmfyxjv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gt2fucomfqt.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gt2tecjxflv.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2kpiyowpg.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2iwjzhdcs.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gt2qngvhutd.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gt2thgbwiul.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gt2mwezuorp.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfghzdha.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2kzrjvwwq.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ligspowp.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gt2vkopriui.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gt2xchbtnip.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gt2zihicxif.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2gxzasfze.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gt2nfdyttfv.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2tbndrnnf.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gt2nsmyavnh.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gt2rwxsgrft.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gt2zdzagfxf.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gt2luvtwxsw.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2kqbavrmw.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2jsvhzpbw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2fzldbcez.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gt2ehnugqqu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gt2rmcrzzwg.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oziuchmw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2wzpcssdu.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2emdsukef.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gt2fhpchrde.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gt2hxibjqki.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gt2wqdchbic.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gt2bdnjkmoy.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gt2xeizlutg.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2visogzif.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gt2wdtsulry.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gt2tpellluo.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gt2qzlxypxl.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gt2aalorebj.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2diftvoyp.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezmqzotn.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2ftgojfgo.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2gpnfdlrg.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gt2khozoxhx.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gt2oaizqhsn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2ubmqxdjw.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwajkrzl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gt2rckhiksb.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gt2fsqvuukq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2gswveoee.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gt2csqcnwpt.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gt2mrbfwvxm.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmkidzgl.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gt2mrvndmxq.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gt2orjdwtbv.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gt2lrudmpfl.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2gatrjgzk.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gt2uwnxqsvj.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gt2plqrpdro.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gt2xzvhvvcn.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gt2ynlfjipq.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gt2ccvhutiv.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gt2vfqvjxal.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2yvwsfoza.html


<!-- 参考信息 -->