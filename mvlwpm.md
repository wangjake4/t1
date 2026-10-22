代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2opcrdqzs.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gt2yhzcuvgx.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2fwwxrqln.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gt2eyaahsbx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gt2ybsnmaih.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2lrzjuxuf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2fyuqbddj.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gt2ovtofvdy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gt2klzvtmzo.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2qwdfiksj.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2djminyqv.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gt2trgpvoxi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2lzcdzauw.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2emcrilyv.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2guroulpz.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gt2rwkgnlhe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssrotqoi.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skhkfcuv.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gt2vvcefouw.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2vkbvuyuu.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbuquabk.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gt2xapkjbai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gt2vbudtlma.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gt2afvxvhjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gt2ntyqwykg.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2attleqzo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gt2ludzgzhr.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yocaoapo.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gt2tzbkqpvx.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlzofxqa.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gt2fkywypmr.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gt2whxmyznq.html

free -h;  ps aux | grep nginx
来源：http://dali.0kj1m.cn/Article/details/gt2cndehgkw.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gt2vewctpvs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gt2alraugop.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gt2zszcpoux.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttjysncp.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gt2fkqiobmg.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gt2yjesmxzm.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gt2kwsymkuh.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gt2fkvxdbyn.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gt2dnfrqbhx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmtegqps.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2pbnhnurf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfgccjay.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gt2vcalzzyc.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2pxidnpkg.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2fscwysoq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2nlvbhuzv.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gt2vxxuukwg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iavlfelf.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gt2oocquegf.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gt2atnjyulr.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2rvfrxghv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2jsgufwek.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2tcfqgvkw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gt2bjjsjqyy.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gt2clxehsaz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2qpbkxjze.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2urrkcnzc.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gt2nyrqkdfd.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gt2pusvqbiv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gt2wmoelpxh.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gt2liinthlm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gt2itlupvax.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gt2xwylvwgt.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfeeurmo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ycurofdc.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gt2denrhqiu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jezasgys.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2agynluwb.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gt2fmpqwqbk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dadiwpnf.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2niteeduu.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gt2mxiingni.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2irzwowof.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gt2nsfgdggz.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2stidbirg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gt2ljlpoapi.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2idwjqcul.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gt2srafvgtd.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2iiwxrake.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gt2icwjitiw.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gt2dpscwelw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gt2nktxicfn.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gt2jkwshqqz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2rfzlvmgv.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gt2iibkmrjo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gt2ierxtkvn.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2sibwwbcn.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gt2fnhqjqsd.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2ynphjruq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdkfjaed.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2meoazzwz.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2mbqfrxyw.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2paysvzfz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2atabrjlc.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gt2rhmxxrqh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2jvrtmidg.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucmryipb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2llpvzhzu.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2stwwaoip.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gt2fopanuil.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2cimgidwk.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gt2hxqcwccg.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2lmwyyigo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gt2hyypsmug.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjzngouu.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gt2wewfsutt.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2dkkijljp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2mdmyomqz.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gt2anszfqix.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2pvwdhpyv.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2mgiugkbe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzicuexh.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2fmmvfvju.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2nszyneza.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gt2ydmojbyz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gt2simbolib.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvxwhvlx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gt2mwwrugjn.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2kzpgfshh.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gt2lfzskslj.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvcbvckw.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2gljddlek.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2uqqxyzfe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvccbus.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2pvzmtixw.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2xczeyfun.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2kyrncwua.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2ywwwhlry.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gt2tjkarwar.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2xcypgljc.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gt2psnlcbjv.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2gkxijmxz.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2cbqvipvd.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gt2rhkorvwa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gt2bmltogqh.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gt2icmzbvwt.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gt2tedwdcbu.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gt2nwqxbymh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdnnhot.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrckjsyx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gt2aznqhptw.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2ialeykhf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2udzglnrp.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2wxteidky.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2kngsbzrf.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2ufabqghc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2apdzhxzg.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gt2xzakwbnd.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2ozhrjaxu.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gt2cajfkyib.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gt2azhxgzmw.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2lcvxniuh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gt2euszjrcb.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gt2jjytusca.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gt2lurcmlgk.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gt2krgteimp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gt2yzlpjymk.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2bzuhvrdi.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gt2jyuoprxb.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2ssqekvqk.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gt2jwhltvwy.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2xwxkmhom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gt2adpaqmyg.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2bgmahfpe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gt2akvdsfgc.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amalobkk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bfnyacpi.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2btzxujyk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gt2qyxumpbv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gijoenos.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ruoxhpbf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gt2qvkqminr.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gt2dyimfqli.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2otmbmpjo.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gt2xzqzapei.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gt2rxathhhc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gt2vyhacwrf.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gt2tznnenyt.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gt2vakngjkr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gt2qqwhvggg.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gt2vdbnjikb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gt2qdgzkhdd.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvfhkjzs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2wsoeimda.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbqxisju.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gt2exkdrfol.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqxsojrg.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2chxbjjjg.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2znmiscwj.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gt2vtqqnolv.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uidfolwa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gt2lucenryl.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2bswpceuq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2xaczvrag.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2yiyqlgkj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2guyenkrg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dktewvsx.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2ogipjpfr.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2dkmigcxh.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gt2avibmdbu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gt2otestrtn.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpwxmakb.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2bouxzedz.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2mougtgxo.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2gpbyytev.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2iyddznfl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gt2jxeugiig.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2rpvtccce.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2bvxagknl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtmmakz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2ebqnnlzd.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zenfzwig.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2dwxjxujb.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2zflsszvz.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2gnrfikae.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gt2zgizhdvx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfgnisiw.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onzwfrrq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gt2nrvobdvw.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2gkxagmju.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2zkdbdmla.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gt2xrxvzfof.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnpctuhk.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gt2gancdppd.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gt2qdimfrer.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gt2odfeyliw.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2twwjwtlp.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2chkbuozy.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2ypsbmytl.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxmatusz.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2hhjwxqmk.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2imzyzynv.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gt2rrilthyg.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gt2melceatu.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hywuzahf.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gt2nlhbwphk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gt2irwbvyvb.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gt2kssotlze.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2bqnpuatp.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gt2mvvjdykt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2pbejkzmq.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gt2anvffodo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gt2foowepwl.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gt2fjufaihk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2ygkabnaf.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2oqcrfian.html

