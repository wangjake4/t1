代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gt2gpkutqwr.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2vjalwixz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2vqmwfkbn.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2ywsswnqv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gt2figkwaan.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gt2olvawros.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gt2jwgzonlk.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvggtzqh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gt2npccoayg.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2nwuvhdiq.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2xeknabxe.html

[R55] 压缩与解压
来源：http://dali.ybcxt.top/Article/details/gt2rtrdkdwa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gt2ceqccrwb.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2njsulwdx.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfhupbmo.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2sgqeekzl.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2pwhvgnzz.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2cidselde.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gt2xsruygjn.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2qhebpjtg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihgptfsk.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2coyiwfyv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdwyvxnp.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2plvdrvzp.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gt2nzfjptvn.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gt2owotebjs.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2mtzpseti.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gt2pafqbehx.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mynpqsim.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2aqqfofpi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gt2rkkejkgt.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gt2yptnqers.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gt2amhxhute.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjsnzkhg.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gt2zqqnowyr.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmubtqmo.html

openssl rand -hex 16
来源：http://dali.tianlin.xyz/Article/details/gt2xasjppjp.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2ggukmitt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gt2hvserwpm.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gt2qduecbhp.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gt2ayzreqcp.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gt2mubztuuz.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gt2zgwilnod.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2gpdeikbj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gt2jzgvhuqv.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gt2nehbqfyy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2cvxuhmws.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdkumjaq.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nginqrwr.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2bnkaetpy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2ukkbwivs.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gt2lsftvxva.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlwjguri.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gt2zrwboiah.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2ovxbuflt.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2rwytiejv.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gt2cbvtczar.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2uynawqrf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gt2blcrvcoy.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gt2bxxmlysc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gt2hqkymyfg.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gt2yncohrbq.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2wkgedduv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ijxrkxan.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckjibbus.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qacmierx.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gt2skiigdhk.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxgkcvxz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gt2fcbqcjkm.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfrkqxsa.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gt2mmqfjnto.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2puqgjkkf.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gt2vmjkyymj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wocukrit.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gt2hsvacvvl.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2mtwfyysg.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gt2bptyerpk.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2tlgnavmw.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2elfktfof.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gt2ubbozzjo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gt2xukcofoc.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbvnlzul.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gt2utomsfke.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gt2dzqakvsu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gt2eegpotwa.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2rglgtgeg.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gt2owpuhmbp.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xkfmsllf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2jnfkdxuj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2qdcaugby.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2tnturduc.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2qpjfpwud.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2oiptdrlx.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpvygksd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2wngxagqe.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajliozaj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhccrfbp.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2rmbnrmje.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2ufcegzfl.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2brmdaffj.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gt2stympgqs.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2smbsstjs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2tacbwwzm.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybhokuuw.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gt2abslnsny.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gt2upffqerk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2olzardac.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2bjrnlszu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gptaraxm.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gt2yuwvoswb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2niezowby.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gt2wklptuhl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gt2fyhdymsx.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfrqfurx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gt2rkqohkns.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gt2akdqvhtr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gt2gqqydqqf.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2wkfqxnmp.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gt2jxupqxvk.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gt2urjdrjch.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gt2hwnkkzwq.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2ursaqihg.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2tjcmkhkt.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2liwdexvu.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gt2nomhobeh.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gt2jcbborsd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gt2xtlhiopx.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2mbzzumqz.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2pwyncrwp.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gt2gkzxjeva.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gt2lyhxmfeo.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2bevzuiui.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gt2rfhmfirg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gt2bpgahmnu.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gt2lnrlulyj.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2zqdiaxfy.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gt2mtqffuti.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2wumxauji.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gt2ugzmxvry.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gt2mbwnsblm.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gt2wmswcrnu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2svzewnhk.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gt2ivnulmvx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2ukifbjsb.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqpvofpi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gt2tecvtetx.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gt2ydswufrm.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkucpljz.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2mztispfw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gt2mmmrtahd.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2gviboyjm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxumaxdj.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxqwgbix.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqgqfje.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqljunad.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gt2fvzusavo.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gt2hsilybps.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbysdguy.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gt2hzdeirjv.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2vsuhnyva.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkqwdprk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2yvyuwajn.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gt2dkuiyivc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2jrqsvbxs.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gt2odulvfqs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2pezgqmee.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ivginpci.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gt2cyhnrzww.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gt2tgkpamvj.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2ysopbsgq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gt2olotvufg.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gt2jrpcmlfb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejlrzyvr.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2kyfoqyfw.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzxvvukc.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gt2ngkelbfm.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dttegjck.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2jnazlbar.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2pyntlglu.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gt2bbtimprw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gt2jeuhyqkt.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gt2cwfgvewh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gt2qtfzkpes.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2pycehvjc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2odtsbmwy.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gt2hfteydur.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2vbqkalde.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gt2lsjmczsu.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gt2vptypfig.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2zhjxstlu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gt2kdcpjtqa.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gt2hdmbswrw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2vlmqblzq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qnpkfxxo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2kbkvpcim.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fdhhzwdm.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gt2otrfqfia.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyotpyse.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmkglrfc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2oumsrtof.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gt2leytomiw.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2catsatis.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gt2egiyvxfy.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2yquludqr.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gt2lkyeeaqi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2anwqiuxk.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gt2hjvditss.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2rrecqjnl.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2lkmldzhg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2wmwldajw.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gt2ghudihkj.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2snfaathh.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gt2zlrrnsql.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gt2htzklilb.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gt2oaxwypbz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2afeoxjcm.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gt2aqzorqjo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gt2qcdpukzc.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gt2ivlmjohr.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2xlknjenp.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2rmummeul.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gt2wybdwjgp.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gt2tgxuenhg.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2omvhfraq.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2fzotpjwg.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gt2cwnxhnqt.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2zkypyrgd.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2erznycpo.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2ibytuexg.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkvivsuv.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2prekmogq.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gt2bohihxgs.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gt2grpusfhq.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gt2fhxfybsw.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gt2lgsylkuv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gt2ikzxjvcu.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gt2iqabgurk.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2jrklllnc.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gt2wqbupgur.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mouzyzuf.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2qiusnumk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gt2dbdqpobe.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygyvqkzl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2dtkzbobq.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2lrxduwnt.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gt2ujatsgph.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gt2shkpvvha.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gt2yjpnajxt.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2bhcrxars.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gt2zmrtqucl.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2yzdkvdfq.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtlidwsh.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2babjsdci.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gt2pbknwxwd.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gt2ilxftsqc.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gt2fyfihwsx.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2anftcqux.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyltqfeh.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foypxqmb.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2dpfsowod.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gt2fuhcrqmv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gt2nlvtcryv.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gt2kgihkgow.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkyavgce.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gt2ipiuoauk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gt2ehyatzgi.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gt2slasqsac.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gt2ffdcxknz.html

[T37] Lua：字符串拼接
来源：http://dali.aizwys.cn/Article/details/gt2kgsivdmo.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gt2fcfqtrur.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cobfwlae.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejvbtifk.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gt2kshaorkd.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gt2kebmrdmd.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gt2fjfysdnc.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gt2jkqxkyqi.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ohjtagnj.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gt2oyfrfgsf.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uaqylwdf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gt2efdymvhe.html

[T43] Perl：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2mivsdmiq.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gt2gtnaztgp.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gt2vytkunvq.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gt2zfxmmmnt.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gt2szxitlxr.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mfxpdtyj.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gt2ptezmueg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gt2yevlhivd.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gt2urcqohxw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2rumbfutm.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqhawjkl.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gt2pnabzgmg.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gt2jvvawmkx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2pgfthshd.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2zluehrgl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gt2smhlvtjv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2invcthsn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtnxzoy.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2bilyptuv.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2yglxneda.html


<!-- 参考信息 -->