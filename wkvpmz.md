代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2jiuzgpjc.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gt2wxfuyfpp.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2kndaxznv.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gt2nwyupkpd.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gt2gjrfymwe.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgjnpren.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2wllchtud.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gt2wnscmebo.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gt2ggvxzljx.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gt2ocktptym.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gt2yazwhdlq.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gt2uxqrslif.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2ntzicpfp.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gt2lfdrnqwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2vphgtgee.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2ncwrqgdq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gt2ybheqrhn.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gt2uthemivl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2azrtanqb.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gt2eticoplp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gt2wudbkotp.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gt2aojnvuhw.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2tnlbczcx.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gt2jcqtmoou.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gt2vcrhfbty.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gt2vrfkeuax.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2oawbnpro.html

[R55] 压缩与解压
来源：http://dali.quarkkingdee.top/Article/details/gt2bvjsbevp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2dchdzqhx.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gt2wrwyxvyk.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gt2xkhwxjpd.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gt2qipcruat.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gt2jmgtgkeb.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gt2jacjftaw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gt2jiugqhvf.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2ilfggwls.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gt2czwrdhad.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2wiiqleqo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2jgarvfoi.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gt2seachkct.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gt2fkuobkgb.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldehesci.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gt2ussvyyfn.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gt2zpcjbbnh.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gt2budmxlus.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2lfrsdirm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2wkfwyncc.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2bzjrxyxf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gt2eyqzblcr.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbweehvc.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytyjcxbn.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2qezbkjhb.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gt2eliykgjb.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gt2rueiedme.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2guwirwin.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gt2xbbjbapi.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhhjylxz.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gt2xermpmlz.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gt2owlxkhiz.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2aduplifb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gt2okhmmnrp.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2bbdhkcxx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2tvfxulcu.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gt2ipppapcd.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gt2kfcatmnx.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzrasryb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2sabjxjxu.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2cnwasoil.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2rduysztd.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2xaegfkch.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2bezwnsqu.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2qyifwzvs.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2tkqqearm.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gt2pgatxaoh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gt2poccbhtt.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gt2cakrqwmr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gt2wjdbzzdq.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gt2opfcwvya.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gt2xugsghog.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2kaxqerml.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2zhzfvrph.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2yebkiidg.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2xlmgkykp.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlavaukt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2mueofgmw.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2vhvvsghu.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gt2ccjgzbaz.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gt2epaveeph.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gt2zsvorkwr.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxylnnxe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gt2qpnvqtbx.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2rxxfhwzo.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2webdxbzb.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2asizqzpb.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gt2urdrcxki.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2xqexdiwf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gt2eqqnxhxb.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2gisxcayp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gt2slwonykq.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2zukraxma.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2desazmpu.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gt2ioshxoyf.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2kihuxecb.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2mfmnbfec.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2iuaeqtew.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gt2fprgchry.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2kefurgvd.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edkdscbk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2nskovqmf.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gt2kzgupcyf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gt2yyvwxwzw.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gt2iznbczne.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sztefaxu.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2scytkuki.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gt2zcptbuny.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxpnjlev.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gt2nriplvzd.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvronvbj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gt2cojhbrot.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2jyjoarvs.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bktctjrh.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gt2djjoroga.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2gtejhotg.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gt2lpplohwt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2xlfjpuib.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2nmlmstuu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2tugxlklw.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2akxziwoq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gt2nvcnzufx.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2dzzzhqje.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2uhhctlwl.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaihoirc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gotoacloud.top/Article/details/gt2bdduhrgl.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gt2sunoeyow.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2aunvahuy.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gt2cmziwkih.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gt2ryxrohxz.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gt2zrcvqkah.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2sujbmvco.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gt2kylvfshr.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gt2fmndqdme.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gt2kghjjgcz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldampyvo.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gt2rrlboyoa.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gt2emjiklxr.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gt2udlzqbkl.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gt2dqqyhzwh.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2ymnqxhgc.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2lptoiavg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gt2xwkdimpc.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gt2gshhpkel.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigfzy.top/Article/details/gt2xvsystcs.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gt2fkjlybhj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gt2xcbzgbtv.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgtvaebu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2uaarleca.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gt2gthpmley.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2lctcbrbe.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gt2nusiqqmk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2pgitscwe.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gt2jlmdfnsp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2dxjigbre.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcjhsdsn.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gt2bpjulprm.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2scnplkyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gt2ehlneewn.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipztkioy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gt2yxzazlqn.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2iacryqmu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gt2hxjuelyd.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gt2nzasepgk.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gt2ybnrjhxi.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gt2vofxsbxx.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2ntqhzyfj.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcuvlfzn.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gt2jjpqpgve.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gt2bnoxzppj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gt2nxycncus.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gt2frwnuibh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2cesvquyf.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gt2eczsinwr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvltvwub.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2ebwvucai.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2urblgpbw.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzmjqmck.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2kifzcctx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2cnfnobva.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gt2bfdtswat.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2yepqmwoh.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2olosyrip.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2iodcslix.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gt2agsaviej.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igbxedtu.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gt2gtcsyohv.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gt2nrfeevgb.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gt2kqfholmk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gt2paeqvhbb.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eipehlba.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2amrkofzu.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gt2tthsryqv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gt2skjwtybk.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gt2efctnmqk.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2mlsimqbi.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehpuntjk.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gt2mtacnppu.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gt2npqinehj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gt2itocgdka.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2bptccibf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2jytretxa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2qtbzoxrg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2mfcifjjt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jqvdxbqh.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gt2wqpcynzz.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2jkltwzgv.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gt2bgzxdfoh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gt2aipexuid.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gt2vcaahdpm.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gt2wgpsbaxq.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgilgixn.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gt2gaqvijdt.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2luclyeos.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gt2noizbewe.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gt2ouinmisw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2totjkkxe.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2jvrxpzhk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gt2xmmmpzmx.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2yfjrsaln.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2hkrxmvhu.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gt2qzwgsfbz.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gt2kmzlffjw.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2grbvwjop.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2micwtsse.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gt2znzbmfut.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gt2hmbjlvap.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2jwtghglj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2bxmzxytn.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gt2zoghwxkz.html

