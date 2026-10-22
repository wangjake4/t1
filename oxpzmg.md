代发 wailian999

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtijjmyene.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gthdohzptd.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtsnrovpxr.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtzzeonboi.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtafhtyccv.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtwrugatuu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtsvkgmahj.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtmmbdvjpu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtquwsrxlb.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtghmdapuu.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtjuhjpaba.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtbmusicht.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtnebgsuna.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtgyspmkpd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtorqqzbet.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtfmitarhp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtwykizzpe.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gtpecuonbv.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gtmodctmbu.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtfaphbkze.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gtuzolfckm.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtuhhffizo.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtscidktem.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkbltstq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtrpfbxnlv.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtnroepsay.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtoizbmjzo.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gtchigokin.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtcrdvcgtt.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtavkktldb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtyqlxfuzp.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtkvjzvqin.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfijsiyo.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtocgavats.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtmetsfwlg.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gternuqfwb.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtygfqirmp.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gtzzecpvdn.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtesmhqymf.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtqexbqrjw.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtivengsan.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gtoubgegog.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gtixaldnyv.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtwxyesumy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtesjrjmhm.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeqnbwat.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gtfnydwvdg.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gteudokthh.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtnxeibawa.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtchagwegb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtkocrtoet.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtrctvfdbw.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gtxtwayldq.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtgesadqtv.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtlvcauzdx.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtmdysoxzb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtcsimxvsu.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtjsuxvpqo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtrrbnwpnk.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gticrmtxff.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gttxfqpmev.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtywfzmcxa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtyssoxeue.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtjuflfkga.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtmsjsqzew.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtihbzsltv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrzbdzxe.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtnqdfhaaj.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtxahmacvs.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtilnyunrt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gtbopetxsn.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtloqhmnvz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtnofmkjfc.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtkazwgsjd.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gttrsrcvfg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtolqxrsrl.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtrrwwgtmh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvwrcwcwo.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtuilrjhob.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gtolzeqyab.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtjfhrclfb.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtjikiorqx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtaeeftosl.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtiiwgnrft.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtuwdrxkph.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gtwyszmvxd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtvardvekj.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtluyqpsgd.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtyhryqctg.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtxvtowlys.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtlblixdwy.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtnpqayzrx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtvhtlfiat.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtcsgkuqiy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtbrhkkknt.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gtqqxqhlck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gtxhqdtzdy.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtyhkjugap.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtvfqmqodp.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtqoosdmjo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gtgbomhmrt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtahthznjv.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtuvvywvzs.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtfgkhkhgq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtxyhwasaf.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtmrkgzvrm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtyhrdsxya.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtwmztspbx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtrqeyieox.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtjzufqgfy.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gttxftqnis.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtkjyeypzq.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtgvsekjpw.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtlqjnnxeq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtgpqdsyxc.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtkqjeupxi.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gthsnxinqy.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtnobajlar.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtasbgallv.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtrimtilqe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtxwbevlct.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtcthcrkwk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtlhwlmjyt.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtcbkmmrcb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtxfagqhou.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtnxsvvhne.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtuhhzhmjm.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtbtepfibz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gtpqvrdizf.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtxiokhiok.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtuhqwvdqh.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gtblzyatrs.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtuznybcnr.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtvlrmkpox.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtbgyvaksr.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gthrxtjkhn.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtjseogdnu.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gtkyafgbze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtzpxcqerh.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gtersuodbo.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtvpamwbwy.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtbypabfdo.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtyqrjekol.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtmznitvnf.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtsqbpqvpp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtfffwbnmd.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gttgoorpmp.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtvorrsxvv.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtzahamjiw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtakrqbjqe.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtgezxtaft.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtalmonkan.html

[S35] C++：map
来源：http://dali.hnxiangtu.top/Article/details/gtamwfzpvd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtggjwobyj.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtpnuddowd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtyhdzhmvh.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtemydeegr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtrfxtwopf.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gttinqjrgt.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtfpznyudx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gttnsxfgmt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtxcdskxni.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtgiqmgbmg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gthxmvjchj.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtkdusfadp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtnwzfxitx.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtcwujskyy.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtagzrisye.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtukigoudd.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtaryrtshd.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtjbpdwcur.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvntqoelt.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gtgwlcjhab.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtjpajxqwb.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtvbwymgsp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtmpxerqhd.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtoechzpnr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtiqmbnnnj.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtbrciytkq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtjmgrdmbg.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gttlxbkdys.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtjiyycwcw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtukitymqn.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtpwbujjos.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtjnbguibh.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtxxetttln.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtiuxzgzvj.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtfkjgonyy.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtzweuugls.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtkakojies.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtxekwzuwg.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtxhhrdxgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtnerkpggs.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtekafvqml.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gtapewpkzu.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtyfpjugft.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtjkihvjca.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtzaypqbne.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqnrsjiw.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtxrtlfbee.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gthwodqhuj.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtvlauycco.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtwqqrnsfb.html

[S60] C++：遍历并删除元素
来源：http://dali.cashguo.top/Article/details/gtgnoaftes.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnhqmnaw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtadkyzhid.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtihnuembw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsixplqux.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtmhhdcoen.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtifsqkwwp.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvzdndoz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtpxbnkkpi.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtrmcsrdoa.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtciwbrpal.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gtoudcmyvx.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtyrtqyzfv.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtzrjjweul.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtrskukkko.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtykpbtdhw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtqmxpdxqk.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtvpxsoisu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtasatwrjw.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtsfszqery.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtqiwufnpo.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gttikgnilz.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gttgoeqmqy.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtyqqddxgt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtcwasiopi.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gtxdwahlmq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtodpsvrkf.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gtuslmslcy.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtbrdcdddr.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtdvmitziz.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtqtmdvfur.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gtieichbqx.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtbfxfuxxj.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtzexnixyx.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtdizbxwly.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtxiivyskz.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtgvabvjmh.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtrarpqphn.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gtvsfvdpzp.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgmyxytm.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtfcaaavej.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtdumxhgfe.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gtnxanysch.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtslqhcdeg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtqylnpcmq.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gtxibeywbu.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtlknoyjnd.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtbyjhqhbp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtdpnytvfh.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtgqqycqjs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gttpdeoiip.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtmecakfwr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtzadkjnrk.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtuojdjyyg.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtqkmbkipz.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gtjoeorjqk.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gticfxsyzt.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtxnncdqrn.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtoavqqraf.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtgozyifbj.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtmypvqntp.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtrqmnjsnt.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtvyggitdo.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtvfkjhefp.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtcqwdjlde.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gthzshvado.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtqkefqoou.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gtholgosao.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gtgktdkjma.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gttxnrkyqf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtmxbakcco.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtcwoqkqqr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtzufntlun.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gtopissthd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtcmwzecig.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gtycumedin.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gttjyioyhx.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtsxepamjr.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtqdwkmxds.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoffzwwa.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gtjupiadpu.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtjtnymich.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtfjsusybd.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtxjysapmz.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gtlkqpfvxw.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtohlgklqc.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtampyfuup.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtgockskld.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtlehcedwa.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtmxqcwwet.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gtzcajcwwq.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gtffjupwtk.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gttjmwwkrj.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtnuqnrnqy.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtuqceoxtq.html

[T46] Perl：哈希操作
来源：http://dali.gzhubu.top/Article/details/gtwuvqwkoc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxdwoizg.html


<!-- 参考信息 -->