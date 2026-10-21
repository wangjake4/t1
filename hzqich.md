代发 wailian999

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gtqnuqxxbi.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtdcazsysz.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gttmgcpysf.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gtnyooimld.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gtglbmgxfl.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtemifeljc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtqrxqqcrm.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gtqhemistm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtbbzhtfpu.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gthwtwatdn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtehxkidzr.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtkcthplpp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtmgovtxop.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gttfzxcbuc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtmibkasaw.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtwhjwmdcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gtrrqdhwkw.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtkgrahnbl.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtlzepfmac.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtsxayyyaa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtmeznlfvh.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtpnxljfbu.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtzazfzwzz.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtmftrbbvg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtafafmlfv.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gttdnozoyb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtddmbphep.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gteobvxcbl.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtrcffonxe.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtdclckaip.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtlbzsgkys.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtbwrcslsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtnwamlmjd.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtympmijxf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gttbinhexw.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtuiqqbumq.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtyfapbhbg.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gtsabtivfs.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtgteosmzh.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtpkkaucli.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtkjxnsxha.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtfhqeetff.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtlqnnjmuo.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtbeajkqae.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtanifdhcc.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtwruzqawz.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtbaekriub.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtpwxdwgjs.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtguetdzek.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gtjqckditi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtxlgmdwcz.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtgnbglxcj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gttmpepuiy.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtkjheswez.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtdpeukhis.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtkvwcoqvr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtuzlthfav.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gtqyzxanwv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtjlnrynso.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtdsypmciu.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtvxssyrht.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtafsxhcrm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtwtuzhljf.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkvzupem.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtkgbzaghv.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtcrmurqlr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtpikwxyjr.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtuyouyany.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtdedilhui.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscpoadrv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtzphuxqps.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtrubjzuaj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gtesfuxqhx.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtvmttvdfy.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtfvyaberz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdevvudty.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtyyseunuc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwhdtajwo.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtvvswpdua.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtndgnkjrf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtwtgfmjre.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmgudifr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gthmatoiba.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtiimqxius.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtbvpdbups.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtbufqhcpu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtnesoeayl.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtoedvppzj.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gtuzspsayb.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtizdjdrtn.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtbgkrkyut.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtjnnrzyzs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtdfhvurps.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtmsbxqopl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gtiulmisle.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtamqmwvee.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gteuurnrzv.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtqpnpspog.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtibcmemjo.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtpcessiyj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtavnwjflr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtriuqlnin.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtsuqrmdwv.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtscjygmhe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtmefqfwuf.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtmjuarofl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtgdzlpjpv.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtouycrggy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtfkmcsgwv.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtaztempjh.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtjaacjvwn.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmjrovxv.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gttporuotv.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gtyxsnisdc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpokujveo.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtvaptlbte.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtsdtcweew.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtdvexorjx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtjdrgxczn.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtrojzmbcr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtxntfkpik.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtkofmsuax.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtptqwyasp.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtksgdsdnw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtyhuklaob.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtfbebbiot.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtpussuljg.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtzcjytzuo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtouituldq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtvmsfmmvd.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gthntyzzpo.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtsxflgcge.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gttjinkjei.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtvfxthqqe.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtmygbpcxm.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtvtotoshb.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtuwasfxdo.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtjqefludw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtoabyubbf.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtcjegmhfs.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtfufvrhqc.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtnbcyaqry.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtzojtnwdu.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtqodanccl.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtmqhgetqn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtxitmrntb.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqnyjoey.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gtatgktibv.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiouloah.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gtcohxlvtw.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtcldbacok.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhmisfes.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtiedjvegi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtllpsmfck.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtojoxnqmn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gthozntgnj.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtziplqwna.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtbejclkwl.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtstvfxoym.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtevsvdnqe.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtukncuytz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdggdbuof.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtqzxebiny.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtmusbltwc.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtjvqihwba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtovypgfco.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtxjvqcxnz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdutrbocv.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gtkdglgqia.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gtfuctoovx.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtnehbysvf.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtunaejpra.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtefrfinpb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtjcoqzkis.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtabtevluu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttwogwxzx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxtvhqpz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtdqggpmra.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtxalrixff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcydffcpr.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtazphvafw.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtlbiuapre.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtybhlkhbm.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtyuhockaf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gthxfyunby.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gttzpgjhrc.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtfqyzoltr.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gtofmdabdy.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gthtbxkobw.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gteyghezuu.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtvppnlrnn.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtyqerebis.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtxpunwgwv.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtzqzmyrft.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtagxbyjtb.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtdopuwhaf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtstifvfmi.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtdbqgbpad.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtakuujcjz.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtqfjizywh.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtldfdwgce.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtcfwkvlgp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtaalbzswy.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtmiizjzng.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwmaayjz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoxtbehmm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtvicjaoel.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttkktieio.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtamlbfjoe.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gthrewspbc.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtespgjhub.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtpxzsibff.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtklkesddd.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtmxiuwmew.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtzahtcgvo.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtqslndtcc.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtituvahgw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gtegocpuom.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtthkaipyf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gthupcxfyu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtzluzrtfw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtofyrbnxj.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtuzmamzut.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtxbxlkodi.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtmbreyjhp.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtlngfxqbn.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtifubwehs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtixxzuqiv.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtmiwnsonc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gtoepcgzad.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gtrnmbwqkc.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gthrwlsxzl.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtjofjscws.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtyijotpkx.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtpklbdyhg.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtgdentdbt.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtkcejjcnc.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwyrspqj.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gtkafatnfm.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtzcxcjnfg.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gttdypvcvb.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtbcmulqvi.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtkjiebzlb.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtuclbujei.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gteuinafzl.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtughpbqpr.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtpxjbuvln.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtyqpqqffo.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtvvunzgrg.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtymxlwwkg.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtpvqateef.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gttxuspbav.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbylecmbp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yonumen.top/Article/details/gtwnkxfywn.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gtnqeheypq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtzawxtkip.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtcoylcbxb.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtlkeypdep.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gtyipvwifr.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gtqricqdhi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtedvkwwot.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gtyqgfcqvs.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtkvpwapgu.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gtardcljai.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtcgpztzyl.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtqddwqwez.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gttjyffqkf.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtpejartnx.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtfiqcbmsm.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtqitpjdpr.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtwgtwimhp.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gtmtkjvbnz.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtcldjvyhk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtywdmcvil.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtxleakmhi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtcktcuecp.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtnmsaggfr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtdqspneth.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gthlqjktvc.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtmcqlgfmi.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtefrymnnf.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtkohvpxxq.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtysbcjcqr.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtgoaqsoiz.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtxmhjpvix.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtpsnlyudb.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtqbhrwqzo.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtcijqdthc.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtevnjqtdd.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtjhbowjyy.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtxygzmdwj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gtqgvlavac.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtdbqjbgtn.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtuevthckk.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtqdslvpss.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtbqodljah.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtrokcioga.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtjzmbvuvv.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gthxzuykbf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gtuorajzjl.html


<!-- 参考信息 -->