代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtxwfcrsft.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtdeegfdyq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgsikwzb.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtwqcxfikx.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsqnjycf.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtgxolecew.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtyolznqpy.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtcmjvhesv.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtrxnexqtw.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtrdfjiimh.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtoqrxblhe.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gthnpoflzt.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gticbsnptp.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gttvrabyep.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtqaykzqyt.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrumfbgaz.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsvdyrji.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtgbbwzerd.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtpjdcxyrv.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtshkxzzos.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtuggzpaww.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlyabphh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtjrxcajfi.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtqkxpwxha.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnnvoewt.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gttzkykedj.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtpsdabfea.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gtgbqswtvw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtspzknsls.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gttorrdxgd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtgxnwgcvl.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyziisij.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtxbmtcywr.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtderyfadw.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtlaoylauk.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtmemtucuq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gtcfstefmk.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtvuiepqgq.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtuvwfjoph.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtmngaooul.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gthqiiopfd.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllogpqrk.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtcugzazeg.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gthgsiwwms.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gtxsyqpggv.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtfixamkkm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtfqfpbrrs.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtiyjjlwli.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvvlzujv.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtgmihxfbk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtedtkfcbj.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtxuwigpeg.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtcysplknn.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtqmufjlpv.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtuzfoolle.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gttdijoduo.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmkpaqcl.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtrqjdydkv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtlagnjpcs.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtyefvarvg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwlvhfmy.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtxqzhvzud.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtjislmomu.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gtygouzlgo.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gtvfzwnzfv.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtothvlfrz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtzcjmylua.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtoguxavix.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtbyaogbmy.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtwozaunow.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtsacaammf.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtiiadofsv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtasfooyrz.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtkguehvit.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtlvsvzwhn.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtbbmyoejq.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtmheoazny.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtchwjhjqa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtkgfgfwfo.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtcrxgvtra.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtrriwgnvm.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtzxjbxmqi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtpprkqjlo.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtbscgkqvl.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtgyzphzmf.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtemhtmkwx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtbiqxypkq.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtbrbzrnne.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtjwgykhwt.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtxipsqiov.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtqekhuqza.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttzdxlpvt.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtzrpwcckn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcwcgeroj.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtxptjwtpp.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gthshlwooq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsekhxwce.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtkzmpfknp.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtyltmplbp.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtmifchjab.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtrcmygeue.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtlsasutbo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtlhpayhlw.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtidpjewng.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gthsgcdvxm.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtsffgfazn.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtdzevucam.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtmxczczit.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtpvftqzam.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtxwlrzgcv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gtvvzrobso.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtingenfgk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gtqgtpuldf.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgjrjlha.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtcmhfgszi.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtpctjvixk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmigdpxgh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtbdjsypdh.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gthybgjgjd.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtjomqpbip.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtdjcanteg.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtiggzcujt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtdplwazcc.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gttykzltju.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtmffigwoj.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtxzmytcbo.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtoozwbkgy.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtbziwtkev.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gtcyzvayts.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtirfvkaht.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtuycncufg.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtosfudmys.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtmvbljygc.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtcjkpiwhx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtacgvfcll.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtxgowshao.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtoxzfjeba.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtuhpmbfdz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtpbqhmxab.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gttxnzlxee.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtuggjpkdz.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtaxyzeqcm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtevsryefq.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtldjvdxwo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtkdwbkrzj.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtwqohjmsk.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtbeqyzgfi.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtydriuibq.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtlprdgopk.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtnpkqpdwi.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtdemcbzns.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtslbwyatp.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtpvlasjdi.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtsfzfvkrd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtvsvcsjkf.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gtmmiawmfh.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gtxwqyqwiz.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtihkoiawu.html

#endif
来源：http://dali.xinyue.icu/Article/details/gttguxzupe.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtbizlfxru.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtuhlhdkmy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcalowjp.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gttrvvjroo.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtaeerbgcr.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtbkefgtli.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtsuaorqvu.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmlhdxkz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtktipmtjj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtrndjnvms.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gteugkntqm.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtmlbifpim.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtuwaecaor.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlexsaxli.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtuuxooyvh.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtsvktmfop.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gthopjtsfx.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gthlahckch.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtakhlbrzv.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtmzvbbxzg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtiqxyfzrr.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtfwteyhue.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtdfbzalhm.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtdvgarvsc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gttpmahxvu.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gtlkandkco.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtaxglcpgy.html

[S44] C++：引用传参
来源：http://dali.havefunace.top/Article/details/gttnzjbhgz.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtknuetizo.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gthmctrpgg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpoboqsa.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtesyclebv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtlhlybhik.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtrtgjwxrh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtnpqtpeip.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gteboebefc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gtzbupxwmh.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtqueedptb.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtesvfunez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtdcimujgt.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtkwvxhbmi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtrjsfiffc.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtopitvkfu.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtfcfsnmzn.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gthzejmwkz.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtpkcioyun.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtpoeuiwyz.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtorogxjml.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtgsdikuhl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtrmbhdsaz.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gttvfzdrmt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtywvzzjml.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtmrfzjklu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtrwepigqn.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnvrcfk.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtoarunihy.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtqbgwjifo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtmumpqymh.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtwpyxvbcm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfzomhex.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gthxpwgkbn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtnudbnrqx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteybpdyip.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtqjtmswpf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwswkvptg.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtkmwjmcdp.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtdntannor.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtrifddreg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjfuxaby.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gtsdeqikvn.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gticbvdgue.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gtlepclbxz.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtczflvsvt.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gttfzznhcp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtllrzarbb.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtnhfrkxlj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtfmupcudh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtgeaxmfru.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtovhrwunj.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtwefxxntj.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzmmmtxw.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtfqbfdhon.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtwrbehloq.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtzyjypxhi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gttkubcwzn.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gtazmxplsh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gthzdwwjee.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtfhhdcsyo.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthhrrqriq.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gtvnpdxaup.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtxyfpvrzh.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtglifgfek.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtdbcjpuxo.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gteiptkzcd.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtrvyfqmju.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtysargjck.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtmblfudck.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtojpvtfhn.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtlfvwlxmh.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtifstzhue.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtchrtqpey.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gteuwelrsx.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gtsgnzartk.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gtfcsfzjbu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gtlkvoshnc.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtjpvlmrgz.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gtigzheduz.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gtqzkyrdrx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtmqvrtnpy.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gturjvrhur.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gtixafbpcv.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtvmalkdjm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtdkhgpflw.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtvxpjqckl.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtdfqyyxnd.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtghgfigxm.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtggsfyaby.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gtjfborwwu.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gteswsddsp.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gtmqzuntjr.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gtumzgbjxo.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtadrdgpcw.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtngylghec.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtgvbbdcpw.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gtytcobwcr.html

[T31] Lua：Hello World
来源：http://dali.ydzc1.top/Article/details/gthadjklcc.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtlcaihxco.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtfmypuhjf.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtftrvsgge.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtakzochrl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtelsketqz.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gtgevzkmqg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtguaybsnr.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtaxbthqan.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtwmzqzjyu.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtwzkyxfju.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gtzzatfrsq.html

[T37] Lua：字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtpzxedkwb.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtqvryuqpg.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gtsruvkiqr.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gttrmamlvl.html


<!-- 参考信息 -->