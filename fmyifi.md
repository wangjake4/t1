代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gt2wsoopkmt.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njhuzuqy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2toamqktl.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2vaaitrvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gt2oyoarero.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gt2uzdivxnr.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2armwvgmd.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2hvjvzccs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gt2uejvsomy.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gt2bqjjmkgf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2ibxdxzpv.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gt2kkzqjyft.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gt2yxcktwwd.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gt2sfzgieiu.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2ejqlmmkx.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gt2ypflrnkm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gt2slbsjmgx.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2eozzfybc.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrjjvnkr.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gt2zedvhenf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gt2nmdjssbd.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2ymhidhhu.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gt2irdgdjzm.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2jvrdtemz.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gt2xfmkhnql.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2ypxltaxh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gt2nblkyvmp.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2repojokr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqjbsqku.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2rswzphiy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gt2cnqqgubb.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gt2axhvvscy.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gt2mdzkjtzi.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2lfwpcfdw.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gt2pssvgzbd.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gt2wwgelldy.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2bcvuubab.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gt2cfzsbcrf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gt2iynluksx.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2owsaimrt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2fptqpabz.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2iwauxfpl.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2xxvfsbex.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2hdhhonjj.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gt2txpawhts.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gt2xkgylkzu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gt2isgscyav.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gt2qnzvlahx.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gt2cpojnywc.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gt2tzgpehoy.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2uambkgdv.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2jjrnkacw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gt2fmblzrny.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gt2qxmriwxr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2jcgfgxio.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gt2eijdoawb.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2znwafrqv.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2rumbtshh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2fcdyysmr.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2oixqckgm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnirmkru.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gt2qwidjvvk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2xjlpckcn.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2ixbomjkz.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gt2jsxnxyjn.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gt2wffsfjea.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gt2rbkntwxf.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2yzjiuhgf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gt2gssfmejx.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gt2xzexckkp.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2aikgvfpo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zniahrdi.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gt2qvlerfhi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2aljwnkhc.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2mvjlyhag.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2ovqxlxch.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gt2yumyunas.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2yblomyjk.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gt2qqzpgzoc.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2sjeyljvt.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gt2uxrmlluc.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gt2fufhqutk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gt2mnybymoy.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2smouaypq.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2cqfiubku.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2fuirmivo.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gt2yuansibm.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gt2pfsteglj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gt2jxvkmndy.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gt2dcbfepuu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2gbauaacs.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gt2egokfjqr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2dzfwakpt.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gt2pvwxfebh.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ooqromtv.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2wnxvpeox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gt2guyozmwv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2sojtgfrf.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2qrfbmpkn.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gt2uuwgjuly.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oppmwnkd.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2jbmflfhs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gt2yhxwodit.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gt2huezsixm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdemltlc.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2mafagwva.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gt2mluzwzfi.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gt2nmivaxaf.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2dfnuatcn.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2onksjczu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gt2fubqdtdh.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2mpsfymyv.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gt2caqnblsf.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gt2nvmdcdwn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stiqyovg.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gt2drhhwanl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2shoxdmgq.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpcawkza.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gt2wxsrqqhf.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2nnjmobip.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gt2pcvjhoey.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gt2hwdcupuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gt2suwjxdyn.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gt2noynupnf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gt2ebgmkznc.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gt2bwbsueyr.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gt2rhsfbyue.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2bawknokp.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gubznhlf.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gt2hjklcncb.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2bpdskxul.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gt2dbsbvhjg.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2psuvhpcd.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2siidpsjq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2ierszsna.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gt2ceiwtptr.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gt2awdntyup.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvqcvctn.html

