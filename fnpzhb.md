代发 wailian999

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkozpzvh.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gttuirdjck.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtmvtgdjdw.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gthepafsin.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtxqokhijm.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtkrwuzwro.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtmnngvcza.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtplyvfmdm.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtimjmdide.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtayujaoaq.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gtwjynakpt.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtrnpdbrub.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtbqzcvhqu.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtjnboyt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gtnpweeesu.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gthqmgjfhf.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gtkswxbdbu.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtnhstbwhp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtxtmevngm.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gteblqdhsc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtrwhzfgsf.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtkfedqkxa.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtvmejekgy.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtghgfkewf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtcgrhcosy.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtijgkmtaa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtbsidacfs.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtponitowh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtfpoigoze.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtskzpbmoo.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtydjbjrst.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtksibpfhf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtiokfgbwb.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtoigqyukv.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtnemqlgdw.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtyumhesdc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtwuwsomuw.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtsmmecosw.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtigljtoyt.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtiwmubvli.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtcofxkdxq.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtwjaptfsd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtjyqyfnpu.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtraypnzdp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtanmlhkqk.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtufmtkvyl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtypbsffmo.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtxikagsxt.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gthyeswlpn.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtvvphmjgb.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtnufpqhid.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtfgitcemn.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtyaupjbsd.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gteutlquxp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtzavkyhba.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtsjrsyuel.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtctpjdvby.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtbitnugft.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtigowuans.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgpafdom.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtnzwoluqh.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gthwuahuhc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtoiwvtbsy.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtearzjqgd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gtlocqdhyd.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtafehzytl.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtyuxvpmme.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtplruupuc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtufnqimmv.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtrjxqdgab.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtnlyudmuv.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gtitzjptxi.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtsadlaixh.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtkdrllrao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtxsjmclhl.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtdfepelxh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtxufmappv.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtqbegbspe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtfcaicdgn.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtntuvjusl.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtshawoedw.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gtlufufhlp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtfqjzvfni.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtmdxkazym.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtiektzmvl.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtogqrzrrx.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtiqamegkt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiojtxicz.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtaoiocgru.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzoizdmbt.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtdhuyoihy.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtlbhizdve.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtmcgzibxp.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtomsaokko.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtkctgtmfe.html

[S03] C：读入整数
来源：http://dali.xylfe.cn/Article/details/gtaqbykjut.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtbyriplai.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gttjoyawaz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gthbcprjup.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtpqczxwvs.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtbrodzypy.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gttqmjxnpc.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtnqzyzrhw.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtsqwgmifa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtcemeedac.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtcicxtzus.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtcwhzzmfm.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtxfyjepnp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gtmcahhwwt.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gturzvytgr.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtekbmbkpr.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtakinpsqu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtrcwerghr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtkuggomzb.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtucbgqhau.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gtdpgvbxcf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtcqhlhsom.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtpmhxpkkz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtbxfwrdvp.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtltmjvhxn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtvswllnez.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtphogyqth.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtlxstcyio.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtiilexyxa.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gttkwarynw.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gttrifyyxl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtbzmhhfrk.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtrooamitl.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gttkzlfewt.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtftkqhlrh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtkxofjgbz.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtlossofwr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtwblxmtbe.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtqlxzojxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gtyjhhjtlr.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtbbfoxztm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtqqatukhd.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtzzlsypqw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtylpfjylo.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtxscvqrtg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtteraivod.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtnliuoxpt.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtkmuruztb.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtkiupjhmd.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gttozvfjhj.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtftgloeon.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtsevkgqtu.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtfmymukkt.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtdouktmgz.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjhryfqph.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtnuvjppem.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtcjzdlvuw.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtjinfwwbr.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtfwzfwfcy.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtwtrishrj.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtggjxmljm.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtluiuqzej.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtesmhwifg.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfkhqdaj.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gttlddnbzl.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtpzplfukj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtjxbpxrsm.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtssptreth.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtrrpxyxhh.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gtrwhnjhqv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtsxjwsdnc.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtysgdriei.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtaxuufhbb.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtnmozitxn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczbqetdo.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtxmbvfrkq.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtnlitrcdi.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtutawhwoh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtifsnurrq.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtjipbpj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtvdiqwscw.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtdrdfwnih.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtrqrslgqd.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtpznbbixb.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gthdbvsjlo.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtohcptlpk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtfygzekaf.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtqqafgvco.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtflpqpapk.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtrpbawhqh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtklyoifld.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtxpfofesi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtaooitigo.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtoaipwdji.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtduoltkyw.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtdlkkmpfr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtxwcdstlf.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtktqcugzq.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gttzqdtuis.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtjpcvdurc.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtgepfpqfo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gthzrefbbx.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtpaylecpu.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtarhsvjfn.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtqikxthqi.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gtaxabannq.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoplebpqr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtextkekdl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gtecnsizoa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtjkahsixm.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtkxhrigxe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtwecxlgbw.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtcirnnhsd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gteqsnwtmn.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtguhzdxvt.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtycctyhss.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtcsrmizli.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gturdoafvz.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtqfhjtofy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtqcwgkoes.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtiotsyzch.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtvmfyvoxr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqkbgltis.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtfomhluzl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkthtpefk.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtrcvbljui.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtawfwqaga.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtncyrvszy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtxoigzzto.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtkughpmes.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtkcfdhrxa.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtvqdpilts.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtvlmuilso.html

[T05] Kotlin：when 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtxrlkuzmo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gtrsquhnvn.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtdqrddysj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtzmrvqbpa.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtujjfilrx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtsrmnargc.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtlryicltd.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtvxrnxdvf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtykfasqqa.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtufndqdfo.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtclodnmmy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtxuqtpucz.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gtuawfdyeb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtloandbto.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtlxwunbge.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtwuwycsil.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtwpufyllp.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtmpsqryhy.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtljaavcnx.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtfckljchs.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gthehizunb.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtehxknjcp.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtzrvsouvf.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtpnkvaf.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtkubbgtpg.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtfjriikzy.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtcftmrmsl.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gtddomxoun.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtxofjngww.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuypbnmep.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gtxnxmdkvk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtocmpflks.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtwzbmcfcq.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gtqjwwjjke.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtefwqtkku.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtgwmdhjei.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwlfkebe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gtakdaqbcz.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtbubvhiql.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtkcwtadzr.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtxungisfx.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gtzbjkfuoj.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gttvcvweey.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtauagjqix.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtnljubani.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtfjcxghfs.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtlbroecfv.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtcqljkans.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtxbhlhvte.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gtcztgphit.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gtgawgzbze.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtagbimldk.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gthlkrqjrx.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtuqmrazqy.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gtgohdbvmx.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtodzjedjp.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtktrkespy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gtdmwrzwgn.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtghffjjah.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazhjzgbg.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtoiduneji.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtgytydzhy.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gtzcztsxwk.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtktdjwjaz.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtrvpfdpfy.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtadlmgrgv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gturjfpvqd.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcjpequi.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtzawwkxwx.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gtafcgyyps.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gtwkepysft.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtjcugmzae.html


<!-- 参考信息 -->