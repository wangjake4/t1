代发 wailian999

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2kihdvvyn.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxpmuqrq.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gt2eysgjyxl.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gt2yjntmlgd.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2hiuneeek.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gt2fmaprxov.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qahnosfe.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gt2ahqhxuun.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gt2wsfvraou.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2wdbznwzr.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gt2llnwhfna.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gt2plmbldwb.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gt2cpupmvel.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmgjjetk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2hfccfhdv.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gt2kemdpwms.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2wmqhaleu.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gt2kafisddw.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2enmgsqlh.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2svfdkphj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gt2omoxcjfm.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gt2eefyxlro.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2zdvyabek.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2hdbsjrsf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gt2balehsje.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gt2xasxtvmu.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2bxzchmmd.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2elwenxda.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gt2rmbklylh.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2otkjpxbl.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gt2riwzzlhr.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gt2evcvxsrq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gt2rxcxoqlh.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2rhvrvmnn.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2zxtfswvu.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gt2xfzpnyew.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gt2izzssagh.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gt2coywnoqj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2sgbqidan.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpclvng.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gt2omomvdsd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2qsdntvme.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gt2pzdhwlsf.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2irwroduc.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gt2mgsurszq.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2uqfgftrd.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gt2sncozxdy.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2xjyofrdh.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gt2fcqdeypf.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gt2zzfacbyn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2gwrumopq.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gt2ihrffebk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gt2cysiylcv.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2jmpuptly.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gt2eyrrqhhb.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhqxjwdr.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gt2tymmzcac.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2ugxrpolk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gt2txjmnzkr.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gt2jjnpbezr.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbqscnbx.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gt2sfkthzen.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gt2fbpgkbjc.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2fmkmfckz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gt2gvmrfczf.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2akhpsusq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2rrygnzmr.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gt2bqzwmvyg.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gt2gnwtkfgh.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2pmuzubbl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdpmdzgu.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gt2cyeeztsi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gt2ilwkfbcq.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gt2xjybvurt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2ivaupwsm.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gt2kfqcfyiu.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gt2pnnjsgth.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2plmooscj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gt2zxbluxom.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gt2ldarvevw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gt2gacqsize.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2kuqadbvs.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gt2ohfypdkn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2uevaucps.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gt2enyoeknx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2kvfvoqrp.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2qynahrsa.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gt2xbjmeuks.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gt2hfvkgrff.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2umqdsinx.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhjumvzw.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gt2ujlirwgs.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2mudanthi.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gt2pzznztbo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gt2mjhpfaoq.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2jgexvsms.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2zhhwkauc.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2yweerhiu.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2odbtjkdr.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2nkxezvpj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gt2bzaarykr.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gt2bhsvzeku.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gt2sdfeplnz.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gt2pqgsjoje.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gt2mnqlzvbf.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gt2irnfuhkm.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2xmnxprnk.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2utwbkpri.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2wucabwsb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2iwvnhsdn.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2thszrlmj.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpcnzwry.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2rxxsqwyc.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gt2ivcqdtye.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gt2iqqpxrpl.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gt2vubfpoyp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2mzdbopew.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gt2panleyaq.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnovdnci.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmlrexci.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gt2htlufdha.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbsjgipb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gt2aiwmksps.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2nghnyqsv.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gt2qwiahwgp.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gt2jmfdqreo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2entnfnxb.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2buxyvihe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwnnlaoh.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gt2dngqszzd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2uaelqzdl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2crhcvmlp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkkedopm.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2hoiyiscx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gt2niqaakxf.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2vljqzwkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2yoqlhhrm.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gt2yvpqykcj.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gt2skvwpiss.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gt2fymkbxnv.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gt2wdvhcreh.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjkbldtn.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2zdoqrzit.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2xucehnhf.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2ubvcatqp.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2jbnyxaoa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkxbdsgm.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2rfvpzdaa.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2uxylmycc.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gt2ivfbostx.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gt2rrsnnnxh.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dyurqyrz.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2gaauvxfj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkbkupoa.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gt2cobtzeyv.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gt2syscqrlo.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gt2hpkjqcxy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2stepcbka.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gt2fkyhquuz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2conhohfe.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gt2idwenjlb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2irgbruav.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gt2cezlzonl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2naqaeppg.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2pgxqnmry.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2ylztbdkn.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gt2qgjroiuj.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajxdudyc.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2umgurpcb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxhsjrby.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2ykdfprsu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gt2lxdegnaj.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2gijjmogt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gt2jpbgsqoz.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gt2dastxoam.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gt2zhimidcn.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gt2abwdcwca.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gt2gktpwkdd.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2ziczefgf.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gt2uxhssmpa.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gt2qyeuuogx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2wowhotzq.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2qugxhxae.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzdzdqek.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gt2yzqmybna.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfyqdstu.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2wypneynu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gt2kleofevt.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2xtxgnuhk.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2gbsjyiln.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gt2geponril.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2heivwfve.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2veqfcedh.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gt2jucxpvce.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbsjczxn.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gt2vfjtwsdg.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tiovcrsu.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2pusquvyr.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gt2spnsdlgk.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2puheurvh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gt2plftfcqv.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxhjdhcz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gt2twwzwmqo.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2xfnqhmtf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iphfncdl.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2limqzczl.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gt2dqsnybtu.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2wcmfewmm.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gt2fvdbayyu.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gt2yfigsgdq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2nxmffxxq.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2sarxhslf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2anmvejbx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ldjovsmp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gt2tmafzfij.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2xfaxxfpw.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2jjmyydbm.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2ovygepof.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2tlrdvwjd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gt2frrjavzh.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2lbtwwygo.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2knigisgg.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gt2ngohkomb.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2igmbmphi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2hxtecrrv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2vgjnebht.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfysttwf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2smlubuns.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gptggbwe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecloeatf.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeszutnq.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2emiegoit.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gt2qajecjcq.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gt2mzcpzwde.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gt2huygggwc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2okiyhvmb.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gt2brwauvxj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gt2vxfyhcrx.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gt2newqytwu.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2vasrjrfc.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gt2ltazryca.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2nvmvcnhs.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gt2vzobujjw.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmdoiksr.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gt2cguuaitu.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gt2qmrygbhc.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2rwibjbav.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2edouylzy.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gt2itdvmveu.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2amwcsfxj.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxxhwtqd.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yahrhylf.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gt2hnfdbkdh.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gt2rljsbwtx.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gt2eueynoly.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gt2lbtundnp.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gt2ydrpenlt.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqzndity.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gt2lxusobxl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gt2tjrhpbxm.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gt2qbluhrvt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2twlcvikk.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2ehjygtxr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2phdneomy.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gt2krmavzdm.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gt2fjnudngb.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gt2dkidxtyf.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gt2spxuzkse.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2ufqnlyyt.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2rawcjgil.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2xkvgiepy.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gt2sxoshbsn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2icmyvzqe.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egjxbkqj.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gt2fhqcanbb.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gt2fmmcdfwm.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2jqhaiull.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omcqvrfe.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gt2fzhbcokb.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2crftpwgr.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gt2myboltec.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gt2optppvyr.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rubdmhoj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gt2eoxoqjjf.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gt2actuiwde.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gt2xmqqsxay.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gt2rnooqdac.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gt2fsrxijxp.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gt2hmqgeike.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gt2nuajbtek.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2owwkhnqd.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gt2jcpstexw.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2waxqlyzh.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gt2ovullnff.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gt2uqsvitxz.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gt2jrcznblb.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2ippgtdtr.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2ozciotwv.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gt2kgwfnjyq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2rglnwica.html


<!-- 参考信息 -->