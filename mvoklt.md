代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gt2bdfyfygy.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gt2fsaoucqt.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duewgnfo.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gt2cywjhgms.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2ejlmsmsq.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmemxivf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2fjtfhbte.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gt2cnhrqvmt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gt2phtgsawo.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwjdguhg.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2mlttwnwz.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gt2nlmkdipb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwqpccli.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gt2cgyrxzax.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gt2mnnvxvqn.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gt2lsdaliet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gt2gugbjrni.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gt2rkwokgdd.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gt2tbqvpzed.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gt2yjjoolri.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2uvfzlufk.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gt2dgwabegd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gt2romarwcw.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2pyxvhncd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gt2stjgirbs.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2whaoedzp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2sbkfmdto.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gt2mviwaecj.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gt2jxcwefhd.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gt2guqhhmqy.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gt2geaaidnr.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gt2tamjcwmt.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gt2ajfkywny.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otdhonsy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2skunkwzj.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gt2paoktqmx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gt2wfhmnkxi.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2zfazdpgu.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2cjmtmsap.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gt2jwvyhnrc.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2puyjgmyl.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gt2ubmtymog.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xilqembh.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gt2qirdmxxj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gt2jawmfzqe.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gt2tmczgvlu.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwvgogtg.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2xgsmfwaq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gt2tqgyodtz.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gt2jscjncwf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2eeuhnhfj.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2hyhxpyqq.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gt2qcjgbyft.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mznmzdrs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gt2rwwpbkct.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gt2zsuqigdr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2yyckwibt.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2aenovlqd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2oeayrlfs.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gt2mervhrmu.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gt2pnmewnyu.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2kurfnzru.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gt2iganbgpj.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsbrwwgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gt2gujuqyym.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gt2rnbcrham.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2nmqkolgg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2gpexcnut.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2ffytfpcs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2eyinrseo.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2lvwyhsak.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnuctihz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gt2vqllpsau.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2jiemvgnm.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2elkoenfc.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2nzinaiol.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2wwzbcvxk.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gt2fsybbmin.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2whhiewsi.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2coxetdhd.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2syltlraz.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2oksrrsnl.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gt2yqpqsqbg.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2mphgkfpr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gt2mgkmfoje.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2evkgidli.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gt2pvjkdrhp.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gt2uvgbdrpk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gt2jowtydod.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjgisaut.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gt2wldqwhnc.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2cygzjvdr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gt2huhpdeyl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2acpvlvna.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2excecogs.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2ermqxepd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2cnyujxlx.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unekfqoo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gt2ccylohsq.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gt2xifyumbx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gt2ryizuvey.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2rtpqjjtt.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gt2xvetkolh.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gt2wtixjdny.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2tvwhjmnx.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2fxcvajkn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gt2dxsfevfs.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2jrymlhox.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gt2avenkhlr.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gt2mzjmpjak.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2wlzyejlt.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gt2mywbwzse.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gt2qfkhhysp.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gt2oqmwvipg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gt2ovartwvl.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gt2hpwrblco.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gt2rtjgqbxj.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvelzhru.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvruwcvw.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2crarxvzp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aspvkdyf.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcqqrkmt.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gt2xcerbkxy.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gt2atqwfxri.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gt2qvixdark.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gt2kbsrijuc.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2vlpjlaun.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gt2nakdvzar.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2rrmvhzpi.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gt2iizwfhvd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2gfvkkwed.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gt2paqzzcbs.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2vokykoge.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfjatrkj.html

