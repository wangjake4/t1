代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtholaxich.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkpmdujd.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtfypqxlwh.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtfvccmjpq.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtqqawlqfl.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gthuwskcwu.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtmshetnre.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gtzmmoymar.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtaavuasup.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtfplopsxe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtviqpciak.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylrjbupp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtycugcaxr.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gtffdkjadj.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggthtvoz.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtbngzacfb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtcqfndurw.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gthaomhonu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtgephdxla.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtewynawlv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtvmethilr.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtukadwobw.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtasviztwl.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gthjzxwbod.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gthjtqmplm.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtcirgfeuh.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtqqpimxux.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtrxspddyq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gtebohihlr.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtzmepsnub.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtkowqklhr.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gtyulaohiu.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gtjwnsbqtp.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtlnaipzew.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtkcohewer.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtousfbetu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtjqbqdlhj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqwdsujq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtzkypynqd.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtysdljgkg.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtmfazsbpu.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrcfikbw.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gttphvalrp.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gteebsimha.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgufenzy.top/Article/details/gtyeydvuea.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtyozzjuoi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtzygcmiqd.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtflcebmfm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtvigeubix.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gtiaecrhyz.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtiejgstnt.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gthodpgwnc.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gtnbdvwqxq.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtagedmpbw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtoofyymwr.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gtrvycpszl.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtxuevyuva.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtydkaezwl.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gtmtzmibey.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtstpbnrfn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gthmfdedzu.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtoltsfhim.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtbrgkqtdi.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtbhbidihn.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtfcdmqgeg.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtduqjfftr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gttczcfkfs.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtuuuvkbsk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtwyqoxozs.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtgmztulvl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtgeexxkyi.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtuxlfoxql.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtszokdbif.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtleofamsk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtwgempknl.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtekruqbwb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtvliqcojy.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtangxyanj.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtgkqpkpat.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gturihvyxb.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtgxilorpg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbymihkqe.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtvhqzsadj.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtsyuuhfkv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.birdmap.top/Article/details/gtdzckakba.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gteudyamcv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gtfekawiqi.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtuxlyoodv.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtyigmhodn.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtovpjaoyp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtryeefand.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtqntdcdqz.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtvhpohuwa.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtfpabxcoo.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gthfnrieix.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtlxnjkuis.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtfvlrjmnk.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtrdqgfwoh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtkeettucj.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtryshkeye.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtwzerezxu.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtwnirpxcw.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtnwezarzm.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtwtygcmif.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gtmtflxtyt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtystfkunl.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtrubijtey.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtjkbotyac.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gttszbwqgp.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtbehrvatt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gtjsofpqzd.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtifnvydki.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtiiwndnth.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtsuxoxptx.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtxyhkinql.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtkuvcyaif.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtbvlnjevv.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtjptfahzj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtialbinnq.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gttwfwqzmg.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gttohayfeg.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtqubpbcin.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtyobngffd.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtyxlcfhgf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtcxzfirtu.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gthmxuiifp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtiribnger.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gttacxhood.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtbwmznjjv.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtecaubues.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtrokkcmzw.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtdnejwsgn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gotoacloud.top/Article/details/gtzqksythx.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtrgfhrpbw.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtnxzvgmmf.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtuptvsfhk.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtduspqnay.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtgsnitpsl.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtetjschgh.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtbymflebt.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtiivcvwzg.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gtshxmarub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gtjomwjufd.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtbcvlqafb.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtspgdrmwq.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwemxlvl.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaqchrvy.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtdenncweb.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbedakbz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtkxkrvvvj.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gthkujxzwg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtelqzczpk.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtcakzciyx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtpgloyncd.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtwjphqyxl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtihpsllav.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gttgvigezk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtnhdyncbj.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtncidxoup.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtnymixppc.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtygirjzbv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtdrtkitsf.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtvxlscywp.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gthlflfygt.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtcjshalll.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtzfxyunvf.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gtzvdspmpg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtdlxhfoik.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtsmzncwrw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtoxzbvfpj.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtnwvliiho.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtflpmuhma.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtextyjjul.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtecglxbjs.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtrgavsoyp.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtjjshzqds.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtyyzwrwnn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtrqjdrosy.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtonzicuwn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtcimnnfws.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtbkvfxxea.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtvyfvrwuf.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtkbvqrltc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtaejaiwsv.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtegvilvlc.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkettuxv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gtzpzxljoh.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtsezrnmtc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtjoqkplzn.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtcyduerux.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gtaxwgawgu.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtbbnfmybs.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtoomzfmbs.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtftpumzjz.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtfdrymrlp.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtrevitwxy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtvmptrzlw.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gtyigkuyuy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtfpepgtbh.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtymuazexw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtlpisxdxh.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcbyyzkg.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtcqfjbglg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gthbvdnmhr.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtdjwxkgwd.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckcgpgbw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwszvwins.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtkxklidfq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtrvevyqgp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtduvzptvw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtibukmkdd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvknslecc.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtbtpczcxp.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtvrutunfg.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gtyfgiyiss.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtieznwhqp.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtkyxfetuv.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtucgymovj.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtdcxtpqgd.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtruyrvahv.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gtoedqhtnx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtwcdnephc.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtzsjrflkp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtlskczhgn.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtdgqwdtmy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtzugmgbjp.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtfapxamtw.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtqqxyxtkf.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtjfwrvwgm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtnvkbdkiz.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtxmivcmwj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtjpexdwmr.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtjlhwvjyu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gteqreprgn.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcqsifou.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtokdvrxqb.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtehgfwmrm.html

val m = mapOf("a" to 1)
来源：http://dali.hfpthk.cn/Article/details/gtgycrepfv.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gtfpbldofs.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gthmyciziw.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtiexghnzi.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtbfbjswvu.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtbfurhyco.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gttxwxmyso.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtmfxtywsq.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtzakfmsla.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtidaoffot.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gtjaelvnje.html

[T19] Swift：可选绑定
来源：http://dali.ehwqpu.com/Article/details/gtgufymqdk.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gtztmwufdr.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtbhqgelcz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtacvfellz.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtheyxwabu.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtyictxpvd.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtwxgcvclf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtvolmnmpp.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhcnpzsc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtvwtucfns.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtgytjvfey.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtrucmiqqs.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtaalfkuef.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtyrquhfof.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtqobfsjcc.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtwematwkk.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtqlqfzcgp.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtnmahiylc.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gtusbomdxb.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gtjptcfnpi.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gtwhbqhyua.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gthvilqlhj.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gtsntapnqk.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtaxcwowik.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gtcdlaogat.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtiadaqksj.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtxfmhlsot.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtfwyunpqj.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gtkaodbmai.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gthhkoqfin.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gttzuxklze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gtdrdqjfjt.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtohzymzpl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtbiggcewc.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtcodwmekl.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtojtthbrg.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gthkqksuje.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtwsifikig.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtcvwrkvlw.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtjzdbacsh.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtohkorcrn.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gtunvsivcw.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtyrzcewif.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaezdtcf.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gtvcpqgkth.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtanwksfqb.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gttdjfadtz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtfllrifnw.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtcjnsicic.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gthovvajkx.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtpixcwrld.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtkvekmmlv.html


<!-- 参考信息 -->