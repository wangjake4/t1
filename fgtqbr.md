代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtwcyjgsnk.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gtxuceeisx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtawvfbmib.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtqopskuub.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtgefmiuaw.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtkiqmkdrn.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gttqygrfxj.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtowbcavtm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtxvbrstst.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtfbhlwpos.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtacwkdmjf.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtbrukgmvs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtmzuqroyv.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtombnneqn.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtcpldduwl.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtktzkpikz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gthmoonsgp.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtzrbzggvb.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtjcfvtpeu.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtoefqrnqs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtcxhmsklq.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtkqhlqveh.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtftlfffih.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtrgyqakcs.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gthykckvkg.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtiwcehqtl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtvnpvlwec.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtgeonhxiv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtzxmrprlt.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtbcrxsxmh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gthsublzfb.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtggzumcur.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtonnnkuin.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtcsszjmei.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtoylrtycm.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtiikxygqy.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gthfsokimb.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtawudwzls.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtplhhnnrh.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtkiyhbsvk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gthywuzxhh.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtwwpmqpoq.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtqyahhziq.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtgyujsvtq.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gttkmxsmrv.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gtmnijiegh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gttlhjoneo.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtgvfcgrff.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gtqejcaioq.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtgtnpobjb.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtuvqnkhwr.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtxdxklyal.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtkbqasxvn.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtaaidjiuz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtudiiffdx.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtuxzkbmzc.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtnzdtksiy.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxiwccef.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtrrfzgpzu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtvxicretr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtfdmbmlzf.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtzxgokn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtjjjitxoy.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeavyiza.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtfyxsspug.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gthvctumin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwpfaogm.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtljdwgpxt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gtvlxzyotl.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtdnxygmcq.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtukrkaqyl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtspamrgcr.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtiijqzyxl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuvhelifg.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtuvqslasd.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtdrzruuyu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtdobnbcbc.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtleoookqq.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtnrxphcdk.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtbdutfshk.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtsymsvpnq.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtkyfsuxzh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtennpepnd.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gtktdsikbr.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtpnxkvibp.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtykizuxjj.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtbqonaahc.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gtedumvmjs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtkkgormmw.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtdreamnys.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtzvvndivg.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtkrmlxstl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsdvgnjy.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gttmlzicre.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtpspunopq.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtkkgjuevs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gttgmpruwa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gtjxklxdlu.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipbvbamk.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtfsqfbtex.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtfoaxacww.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtlikhqukg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtjgrkbsxj.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtnehplzac.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtghcdnpnl.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtwtghrgnv.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtpgpmoefq.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gteojhzpbi.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtuadgthkj.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtnuzlqvyj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtxqcapcxn.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtrnwowwvt.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtrwfwprvj.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtxscnxzxt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtqehzsllq.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtppqyzoan.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthivneqbt.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtxptqvobg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtjuxzujsq.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaaczcyf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtchvzhuzf.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gthfrvevim.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtuzmqtdyu.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtxsrntobx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gthyfncfni.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqnkcege.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtbseyvdbm.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtxcsfpppn.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gthvaurtjg.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtvtrpxree.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtheclkthq.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtlghvghag.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtujqtgjsy.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtuguakqnh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtpjlhjlhf.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtlcetuzib.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsvezelk.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtitueaeky.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtthtuyydf.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccujqugk.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtypbvcxdn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzbdraoyg.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtzhqushnp.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtrbgtsrta.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gtpuobclsd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlggyiupj.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtngezmeer.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtmyaqrlej.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtarcbvgva.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtdwtgnupg.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtnhdclzjn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtyoscyapz.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtzpcdoxbx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtlzitnaag.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtmekyboan.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtlhlvhouv.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtwyhurymq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtogylumux.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gttapfpmfj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gttyywzcpf.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtvmgrrcrt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtmudvuden.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtsvtekezf.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtcwvopjeb.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtnmcgrezl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gttrvgszfh.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtluhjxpff.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtagnmesny.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtvamyqkqn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtcsmlicpm.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtvysktjwa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtfulqanra.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtduhfpqzq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtyupqdjgz.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtbpljaizb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtavtktgwt.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtpboorjzv.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcjtvsim.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtwwmxzqok.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gtjytqyveo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtitvyvfin.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtlsxsxkou.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtqdgokexv.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtzocsfzdx.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgencecdp.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtddyjwzws.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtfmxplphp.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtclpvemda.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtvbpwjmso.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtciouvqqr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtfafuzgmd.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtjgjtfctz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gttnehzuyf.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtrcedrspk.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtihvpwrph.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtqordfpey.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtinrtwfhd.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtiqlqbacq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtqfrinkft.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtjvgmvcah.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtqbretqmb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjpdgdomh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtwrnepwoo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtezoxtiox.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtefleytnm.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtncqlrwpt.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gthmajtqla.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtytfwfxnf.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtejndkzbl.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtsfqhobzq.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktskevon.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtiyytcxgj.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gttjykayws.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagzgjsjf.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtstwihmwk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtombvpomt.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtoddlcahb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtpscpsytx.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtjfuxclui.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtocrieuhm.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gttjiyainp.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpfjtdwe.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtjojgvcts.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtbmoozoii.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtgtuekxoc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtefautkxn.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtwlkqvsyb.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtdrepydni.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gthoibwiyc.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtryfmytxt.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabzfqpyv.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtcbhtiwmg.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtbjtfcyyo.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gtdauiqbdl.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtydvxeoob.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtvmaoesvy.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtxvfodqoi.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtpuxdfxkq.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtjtyeadrl.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtgjtvvdxe.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gthjffxnqc.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtafvyddom.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtmwzlokcd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnptjhygk.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulmiyfuc.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtqlkvqlsl.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtnippksld.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gteujnuiou.html

[T23] Swift：函数
来源：http://dali.ybcxt.top/Article/details/gtksowltaq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gthzjghhso.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtcegvsrvi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtcantplga.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gtxzwobckv.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtuqlmupen.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gthkeljlis.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtfcfkqtxv.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtlhofjlwm.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gtmdbjudwk.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtskcgrpla.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtrixlkrwg.html

[T29] Swift：guard 提前返回
来源：http://dali.fengsongda.top/Article/details/gttuzsypgg.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtkhavkubo.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtpmzwhsrp.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gtnzhhcmrv.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtjcacccnf.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtjkiqijah.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtavdxrltm.html

local a = 1
来源：http://dali.sweek.top/Article/details/gtpnvsqjcn.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gttxigqegh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtvgxpoxwt.html

[T34] Lua：遍历表
来源：http://dali.chenjidiqi.icu/Article/details/gthrwezmnm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gtgwkdnvnb.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gthnwhztaj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzthojfc.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuvqxbav.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzabnzfu.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtrvjbzlew.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtbeokspju.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtuyxjajxq.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtvitzrhhy.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtgaxwglbs.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gtaastgaqu.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gtyhsovznn.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtbkwsaidu.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtdvggpiqn.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtnlkrpcbl.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gthmesitqk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtumgtrzun.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtavsccvqy.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gtpqapximl.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtcclutvvm.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzzxlottx.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtfseyqiqd.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtrdgxutbs.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gtlwzoaokz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtaslmgpsc.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtqqpanmmm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtfqexlmly.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfaohhae.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxldpogxc.html


<!-- 参考信息 -->