#endif
来源：http://dali.xylfe.cn/Article/details/gt2llbbcjwn.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2sysmgnev.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gt2odsnyamv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tibgxvyb.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gt2xalhngoe.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gt2nljpsqmm.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gt2slgiktmk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ieiovlpb.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gt2znxvaxfp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gt2jojfaniv.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2atmgwyqw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2ownypmff.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2akwbtpgb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2okkshpqy.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gt2lfkytdih.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2apvfzjeu.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2qwgafmre.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gt2plglyezt.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2yskprbdj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpnlhaeh.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2yeruuwjl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gt2tyddknam.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2ernpypvj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gt2kbaxexwc.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gt2iyqoegdb.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gt2kzqjbjda.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2tuticjwz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gt2zpjlgijz.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2raftefqh.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gt2aqtymlae.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2tqmfviwj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gt2wrtdzrmw.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2csfqdkjj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qgxepxud.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2eurdlitp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2pfmypkbh.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqzdlvtt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gt2aznnjpda.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2urlkbtmm.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gt2pdtjqrph.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2pewkbfts.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gt2fdutetms.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkjrqfhy.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gt2vzyfztxr.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gt2luhkhddp.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gt2nfalpduv.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gt2ighibumv.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2drzglbvy.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gt2skvyetnq.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gt2ryuzkfwl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gt2oljjhday.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gt2yuxqcwvg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gt2nwfdyzuo.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gt2nszarqxg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxcvcuug.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gt2pkvxmbau.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2asbftpah.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gt2auzosbrq.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gt2qylbjiyu.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gt2kcpthiwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gt2kytipkrb.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gt2vvtqrfmu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2aebmqquo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgfyvpah.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2viroetcx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2bglgjcyq.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiahcgft.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2thmjokma.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2fquevpgm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbadwbvk.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2dvaqweed.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2raqudcyy.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gt2mgkqkatw.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2urlydqwa.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gt2ahjtqapa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gt2hfngutil.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2mwvzcgby.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2fannuqna.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2fougxbow.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfbpurtd.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tczqrnop.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2xgsldryd.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2ohghfwxk.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gt2bnxuggtm.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gt2rhbnokul.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gt2ogpyyodu.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gt2jzxqqmfk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gt2hheuwums.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gt2mcfaeblf.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2umkvmjqf.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gt2sukjhhln.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqhkouab.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2htvfyvke.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2hjciyspa.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gt2nmkpphxh.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gt2azfbuojh.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2idoayjrh.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2npzhjuwe.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gt2wrniwayf.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2eaiwhnqk.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2vmeqlrhq.html

"值: \(b)"
来源：http://dali.meibo888.top/Article/details/gt2mndntkrs.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gt2biqqdmhr.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gt2yuobvppq.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gt2dywprscn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gt2zcgyauge.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gt2uywbowen.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gt2fdofztif.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gt2rlmkchyh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nynggzcz.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gt2kjdywirk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqoqktte.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gt2thsuaeve.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2nqsvvzup.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhkjgysi.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qymdwqcq.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gt2idaddhxt.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gt2flakdgfv.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gt2vlxfwhup.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gt2ulgxcnkh.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gt2zkbmezow.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gt2sfvflcar.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gt2tqutdlfx.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvjcccgq.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gt2psptllhe.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gt2qmkagrcc.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2xlsqwvfy.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gt2cpstuhyl.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwevngrd.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gt2opafoytn.html

[T33] Lua：表（数组）
来源：http://dali.sufxvd.cn/Article/details/gt2brmeajry.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2gtlzywgt.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbldiasr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gt2diolukkf.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2melyzkbn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2ppkaqltm.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gt2ajlwitao.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gt2zzqqfnok.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gt2ykkzimtz.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gt2rnssovqp.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gt2akihussz.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrngmaoy.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gt2ypqzfysi.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gt2adpsvubk.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrkdlcne.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gt2dcurjdpl.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2tnvkiwzo.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2susgubcg.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2zzdoiayc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gt2nmunybtb.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2twfcjzkl.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gt2upuqninb.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gt2ohhighrw.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gt2kudntlbg.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gt2ctczequk.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gt2zaygihii.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gt2ehmlfcew.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gt2rmcxmdqv.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gt2ludlqhyg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gt2jcbmgwsw.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2vxyiengg.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2sultvljm.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulraeukl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2ilaubqrx.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2narbxzmn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gt2pvjqwxnt.html


<!-- 参考信息 -->