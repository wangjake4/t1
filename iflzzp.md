代发 wailian999

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrxtkzaf.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gt2wmejfodl.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2qiygcand.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2dxszrjzl.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gt2eqkxeyjn.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gt2xoebmnwr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2immyhbki.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2xmoqshxu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gt2nmxtdadu.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gt2iiacrjnk.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2edjazmll.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gt2sdijtuvh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gt2ioasblzw.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gt2rcbqezvp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2wvrxdhck.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2tjexrlqy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gt2aomigyna.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2gaxxncnv.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2xrsyvzzf.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gt2ipzfwzni.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2rnxwvacz.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfdfqlwf.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gt2mnfuhoqi.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gt2sqdjpyuu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gt2dlddjtkn.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gt2jznvzhyy.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gt2wexxdyyq.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gt2wvgcjklz.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gt2zbtwtrjp.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gt2itrtvrxa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gt2cjbxgcey.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2ymwkhsws.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2rotxiiyx.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gt2lhvcqoqr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhwyldbm.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gt2kpyvynmi.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gt2ucipoeju.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2mfmwotnz.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2magjqvkb.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gt2omrccnck.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gt2nactkvub.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gt2cdjzeixb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gt2bynbqtwk.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gt2jwgywxhr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gt2gcmmkkdh.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2woeirsty.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gt2xvodxggo.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gt2slbmbrkr.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gt2zwypumjs.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gt2pptmjubs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gt2ivlplfss.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gt2tnuovmgv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gt2libycara.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gt2zpmqdtda.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gt2xmikence.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2tqjhphiv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2fgiyyjdx.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gt2qrcignxk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpcawujd.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gt2yczeihkp.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gt2ipesnvkw.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orzgjzji.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gt2vrxqnwxk.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2aeqlhwoc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gt2vdhjgogo.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awkiwtah.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2tsfpwnym.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gt2vsngttwa.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2mpglxcrh.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eabslmgz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gt2jlzwsall.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gt2vxjlewkq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2pghkmtcs.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gt2alszrzvj.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gt2zfplivps.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2fxznzept.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gt2ifzeuuhl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2vpkbujar.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxkzrvr.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2nswaglgk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gt2yiaplmrj.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwvqijxq.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2myzitgin.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2aoehqkxd.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gt2wstufxsi.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gt2testqvli.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gt2bskfmzif.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2agbwlibj.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gt2otuqaisx.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2caqntkfl.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2lwzhcgjr.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxnwktdm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjzhhcou.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2xwjnekdw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gt2sqappkje.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gt2ocxckaam.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gt2qenhjchl.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfijpfjv.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2eeyttqfk.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2scjdxgrm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gt2rskmbrbp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2lnruwvzv.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2oqfdbrfv.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2jbolkvbv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2vckrwkfm.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gt2nkslbspd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2xmyxnbie.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gt2kazdpejx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gt2foevtiql.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gt2umvxpmmq.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gt2ssnqkypy.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gt2lfsjqzaw.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2nrfypgqr.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2mowzlnpc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2hrkwhnxu.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2hecrskht.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gt2qkozduou.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2myjjkptg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2uahzfdbf.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gt2ghgnndij.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2rzushojd.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2pfpdadnz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2qqscmemv.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gt2bfrjmgrt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gt2mblarfhm.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gt2jakhpoda.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2goaqssnf.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gt2ehxvidot.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2xwfeswyj.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gt2xgxkbcvl.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gt2thksuktx.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gt2xhvzcnkb.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gt2vutmgant.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2nepswdkz.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2kwpflyfu.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gt2bbxlesqr.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wattgcte.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2wnxxfffa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gt2gusmkqgy.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gt2znjmgqbr.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gt2oictihrp.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2oxwairui.html

