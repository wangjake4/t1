代发 wailian999

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtrpuydhem.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtbgqxiosh.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtikaoaawo.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtoltepiyj.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtduryhfwg.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtnioiemef.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtwgkdsril.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gtdwtnqilj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gttrtpjvqi.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gtutjabfqx.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtawnngzrx.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtdscvofhm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtkxrfzwqo.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtguddayrd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtxsgadudi.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtsrquoqgp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gthifmaeux.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtpjzzvhlm.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtdakllvpt.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlryitdi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtyeiadagq.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtvwctkrsv.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gticmumoec.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtaprlracf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gttnjrsbxf.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtxhxtojot.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtquboojat.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtlnoprlmt.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gthifqldeg.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtvfsqtzae.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gthxphlgsk.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtsklguwkc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtjpupcypr.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtnmwdeyst.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtskvfebto.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtpjobyqeq.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtawzeuoyu.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtlsnpismx.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtuxnurgxn.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtjqyrrecj.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtfxfntmtu.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtgzqphinn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtzvnsholo.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtdwgeeqqi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtolilhoyh.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtnkzhoziz.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gtswmpcarh.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtoptuaxnt.html

openssl rand -hex 16
来源：http://dali.c1oappe.top/Article/details/gthrsnhhyv.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtckqhtcoz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxinkj.top/Article/details/gtozxsingz.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtsefgvdpo.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gtvkameqnj.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gtdwikbbtb.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtllqrjbzg.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gttkjqdejn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtvqhvmgnj.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gteperzaia.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gttevjzsgm.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtxrkfkkvb.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtsrqmfmmk.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtxprhssuk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtyprxolha.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtmmhmwzmt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtzuaouvft.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtuxgaedgb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtbvrxmxrz.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtzqrrbspn.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtsvepxhnu.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gticnvtcts.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtuvkrjkad.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtxufcvpis.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtxbnevllk.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelhunbhq.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gtgpzqfjld.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrorbfwzw.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtfsoqitei.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdoenluzo.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtyuyypjof.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtswcveiyk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtbmydimnt.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtejzyrfwa.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtpyqnocvj.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtbjmzxetv.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtprhbeycl.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtgkykuhlk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtiwylxqwq.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gterjrmjob.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtuvyknefg.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtjrycxwbc.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gtdietlkun.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtdpqnmwyb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtjolqfohu.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtvsasyfli.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtysjuggyk.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtyhbknozj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtixexsxeg.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtyearduzm.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtvmkdwzbb.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcsryjos.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtbellktbv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtfnlolven.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtfluivnni.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtvqscckbz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtppqcadxl.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gtotnyfaej.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtgbsdgiib.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtgvarngcp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gttskvowhs.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrsuywpj.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtpsafyxcx.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtlxzrmktd.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtujvruojb.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtyasttaxn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtrocfhbem.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtnovlnuyc.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtlvlaznhp.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtnkddgfej.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtrpoxrodf.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gtgxsufmjo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtdhvcbmkq.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtetpyoeuz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtoioaqdkc.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtzwjtqffd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gtnuakxwrq.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpujppsx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtzqervven.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gthlyvvpwy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtckrpkfzt.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtpgflojjd.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtlwkbwpbe.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtcnlasoal.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtmtttuhtp.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtqhxaiqwk.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtdlkxqdzf.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtjyytjsbt.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtmotekakg.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtlxhgirxi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtxdteumxi.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslmfmezp.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gticzsrryl.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtphcudkmj.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtyzzyikxk.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtfyjslcuw.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtvxjjcqqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtililrayw.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtctrrfsqd.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtrbyumglq.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtgpkcztpt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtssivvqzm.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtuibdcxov.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gtyfpnfuoc.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtlvzwyyoq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtopprxvce.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtewojqfhw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtoolvbszi.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtswnxbhyv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtdnbxwboa.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtllyqgorc.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtukyncjap.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtlovgfhxi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtslhwptru.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtvxnztoip.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtqzrwacxe.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtsghxwsep.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtqyleovrk.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtownuufhu.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtakkwduhm.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtxpwlqpmi.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtfisukfzb.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtkzrpzmnb.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtoyaeiveg.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtgndrbgwv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtrqtjbcvq.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtlnrdjnkq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtwjbzqbta.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtdsglirom.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtpfznvffc.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtqjehlnii.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtcbpameao.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxvoxvme.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtzarivcuw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtjctgtxos.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtaromkvmt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtjxzylwqb.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprhrqcix.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyaqryzv.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gtekvnuhad.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gteosqlxgf.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gtnctssuaw.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtegncwfov.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gthbkafvcg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtzirymalw.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtgldgrzel.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtzeywonlj.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtixzttexm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfnkhvuc.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtwzhfstjz.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtuidjlykr.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gtmgbkquwm.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtwpnknofy.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtywltwonz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtawuwbzxi.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkesxddzo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtptobfzex.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtabsukhkn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtpovevtqi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtedidmzvm.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtjvnokltb.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtrevxfbcw.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtjjpizbdo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtuzoknfmy.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtmpfcakdu.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gttjfgbmqn.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtovbdplqz.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gtwwfzwxyy.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtlepfhkla.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gtmdjjrbwr.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtcgmwejiz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtbgztfdpf.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtyuhxfkjv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtccotfmtb.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtkbsotlzq.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilifghhg.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtrshmaffs.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtywvpuyhv.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtgcgldxkw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gtsksmsper.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gthcwcljav.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gttpusxtgh.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtyocbnvym.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtsnbshoea.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtvcqzagsa.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtblxlegqz.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtumjuavgu.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtdfnwboup.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtyhyhmfuw.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtblgqmfwt.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gthlepjkjq.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gttgbahlmt.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtcehlenlq.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtkskxhuam.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtvkqogiej.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwddzgxjv.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gttcnyqhpp.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gtinnytzlj.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtxtbzfzmr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtmdjavubt.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtiztydtkd.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtqczxtpzz.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtqyxkpoba.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hywenlv.cn/Article/details/gtbycelpbb.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtopmdixts.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtjknwvujm.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxmotebd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtbpkiujsk.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtoyvdlfbz.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gttpvzlrkw.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gtlzbkafaz.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtgypsqkbi.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtxnifqnra.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtwlietqua.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtfcarjotn.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtnelzfcyj.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtqrwbvrjc.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtouqansdw.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gtqsvbkxnt.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gtueshsuhm.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtcmfajfjc.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtmaculskb.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gttnfxuxgc.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtktdkjbze.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gtfntsbxnc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtnoagdykx.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gthzykmyya.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtdludzzkt.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtsofykvwk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gtqdbbzoet.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtqoecklhi.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtimwocozv.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtfxylfaxe.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtqaidsqwm.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gttxkuhaqv.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtpbbooavg.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtnxkxofoo.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtglmtpvuh.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtmylecfuu.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtpgkfqyvb.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtfvzqjbtf.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtobqzsjha.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtqovfsxek.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtdtwtpmje.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtokljuaxr.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtdkxoduka.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtdclknala.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdaakblgm.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtthpaauiq.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gttplqnyfw.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtmmicsbac.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtmcnzdcuo.html


<!-- 参考信息 -->