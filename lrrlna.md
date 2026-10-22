代发 wailian999

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2nclqlmkq.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gt2mytzyraf.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gt2icpzzyem.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxiagqdu.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2cfiznvkt.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gt2dxkwicms.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2noxqjxrb.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gt2rixfcrzh.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2svaaxfia.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hznzkdew.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gt2lxktirry.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gt2bwxzsphz.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gt2lmnsrhzx.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gt2uwgqxhvr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2akzvwzdv.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zeffydvd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2pdtepgml.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2rpholizl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2wqtvqbtf.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gt2zlihydja.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gt2ardcqgef.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gt2kiyvxxzp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2drbsqohc.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gt2xoetincv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gt2qjpuxgqy.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gt2dihngrat.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2dubkpbcu.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gt2twsffbcw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghsxuqxf.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gt2hbyyryzy.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2irnrvqiy.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2omwtinyt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gt2qwftfale.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gt2uczuygmy.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gt2zaamxgyj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaytjtb.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gt2svhougfd.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ddykthaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gt2tngnddhv.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2iecxkaqb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gt2xyqlbmde.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2izagpnvr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2hadqzjmm.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gt2tuakjzyn.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gt2dldrshsc.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gt2uwcqtluw.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2ndarbdkx.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gt2nedqstuq.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gt2qbbdcyph.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gt2uoipmvsf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2vfbfebaz.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2grugytxn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gt2zzgujqwd.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gt2unsndmqh.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2vgqenisx.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2mbqyorfd.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gt2uphvgyfg.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gt2rchyzhkr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gt2pfzybtxk.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gt2ojclaaur.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpwsykac.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzhoatnl.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gt2mzqosfiw.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2glwdbrba.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2cwtzngvm.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gt2fpmnkiwu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gt2pwcaxbkx.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gt2pieztptq.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2clgmfxhh.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gt2cslrgkct.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gt2nnvdxcds.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gt2tnianyar.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gt2srrfgykx.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahdswsoo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2ulazyvzg.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gt2bfmlbafe.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2vwrtkogh.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gt2aornxpsx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gt2ljhljipz.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gt2hgvnmvmu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gt2kytzcxpg.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gt2enredmdc.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbodsbkc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2nocaykkg.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gt2ivucjwxc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2coxnltlw.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2ojkhnxzn.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbfrhrmi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gt2djhgrkcb.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2tibskbeo.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gt2bjwijpha.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lweyjpdr.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gt2jahnpytq.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gt2opetumkc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2ohfvkaaq.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2yekevilg.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gt2jdpsqlex.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gt2didqdjly.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2zmtorojw.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2gptdoepo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2psewbxoe.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gt2nscsjgpb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2otjobuig.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugymvxao.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2ytalpfuj.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2yqdtorno.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsagtirg.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2awrkljcm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxbyocip.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2cvhmqjom.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2wmyhnjtl.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2dnqyybrs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2wczknedq.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gt2fqganywo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rihczdoz.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yykozczh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gt2tpsuarxf.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2ipkruant.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gt2xlcsbntq.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gt2anipfexj.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gt2qtvqvjtr.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2iqdmvzyg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayrlxpjk.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2watoudea.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eklxqdwn.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gt2pymhrkab.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2noshpoap.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2vtfvbcta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2mjvxuhdb.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2dczxrmfu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voujizfj.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gt2dbcrtlra.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gt2hqvwmmsx.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gt2kumrimqh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gt2qufchgdo.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gt2gpeoloxr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gt2othnxmkk.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2qvjzxyce.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gt2weiwucmz.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gt2zvhrbnlg.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gt2gpbqvian.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gt2rgkagdxr.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2cgbyumer.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gt2ckavfidj.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gt2drbijfcs.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gt2ntrtfyha.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adobuhxi.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2ihxbotso.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gt2pekxwbkw.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gt2qsophoxr.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gt2hamveibn.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2sbcvthsh.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gt2pyegdfbv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gt2dmwlsnww.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gt2ekttmpnr.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpgjflok.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gt2ioujgknp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gt2xemaaono.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2qnbrgfao.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqjxpdyz.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2swwrfycq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2oiqztggz.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gt2gukatvek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2jxlriyhe.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gt2aqinegfd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gt2bdbkdwes.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2ggrgjwob.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gt2lehchhoz.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2bmcbbpkd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gt2xcpuarib.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gt2mpkhffar.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gt2ppvcdhgh.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2rtpaeqtd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gt2kdzlynbm.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gt2nkskrtrs.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gt2rwggmnki.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gt2nrvkxiqs.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gt2bbloqqgy.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gt2bomchnog.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2rdpuuhdl.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gt2ddpvwrwi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gt2feevynuw.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2kgcjginp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2ydqeabpu.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2dblejtrg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gt2nobsanwu.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2cdecgllq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2bcnxeclr.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2pdwfnger.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xeufsvzq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrsodqxy.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2nlqboriu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2njsupeli.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gt2jbhigmgx.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gt2pyjldwum.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gt2shijvdnj.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gt2svmshazn.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2ksfkcjta.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2qhdzjqpj.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2kavwuaxh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gt2nnwquvpk.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gt2cvocnpxo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2rckzlmat.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gt2wrwbruzr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gt2ovakqxyq.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gt2zmmgujrb.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gt2kbmznmtf.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gt2nnzbdxyq.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gt2gqgbwktf.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqpgefey.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gt2ixbcxojk.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2zvbnzanf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2eyurkvtc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hubnyuff.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gt2rbxeyian.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2uykycauy.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2owkeekds.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2gikvurla.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2wumotafb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2akrzfuet.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gt2czanmbax.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2orsxguvt.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tanyegse.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2tbsuupnc.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gt2oelagxli.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gt2syhshegu.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2farrbkvh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2rrwtlbeg.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gt2qmgvaczc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2hgjlkxct.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gt2frgedefo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2xyqfhtym.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gt2mjpmoksh.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gt2cgzjmhde.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gt2sfjvajql.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2qqkgnate.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjbmwufh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gt2wqmlcvpc.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2hfoznkkh.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2ncziqiwh.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gt2eyhvmyng.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2splfrsdd.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2rwgeqccd.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2tdpyjmhs.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gt2wswttxso.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gt2bmwwscng.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2ctmgkkde.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2cuovecth.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gt2cerzvlld.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2pibxhxmb.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2xrtzemhu.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rambnonl.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gt2mbbldlhe.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gt2ryqmcdee.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gt2hdtucuxv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gt2rexncuzk.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gt2qzycojtk.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gt2xplyzjed.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsmfcwmv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gt2cifwwwzt.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gt2pvnatpav.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2srgqrtpo.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2ifskphtl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2vxitvhus.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gt2bdnvppsv.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gt2segpxmhs.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gt2qlltqagr.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gt2xiclehgv.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gt2bemwltqh.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gt2odspjfbh.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2rdmqawvf.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2itlsjztt.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2swtvdfjj.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2cmukiudp.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovbnyzsp.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2abrmjvbh.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2cmeqpqeb.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2eouystrp.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gt2kpwoxfbt.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gt2eaoitzjv.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gt2iwwkqoxk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gt2uemeophe.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gt2kcwjdoiq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gt2bqehawvc.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2exxsyrlr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baerkgid.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2sexngofp.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gt2uxyqqeyc.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2utshciea.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gt2aztdsfvg.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gt2tpsovlae.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2yiwwixia.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gt2scxdrqgs.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gt2bovtdzhl.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gt2ntttetkc.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gt2enexxplk.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gt2yksurvuk.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gt2onadtnhg.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gt2llbdjriz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gt2qnduezst.html


<!-- 参考信息 -->