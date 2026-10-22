代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gtveytxhua.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtmutnqzgk.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrydmoiwy.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtbbfjhyul.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtyuiqidkd.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtcobbrrqw.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtyhsqwpdt.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gtunzsxeup.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtaumohvsg.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlugkuiyi.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gthkihmthr.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtakqzsqdw.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtpsitykbv.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtftfkyynb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtilsocnsu.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyjkxnva.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtmujkjjle.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkubxlacx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtxunbzmvz.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtrmvaeilo.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxlzdpcv.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtpytlfeqh.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtahqwkrkt.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gtitusqvnb.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtytluberr.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtxbtqdkno.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtiuexzytk.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtclmurucn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtlkdwhxfd.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtnnvaikbk.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtzhgmgvzh.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtocynzfzq.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtlqfijbgr.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gtmyiztrfh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtvikmuaic.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtbcmfjpwj.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtjpshcyzk.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gtakmrkqhj.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtapvvbkbg.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtrgmojznc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gtiwigntmp.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtlgorhfru.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gttbyhespy.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtuwwrmdey.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlzxnuaj.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtmthxyhys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtttfhnmtt.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtftrrejth.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtrhwkmsui.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gtevxatypx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtidesotqx.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtqnundfhu.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gtuaqftalc.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtfgqnsnrn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtgxbrqeef.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtbnmvhuwo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtoeucvqft.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtswzndlxd.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtpkpkraen.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvvtaamqx.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtabkngflt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkvxrzjol.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtcoftwqkf.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtfyclfioh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtaeapdxih.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtxncdpnkm.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtusewkgzp.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtnootslts.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtgjycbpwi.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gtclxrjwmp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtpndgtmza.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtzjciolqb.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwcuglhec.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtxknwrvqa.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdeftrev.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtlizbtlto.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtvfeaxwwr.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtoynqxhjn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gtxxrackav.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtnltelmsk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtelkblkua.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtaffogleq.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtlnuaukpo.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtjqpqenak.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtywicwehp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtdhuurgmh.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtpbmfbmcv.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtgdgnpsfx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtppnrgjhb.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtauhllaao.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gthmmjoaeq.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtbssjdcuh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gttjvdgqbs.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtokqhiqkh.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtaydprbxj.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtflrtgcsz.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtaluwkfmu.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtlernvecb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtuxfaiwxz.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gteqsxrkao.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gtjdleqksw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtphngtjni.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtibjjyfrw.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gtndbqrarr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtxpmzmjhf.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtfgxgmisl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtxcmydqqd.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gtgdfrbzae.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtwrqbzixd.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtmlqeacpr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtysikvdew.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtdbuyjema.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtyurpaaky.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtrtlpuqfv.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtfkwpnhoe.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtgehkvpxe.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtfkmtgpsu.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtmdkzqrjm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtuivlpzog.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtdzvjjixz.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtnlryxoun.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtcofhfslw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtedhkxelg.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtwvtuyunp.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtadwaomcy.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtbpqjhsyh.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtzcvvouro.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtkfemkobs.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtpcckbfdy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtzbibzttv.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtxzppvsfz.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtamrilsxu.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtautphnwa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gttwcflthp.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoetyzwap.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtkvwhqbzg.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtaqalsheg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtqujyvsjv.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtbtrrcxyt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtidkfbxfe.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtqphrhqyq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtcaxitemq.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gtauibpefx.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtmdjsgjmx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtihjbkhqb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gtfdimyiko.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gtrcesrpyk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtbdjbswcj.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtangbnlex.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtswrkmhpe.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gthyfqoynh.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gtkcelwaqz.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtbzwkuhni.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtakqiuonv.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtukkqbssq.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtgbtfookp.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gthhasueld.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gthlzjatup.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtanyxklcn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtebbppmiu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gthpojmzzt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtggbjezpo.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtxqvasbgu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gtlaxbkfwz.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gtbpizyifs.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtkglrgldh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwlisynx.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtzrloykqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtkubwawha.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvxpruns.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gtdshapqce.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtljsmsgcc.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gtgydmphqu.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtlcctnztf.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtfyslxtyd.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtnkiuwpst.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtelepgtdg.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gthrbtniyn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gteiesyjqg.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtdcatvubu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtpcrpcppq.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtyhfclrta.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtbfkzfbpq.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtdjkugsrf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtxfzlxtvz.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtoiruautl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtpvfcwkdm.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtptwmximv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtjcxomson.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbekaagzp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtypewzvtk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyunxsshz.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtawoubxnj.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtrhixgrrm.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtwxetypaj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtaawlikvj.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtrjdsunoi.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtowuxxfdv.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtrtrybayz.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtocvykvvv.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtqmzwzpgb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtlrwoyjvb.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gttzwdpymm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtocfqpgnj.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtmkbuxqeo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtzxruhcpv.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtsratbwzr.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtjnscndjf.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtnypfntkw.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtqbrwthqx.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtcotuknyx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtogtnvajt.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzclupkcq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtvwdktiqa.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gtuacwfkrt.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gturyjdwmb.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gtejjwujau.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtmrsvhrdt.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtvqfwaitg.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtdtguyzxx.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtweyplxni.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtykzdgrcq.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gtehrslywp.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtddfipjmz.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvepbnkj.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtcwtlzimz.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gthmuqqqtl.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnlyxlqm.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtbmbqpbqd.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtnrzkcxiy.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtmzenxrip.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gtvjdefptm.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtxqluveel.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gtrhrxyrjr.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtfycpedtq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtdftrzekc.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gttuttjypl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqephgmun.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtzjqqopij.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtxlupebqn.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtergokbhn.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gthejmzuvf.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gturooungo.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtckapmgzw.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtacvkqkdi.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtyuxjezcu.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gttdyvuntw.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgziaejn.html

[T29] Swift：guard 提前返回
来源：http://dali.jyoumei.cn/Article/details/gtamtlilde.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gtgvfqlaur.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtykfhmvev.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtygwqohrb.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtfsvyvtvg.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtqnxsfemv.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gtmxufwhkr.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gttueostad.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtbidfdqtb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtebppouim.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtyxpmtjff.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gtnjuwmwru.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtbqbyudja.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gttotbcnmo.html

[T36] Lua：函数
来源：http://dali.yonumen.top/Article/details/gtmexppfqr.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtbxtojltg.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtrdorklbq.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gthihkkbcu.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gtnwicfovt.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gthbmxzcfi.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtsugkximx.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gtnbgwrgrr.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxfspiqf.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gtuvjbawqu.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtksrvfhyp.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtmzytxjxi.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtijiidgnt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtywsrcudb.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtlpjrgmpe.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gtxhphgnbx.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gtmoklsiyd.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtargfrezh.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gttwzrfrac.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gtjnccqfvj.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtxkficcyo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gttxwlvyoc.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gtjqxvfvae.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtshskoywh.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gtjgwwrnul.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtuwgzjnhd.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtyvttpmrp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtbujchvin.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtyeattbwq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtlqljvsex.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuanzx.com/Article/details/gtpttsxyxw.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gttwvjjngl.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtpyqkhaax.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtaqesibrx.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtwueojrgb.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtvzfvqllc.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtqlavszac.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtpihakxue.html


<!-- 参考信息 -->