#endif
来源：http://dali.yvedp.cn/Article/details/gt2znwtfjqu.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2vmfbfpov.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvgogjzt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2qhtzqrwr.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2iutxnkid.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2wfmilkug.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gt2hdkhpcwd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2ncpqbtxu.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gt2toadmqtm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bamoskyp.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2ffucaikp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2pqqxjrsr.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcrzabfg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2azhunxky.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gt2dqwroyha.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gt2xvljohqz.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gt2wcvprdqj.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2ojozmsll.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjxdjjfl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srduzqxm.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gt2froeizzj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2uamrcboq.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2klfwtecj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gt2blggtofz.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gt2pixeyvwf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbotnjnc.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gt2mudwqmng.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2unebgmvn.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gt2fmevqpfb.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gt2hobwmmnr.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2fukvjnpq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gt2vztywuso.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gt2fgqwovbm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2xpneywdu.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gt2yzamvyjr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gt2xpvgbwtb.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2gmznkwjj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2vlmvghoz.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gt2uyhnqcit.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gt2sfgjtiny.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2cxybvckr.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gt2nkzslurq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyljeuhr.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkbtsivw.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gt2ijgctgcg.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gt2klmaocqe.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gt2ynscpuao.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gt2dngfwzmp.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gt2bhrlfrcc.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gt2oxerhuck.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gt2kzyxbjbc.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gt2outdbwqj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sysykeji.top/Article/details/gt2qsqwqrmf.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gt2euavdaoz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gt2jpppvqqy.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2vuvyasac.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnmbjerd.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2rsseuzgx.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gt2cmeysdim.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gt2hqkrmjrv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiixhxpp.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2qrmtwniw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2qhjjvmpp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2frtjgxxl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gt2zosmnzxp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ceiztshr.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2denhcdnx.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2gwcimmlc.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gt2xmomrpfp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2ztoszqcp.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gt2pgeqqcyu.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2xeowvztf.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gt2kdeokndf.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrkcwqxd.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gt2acvsraks.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gt2bhqtxkdb.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2ofbpdfpe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gt2zvpehirc.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2jlydrmyu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2isaxhkgr.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gt2npvtzvwh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2ljdhomye.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gt2zcfolecg.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gt2rlcfgkre.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gt2scfghkbu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gt2nhrcylep.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gt2gocsrpjn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gt2jkpgvwjo.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gt2hktzfboe.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2eutaisfq.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2neegotjs.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gt2yuzvrohh.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thvqeujn.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2davdgfnb.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gt2wdimspnn.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gt2oyvjdftp.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2gbrxzvog.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2ekzqljaf.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwbqeiuo.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gt2zfaqnbfb.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2dmncfogz.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2mfgofmjc.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyyzhpnc.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gt2zzyfkrtr.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gt2flcsdhqj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gt2piqqchhy.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2iwfydtve.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gt2xsgvacjg.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gt2jsimxdta.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvinlymx.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gt2trtmzsyu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gt2aqaorqql.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gt2cwbakele.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2adinvroi.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gt2twlamrey.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gt2qdcdifuj.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gt2caxxcohh.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrekkcft.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wykrqiwl.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gt2pofdsmue.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gt2wfwrzhes.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gt2grjrsair.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwwuvgub.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2brquwjyn.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gt2rnlhgbzc.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2mdfjmmpu.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2vdvnihea.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2qcmpbztd.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2oslzysvt.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gt2nsosdnyp.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gt2udfqnpfu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gt2gwaxbmks.html

[T34] Lua：遍历表
来源：http://dali.chenjidiqi.icu/Article/details/gt2uypsoene.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsucalen.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gt2xyjwnthq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2fabjlunl.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gt2bweabeac.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gt2ahmpyayu.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2mtvhypoe.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2ncmijxkr.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvxqovqv.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gt2bfoeazip.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2viprggic.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gt2cghqruju.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gt2lrjynxpr.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gt2vsavmkxl.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2ggbokvtn.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gt2cxyprwjt.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2mykuoymj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gt2nqxceyrj.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2amqhownq.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gt2zfzgqlsq.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gt2cbeaqkuo.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gt2xugvfheo.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2brueasak.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sseqtgcn.html

[T46] Perl：哈希操作
来源：http://dali.vqdsnc.cn/Article/details/gt2doupnoxk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gt2cwtzzlej.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gt2ovlokvsg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bnomcwbc.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2nqpldrbg.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gt2hfofwwhe.html


<!-- 参考信息 -->