代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtzpvxnyaz.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtmffljnui.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtsoqsdxxk.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtarvozeeh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtzgybzerv.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtkqnzkanj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gthaxdjjmz.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtjxyiwbch.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtguiwexrl.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gtyblexznd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtjdehhork.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlzivqql.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtqlrzrpwz.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtvwxhgqes.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaieiqso.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gttbxsnrsk.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtwwysbgyy.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gttydcqjhh.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtaahgaowp.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtufgncdau.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtfwxoaqlo.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtepjvqxiz.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtkvyccuwh.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtcemihkvr.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtkwnjakgc.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtyyttzfdr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtxnnedqoe.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtgqxdzvpe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gthodgwked.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtdgzwteup.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtmrakhrxw.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gtvhsjcera.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gtyijctarz.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzbtfuhx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtfdeokfwe.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtsrfgfilr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gtyuxgerbc.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzxzfqci.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtfffejqqq.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtrtgioxir.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtishcfbvk.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtaeonzsgx.html

diff a.txt b.txt
来源：http://dali.yanxiufei.cn/Article/details/gtxxhxkvhl.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtojpqrzlq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtoylszxeu.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtwbwezavz.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtczjroczw.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtdjsautsk.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtahuwolrj.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtranhdras.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtunjfetag.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtikvqnnnu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtlsgulvgn.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtqhcwksnv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzgbdtox.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtdgvrxscl.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtslhxfqts.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gtrwciecqt.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gtbfgzjywa.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtgmvvxxzc.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtxzvvcyjm.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtcudevydh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtttgmlmbz.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtepbqxlze.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgpfxceh.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtmtetxlpm.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtixmhjzzm.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtlxnqgprm.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtahrjypow.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrekqztdl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtvjmgayfx.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtekwsowuh.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtokzpoboq.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfklwpco.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gtsaxvkeik.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtzgzeixmp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtrmtdoanv.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtnovuulkf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtixmmiycf.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtmoxdbnfi.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtiezbsqcf.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvnoifbp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtfhrwqxqe.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtsnxagxmb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtfnfhabxe.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtbpfhpcyu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtontytdpr.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtpoojmhsf.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gtqmumknvf.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtbyprbict.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtwabpkaon.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtnccdqtln.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtqbddppgc.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtkkawtcbv.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtcbrymlqq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtslqisylh.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtippffdaw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgjcxqyra.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtmzvgkrrl.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtrhmktsbp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtuarzgcqh.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtbacjdwqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtjuakihzm.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtqdqhclcc.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtmybkmrel.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gttrqebpor.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxxkuahn.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtznrzmkbr.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtekgsoaxj.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtrntcfmpa.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gteknsroia.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gtfvqdesde.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtaecxulgx.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtdcpcuzzn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtgiivbeft.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gthkpdkcue.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gteipsirgu.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtzgecijiu.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gttllfykqi.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtfxajicue.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfperyrvv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtublmejti.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gttvzdzkfv.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtlnxanatj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gturqlsxxo.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtmgupbonx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtplbpbqnm.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gthisatbmx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtqbcgatuq.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtgtchkypv.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gtllusuwpq.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gtjmvcbpdi.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gttaintegm.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtawcaxhkm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtlbdulijr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtesztfaqw.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtmzldtgwy.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtslvpimzx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtmridjaap.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gttyibvbpa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqrptmlc.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtlttcbrpn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtocntuxuu.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtgsoadfbr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtivyyliet.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gthmfebzgg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtuhowsouu.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtzyvlnbzr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gtnlzgapib.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtkaboqanm.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtztkxeudz.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtsvasxftm.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtjfyjayca.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvadpgaz.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtlekpaclv.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtwkaobccm.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtrvoklcae.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllxkgfhm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtznjceooj.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtjosocpxy.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtncbkkthp.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtztblbcib.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gtucnpdmxx.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtskwncesm.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvapsutvr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtfemyclps.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtrkeylhye.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gttgjopjsl.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtlmzxuflh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtrclgzujr.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtnkhhgqid.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gthpohantf.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtycsnpbvx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtalipfkqn.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtmlklaojr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtgqagcpcc.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtroualrwg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtjxplpybq.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtdewinerp.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtcftudxcm.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtmrygylib.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtbfqpotrs.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtlmgruyro.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsgcxzbj.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtcutoqoul.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gttrwwqyek.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtyxlqrzgp.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gttxmjazov.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gtujuqljgb.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtihdrdgff.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtuktniypv.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtabkoayug.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtxoqvihjs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtizvnsevw.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtsgnjbzho.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtfprnimzd.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtfffrsefx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gtnfzgvsqp.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtkyabqvxx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtwwcrlnmw.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtjeebxiia.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtecsyydpi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtzeicmlnv.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtqqqkwrij.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtctvjfhvp.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtkpkuunwr.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtdqzuxkft.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtxmrwkdjo.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtllxslfkd.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtyhgagzdi.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtnqjkatnv.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtymrdvgoo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqadphcsn.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gthzyevyvp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtpbrpdkts.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtzyesxgjj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtqnyyicrj.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtysnpiimj.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gttkfxgtkk.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtsjzcfhdj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtbytyqsoh.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtonfvhdfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtchoodcfb.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtdqkgypvq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtqqwqchgt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlopvmehy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtxruhorzf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjeoxiyfs.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtskopocyg.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtpbxinsdj.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gtjvfpwsyr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtneiatybl.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gtcppafuol.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gttstvaota.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtujjzwghw.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtgwpkclvk.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gtkrqqvezz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gttkzlauhm.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtrhtmcesb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtttyobikx.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtgtpzqhtq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtrxwplhtc.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtsphekvpi.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtvedoeevb.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtpuurcyyl.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtsehcgmcq.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtzwwuonno.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfejmnzrs.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gtmjxluioy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtoexrcbmu.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtsybmuexz.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtyqkckcht.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtjgzalrfk.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvxisfeoe.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtgkhdzrlu.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtamytzxlq.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtzangpyuk.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtjyselkiu.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtltsrkxhi.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtfihuboof.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gtjnqvtdvg.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtojobeyzu.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtkgqrlgku.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtkmvlvtfu.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslrlzzuk.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtbubzoiqk.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtdlitlciz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gtqgigadvo.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtsbgeuoih.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtdrciigmk.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtsingcrkd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gtxfsdyglt.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gthobpavhw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtakjdkhng.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtlhwxfltf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtlpactvaz.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gttbvhgvjh.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gttzmezfey.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gtiwjownjj.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtjjezwwai.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtlvxrohgj.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtzoouvzoj.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gteeirdfwm.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtekxhtasy.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gthzqvqdtq.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gtghxpszkr.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtpkjmaqjt.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtqanbslap.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gtvsxncbjj.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtoebvhawt.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtcwhomzkn.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gtxmbqnafl.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtenjtuomh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gtewrnvxje.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gthrwjqned.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtvbwielsz.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtanziwsny.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtzbbjdflr.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtklviljiu.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gtnjiescus.html


<!-- 参考信息 -->