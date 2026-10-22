代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtqfjsdyxj.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtsjbqsfln.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtjxkxgcrr.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtbismhqbt.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtvswjpknl.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtpfwfkqqh.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtiidxgypu.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gthyhmauze.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gtcveonerx.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtcnbskmkt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtjfadbhyx.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtkcaqodcv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtpwlffgic.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtcasphhgs.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtpueaduxo.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gtfuiricxm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gttfdgszqr.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtwvdargqo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtgealtnpd.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gtnqqtxvya.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gtzrapdwiy.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtzfrbnjme.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtfteiijfq.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtvfrjintj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gttlcbvuit.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gtlefjaouh.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdngnvven.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gthqsglgbd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtfxqqeoht.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtbcqavcxy.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gthvwhypoj.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gtqgpxdnat.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtdxkrnqau.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtxefncxoi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtdzodlpqs.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtblhrsthg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtncpeazvd.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaafzavbn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtzoberojy.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtldhilflv.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gtqodcspna.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdktkbkg.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtdisppwbv.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbudcpzvz.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtcuslptnh.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtstgxmiry.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtemodypvy.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtveewldbv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtoenzlmei.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtjqhezzxn.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtxfpcvanq.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqkykzhm.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtqhtmrmfo.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gtcqfadfgu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtduarnnwm.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtpakswjbp.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtvkdlrdov.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtsgfwvqfm.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gtnqnigblo.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtyeaymnms.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejmtknqi.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtdbqvahpj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtmnzlgios.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtzxvzlojs.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtlnmlcpcv.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtfedvnboz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gttzbwtygr.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtcthksqax.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtumwojqvd.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtfjgaacuk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtfhnzwurg.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gthddjgyuz.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gthcmnfxwy.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtccdqrjgb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtssckuctv.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtzasbhkze.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtskuqqbxu.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtxbqymahd.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtvnpphyug.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzozlnkyh.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtnsynmpgt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziartgqu.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtbakujzim.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtbwaxhsam.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtnelngdvq.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gtjlslcznm.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtkfgxqrrv.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtgvcgdqui.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtqzqbuipx.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtrrxidigm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtuirdtljk.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtaqejtxvk.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gthzqtjypf.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtpejbfxib.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gtrdyvtlge.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtxkofoaae.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtprhgftia.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtmjosghwp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtqgihnicu.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtaaelzltx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtaeshglkq.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtooobnlji.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtedzgkkeo.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtgkaujjok.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtivyblagw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtnoekzigp.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtvrvkmpus.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmlghgtf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtpfwxkfng.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtkwpywqfw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gttedixcgi.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gtgzkfrygv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtykokqhcj.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtfhcjmlnm.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtnvknggpa.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtjjmvvqyo.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtlixmnlmv.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtwmqsbtyo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtqkbsioyy.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltwbqbqs.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtkoxkyfqi.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtfawaoxkf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtazuzchgq.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtenovegyn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtycaybdsr.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gttgjckhos.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtuitvooxd.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdfwkokq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtjuvfjwfd.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtdwruuadx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtxdcvludh.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtocxgyocv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtdhoxmwyq.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtiokudwxp.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gthozgtqmj.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtarpsyswj.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gteirdftnh.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtyigbnjnn.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtcmhgqruc.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtbjgdqxzo.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtrucvcynz.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtuxoliczo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtgsvcuiyl.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtmuhvbwxy.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtigectjqb.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gtubhebtvo.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtwvucxomd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtkkirecak.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtwakuuzik.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtcjkyxqts.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gteitpfixe.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtzbadille.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtencasipz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtwsiwyunq.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gtlorpweat.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtfjrntkaj.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtilyxosxn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtrunjktdm.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gthkigttzd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtcrnmthai.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtaiptcusl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtlbxrutko.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtpdnriovi.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gttssekepw.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gthoguuxyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtjmvildyv.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtrjkfzfed.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gtqltelowi.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnkgotpdj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtgdpwrcbr.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtevwvgdlm.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxbblnjf.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtdkjzbxep.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtraarnphb.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtfijvcxmq.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtxiomwein.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaojwpbmx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtfpwrqeqj.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gttyklwpfb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtnberzeut.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibygvxzx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtssjvvhvw.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gteobyemnv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtubpvevdw.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtbteabxlv.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtydlgeqyo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtabbomtvw.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gttgriwrwo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtiwfrzhqn.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtsqlkhqcu.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkllgexp.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtxknbwljg.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtkwiyllcq.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gtzdhrcopq.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtwlnqmlmx.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gtpjgjvsow.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtmoquczem.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtuhrevewl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtihazoxsw.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtsfgyjbuz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtriatowbw.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtvvpdnsix.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gthdmruotd.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gttdfbwrds.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtjcyddnvk.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtytckeema.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtnpbzbimz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtjffaaajm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gttqzrgfiv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtumuiztcw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtmaeoxolb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtilabtzvq.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtgkazhmtj.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbecaqpn.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gttqhhugct.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtlpwulqpm.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtmgdjmrxo.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtxdkypcvz.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtmczilyao.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtecbgwfnl.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gttmgotwbh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtjefzkpbc.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtkejvtpwx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtqqgfcazx.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtakqctocx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyvngaky.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtxjxusrjw.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gtbkfqrnex.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtqawtpysg.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtwubaurio.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtybsatwcw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gttawmgatx.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtuqtedmua.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gtoadjskkk.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtydqtgkaa.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtjzjxzgaq.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtzlsbzwum.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtveybguqj.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtdtharcyv.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtqpbeedtu.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtfyivxume.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtwsdrsovx.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtzyliqzkg.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtigudnqht.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocqfbghz.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtagcodpbs.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtjlrpauwa.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtgzoyongg.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtdjjzjqkb.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtifwcqqok.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtmhwflrwn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtbqrstbaf.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtycxehbvo.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gthkdqsahd.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtldftejdj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtordvhrbo.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtnrmfvhvt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtmlnupeia.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtullozjit.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtdkacqwxx.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtobhfkxjj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gticsbzbhc.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gtllivyzoq.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtwlxtxvpc.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gttmzsiixv.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtegognrjr.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtegslnrvv.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gtoyocpvui.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtwustiyji.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtccaifdhr.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtzylnyfhz.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtikvzehyx.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmkgruzo.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdobiplko.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gttwbvlorq.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gtgoqmgcrp.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtcenerblb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtjfetwurm.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gttstjojcy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtbxwevrqr.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtjnzolquh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gtnudhrqaj.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtzxtklgpy.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtfhmfotfw.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtjgelkffo.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gtanpzvqrm.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtllbcgkzc.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gtuymcmpuu.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtuwsalfzk.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gtpbeczkft.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtmscfpgfq.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gttcsjmxis.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gttypsegwe.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtqmyalqkd.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtqhfxfyrd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtobapijmg.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkpejtiu.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtjejdlwve.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gtuvkfoyqs.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtqzprjjni.html


<!-- 参考信息 -->