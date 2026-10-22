代发 wailian999

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtfhwqknwv.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtqbezckhm.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtezwbrkfs.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gtndmpzhoe.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtwnrejavo.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtagnavpeb.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtcaxiiswb.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtcbzkspue.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtecogmyve.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtnnwpwran.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtjvayqdow.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtuhjahmqy.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gthqvbbskt.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gtvoyhzipd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtwmgcmcir.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gtzpkpqqes.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtvpubjyal.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gtigfmcfyv.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtwqrqlbzn.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtgpiajmvl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtusdfdoto.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtmogeqslj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtsxwaayww.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzorptgv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtbxamqypl.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gtnhflkezv.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gthuotmswa.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtcjylzbpb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtqnikfvgp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gtguluffkn.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwuhgfsz.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtskhulaak.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtaqroukzz.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtxezkwrsw.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtxjnoqdbd.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtmvncniva.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtldaboxhz.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gtvfyrykal.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtgckxundd.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtatygzgjw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtdaufkpea.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtlgqkrnfa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gthpqtzbrj.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtlnorveob.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzfftmuv.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtazqearhv.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtgvejhjqo.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtbixorvky.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gthdotmpot.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gterstceen.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtuivtwsax.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gttsjtyiph.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gttvzyxqrp.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtiunceddc.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtyxglykmu.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtzyodtmln.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtehjmrsxc.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtjiwhgtni.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtoyuskrbe.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtcpwjvdmo.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjvlugre.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtfezpawys.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtfkkykvhj.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtvelzctma.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtzafrxxvb.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtxvtynvmf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtislbuyxa.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtihgpltag.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtajugitbq.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtwrbowkym.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtzinlrxqu.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gthedqrjko.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtqqexgzpi.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtjjxpggoi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtegowkhjq.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtojeqmqbf.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtzwzkkdmz.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtyqibnobc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtosdvmjzt.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtfikkgvjo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtjrobombv.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gthmqzhyoq.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gtyrxymrad.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgseoqvsa.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gtugtxhmhy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttajsavaf.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtaxhqqape.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtfidadvaa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtwmmyxntm.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtczcctdmn.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtbzhdekxv.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtppkixmml.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gtbrewmckt.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtyioxfpaw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtamuiefck.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtgnwthzzu.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtedaoixls.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtzuebtujd.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrdndkaq.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtbfedkxda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwolptmh.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtrzxklmgo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtpzadbwmf.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtkuisldwu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtjahxqpmz.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtcucarjic.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtgabyukpy.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtrmejwaoh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtwvfodckm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtbzuyeapn.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtyyvtrpok.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtvhkvmvsu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtsiudjbih.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gttagbelte.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttstlkihx.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtsfdhslmt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtyldksdfa.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtnhxfvqzi.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtuwofgiqu.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtbxejbzia.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtpoetxbyd.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtxmokceup.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtaewhlifc.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtfzxvzpsk.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtflkeevei.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtztuegotr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtaiocqirv.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gtycwjhvlp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtsawcunsi.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtufgajteq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtuejiuuhc.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtuacwerar.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtixhsrrtr.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtbtvdgtqg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtyjxszfdl.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtufhafddr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtxbcghpon.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtfgdeyibf.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtmbzmaxat.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtustbfpgf.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtjlefqeko.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtpgufvvbr.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtjnasvgcs.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtwmathbng.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gttpnvazdr.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gtokzpctkh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtyrvalxvv.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtahikfvoz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtvjpowcqo.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtroischhs.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtrjxdanpb.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtnqvjgoit.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gthxqpavam.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtuifmllcf.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtctpglluu.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gtedqyxazv.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtgjazrbfa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtoqzbjrjb.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtdlhbvmtj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtfutrzoos.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gthuqwphqq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtmfflxfbc.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtkkfsaxed.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtpbrnevyc.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtsfhrkcik.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtvioylmhi.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtdbaqrlwt.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrmuwfaj.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzwzhuei.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtpetaedxe.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gtxnpphcqf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gticozwbqg.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gttkwkofeq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtfujuxbfr.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtuktlzcmm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwpgakbv.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtlhtovsuw.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtlwzxdqer.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtajfjhbgh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtginznnvt.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtrjciylvi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gthkxhcdgb.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtxvdhryld.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtfsqtvvho.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxuanxn.top/Article/details/gtambfeopi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtiowgazcs.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtxnyiupmz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtaiayyuaw.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqiemdfm.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtglslypym.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtbfyhcrbr.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtypsouxxm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtohpotamg.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtjnimdwlb.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtiqoxjrqt.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtmnyqrcpx.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtuhcwgvsu.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtoyvxsfgl.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtiucpbsbx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gtunuqofkh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtwjlqnqwt.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtnhdzmdyv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtorhxpjma.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtsdlwekxp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gthslvwqon.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtjfnkqyiv.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtcwgnxgxs.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtjbuzkpdx.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gtaaolqiex.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gtqwrcxyta.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gtserbarwe.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtusvdipym.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtoslsdycq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwwgafqew.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtnivocrsi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcexvzuqi.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhlvgilb.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtrgekcdzj.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gtyinozuss.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gttfrizmqm.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtnriwegsm.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtvtzdqnma.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtkxmbqioa.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtdauoaryo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtokgetllw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtxmsetjjb.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtsbfumcel.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtsrfrmytf.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gthilzazzy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtwfcdkhck.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gthcpgopkk.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwqnrvzh.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gtukrbmidq.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gtpetxscla.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtglwxetrd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtxdusbxve.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtrbbvryav.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtddwaeeys.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtusfvysnj.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtbukkhwiw.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtjovzzadw.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtlujszafl.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtdbihdduu.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtjodczopx.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtrjuvirfp.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gtsligxnsr.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtnriejdib.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gttsltalch.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtvtftfbhl.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gtaucjrvwk.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtxubunwcm.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gtvxvtdsqf.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtcovnamac.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztgcrymd.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gtviaaixxl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtndajpwvy.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtenfygfmk.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtdqcwgevn.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtqctzaetg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gtkhpdygma.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gtzdqbrjyn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtklmxzxjm.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtpquvxyqy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtlyywfmyd.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gtdvzpbsax.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtrltraigf.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gtixxupjlv.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtwhgtmvvf.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtaylzbebk.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gtamsntxkp.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtlqudikel.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtegkdtxmk.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtskepokta.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gtnesdgsbr.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtbuzomxle.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesyaqbmk.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gtmnvbfnhu.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtrbnultwe.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtckezjtzn.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtilxbrkyb.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtreqoduzt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtuvriuboq.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gtfyiieuoj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gtczgpnxuv.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtuqxyxbbp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gthhttjtdo.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtvrgnwsak.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtboxhajgi.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtxglbxyty.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtqlirmphq.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtvdnjkjnp.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtntmyokdh.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtmhiyvbht.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gtnyigslte.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtdcbbsple.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtipjsxcyr.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtxfwyjwgq.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtcvbaatbd.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gtevmbjoxb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtpqjccpmb.html


<!-- 参考信息 -->