#endif
来源：http://dali.wangdashe.top/Article/details/gt2baaekfla.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2ckafxevc.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gt2ptzutlrh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2kdafyeny.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gt2jnllutfm.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gt2tcygbeqf.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2mahrwbjq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2loraqaqe.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gt2jghgthac.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gt2xukhpdry.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gt2fkvjvgxt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2atqlqfdi.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpsgomnx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmydmtyq.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2qqnxmwsb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2vutasurd.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gt2xnzkljmu.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvgnnvso.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdelqlr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2jdklyuhz.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gt2yjkorxfh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2ktvtfxbi.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gt2pxwooxif.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2xbngvglm.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gt2jdujfcgx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gt2wihheeqy.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gt2pemljmmr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gt2rkszyfti.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gt2yllatxuq.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywtonrhp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwiorta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gt2bbodafvc.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gt2otyaijrg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gt2pnopvote.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gt2fosbpzya.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2lgxzrhsk.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zveytilr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzxjpgx.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evozigyz.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2lollscll.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gt2jsqwvspt.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2qdtgjvyx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2bmwjvotg.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gt2eabiogiy.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gt2bnxfoyya.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gt2kmunjdzh.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wkecrlgo.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gt2irkfoiil.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gt2euqswfls.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhcdqji.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gt2awveinqo.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gt2cvhbpspy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gt2uofmasqm.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2okyjolxn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2npjwoyua.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gt2qeevagtj.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2cuamudkq.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gt2zqlciyuh.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2tfwzvnjn.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gt2btsoiqaz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxsfztly.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2izwewues.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gt2obaocoms.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2sfxhamjm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2vuarioon.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fppqcxdo.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2dmmbbbgd.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2adtjwnmr.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gt2xqhedzic.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gt2cpnobxum.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svqdacgw.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2auqwecfy.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygvjpzdc.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2fngjllzi.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gt2laoouzhk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gt2veionsiv.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gt2ysmktbet.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2nlpxveaq.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2pnsckoyu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gt2leawugcj.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2oejxybjc.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vixnkszx.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gt2tedwidvy.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gt2exejaonq.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2hzfdeeru.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqekfazk.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gt2osnejblq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gt2vtmuzmhl.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gt2xdvkbhuy.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2nbovfsmn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gt2zafrevmx.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2bucoetie.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gt2cmoofasd.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhdraipp.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gt2vbdzdpfk.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gt2whzcnojf.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2ujezprza.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2jlxzudld.html

[T17] Swift：变量与常量
来源：http://dali.jinqigufen.top/Article/details/gt2alhaubzv.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2gzlrfcpb.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2lulxvsej.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gt2ryrjshqe.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2taazqtph.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gt2elqhmqkz.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2xnzdfpyc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fseskmxt.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gt2qfdzgcty.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2lxydbkyk.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gt2treikdqp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gt2ordonhbw.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gt2zarlodof.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gt2alydeqjk.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gt2sxniifgc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2dqehlnac.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gt2obtlfchc.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2znuxityz.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2hyfgychz.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gt2sqayfptg.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emsvqfbx.html

do { try f() } catch { print(error) }
来源：http://dali.ppjwa.cn/Article/details/gt2qbusvjxa.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2cyvayulc.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkuejksg.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2yhvsdqea.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gt2xmcxensw.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gt2bxjyyexc.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gt2bkrlcwmc.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2izxlmvtg.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2rypkturd.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2pljuawrx.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2eahsdeiu.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gt2lelbcdai.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gt2zyiwgham.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2doeomkav.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gt2spwcifey.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gt2jcoqpnyv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2kpoznoos.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gt2mpclivmp.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gt2vsvwdkll.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2rhadlemy.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gt2doqinqvh.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gt2wadxnyba.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gt2ztecjzdi.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2qhvtvbve.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2fvtulwec.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gt2weumitqw.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbrxkhdp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eimusluh.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gt2gmamzqcb.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gt2unippifp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gt2ljsuliba.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2zhlqpvmx.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viczsccm.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2rdfyqybk.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bllhmvga.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gt2bhgxhttc.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2gyltbnxl.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gt2fiodaapr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2ssvsqrmz.html


<!-- 参考信息 -->