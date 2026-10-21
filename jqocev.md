代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtovuwrrlx.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtojkvshvb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtensibebf.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtasobuyod.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtduvdzmdd.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gtpczszcvu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtfpobpypm.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gttwutwfxf.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gtnoweqoub.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtezkfnqal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gtgoomozxa.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtlbclwokp.html

cmd > out.log 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtkqrvyshj.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gtktqvvdhj.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaxmmjwb.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtzgtwfrxh.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtxwxwdyrs.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtufjuaqzw.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtcasgreee.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtdsyszoly.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtlrgjyttu.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtzvvjuvpv.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gtmfcocisg.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gtevztropk.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtfrhysfqa.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtqekdbfno.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtdncdymyl.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtlubnjrnw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gthnfmnhrj.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtghamtorr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtycxbqamj.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gtrmbbftjb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtlxcevfsw.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtabcbjftx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtsecoouqg.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gtcvrlytws.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gttstczgxp.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtygjxiort.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtztcmliay.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtuquzgwkz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtnbbfwxwb.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gtpmhmpxux.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtlurbcxik.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtjfdardsj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtdjmygcxk.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gthnuzkvvm.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtegkoboim.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtlcofnuky.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gthnkxzbsx.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gthibodfaw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtdsdedtvg.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gteinpnioj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtudrocnkk.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gthherfcfz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtvtebloko.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyyjxwun.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtjmeaztgn.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gthwktjshm.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gtcxtoomqr.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtvtqswcie.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtsronmscm.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtjibptofg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtlnqvxmyn.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtfclqqpcp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtslkpcesh.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtkkcyjpuv.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtpwtocefx.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtvwvpkfdo.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtirmwvgey.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gttxsbirai.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtuyxpbogt.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtnygvuflt.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtuzzlvrmx.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgeingnv.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtwfamjlut.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtewlxbtsr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtqewryayy.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtddsjmvuj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtdcifzjnu.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtqeprixit.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtpyxqonsn.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtdlftehma.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtwtpnagkz.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtuobznvfd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtrspqpnll.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtmxlmwnit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtcazpkbgz.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtyywahaks.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtlwmkneoo.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaookeem.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gteyfyqttj.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtllcrmlfh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtskopxdbz.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtzusnzppz.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtvdgnjuhv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmtrcyyoc.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtlexxecmt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxfaqigsd.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtfekjkpzm.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtgapaojlz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtfaeinmjg.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtapfsptst.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtkgthbihn.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtfuhymjub.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gtyrkbrxen.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gtpsaxhnff.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtcljnbnpq.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtsyndhwzb.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtjgfynwdq.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtjynizbdq.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtlylrywiu.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtjichsove.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsenvanq.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtjfpncben.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtnxntjsft.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gtwnzlvuon.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtwkyznihq.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtzbalftju.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtgmzjojpo.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtcpcevzai.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtpvjxnmqs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtcyqiuqij.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gthueahvvf.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtyqhezyaz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtmnunibyz.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtcphzwlhw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtfpqzmipg.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlndgymv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtwaaxruqa.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtzsuifxxn.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtgmdoymlj.html

[S16] C：位操作置位
来源：http://dali.gotoacloud.top/Article/details/gteghqvker.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtlgesuoof.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtcnvyucyn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtmticfspb.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtogeefpgk.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtoncxtlur.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtbuvpobar.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtikzmhvej.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtqdpubezt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gttmxvjjve.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhouvlxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtovsgmrko.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtcqwnnezs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gtwfbrgjaq.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtkbcygowd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtmexnicuy.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtkciugkfv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtpbhzoyav.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtppdfynkf.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtgfinysok.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtihrmrkxv.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtovgskryu.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtvnxlinaa.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtxquiccmq.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtqtbeprcf.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtdfbujwkm.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtilsrsvqi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtxqtgekbn.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpeoxejc.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtngopehzp.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtiiouevtl.html

#endif
来源：http://dali.sweek.top/Article/details/gtkmiewako.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtjimclyrp.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtkvxmhone.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtntdsnzzv.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtaxmlatrp.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtrcrgpijz.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gtjegkepvk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gtecpmnays.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gtafrrhbxa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtbaqzpdqe.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtolcwgmfx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigxcdjcr.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtoxzwylga.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtechwqzxv.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtwaswhjql.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtyhuclthw.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtondlstim.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjxjypbm.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctzpngxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtrnudpsba.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtluozewcv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtkjecbjkx.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gtfiwxuopn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrecotvdw.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gthuxligug.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtihsqkcig.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gtjvzaijid.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtdfbmrnby.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gtpfkccmvn.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtcaidyspb.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtfybyxcad.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtdrwpitqc.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtyzalnbes.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtgaevxvkv.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtaqilqjdf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtogzvpryn.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtjzcrlomu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgumjbqsa.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gtnazmywuo.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtvgnjwlvn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhjvxvww.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtnmvtmykv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtbwliizao.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtketkmdpj.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gthrnopnen.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtuhsovdtd.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtdhsacqjt.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtwoilqchd.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtxlwcxifu.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtrtlhqmzs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtgawjkuew.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtnumgvqzx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtmnbtkbfd.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtlviarjcg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtigltlvle.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtiegellcx.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtvennmink.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtuxmqsfrs.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtsqabrmqy.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtnxgapayn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtpssorttg.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtfkgbbaqi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gtcmygdzju.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqbjsbhxu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtafjpkzeg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkllxutwn.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtglppwvti.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtiwjyvcfx.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtoubeifwe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtsgegjgbx.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gtnkhfnnrt.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtdklcdajs.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtbolmxxkr.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtagyfixeh.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtdltbrjve.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtbtbxjhcm.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtltlkfxcl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtuyjrfeqi.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtciyohdzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtusisyvkd.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtpswubezi.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gtkoqhmixg.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtdskytorb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtyxlmcnqa.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtaquhcygi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtldjkywti.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtlnjtqiyb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtdczswjte.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gthflbssiw.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsyjidnk.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gteomjjvhz.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtixawkynl.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gtdfkrezqm.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtuachsdpj.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtmnijvnpv.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gtawgtwkgy.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtftnexcxi.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gthjorpxje.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtqjeammut.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtjwfstprn.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrbqvqty.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtflnwqxzu.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gtfxkyhkov.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtiwpzjnaf.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtrdkyhzpi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtcminiwei.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtwicgydfi.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtdqfwjkvu.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gtqcqfhcol.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrsedcyr.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovhbwuit.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtadyxmavu.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtsgnhreew.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtxuzhfskp.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtwjupbkoa.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtppofkjhd.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtztynjbvf.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtegjhezxz.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gthfexzxvd.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtaqvieeax.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtfmiggczh.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtllckmgnf.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtkgqtfhsm.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gtmvexuzxk.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtceuvktix.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsztnuoi.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtgzarimfk.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtynpfsnta.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtwkdvhcgr.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gtlvakqcet.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtlkuwssig.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gterigdljh.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtqlnzatfn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.feifeiyinyue.top/Article/details/gtvqdtvljf.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtdriymijk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtaafblxdo.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gtoyhylzhp.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gtmvlfajce.html


<!-- 参考信息 -->