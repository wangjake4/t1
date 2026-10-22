代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtcwlgegxj.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtkejkqucu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtknwmanjh.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtjbmbfwxt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtfmbffpqi.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gthcavpshy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtnmomyxhb.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gtsxhtupsq.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyettokx.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtlipstwxo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtlnffwvfe.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtjdcghpqv.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtmjefuvca.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gthzjhkxsy.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtshpkvscy.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtcrmyhjtm.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtinxdavom.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gtkiadccml.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtjzqtmznf.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtfldtqyvk.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtqtkvkypw.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtxgpbnbti.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtxeiayubr.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcfghoei.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtkmjkwicb.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtcmrfvhmp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gtgrnkykxo.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtevtraeeh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gttrprsaei.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtghzexxye.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gttrzhsxio.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtypyivcxi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtbuptetjk.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gthmdjmone.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtjzglgbwv.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtqtkozpie.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwmiklzh.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gttzonhtto.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtyvueonqe.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gtppblfneg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtvbpfrdvn.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtwjjwejmk.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtohfgtlwi.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtmworbnbq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gtldovwcbg.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtqkmgylyp.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtdalwcubz.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtdipfbneo.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtkmigpedx.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gtxvygzsag.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gtjcdcrjvm.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtdwbhknac.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gtclfuwyln.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtqxiwjgzc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtmwkwmljt.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtgzcoxffu.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gttxlkafcb.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gttiglropu.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtqedwfjav.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtztfqxuap.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtaumjzjlt.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtevferkuf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtkdngjtnk.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtkolmpsvj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtgoueacym.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtovzyghxc.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtklofyjcq.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtzpejdxap.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtrbsvjftg.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtbbveizpm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gtkztuvjyc.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtyibdawuu.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtfkymwalc.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtdsmuidpo.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtxontxivk.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtapjmxtkq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gthwtnxiue.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtpjjmuesj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtkishlasw.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtvhfixisi.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtkoxelfhk.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtsistmxio.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtocpucgwo.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtghowumpd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtfrmfpjtj.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gtgjjxjemf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtwurjycri.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtpmwvjfzq.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtviksjtqs.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtxmdntehu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtfzvsczio.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtvbpagpqd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtdtgmcfib.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gtdashfoiq.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gtehvtfnqy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrhwoidvc.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtlppgjasj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmxbuhwnz.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtiibbxjvh.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvqflygb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtqcpopmqi.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gteyccafyc.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtrnumgqpt.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtrqpdzlpd.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhnvmrhv.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gtklnpglcn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtisxdjvgr.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gtemqdjljl.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtntiuzctp.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtvirfgnqo.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtbdcakepi.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gtjumdpscf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtywkddwic.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtxnagkkrk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtcryatofs.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtuovpvogp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvltgoepj.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabnpnbpy.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gttlzgrqfj.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtdhaqbtic.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gtoghbjung.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtgloqoikx.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyexrfkbk.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtpdcjtzbr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmdnueug.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtcwsisgph.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gtapwojstn.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtbuwbovve.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gthuptxgdk.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtwpxftcvz.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtmultacua.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtqbjblpfw.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtugpckyza.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtjrqtcmrs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gtdpxbrihw.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtxszsjfbs.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtrgwupzww.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtfmpouthn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtqbrtdwko.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtjqctqqxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtgxfpoclq.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtwlbsonew.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtaoexxcjx.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtmkgoyvsj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbyiodil.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtidnquqms.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtovjwkqsf.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtbvzgdtmm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtakrdcmoh.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtrrsnvjju.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gtkcujwlae.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtktjljlgp.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtnnjbxqvs.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtvuzwspux.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtmfcolnyz.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtjujyyweu.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gttxgyizni.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtmottjblp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gtiesfskgl.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtutsrajro.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtopoorord.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtmbpebpcr.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtjggfexgi.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gthiilkpxn.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtqhctzysz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtiqqmpfjb.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gttwswtekx.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gthrookddr.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtohipjrfj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtuqcirqrl.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtunmuovkl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtgmhrvqgn.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtextvgmnk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtmqejjrio.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtrmzlshtt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtpymlmkiw.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtzyfxiasq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtacpasnzg.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtokdkpgxw.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gthbubkntb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtthmlrpbm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtvchlnqvs.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtmuxdkruv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gtqtrazpmj.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtdfabdeyb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtahzfkekh.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gtvfhcgcfr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtdpqkvwsv.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtubdrcdur.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gteeubqdnv.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtdjpwfzvf.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtonfahfww.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtzvteqrwz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtrgvgvpsh.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtaoakbrjg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjlddkipf.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gttkxelvlt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtafxubbaj.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbbjmdcs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtnbjlxodd.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtwzkuwjci.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtljdouerg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gtbmvrdofa.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtihntcwmd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtqvdmljzn.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtkdzhjvwb.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtdrbuklqy.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtnuthplqa.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtrhrdfyts.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtnafzmmxl.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtxonrsfft.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtaqrlwlrl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gtopdoalpq.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtcanssdhg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtkbznmtkc.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtmupcorqr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtmjaegncl.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtgibnquxp.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtsefniigq.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gteunpforp.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gteifwgeby.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtszefwyly.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtpnateqca.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtaltmmhfv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtwilmeuvd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkhjwekmi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtivyorwxn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtshqctcmh.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gteqkwiswf.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtrkwltehs.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtmyasywjt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gtxzlazdss.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtsysromzh.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtkfuyprzh.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtjiylduib.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtfghfsjtu.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gtelkfhcdb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtfmdebynh.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtieylxcuy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtlrlyjvhz.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtplouqkyn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtagdutvns.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqspsvfdt.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gtrqinhoxp.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gttiommckr.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtouhfjjym.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtxxmdbasu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtwkixuffu.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtfnplqecd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtfkhxarsd.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtensjtqup.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsssamqnu.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtixuqvsxh.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtydshvsuw.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcddsgzkc.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gticvbayfm.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtuibmounm.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtgqqlcvgc.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtyimuzvex.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuifswjng.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtiklzbdbg.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtufcqkbxo.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjoglgbm.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gtctpkxbzr.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtxqmgnqhj.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtdylbsqva.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtrtcuboqk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtsgpxiijo.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gtfrzalpgt.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtwmyngglm.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gthfmgixpl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtttbkhqvw.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtguqqdrku.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtgglotlsz.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gthsnvykyw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtuykslomv.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowlmhyul.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtpgfafoac.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gtiyjussxg.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gtngbbjnko.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtcrqibrgr.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtzqozfdrm.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gthmyildvy.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtksstaucc.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gttkjxyfup.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtwaoupdzd.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtxysrejha.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gtoxidrvva.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtpmnzecdi.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtqjwcihav.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtukgadjqw.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtdfyvmtxb.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtdzglhsys.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtxyqtnzed.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtgjdzjqyh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtamatuvce.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtubzzfjvn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gthockkvik.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gtzjbluqel.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtizbdwkar.html


<!-- 参考信息 -->