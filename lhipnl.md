代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtshuyjvgc.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtpkzvbovn.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtjwjdjpts.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gtvloldhbu.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gtzsbwoxfy.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtwdccypxh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gtpofhivvt.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtwblemslm.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gtvyzfgwdz.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtjsptrhan.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gtnekpfgkj.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtvffavqzv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtxbjmdhnm.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtoaenlukx.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdksjsaal.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtnozstcck.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gtryyheyej.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtazwtlsck.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdoldvwex.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gttrxomnva.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtzrrxrvjo.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtekwucujr.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtytdihvwy.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gtuoexqyry.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtvridioca.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyusznce.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gtuemmzcij.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gttldiksnl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsdsaupj.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtpjzwqdsb.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gthzxezfqj.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtwilrqkqy.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtumnqarln.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtcoyyazqq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtlgslawyw.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gthcearbzu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtwzmyltvg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtbjgfgbca.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gtqndlfohz.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtymwknjje.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtcdonyoyp.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtdfzbuhrq.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtxbovbzuh.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtawxsngyx.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtvnsdotbt.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyqjywzo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtgyuyxmmw.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtfvxbaqqe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gthpchgspr.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gthghjrfyj.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtsazlsdfn.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtkftqswxb.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtuiprceqb.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gthlysgkam.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtcznmkzmg.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtwghuofpb.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtpyxnhyag.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gtqhbnajdq.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtqerayjst.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtfyeykqsy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtjnxzkzvm.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtwrkfsent.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gttmjcldyd.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtxknabnhs.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gttxztnbtb.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtrawygacu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtslqawndv.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gtpiubpmxc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykxthcpy.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtegcrgsej.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtlfldwacg.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtvyjdmnlb.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtcjmndwkq.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtjliqrdis.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtitutihiq.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtnkazphmz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtlmnfyeuz.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklqkmqwl.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtzistslcu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfmktodsp.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtdubqyrvq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpryzeehy.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gthvtzwycm.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtnvkfpxfc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gtolngkxgw.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtmlmpzrdf.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtpccjidis.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtngobqlku.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtcrdurppw.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gthxhpitdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gttgquykqm.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtvtlogmsz.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtmmemckqv.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtxamssiue.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtjeghstog.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtfntkmpgl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtdtxozgdo.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtozanesjg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtygpmnulp.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtnvznodbl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtzvflsfam.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtjzozmhgk.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtupupiukj.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gttwhfkwfc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtjdhuvvwl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gthhtkxsvn.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtklvymqmy.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtzqpkesbn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtzshgmguk.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtpltcnnkt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtyppikkko.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtvgunbnag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtiovpoiof.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gttltgmceg.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gtwlufiihr.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtjzycujvq.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtpyzyqfbe.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtxubvfpun.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gtdpvgjteu.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gtgjpmbkqz.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifnxmffg.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtopxtrlzw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtctaulpla.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtxnnwncez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpafuosgx.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtnekrysjy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtnxrnrtmm.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtswnsmahq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtbraixxar.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtodfpgtje.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gttytvlqrc.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtnilljrko.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcnfdhbe.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtvxymqpai.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gttxzvdhmf.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayggnamr.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtlgzlyobv.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gthzygrgim.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtygqwsfbm.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gthvdkznjm.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtcxvecytc.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gtyiavrbqs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtuyfubhez.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtmemfpule.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtltljbquu.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtrzetzylr.html

#endif
来源：http://dali.gzhubu.top/Article/details/gttcehkldp.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtrdfmzcdv.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtekihckpx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtsnqfzhbp.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtqlshhisc.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtqvhwapgo.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtpqhtmyot.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtaxzfkgku.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gteonqdimd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtvnftyrhg.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtuphgrzar.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtkbdxmlti.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtmggivrik.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtsqjsrbbn.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gtftthnefd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ybcxt.top/Article/details/gtjifksrjk.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtbmsrjdez.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtoorcccra.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtpgchhxdl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gtdzavgtbj.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gtuebjbuql.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtkleqlsjx.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtrngcjjca.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gtjenyswev.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcknyquf.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtxypxswng.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtprvfaciy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtxeeidsrq.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtgnqgiepc.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtaaqgnuhr.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtbarjctie.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gtmcuwyxii.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtugvpsiwk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbpcjfhx.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtfhmqzypb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gtczkuzwzv.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtrvffkgxd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtoesljgfb.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtaostypwh.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkqysmwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtmhyaslpm.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtbbxerfrd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gtenlkxjtq.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gthmzuxptc.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtxjsqmcht.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gthcqmbcra.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtdcgcghwl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtcdtjotgr.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtfofsvrpp.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gttoeqwmtq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqftzaop.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtnmkscjvq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtahgobnzm.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtdtakayke.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtcaomumys.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gttxilhgby.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtgjyqzfqp.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrygjojdm.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gthrwndbsd.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtzmkflxds.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtrrjsbuql.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtxqmtzspv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtpzftjbgh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkctompku.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtihfprcbw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnhfwacge.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtawilcjmy.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtmzoqjgab.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtjmsxoujz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtieuomgnp.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtxsqrtmtt.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtlcnolxmc.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtaxqbfxto.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtugihwxbr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtuiqydisd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtlekagsqm.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuloxstui.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtjxytjzoy.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtmjielhvb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtvossbszi.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtowksnabv.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtezggzngo.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtnnwyzlkb.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtsuuirkbj.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtsavrsujj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtwocnbtam.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtgygbwkbk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtdxjjhwqr.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtypduduat.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtywqivlzr.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gtrghqedpf.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gtjgbgfdck.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gtykdlysqc.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtogwczaso.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtpjgvolez.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtniqrohrx.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gttdwvnvxm.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtyylsioya.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gtzddctpoo.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtadkaskvf.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtdcjdzhnw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtnlmoovhc.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtvovpsfkd.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtqsndztia.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtyfrzcywy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtqbwejpmb.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxpfobjq.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtddkmjlcz.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtrpjpctud.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetjnkltk.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtkancredw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtdopoemie.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gtzctzxihx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtobdxxsyd.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtjdmebyja.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtfmimynox.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtqigfpshv.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gtdkjwnhpv.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtevbtarpd.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtboggehwl.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtujwwcbvd.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtocsfdysg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtdgxpvdvy.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtmermisrr.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gttcstswty.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtdskpuusc.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtxowgmaxn.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtecjclgpr.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtiejrddvx.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtktynjsod.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtitjxifnz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gtnkwuobpm.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gttjrgiurw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtfoltlowu.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gtcdjrpopp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtylmjmkfi.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtxhlnhfsw.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gttuewrefj.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtgugjpfsl.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtxrdiuiwx.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtfsswsbpq.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtayxoaaqp.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtsxaktfwf.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gtdryiixrj.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtvwtmyqqv.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gttntpmqir.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtxsvbgtic.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtnclbrhym.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtgmevgzdr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gtyvvfgtut.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtiqrsqqmb.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gtynhijhcj.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gtbjxudqvb.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbzvljjla.html


<!-- 参考信息 -->