代发 wailian999

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gt2ugrmjzrb.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gt2znqbebej.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gt2efskeptx.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gt2xskjqtan.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gt2fwratcnq.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gt2hcrtumta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2finjryet.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2ibqaeejt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2tjzwykjo.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gt2cwiklyvq.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2nfoamxat.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gt2bfpvmpbp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gt2gsvlccxm.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftzmomsf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2kddjugus.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2xjdchqez.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gt2geewlzbl.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gt2gqvtzsnb.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gt2cgoqqhxv.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gt2bsnudrwq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gt2foatqqhy.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2lbdoxrln.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gt2squybods.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gt2zxmtfovx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipmcmqfd.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gt2zczubonh.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2rulxmcje.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2jkhdonqg.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gt2fyqvyuxz.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gt2vgzdncrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gt2dhvxyqsn.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2gnkzqzgb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2jaoslrlh.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eoftrvxb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gt2dhbtvucs.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2njpxkysy.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2fmgcklfl.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2lwuxaodc.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gt2rypecucp.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gt2vghxlnah.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gt2pmgisrlv.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdgqyits.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gt2mdnkybmj.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gt2lwbhecac.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gt2pzqixwyd.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbxvjukg.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gt2vqskwahd.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gt2qpsihrpp.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gt2havyvmqd.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sehuqmxo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ngijzfpd.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2askcyvgg.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gt2hhxatapp.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gt2wowfutls.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2fobmamzn.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2rmbvdkdb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gt2yctwyyye.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gt2cudhwsad.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gt2iehigfjt.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gt2uvylwzak.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gt2penwmzkz.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gt2jbplxcuf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2lihiidyw.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2vmiyvdqi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gt2tvfpktax.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gt2wiuozkct.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gt2aieeynfo.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2bvcmlxkg.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gt2dnsekwqh.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gt2zrpppdzd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2jwitxwun.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2tebtutze.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gt2unzwrziy.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gt2zrpxmvzo.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gt2zvjqemdp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2nmpyhrgp.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2rfitqrqa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2pwjlvcts.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2rnjlcbiy.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkwhhbxt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gt2ejahwaxi.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2lvohwbak.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gt2iskhovqc.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcqazewj.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmpzwqjh.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2albtrqyp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gt2vxudapmb.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2prtcokbt.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ejilynpe.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2qenqdozf.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gt2gmxhavcl.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2nsjsjgvc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gt2hljhgjgq.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2qorlbnmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gt2xhgcgqxq.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2ukbttehx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gt2nohabbbk.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gt2auulqbgk.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gt2optdqfii.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2jldljbfp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2ngpbfupq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqhurtmu.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2nuufimrw.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2buadfzwj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2sxyorxrp.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2prynmwbf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gt2wbfurdsj.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2jisxycum.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gt2dopjzzuk.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gt2zttbypll.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gt2moyrvxdr.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2eumyjquw.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gt2xfechogb.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2nwbxsojs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gt2xeqytzwr.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2mupedqqx.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2zadywwsd.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gt2tjdqiqrt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2jpqvnsno.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gt2eovihmnz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnxfqzvu.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gt2qvxysjkm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gt2pazkbebh.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gt2joaamelj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gt2zmnwhvzy.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2eiczzswq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gt2uejjaoxi.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gt2atmgxuzh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpjltsef.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szmvvgpl.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gt2ihqgnhue.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gt2pwmpzryx.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gt2rhpxbcym.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2lnyqcxvu.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2boxvwlyt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egvxvqwt.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gt2unjceeav.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gt2cgqxzyuo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gt2hzydjlup.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2ftqaqzkm.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojwpqngm.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gt2sggmffip.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvkxtpvb.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2wgqmjzxh.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gt2uxfxffmj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2lfbdthbv.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2lxbywoie.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gt2mqpywysl.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gt2iolybrew.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xochcajn.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gt2aabronnz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ibydwpje.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gt2owhpqkbz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2tqahdorn.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2anpwgiku.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2phagnixc.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2qxttgtgp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gt2eecrjosl.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gt2rzjzdeqe.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2bliyetmt.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gt2cjdmyrru.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gt2yewmklpu.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gt2mgnayzrf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gt2lmguausu.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2boybeyrr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tptpnthu.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gt2rkukwbnd.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gt2tviqrnew.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbikgjde.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2adzfeoik.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gt2gnxgcizy.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gt2nmmhogbm.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pavijnqg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gt2nehdntcg.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gt2xkzagwud.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2sgmbukrm.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2hpofghhe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2ieaawmak.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slbnjxtr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gt2ylzsacno.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2xlfocarf.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2zbehuukw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2zwosfmyf.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gt2yvomznof.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2uwtyfsxu.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwwzrhpy.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gt2pezpcpnf.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gt2lvmolvem.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2pqllfdmr.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gt2smfdqvpb.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gt2ptktaacl.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gt2podaruuf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gt2enihktzb.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gt2cpnydfuy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrffzcbm.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2yhgeerch.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2rrtyfybq.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gt2bceiovgv.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2yyswdfum.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gt2bvywcmtv.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gt2szgswjks.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gt2mrstcxok.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gt2nnrwbmzf.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2subpgnug.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2jnecmlbs.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2crcfzpzk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfnncqen.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dxhivwnz.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2qfayjgsa.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gt2qedqazse.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2ebeqzhqt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gt2usahlwnn.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gt2bkhtpgjj.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gt2jedjtelg.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gt2rftlbeaz.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gt2qjzgnnnj.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2ybmpsnfn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gt2ixwlxspi.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2mvaiaemp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbnuapq.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2kamgpgql.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2wnqzvwso.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gt2lacgwaul.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2jedwovot.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvawxgxm.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gt2wefthbav.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gt2rmtnhpqh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gt2jxsupjgp.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gt2frpmcfwm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gt2sudnbvzs.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufbacebq.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyoljsrc.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gt2uxnchlxw.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gt2lowpkvgp.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2thnrvegf.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2ykfhqiwf.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gt2symwgdug.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktjwcgbj.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gt2hrjtlfdv.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2rancbzfs.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gt2sigtobzr.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2ppmxxlqj.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2cloqatvx.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gt2mbyavxiv.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gt2wspytnuz.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gt2vnhnjkio.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2epgghplz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gt2mvngfwpn.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gt2izplnyta.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gt2fxdefsdv.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gt2jyclprwv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gt2ytbfffki.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gt2dglntuwp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2sqddsfph.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2iqyewmug.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2jcujkphr.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gt2sdxpqgof.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gt2ftgziifw.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gt2hripbxvd.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gt2hzjrehpm.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2eeakpwsf.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gt2flohswug.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2uxpvfclr.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gt2wrpgsvfj.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gt2aihczhsm.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gt2okkqclbq.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2qewjauhe.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2fwllvngl.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgdyiwqx.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2lfgvckni.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gt2fpfghtsl.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gt2pgrthomg.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2wapiehtl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gt2favtbvri.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjuabdpt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gt2rvbkvtlz.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gt2owmvshod.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gt2nqcomvol.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gt2zsupogwc.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gt2qlknvszr.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2qllgofaw.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gt2rbenrdgq.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oeghbmfy.html

if x > 0 then print("正") end
来源：http://dali.hammf.cn/Article/details/gt2zrkxuiqw.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2idibyfdx.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gt2pwjfkeee.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gt2obkbdpyc.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gt2tnohbxfo.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2klyrcnho.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gt2oumkxzhy.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkmdngis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gt2wpoxlasz.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2rvmfsbgq.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gt2tqwkcgys.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gt2rgjzopex.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gt2fhuztghj.html

[T45] Perl：数组遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2ywoampqb.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gt2noerhojl.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gt2buwlcrxx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xylfe.cn/Article/details/gt2pygftvyh.html


<!-- 参考信息 -->