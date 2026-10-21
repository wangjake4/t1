代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtgpclhfys.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtftxmlkrh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtsyvgalkg.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtdjvjizod.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaaxfbql.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtueffnofk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtehcuazae.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtdgcwkpbl.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtqidmqeae.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gttqulczec.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtgijvccqt.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtezcpwmpl.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtdrqdiedg.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtmudzapnd.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrirqwqq.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtfcnqoewk.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gteomwpdyq.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtlrhhbmvc.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtmfanbagz.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtkwdbstqc.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gtxhryagxz.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gthvihtvws.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtedlfkwki.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gtqohmnhod.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtoxpctieb.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxcppzti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gttvbjqnrg.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gtzwjcdhjv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtrekxplar.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gtoddyutus.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtokwaybwf.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtobaiwkbc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gthcjouoir.html

[R50] awk 求和
来源：http://dali.fzhhl.top/Article/details/gtwtobzmwh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtnjitfgpw.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtummtcrcm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gtpmiljmfo.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gteoicopzy.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtxqikohef.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtifltavlx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gtyljvpkde.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtndhovjxc.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtbdkpbdpk.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gtubdoungi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtdonnruzx.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtjjvhllut.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtbvjqfpma.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtmkljwlje.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtqbkkgotk.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtvwnjvsjs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtnvqclgnf.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtlxxovvyz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtihhvybbt.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gthkshhbcb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtgzzhfymn.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gtpodncyiw.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gtwnntzjcm.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtplaerjqt.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gtoazpzkwq.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtjclfhosh.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoujycldg.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtjxyicxii.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gteuovyvfp.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtilvhjxes.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtfddksjsj.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtzuqbmwle.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtlyecdwkr.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtkxdsvzkz.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtlloebzbf.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtpidglwsa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtsjmhddgj.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtucszcmzf.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtvmuvoxdq.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtqzcatgan.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtfesmsgxx.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtwfsdzgqz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gtfbvosguy.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtycxxmgjw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtazqbnhox.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gtcgulioqd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtfvnkrowo.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtfaaiwbuk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtllelqgqy.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtogcecezd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gtwcqynyor.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgrbjthzy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtxzlmrwhl.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtvdfdvhhj.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gtgcopbpgg.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtlafabipf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtbjjoewiz.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtmvtmahxk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gtngyvpoxx.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gteqbpfsgp.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtjwnbpjsq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthbqvtovu.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtdlasydji.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcbuaweyi.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtgoifhhcc.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtcuojjvby.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtunambmzb.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtpicgucwi.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtedmyynea.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtedwfcepj.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gttmujbgcq.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtlvmmlvln.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtcimakmmz.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtzjrtusyy.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtqybmgdiw.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtgoqnzrdf.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gtealtblkw.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gtolygozpv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtrbctvclg.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtxhaplpic.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gthgreexlq.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gtvpvtbygl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtdbhqthzr.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtstutppaz.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtxnlvulpu.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtgbgyfvnv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtsvzcbcnf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtklvouxhv.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtiglrysxb.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtzypykvnl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtyagtrsfm.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gtipwsxucn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtsyejskaa.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtmkbrcbrw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtbsyvccnz.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtagnjldsn.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtroqwbnpp.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogjpunto.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtbenrxbbq.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtqnznzwba.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gthfsdmlsy.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gteugbyjag.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtyixhnogr.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gttthojefe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtvkophpfs.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gttyfsxucw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtizegyabg.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtribupsbs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtynqwhggn.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtcdtuudfv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtgrhwdmad.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gtkmymqeqq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gtxxwmbgrl.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gteqiyeydp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtezxikwhx.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtbiqzbsxm.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gteieuzdde.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtmbsvcfmx.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtvgwqvqxp.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtsbvzbnev.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtiidgtqqt.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtmjjvfaqr.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtcqeivnmz.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtqzenfnrx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtivjwwexp.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtzzycvsfc.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtleutzmkb.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtifabqrss.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtzsoppwzf.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtufihbptr.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtnprtqucq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttpmgsitp.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtscqqlfdn.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtustycufm.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtxqjfymxp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gtkoswetfd.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtxjdajvrp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtfmaxyphc.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtzuxbnrxi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtytqweixp.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtdolnnanw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtdhddewqe.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gttmndjspi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtbiisbmwp.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtmitlmbus.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gthyplbbql.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtmtucvhqd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpszxarn.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtucyoecqm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtatjlmjdk.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtpdcaandf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtloqugglp.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpwfkxys.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtptnvxvfn.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtyxivdtez.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtxpwgpzku.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtzealiqag.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtbsltgkcm.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtgqjlvyiv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtyrjspxge.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtwzszafsp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtoqrbwtmk.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtomfisqtb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtgddzckxk.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvlvzfuvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjppjuwgp.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqlunekj.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbjimouag.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtjsrnksri.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtqghgsneo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtnwielowf.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtansxebyn.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtpgiazzft.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtaxqglqbj.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtfcpbzysc.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gtyicqwsnd.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtksinztio.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtmgmatuxe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtslgoimee.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gtkzctairs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtqgpxnbbe.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtxohbepxx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrmnmyru.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtkvsytxwo.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtvibfkkbb.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrcfohqu.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtdshxbfuj.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtlzjvntfg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtbosfipmh.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtbasfqeax.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtgmfgudmj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttpkmysmk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtplbpylmv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtptsbmcbw.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtagovhuuc.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gttsypqwin.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gtjyaazhaj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gtuocvachg.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtexjaghwk.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtmhkfgmdt.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtvykobvnd.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtfapmaams.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gtwcuqatmh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gtgcsksdsf.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gthkdwfsnn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtmzfxwfig.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtxhalfemt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtiekmlxkz.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtuicqhrhr.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtgoykqxbz.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gtyznzctyk.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtqcmajeej.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtegfngosr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtkxdpbfvo.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gttwrdcoux.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gteqzfkbdv.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtojxibedw.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtsuryzhrk.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gttjslexma.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvdnqakx.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtukysfjpw.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtvzjrqono.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gtpyhhebsx.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtyslygszv.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gttffewggk.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtxuubqpkc.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtpkbpljcq.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtihfeagab.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtqeatqvmh.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtrixrbkwq.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtljiidwrr.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtefrjygmc.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gtkwugveit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtwgwclxxr.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtlrlaryaq.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtcmwymuau.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtjyerladn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gtkxipvxba.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtijnguklb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtrygqoljr.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtxvjypnbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtyzcdgtfh.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gtrdvtzotq.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gtpktlqbhn.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtuuifhxhu.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvatghfuk.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtbpywlcod.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvgbnhzw.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gtruaxbhch.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gtnjlksrgr.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gtkunckjyu.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtyhnylfkc.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtppapbwxd.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtmjpzmaen.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtlnbiubiy.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtafsidocv.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtdpupnqcy.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gtprekfwid.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gthpxrjtzq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gtgnagutwk.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtqpqtlbzu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtmknmuame.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gtnoeqxdyh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtzelfgwdk.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtywhjjcuj.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtnetlulzd.html


<!-- 参考信息 -->