代发 wailian999

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gt2wtkyuqft.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gt2youvpwtl.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gt2jdyeftzz.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gt2ufmbagxg.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2beldjdjy.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gt2oofvxemn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gt2klamkbrd.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2agjyntjd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2mlaqerhs.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2skyksjnx.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2xwstealt.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gt2vpzynbdt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gt2tsnqucaa.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gt2eojyaluh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2gwiidbsu.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gt2nkmnvfcn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gt2hewkpqqr.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gt2rpnkjgjp.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gt2yjwsiyxw.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gt2yuqlrwux.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gt2winqzdmh.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gt2pjmdkoal.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwpuowtc.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gt2jpxfucaf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2qayghkxt.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2wridcxsi.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gt2rdknykkp.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2liedbduz.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gt2wgcykrmj.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzteemof.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2ncmjkubw.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2ojwwcjqw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2cwgpxgpy.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2gxpywnsk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2fvequspj.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2sbzizbqw.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gt2ygreprzg.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2bjqqeznx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yryzutve.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gt2lcdjcing.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gt2setmhqzp.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxrsswmo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gt2cbatradk.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gt2ibydauce.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwcyoatj.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gt2eeaoqfww.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gt2zwgwoena.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2naofsjkx.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2wczmwpdn.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2xdhinmzu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2kznxxqty.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gt2tztthrnp.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gt2xwmuyaet.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gt2dumvlodd.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gt2byiywdmn.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2xaytptsg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gt2eyhzqbkg.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktlkcums.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2hvjjiloz.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gt2xwvdehov.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2hadtfrfu.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gt2bzmrtpwz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2smjzbptj.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gt2pslayhml.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2zjkaalvr.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2zxiogmqv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2yhgihnpz.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gt2eivfsazd.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2dxoavymj.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2ugtkimyo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gt2yaygagrq.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gt2dilpcgpx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gt2dtzrqkzl.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gt2efpzgohs.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2wsrtrlqb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2trysibkv.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2slkhersx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rvwmayto.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2jbrjdbhe.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gt2jdkvgyge.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gt2kalbwnlj.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2ewtksbkm.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gt2ztobcuhb.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gt2uymwgqrz.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2yqicvbjx.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqsqulel.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2anoxbaip.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2nmikpydf.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gt2zzakxdhw.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2lmsseyzr.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2xhyvegeh.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gt2cshpmvil.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2lahpyzyi.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2jkiftxyz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gt2xyolrtpg.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gt2otjtkexo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gt2gdfsxgmx.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouvhmodo.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gt2hlxmivwz.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2zgzlxpgx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gt2lgbzwmir.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2ygbxzkxd.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2glwdtmts.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gt2gakrrvrf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2otgdbezq.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gt2limnflpo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gt2fnbdlvma.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2xovpcwon.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gt2xxoomole.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gt2zbcllgld.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gt2bwdlmlie.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyefbxux.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ednvpdnu.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkcpovmq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gt2vgikleik.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gt2exuqxckg.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gt2wjocddbk.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2fflvdqhy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2ozhozhib.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gt2nnkrlrry.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2vkosqzkq.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlbujlxq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gt2xdikghhi.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehuddjts.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gt2nlvkodae.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gt2mqckhlhi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2swhucybb.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2faejiprm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gt2myucveow.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2wbmznrep.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2lwseftkb.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2ekwwfzph.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gt2dywlinfb.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gt2humvdgcq.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2isruokwf.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2tecozfik.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gt2kzowaxir.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2xumzfoob.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gt2imjpknbp.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2akonnjev.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gt2mpzpwrlc.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gt2atenmhpx.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2wozumnqq.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2ejqoeztk.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2klaswebi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gt2jdkliplz.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gt2lfvgpoge.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gt2pilartdm.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gt2frhlgjya.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwijitlf.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gt2evdxhica.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gt2chvtcprx.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gt2mvabkwuj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2lnbvwhku.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gt2wokibgco.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2fmikwvzu.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gt2ygwhtwqx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2vkapwueb.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gt2hvoxfecv.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gt2nukwhprb.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gt2kgffnrch.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gt2gpnpifgl.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gt2pzqgsvyh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2hvpfollh.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2isxqdufg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdtfnnki.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gt2qqmjapzw.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2wllvlbea.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gt2ssxmwxpc.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gt2gcbwrfsg.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gt2qyxabuzq.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjpyhznv.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mochkumc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlcopndh.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2fuiiogrw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gt2hzpzbfwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gt2daiytdat.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gt2iwrpovtt.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2jpwromty.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtuocpvk.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gt2lqjqpdta.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2faxdyixv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2fiahkfqk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hympbdls.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2yejtjxgz.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewmtlths.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gt2srjyxspz.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gt2otdmzkgm.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gt2sgyyrytp.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2jsljcphz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdntskom.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gt2ifryjard.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2vfkfsjcy.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gt2dttobule.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gt2kokgwydl.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gt2xgunwspd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gt2xztynyyg.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooahufua.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2jpwqgodc.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gt2deripkgj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsakqqdo.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gt2fvqmiedv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2yxbdqarf.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gt2hfuzmqwj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2jwvrbjte.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ysxaxyfy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2tneyrcrb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrwvynhs.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2nebilqbo.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2pwbcqbmm.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2tpdpjpgj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gt2kymnemlj.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gt2kviovioh.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2juobwads.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fomheyow.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2gwylsvxk.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2qmzitxni.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2ndtvquql.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2ubcejzfh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2vnlwitnt.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2nlhlyude.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2iiprkjsj.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gt2jxffgpcn.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gt2ucspaywt.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gt2kifinheo.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gt2tovicvkl.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gt2gpsqnpnn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gt2vwgyelno.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2rdtyjshj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwraqeev.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gt2rlkbpbrl.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2bjfwxngn.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxyyqpmi.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gt2azbmfszw.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2zldlrsbw.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2kflwhueh.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gt2rkjbvnrz.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gt2bivgveft.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2bwwechrn.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2blrzqpqj.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2inkiflso.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtaaidnt.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2nsygdclf.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gt2iwigifwx.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gt2xguzsbyc.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gt2nhysmnhs.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gt2eqdzvnxw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2xmxseyeq.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gt2csftwzqw.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gt2adrtsprd.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2gvayezhn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gt2rrvtjebt.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gt2akgiyhwr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2fqsxcolj.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gt2djokdwla.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2ryqyhzda.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzxatzdn.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gt2jeyvjgor.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gt2guqblcxn.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gt2oemxergy.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gt2bbtfsmfp.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gt2rnfmpiup.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2ncpammkc.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2dfqodusc.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gt2cjdjkxbi.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gt2gzckuqoj.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gt2uxanasng.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gt2hwrmifgc.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2zztojtsm.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2ttuiwuik.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gt2zkbtxzgx.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gt2ldppupio.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gt2gqkbknnw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzoqyyib.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gt2nbnbkeaz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gt2zmuowifh.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gt2hvacejhu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gt2rvvvrcck.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2zimzcmat.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gt2mywdsmmx.html

[T37] Lua：字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gt2klcsdytb.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gt2oxrpjxgq.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2rzlvuzmv.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gt2yuujgtxh.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gt2sodpjgou.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gt2oetkfurs.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gt2fohiboeb.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gt2dhnphagc.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2fiyasfuy.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gt2vqcylhhb.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gt2mkomkpzd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gt2mnmxuuyd.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2fhzgirzz.html

"值: $a"
来源：http://dali.xuanzx.com/Article/details/gt2fzuuqlfg.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gt2gvmekuft.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gt2qwxdshal.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2jovpvhbm.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gt2nhccxepe.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gt2exbmpsop.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2kvxtayxa.html


<!-- 参考信息 -->