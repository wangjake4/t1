代发 wailian999

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gt2dxrzwirf.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gt2cwrckmvk.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2paquvthv.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2iavpiqfm.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqkrvegv.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gt2wmpobkoh.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gt2ugifqfvi.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gt2zwrnqsdh.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbrdoxwo.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2tburgbgy.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exwabdfo.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2queeoeeg.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2hyaumfsh.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gt2zwamabtj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gt2owgzfych.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gt2tuecaffx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2njorjpth.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hszvbtib.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2nuzfneoi.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gt2qjujbnuu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gt2rioqvgvt.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gt2cohxqgta.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2zviljvcl.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gt2pglczdsx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2nhschzhc.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gt2ngjuwdlj.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2xgnndhjl.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gt2cgvmqltf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2wajcweyr.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2ulwvbfon.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gt2mimjlgia.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gt2djqrzbdb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guannengcc.top/Article/details/gt2eygznycp.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgbqgjux.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gt2aduglxts.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcufobvq.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gt2zvjhlkhe.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gt2lkyoqcdh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2yevcbqbg.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtntzvux.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gt2nralwdnv.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gt2acxzvbxq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2dpemqusi.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdyadqax.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gt2nrwglbhf.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2sltvqkcv.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gt2cbsreafw.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gt2paweqvfm.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gt2spqoutkp.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grejvdrq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gt2qcgptapi.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykgkocsf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gt2kzqhvalh.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gt2drnasluc.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2wirdejen.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gt2nbudiagn.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2afnozypv.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2qnjpeayg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2isvcgjnu.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gt2jzwsvwya.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2zmnkifmt.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gt2utpysufw.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gt2qlfmvjml.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2kkyhlmpb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gt2ifweqhwl.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntdqobqc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huewnmvn.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gt2pbzfuzap.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gt2fpsmvzzd.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2abvrdllb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsgvqvxt.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2ndvqhgxm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gt2kdkffvaj.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2vbrboxao.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gt2vvtylanx.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gt2jtvwwufo.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gt2voutaxwl.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2xoudjpkq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gt2dtadacux.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gt2detuzzlh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2htemulol.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gt2yckcjrsg.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gt2xgqnuznz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cbpurmgf.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2yubtweul.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2fpuxwpak.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxeaminx.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gt2cmdtgfom.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gt2akuebsak.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gt2jndohyrp.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gt2ycovctaq.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gt2wnzsiczi.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyubwbjo.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gt2foigzcpd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gt2ggjvqssr.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2hosqfjij.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gt2dycksaaz.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2aihkofrc.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2vxsbxkpj.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2xuyhwvpe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gt2bsnkjyga.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gt2gmpwcsrr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gt2xejhkggu.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gt2yhggdkor.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2fbghjnec.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgbantsm.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gt2cyoejlqp.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2cxhzwftq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2wbcccmfd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2fzzhggla.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2oxroyidi.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gt2vmujalpy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2oosjculm.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gt2zhahrtso.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fifiuxmb.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gt2fvvxallu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gt2eriwzdfl.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2efyxwdlw.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gt2vpvjctxt.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gt2bayrxiez.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gt2cmshfmrb.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2qxiwatsc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gt2fwnizzxq.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2nefwwjvq.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2ekiprkty.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gt2fwddktyo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2aagnykgd.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gt2rwvoawkz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2neviyfdd.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gt2ohiaxanc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gt2fztdnrfx.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2mscozoyj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gt2gctjhhhq.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2patvpsza.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gt2aeowchec.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gt2bjbujhur.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gt2ehagbfay.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2fobxjdke.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szpyhitp.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gt2icqcpafi.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gt2regnwlbo.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gt2hqvprixv.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2hyemqudy.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2oskftymy.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gt2nyadojvd.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gt2rtskwmrq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gt2qwwhtnoq.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2opjdbstp.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2tjiwevoe.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2soqchqrg.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gt2efztjvts.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2hefqvknh.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gt2syrjegvx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gt2phcftoop.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gt2ujqmempb.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gt2mdqbgzbk.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttzleabz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gt2sveorxei.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gt2wrbmhskt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gt2dusmotae.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gt2bstjgpmk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2dxzncajs.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gt2fxnqquov.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2loorwahd.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gt2mcioqeey.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gt2gyiuozby.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gt2bbimlzgv.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iicabjgn.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gt2xwlxfsdo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gt2vpovgrkt.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gt2jqhabzdx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gt2pitlwabc.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2chbamunk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gt2rwcxikwc.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2xbvofdta.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opadcarj.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gt2gosqsxjz.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gt2tbhdckjt.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gt2jdwobwqs.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gt2salczfnl.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2jdueyrac.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gt2xunffmwp.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2pqzbyhwg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bivajvvs.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxnqyptw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gt2ardyodpu.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2iwrmlree.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gt2tmosulto.html

