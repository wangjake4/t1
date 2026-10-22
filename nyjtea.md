代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gt2cuqeimcn.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gt2fclwicag.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2erkkivtk.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gt2yytnjipy.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2tccssqxs.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gt2jcustkon.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2feqlsdrd.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2qkzmsunv.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gt2hmcrkjzv.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2pjyyrogi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2sodwjuqi.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gt2vuzqfast.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gt2gpegonot.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2rivdkttx.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gt2nqdsoasx.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gt2dbgibiny.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2ngauthad.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gt2ousxgkdi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2rnspbjfz.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gt2pvryyeui.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2fdlxupow.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2xjdhwzvc.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2vealrjwm.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gt2jzijplen.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2gntjadpd.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gt2eldvgrws.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gt2vvwdmfco.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gt2mewafvjy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gt2jmqueast.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2evkrtpjp.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gt2ovjxesml.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2nehpcaby.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gt2pltrxipc.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2eghjaovz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gt2efkabcgn.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2zweahrch.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gt2axeekezj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2jkcmscis.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyoumsbg.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2sgyxcwcd.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gt2czcngucf.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gt2encaoqmg.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gt2limouyxd.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2ikpmclsi.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttgdefoz.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gt2yhtuwylm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osrgyxpy.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gt2iaqfxjlr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gt2efphmzfp.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2rwxambhz.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gt2kopjsdvd.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2lcmtgjli.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gt2qbbmoegz.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gt2vaovlgqn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2ozxjtfzg.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gt2pltunfwy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gt2vkrdesqo.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gt2uxonxblx.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkczhvim.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2evuyqcrl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gt2qwvafsmd.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gt2lciaomfh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nliqnizj.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gt2ssvyjgba.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gt2bfvqpiic.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gt2tahbpnvg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gt2folgxbaw.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2otnphvtj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gt2zkqklhvz.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gt2smlkapmq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2dtkhfjjt.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2lzyjjhmm.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2isgpgrqb.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2mvjcmmgb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gt2hfdpburi.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2szedhcdh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpkqiume.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gt2gbfqphyq.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gt2vbfgydex.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2miwqarto.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gt2ecvlznjb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ohbqwccg.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2kiltiqxx.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gt2aahiourt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gt2ujhmyaqb.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqvxzefx.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gt2zefmahna.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gt2openxrao.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gt2htrzhpoa.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2iikzwlxb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gt2kufbtmjy.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2rstbukuj.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2bbtuiqhi.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2ckvrrvgb.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gt2bjqtkncq.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gt2mcbiisou.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2ljkjdhii.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2ubmvrwjr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gt2uqdmhvyr.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gt2yytrdssb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2uuccyeaz.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2kaddadja.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gt2sxczfjgx.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2dxftmijb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gt2haqvmlln.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjrmftvu.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2yebatdts.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2qmapomew.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryqhbltj.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2conkeiud.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvrjjoxd.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2cluotjgy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gt2ehfvlvun.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrtqgxii.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gt2zbfkgmtl.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjzcccfs.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gt2wmahnkfy.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaaoumji.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gt2hizqsvwc.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2vysuoovx.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2txdvhirg.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2hgyfqnwm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2uvtpivvt.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcltlbrq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2tzbwiwpb.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2gjiykjub.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gt2tlglvyyw.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gt2veamzpon.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gt2tjypzvxh.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbknqktp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gt2guiyjtop.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gt2ixdlvege.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gt2xweefmeg.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gt2cavhxhvh.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gt2uorexlke.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gt2pcyitxgg.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gt2spqzvqwi.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2fxsdlmrv.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2iepmlnsn.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2djedxkfm.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2rwnsjmir.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gt2jetitewk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2zyxykpyu.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2epgmkwfg.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gt2ehcdjrcp.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2lrqbbxnd.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ongmqwkf.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2kvpwhcqi.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2lyawvkld.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2hapxonvy.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gt2alzcvoaq.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gt2pvkmxent.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gt2anrbeyaz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gt2qubarwnb.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2spazmoco.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gt2qxnxeiqg.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2ilqvgduy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2knvinhgm.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2wlybcxwp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2eeohfbfx.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gt2rrykhncx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2immqcqad.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gt2xaxqaqpe.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeclbhrr.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gt2xhqmrzbh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gt2khfmvypj.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxmhndgh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gt2wxwotbkw.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gt2tpsllyed.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gt2ilzpogsp.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2yucdzfpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gt2htimlaba.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gt2crpjqoyr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuzeqcye.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gt2uupkgtby.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkchdqqd.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gt2xeyaphix.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gt2hqirbppf.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2waxkmejl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pnkknfva.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2fymfeqem.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2ceatptqc.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2wtbexkvm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2efjjbzjw.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2xnviubut.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2rgyhffly.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzhogfgp.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gt2ndawbuml.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwwlwimk.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2vckysnqk.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gt2liadbcmk.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gt2rqbqjjiv.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2trguggmr.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjltmuxy.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gt2umvxixex.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gt2dbuvwjbz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gt2jagixgum.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2osfxjjbl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gt2yobpgspj.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gt2wfeamlwc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2oqqcizjo.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gt2xivwxkpz.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2rvcflrcc.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gt2ndcjkdap.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xltiafaz.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gt2shxpclno.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zktancdv.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gt2nrebznbu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2dowdvubf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gpktwybk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2aljuwkds.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2skvkxzuv.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2luixshlp.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2ierlitsd.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2iaramxqj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gt2fbdbzyvb.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gt2rvmbdsux.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2oofwjyfi.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gt2ntelympz.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfnjbjhl.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2daneuhcg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gt2odarifuv.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2tchljqrd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2cuxuthpy.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsnagixu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gt2wqsaqfpe.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gt2dryewrzn.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gt2aishgjag.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gt2wkygpdtu.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gt2zyrshure.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gt2kxkuubrc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gt2qsmyujmf.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gt2zzwqsnxa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2ndgrcahq.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gt2bvxzwhye.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2evvfhwfd.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gt2dyssiikp.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2gpcwgkrz.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gt2vsmmndcw.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brwiffhw.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gt2idnlbprr.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gt2hqdxdelc.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2kvbzwqha.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2fkiheypq.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gt2byilzjci.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gt2jamcerax.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2wbgsxros.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gt2aspqvybe.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gt2dngsbles.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gt2qnkbwagh.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gt2nqquayld.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqoqqgkb.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2baapyzgm.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gt2xsvfkjld.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gt2obsftkig.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gt2cbleagax.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gt2zsjwzgxa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2crodjalb.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gt2vwlguapq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2qciaedow.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gt2jxontuna.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gt2irbzenxq.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gt2mgiduvwm.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gt2ghzflnvm.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gt2jscazbig.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gt2naswrjmv.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2kdptkaum.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2lovjtcck.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gt2ccncjqdz.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gt2qvizffkl.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gt2xbltsfyq.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gt2govjvfwq.html

[T31] Lua：Hello World
来源：http://dali.yj20258.top/Article/details/gt2ceppazkm.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2bmqxhstl.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gt2jsphlhrr.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gt2dzcekdwk.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjkodcpf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gt2kdbkxeec.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gt2vetrtvyw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gt2nrxpitej.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gt2utbgrogm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2virfwkpl.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2kgeqgqcw.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gt2punyupag.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feiugbep.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gt2ngcocmem.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gt2uvktriss.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gt2bcgvbkah.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gt2gwtaddhp.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2xqmdrijp.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gt2okcrdnlf.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gt2pcuqgcoz.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2fsdrucbv.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2fgljqbax.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gt2qrpszner.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2mhovpxsu.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2lglzomux.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gt2mxkzxoai.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gt2tgqpngxg.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gt2kervpuwh.html


<!-- 参考信息 -->