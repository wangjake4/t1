代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2eoifjmro.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2jtoihsnp.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gt2cpohshoj.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gt2wwyihyli.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gt2jultnhfj.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2itdmwwnt.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gt2mqvadoqc.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gt2cadaenou.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gt2eqkrfeqc.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gt2ekqqkuwk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gt2fgoabqxn.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2hyuqdxnr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gt2ijcotymk.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2jaioqswk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2ditackct.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2yeqlojsp.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gt2fddowdfu.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gt2bllgsbhh.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gt2aajpmmvn.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gt2wcwchbgn.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gt2donnwzeo.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsummsvx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gt2tfilvfpb.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gt2ahoascas.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2jcoihbtn.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2sajqdmdp.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gt2wzqitbtu.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywgusqza.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gt2mzoaakvj.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gt2hlinpoeq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsdtthgx.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gt2lmmytsrl.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2susybnxu.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gt2yuyspwpg.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gt2uazgdxbr.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gt2zrmjafdl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2fudjxbii.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gt2dsuhavii.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2fyryymww.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaamjko.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gt2dpctrhps.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gt2nzbsjofi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gt2dlaxqgsa.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqkkhtca.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gt2qwbpkdmd.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2mlgsxuoc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2zwmhupjc.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2uipygsep.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gt2vyqftfwy.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gt2rljrwgtz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gt2twvajeov.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gt2hnyozwew.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gt2kuqxivnl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gt2eqxbsjvm.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gt2mbekklhl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2udhbrptw.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gt2nswowoac.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2kyloddmd.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2jzjdmmdi.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gt2zlaxyrxn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wpfgnhjn.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2wmvtyjbv.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gt2jdmmqakz.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gt2udupkweq.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gt2urjvtmgx.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gt2waggwfbt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gt2fwyfngmh.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2arjbhiik.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2teayzwop.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2rotsmukk.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2xnxaceki.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgsoiwpg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gt2vpltocnh.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2tayiayfs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2npbxlqci.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gt2wzrvzpop.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2eylzncez.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gt2cjeglulx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcffvlcp.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2dpexzuwv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2xcduobke.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2lkxahlrr.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2swokfpka.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gt2lsjbbbqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2qvmhuecq.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gt2lsmwbgzf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmvpdhxk.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2wpndqmeb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2lgtakvow.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2cwfutmzj.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2maqftpur.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gt2dwmyrorq.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwrousgo.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2ymzansfi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gt2wrezhphc.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2vxwagkrn.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwdduipe.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gt2ywedvtiu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2iqmfkayi.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2wrnaptkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnjcrfcx.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjovjqrk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gt2awlxuqkb.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2ncjrhgrr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvnoifio.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gt2bbytrnpe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gt2rlnbfbwk.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gt2jfmjvxxp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gt2fmzxcpop.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gt2xhmnnrzi.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gt2ggcrthue.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2bdpjmilg.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gt2uifgpuae.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gt2dvmyksqm.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2ipmrofex.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2jmfwacho.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtfxtahc.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gt2nzuwpvbv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gt2prybmswl.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gt2ktsxezty.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2qfnrfwpw.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gt2cgrgjkka.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gt2xsblbnij.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2ugfskavn.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gt2fkfcswye.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxvzpqkg.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gt2pcdmawfw.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gt2rryelsyn.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmpyfmru.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxuevsxs.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gt2mutsskac.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gt2puizoxfl.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gt2fqvlczxh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2dnxntvjv.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2qkcfsssv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2ibtxwsdf.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gt2esfavwgn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gt2ljmwvfzb.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbzjpmbf.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2gbpeefyd.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2xpkuomez.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2pzfphgwj.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gt2htcxydwx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gt2vimgfeaj.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gt2xploejdv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gt2vbrehaos.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2qacimtcj.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2tupqxypx.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2nelpnpba.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnafscdx.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2ultdrams.html

void inc(int &x) { ++x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zjrgmxay.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acbqavrb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2xwsykdfc.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gt2krltpvdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gt2gzmjbful.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfldmxv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzaorsem.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2xhywovvz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kauvbzkn.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2ienexntr.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2ktapqqnu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gt2fgtsymku.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gt2ajqoiapn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2mzekvhpd.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gt2mygtyfpe.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2nxigwefq.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gt2kmazhrrm.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gt2pnkrcwac.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2jjufrwwj.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gt2fmrplhve.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gt2tulkxxhd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2korkdbpp.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2cofzhntr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gt2ycjqfmhd.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gt2bxfepotv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gt2snbmqxmn.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gt2bdkonotv.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2szjypwkx.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2vqdckhub.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gt2pvuqjppl.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gt2numsboqo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqcedfrj.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gt2dlahstkr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2oaueipei.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rrsjwura.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gt2mfnwqvts.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2kmksqzbj.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqmejsjr.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2qlptzfbz.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2wopssmbf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gt2hexhcvoy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iippnund.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gt2lgdvwfnu.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gt2gbgnxfno.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gt2cnzgasqf.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpkmxjtj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gt2igrlemsw.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2cuweukse.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2senhmsqq.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2kdexjous.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2mgyosdry.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gt2yoclyevv.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2xpokesda.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2vreinudu.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tapodwjj.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nezdxugl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntgoxakj.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gt2niiqnure.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gt2kotgntvu.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gt2owkqjuqa.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htqzkvum.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gt2frmbfgjw.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjmpzcxd.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2ucamoaso.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2sjfwpcue.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gt2eflcrxnw.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gt2vqmpiwrm.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2qbawismd.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2ftjvponr.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gt2fyxwznaj.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eovnvxxl.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2ygmxalcu.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gt2zcdxjjqw.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gt2pstefsec.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gt2wwlnuxkg.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gt2uqqivzvv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2ihbrrnhi.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2codacvfd.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gt2lgvulvda.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2cthilxjf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzjcfaja.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2fnmnukew.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2ndtknoee.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gt2wcoeodjb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llxldefq.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2fiujqgtn.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gt2putpuduz.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gt2odwnghld.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2qzcxzmmj.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2xfhjudzi.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gt2ibijxzce.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2cimjhehq.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gt2rundwwtr.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gt2zbuyiekr.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gt2kzvdegim.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gt2bnyxlgaj.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alzzznjo.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2dyyzqmgs.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2buhxsewf.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gt2uasetrrh.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gt2xcjojpjs.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gt2qjqcuqmd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gt2irbwejnk.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gt2kpeqmvzb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqsolbvl.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2cvncgish.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2gqqpshbx.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gt2wyupbhuw.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gt2bmftbkta.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2foneasef.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gt2qowdlbnb.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gt2hvtuahit.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdaokzvq.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqpoedcu.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2ovemwynr.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gt2lfqnxblj.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2jqxmhxok.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2xbhvwgiv.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gt2dhpctgqx.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gt2jobmzobl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gt2pozawksw.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2euoumpho.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpnjyeep.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqjqdgdv.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gt2lntqmrhb.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2znlsvyio.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gt2bpbkftgo.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljpxprfx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qbwqizzc.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddwhrjcq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dianchejie.cn/Article/details/gt2dcxjjimz.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gt2cpymmjrc.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gt2jnaktfzh.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gt2blzvicfv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2hcujmnof.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2vokkqxpz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gt2jkyevftw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gt2kmberzkb.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2pritkmks.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2hazkyhld.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2kbazefyp.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2cigywacn.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2hzbxiboe.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2lanipmzo.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2pdkuvebq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnjtkgjo.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2wqannfgv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gt2cemeycgh.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gt2vdqqzzky.html


<!-- 参考信息 -->