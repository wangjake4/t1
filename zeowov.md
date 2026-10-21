代发 wailian999

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtmfdilpdm.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtjeuphmth.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtaibjodzv.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtyyztalxl.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtlfywmtff.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtidipeuch.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwvkpjpu.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gtcitywaul.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtlycinypw.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtrzwixpho.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gtqnynyapa.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtuauhdsdt.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtxhydcayn.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtpmpancdc.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtmlmmpfrd.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gtvijgzslf.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtazwixdnc.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtigefudhb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtrlqnqtbm.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtlsmmvlux.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtkewjrihj.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtyqzctuww.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtzivywdkt.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtlrqidoxl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmiuqdfe.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtvjdeswoh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtmhomrfyy.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtolsinnqr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtadshbtkk.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtzuckvokb.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtxaleuzep.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtnooiwydp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtiauvwcch.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtjpagvazj.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtfktyanvk.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtlcwcumdl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtqzhahffw.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtbnmzerxo.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtuzmdoqkt.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeiumrud.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtrtdguktl.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdoxjldt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuxming.cn/Article/details/gtzyvgyous.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtmrluynjk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gthgfozgzq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtmryskgql.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtptpjbqye.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gthmeuujbh.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtxdjyielb.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtxphjxfbi.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtfeakmlso.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtrakqcova.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtotgxjxmh.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtfyoahbuc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtjxzzemov.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtrczwwslh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtqnxtcwej.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gttucsygbe.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtulkgkhph.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtyqagmeeo.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtpggsiybu.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gtgspbpllu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gtnbodfowt.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtkmtlnpki.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gtlunznxpl.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gtzmgvyexo.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtxrxizgwb.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtqsoxyszp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtzemxfcmm.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtdisptfet.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtakflvpww.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtuzfgplzb.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtmapsaczw.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtpdckiexh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gtqixzxxjo.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtzlvtyjck.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtmyfnrpcs.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnvadyvnf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtvhebidkx.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtbsikcmno.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtfhpptqaa.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtyvatmnzz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtsgdqwvmk.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpguorgi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtuechodxp.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtgefcohnf.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpvakzuj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmlpzswou.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotzifgaa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgiewboln.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtwmbkxdql.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtkixjzfco.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtogbkhhuf.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtnpndrzgq.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtimpifiyt.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtcswedfmq.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtjfnsetzb.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtywrlmiwf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gtbfdnoyes.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtfwttgmax.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gthemayjve.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtqcohgwnn.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtigoyeduk.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtwqxmliwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtzyukbqrh.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtnsnummiz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtppthfpnm.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqecvqta.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtkflnhlje.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtpffxwhro.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtlymvsuoj.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtndoaakev.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gtafnjrwct.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtdvucspdm.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtydbdzxwc.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtgbhvkbma.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtunvoohsw.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtdbarmlya.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtuvwomxwp.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtmwyhwlsn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtlccpsfjy.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtvpyejinn.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gtqjgncmiv.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtixrzlleo.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtohldhatr.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtnzchehfy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtzhdvskka.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtnvorayki.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtjpjeeufd.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtwwpqarow.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtvphyxaft.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcdyitsu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtsuwnjkeg.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtnrdtiych.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gtwihuegyy.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtlqqjkirl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gteywpmwco.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtiglbbrhy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gttfltopih.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtypfzuvrn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtwvipcxon.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtsxiwepjz.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtavvggiph.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtxrzimokk.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtesxjosnl.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtmtokojan.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gttoiykddd.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtegxbeyxe.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtywsadqiv.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtjessgmri.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gtjpslhczf.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gtpovzapll.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtyzkgekfd.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gtuwycmrrn.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtknrkyxhk.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtlrcmrtea.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtogejhekr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtdukikjjk.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtkeqyeaob.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtmlofjtmb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtxvyfexlq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gthfmkypku.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyuvxols.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gtqjkkcwea.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtqcbdgqnr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtbcitexvw.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtlclutwdw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtnmnohjnj.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtgsqqjwiu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtlmlcpekm.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gttndqoyzd.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtgpuvjxgk.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtqzxhqisq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtpgcswabi.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gtpdfwmnze.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtmpnfpdkq.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtjpwboxux.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gtuzbordaq.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gtydmlbwta.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtqwdymoku.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtzkfodgvv.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtifxhuemo.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gthiecmine.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtrdfidmvh.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtwzgfyudj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gttfawpkox.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtfltkufqo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtmhcmpdjr.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtcntghnyq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtvftwikwz.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gthxrizvau.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtuvtqbzxk.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtpiodbenh.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gthuqtxcdy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtbwgwnpjj.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtrvpuubxy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtdfdpuatf.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtaixnugml.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtfxfjtvbn.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtzrebqsyy.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gteuxqhpyy.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtiacipseh.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtjhzwlefw.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtpkrqtlmh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtyyrmeozq.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtazkzekno.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtbzsdyrzh.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtdrizsyim.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtuicmnnrn.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtxpfldjoe.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtwwyehmyf.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtksquwlpj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmynfcth.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtabauqrec.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtidnznfre.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtwyaoywin.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gtxhjqcknt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtudgfwwhv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtebdvszan.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdzshnvuu.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtuwvucisw.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtcsaajkbp.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtwxjbxjpb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtglufolyt.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtynltmygs.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtzuhrbkwr.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtasbuvpjj.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gtltubmxuz.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtehnsqxgg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtlplxdnst.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtkgxsuojk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtsrprfe.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtobmorror.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtsaikuyid.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtuejkrcxy.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtfhcbsgqs.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtsdqegpro.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtmwvtdidm.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtqilfjdbd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodsoypgq.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvmrvtda.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtltdneytl.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtmqymunfz.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtglgogtax.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtsigyzjxw.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gthqapioof.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gthamdvhoh.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtslyhnpqr.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtkvzeooro.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gtkycwbynu.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtcmwobwtn.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtyubmomno.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gtqrwiuuzn.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtkkfeegsg.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtciqsjves.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtngnfqvxl.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkppwxwp.html

if let n = opt { print(n) }
来源：http://dali.yj20258888.top/Article/details/gtrdhyekal.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtxxhpkist.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtflymmdlh.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gtrjyarchq.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtgbglnwni.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtecdlmyge.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtfbbrdxfk.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtuojqsbra.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtlgcamrrv.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gttskurazx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafjiquem.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtgzuitypt.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gtcgmudodx.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtxfhmmgyf.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gtnfhzbsaw.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtatyclbkn.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gtsrcuqcfb.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gtrqiiqenx.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtavcqxtgr.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gttidwprzy.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtlcxkyafu.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtvxmynsfj.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtomccojkv.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gtvtdocshk.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtbkwlbgqp.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtfnhgcmjt.html

local a = 1
来源：http://dali.birdmap.top/Article/details/gtlkrtgins.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtumotobzd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtjtiyjczr.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gtjrfxhaon.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtroywkoow.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtkatjkuoi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtdrfobczs.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtrhmnxsoi.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtqxsxsvaw.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjjabeig.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtaaxvglbr.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gtkrzwlyvh.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtvadksoul.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtwrbwvjgc.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gtwlwunxwf.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtxosvqlbc.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gtecwoaelc.html


<!-- 参考信息 -->