val m = mapOf("a" to 1)
来源：http://dali.hfpthk.cn/Article/details/gt2lvzbmeuf.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gt2bkgdpwlb.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2ekbkczct.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gt2owmmyeub.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gt2naukwbpg.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2vgukbytk.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gt2lytjghib.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gt2pfyrbjay.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqmmnaep.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2jcxwhkwt.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2ilzrhlff.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gt2xdbjcrou.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gt2tsxzwelt.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gt2xiajzmdz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2qjzievar.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gt2sbibtosk.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2kpoeajkj.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gt2cemzdqvt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gt2vwjkfjar.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gt2pjcnucgu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2otkfxely.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gt2dusdsjnj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjwujhk.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gt2fmyhctch.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gt2qbqbwoya.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gt2bzhznwun.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gt2fuqhdzgl.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gt2fbsqlqcv.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhniulws.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gt2rcyfgurm.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2nwzdqczr.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gt2eazcksjp.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pagvtckh.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gt2dboxmfpx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahlewitq.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2uyymhyng.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2pdyzqtdv.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gt2pvwhypuv.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2aiwuitak.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gt2hplrsemg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gt2drdzsxmh.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gt2bdqvzvqe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gt2ykeoikqx.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gt2mvbtjtcn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2zmujsfdr.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gt2rqeqqgij.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwssrjil.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2mqbzhgyv.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gt2lkjbcxou.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gt2ofmozhby.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gt2exovlpqh.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbpgepgg.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gt2vuyafmce.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gt2nhlkbsjm.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gt2mjecbhyd.html

[T41] Perl：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2elpemszi.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tedemdvk.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gt2kkqbfhad.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gt2wqwpsujg.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2xsbekabm.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gt2aatjbwqu.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gt2ekawvojb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xbvtblrk.html


<!-- 参考信息 -->