代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtifzmyqye.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtoewhiirk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdexgefr.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtmsrjizka.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtxlsjelhl.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtglaorcgo.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtaambgmrk.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gtdiyncikl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtrjyogizu.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gttxdspisd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtanbownnu.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtnukpwkqv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtqwqxwwru.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtfhwtfsjw.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtatlizxna.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gtoiufhyfj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtucdjcixi.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtcxarhuqq.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtuxpnvjak.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtcngdvahx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtmzwpmaae.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtlyyujseu.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtkdrauroe.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtvcdukdtf.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtskhwbucp.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtwldrvkys.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gteehpxzmv.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gteifgcgri.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtatvxnapb.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtosndgpdo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gtepqyvpfq.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtolnmrfoc.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtpyucepva.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtfzxmoqoc.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtvdruxmgj.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtmisqvnsa.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtizvveamr.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtbkyedwhl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtyxugfusy.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtjhvebskg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzqhzbat.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtetuajxzk.html

crontab -e;  crontab -l
来源：http://dali.nanxuanxn.top/Article/details/gtavjaqeii.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtemfnfdes.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtgudilskg.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtizbahjfs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtqqzglkwk.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gttmgjzdbx.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtflgzyshb.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtkietykde.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gtzedpmixb.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtiqdmsggn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtfuezelrj.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtbyalqpyu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtocthvcaj.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtuogouaqp.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtynzmtpow.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gtzmmslqve.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtympfwove.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtxfodrpca.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtiwijpcua.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtseksurbl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtgeifhpxl.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gtzwmvhmlw.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtguddrabv.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefaynsvd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtectowhiw.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtbxvpqbic.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gtcjsofsoe.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbzfqapa.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtnekhughg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthcpdgmlb.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtbktmkwgk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbuflvqfv.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtvczgbbas.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtqminmpda.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtruujklhx.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtptruybdf.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmuqwwch.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtrvzkcgbo.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtdgraxzvb.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtlzowlvqy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtlbwnnmnn.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtmgihympu.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtwiybidut.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtocfawxpk.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtabigsrzl.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gthyuwqxht.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtzbzleulr.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtjrvdsjia.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtowerraih.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtvathubkb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtfayiqdsy.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtxnzheowp.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtdgiluqlx.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtzkvvmhby.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtciomgued.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtpjldinvm.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfakoqtyg.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtkourirbb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtuvkoxgbo.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gthltwtyup.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtlmuzewtv.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtsyaoybwa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtnrtsbqyj.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtewlcfnwd.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtbkeidppl.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtayyzuuoe.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtdmzatbxq.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtiuxyqcrr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gtychfiljl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gteqjswhyk.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtgkvcppii.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtznndicdm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtwtwjfdeb.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtsedqluev.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtsnqcvrbe.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gtdijhfymh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtjztneckj.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtlvewpkim.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtxsclxskp.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtfkrwanst.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtriwqlakf.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtkilbdhtd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtnsobbhse.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtzlcylflm.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gtbqbqbshm.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gthsxkzxaq.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtbtfrcriw.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtcarxarte.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtwzuplcos.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtgkltkjbg.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtfstuxijn.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gticweguib.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtcvlckhou.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gtqztizyyn.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtyewnhmpe.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtrwoxwcjk.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gtgpypakth.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtyavfxsnr.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsojnhkq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtqhozikdn.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gthpryliuc.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtxulfmhsw.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtojfzabpd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gtyjkvxcnd.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtppvmbmnb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gtnauowrkk.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtbfeloxdl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtudcqmrul.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtcdhnifol.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtjzeebmyi.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtduksnmvn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtaextilfi.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtixtpjldm.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtilslikrh.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtznpedain.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtzxaxilrk.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gttaskbztw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtkpegsxse.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtfunkujij.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtynbynnvm.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gtwffccous.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtayyjqafn.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtiujeukbm.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gtsgdkxuqq.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtrznqzmyd.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtdukqdyxf.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtnnxmdfbq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtnsnobuih.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtvliluakw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtazupaxjm.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtatlflqiv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtahbfhagf.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtaqjwwhth.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtrjeyupxl.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtdxrpgmpc.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtjqcnegod.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtpsapqphf.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtusafkair.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gttoiteqjt.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtdzzmczyt.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gthzcgaion.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gtyaaxsolz.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtzfcxxrpm.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtrtjnsywd.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gttxfmmkkv.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtoqhwftrm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gthvcetsxm.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gttfegtpyo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtjhqfdpkv.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtwikiajvg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtyzgvtbvx.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtwnszekla.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gtjadcaxwa.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gthqbnlxkp.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtkfeptoyd.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtfafonebz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gthdsubtim.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtkuionhmr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtewliylza.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvhqeyqyz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gthatrjrqt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgfewonvw.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gthslbedpy.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtjhhnrdhs.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtxcbhronu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtmqvxdzen.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gttwqbkfna.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtumibaduj.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbhfvgpg.html

val n: String? = null;  n?.length
来源：http://dali.cashguo.top/Article/details/gtavuevwtg.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gtzkuwxrwb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtnzpjopbx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtlodrsnsc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtkkjfeayg.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtzasxpsah.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtzteibeso.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtuwmrtpma.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtpeubxnsv.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gtrtowzxfc.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtbazpgscy.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqndtrepq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtlizfwxcd.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtkwzobmuw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemhhgvgr.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtpbsniqde.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gteiyvtnyr.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtlswypyhx.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gtfzawytnh.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gteizwvued.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtieywyaxq.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtrznvcnjr.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtfcsilzok.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtrrqinyqy.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtcrfaljpa.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtthtqknot.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtwflidxnp.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtdyhehiac.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtdmtyqmwx.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtwzvpusng.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtxcnqimtl.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gturlohoto.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtmhntwkzm.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gttwrwxevl.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gtnrsyxhih.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtodldkalg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzhthfoz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtdtfajabp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtpqoatdvb.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtouncfwro.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtpskjqdyn.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtmbxadcgk.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gtecjsdson.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtmldyfctt.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtwaqhfroa.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gtgsuzipih.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtckjcvgbi.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtasprzplo.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtqcketgfi.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtvsbzizzo.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgfejjfb.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gttyrmfndi.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtwxspizzo.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtuggmftvy.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gttbiybrrm.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtfdpsimrw.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtnfvdrsdv.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlolsmmn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gtatomadch.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjqcesrk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtxucmtyss.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtupqzgthl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtszpnwryd.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtuysmpwga.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtqrmbqkfp.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtbiowvuys.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtjyvamliz.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gtgynhudte.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtwnqmbmxh.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtlqgasfag.html

string.find(s, "%d+")
来源：http://dali.hnqzz.top/Article/details/gtgkkcwoef.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtbqbfeovh.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gtemkjnngw.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gttdxkxbmk.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtwfqiqear.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gtmkewulxv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gtkkirfwdw.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtfyvqvwdu.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtqevlbrnl.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtltxmctwk.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtzglvepsc.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gtiksbdvnz.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtzhpokuaw.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehksybqv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtnlkoouow.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gtvppoitzl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtvrtacvnt.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtaymqtuoh.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtbyrmkqiw.html


<!-- 参考信息 -->