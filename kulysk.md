代发 wailian999

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtrapdhgxv.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtgarzcune.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtzmnmctjp.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gtdfgmpklr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtpdxhevyq.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtpqqipxtx.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtzdibzwag.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtkgigzwxz.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtydghfjns.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtoyemyujz.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtbrwzhrqo.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtembhzxro.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtjdpmsnmv.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtoarseckd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gttxlwwarf.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtesmgnwmm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtswhphnwg.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtoxeciapr.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtuwfltmif.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtvyzrvnhr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtwguqlunh.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gtmjtlvbvf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtatjsfrna.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtmsxszdur.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtmxlygvuj.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gtmluhvgkt.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtoukesxav.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtilcrbktk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtwxxlhino.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtvbqoosba.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtcumripiy.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtojbffuja.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gtzdhvxtch.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtkjckubxp.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtpayazzay.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtsrcpqcxd.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtvxnuqxkj.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtgqwbvner.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gthnpebqyf.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtaufqjcjh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtbgxxgryl.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtncerdovn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gthlinfkqw.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtbudvlgkg.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtsyszfhcr.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtnqugkzne.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gthsvjtocf.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtmbrresoa.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtazibnszn.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtycqjmcth.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtcpvoplrh.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtrgrhfera.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtqjstknzy.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtigypqfbu.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtywozddcx.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtbwllacmb.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gthxxqirmo.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gtsqsosvqc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gtimbvscis.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtcmoaeomb.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtgzztwpsb.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtodxprcku.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtoyqfkvqw.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtmdergfno.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvjcmowx.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtyhmpwcmz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtgcutfete.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtdrfwmhzq.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtgdjlvblb.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtucjhophe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtdmfzvujq.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtvdcyeqxm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtefextlqq.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtflrolhnb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtvutxfitq.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtlqcvvver.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtpyskthfo.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtymsyttkt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtuyxotptx.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtwjtnaksm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtpmqnzaet.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtlysvlkju.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtqswigwnv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbjmwcyof.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gttaxoqnyy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsfxjjxk.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtptxnvdtr.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtyazsefxu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtuyjrlepk.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtfgvhgrtz.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtajepiddl.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtszbhehjb.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtjnffdznb.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtwngesvcg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtibumosjx.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtvsunvrro.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gttxcsxhpn.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtocczzfln.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtkmyhgehj.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtemalbsvn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtrhljhdpr.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtagnecgqa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gthekhntrc.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtcuqbtnzd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtbcxsxtjy.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtqafsprkm.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtbexwfuoz.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtmyijnjrs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gtpoahcbde.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtlksxfvfj.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtctwpywow.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtoklqnknc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtihvrfkiv.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtukczatiu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtsjadlapw.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gtfmtzablh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtsvzbfrey.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtrbbbdisw.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtshtlzghy.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gttzjawxab.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtvvmkxaun.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtivnpbiff.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtvdqsthec.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtbzpkygdr.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtqikukmch.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtwjmanfyl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtlystsrwm.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtchhbzytr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtzgvqhunv.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtxpjleuqz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtgtrklocp.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtphobtmof.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtvhggzlay.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtevlrmnmy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtxmtwgdth.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gtiwqickkz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtnftvmywc.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtlllembgv.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtiuxexvch.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtxholotfd.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gttcvcnngj.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtvdjlsmqe.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gterfnoswj.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gtoxjglvry.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gtqghabdls.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtnqcztixi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtkscgwawb.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtkkkedrzb.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxhjfxqz.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtvujwjlfh.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtqcvlzqxj.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gttrdfetwz.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gtzfhelwix.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtwiebdufe.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtelcoepet.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtmiooemyf.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtflxjsxxy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtrpkawuks.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gttjtnlowf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjxptejqe.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtxkrmwszt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtymmnqson.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gthaovilhk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtpyioomkd.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufjenbrq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtamzlizyp.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtcqtiaqvb.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtjeqqoeik.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gtizqkimdr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gttrptdbqg.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gthmmopyiz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtfqycjyfr.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtiursalri.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gtkndbgmoe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtvkiiyztf.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtopoehtzy.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtaltjnxdk.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtnsrqolvd.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmhwagam.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtyrovtxwc.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtiqlphnje.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtkrryacoz.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtpwliyveg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtvbzydjyh.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gttgvitaad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtazwnhkoi.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtszzkzttd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtsxyhqeuo.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gteokjvuti.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtydgcrggx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtequpkjfs.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtxhsudjwx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtvootwnnk.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtooctwqfc.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtwviuoevw.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtlogjbryz.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvwfvgolp.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtpzstrdgq.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtfyupytyh.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gthwuebexy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiaxkvvs.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtpczmatai.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtethamqga.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtfclzmyfk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcloxlfkp.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtoaqgduhz.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdxbdcxk.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtpxhqtnpr.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gteorbyyaz.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtgbxahqzq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtpyehlwof.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtkqcgzzvf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaunwmuke.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtunawczvw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtdezooifk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcdgogbap.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtwpccdqmm.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtztrckknc.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtrabkrsiw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojjsdalr.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtdorhruca.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtuufhmoct.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gthicjnfuz.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gtaeiklfdl.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtmpguranm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtbrpqzdbj.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtghwygxey.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtppnzllew.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtxmmrmgml.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtbgaohmnl.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtwjqjffdh.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtnxdnuizs.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtqlmgyfdd.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gttlyxotcd.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmihqbcgv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtwaoxnlkm.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gtzlaoterz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtyysvloqn.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtiovaxtxu.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtyscpcmtk.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtsfeznrcc.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtdcyutcya.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtedrlcdxi.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtjmukuleb.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtwzxqpkpb.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtrcesqamo.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtjordvqve.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtgpdyaetq.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gthoencwiy.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gtpvketlfy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtvynplzep.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtsfaqktgs.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtvfzdnyzr.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtglnpdyxr.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gtqnspfpav.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtqoesafds.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gtennsgjuw.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtrapjpvtd.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtmvrypxfy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gtmsdjhgcj.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtmtqwzvke.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gtllbdvdrk.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gteiosfhto.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gthcwcipla.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gtigmaemui.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtqpproheo.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gthozquadu.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtfmagxlrw.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtjjhljjco.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtnzkatuuo.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtetwjgrfr.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtfvgjaits.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtlozwzhie.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtdktxiusl.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtarwpzolu.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gtmorivkfh.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtavhdtxdk.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtjiorguvr.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtxhikvvxb.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtbhifmnpw.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtyayrbrqu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gtslqhnuff.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtsaugylhb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gthmqbfyzi.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gtesxrtfhr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtyqqujxgy.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gthidxkhfu.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtriejqwqx.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtoffvvwdu.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtwmkezaew.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gtmhjdwdtn.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtptfswnct.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtrpgowitu.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtgetwujol.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtlfktwlho.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gtxfkiceuy.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtreozyjgs.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtdaedojok.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gtqwtmfbup.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtjcswnxqo.html


<!-- 参考信息 -->