代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gt2aevpgkaw.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gt2pkwnbvqa.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2mrsxyeiz.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gt2kudpsjah.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gt2yjifqibu.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcbvxqry.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcrelavc.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gt2kbzxbbmy.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gt2nntpeeyp.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2bevhcrkp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gt2ydajbuln.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2xmafrlhi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2hedmfbxs.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gt2lxsrurwp.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ldoizrqp.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gt2fujdphxi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gt2yudfdhtu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vssoybno.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ikofyhbu.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gt2wuxsbkny.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gt2azykredv.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gt2mxfnqgcj.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2knayrcah.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gt2juodptuo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2emfzlkqq.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gt2fjdzowmn.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2exyyjhwe.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2dhkmjvdv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gt2giewsupd.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2blfmjmky.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2qmtyimtt.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gt2zrjfkeud.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gt2agfktjxa.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gt2oyfuexlm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2jwglhrwc.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2wqbuawhq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gt2amfsidzg.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2yekqwosh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gt2rhwccihl.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eboqdfvu.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gt2ngmbseuu.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjhfmjdc.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gt2zadddcsz.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gt2otdfpyzk.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2odsknhud.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2rcwamckr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gt2veulaqcw.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gt2kefkadfi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2hsnfcvum.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2nabvdrmc.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gt2zussqazn.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gt2rgdeorot.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2bimytcma.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gt2hehyoiju.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2ktbfcsvx.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gt2jjlgcmun.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2cpvmucsl.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gt2zsfbxrrs.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjzfyhiw.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2mnaoudmz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gt2nozhgmdx.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2gvyvhdro.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2jmdywhwq.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gt2vuvpcxih.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gt2djzxfczh.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gt2ilvbeqkq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gt2frejrsdp.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gt2gegsmequ.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffnqkhva.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ivozgvgf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2uxpnesrx.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gt2flhmqjpt.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gt2fvdnajym.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2mgkgayqi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msfqyxbk.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gt2wzcespfa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gt2oxeptdfq.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2oqduvzmm.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2prlfwpbn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2nrgfjbpe.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gt2ysrxziad.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2bueautjl.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2srzwnhpi.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gt2opllycsw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vuevylzn.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2glmlonxi.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2sepsmeyk.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2pskvuczc.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2godyosrq.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2clawekms.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gt2bnlqldzk.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhhjexdo.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gt2rnzaorxx.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2cfegbqrs.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2hfygtryz.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2zytlczvo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gt2vvfztods.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gt2auoctrtd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gt2mujvpdlc.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gt2bruhadya.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2lgfmvjhh.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2dwvbdcbz.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gt2sfwpupoj.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2kcluxfkg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gt2jxymkylv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2ggagtbhe.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gt2fpyzvyan.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gt2yceeemmu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2gggcqbzn.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdkvadiy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gt2dggcxrif.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gt2esgmxlox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gt2ndibfvut.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gt2uveaqdyr.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gt2dmvfgxak.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gt2hyashcso.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gt2cqzvipwm.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyvkfysx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gt2izmamlxh.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjkjvbcd.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gt2yplcztiz.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2mijyiurr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2rlxeuxms.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gt2wxzjaocf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2vpzphbsu.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gt2nntvdeju.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzoztset.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gt2xojzojcv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gt2nlinatle.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gt2prirenuh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2rxkfhxlc.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gt2aedgmmzq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gt2ufktjnkj.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gt2ldisvnzp.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2idmnfmit.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2wmtagwwe.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gt2kmubdpqv.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gt2tebbwibq.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2gcfiincz.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gt2vxnxcnka.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2uczwzart.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gt2ghnfzzqa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gt2ttkclkis.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2vbjwvvxg.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2ilftoqol.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gt2ompwhfbw.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2eoyiczhu.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2nrjxjwph.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmguoszs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gt2btnvgqte.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gt2drnvtzoz.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gt2zedkocgt.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gt2ciegonse.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkqxbgiy.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gt2fmbrceua.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2umkyagfp.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gt2jjzeeclt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2yrbslrtj.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2kjetrzob.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2uvfliovn.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gt2wblkjizl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2hjzxdqjp.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gt2tpmbemis.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2whxfqdwx.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gt2hwbjkdvf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gt2avcztsll.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gt2lknvgalu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvxvgqnj.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2wqdddfgh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2ucfhbatl.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gt2jzmklvcd.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gemtgghj.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gt2samwlzjd.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2yfiktmfb.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2fqojkmuw.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gt2zqwazyba.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2pddweqxb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2lndhersx.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gt2mexbnjng.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gt2lkkmokru.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gt2ngyxupwl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kaepioql.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2xafgrhcd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gt2mdukgzar.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2dzffykqx.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gt2gmiawzum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gt2cxtjwhay.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gt2axplfwng.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2mjsxsdjr.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2qbltvmew.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gt2jiavebsu.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvkuzchs.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2ehhgwpah.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gt2dxjpolhg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gt2orcehrif.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gt2yoyytbms.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gt2bwokkefw.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2sycmlpyw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gt2nikqdexp.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gt2eaczlamb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gt2ijdmnvxf.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gt2aynddzym.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gt2hecdjefj.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gt2fliqbsws.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gt2dawuykzp.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gt2bciomepe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gt2ufpjkdpb.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gt2rgwvzrzm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gt2ocodpcqm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uojatqda.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjqsoknm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bmrjlqmm.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2wgbkckrq.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2kcrexseb.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gt2zsifygfj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncqiwwcx.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gt2tjodkbvw.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2kficytzg.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gt2mhocdjcr.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gt2rihzyelb.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2yeuumhwv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gt2cfskupxn.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiwcgmvf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2batmfldv.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2tysfnfxc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gt2gratyfrx.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2mewrljxe.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2npxnnhoz.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gt2zynwpoia.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2rzufwlpj.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gt2euyyaraw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2slwydcoh.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gt2brjsewps.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2czkbzjtf.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gt2bqspvfiq.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2rbqlslfe.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2yjivlyru.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acwuajei.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gt2jcajgwhc.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2qjsjehcv.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2aphtbwec.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gt2zkloztww.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2zsjhqahn.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2dgziirgl.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2gdbycbgj.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2gkurhaho.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2ydpixhcv.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gt2dryidlgg.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gt2tuzabnyz.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gt2cunnhlbh.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpynprct.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gt2vuujxvde.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gt2biuonoet.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2pmflwiig.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gt2cxhuzfuv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gt2uohzdlih.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gt2npypbxnw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gt2weacosws.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gt2behoreuf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2qsndetki.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2valdgbmy.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gt2dbroduxl.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gt2xvzthmyp.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gt2pbussydn.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2cimcmwan.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gt2dwyjcbdt.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2xrsuwzwn.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gt2euvjsndt.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gt2boqepcme.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gt2hbtjbxtv.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gt2lcuhanil.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffmqhaaw.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2psmgfxlg.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2drpzewek.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gt2neuqisyf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zltkfdmc.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gt2fkglrfeq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2epstjqoo.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gt2ahdplcrr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gt2kbgxbklc.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrsxpazt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2kiuqbzyu.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gt2oqebjhsk.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gt2gknkmkic.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2ltkzfomp.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gt2vekzmjkd.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gt2mspmffxk.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gt2qzdrfhiw.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2nvpyuutq.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gt2jnbiienh.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gt2jygiigpu.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gt2ofgehgfv.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2kglaosbs.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gt2ddowmahn.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2djgqcjbp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gt2vseaycah.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2kglmkrbs.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gt2rermuybu.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2wcmiqvkl.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gt2vyvohckw.html


<!-- 参考信息 -->