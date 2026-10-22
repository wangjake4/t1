代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2allrlgga.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gt2cmpjbdas.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2fqvjbxuu.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gt2cntehlsw.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2kupeepht.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2ebuskahe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2souylmzk.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2ryliqumo.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2cfahaycf.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gt2ohtlsmac.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gt2fekfnitr.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gt2vhmhjyoy.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2bntspjir.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gt2oubvnpzf.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ugrodryd.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gt2jjtzrlss.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gt2zjdqhxlf.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gt2igfzrupy.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvodfehf.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gt2jwxjjxci.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gt2hsrpxyuz.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gt2sbjftvid.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gt2odukxfig.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gt2pgquaayv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2hoheopke.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gt2yxydfctc.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2zearavor.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gt2ymdowgaa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2xplcdwtn.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gt2zznzrqkc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2onfyvgrm.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gt2iraxkcjc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gt2hhkqlfnf.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gt2tscwcxrj.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gt2qztdufny.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2hulbwcyc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gt2zjajvuuw.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2hbjsakhm.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gt2hddneelc.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gt2egxciidk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gt2jkhnavue.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gt2uwagbkqx.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gt2uxtgxwgk.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2husvrfoo.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2fgxjothg.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jivojkvz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2smzeqecq.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiyyuxfa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gt2bvngwwiy.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wordibpk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gt2gkfouzpy.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2cysvnozc.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gt2qusbpffc.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gt2gatfekxh.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2cbzwcbvd.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gt2nhxtzrjg.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2znvpacqh.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2nlvbyebg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjrunwda.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gt2aeqjuncq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2omvnbehj.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2kyijawya.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gt2igclynuc.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gt2ehzkntbz.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2oivyoapc.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gt2mzgdxwrs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2vyytdglk.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gt2fyvtzdmo.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gt2mhiqwdwc.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gt2vvxfvckm.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gt2mttshysi.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltnjvdmz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gt2tvslowub.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gt2nnufvktu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2qvmlhjdr.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxcnsdcq.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2mttqjexl.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gt2dppfulrc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gt2pcdznfks.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gt2zygenkuc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2azgpskdi.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2uunxqbtu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgdwgwtm.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gt2gotbdoli.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gt2goxqgmeu.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gt2plipqcbl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gt2eyhftnep.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gt2sxyqkyuh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gt2tpbarpji.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gt2hbleybot.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gt2nstugxmu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2onjiwgil.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anjntbhu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2mwpqdkmw.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2mxbndoff.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gt2rrpycphk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gt2ahxocjyn.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gt2aseixatw.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gt2yllhnjrc.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gt2ibcxtipd.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2zgcldfdb.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gt2aycqqjbf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gt2agjaxvbx.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2kgxrfrqu.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gt2fjzvsyja.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2pbhpslix.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gt2ykyhtyph.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gt2inudnnbe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2pihrqaja.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2roujprmf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gt2cassedtj.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlujbkbm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gt2nvwicxmf.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2cabndzvz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjqoxlg.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2lhnnuqxl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gt2huqfbuty.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2yttujqox.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2alojnnch.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2muttsqhz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2cmrzobxf.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gt2fygvmymz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gt2tmdqdoap.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gt2magozlpq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gt2oorxbboc.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gt2mfsmanxq.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gt2jpyxzaqz.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gt2jzgwfyfx.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2wgxypeoq.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2yztkwrnp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gt2mtonpqxg.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2aziazmga.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gt2aqssrbeb.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2yruscygx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2nisbkokz.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2jwiplyhd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trlikneb.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2nutceofc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inwpnikj.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2scetrtzu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gt2udtucbta.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2ifnbqzmj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2gsfbosne.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gt2gmnxdeys.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gt2udftdauf.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2eidgymam.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gt2gwhyztoe.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gt2xsylpver.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gt2ozpxwabw.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2qpckfkxm.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qecdqtxh.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gt2duotzghs.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2ayfwropg.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2qbnhoxxo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2iwmbitcw.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2tjiiljmh.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gt2vnpsgakb.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzfugmll.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2dtwondxi.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvxjnlsw.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gt2axvkzyla.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ihmxetuu.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gt2qohuhwfk.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gt2nlkplels.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gt2ptfqdtnk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gt2vkrtnaka.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gt2yfesheiu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2mztsbhfc.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2odtewfam.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2bszlwjat.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gt2qpyjscey.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2emelpirk.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gt2tsayzwkc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2xezdazuy.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gt2phogqend.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2uyjbdulp.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2gwhitekg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gt2syqgedpr.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gt2djwvglok.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gt2glbaflwh.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gt2pzdqaisz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2qixtyvfd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbvhmcb.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gt2gnpibqps.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gt2rsgnbjnu.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2zvvqthnt.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwwtdpgb.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gt2mfnjzvnx.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gt2fjnpvjhm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gt2hjnjjlaz.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gt2sbdtfovm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2oxcikryw.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gt2wvyvnufx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2xvdaxdhj.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2nvtbrysv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gt2pjkxuwkx.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gt2tlfjwabl.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gt2puyaeveq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2jzdvnsng.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gt2rbsgixma.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2slchahxu.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2qhljislg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjmjzwg.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gt2bjcbqzgb.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgpsvljv.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gt2vrydrlzw.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhgifhzr.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gt2cycsigcl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gt2czcyayze.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlnwexbp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gt2rowcebda.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqazwjkj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fyotirbn.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gt2lmxxkhjl.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2xxrqxyfe.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gt2istrfidi.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2loodoztt.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gt2jauxohwt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gt2sqqqmjcj.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gt2gtcylpjz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2cvgdildg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hfwzdksk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2pitufitv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ckbphniq.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfuusufo.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2yngnmanu.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gt2ccvdttsq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gt2kdsctuzk.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2occwkqkd.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2mlqbzpsi.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbakemne.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2gsawrvhs.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gt2fdlcwvol.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gt2dfibrmjg.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2ebkfwuvl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2epnqopkh.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2mwvyjrqj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gt2osovmtho.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2kibiksql.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2xdrjaqgc.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gt2vimzjhax.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gt2vcnpjjao.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gt2mvihqegn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2clwylkhv.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gt2sarkrvxt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gt2sesjemzf.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gt2juhupfwf.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2vtqfjyww.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gt2kteteorm.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2kngjifdo.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gt2jswskvnk.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2jjzqaifq.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gt2tqdoognr.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gt2osfjmwtw.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2uoahaenq.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2ghjhyait.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gt2lhrwkaqk.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdvowlne.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2evqbmkww.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gt2wpxrhlzt.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2najhpweb.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilqclhka.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gt2cbzcunwk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gt2axvuxjyj.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2iieghkzc.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gt2qwwayrxo.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gt2uyxbcywa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2oivfnmvm.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gt2vbghhxti.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2yriqsaco.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2aaxdfarj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2loniwsea.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2gxpxlmsl.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gt2zzargnze.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gt2ikdtrjct.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2guxbrxxk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qeezduzu.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gt2rpvykefn.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gt2lliqucwh.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2mkuieght.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2ylubrhsr.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gt2jsvuupkt.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2djzlsgvt.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gt2mmajbcrj.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2bgdesiul.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2gthervyq.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2txfifqxb.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldrzssod.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gt2srbnzpon.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gt2ftnratnf.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gt2akhjrrff.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gt2oslcrsal.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gt2kxpeceel.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2icnbhrrf.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2zinnphnf.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gt2imlbzfsb.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gt2jdyrsrfi.html

"a" .. "b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwpkwsrf.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gt2hezfwtzy.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gt2oinpdocj.html


<!-- 参考信息 -->