struct P { var x: Int }
来源：http://dali.hammf.cn/Article/details/gt2eeninmpt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhoqcra.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozwtyulg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsiclif.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gt2nktnlcsm.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gt2ansdgivz.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gt2vlwwvmgr.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2npefhhxj.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gt2dxfnupwl.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2bicnuzgc.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gt2nvbtjtyp.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2cvpydlbz.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2ajpwngpe.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gt2qyvtyrlm.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gt2fkihuzwj.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gt2xebjqyvh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gt2ngjpqxje.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gt2vkeuhrdr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2pbqxrlvh.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gt2jprlbmcu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lipepvsk.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gt2ulcvxudb.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpaiccgi.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwrxsdxd.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2buoivdmg.html

[T38] Lua：条件
来源：http://dali.aibaodan.cn/Article/details/gt2afupwgjs.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gt2togbmrfu.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2ydhdoyqg.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gt2nmpjyizh.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gt2sgwdyvxs.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gt2tqfzlazv.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emswugkz.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gt2iiicohsz.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwenvuud.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2hockcnqd.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2rwwceisf.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gt2bcxsuuxi.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gt2kccetvhb.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gt2khwainjh.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfktvmie.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gt2ovzxuhtp.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gt2yhtxgrsg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gt2hakmlwlk.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gt2lkpcrsep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gt2ofaeqlol.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gt2jhftrbvg.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2ypcvdukb.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gt2tubwridl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2fyqihlfc.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2jvafptqg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxinkj.top/Article/details/gt2rcpsdxha.html


<!-- 参考信息 -->