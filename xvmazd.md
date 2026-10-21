代发 wailian999

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtvwkjlikh.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gtujacgdvz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtdlsufcpb.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtumsrpmzf.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtovdoapta.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtxdgvqhin.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtzfggzxow.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtbruwwtvm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtskzfxjqa.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gtnaxjeyzw.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtumwvxryw.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxcasxxw.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtsxpxemmv.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gtnzffsznv.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtoawmqbkk.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtojgufktp.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtdguvycjr.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gttyrztlof.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtarcdvwan.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtggtpvlim.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gthiqntbba.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtewafxefl.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtsbnuymsn.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtzboywmok.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gtvlukaely.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtiygxjgyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtoifpguxi.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtmjgwqiik.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtcyyzmbzh.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gthuvsvvgg.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtuvsdurxa.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gttgpqgmwh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvrdbsps.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtihehdgcw.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtghtgysnk.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gthusbsfar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyvjfqst.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtbubvsnoa.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtgulciysz.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtbsijeawe.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gtodieeasu.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gtztblkvmf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtvkqdvwum.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtnjefipfj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtbdddfqij.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtbrsbgjmj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtvhyxeoyp.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtoqxsstok.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gterptbxqe.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjujxsnl.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtcuigkwhi.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtgioulsje.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtoozujyll.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtgjrvucgl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gteshfdpdp.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtdumxvddw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtsdhrjztw.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtmfqzieww.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtzgedmxlb.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtlhjgzoku.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtnwcnadeo.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtdhjxeacz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtunjkyvrg.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gtmrdukvly.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtslpfsszh.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtswcwiitf.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtllsdflvl.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtpxrpaixo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gtizqkmhei.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtmsujhtfm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtqgehcesj.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtuuxbyykd.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtqpalcbya.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gttbzzonue.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtaklvukvn.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtfqpkxrsq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gtmfrvcqkz.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtzjmyjyik.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtioohckwb.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjoyzzff.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtmpehonay.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtlgtdhdye.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gtgbwbijmw.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gtiufdprne.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gtzefpvrzi.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtmtdtchjo.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtzilegbof.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxazscdtn.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtagvdlpks.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrajxmuuf.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtvlrpjwbp.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gtywqrocnu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtympjstyr.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtfgqiuvfy.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtkytxbhwh.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtdrxpjcxn.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtnubhuajf.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtykueercq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtuaykezmp.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtixirjjyu.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtwzflukqs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtaqlatawi.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkwkbvyx.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtyfjrqdfn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtlrjngdyo.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtgtofbgmb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtzlbtqysw.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtazzatxio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtdphxykjb.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtbzserbvm.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtibjgfiur.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtovvnwuua.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtimlgiezp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtixioilew.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtqxjgkrtk.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtvyhtudjg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtfdlacydf.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeppctpx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtytysoeem.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtuwmsgwsy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtokmmxtgy.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtpdaurgpj.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtnqjaybma.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtkffrcqdk.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gthfgzlcyi.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtxggzygvb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtirpuiklb.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtxuztltrf.html

int main(int argc, char **argv)
来源：http://dali.yuxming.cn/Article/details/gtauncgwzl.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtpfwudfuf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtdvhdxvje.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtygsmkduq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtpaieqqpu.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtfydbutma.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtwyarbolo.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtkncqvgsg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtwvldxgpk.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtumyorglo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtxckywerp.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gtjvskcpwz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtjmtajkxv.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyicztaoc.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtidsizcnu.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtcilqpalk.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbuskxsf.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtfgscgnje.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtlzvkfbsy.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtdzcmqwww.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtoqndvrmx.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtfwizimdj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtzpqbmngo.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtrghuzbtu.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtxokptefh.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtdxnjzgyq.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtqxdgkgdr.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtotarrkds.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gtgeuypxje.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtxkgywxbz.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtdwkjrkbz.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtadxpflfn.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtcggtvnan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gtvxrsdrem.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtalthqbpc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtgijkcygf.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtipfvnprj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gteaksimko.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtzjwxhisk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtawlnpmcp.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtrermvzph.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtcreuayef.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtjirhlvct.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtnpcaxviy.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gtonwnotvs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtcfxsnjmc.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gttgaopgpu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtsmkoeybe.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtfxpplmxs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gttjzsreyu.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gtqiacsqrd.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gthrevdfrm.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtmsstacba.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtjbrxophz.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtffkouroj.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtgkjbarvq.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtejnuqstl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtfdsmifdi.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtuzhelibz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtzbemgsqy.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtzfaglkqu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtajjeoxks.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtjlqunyui.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtxxykvxak.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtsmmasxig.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtfrvxwocy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtmkslhapn.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gtovcomlgu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtlqhqtify.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtwcwmyfob.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtdbbxohxi.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtmmecqgse.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtcaylfcyk.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtcbbttqts.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtvsmfysnb.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtsapqqtym.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtwrwbunbn.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtstvzhygz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtoovxpdyq.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gthxfzciuj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtlnouwtsy.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtvfepejkz.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gtbspowknv.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtlxcvlvda.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gtqsxumznd.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtjrwhwfof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtrukhakil.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gtaigavuqt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtxshrdtxt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwzzwfmli.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtuiwrpinh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtoryhnwtp.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpduyaout.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtlryanxkn.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtzkjkplur.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtmacspril.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtoaaogjnd.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtumwxutep.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtmqsdkbex.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtahzevgaj.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gtbfyymkcg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtrsknsynp.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyeagtma.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtdotuwgby.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtjplifzmc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gtqpxafqqs.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtmzpormfo.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtrehzcliq.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtvvtcvixf.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtjihbufmo.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gtyzqugwsw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtahndtakm.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtewdmmzkg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtixihqlsl.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gthsmarovj.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtzdqopotz.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtzradldle.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtmfdqcpkm.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtvfgfggel.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtsozktxaa.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gtgwxntttm.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtjfcasdbn.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtlvhgquqw.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtpgsjmagt.html

[T17] Swift：变量与常量
来源：http://dali.zhiwuduotai.top/Article/details/gttdkfnirf.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtmkhdmjys.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvdurooz.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gthjlejldi.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gthpmolcfc.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtbfdhldcb.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtaathmnek.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gteomxvjym.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtvchgoocz.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gtrsknhsot.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gtczrgdarw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gthztjcuqs.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtoglqvepf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknpwlvqc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gthpbkbmnl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtokgtwurj.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtzxcdndis.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtaqsislxk.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtsqmkbvot.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtxpjanicr.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtgdseoamr.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtwypwyxmi.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwwoftez.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtsxropsiw.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gthuinscbb.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gtpgdyzglg.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gtrztiampl.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gtyoamjgwh.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gtkcgzkvxq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtrejumlod.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtuzlmkysr.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gtxtetowqj.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtmnqrvpfu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtjiaedigk.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtrxqwywvf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtpdmashoc.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtdcefznzy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gternigxpr.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtervuksvg.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtgsdbwpop.html

[T37] Lua：字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtkfupevjf.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtzoegrlqr.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtcroqxici.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtdtxvjbsw.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtkadxzqrm.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtmwtpzudy.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtxpijmdiz.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gttendduie.html


<!-- 参考信息 -->