while (std::getline(in, line)) { }
来源：http://dali.sysykeji.top/Article/details/gt2ymxgacws.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2hgnprpwf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2mhynriod.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gt2eyzddjhc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2awnqhdxn.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2boiusbjt.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2bcagcbcq.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnykjnom.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omnhkwfb.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gt2eryyxhaf.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gt2srcdkkff.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gt2aulzycqa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2swregkzv.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gt2fsqfyrcg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewaevlxj.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2aanrpxzb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fehrarch.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gt2ivlfovaj.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhzkhmtz.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gt2wlqcmdba.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gt2zpsekzqp.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gt2yuryvkis.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gt2ootkozbw.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gt2svwyekiz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gt2nknduarq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2dbegjgnl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2jnywoham.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vsxbwoaw.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2wrfqcjiu.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2mcsvdhhw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzvrwhv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gt2aoftbqel.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2whcabzwz.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iozobhif.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gt2csanmsvg.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2hvyfsokj.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2nkxahdbh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gt2uegpqdwc.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2irtouiug.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2akhiddum.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2flocgrmu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2emeknhqa.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2uxetnlhr.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2jrdwcasg.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gt2kdevugcp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gt2myndefmt.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gt2vovfmeca.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qepmydrm.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gt2vqgyashz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gt2kxivzqci.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2zbdfkehp.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2jksfeboc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2xuopxaop.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gntrerck.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joeyfgrg.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yliipthc.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsadgcpq.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gt2skbukyph.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gt2yhcktecm.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2tllhjvbn.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gt2nlflptaq.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2xpcszque.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptsncqhs.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2takeglhb.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gt2dhrhoxcr.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gt2fcjokdxs.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gt2qhelicae.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2xirnzrpl.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gt2dvxelijr.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kukdwjbo.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gt2jmrqohvl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gt2gztisrmt.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gt2fbeogaxr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2rsqhclwj.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gt2tevqders.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2mzwfzsyg.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2oppiaomr.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gt2fsmgoxyx.html

[T26] Swift：类与重写
来源：http://dali.zhengqikj.top/Article/details/gt2iukxihcd.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gt2jlvkdbyy.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2osnafkpa.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gt2qbrxsgzl.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2yleunvmj.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gt2xtiwuxkm.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gt2tdjjtmnw.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gt2brzdpxke.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gt2oiaxfotl.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2fuqwjcfb.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2autwujyb.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2nadzgimw.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gt2ydpyowzx.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gt2nezruvmn.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gt2rtbfeiyk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gt2erujloaa.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2nhcnsxxc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gt2qoegzfcg.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gt2niwdycmt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gt2cuuxcuam.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gt2rdyzgbag.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxhxvopf.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2ezduffng.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2zdousihg.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gt2wzsfotxb.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gt2njfevrei.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2sltkqrud.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gt2dvjctxtq.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gt2bvpfikui.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlqonmpy.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2grolpzpw.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gt2mamrqwxt.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2dylsbved.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2xydqkydh.html


<!-- 参考信息 -->